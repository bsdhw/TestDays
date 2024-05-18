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

Total: 248

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| PC Engines    | APU                         | [7fbd1ae00c](https://bsd-hardware.info/?probe=7fbd1ae00c) | Apr 28, 2024 |
| IceWhale T... | ZimaBoard 832 ZMB           | [9dfb20c904](https://bsd-hardware.info/?probe=9dfb20c904) | Apr 23, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [a2cbe8253b](https://bsd-hardware.info/?probe=a2cbe8253b) | Apr 09, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [3ccdd0084b](https://bsd-hardware.info/?probe=3ccdd0084b) | Apr 05, 2024 |
| Unknown       | Unknown                     | [f6ead7640d](https://bsd-hardware.info/?probe=f6ead7640d) | Mar 30, 2024 |
| Unknown       | Unknown                     | [28feb266fd](https://bsd-hardware.info/?probe=28feb266fd) | Mar 24, 2024 |
| ASUSTek       | Pro B660M-C D4              | [dea6d03494](https://bsd-hardware.info/?probe=dea6d03494) | Mar 24, 2024 |
| Intel         | D53427RKE G87971-403        | [5cf0576fee](https://bsd-hardware.info/?probe=5cf0576fee) | Mar 23, 2024 |
| HP            | ProLiant MicroServer        | [c158a70e91](https://bsd-hardware.info/?probe=c158a70e91) | Mar 22, 2024 |
| PC Engines    | APU2                        | [1f2d9aef5b](https://bsd-hardware.info/?probe=1f2d9aef5b) | Mar 22, 2024 |
| Sun           | SUNW,Ultra-1                | [33ed69952b](https://bsd-hardware.info/?probe=33ed69952b) | Mar 17, 2024 |
| Unknown       | Unknown                     | [07a7ed8dde](https://bsd-hardware.info/?probe=07a7ed8dde) | Mar 15, 2024 |
| Dell          | 0T7D40 A01                  | [5b8f4fe788](https://bsd-hardware.info/?probe=5b8f4fe788) | Mar 14, 2024 |
| IceWhale T... | ZimaBoard 832 ZMB           | [8f4dfa8bb2](https://bsd-hardware.info/?probe=8f4dfa8bb2) | Mar 10, 2024 |
| Unknown       | Unknown                     | [a10048c3e7](https://bsd-hardware.info/?probe=a10048c3e7) | Mar 01, 2024 |
| Intel         | QHSW02                      | [11ee14ed87](https://bsd-hardware.info/?probe=11ee14ed87) | Feb 26, 2024 |
| Shuttle       | XH610                       | [e7780e6013](https://bsd-hardware.info/?probe=e7780e6013) | Feb 26, 2024 |
| Shuttle       | XH610                       | [dc854cc185](https://bsd-hardware.info/?probe=dc854cc185) | Feb 25, 2024 |
| Dell          | 0T7D40 A01                  | [151b04e792](https://bsd-hardware.info/?probe=151b04e792) | Feb 23, 2024 |
| Dell          | 0T7D40 A01                  | [7aeebe2c82](https://bsd-hardware.info/?probe=7aeebe2c82) | Feb 18, 2024 |
| Hardkernel    | ODROID-H2                   | [a4045617ec](https://bsd-hardware.info/?probe=a4045617ec) | Feb 14, 2024 |
| Unknown       | Unknown                     | [ef910cb303](https://bsd-hardware.info/?probe=ef910cb303) | Feb 14, 2024 |
| Shuttle       | FH170                       | [e7eaced298](https://bsd-hardware.info/?probe=e7eaced298) | Feb 13, 2024 |
| Unknown       | Unknown                     | [11b10e5acb](https://bsd-hardware.info/?probe=11b10e5acb) | Feb 06, 2024 |
| Unknown       | Unknown                     | [4437069c86](https://bsd-hardware.info/?probe=4437069c86) | Feb 05, 2024 |
| Dell          | 0T7D40 A01                  | [19ab947fb4](https://bsd-hardware.info/?probe=19ab947fb4) | Jan 29, 2024 |
| Unknown       | Unknown                     | [c28104b9b5](https://bsd-hardware.info/?probe=c28104b9b5) | Jan 28, 2024 |
| Supermicro    | X11SDV-8C-TP8F              | [17c3586ebc](https://bsd-hardware.info/?probe=17c3586ebc) | Jan 23, 2024 |
| Unknown       | Unknown                     | [0b0142d5dd](https://bsd-hardware.info/?probe=0b0142d5dd) | Jan 19, 2024 |
| PC Engines    | APU2                        | [189362d834](https://bsd-hardware.info/?probe=189362d834) | Jan 19, 2024 |
| MW            | GMLK-2_5G4L                 | [8707b73983](https://bsd-hardware.info/?probe=8707b73983) | Jan 08, 2024 |
| Unknown       | Unknown                     | [058859b9c4](https://bsd-hardware.info/?probe=058859b9c4) | Dec 26, 2023 |
| Lenovo        | 3708 SDK0J40700 WIN 3258... | [7ad0451a6f](https://bsd-hardware.info/?probe=7ad0451a6f) | Dec 25, 2023 |
| Intel         | Q3XXG4-P V1.0               | [80e8d502be](https://bsd-hardware.info/?probe=80e8d502be) | Dec 24, 2023 |
| PC Engines    | apu4                        | [48a0e27e11](https://bsd-hardware.info/?probe=48a0e27e11) | Dec 22, 2023 |
| Unknown       | SKYBAY                      | [7f8968ee0a](https://bsd-hardware.info/?probe=7f8968ee0a) | Dec 22, 2023 |
| Intel         | DH67BL AAG10189-207         | [e6210120bd](https://bsd-hardware.info/?probe=e6210120bd) | Dec 12, 2023 |
| Unknown       | Unknown                     | [be6c7879b4](https://bsd-hardware.info/?probe=be6c7879b4) | Dec 07, 2023 |
| Protectli     | FW4B                        | [dab9b84618](https://bsd-hardware.info/?probe=dab9b84618) | Dec 03, 2023 |
| Unknown       | SKYBAY                      | [e1a3d3ff53](https://bsd-hardware.info/?probe=e1a3d3ff53) | Nov 30, 2023 |
| Unknown       | SKYBAY                      | [6ceeb87719](https://bsd-hardware.info/?probe=6ceeb87719) | Nov 30, 2023 |
| Intel         | DH67BL AAG10189-207         | [734103b696](https://bsd-hardware.info/?probe=734103b696) | Nov 22, 2023 |
| CncTion       | N5105-4L B0                 | [6074d7118a](https://bsd-hardware.info/?probe=6074d7118a) | Nov 18, 2023 |
| CWWK          | CW-ADLN-6L                  | [0662bae41e](https://bsd-hardware.info/?probe=0662bae41e) | Nov 12, 2023 |
| Gigabyte      | H610M H DDR4                | [bdc4fdaf9c](https://bsd-hardware.info/?probe=bdc4fdaf9c) | Nov 05, 2023 |
| Fujitsu       | D3543-A1 S26361-D3543-A1... | [4b685d7ff1](https://bsd-hardware.info/?probe=4b685d7ff1) | Oct 14, 2023 |
| Gigabyte      | H610M H DDR4                | [ab5400f952](https://bsd-hardware.info/?probe=ab5400f952) | Oct 08, 2023 |
| Unknown       | Unknown                     | [13f17e09d4](https://bsd-hardware.info/?probe=13f17e09d4) | Oct 06, 2023 |
| Fujitsu       | D3543-A1 S26361-D3543-A1... | [5076395072](https://bsd-hardware.info/?probe=5076395072) | Oct 06, 2023 |
| PC Engines    | apu4                        | [20c432e07b](https://bsd-hardware.info/?probe=20c432e07b) | Oct 02, 2023 |
| ShenZhen M... | 3865U-6L                    | [53a70ddb3b](https://bsd-hardware.info/?probe=53a70ddb3b) | Oct 02, 2023 |
| Fujitsu       | D3543-A1 S26361-D3543-A1... | [8809e169a1](https://bsd-hardware.info/?probe=8809e169a1) | Sep 30, 2023 |
| Unknown       | Unknown                     | [20fb7f1ba8](https://bsd-hardware.info/?probe=20fb7f1ba8) | Sep 30, 2023 |
| Unknown       | Unknown                     | [7e82c0f66d](https://bsd-hardware.info/?probe=7e82c0f66d) | Sep 29, 2023 |
| MW            | GMLK-2_5G4L                 | [8ebba0ee37](https://bsd-hardware.info/?probe=8ebba0ee37) | Sep 19, 2023 |
| Hardkernel    | ODROID-H2                   | [35544a61bd](https://bsd-hardware.info/?probe=35544a61bd) | Sep 16, 2023 |
| Intel         | D2500CC AAG43156-303        | [281e4a541b](https://bsd-hardware.info/?probe=281e4a541b) | Aug 26, 2023 |
| Intel         | D2500CC AAG43156-303        | [c5745af495](https://bsd-hardware.info/?probe=c5745af495) | Aug 26, 2023 |
| IceWhale T... | ZimaBoard 832 ZMB           | [97321f0843](https://bsd-hardware.info/?probe=97321f0843) | Aug 20, 2023 |
| Fujitsu       | D3313-B1 S26361-D3313-B1    | [87bc92631a](https://bsd-hardware.info/?probe=87bc92631a) | Aug 16, 2023 |
| Fujitsu       | D3313-B1 S26361-D3313-B1    | [ec68697ed9](https://bsd-hardware.info/?probe=ec68697ed9) | Aug 16, 2023 |
| Hardkernel    | ODROID-H2                   | [a92e1efca1](https://bsd-hardware.info/?probe=a92e1efca1) | Aug 07, 2023 |
| Dell          | 0T7D40 A00                  | [e903094a75](https://bsd-hardware.info/?probe=e903094a75) | Aug 03, 2023 |
| ASRock        | J3355B-ITX                  | [234f0fd8aa](https://bsd-hardware.info/?probe=234f0fd8aa) | Aug 01, 2023 |
| IceWhale T... | ZimaBoard 832 ZMB           | [aeb59c510b](https://bsd-hardware.info/?probe=aeb59c510b) | Jul 26, 2023 |
| Dell          | 0T7D40 A00                  | [24e7268bbe](https://bsd-hardware.info/?probe=24e7268bbe) | Jul 19, 2023 |
| ASUSTek       | H110M-R                     | [cc5fe45365](https://bsd-hardware.info/?probe=cc5fe45365) | Jun 15, 2023 |
| ShenZhen M... | 3865U-6L                    | [5733ad3c03](https://bsd-hardware.info/?probe=5733ad3c03) | May 25, 2023 |
| Hardkernel    | ODROID-H2                   | [3966c4828d](https://bsd-hardware.info/?probe=3966c4828d) | May 12, 2023 |
| PC Engines    | apu4                        | [2589a0c02c](https://bsd-hardware.info/?probe=2589a0c02c) | May 10, 2023 |
| Gigabyte      | H81M-D2V                    | [5f9bbf2d15](https://bsd-hardware.info/?probe=5f9bbf2d15) | May 04, 2023 |
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
| Intel         | D2500CC AAG43156-303        | [d2d10a1ffc](https://bsd-hardware.info/?probe=d2d10a1ffc) | Jan 21, 2022 |
| Biostar       | N3050NH                     | [31e33326fa](https://bsd-hardware.info/?probe=31e33326fa) | Jan 06, 2022 |
| Gigabyte      | B150-HD3P-CF                | [9752eae10b](https://bsd-hardware.info/?probe=9752eae10b) | Jan 06, 2022 |
| Fujitsu       | D3164-C2 S26361-D3164-C2    | [765210be77](https://bsd-hardware.info/?probe=765210be77) | Dec 28, 2021 |
| Purism        | Librem Mini v2              | [528ef01c87](https://bsd-hardware.info/?probe=528ef01c87) | Dec 20, 2021 |
| HP            | 805D                        | [324b4670b6](https://bsd-hardware.info/?probe=324b4670b6) | Dec 12, 2021 |
| Unknown       | Unknown                     | [943365b2f1](https://bsd-hardware.info/?probe=943365b2f1) | Dec 11, 2021 |
| BESSTAR Te... | IB9                         | [26717d3708](https://bsd-hardware.info/?probe=26717d3708) | Dec 10, 2021 |
| HP            | 3397                        | [ac295c89b0](https://bsd-hardware.info/?probe=ac295c89b0) | Dec 05, 2021 |
| Protectli     | FW6E                        | [3ddd9d297c](https://bsd-hardware.info/?probe=3ddd9d297c) | Dec 02, 2021 |
| Intel         | D2500CC AAG43156-303        | [69194e4ead](https://bsd-hardware.info/?probe=69194e4ead) | Nov 23, 2021 |
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
| Intel         | D2500CC AAG43156-303        | [b77ceeed88](https://bsd-hardware.info/?probe=b77ceeed88) | May 14, 2021 |
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
| OPNsense 21.7.3  | 9        | 4.27%   |
| OPNsense 22.1.1  | 7        | 3.32%   |
| OPNsense 23.7.5  | 5        | 2.37%   |
| OPNsense 23.1.5  | 5        | 2.37%   |
| OPNsense 22.1    | 5        | 2.37%   |
| OPNsense 21.1.5  | 5        | 2.37%   |
| OPNsense 21.1.4  | 5        | 2.37%   |
| OPNsense 23.7.9  | 4        | 1.9%    |
| OPNsense 23.7.12 | 4        | 1.9%    |
| OPNsense 23.1.6  | 4        | 1.9%    |
| OPNsense 23.1    | 4        | 1.9%    |
| OPNsense 22.7.9  | 4        | 1.9%    |
| OPNsense 22.7.2  | 4        | 1.9%    |
| OPNsense 22.4.3  | 4        | 1.9%    |
| OPNsense 22.1.4  | 4        | 1.9%    |
| OPNsense 21.7.7  | 4        | 1.9%    |
| OPNsense 21.7.6  | 4        | 1.9%    |
| OPNsense 21.1.3  | 4        | 1.9%    |
| OPNsense 21.1    | 4        | 1.9%    |
| OpenBSD 6.8      | 4        | 1.9%    |
| FreeBSD 14.0-p5  | 4        | 1.9%    |
| OPNsense 24.1.4  | 3        | 1.42%   |
| OPNsense 24.1.2  | 3        | 1.42%   |
| OPNsense 24.1.1  | 3        | 1.42%   |
| OPNsense 23.7.8  | 3        | 1.42%   |
| OPNsense 23.7.10 | 3        | 1.42%   |
| OPNsense 23.1.11 | 3        | 1.42%   |
| OPNsense 22.7.11 | 3        | 1.42%   |
| OPNsense 22.7.10 | 3        | 1.42%   |
| OPNsense 22.1.9  | 3        | 1.42%   |
| OPNsense 22.1.7  | 3        | 1.42%   |
| OPNsense 22.1.10 | 3        | 1.42%   |
| OPNsense 21.1.8  | 3        | 1.42%   |
| OPNsense 21.1.2  | 3        | 1.42%   |
| OPNsense 24.1.6  | 2        | 0.95%   |
| OPNsense 24.1.3  | 2        | 0.95%   |
| OPNsense 24.1    | 2        | 0.95%   |
| OPNsense 23.7.4  | 2        | 0.95%   |
| OPNsense 23.7.1  | 2        | 0.95%   |
| OPNsense 23.7    | 2        | 0.95%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Desktops | Percent |
|-------------|----------|---------|
| OPNsense    | 124      | 84.93%  |
| FreeBSD     | 10       | 6.85%   |
| OpenBSD     | 8        | 5.48%   |
| TrueNAS     | 1        | 0.68%   |
| helloSystem | 1        | 0.68%   |
| GhostBSD    | 1        | 0.68%   |
| FreeNAS     | 1        | 0.68%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| amd64   | 144      | 98.63%  |
| sparc64 | 1        | 0.68%   |
| i386    | 1        | 0.68%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Console      | 136      | 91.28%  |
| helloDesktop | 4        | 2.68%   |
| KDE5         | 3        | 2.01%   |
| xinitrc      | 1        | 0.67%   |
| XFCE         | 1        | 0.67%   |
| wlroots      | 1        | 0.67%   |
| TWM          | 1        | 0.67%   |
| LXQt         | 1        | 0.67%   |
| fvwm         | 1        | 0.67%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 138      | 93.24%  |
| X11     | 9        | 6.08%   |
| Wayland | 1        | 0.68%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Console | 142      | 96.6%   |
| SDDM    | 3        | 2.04%   |
| SLiM    | 1        | 0.68%   |
| LightDM | 1        | 0.68%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 131      | 87.92%  |
| C       | 11       | 7.38%   |
| en_US   | 6        | 4.03%   |
| de_DE   | 1        | 0.67%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 129      | 88.36%  |
| BIOS | 17       | 11.64%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ufs     | 91       | 61.07%  |
| Zfs     | 48       | 32.21%  |
| Ffs     | 8        | 5.37%   |
| Cd9660  | 1        | 0.67%   |
| Unknown | 1        | 0.67%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 134      | 91.78%  |
| MBR     | 8        | 5.48%   |
| Unknown | 4        | 2.74%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                       | Desktops | Percent |
|----------------------------|----------|---------|
| Unknown                    | 26       | 17.81%  |
| PC Engines                 | 16       | 10.96%  |
| Intel                      | 9        | 6.16%   |
| Dell                       | 9        | 6.16%   |
| ASUSTek Computer           | 7        | 4.79%   |
| Shuttle                    | 6        | 4.11%   |
| Lenovo                     | 6        | 4.11%   |
| Gigabyte Technology        | 6        | 4.11%   |
| Fujitsu                    | 6        | 4.11%   |
| Deciso                     | 6        | 4.11%   |
| Hewlett-Packard            | 5        | 3.42%   |
| Protectli                  | 4        | 2.74%   |
| MW                         | 4        | 2.74%   |
| IceWhale Technology        | 4        | 2.74%   |
| BESSTAR Tech               | 4        | 2.74%   |
| ASRock                     | 4        | 2.74%   |
| Techvision                 | 2        | 1.37%   |
| Secudos                    | 2        | 1.37%   |
| MSI                        | 2        | 1.37%   |
| Hardkernel                 | 2        | 1.37%   |
| Biostar                    | 2        | 1.37%   |
| AAEON                      | 2        | 1.37%   |
| ZOTAC                      | 1        | 0.68%   |
| Winston Marriot            | 1        | 0.68%   |
| Supermicro                 | 1        | 0.68%   |
| Sun                        | 1        | 0.68%   |
| Silicom                    | 1        | 0.68%   |
| ShenZhen MinWin Technology | 1        | 0.68%   |
| SeeedStudio                | 1        | 0.68%   |
| Seeed Studio               | 1        | 0.68%   |
| Purism                     | 1        | 0.68%   |
| NEXCOM                     | 1        | 0.68%   |
| CWWK                       | 1        | 0.68%   |
| CncTion                    | 1        | 0.68%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                      | Desktops | Percent |
|-------------------------------------------|----------|---------|
| Unknown                                   | 29       | 19.86%  |
| PC Engines APU2                           | 8        | 5.48%   |
| PC Engines apu4                           | 7        | 4.79%   |
| Deciso Netboard A10 GEN2 Model G          | 6        | 4.11%   |
| MW GMLK-2_5G4L                            | 4        | 2.74%   |
| IceWhale ZimaBoard 832 ZMB                | 4        | 2.74%   |
| Protectli FW4B                            | 3        | 2.05%   |
| Intel Q3XXG4-P V1.0                       | 3        | 2.05%   |
| Techvision TVI7309X                       | 2        | 1.37%   |
| Shuttle DS10U                             | 2        | 1.37%   |
| Shuttle DH170                             | 2        | 1.37%   |
| Hardkernel ODROID-H2                      | 2        | 1.37%   |
| Fujitsu FUTRO S720                        | 2        | 1.37%   |
| Fujitsu ESPRIMO C720                      | 2        | 1.37%   |
| Dell OptiPlex 5040                        | 2        | 1.37%   |
| AAEON UP-APL01                            | 2        | 1.37%   |
| Winston Marriot PICO PC  PICOPC           | 1        | 0.68%   |
| Supermicro SYS-E301-9D-8CN8TP             | 1        | 0.68%   |
| Sun SUNW,Ultra-1                          | 1        | 0.68%   |
| Silicom Minnowboard Turbot D0/D1 PLATFORM | 1        | 0.68%   |
| Shuttle XH610                             | 1        | 0.68%   |
| Shuttle DS61                              | 1        | 0.68%   |
| ShenZhen MinWin 3865U-6L                  | 1        | 0.68%   |
| SeeedStudio ODYSSEY-X86J4125              | 1        | 0.68%   |
| Seeed Studio ODYSSEY-X86J4105             | 1        | 0.68%   |
| Purism Librem Mini v2                     | 1        | 0.68%   |
| Protectli FW6E                            | 1        | 0.68%   |
| PC Engines APU                            | 1        | 0.68%   |
| NEXCOM ASG                                | 1        | 0.68%   |
| MSI MS-6788                               | 1        | 0.68%   |
| MSI Compaq dx2420 Microtower              | 1        | 0.68%   |
| Lenovo ThinkPad T400 2768W3A              | 1        | 0.68%   |
| Lenovo ThinkCentre M93p 10AB003CGE        | 1        | 0.68%   |
| Lenovo ThinkCentre M92P 3237CK4           | 1        | 0.68%   |
| Lenovo ThinkCentre M73 10B4S03V05         | 1        | 0.68%   |
| Lenovo IdeaCentre 310S-08ASR 90G9002PGE   | 1        | 0.68%   |
| Lenovo IdeaCentre 3 07ADA05 90MV007UGE    | 1        | 0.68%   |
| Intel UTC-520C                            | 1        | 0.68%   |
| Intel QHSW02                              | 1        | 0.68%   |
| Intel DH67BL AAG10189-207                 | 1        | 0.68%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                          | Desktops | Percent |
|-------------------------------|----------|---------|
| Unknown                       | 29       | 19.86%  |
| PC Engines APU2               | 8        | 5.48%   |
| PC Engines apu4               | 7        | 4.79%   |
| Dell OptiPlex                 | 6        | 4.11%   |
| Deciso Netboard               | 6        | 4.11%   |
| MW GMLK-2                     | 4        | 2.74%   |
| IceWhale ZimaBoard            | 4        | 2.74%   |
| Protectli FW4B                | 3        | 2.05%   |
| Lenovo ThinkCentre            | 3        | 2.05%   |
| Intel Q3XXG4-P                | 3        | 2.05%   |
| Fujitsu FUTRO                 | 3        | 2.05%   |
| Fujitsu ESPRIMO               | 3        | 2.05%   |
| Techvision TVI7309X           | 2        | 1.37%   |
| Shuttle DS10U                 | 2        | 1.37%   |
| Shuttle DH170                 | 2        | 1.37%   |
| Lenovo IdeaCentre             | 2        | 1.37%   |
| HP Compaq                     | 2        | 1.37%   |
| Hardkernel ODROID-H2          | 2        | 1.37%   |
| Dell PowerEdge                | 2        | 1.37%   |
| ASUS 1HE                      | 2        | 1.37%   |
| AAEON UP-APL01                | 2        | 1.37%   |
| Winston Marriot PICO          | 1        | 0.68%   |
| Supermicro SYS-E301-9D-8CN8TP | 1        | 0.68%   |
| Sun SUNW                      | 1        | 0.68%   |
| Silicom Minnowboard           | 1        | 0.68%   |
| Shuttle XH610                 | 1        | 0.68%   |
| Shuttle DS61                  | 1        | 0.68%   |
| ShenZhen MinWin 3865U-6L      | 1        | 0.68%   |
| SeeedStudio ODYSSEY-X86J4125  | 1        | 0.68%   |
| Seeed Studio ODYSSEY-X86J4105 | 1        | 0.68%   |
| Purism Librem                 | 1        | 0.68%   |
| Protectli FW6E                | 1        | 0.68%   |
| PC Engines APU                | 1        | 0.68%   |
| NEXCOM ASG                    | 1        | 0.68%   |
| MSI MS-6788                   | 1        | 0.68%   |
| MSI Compaq                    | 1        | 0.68%   |
| Lenovo ThinkPad               | 1        | 0.68%   |
| Intel UTC-520C                | 1        | 0.68%   |
| Intel QHSW02                  | 1        | 0.68%   |
| Intel DH67BL                  | 1        | 0.68%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2017    | 18       | 12.33%  |
| 2016    | 17       | 11.64%  |
| 2018    | 16       | 10.96%  |
| 2022    | 15       | 10.27%  |
| 2021    | 15       | 10.27%  |
| 2020    | 14       | 9.59%   |
| 2023    | 11       | 7.53%   |
| 2014    | 8        | 5.48%   |
| 2019    | 7        | 4.79%   |
| 2015    | 7        | 4.79%   |
| 2013    | 5        | 3.42%   |
| 2012    | 4        | 2.74%   |
| 2011    | 3        | 2.05%   |
| Unknown | 3        | 2.05%   |
| 2009    | 2        | 1.37%   |
| 2007    | 1        | 0.68%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 146      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 121      | 82.88%  |
| Yes  | 25       | 17.12%  |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 8.01-16.0       | 60       | 40%     |
| 16.01-24.0      | 35       | 23.33%  |
| 4.01-8.0        | 32       | 21.33%  |
| 32.01-64.0      | 7        | 4.67%   |
| 2.01-3.0        | 7        | 4.67%   |
| 64.01-256.0     | 3        | 2%      |
| 24.01-32.0      | 2        | 1.33%   |
| More than 256.0 | 1        | 0.67%   |
| 3.01-4.0        | 1        | 0.67%   |
| 1.01-2.0        | 1        | 0.67%   |
| 0.01-0.5        | 1        | 0.67%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 0.01-0.5   | 81       | 53.64%  |
| 0.51-1.0   | 50       | 33.11%  |
| 1.01-2.0   | 12       | 7.95%   |
| 2.01-3.0   | 3        | 1.99%   |
| 0          | 2        | 1.32%   |
| 4.01-8.0   | 1        | 0.66%   |
| 32.01-64.0 | 1        | 0.66%   |
| 3.01-4.0   | 1        | 0.66%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 121      | 80.13%  |
| 2      | 14       | 9.27%   |
| 0      | 11       | 7.28%   |
| 4      | 2        | 1.32%   |
| 3      | 2        | 1.32%   |
| 9      | 1        | 0.66%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 135      | 90.6%   |
| Yes       | 14       | 9.4%    |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 145      | 99.32%  |
| No        | 1        | 0.68%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 123      | 83.11%  |
| Yes       | 25       | 16.89%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 130      | 89.04%  |
| Yes       | 16       | 10.96%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Austria | 146      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                     | Desktops | Percent |
|--------------------------|----------|---------|
| Vienna                   | 71       | 42.26%  |
| Graz                     | 16       | 9.52%   |
| Linz                     | 5        | 2.98%   |
| Innsbruck                | 4        | 2.38%   |
| Wels                     | 3        | 1.79%   |
| Feldkirch                | 3        | 1.79%   |
| Stockerau                | 2        | 1.19%   |
| Sankt Veit an der Glan   | 2        | 1.19%   |
| Salzburg                 | 2        | 1.19%   |
| Purkersdorf              | 2        | 1.19%   |
| Krems                    | 2        | 1.19%   |
| Klagenfurt               | 2        | 1.19%   |
| Hittisau                 | 2        | 1.19%   |
| Axams                    | 2        | 1.19%   |
| Zell am See              | 1        | 0.6%    |
| Voggenberg               | 1        | 0.6%    |
| Tulln                    | 1        | 0.6%    |
| Trausdorf an der Wulka   | 1        | 0.6%    |
| Tragwein                 | 1        | 0.6%    |
| Steyr                    | 1        | 0.6%    |
| Steinhaus                | 1        | 0.6%    |
| Spittal an der Drau      | 1        | 0.6%    |
| Sieghartskirchen         | 1        | 0.6%    |
| Siegendorf im Burgenland | 1        | 0.6%    |
| Seyring                  | 1        | 0.6%    |
| Schwechat                | 1        | 0.6%    |
| Schluesslberg            | 1        | 0.6%    |
| Sankt PÃ¶lten          | 1        | 0.6%    |
| Sankt Pantaleon          | 1        | 0.6%    |
| Rankweil                 | 1        | 0.6%    |
| Poelfing                 | 1        | 0.6%    |
| Pichl bei Wels           | 1        | 0.6%    |
| Pfaffing                 | 1        | 0.6%    |
| Ohlsdorf                 | 1        | 0.6%    |
| Oberpullendorf           | 1        | 0.6%    |
| Oberndorf in Tirol       | 1        | 0.6%    |
| Niklasdorf               | 1        | 0.6%    |
| Neulengbach              | 1        | 0.6%    |
| Mistelbach               | 1        | 0.6%    |
| Millstatt                | 1        | 0.6%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Transcend           | 23       | 31     | 14.56%  |
| Samsung Electronics | 23       | 38     | 14.56%  |
| Kingston            | 15       | 18     | 9.49%   |
| Crucial             | 13       | 17     | 8.23%   |
| WDC                 | 9        | 14     | 5.7%    |
| Intel               | 7        | 11     | 4.43%   |
| China               | 6        | 8      | 3.8%    |
| SanDisk             | 5        | 11     | 3.16%   |
| Hoodisk             | 5        | 6      | 3.16%   |
| Toshiba             | 4        | 7      | 2.53%   |
| Seagate             | 4        | 11     | 2.53%   |
| Phison              | 4        | 5      | 2.53%   |
| Silicon Motion      | 3        | 3      | 1.9%    |
| Patriot             | 3        | 5      | 1.9%    |
| Innodisk            | 2        | 3      | 1.27%   |
| FORESEE             | 2        | 3      | 1.27%   |
| Dogfish             | 2        | 2      | 1.27%   |
| Dell                | 2        | 2      | 1.27%   |
| Corsair             | 2        | 5      | 1.27%   |
| BORY                | 2        | 5      | 1.27%   |
| A-DATA Technology   | 2        | 5      | 1.27%   |
| Verbatim            | 1        | 1      | 0.63%   |
| SPCC                | 1        | 2      | 0.63%   |
| SK hynix            | 1        | 6      | 0.63%   |
| Plextor             | 1        | 1      | 0.63%   |
| OCZ                 | 1        | 1      | 0.63%   |
| Mushkin             | 1        | 1      | 0.63%   |
| Micron Technology   | 1        | 1      | 0.63%   |
| LITEONIT            | 1        | 1      | 0.63%   |
| Leven               | 1        | 2      | 0.63%   |
| KIOXIA              | 1        | 1      | 0.63%   |
| KingSpec            | 1        | 1      | 0.63%   |
| KeepData            | 1        | 1      | 0.63%   |
| Hitachi             | 1        | 1      | 0.63%   |
| HGST                | 1        | 8      | 0.63%   |
| GOODRAM             | 1        | 1      | 0.63%   |
| Fanxiang            | 1        | 2      | 0.63%   |
| BR                  | 1        | 1      | 0.63%   |
| BIWIN               | 1        | 1      | 0.63%   |
| BAITITON            | 1        | 1      | 0.63%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Transcend TS128GMSA370 128GB         | 6        | 3.7%    |
| Transcend TS128GMSA230S 128GB        | 5        | 3.09%   |
| Samsung SSD 840 EVO 250GB            | 5        | 3.09%   |
| Crucial CT240BX500SSD1 240GB         | 3        | 1.85%   |
| China SATA SSD 16GB                  | 3        | 1.85%   |
| Transcend TS64GMSA230S 64GB          | 2        | 1.23%   |
| Transcend TS256GMSA230S 256GB        | 2        | 1.23%   |
| Transcend TS240GSSD220S 240GB        | 2        | 1.23%   |
| Transcend TS16GMSA370 16GB           | 2        | 1.23%   |
| Silicon Motion P10D 1TB              | 2        | 1.23%   |
| SanDisk SSD PLUS 120GB               | 2        | 1.23%   |
| Samsung SSD 980 250GB                | 2        | 1.23%   |
| Samsung SSD 970 EVO Plus 250GB       | 2        | 1.23%   |
| Samsung SSD 830 Series 256GB         | 2        | 1.23%   |
| Phison SATA SSD 16GB                 | 2        | 1.23%   |
| Kingston SUV500MS120G 120GB          | 2        | 1.23%   |
| Kingston SKC600MS256G 256GB          | 2        | 1.23%   |
| Intel SSDSC2KW128G8 128GB            | 2        | 1.23%   |
| Intel SSDPEKNU512GZ 512GB            | 2        | 1.23%   |
| Hoodisk SSD 64GB                     | 2        | 1.23%   |
| Hoodisk SSD 128GB                    | 2        | 1.23%   |
| FORESEE 128GB SSD                    | 2        | 1.23%   |
| Crucial CT250P2SSD8 250GB            | 2        | 1.23%   |
| Crucial CT250MX500SSD1 250GB         | 2        | 1.23%   |
| China SATA SSD 64GB                  | 2        | 1.23%   |
| BORY M500 128G                       | 2        | 1.23%   |
| WDC WD800JD-60LSA5 80GB              | 1        | 0.62%   |
| WDC WD5000BEVT-22ZAT0 500GB          | 1        | 0.62%   |
| WDC WD40EFZX-68AWUN0 4TB             | 1        | 0.62%   |
| WDC WD1600BEVT-75ZCT2 160GB          | 1        | 0.62%   |
| WDC WD1600BEVS-00UST0 160GB          | 1        | 0.62%   |
| WDC WD120EFBX-68B0EN0 12TB           | 1        | 0.62%   |
| WDC WD10JPVT-75A1YT0 1TB             | 1        | 0.62%   |
| WDC WD10EZEX-08WN4A0 1TB             | 1        | 0.62%   |
| WDC WD Elements 25A1 4TB             | 1        | 0.62%   |
| WDC PC SN530 SDBPMPZ-256G-1001 256GB | 1        | 0.62%   |
| Verbatim Vi550 S3 256GB              | 1        | 0.62%   |
| Transcend TS64GMSA370 64GB           | 1        | 0.62%   |
| Transcend TS256GMTS430S 256GB        | 1        | 0.62%   |
| Transcend TS256GMSA370 256GB         | 1        | 0.62%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 8        | 12     | 38.1%   |
| Toshiba             | 4        | 7      | 19.05%  |
| Seagate             | 3        | 4      | 14.29%  |
| Dell                | 2        | 2      | 9.52%   |
| Samsung Electronics | 1        | 2      | 4.76%   |
| Hitachi             | 1        | 1      | 4.76%   |
| HGST                | 1        | 8      | 4.76%   |
| Apple               | 1        | 1      | 4.76%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Transcend           | 23       | 31     | 21.3%   |
| Samsung Electronics | 15       | 22     | 13.89%  |
| Kingston            | 14       | 17     | 12.96%  |
| Crucial             | 10       | 14     | 9.26%   |
| China               | 6        | 8      | 5.56%   |
| SanDisk             | 5        | 11     | 4.63%   |
| Hoodisk             | 5        | 6      | 4.63%   |
| Intel               | 4        | 5      | 3.7%    |
| Phison              | 3        | 4      | 2.78%   |
| Innodisk            | 2        | 3      | 1.85%   |
| FORESEE             | 2        | 3      | 1.85%   |
| Dogfish             | 2        | 2      | 1.85%   |
| BORY                | 2        | 5      | 1.85%   |
| Verbatim            | 1        | 1      | 0.93%   |
| SPCC                | 1        | 2      | 0.93%   |
| SK hynix            | 1        | 6      | 0.93%   |
| Seagate             | 1        | 7      | 0.93%   |
| Patriot             | 1        | 1      | 0.93%   |
| OCZ                 | 1        | 1      | 0.93%   |
| Mushkin             | 1        | 1      | 0.93%   |
| LITEONIT            | 1        | 1      | 0.93%   |
| Leven               | 1        | 2      | 0.93%   |
| KingSpec            | 1        | 1      | 0.93%   |
| KeepData            | 1        | 1      | 0.93%   |
| GOODRAM             | 1        | 1      | 0.93%   |
| BR                  | 1        | 1      | 0.93%   |
| BIWIN               | 1        | 1      | 0.93%   |
| BAITITON            | 1        | 1      | 0.93%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SSD  | 103      | 159    | 68.21%  |
| NVMe | 30       | 49     | 19.87%  |
| HDD  | 18       | 37     | 11.92%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 112      | 196    | 78.87%  |
| NVMe | 30       | 49     | 21.13%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 102      | 167    | 85.71%  |
| 0.51-1.0   | 11       | 16     | 9.24%   |
| 3.01-4.0   | 2        | 5      | 1.68%   |
| 4.01-10.0  | 2        | 5      | 1.68%   |
| 10.01-20.0 | 1        | 2      | 0.84%   |
| 1.01-2.0   | 1        | 1      | 0.84%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 101-250    | 86       | 56.95%  |
| 251-500    | 21       | 13.91%  |
| 21-50      | 15       | 9.93%   |
| 1-20       | 11       | 7.28%   |
| 51-100     | 11       | 7.28%   |
| 501-1000   | 6        | 3.97%   |
| 1001-2000  | 1        | 0.66%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 1-20     | 142      | 94.67%  |
| 21-50    | 6        | 4%      |
| 101-250  | 1        | 0.67%   |
| 501-1000 | 1        | 0.67%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| WDC WD1600BEVS-00UST0 160GB       | 1        | 1      | 16.67%  |
| SK hynix SC308 SATA 128GB         | 1        | 6      | 16.67%  |
| Samsung Electronics HM500LI 500GB | 1        | 2      | 16.67%  |
| Intel SSDPEKKW128G7 128GB         | 1        | 1      | 16.67%  |
| Hitachi HDS721050CLA660 500GB     | 1        | 1      | 16.67%  |
| HGST HTS725050A7E630 500GB        | 1        | 8      | 16.67%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 1        | 1      | 16.67%  |
| SK hynix            | 1        | 6      | 16.67%  |
| Samsung Electronics | 1        | 2      | 16.67%  |
| Intel               | 1        | 1      | 16.67%  |
| Hitachi             | 1        | 1      | 16.67%  |
| HGST                | 1        | 8      | 16.67%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 1        | 1      | 25%     |
| Samsung Electronics | 1        | 2      | 25%     |
| Hitachi             | 1        | 1      | 25%     |
| HGST                | 1        | 8      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 4        | 12     | 66.67%  |
| NVMe | 1        | 1      | 16.67%  |
| SSD  | 1        | 6      | 16.67%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                     | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Intel SSDPEKKW128G7 128GB | 1        | 1      | 50%     |
| Crucial CT250P2SSD8 250GB | 1        | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Intel   | 1        | 1      | 50%     |
| Crucial | 1        | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 129      | 220    | 92.81%  |
| Malfunc  | 5        | 19     | 3.6%    |
| Detected | 3        | 4      | 2.16%   |
| Failed   | 2        | 2      | 1.44%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 110      | 61.11%  |
| AMD                         | 33       | 18.33%  |
| Samsung Electronics         | 8        | 4.44%   |
| Silicon Motion              | 4        | 2.22%   |
| Phison Electronics          | 4        | 2.22%   |
| SanDisk                     | 3        | 1.67%   |
| Micron/Crucial Technology   | 3        | 1.67%   |
| Broadcom / LSI              | 3        | 1.67%   |
| ASMedia Technology          | 2        | 1.11%   |
| Realtek Semiconductor       | 1        | 0.56%   |
| Micron Technology           | 1        | 0.56%   |
| MAXIO Technology (Hangzhou) | 1        | 0.56%   |
| Marvell Technology Group    | 1        | 0.56%   |
| Lite-On Technology          | 1        | 0.56%   |
| KIOXIA                      | 1        | 0.56%   |
| Kingston Technology Company | 1        | 0.56%   |
| Hewlett-Packard             | 1        | 0.56%   |
| Dell                        | 1        | 0.56%   |
| ADATA Technology            | 1        | 0.56%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Desktops | Percent |
|----------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 23       | 12.04%  |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 11       | 5.76%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 10       | 5.24%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 9        | 4.71%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 9        | 4.71%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 8        | 4.19%   |
| AMD FCH SATA Controller [IDE mode]                                               | 8        | 4.19%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 6        | 3.14%   |
| Intel unknown                                                                    | 5        | 2.62%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 4        | 2.09%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 4        | 2.09%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 4        | 2.09%   |
| Intel Comet Lake SATA AHCI Controller                                            | 4        | 2.09%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 4        | 2.09%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 4        | 2.09%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 3        | 1.57%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                               | 3        | 1.57%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 3        | 1.57%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 2        | 1.05%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                              | 2        | 1.05%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)             | 2        | 1.05%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 2        | 1.05%   |
| Intel Tiger Lake-LP SATA Controller                                              | 2        | 1.05%   |
| Intel SSD 670p Series [Keystone Harbor]                                          | 2        | 1.05%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 2        | 1.05%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 2        | 1.05%   |
| Intel Atom Processor C3000 Series SATA Controller 0                              | 2        | 1.05%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 2        | 1.05%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 2        | 1.05%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 2        | 1.05%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 2        | 1.05%   |
| SanDisk WD Green SN350 240GB (DRAM-less) / SN560E NVMe SSD                       | 1        | 0.52%   |
| Sandisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD          | 1        | 0.52%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                            | 1        | 0.52%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 1        | 0.52%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                    | 1        | 0.52%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1        | 0.52%   |
| Realtek RTS5763DL NVMe SSD Controller (DRAM-less)                                | 1        | 0.52%   |
| Phison E16 PCIe4 NVMe Controller                                                 | 1        | 0.52%   |
| Phison E12 NVMe Controller                                                       | 1        | 0.52%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 129      | 70.49%  |
| NVMe | 32       | 17.49%  |
| IDE  | 13       | 7.1%    |
| RAID | 6        | 3.28%   |
| SCSI | 2        | 1.09%   |
| SAS  | 1        | 0.55%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Desktops | Percent |
|---------|----------|---------|
| Intel   | 112      | 76.71%  |
| AMD     | 33       | 22.6%   |
| Unknown | 1        | 0.68%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| AMD GX-412TC SOC                                       | 15       | 10.27%  |
| Intel Celeron J4125 CPU @ 2.00GHz                      | 7        | 4.79%   |
| Intel Celeron CPU J3160 @ 1.60GHz                      | 7        | 4.79%   |
| Intel Celeron N5105 @ 2.00GHz                          | 6        | 4.11%   |
| AMD GX-420MC SOC                                       | 6        | 4.11%   |
| Intel N100                                             | 5        | 3.42%   |
| Intel Core i5-10210U CPU @ 1.60GHz                     | 3        | 2.05%   |
| Intel Celeron CPU J3455 @ 1.50GHz                      | 3        | 2.05%   |
| Intel Xeon CPU E5620 @ 2.40GHz                         | 2        | 1.37%   |
| Intel Pentium CPU G3220 @ 3.00GHz                      | 2        | 1.37%   |
| Intel Core i7-8565U CPU @ 1.80GHz                      | 2        | 1.37%   |
| Intel Core i5-6600 CPU @ 3.30GHz                       | 2        | 1.37%   |
| Intel Core i5-6500 CPU @ 3.20GHz                       | 2        | 1.37%   |
| Intel Core i5-4200U CPU @ 1.60GHz                      | 2        | 1.37%   |
| Intel Core i3-6100T CPU @ 3.20GHz                      | 2        | 1.37%   |
| Intel Core i3-4130 CPU @ 3.40GHz                       | 2        | 1.37%   |
| Intel Celeron J4105 CPU @ 1.50GHz                      | 2        | 1.37%   |
| Intel Celeron CPU N3450 @ 1.10GHz                      | 2        | 1.37%   |
| Intel Atom CPU E3845 @ 1.91GHz                         | 2        | 1.37%   |
| Intel Atom CPU C3558 @ 2.20GHz                         | 2        | 1.37%   |
| AMD GX-217GA SOC with Radeon HD Graphics               | 2        | 1.37%   |
| Intel Xeon E-2136 CPU @ 3.30GHz                        | 1        | 0.68%   |
| Intel Xeon D-2146NT CPU @ 2.30GHz                      | 1        | 0.68%   |
| Intel Xeon CPU E5320 @ 1.86GHz                         | 1        | 0.68%   |
| Intel Pentium Silver J5005 CPU @ 1.50GHz               | 1        | 0.68%   |
| Intel Pentium Dual-Core                                | 1        | 0.68%   |
| Intel Pentium CPU N4200 @ 1.10GHz                      | 1        | 0.68%   |
| Intel Pentium CPU G4400 @ 3.30GHz                      | 1        | 0.68%   |
| Intel Pentium 4 CPU 2.40GHz ("GenuineIntel" 686-class) | 1        | 0.68%   |
| Intel N200                                             | 1        | 0.68%   |
| Intel Genuine CPU 0000 @ 2.40GHz                       | 1        | 0.68%   |
| Intel Core i7-8550U CPU @ 1.80GHz                      | 1        | 0.68%   |
| Intel Core i7-7500U CPU @ 2.70GHz                      | 1        | 0.68%   |
| Intel Core i7-5550U CPU @ 2.00GHz                      | 1        | 0.68%   |
| Intel Core i7-4790 CPU @ 3.60GHz                       | 1        | 0.68%   |
| Intel Core i7-4770 CPU @ 3.40GHz                       | 1        | 0.68%   |
| Intel Core i7-3770 CPU @ 3.40GHz                       | 1        | 0.68%   |
| Intel Core i7-3517UE CPU @ 1.70GHz                     | 1        | 0.68%   |
| Intel Core i7-10510U CPU @ 1.80GHz                     | 1        | 0.68%   |
| Intel Core i5-9500 CPU @ 3.00GHz                       | 1        | 0.68%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Celeron           | 35       | 23.97%  |
| Intel Core i5           | 25       | 17.12%  |
| AMD GX                  | 23       | 15.75%  |
| Other                   | 13       | 8.9%    |
| Intel Core i3           | 12       | 8.22%   |
| Intel Core i7           | 10       | 6.85%   |
| Intel Xeon              | 5        | 3.42%   |
| Intel Pentium           | 4        | 2.74%   |
| Intel Atom              | 4        | 2.74%   |
| Intel Core 2 Duo        | 2        | 1.37%   |
| AMD Ryzen 7             | 2        | 1.37%   |
| Intel Pentium Silver    | 1        | 0.68%   |
| Intel Pentium Dual-Core | 1        | 0.68%   |
| Intel Pentium 4         | 1        | 0.68%   |
| Intel Genuine           | 1        | 0.68%   |
| AMD Turion II Neo       | 1        | 0.68%   |
| AMD Ryzen Threadripper  | 1        | 0.68%   |
| AMD Ryzen 5 PRO         | 1        | 0.68%   |
| AMD Ryzen 5             | 1        | 0.68%   |
| AMD G                   | 1        | 0.68%   |
| AMD FX                  | 1        | 0.68%   |
| AMD Athlon              | 1        | 0.68%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 95       | 65.07%  |
| 2       | 34       | 23.29%  |
| 8       | 7        | 4.79%   |
| 6       | 3        | 2.05%   |
| 1       | 2        | 1.37%   |
| Unknown | 2        | 1.37%   |
| 64      | 1        | 0.68%   |
| 16      | 1        | 0.68%   |
| 12      | 1        | 0.68%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 140      | 95.89%  |
| Unknown | 4        | 2.74%   |
| 2       | 2        | 1.37%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 101      | 69.18%  |
| 2       | 41       | 28.08%  |
| Unknown | 4        | 2.74%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Puma          | 21       | 14.38%  |
| KabyLake      | 18       | 12.33%  |
| Unknown       | 17       | 11.64%  |
| Skylake       | 11       | 7.53%   |
| Silvermont    | 11       | 7.53%   |
| Haswell       | 11       | 7.53%   |
| Goldmont plus | 11       | 7.53%   |
| Goldmont      | 10       | 6.85%   |
| IvyBridge     | 7        | 4.79%   |
| Zen           | 3        | 2.05%   |
| SandyBridge   | 3        | 2.05%   |
| Penryn        | 3        | 2.05%   |
| Westmere      | 2        | 1.37%   |
| TigerLake     | 2        | 1.37%   |
| Jaguar        | 2        | 1.37%   |
| Excavator     | 2        | 1.37%   |
| CometLake     | 2        | 1.37%   |
| Broadwell     | 2        | 1.37%   |
| Zen+          | 1        | 0.68%   |
| Zen 3         | 1        | 0.68%   |
| Zen 2         | 1        | 0.68%   |
| NetBurst      | 1        | 0.68%   |
| K10           | 1        | 0.68%   |
| IceLake       | 1        | 0.68%   |
| Core          | 1        | 0.68%   |
| Bobcat        | 1        | 0.68%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 102      | 85%     |
| AMD                        | 10       | 8.33%   |
| ASPEED Technology          | 4        | 3.33%   |
| Nvidia                     | 3        | 2.5%    |
| Matrox Electronics Systems | 1        | 0.83%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel GeminiLake [UHD Graphics 600]                                                      | 10       | 8.26%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 9        | 7.44%   |
| Intel HD Graphics 530                                                                    | 8        | 6.61%   |
| Intel HD Graphics 500                                                                    | 7        | 5.79%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 6        | 4.96%   |
| Intel JasperLake [UHD Graphics]                                                          | 6        | 4.96%   |
| Intel Alder Lake-N [UHD Graphics]                                                        | 6        | 4.96%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4        | 3.31%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 4        | 3.31%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 3        | 2.48%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3        | 2.48%   |
| Intel HD Graphics 630                                                                    | 3        | 2.48%   |
| Intel HD Graphics 620                                                                    | 3        | 2.48%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 3        | 2.48%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 3        | 2.48%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2        | 1.65%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 2        | 1.65%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2        | 1.65%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2        | 1.65%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2        | 1.65%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 2        | 1.65%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2        | 1.65%   |
| AMD Kabini [Radeon HD 8280E]                                                             | 2        | 1.65%   |
| AMD ES1000                                                                               | 2        | 1.65%   |
| Nvidia NV28 [GeForce4 Ti 4200 AGP 8x]                                                    | 1        | 0.83%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 1        | 0.83%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1        | 0.83%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 1        | 0.83%   |
| Intel Whiskey Lake-U GT1 [UHD Graphics 610]                                              | 1        | 0.83%   |
| Intel UHD Graphics 620                                                                   | 1        | 0.83%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 1        | 0.83%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 1        | 0.83%   |
| Intel HD Graphics 6000                                                                   | 1        | 0.83%   |
| Intel HD Graphics 5500                                                                   | 1        | 0.83%   |
| Intel HD Graphics 510                                                                    | 1        | 0.83%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 1        | 0.83%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 1        | 0.83%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 1        | 0.83%   |
| Intel Apollo Lake [HD Graphics 505]                                                      | 1        | 0.83%   |
| Intel AlderLake-S GT1                                                                    | 1        | 0.83%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| 1 x Intel  | 100      | 68.49%  |
| Other      | 26       | 17.81%  |
| 1 x AMD    | 10       | 6.85%   |
| 1 x ASPEED | 4        | 2.74%   |
| 1 x Nvidia | 3        | 2.05%   |
| 2 x Intel  | 2        | 1.37%   |
| 1 x Matrox | 1        | 0.68%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 119      | 81.51%  |
| Unknown     | 26       | 17.81%  |
| Proprietary | 1        | 0.68%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 144      | 98.63%  |
| 1.01-2.0   | 1        | 0.68%   |
| 0.01-0.5   | 1        | 0.68%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Samsung Electronics | 2        | 22.22%  |
| Philips             | 2        | 22.22%  |
| Dell                | 2        | 22.22%  |
| Medion              | 1        | 11.11%  |
| Lenovo              | 1        | 11.11%  |
| DENON               | 1        | 11.11%  |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Samsung Electronics SyncMaster SAM021E 1680x1050 430x270mm 20.0-inch | 1        | 11.11%  |
| Samsung Electronics CJG9S SAM9596 3840x1080                          | 1        | 11.11%  |
| Philips PHL BDM4037U PHLC142 3840x2160 890x500mm 40.2-inch           | 1        | 11.11%  |
| Philips PHL 273V7 PHLC156 1920x1080 600x340mm 27.2-inch              | 1        | 11.11%  |
| Medion MD22321 MEA8302 1920x1080 700x390mm 31.5-inch                 | 1        | 11.11%  |
| Lenovo LCD Monitor LEN4033 1440x900 300x190mm 14.0-inch              | 1        | 11.11%  |
| DENON AVR DON004B 1920x1080 1330x750mm 60.1-inch                     | 1        | 11.11%  |
| Dell P2210 DEL404E 1680x1050 470x300mm 22.0-inch                     | 1        | 11.11%  |
| Dell 2001FP DELA007 1600x1200 410x310mm 20.2-inch                    | 1        | 11.11%  |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 3        | 33.33%  |
| 1680x1050 (WSXGA+) | 2        | 22.22%  |
| 3840x2160 (4K)     | 1        | 11.11%  |
| 3840x1080          | 1        | 11.11%  |
| 1600x1200          | 1        | 11.11%  |
| 1440x900 (WXGA+)   | 1        | 11.11%  |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 20      | 2        | 22.22%  |
| 60      | 1        | 11.11%  |
| 40      | 1        | 11.11%  |
| 31      | 1        | 11.11%  |
| 27      | 1        | 11.11%  |
| 22      | 1        | 11.11%  |
| 14      | 1        | 11.11%  |
| Unknown | 1        | 11.11%  |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 3        | 33.33%  |
| 801-900     | 1        | 11.11%  |
| 601-700     | 1        | 11.11%  |
| 501-600     | 1        | 11.11%  |
| 201-300     | 1        | 11.11%  |
| 1001-1500   | 1        | 11.11%  |
| Unknown     | 1        | 11.11%  |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Desktops | Percent |
|-------|----------|---------|
| 16/9  | 4        | 44.44%  |
| 16/10 | 3        | 33.33%  |
| 4/3   | 1        | 11.11%  |
| 32/9  | 1        | 11.11%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 151-200        | 2        | 22.22%  |
| More than 1000 | 1        | 11.11%  |
| 81-90          | 1        | 11.11%  |
| 351-500        | 1        | 11.11%  |
| 301-350        | 1        | 11.11%  |
| 201-250        | 1        | 11.11%  |
| 501-1000       | 1        | 11.11%  |
| Unknown        | 1        | 11.11%  |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 5        | 55.56%  |
| 1-50    | 1        | 11.11%  |
| 121-160 | 1        | 11.11%  |
| 101-120 | 1        | 11.11%  |
| Unknown | 1        | 11.11%  |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 137      | 93.2%   |
| 1     | 9        | 6.12%   |
| 2     | 1        | 0.68%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 116      | 63.39%  |
| Realtek Semiconductor | 46       | 25.14%  |
| Broadcom              | 5        | 2.73%   |
| Qualcomm Atheros      | 3        | 1.64%   |
| TP-Link               | 2        | 1.09%   |
| LG Electronics        | 2        | 1.09%   |
| Edimax Technology     | 2        | 1.09%   |
| Seeed Technology      | 1        | 0.55%   |
| MediaTek              | 1        | 0.55%   |
| Google                | 1        | 0.55%   |
| Dresden Elektronik    | 1        | 0.55%   |
| Davicom Semiconductor | 1        | 0.55%   |
| AVM                   | 1        | 0.55%   |
| Arduino SA            | 1        | 0.55%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 39       | 17.11%  |
| Intel I211 Gigabit Network Connection                                  | 29       | 12.72%  |
| Intel I210 Gigabit Network Connection                                  | 25       | 10.96%  |
| Intel Ethernet Controller I226-V                                       | 13       | 5.7%    |
| Intel Ethernet Controller I225-V                                       | 11       | 4.82%   |
| Intel I350 Gigabit Network Connection                                  | 8        | 3.51%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 7        | 3.07%   |
| Intel Ethernet Connection (2) I219-LM                                  | 6        | 2.63%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                   | 5        | 2.19%   |
| Intel Wi-Fi 6 AX200                                                    | 4        | 1.75%   |
| Intel 82576 Gigabit Network Connection                                 | 4        | 1.75%   |
| Realtek RTL8125 2.5GbE Controller                                      | 3        | 1.32%   |
| Intel Ethernet Connection (2) I219-V                                   | 3        | 1.32%   |
| Intel 82574L Gigabit Network Connection                                | 3        | 1.32%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                         | 3        | 1.32%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                 | 2        | 0.88%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 2        | 0.88%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller      | 2        | 0.88%   |
| LG Optimus Android Phone [USB tethering mode]                          | 2        | 0.88%   |
| Intel Wireless 7260                                                    | 2        | 0.88%   |
| Intel Gemini Lake PCH CNVi WiFi                                        | 2        | 0.88%   |
| Intel Ethernet Connection X553 1GbE                                    | 2        | 0.88%   |
| Intel Ethernet Connection I217-V                                       | 2        | 0.88%   |
| Intel Ethernet Connection (6) I219-LM                                  | 2        | 0.88%   |
| Intel Ethernet Connection (17) I219-V                                  | 2        | 0.88%   |
| Intel Centrino Advanced-N 6235                                         | 2        | 0.88%   |
| Intel 82583V Gigabit Network Connection                                | 2        | 0.88%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]         | 2        | 0.88%   |
| Seeed Seeeduino_Cortex_M0+                                             | 1        | 0.44%   |
| Realtek USB 2.5GbE Controller                                          | 1        | 0.44%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter               | 1        | 0.44%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                        | 1        | 0.44%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                 | 1        | 0.44%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                | 1        | 0.44%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 1        | 0.44%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1        | 0.44%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 1        | 0.44%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)         | 1        | 0.44%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1        | 0.44%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                | 1        | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 14       | 51.85%  |
| Realtek Semiconductor | 6        | 22.22%  |
| TP-Link               | 2        | 7.41%   |
| Qualcomm Atheros      | 2        | 7.41%   |
| Edimax Technology     | 2        | 7.41%   |
| MediaTek              | 1        | 3.7%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 4        | 14.81%  |
| TP-Link Archer T3U [Realtek RTL8812BU]                         | 2        | 7.41%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2        | 7.41%   |
| Intel Wireless 7260                                            | 2        | 7.41%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 2        | 7.41%   |
| Intel Centrino Advanced-N 6235                                 | 2        | 7.41%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS] | 2        | 7.41%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1        | 3.7%    |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 1        | 3.7%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 1        | 3.7%    |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1        | 3.7%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1        | 3.7%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1        | 3.7%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 1        | 3.7%    |
| Intel Wireless 7265                                            | 1        | 3.7%    |
| Intel Wireless 3165                                            | 1        | 3.7%    |
| Intel Wireless 3160                                            | 1        | 3.7%    |
| Intel Ultimate N WiFi Link 5300                                | 1        | 3.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 110      | 68.75%  |
| Realtek Semiconductor | 43       | 26.88%  |
| Broadcom              | 5        | 3.13%   |
| Qualcomm Atheros      | 1        | 0.63%   |
| Davicom Semiconductor | 1        | 0.63%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Desktops | Percent |
|-------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller        | 39       | 20.31%  |
| Intel I211 Gigabit Network Connection                                         | 29       | 15.1%   |
| Intel I210 Gigabit Network Connection                                         | 25       | 13.02%  |
| Intel Ethernet Controller I226-V                                              | 13       | 6.77%   |
| Intel Ethernet Controller I225-V                                              | 11       | 5.73%   |
| Intel I350 Gigabit Network Connection                                         | 8        | 4.17%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 7        | 3.65%   |
| Intel Ethernet Connection (2) I219-LM                                         | 6        | 3.13%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                          | 5        | 2.6%    |
| Intel 82576 Gigabit Network Connection                                        | 4        | 2.08%   |
| Realtek RTL8125 2.5GbE Controller                                             | 3        | 1.56%   |
| Intel Ethernet Connection (2) I219-V                                          | 3        | 1.56%   |
| Intel 82574L Gigabit Network Connection                                       | 3        | 1.56%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 3        | 1.56%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 2        | 1.04%   |
| Intel Ethernet Connection X553 1GbE                                           | 2        | 1.04%   |
| Intel Ethernet Connection I217-V                                              | 2        | 1.04%   |
| Intel Ethernet Connection (6) I219-LM                                         | 2        | 1.04%   |
| Intel Ethernet Connection (17) I219-V                                         | 2        | 1.04%   |
| Intel 82583V Gigabit Network Connection                                       | 2        | 1.04%   |
| Realtek USB 2.5GbE Controller                                                 | 1        | 0.52%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 1        | 0.52%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1        | 0.52%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 1        | 0.52%   |
| Intel I210 Gigabit Fiber Network Connection                                   | 1        | 0.52%   |
| Intel Ethernet Connection X722 for 10GbE SFP+                                 | 1        | 0.52%   |
| Intel Ethernet Connection X722 for 10GBASE-T                                  | 1        | 0.52%   |
| Intel Ethernet Connection I217-LM                                             | 1        | 0.52%   |
| Intel Ethernet Connection (7) I219-LM                                         | 1        | 0.52%   |
| Intel Ethernet Connection (5) I219-LM                                         | 1        | 0.52%   |
| Intel Ethernet Connection (14) I219-V                                         | 1        | 0.52%   |
| Intel Ethernet Connection (12) I219-V                                         | 1        | 0.52%   |
| Intel 82579V Gigabit Network Connection                                       | 1        | 0.52%   |
| Intel 82576NS Gigabit Network Connection                                      | 1        | 0.52%   |
| Intel 82575EB Gigabit Network Connection                                      | 1        | 0.52%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1        | 0.52%   |
| Intel 82567LM Gigabit Network Connection                                      | 1        | 0.52%   |
| Intel 82541PI Gigabit Ethernet Controller                                     | 1        | 0.52%   |
| Davicom DM9621A USB Fast Ethernet Adapter                                     | 1        | 0.52%   |
| Broadcom NetXtreme II BCM5708 Gigabit Ethernet                                | 1        | 0.52%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 145      | 81.01%  |
| WiFi     | 25       | 13.97%  |
| Modem    | 5        | 2.79%   |
| Unknown  | 4        | 2.23%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 143      | 99.31%  |
| WiFi     | 1        | 0.69%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 4     | 40       | 27.4%   |
| 3     | 32       | 21.92%  |
| 2     | 27       | 18.49%  |
| 6     | 16       | 10.96%  |
| 1     | 14       | 9.59%   |
| 5     | 7        | 4.79%   |
| 8     | 4        | 2.74%   |
| 7     | 3        | 2.05%   |
| 12    | 1        | 0.68%   |
| 9     | 1        | 0.68%   |
| 0     | 1        | 0.68%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 139      | 93.29%  |
| Yes  | 10       | 6.71%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 11       | 68.75%  |
| IMC Networks          | 2        | 12.5%   |
| Realtek Semiconductor | 1        | 6.25%   |
| MediaTek              | 1        | 6.25%   |
| Lite-On Technology    | 1        | 6.25%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                          | Desktops | Percent |
|------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                          | 4        | 25%     |
| Intel Bluetooth wireless interface             | 3        | 18.75%  |
| Intel Centrino Bluetooth Wireless Transceiver  | 2        | 12.5%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 2        | 12.5%   |
| IMC Networks Realtek Bluetooth Adapter         | 2        | 12.5%   |
| Realtek RTL8821A Bluetooth                     | 1        | 6.25%   |
| MediaTek RZ608 Bluetooth Adapter               | 1        | 6.25%   |
| Lite-On Atheros AR3012 Bluetooth               | 1        | 6.25%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 89       | 86.41%  |
| AMD                                          | 10       | 9.71%   |
| Nvidia                                       | 2        | 1.94%   |
| Zoran Co. Personal Media Division (Nogatech) | 1        | 0.97%   |
| Creative Labs                                | 1        | 0.97%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Desktops | Percent |
|---------------------------------------------------------------------------------------------------|----------|---------|
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 11       | 9.09%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 9        | 7.44%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 8        | 6.61%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 8        | 6.61%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 6        | 4.96%   |
| Intel Jasper Lake HD Audio                                                                        | 6        | 4.96%   |
| Intel Alder Lake-N PCH High Definition Audio Controller                                           | 6        | 4.96%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 6        | 4.96%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 5        | 4.13%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 4        | 3.31%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 4        | 3.31%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 3        | 2.48%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3        | 2.48%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 3        | 2.48%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3        | 2.48%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3        | 2.48%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2        | 1.65%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 2        | 1.65%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2        | 1.65%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2        | 1.65%   |
| Intel Alder Lake-S HD Audio Controller                                                            | 2        | 1.65%   |
| Intel 8 Series HD Audio Controller                                                                | 2        | 1.65%   |
| Intel 200 Series PCH HD Audio                                                                     | 2        | 1.65%   |
| AMD FCH Azalia Controller                                                                         | 2        | 1.65%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2        | 1.65%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID                                    | 1        | 0.83%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1        | 0.83%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1        | 0.83%   |
| Intel Smart Sound Technology (SST) Audio Controller                                               | 1        | 0.83%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1        | 0.83%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 1        | 0.83%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1        | 0.83%   |
| Intel Broadwell-U Audio Controller                                                                | 1        | 0.83%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 1        | 0.83%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1        | 0.83%   |
| Creative Labs EMU10k1 [Sound Blaster Live! Series]                                                | 1        | 0.83%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 1        | 0.83%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 1        | 0.83%   |
| AMD High Definition Audio Controller                                                              | 1        | 0.83%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 1        | 0.83%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Crucial             | 22       | 16.54%  |
| Kingston            | 17       | 12.78%  |
| SK hynix            | 14       | 10.53%  |
| Samsung Electronics | 14       | 10.53%  |
| Unknown             | 13       | 9.77%   |
| Unknown (ABCD)      | 9        | 6.77%   |
| Micron Technology   | 9        | 6.77%   |
| Corsair             | 7        | 5.26%   |
| G.Skill             | 5        | 3.76%   |
| Unknown             | 5        | 3.76%   |
| Transcend           | 3        | 2.26%   |
| Ramaxel Technology  | 2        | 1.5%    |
| A-DATA Technology   | 2        | 1.5%    |
| tigo                | 1        | 0.75%   |
| Nanya Technology    | 1        | 0.75%   |
| Mushkin             | 1        | 0.75%   |
| Lexar Co Limited    | 1        | 0.75%   |
| Kingmax             | 1        | 0.75%   |
| Kimtigo             | 1        | 0.75%   |
| GOODRAM             | 1        | 0.75%   |
| GeIL                | 1        | 0.75%   |
| DSL                 | 1        | 0.75%   |
| Avant               | 1        | 0.75%   |
| ATP                 | 1        | 0.75%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s   | 9        | 6.62%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                    | 6        | 4.41%   |
| Unknown                                                        | 5        | 3.68%   |
| Crucial RAM CT16G48C40S5.M8A1 16GB SODIMM DDR5 4800MT/s        | 3        | 2.21%   |
| SK hynix RAM HMT125U6BFR8C-G7 2GB DIMM DDR3 1067MT/s           | 2        | 1.47%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1333MT/s            | 2        | 1.47%   |
| Kingston RAM CBD26D4S9S8K1C-8 8GB SODIMM DDR4 2667MT/s         | 2        | 1.47%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s        | 2        | 1.47%   |
| Crucial RAM CT8G4SFS824A.M8FRS 8GB DIMM DDR4 2400MT/s          | 2        | 1.47%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                      | 1        | 0.74%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                           | 1        | 0.74%   |
| Unknown RAM Module 8GB 1600MT/s                                | 1        | 0.74%   |
| Unknown RAM Module 4GB SODIMM DDR3 667MT/s                     | 1        | 0.74%   |
| Unknown RAM Module 4GB DIMM DDR3 1066MT/s                      | 1        | 0.74%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                           | 1        | 0.74%   |
| Unknown RAM Module 1GB DIMM DDR2 1033MT/s                      | 1        | 0.74%   |
| Unknown RAM AW24P64F8BLK0S 8GB DIMM DDR3 1600MT/s              | 1        | 0.74%   |
| Transcend RAM TS512MLK72V6H 4GB DIMM DDR3 1600MT/s             | 1        | 0.74%   |
| Transcend RAM TS2GSH64V1B 16GB SODIMM DDR4 2133MT/s            | 1        | 0.74%   |
| Transcend RAM JM3200HSE-16G 16GB SODIMM DDR4 3200MT/s          | 1        | 0.74%   |
| tigo RAM 1600Mhz-4G 4GB SODIMM DDR3 1600MT/s                   | 1        | 0.74%   |
| SK hynix RAM Module 2GB DIMM DDR3 1333MT/s                     | 1        | 0.74%   |
| SK hynix RAM HMT451U6DFR8A-PB 4GB DIMM DDR3 1600MT/s           | 1        | 0.74%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s           | 1        | 0.74%   |
| SK hynix RAM HMT451S6DFR8A-PB 4GB DIMM DDR3 1600MT/s           | 1        | 0.74%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s         | 1        | 0.74%   |
| SK hynix RAM HMT351U6EFR8A-PB 8GB DIMM DDR3 1600MT/s           | 1        | 0.74%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB DIMM DDR3 1600MT/s           | 1        | 0.74%   |
| SK hynix RAM HMT112U6TFR8C-H9 1GB DIMM DDR3 1333MT/s           | 1        | 0.74%   |
| SK hynix RAM HMCG78MEBSA092N 16GB SODIMM DDR5 4800MT/s         | 1        | 0.74%   |
| SK hynix RAM HMCG78AEBSA092N 16GB SODIMM DDR5 4800MT/s         | 1        | 0.74%   |
| SK hynix RAM HMCG66AGBSA095N 8GB SODIMM DDR5 5600MT/s          | 1        | 0.74%   |
| SK hynix RAM HKNNNFBMAVAR-NEH 2GB Row Of Chips LPDDR4 3200MT/s | 1        | 0.74%   |
| Samsung RAM Module 8GB DIMM DDR4 2133MT/s                      | 1        | 0.74%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 1600MT/s          | 1        | 0.74%   |
| Samsung RAM M471B5273CH0-YK0 4GB SODIMM DDR3 1600MT/s          | 1        | 0.74%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s          | 1        | 0.74%   |
| Samsung RAM M471B5173QH0-YK0 4GB DIMM DDR3 1600MT/s            | 1        | 0.74%   |
| Samsung RAM M471B1G73QH0-YK0 8GB DIMM DDR3 1600MT/s            | 1        | 0.74%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s          | 1        | 0.74%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 51       | 41.46%  |
| DDR3    | 49       | 39.84%  |
| LPDDR4  | 12       | 9.76%   |
| DDR5    | 7        | 5.69%   |
| DDR2    | 2        | 1.63%   |
| Unknown | 2        | 1.63%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| SODIMM       | 61       | 50%     |
| DIMM         | 56       | 45.9%   |
| Row Of Chips | 2        | 1.64%   |
| Unknown      | 2        | 1.64%   |
| Chip         | 1        | 0.82%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 53       | 41.41%  |
| 4096  | 31       | 24.22%  |
| 16384 | 26       | 20.31%  |
| 2048  | 12       | 9.38%   |
| 32768 | 4        | 3.13%   |
| 1024  | 2        | 1.56%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 32       | 24.81%  |
| 2400    | 27       | 20.93%  |
| 1333    | 18       | 13.95%  |
| 3200    | 14       | 10.85%  |
| 2667    | 14       | 10.85%  |
| 4800    | 6        | 4.65%   |
| 2133    | 6        | 4.65%   |
| 2666    | 2        | 1.55%   |
| 1067    | 2        | 1.55%   |
| 65535   | 1        | 0.78%   |
| 5600    | 1        | 0.78%   |
| 3000    | 1        | 0.78%   |
| 1066    | 1        | 0.78%   |
| 1033    | 1        | 0.78%   |
| 800     | 1        | 0.78%   |
| 667     | 1        | 0.78%   |
| Unknown | 1        | 0.78%   |

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
| 1     | 74       | 49.33%  |
| 0     | 47       | 31.33%  |
| 2     | 14       | 9.33%   |
| 3     | 13       | 8.67%   |
| 5     | 1        | 0.67%   |
| 4     | 1        | 0.67%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 93       | 75%     |
| Net/wireless             | 12       | 9.68%   |
| Card reader              | 7        | 5.65%   |
| Bluetooth                | 7        | 5.65%   |
| Network                  | 3        | 2.42%   |
| Sound                    | 1        | 0.81%   |
| Graphics card            | 1        | 0.81%   |

