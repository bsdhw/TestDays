BSD in Austria - Tested Hardware & Statistics
---------------------------------------------

A project to collect tested hardware configurations for BSD in Austria.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Austria/Desktop/README.md) and [notebooks](/Location/Austria/Notebook/README.md).

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

Total: 340

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Hardkernel    | ODROID-H2                   | Desktop     | [a4045617ec](https://bsd-hardware.info/?probe=a4045617ec) | Feb 14, 2024 |
| Unknown       | Unknown                     | Desktop     | [ef910cb303](https://bsd-hardware.info/?probe=ef910cb303) | Feb 14, 2024 |
| Shuttle       | FH170                       | Desktop     | [e7eaced298](https://bsd-hardware.info/?probe=e7eaced298) | Feb 13, 2024 |
| Unknown       | Unknown                     | Desktop     | [11b10e5acb](https://bsd-hardware.info/?probe=11b10e5acb) | Feb 06, 2024 |
| Unknown       | Unknown                     | Desktop     | [4437069c86](https://bsd-hardware.info/?probe=4437069c86) | Feb 05, 2024 |
| Supermicro    | A1SRi 123456789             | Mini pc     | [5b7342de3f](https://bsd-hardware.info/?probe=5b7342de3f) | Feb 04, 2024 |
| Dell          | 0T7D40 A01                  | Desktop     | [19ab947fb4](https://bsd-hardware.info/?probe=19ab947fb4) | Jan 29, 2024 |
| Unknown       | Unknown                     | Desktop     | [c28104b9b5](https://bsd-hardware.info/?probe=c28104b9b5) | Jan 28, 2024 |
| Supermicro    | X11SDV-8C-TP8F              | Desktop     | [17c3586ebc](https://bsd-hardware.info/?probe=17c3586ebc) | Jan 23, 2024 |
| Unknown       | Unknown                     | Desktop     | [0b0142d5dd](https://bsd-hardware.info/?probe=0b0142d5dd) | Jan 19, 2024 |
| PC Engines    | APU2                        | Desktop     | [189362d834](https://bsd-hardware.info/?probe=189362d834) | Jan 19, 2024 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [14e2e2c18c](https://bsd-hardware.info/?probe=14e2e2c18c) | Jan 16, 2024 |
| MW            | GMLK-2_5G4L                 | Desktop     | [8707b73983](https://bsd-hardware.info/?probe=8707b73983) | Jan 08, 2024 |
| Sophos        | XG                          | Firewall    | [c30f177b0f](https://bsd-hardware.info/?probe=c30f177b0f) | Dec 26, 2023 |
| Unknown       | Unknown                     | Desktop     | [058859b9c4](https://bsd-hardware.info/?probe=058859b9c4) | Dec 26, 2023 |
| Lenovo        | 3708 SDK0J40700 WIN 3258... | Desktop     | [7ad0451a6f](https://bsd-hardware.info/?probe=7ad0451a6f) | Dec 25, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [80e8d502be](https://bsd-hardware.info/?probe=80e8d502be) | Dec 24, 2023 |
| PC Engines    | apu4                        | Desktop     | [48a0e27e11](https://bsd-hardware.info/?probe=48a0e27e11) | Dec 22, 2023 |
| Unknown       | SKYBAY                      | Desktop     | [7f8968ee0a](https://bsd-hardware.info/?probe=7f8968ee0a) | Dec 22, 2023 |
| Supermicro    | A1SRi 123456789             | Mini pc     | [a2aa82ed5d](https://bsd-hardware.info/?probe=a2aa82ed5d) | Dec 16, 2023 |
| Intel         | DH67BL AAG10189-207         | Desktop     | [e6210120bd](https://bsd-hardware.info/?probe=e6210120bd) | Dec 12, 2023 |
| Unknown       | Unknown                     | Desktop     | [be6c7879b4](https://bsd-hardware.info/?probe=be6c7879b4) | Dec 07, 2023 |
| Protectli     | FW4B                        | Desktop     | [dab9b84618](https://bsd-hardware.info/?probe=dab9b84618) | Dec 03, 2023 |
| Unknown       | SKYBAY                      | Desktop     | [e1a3d3ff53](https://bsd-hardware.info/?probe=e1a3d3ff53) | Nov 30, 2023 |
| Unknown       | SKYBAY                      | Desktop     | [6ceeb87719](https://bsd-hardware.info/?probe=6ceeb87719) | Nov 30, 2023 |
| Intel         | DH67BL AAG10189-207         | Desktop     | [734103b696](https://bsd-hardware.info/?probe=734103b696) | Nov 22, 2023 |
| CncTion       | N5105-4L B0                 | Desktop     | [6074d7118a](https://bsd-hardware.info/?probe=6074d7118a) | Nov 18, 2023 |
| Unknown       | Unknown                     | Notebook    | [8854b07e12](https://bsd-hardware.info/?probe=8854b07e12) | Nov 15, 2023 |
| CWWK          | CW-ADLN-6L                  | Desktop     | [0662bae41e](https://bsd-hardware.info/?probe=0662bae41e) | Nov 12, 2023 |
| Gigabyte      | H610M H DDR4                | Desktop     | [bdc4fdaf9c](https://bsd-hardware.info/?probe=bdc4fdaf9c) | Nov 05, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [1859b56be4](https://bsd-hardware.info/?probe=1859b56be4) | Nov 02, 2023 |
| Shuttle       | DS437                       | Notebook    | [45c2e3460c](https://bsd-hardware.info/?probe=45c2e3460c) | Oct 30, 2023 |
| Sophos        | SG                          | Firewall    | [7bdc18c407](https://bsd-hardware.info/?probe=7bdc18c407) | Oct 19, 2023 |
| Supermicro    | X11SCL-IF                   | Server      | [34ae4abdcc](https://bsd-hardware.info/?probe=34ae4abdcc) | Oct 17, 2023 |
| Fujitsu       | D3543-A1 S26361-D3543-A1... | Desktop     | [4b685d7ff1](https://bsd-hardware.info/?probe=4b685d7ff1) | Oct 14, 2023 |
| Deciso        | NetBoard-A10                | Notebook    | [12b5a57360](https://bsd-hardware.info/?probe=12b5a57360) | Oct 10, 2023 |
| Gigabyte      | H610M H DDR4                | Desktop     | [ab5400f952](https://bsd-hardware.info/?probe=ab5400f952) | Oct 08, 2023 |
| Barracuda ... | Barracuda NG Firewall F2... | Firewall    | [bdf86afe1c](https://bsd-hardware.info/?probe=bdf86afe1c) | Oct 07, 2023 |
| Barracuda ... | Barracuda NG Firewall F2... | Firewall    | [f76e1fb940](https://bsd-hardware.info/?probe=f76e1fb940) | Oct 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [13f17e09d4](https://bsd-hardware.info/?probe=13f17e09d4) | Oct 06, 2023 |
| Fujitsu       | D3543-A1 S26361-D3543-A1... | Desktop     | [5076395072](https://bsd-hardware.info/?probe=5076395072) | Oct 06, 2023 |
| PC Engines    | apu4                        | Desktop     | [20c432e07b](https://bsd-hardware.info/?probe=20c432e07b) | Oct 02, 2023 |
| ShenZhen M... | 3865U-6L                    | Desktop     | [53a70ddb3b](https://bsd-hardware.info/?probe=53a70ddb3b) | Oct 02, 2023 |
| Fujitsu       | D3543-A1 S26361-D3543-A1... | Desktop     | [8809e169a1](https://bsd-hardware.info/?probe=8809e169a1) | Sep 30, 2023 |
| Unknown       | Unknown                     | Desktop     | [20fb7f1ba8](https://bsd-hardware.info/?probe=20fb7f1ba8) | Sep 30, 2023 |
| Unknown       | Unknown                     | Desktop     | [7e82c0f66d](https://bsd-hardware.info/?probe=7e82c0f66d) | Sep 29, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [8ebba0ee37](https://bsd-hardware.info/?probe=8ebba0ee37) | Sep 19, 2023 |
| Hardkernel    | ODROID-H2                   | Desktop     | [35544a61bd](https://bsd-hardware.info/?probe=35544a61bd) | Sep 16, 2023 |
| Intel         | D2500CC AAG43156-303        | Desktop     | [281e4a541b](https://bsd-hardware.info/?probe=281e4a541b) | Aug 26, 2023 |
| Intel         | D2500CC AAG43156-303        | Desktop     | [c5745af495](https://bsd-hardware.info/?probe=c5745af495) | Aug 26, 2023 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [97321f0843](https://bsd-hardware.info/?probe=97321f0843) | Aug 20, 2023 |
| Supermicro    | A2SDi-4C-HLN4F              | Server      | [f5a3c00551](https://bsd-hardware.info/?probe=f5a3c00551) | Aug 19, 2023 |
| Fujitsu       | D3313-B1 S26361-D3313-B1    | Desktop     | [87bc92631a](https://bsd-hardware.info/?probe=87bc92631a) | Aug 16, 2023 |
| Fujitsu       | D3313-B1 S26361-D3313-B1    | Desktop     | [ec68697ed9](https://bsd-hardware.info/?probe=ec68697ed9) | Aug 16, 2023 |
| Hardkernel    | ODROID-H2                   | Desktop     | [a92e1efca1](https://bsd-hardware.info/?probe=a92e1efca1) | Aug 07, 2023 |
| Dell          | 0T7D40 A00                  | Desktop     | [e903094a75](https://bsd-hardware.info/?probe=e903094a75) | Aug 03, 2023 |
| ASRock        | J3355B-ITX                  | Desktop     | [234f0fd8aa](https://bsd-hardware.info/?probe=234f0fd8aa) | Aug 01, 2023 |
| IceWhale T... | ZimaBoard 832 ZMB           | Desktop     | [aeb59c510b](https://bsd-hardware.info/?probe=aeb59c510b) | Jul 26, 2023 |
| Dell          | 0T7D40 A00                  | Desktop     | [24e7268bbe](https://bsd-hardware.info/?probe=24e7268bbe) | Jul 19, 2023 |
| Intel         | NUC5i7RYB H73774-101        | Mini pc     | [49d1520c4a](https://bsd-hardware.info/?probe=49d1520c4a) | Jul 17, 2023 |
| Deciso        | DEC2700 - OPNsense Appli... | Notebook    | [aedd3a8255](https://bsd-hardware.info/?probe=aedd3a8255) | Jun 28, 2023 |
| Lenovo        | ThinkPad T480 20L6S2S800    | Notebook    | [722403df31](https://bsd-hardware.info/?probe=722403df31) | Jun 15, 2023 |
| ASUSTek       | H110M-R                     | Desktop     | [cc5fe45365](https://bsd-hardware.info/?probe=cc5fe45365) | Jun 15, 2023 |
| ShenZhen M... | 3865U-6L                    | Desktop     | [5733ad3c03](https://bsd-hardware.info/?probe=5733ad3c03) | May 25, 2023 |
| Hardkernel    | ODROID-H2                   | Desktop     | [3966c4828d](https://bsd-hardware.info/?probe=3966c4828d) | May 12, 2023 |
| Supermicro    | X10SLL-F                    | Server      | [d72b0581a4](https://bsd-hardware.info/?probe=d72b0581a4) | May 11, 2023 |
| PC Engines    | apu4                        | Desktop     | [2589a0c02c](https://bsd-hardware.info/?probe=2589a0c02c) | May 10, 2023 |
| AWOW          | AK34Pro                     | Mini pc     | [463ffd90f0](https://bsd-hardware.info/?probe=463ffd90f0) | May 08, 2023 |
| Barracuda ... | Barracuda NG Firewall F1... | Firewall    | [d7b4814da7](https://bsd-hardware.info/?probe=d7b4814da7) | May 08, 2023 |
| Gigabyte      | H81M-D2V                    | Desktop     | [5f9bbf2d15](https://bsd-hardware.info/?probe=5f9bbf2d15) | May 04, 2023 |
| ZOTAC         | Unknown                     | Desktop     | [f6c39a3582](https://bsd-hardware.info/?probe=f6c39a3582) | Apr 30, 2023 |
| HP            | ProBook 640 G4              | Notebook    | [7b44e1591f](https://bsd-hardware.info/?probe=7b44e1591f) | Apr 29, 2023 |
| Deciso        | Netboard A10 GEN2 Model ... | Desktop     | [e7e7a6470d](https://bsd-hardware.info/?probe=e7e7a6470d) | Apr 27, 2023 |
| Deciso        | Netboard A10 GEN2 Model ... | Desktop     | [b517729fb4](https://bsd-hardware.info/?probe=b517729fb4) | Apr 27, 2023 |
| ShenZhen M... | 3865U-6L                    | Desktop     | [1548471a4d](https://bsd-hardware.info/?probe=1548471a4d) | Apr 25, 2023 |
| Shuttle       | DS437                       | Notebook    | [284decb573](https://bsd-hardware.info/?probe=284decb573) | Apr 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [0d7a1b58ed](https://bsd-hardware.info/?probe=0d7a1b58ed) | Apr 21, 2023 |
| MSI           | 2A78h                       | Desktop     | [8560ebd69c](https://bsd-hardware.info/?probe=8560ebd69c) | Apr 18, 2023 |
| ZOTAC         | Unknown                     | Desktop     | [8c3cdf29a2](https://bsd-hardware.info/?probe=8c3cdf29a2) | Apr 17, 2023 |
| Shuttle       | DS10U                       | Desktop     | [7f98ef1865](https://bsd-hardware.info/?probe=7f98ef1865) | Apr 10, 2023 |
| Shuttle       | FS61                        | Desktop     | [9c3df7e926](https://bsd-hardware.info/?probe=9c3df7e926) | Apr 09, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [8452deae22](https://bsd-hardware.info/?probe=8452deae22) | Apr 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [11f0439894](https://bsd-hardware.info/?probe=11f0439894) | Apr 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [9a5ccefb18](https://bsd-hardware.info/?probe=9a5ccefb18) | Mar 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [f80047716b](https://bsd-hardware.info/?probe=f80047716b) | Mar 15, 2023 |
| Dell          | 01TN68 A02                  | Desktop     | [cb6c76df00](https://bsd-hardware.info/?probe=cb6c76df00) | Mar 13, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [62c09245a4](https://bsd-hardware.info/?probe=62c09245a4) | Mar 10, 2023 |
| ASUSTek       | P11C-M Series               | Desktop     | [80814c04b6](https://bsd-hardware.info/?probe=80814c04b6) | Mar 10, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [278a2a11cd](https://bsd-hardware.info/?probe=278a2a11cd) | Mar 09, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [ef85735453](https://bsd-hardware.info/?probe=ef85735453) | Mar 09, 2023 |
| ASUSTek       | P11C-M Series               | Desktop     | [242677230a](https://bsd-hardware.info/?probe=242677230a) | Mar 09, 2023 |
| BESSTAR Te... | TH50                        | Desktop     | [e27931f082](https://bsd-hardware.info/?probe=e27931f082) | Mar 07, 2023 |
| ASUSTek       | P11C-M Series               | Desktop     | [866573ffa0](https://bsd-hardware.info/?probe=866573ffa0) | Mar 03, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [bf21395f79](https://bsd-hardware.info/?probe=bf21395f79) | Feb 24, 2023 |
| Intel         | DENLOW_WS                   | Desktop     | [f6f5953979](https://bsd-hardware.info/?probe=f6f5953979) | Feb 23, 2023 |
| HP            | 3397                        | Desktop     | [8b231fd832](https://bsd-hardware.info/?probe=8b231fd832) | Feb 19, 2023 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [0f4dd9a9bc](https://bsd-hardware.info/?probe=0f4dd9a9bc) | Feb 15, 2023 |
| Fujitsu       | D3313-B1 S26361-D3313-B1    | Desktop     | [be8fb945ef](https://bsd-hardware.info/?probe=be8fb945ef) | Feb 12, 2023 |
| Intel         | ChiefRiver                  | Desktop     | [ae6ea07868](https://bsd-hardware.info/?probe=ae6ea07868) | Feb 05, 2023 |
| PC Engines    | APU2                        | Desktop     | [d59ed5b52f](https://bsd-hardware.info/?probe=d59ed5b52f) | Feb 02, 2023 |
| CncTion       | N5105-4L B0                 | Desktop     | [d9746ad1c3](https://bsd-hardware.info/?probe=d9746ad1c3) | Jan 28, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [84375af67f](https://bsd-hardware.info/?probe=84375af67f) | Jan 27, 2023 |
| Lenovo        | ThinkPad X220 4291WF5       | Notebook    | [24544f4a94](https://bsd-hardware.info/?probe=24544f4a94) | Jan 24, 2023 |
| Intel         | NUC5i7RYB H73774-101        | Mini pc     | [9954516f1a](https://bsd-hardware.info/?probe=9954516f1a) | Jan 22, 2023 |
| Unknown       | YL-E3845L4-V2               | Desktop     | [d93eb933f1](https://bsd-hardware.info/?probe=d93eb933f1) | Jan 20, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [ba99fba661](https://bsd-hardware.info/?probe=ba99fba661) | Jan 19, 2023 |
| Unknown       | Unknown                     | Desktop     | [22015084fc](https://bsd-hardware.info/?probe=22015084fc) | Jan 17, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [78327c664e](https://bsd-hardware.info/?probe=78327c664e) | Jan 16, 2023 |
| Lenovo        | ThinkPad A485 20MVS0LG00    | Notebook    | [247370372d](https://bsd-hardware.info/?probe=247370372d) | Jan 15, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [d4846c3ec1](https://bsd-hardware.info/?probe=d4846c3ec1) | Jan 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [87d79c88e1](https://bsd-hardware.info/?probe=87d79c88e1) | Jan 11, 2023 |
| MW            | GMLK-2_5G4L                 | Desktop     | [5a4affef3e](https://bsd-hardware.info/?probe=5a4affef3e) | Jan 04, 2023 |
| Sophos        | SG                          | Firewall    | [8679b4c8f4](https://bsd-hardware.info/?probe=8679b4c8f4) | Dec 31, 2022 |
| Hardkernel    | ODROID-H2                   | Desktop     | [b685ddc2ad](https://bsd-hardware.info/?probe=b685ddc2ad) | Dec 28, 2022 |
| Lenovo        | ThinkPad A485 20MVS0LG00    | Notebook    | [683591700f](https://bsd-hardware.info/?probe=683591700f) | Dec 19, 2022 |
| Unknown       | Unknown                     | Desktop     | [f7700c781d](https://bsd-hardware.info/?probe=f7700c781d) | Dec 17, 2022 |
| Intel         | H81U                        | Notebook    | [fab3eecc66](https://bsd-hardware.info/?probe=fab3eecc66) | Dec 15, 2022 |
| Intel         | H81U                        | Notebook    | [fe1c3cb754](https://bsd-hardware.info/?probe=fe1c3cb754) | Dec 14, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [657972a55d](https://bsd-hardware.info/?probe=657972a55d) | Dec 06, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [33f23b1291](https://bsd-hardware.info/?probe=33f23b1291) | Dec 06, 2022 |
| ZOTAC         | ZBOX-CI341                  | Mini pc     | [2299087d09](https://bsd-hardware.info/?probe=2299087d09) | Nov 29, 2022 |
| Deciso        | Netboard A10 GEN2 Model ... | Desktop     | [d48dbd053d](https://bsd-hardware.info/?probe=d48dbd053d) | Nov 28, 2022 |
| PC Engines    | apu4                        | Desktop     | [588e065800](https://bsd-hardware.info/?probe=588e065800) | Nov 28, 2022 |
| Dell          | 0T7D40 A01                  | Desktop     | [45d96a0b5a](https://bsd-hardware.info/?probe=45d96a0b5a) | Nov 24, 2022 |
| Gigabyte      | J3455N-D3H                  | Desktop     | [2f812bd8c3](https://bsd-hardware.info/?probe=2f812bd8c3) | Nov 22, 2022 |
| Gigabyte      | J3455N-D3H                  | Desktop     | [86dcacdb40](https://bsd-hardware.info/?probe=86dcacdb40) | Nov 13, 2022 |
| PC Engines    | apu4                        | Desktop     | [7ed7638be3](https://bsd-hardware.info/?probe=7ed7638be3) | Nov 03, 2022 |
| PC Engines    | APU2                        | Desktop     | [0c573848ce](https://bsd-hardware.info/?probe=0c573848ce) | Oct 27, 2022 |
| PC Engines    | APU2                        | Desktop     | [0677b5c196](https://bsd-hardware.info/?probe=0677b5c196) | Oct 25, 2022 |
| Gigabyte      | J3455N-D3H                  | Desktop     | [9757e40c42](https://bsd-hardware.info/?probe=9757e40c42) | Oct 13, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [53dfc5844c](https://bsd-hardware.info/?probe=53dfc5844c) | Oct 01, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [30cb759583](https://bsd-hardware.info/?probe=30cb759583) | Sep 30, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [2c1aad67d1](https://bsd-hardware.info/?probe=2c1aad67d1) | Sep 26, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [c33dc6a072](https://bsd-hardware.info/?probe=c33dc6a072) | Sep 25, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [37cafd59eb](https://bsd-hardware.info/?probe=37cafd59eb) | Sep 20, 2022 |
| Deciso        | Netboard A10 GEN2 Model ... | Desktop     | [e0b8ceecae](https://bsd-hardware.info/?probe=e0b8ceecae) | Sep 16, 2022 |
| Deciso        | Netboard A10 GEN2 Model ... | Desktop     | [e082eca671](https://bsd-hardware.info/?probe=e082eca671) | Sep 08, 2022 |
| PC Engines    | APU2                        | Desktop     | [1650d8c419](https://bsd-hardware.info/?probe=1650d8c419) | Sep 05, 2022 |
| AAEON         | UP-APL01 V0.4               | Desktop     | [a8d73a9156](https://bsd-hardware.info/?probe=a8d73a9156) | Sep 01, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [63587e2fca](https://bsd-hardware.info/?probe=63587e2fca) | Aug 31, 2022 |
| Deciso        | NetBoard-A10                | Notebook    | [aefb2f4660](https://bsd-hardware.info/?probe=aefb2f4660) | Aug 24, 2022 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | Desktop     | [45043e0e42](https://bsd-hardware.info/?probe=45043e0e42) | Aug 18, 2022 |
| Fujitsu       | D3224-A1 S26361-D3224-A1    | Desktop     | [4e056b6f77](https://bsd-hardware.info/?probe=4e056b6f77) | Aug 11, 2022 |
| Deciso        | Netboard A10 GEN2 Model ... | Desktop     | [1cd64c78d5](https://bsd-hardware.info/?probe=1cd64c78d5) | Aug 10, 2022 |
| HP            | EliteBook 850 G7 Noteboo... | Notebook    | [f603e648c7](https://bsd-hardware.info/?probe=f603e648c7) | Aug 01, 2022 |
| IP3 Tech      | IB2                         | Mini pc     | [9e304de7ad](https://bsd-hardware.info/?probe=9e304de7ad) | Jul 31, 2022 |
| Deciso        | Netboard A10 GEN2 Model ... | Desktop     | [5c00da486d](https://bsd-hardware.info/?probe=5c00da486d) | Jul 29, 2022 |
| Dell          | 0T7D40 A01                  | Desktop     | [bd2f6f8596](https://bsd-hardware.info/?probe=bd2f6f8596) | Jul 29, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [69c0b0d218](https://bsd-hardware.info/?probe=69c0b0d218) | Jul 29, 2022 |
| Biostar       | A10N-8800E                  | Desktop     | [fe4d305991](https://bsd-hardware.info/?probe=fe4d305991) | Jul 27, 2022 |
| Gigabyte      | H87-HD3                     | Desktop     | [e6a9b0dd8b](https://bsd-hardware.info/?probe=e6a9b0dd8b) | Jul 25, 2022 |
| MW            | GMLK-2_5G4L                 | Desktop     | [57da61c80c](https://bsd-hardware.info/?probe=57da61c80c) | Jul 17, 2022 |
| PC Engines    | apu4                        | Desktop     | [4e24f7aa5b](https://bsd-hardware.info/?probe=4e24f7aa5b) | Jul 15, 2022 |
| Deciso        | Netboard A10 GEN2 Model ... | Desktop     | [bfbac4efa5](https://bsd-hardware.info/?probe=bfbac4efa5) | Jul 05, 2022 |
| Secudos       | Unknown                     | Desktop     | [beaf8ea459](https://bsd-hardware.info/?probe=beaf8ea459) | Jul 04, 2022 |
| Secudos       | Unknown                     | Desktop     | [e54c622459](https://bsd-hardware.info/?probe=e54c622459) | Jul 04, 2022 |
| Lenovo        | 3708 SDK0J40700 WIN 3258... | Desktop     | [e68d7a5dff](https://bsd-hardware.info/?probe=e68d7a5dff) | Jun 29, 2022 |
| HP            | EliteBook 850 G7 Noteboo... | Notebook    | [f573327012](https://bsd-hardware.info/?probe=f573327012) | Jun 29, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [f68b48b102](https://bsd-hardware.info/?probe=f68b48b102) | Jun 28, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [86bac086b3](https://bsd-hardware.info/?probe=86bac086b3) | Jun 27, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [153c93c827](https://bsd-hardware.info/?probe=153c93c827) | Jun 20, 2022 |
| Fujitsu       | LIFEBOOK A555               | Notebook    | [23d96bc669](https://bsd-hardware.info/?probe=23d96bc669) | Jun 11, 2022 |
| PC Engines    | APU2                        | Desktop     | [b296296b84](https://bsd-hardware.info/?probe=b296296b84) | Jun 10, 2022 |
| AWOW          | PC BOX                      | Mini pc     | [9c86650e6a](https://bsd-hardware.info/?probe=9c86650e6a) | Jun 01, 2022 |
| MSI           | MS-6788                     | Desktop     | [f750cb83e3](https://bsd-hardware.info/?probe=f750cb83e3) | May 31, 2022 |
| Dell          | 055H3G A01                  | Desktop     | [cc1c76afc0](https://bsd-hardware.info/?probe=cc1c76afc0) | May 24, 2022 |
| Shuttle       | DS10U                       | Desktop     | [573358361a](https://bsd-hardware.info/?probe=573358361a) | May 22, 2022 |
| Protectli     | FW4B Ver                    | Desktop     | [02f79b14cb](https://bsd-hardware.info/?probe=02f79b14cb) | May 20, 2022 |
| PC Engines    | APU2                        | Desktop     | [7132ae8216](https://bsd-hardware.info/?probe=7132ae8216) | May 19, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [f658f57d9a](https://bsd-hardware.info/?probe=f658f57d9a) | May 12, 2022 |
| ZOTAC         | ZBOX-CI323NANO              | Mini pc     | [d97560d02b](https://bsd-hardware.info/?probe=d97560d02b) | May 08, 2022 |
| BESSTAR Te... | U820                        | Notebook    | [6f2aa2d02a](https://bsd-hardware.info/?probe=6f2aa2d02a) | May 07, 2022 |
| Dell          | 0T7D40 A01                  | Desktop     | [7a43bfada9](https://bsd-hardware.info/?probe=7a43bfada9) | Apr 23, 2022 |
| Dell          | 0T7D40 A01                  | Desktop     | [4ad1c07aa5](https://bsd-hardware.info/?probe=4ad1c07aa5) | Apr 19, 2022 |
| PC Engines    | apu4                        | Desktop     | [beb62ed999](https://bsd-hardware.info/?probe=beb62ed999) | Apr 07, 2022 |
| Unknown       | Unknown                     | Desktop     | [4d52408404](https://bsd-hardware.info/?probe=4d52408404) | Apr 04, 2022 |
| Dell          | 096JG8 A01                  | Desktop     | [7ee68eb371](https://bsd-hardware.info/?probe=7ee68eb371) | Apr 02, 2022 |
| Dell          | 096JG8 A01                  | Desktop     | [657c893958](https://bsd-hardware.info/?probe=657c893958) | Apr 02, 2022 |
| PC Engines    | APU2                        | Desktop     | [5aef21bfc3](https://bsd-hardware.info/?probe=5aef21bfc3) | Mar 26, 2022 |
| Secudos       | Unknown                     | Desktop     | [970e9962ff](https://bsd-hardware.info/?probe=970e9962ff) | Mar 24, 2022 |
| ZOTAC         | ZBOX-CI341                  | Mini pc     | [fc5d42c3b7](https://bsd-hardware.info/?probe=fc5d42c3b7) | Mar 21, 2022 |
| PC Engines    | apu4                        | Desktop     | [395eb04c69](https://bsd-hardware.info/?probe=395eb04c69) | Mar 14, 2022 |
| Lenovo        | ThinkPad T410 2537WEE       | Notebook    | [973ade9e4a](https://bsd-hardware.info/?probe=973ade9e4a) | Mar 07, 2022 |
| PC Engines    | APU2                        | Desktop     | [c5ed9017c3](https://bsd-hardware.info/?probe=c5ed9017c3) | Mar 05, 2022 |
| ZOTAC         | ZBOX-CI323NANO              | Mini pc     | [59cee41440](https://bsd-hardware.info/?probe=59cee41440) | Mar 01, 2022 |
| Shuttle       | DS10U                       | Desktop     | [1300217458](https://bsd-hardware.info/?probe=1300217458) | Feb 28, 2022 |
| HP            | 805D                        | Desktop     | [4c07559a11](https://bsd-hardware.info/?probe=4c07559a11) | Feb 28, 2022 |
| PC Engines    | apu4                        | Desktop     | [606d9c838c](https://bsd-hardware.info/?probe=606d9c838c) | Feb 26, 2022 |
| PC Engines    | apu4                        | Desktop     | [8b42751f17](https://bsd-hardware.info/?probe=8b42751f17) | Feb 25, 2022 |
| Unknown       | Unknown                     | Desktop     | [96bae6432b](https://bsd-hardware.info/?probe=96bae6432b) | Feb 24, 2022 |
| Supermicro    | X11SBA-LN4F                 | Server      | [b64aeb3448](https://bsd-hardware.info/?probe=b64aeb3448) | Feb 23, 2022 |
| Shuttle       | FH170                       | Desktop     | [5fd212645c](https://bsd-hardware.info/?probe=5fd212645c) | Feb 18, 2022 |
| Dell          | 096JG8 A01                  | Desktop     | [6baeaf5d48](https://bsd-hardware.info/?probe=6baeaf5d48) | Feb 17, 2022 |
| Unknown       | Unknown                     | Desktop     | [f172be6fb0](https://bsd-hardware.info/?probe=f172be6fb0) | Feb 17, 2022 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | Desktop     | [f1dd03cdcb](https://bsd-hardware.info/?probe=f1dd03cdcb) | Feb 16, 2022 |
| Lenovo        | ThinkPad T400 2768W3A       | Desktop     | [4691fdb146](https://bsd-hardware.info/?probe=4691fdb146) | Feb 13, 2022 |
| Lenovo        | ThinkPad T400 2768W3A       | Desktop     | [97788dfb1a](https://bsd-hardware.info/?probe=97788dfb1a) | Feb 13, 2022 |
| Fujitsu       | D3224-A1 S26361-D3224-A1    | Desktop     | [0117d61d81](https://bsd-hardware.info/?probe=0117d61d81) | Feb 07, 2022 |
| Lenovo        | ThinkPad T510 4384AJ6       | Notebook    | [70a56029e7](https://bsd-hardware.info/?probe=70a56029e7) | Jan 31, 2022 |
| Dell          | 0NKW6Y A00                  | Desktop     | [1ea6d60d70](https://bsd-hardware.info/?probe=1ea6d60d70) | Jan 30, 2022 |
| HP            | 805D                        | Desktop     | [d7e312307f](https://bsd-hardware.info/?probe=d7e312307f) | Jan 30, 2022 |
| HP            | ProLiant DL360e Gen8        | Server      | [f97e208e22](https://bsd-hardware.info/?probe=f97e208e22) | Jan 30, 2022 |
| HP            | ProLiant DL360e Gen8        | Server      | [c2431ee491](https://bsd-hardware.info/?probe=c2431ee491) | Jan 30, 2022 |
| Unknown       | YL-J3160L4                  | Desktop     | [763dc53716](https://bsd-hardware.info/?probe=763dc53716) | Jan 28, 2022 |
| Lenovo        | Y50-70 20378                | Notebook    | [1feb455e8c](https://bsd-hardware.info/?probe=1feb455e8c) | Jan 25, 2022 |
| Lenovo        | 0B98401 WIN                 | Desktop     | [c5430f00cf](https://bsd-hardware.info/?probe=c5430f00cf) | Jan 22, 2022 |
| Intel         | D2500CC AAG43156-303        | Desktop     | [d2d10a1ffc](https://bsd-hardware.info/?probe=d2d10a1ffc) | Jan 21, 2022 |
| Dell          | Precision 7530              | Notebook    | [498bfe852c](https://bsd-hardware.info/?probe=498bfe852c) | Jan 07, 2022 |
| Biostar       | N3050NH                     | Desktop     | [31e33326fa](https://bsd-hardware.info/?probe=31e33326fa) | Jan 06, 2022 |
| Gigabyte      | B150-HD3P-CF                | Desktop     | [9752eae10b](https://bsd-hardware.info/?probe=9752eae10b) | Jan 06, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [6c208c85a5](https://bsd-hardware.info/?probe=6c208c85a5) | Jan 06, 2022 |
| ZOTAC         | ZBOXNANO-ID63/ID64/ID65     | Mini pc     | [d8d2cea545](https://bsd-hardware.info/?probe=d8d2cea545) | Jan 05, 2022 |
| Fujitsu       | D3164-C2 S26361-D3164-C2    | Desktop     | [765210be77](https://bsd-hardware.info/?probe=765210be77) | Dec 28, 2021 |
| Unknown       | Unknown                     | Notebook    | [db4d12babd](https://bsd-hardware.info/?probe=db4d12babd) | Dec 23, 2021 |
| Purism        | Librem Mini v2              | Desktop     | [528ef01c87](https://bsd-hardware.info/?probe=528ef01c87) | Dec 20, 2021 |
| HP            | EliteBook Folio 9470m       | Notebook    | [b872e9b044](https://bsd-hardware.info/?probe=b872e9b044) | Dec 18, 2021 |
| Unknown       | Unknown                     | Notebook    | [eab0d6c6d3](https://bsd-hardware.info/?probe=eab0d6c6d3) | Dec 12, 2021 |
| HP            | 805D                        | Desktop     | [324b4670b6](https://bsd-hardware.info/?probe=324b4670b6) | Dec 12, 2021 |
| Unknown       | Unknown                     | Desktop     | [943365b2f1](https://bsd-hardware.info/?probe=943365b2f1) | Dec 11, 2021 |
| BESSTAR Te... | IB9                         | Desktop     | [26717d3708](https://bsd-hardware.info/?probe=26717d3708) | Dec 10, 2021 |
| HP            | 3397                        | Desktop     | [ac295c89b0](https://bsd-hardware.info/?probe=ac295c89b0) | Dec 05, 2021 |
| Protectli     | FW6E                        | Desktop     | [3ddd9d297c](https://bsd-hardware.info/?probe=3ddd9d297c) | Dec 02, 2021 |
| Unknown       | Unknown                     | Notebook    | [6d1fb7b4bb](https://bsd-hardware.info/?probe=6d1fb7b4bb) | Nov 27, 2021 |
| Intel         | D2500CC AAG43156-303        | Desktop     | [69194e4ead](https://bsd-hardware.info/?probe=69194e4ead) | Nov 23, 2021 |
| HP            | ProLiant DL360e Gen8        | Server      | [d12db83eb6](https://bsd-hardware.info/?probe=d12db83eb6) | Nov 13, 2021 |
| PC Engines    | APU2                        | Desktop     | [9a262221d5](https://bsd-hardware.info/?probe=9a262221d5) | Nov 03, 2021 |
| Winston Ma... | PICO PC  PICOPC             | Desktop     | [55a9e67b4c](https://bsd-hardware.info/?probe=55a9e67b4c) | Oct 26, 2021 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | Notebook    | [087d40ba7c](https://bsd-hardware.info/?probe=087d40ba7c) | Oct 19, 2021 |
| BESSTAR Te... | UM270 V1.0                  | Desktop     | [aa7ee48846](https://bsd-hardware.info/?probe=aa7ee48846) | Oct 19, 2021 |
| PC Engines    | APU2                        | Desktop     | [6580ee2c23](https://bsd-hardware.info/?probe=6580ee2c23) | Oct 19, 2021 |
| HP            | 805D                        | Desktop     | [b61f6f9d52](https://bsd-hardware.info/?probe=b61f6f9d52) | Oct 16, 2021 |
| ASRock        | B460M Pro4                  | Desktop     | [e0fbe78c7e](https://bsd-hardware.info/?probe=e0fbe78c7e) | Oct 14, 2021 |
| ASRock        | H510M-HDV/M.2               | Desktop     | [39c65baf01](https://bsd-hardware.info/?probe=39c65baf01) | Oct 14, 2021 |
| Silicom       | MinnowBoard Turbot          | Desktop     | [0c6c98cbd3](https://bsd-hardware.info/?probe=0c6c98cbd3) | Oct 09, 2021 |
| ASUSTek       | P11C-I Series               | Desktop     | [2690a544a5](https://bsd-hardware.info/?probe=2690a544a5) | Sep 29, 2021 |
| Shuttle       | DS10U                       | Desktop     | [6f5d8afb4b](https://bsd-hardware.info/?probe=6f5d8afb4b) | Sep 29, 2021 |
| Unknown       | YL-J3160L4                  | Desktop     | [ad178dbed0](https://bsd-hardware.info/?probe=ad178dbed0) | Sep 13, 2021 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | Notebook    | [bf9b083102](https://bsd-hardware.info/?probe=bf9b083102) | Sep 08, 2021 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | Notebook    | [62f9376847](https://bsd-hardware.info/?probe=62f9376847) | Sep 04, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [5147f5734d](https://bsd-hardware.info/?probe=5147f5734d) | Sep 04, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [2e8b641cc4](https://bsd-hardware.info/?probe=2e8b641cc4) | Sep 04, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [d6fb115604](https://bsd-hardware.info/?probe=d6fb115604) | Aug 21, 2021 |
| Shuttle       | DS10U                       | Desktop     | [7e11cc28f5](https://bsd-hardware.info/?probe=7e11cc28f5) | Aug 19, 2021 |
| HP            | 1495                        | Desktop     | [d7e136e07f](https://bsd-hardware.info/?probe=d7e136e07f) | Aug 11, 2021 |
| PC Engines    | apu4                        | Desktop     | [f6d199de58](https://bsd-hardware.info/?probe=f6d199de58) | Aug 08, 2021 |
| Silicom       | MinnowBoard Turbot          | Desktop     | [6defda405f](https://bsd-hardware.info/?probe=6defda405f) | Aug 02, 2021 |
| Shuttle       | FH170                       | Desktop     | [0c381808eb](https://bsd-hardware.info/?probe=0c381808eb) | Aug 02, 2021 |
| Supermicro    | X11SBA-LN4F                 | Server      | [2030131cb8](https://bsd-hardware.info/?probe=2030131cb8) | Jul 31, 2021 |
| SeeedStudi... | ODYSSEY-X86J41X5 SD-BS-C... | Desktop     | [eb75d5e2a3](https://bsd-hardware.info/?probe=eb75d5e2a3) | Jul 29, 2021 |
| Unknown       | YL-J3160L4                  | Desktop     | [1d117c1c21](https://bsd-hardware.info/?probe=1d117c1c21) | Jul 28, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [e91c7fa2c8](https://bsd-hardware.info/?probe=e91c7fa2c8) | Jul 26, 2021 |
| NEXCOM        | NSA3110 B                   | Desktop     | [4f532bbd9e](https://bsd-hardware.info/?probe=4f532bbd9e) | Jul 25, 2021 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [d26a6c8990](https://bsd-hardware.info/?probe=d26a6c8990) | Jul 24, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [c1c721ac0b](https://bsd-hardware.info/?probe=c1c721ac0b) | Jul 16, 2021 |
| Shuttle       | DS10U                       | Desktop     | [746d0761cc](https://bsd-hardware.info/?probe=746d0761cc) | Jul 16, 2021 |
| Supermicro    | X11SDV-4C-TP8F              | Server      | [0b9c25527f](https://bsd-hardware.info/?probe=0b9c25527f) | Jul 09, 2021 |
| Dell          | 0T7D40 A01                  | Desktop     | [f67d589e29](https://bsd-hardware.info/?probe=f67d589e29) | Jul 08, 2021 |
| Dell          | 0T7D40 A01                  | Desktop     | [d39de0c0dc](https://bsd-hardware.info/?probe=d39de0c0dc) | Jun 30, 2021 |
| BESSTAR Te... | IB9                         | Desktop     | [1c8c267ce2](https://bsd-hardware.info/?probe=1c8c267ce2) | Jun 20, 2021 |
| HP            | 1495                        | Desktop     | [572b748256](https://bsd-hardware.info/?probe=572b748256) | Jun 10, 2021 |
| BESSTAR Te... | IB9                         | Desktop     | [f152e4b3e7](https://bsd-hardware.info/?probe=f152e4b3e7) | Jun 10, 2021 |
| HPE           | ProLiant MicroServer Gen... | Server      | [c42933f9fd](https://bsd-hardware.info/?probe=c42933f9fd) | Jun 01, 2021 |
| HP            | 3397                        | Desktop     | [ab3fc66a9e](https://bsd-hardware.info/?probe=ab3fc66a9e) | May 20, 2021 |
| HP            | 1495                        | Desktop     | [3d2d524163](https://bsd-hardware.info/?probe=3d2d524163) | May 19, 2021 |
| HP            | 3397                        | Desktop     | [5d2d602907](https://bsd-hardware.info/?probe=5d2d602907) | May 19, 2021 |
| Protectli     | FW4B                        | Desktop     | [1a8296fffd](https://bsd-hardware.info/?probe=1a8296fffd) | May 15, 2021 |
| Protectli     | FW4B                        | Desktop     | [47aa4d946c](https://bsd-hardware.info/?probe=47aa4d946c) | May 14, 2021 |
| Intel         | D2500CC AAG43156-303        | Desktop     | [b77ceeed88](https://bsd-hardware.info/?probe=b77ceeed88) | May 14, 2021 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [b3acafeb1a](https://bsd-hardware.info/?probe=b3acafeb1a) | May 09, 2021 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [86cec3b874](https://bsd-hardware.info/?probe=86cec3b874) | May 09, 2021 |
| Unknown       | Unknown                     | Desktop     | [2d8cb88aa7](https://bsd-hardware.info/?probe=2d8cb88aa7) | May 03, 2021 |
| Unknown       | SKYBAY                      | Desktop     | [34073c7322](https://bsd-hardware.info/?probe=34073c7322) | Apr 21, 2021 |
| HP            | EliteBook Folio 9470m       | Notebook    | [e1837571df](https://bsd-hardware.info/?probe=e1837571df) | Apr 15, 2021 |
| Shuttle       | DS10U                       | Desktop     | [491a0135a0](https://bsd-hardware.info/?probe=491a0135a0) | Apr 14, 2021 |
| Fujitsu       | D3224-A1 S26361-D3224-A1    | Desktop     | [478a874db2](https://bsd-hardware.info/?probe=478a874db2) | Apr 09, 2021 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | Desktop     | [fd03138dfc](https://bsd-hardware.info/?probe=fd03138dfc) | Apr 08, 2021 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [f8d08a1ec0](https://bsd-hardware.info/?probe=f8d08a1ec0) | Apr 08, 2021 |
| Sophos        | SG                          | Firewall    | [31f0629346](https://bsd-hardware.info/?probe=31f0629346) | Apr 07, 2021 |
| HP            | 8054                        | Desktop     | [ab00142638](https://bsd-hardware.info/?probe=ab00142638) | Apr 07, 2021 |
| BESSTAR Te... | UM250 V1.0                  | Desktop     | [ec9c1e37db](https://bsd-hardware.info/?probe=ec9c1e37db) | Apr 07, 2021 |
| Shuttle       | DS10U                       | Desktop     | [bd2ea41c3d](https://bsd-hardware.info/?probe=bd2ea41c3d) | Apr 05, 2021 |
| BESSTAR Te... | IB9                         | Desktop     | [202b90b7bf](https://bsd-hardware.info/?probe=202b90b7bf) | Apr 02, 2021 |
| HP            | EliteBook Folio 9470m       | Notebook    | [57de8a523c](https://bsd-hardware.info/?probe=57de8a523c) | Mar 29, 2021 |
| Intel         | S5000PSL                    | Server      | [411f470773](https://bsd-hardware.info/?probe=411f470773) | Mar 18, 2021 |
| PC Engines    | APU2                        | Desktop     | [e578d2eadd](https://bsd-hardware.info/?probe=e578d2eadd) | Mar 17, 2021 |
| Unknown       | Raspberry Pi                | Soc         | [e3f20f8770](https://bsd-hardware.info/?probe=e3f20f8770) | Mar 17, 2021 |
| Supermicro    | X10SRA-F                    | Server      | [14a919ab3f](https://bsd-hardware.info/?probe=14a919ab3f) | Mar 17, 2021 |
| HP            | 3397                        | Desktop     | [4e4f84fe7e](https://bsd-hardware.info/?probe=4e4f84fe7e) | Mar 17, 2021 |
| PC Engines    | APU2                        | Desktop     | [70050ec377](https://bsd-hardware.info/?probe=70050ec377) | Mar 16, 2021 |
| Unknown       | SKYBAY                      | Desktop     | [e44d5add26](https://bsd-hardware.info/?probe=e44d5add26) | Mar 16, 2021 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [50caf95a09](https://bsd-hardware.info/?probe=50caf95a09) | Mar 15, 2021 |
| Shuttle       | DS10U                       | Desktop     | [8e895a4efd](https://bsd-hardware.info/?probe=8e895a4efd) | Mar 15, 2021 |
| Shuttle       | DS10U                       | Desktop     | [8fe918937b](https://bsd-hardware.info/?probe=8fe918937b) | Mar 15, 2021 |
| Unknown       | SKYBAY                      | Desktop     | [0cae097db1](https://bsd-hardware.info/?probe=0cae097db1) | Mar 14, 2021 |
| Panasonic     | CF-30KTP48NL                | Notebook    | [119b4875e9](https://bsd-hardware.info/?probe=119b4875e9) | Mar 12, 2021 |
| HP            | ProLiant DL360 G6           | Server      | [a8b43ed394](https://bsd-hardware.info/?probe=a8b43ed394) | Mar 10, 2021 |
| Unknown       | Unknown                     | Desktop     | [155c42b4b5](https://bsd-hardware.info/?probe=155c42b4b5) | Mar 08, 2021 |
| Intel         | S5000PSL                    | Server      | [ccf8f22e7c](https://bsd-hardware.info/?probe=ccf8f22e7c) | Mar 08, 2021 |
| Unknown       | J3160-4L                    | Desktop     | [0390ce8498](https://bsd-hardware.info/?probe=0390ce8498) | Mar 06, 2021 |
| ZOTAC         | ZBOX-CI527/CI547NANO        | Mini pc     | [6ca50f8007](https://bsd-hardware.info/?probe=6ca50f8007) | Mar 06, 2021 |
| Supermicro    | X11SBA-LN4F                 | Server      | [9479fdf6dd](https://bsd-hardware.info/?probe=9479fdf6dd) | Mar 06, 2021 |
| HP            | 3397                        | Desktop     | [901050fb80](https://bsd-hardware.info/?probe=901050fb80) | Feb 26, 2021 |
| ZOTAC         | ZBOX-CI341                  | Mini pc     | [e7a255c3aa](https://bsd-hardware.info/?probe=e7a255c3aa) | Feb 20, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [1439878133](https://bsd-hardware.info/?probe=1439878133) | Feb 12, 2021 |
| ZOTAC         | ZBOX-CI341                  | Mini pc     | [ae36e30e53](https://bsd-hardware.info/?probe=ae36e30e53) | Feb 08, 2021 |
| AAEON         | UP-APL01 V0.4               | Desktop     | [8fc8c1d27e](https://bsd-hardware.info/?probe=8fc8c1d27e) | Jan 31, 2021 |
| Dell          | Vostro V131                 | Notebook    | [897616d9c8](https://bsd-hardware.info/?probe=897616d9c8) | Jan 31, 2021 |
| Supermicro    | X11SBA-FA                   | Server      | [53c6203cec](https://bsd-hardware.info/?probe=53c6203cec) | Jan 27, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [93e276fc9b](https://bsd-hardware.info/?probe=93e276fc9b) | Jan 26, 2021 |
| HP            | ProLiant DL360p Gen8        | Server      | [1e629d4c5a](https://bsd-hardware.info/?probe=1e629d4c5a) | Jan 26, 2021 |
| Dell          | Vostro V131                 | Notebook    | [630822a6a1](https://bsd-hardware.info/?probe=630822a6a1) | Jan 25, 2021 |
| Protectli     | FW4B                        | Desktop     | [0a02b075ac](https://bsd-hardware.info/?probe=0a02b075ac) | Jan 24, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [1a07b34622](https://bsd-hardware.info/?probe=1a07b34622) | Jan 22, 2021 |
| PC Engines    | apu4                        | Desktop     | [e7fcefa741](https://bsd-hardware.info/?probe=e7fcefa741) | Jan 21, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [64254af8aa](https://bsd-hardware.info/?probe=64254af8aa) | Jan 20, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [3bd99c74b9](https://bsd-hardware.info/?probe=3bd99c74b9) | Jan 20, 2021 |
| HP            | ZBook 17 G4                 | Notebook    | [40ad0612de](https://bsd-hardware.info/?probe=40ad0612de) | Jan 02, 2021 |
| Acer          | TravelMate Spin B118-RN     | Convertible | [c3acc4d372](https://bsd-hardware.info/?probe=c3acc4d372) | Dec 21, 2020 |
| Supermicro    | X10SDV-TLN4F                | Server      | [8ab697e7dd](https://bsd-hardware.info/?probe=8ab697e7dd) | Dec 15, 2020 |
| HUAWEI        | BC11HGSA0 V100R003          | Server      | [ac2c7107d3](https://bsd-hardware.info/?probe=ac2c7107d3) | Nov 19, 2020 |
| Acer          | TravelMate Spin B118-RN     | Convertible | [41c071ead3](https://bsd-hardware.info/?probe=41c071ead3) | Nov 03, 2020 |
| HP            | ProLiant SE326M1R2          | Server      | [e59d5d41a5](https://bsd-hardware.info/?probe=e59d5d41a5) | Oct 29, 2020 |
| HP            | ProLiant DL360 G6           | Server      | [e523287429](https://bsd-hardware.info/?probe=e523287429) | Oct 29, 2020 |
| Unknown       | Unknown                     | Desktop     | [e69210e453](https://bsd-hardware.info/?probe=e69210e453) | Oct 29, 2020 |
| Lenovo        | ThinkPad T410 2537AT1       | Notebook    | [4e693bfcb2](https://bsd-hardware.info/?probe=4e693bfcb2) | Oct 29, 2020 |
| ASRock        | TRX40 Taichi                | Desktop     | [dda9a512ac](https://bsd-hardware.info/?probe=dda9a512ac) | Oct 29, 2020 |
| Dell          | PowerEdge 1950              | Desktop     | [3cfcdfce6d](https://bsd-hardware.info/?probe=3cfcdfce6d) | Oct 19, 2020 |
| Dell          | PowerEdge 1950              | Desktop     | [0865193e7e](https://bsd-hardware.info/?probe=0865193e7e) | Oct 19, 2020 |
| Dell          | PowerEdge R610              | Desktop     | [2ea539bbd3](https://bsd-hardware.info/?probe=2ea539bbd3) | Oct 19, 2020 |
| PC Engines    | APU2                        | Desktop     | [2ab3051cb8](https://bsd-hardware.info/?probe=2ab3051cb8) | Oct 19, 2020 |
| PC Engines    | apu4                        | Desktop     | [f0116986e0](https://bsd-hardware.info/?probe=f0116986e0) | Oct 19, 2020 |
| Dell          | Latitude E7440              | Notebook    | [acd2735dc4](https://bsd-hardware.info/?probe=acd2735dc4) | Aug 07, 2020 |
| HP            | EliteBook 840 G3            | Notebook    | [71c35a9cc2](https://bsd-hardware.info/?probe=71c35a9cc2) | Aug 06, 2020 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [be9c9d6b01](https://bsd-hardware.info/?probe=be9c9d6b01) | Aug 01, 2020 |
| HP            | EliteBook 840 G3            | Notebook    | [6c7374d0ab](https://bsd-hardware.info/?probe=6c7374d0ab) | May 29, 2020 |
| Lenovo        | ThinkPad T60 2007J3G        | Notebook    | [ee60eb3dc8](https://bsd-hardware.info/?probe=ee60eb3dc8) | May 25, 2020 |
| Dell          | XPS 13 9360                 | Notebook    | [152f5cda4c](https://bsd-hardware.info/?probe=152f5cda4c) | May 23, 2020 |
| Fujitsu       | D3049-A1 S26361-D3049-A1... | Server      | [6cf7f9ea4b](https://bsd-hardware.info/?probe=6cf7f9ea4b) | May 23, 2020 |
| Dell          | XPS 13 9360                 | Notebook    | [d350b44569](https://bsd-hardware.info/?probe=d350b44569) | May 23, 2020 |
| Dell          | XPS 13 9360                 | Notebook    | [4199e37b56](https://bsd-hardware.info/?probe=4199e37b56) | May 23, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| OPNsense 21.7.3      | 9         | 3.15%   |
| OPNsense 22.1.1      | 8         | 2.8%    |
| OPNsense 23.7.5      | 7         | 2.45%   |
| OPNsense 21.7.7      | 7         | 2.45%   |
| OPNsense 22.4.3      | 6         | 2.1%    |
| OPNsense 21.1.4      | 6         | 2.1%    |
| OPNsense 20.7.8      | 6         | 2.1%    |
| FreeBSD 13.1         | 6         | 2.1%    |
| OPNsense 23.7.10     | 5         | 1.75%   |
| OPNsense 23.1.6      | 5         | 1.75%   |
| OPNsense 23.1.5      | 5         | 1.75%   |
| OPNsense 22.7.9      | 5         | 1.75%   |
| OPNsense 22.7.11     | 5         | 1.75%   |
| OPNsense 22.1        | 5         | 1.75%   |
| OPNsense 21.7.6      | 5         | 1.75%   |
| OPNsense 21.1.5      | 5         | 1.75%   |
| OPNsense 21.1.3      | 5         | 1.75%   |
| OPNsense 21.1.2      | 5         | 1.75%   |
| OPNsense 21.1        | 5         | 1.75%   |
| OpenBSD 6.8          | 5         | 1.75%   |
| OPNsense 23.7.9      | 4         | 1.4%    |
| OPNsense 23.7.8      | 4         | 1.4%    |
| OPNsense 23.7.12     | 4         | 1.4%    |
| OPNsense 23.1.7      | 4         | 1.4%    |
| OPNsense 23.1.11     | 4         | 1.4%    |
| OPNsense 23.1        | 4         | 1.4%    |
| OPNsense 22.7.2      | 4         | 1.4%    |
| OPNsense 22.7.10     | 4         | 1.4%    |
| OPNsense 22.1.9      | 4         | 1.4%    |
| OPNsense 22.1.7      | 4         | 1.4%    |
| OPNsense 22.1.4      | 4         | 1.4%    |
| OPNsense 21.7        | 4         | 1.4%    |
| OPNsense 21.1.8      | 4         | 1.4%    |
| FreeBSD 14.0-CURRENT | 4         | 1.4%    |
| FreeBSD 13.1-p5      | 4         | 1.4%    |
| OPNsense 24.1.1      | 3         | 1.05%   |
| OPNsense 24.1        | 3         | 1.05%   |
| OPNsense 23.7.7      | 3         | 1.05%   |
| OPNsense 23.7.1      | 3         | 1.05%   |
| OPNsense 22.1.10     | 3         | 1.05%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| OPNsense    | 157       | 74.06%  |
| FreeBSD     | 38        | 17.92%  |
| OpenBSD     | 8         | 3.77%   |
| helloSystem | 4         | 1.89%   |
| FreeNAS     | 3         | 1.42%   |
| TrueNAS     | 1         | 0.47%   |
| NetBSD      | 1         | 0.47%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 209       | 98.58%  |
| arm64 | 2         | 0.94%   |
| i386  | 1         | 0.47%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Console      | 174       | 80.93%  |
| KDE5         | 10        | 4.65%   |
| XFCE         | 7         | 3.26%   |
| helloDesktop | 6         | 2.79%   |
| MATE         | 3         | 1.4%    |
| Cinnamon     | 3         | 1.4%    |
| LXQt         | 2         | 0.93%   |
| i3           | 2         | 0.93%   |
| fvwm         | 2         | 0.93%   |
| xinitrc      | 1         | 0.47%   |
| wlroots      | 1         | 0.47%   |
| TWM          | 1         | 0.47%   |
| Openbox      | 1         | 0.47%   |
| Lumina       | 1         | 0.47%   |
| GNOME        | 1         | 0.47%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 177       | 82.71%  |
| X11     | 35        | 16.36%  |
| Wayland | 2         | 0.93%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 188       | 87.85%  |
| SDDM    | 14        | 6.54%   |
| SLiM    | 7         | 3.27%   |
| LightDM | 3         | 1.4%    |
| XDM     | 1         | 0.47%   |
| GDM     | 1         | 0.47%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 171       | 78.8%   |
| C       | 22        | 10.14%  |
| en_US   | 17        | 7.83%   |
| de_DE   | 4         | 1.84%   |
| cs_CZ   | 2         | 0.92%   |
| de_AT   | 1         | 0.46%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 187       | 88.21%  |
| BIOS | 25        | 11.79%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ufs     | 120       | 55.81%  |
| Zfs     | 85        | 39.53%  |
| Ffs     | 8         | 3.72%   |
| Cd9660  | 1         | 0.47%   |
| Unknown | 1         | 0.47%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 199       | 93.87%  |
| MBR     | 9         | 4.25%   |
| Unknown | 4         | 1.89%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Unknown                    | 26        | 12.26%  |
| Lenovo                     | 20        | 9.43%   |
| Hewlett-Packard            | 15        | 7.08%   |
| PC Engines                 | 14        | 6.6%    |
| Dell                       | 13        | 6.13%   |
| Supermicro                 | 10        | 4.72%   |
| Intel                      | 10        | 4.72%   |
| Fujitsu                    | 8         | 3.77%   |
| Deciso                     | 8         | 3.77%   |
| ZOTAC                      | 7         | 3.3%    |
| Shuttle                    | 6         | 2.83%   |
| Gigabyte Technology        | 6         | 2.83%   |
| BESSTAR Tech               | 6         | 2.83%   |
| ASUSTek Computer           | 5         | 2.36%   |
| AMI                        | 5         | 2.36%   |
| Sophos                     | 4         | 1.89%   |
| Protectli                  | 4         | 1.89%   |
| MW                         | 4         | 1.89%   |
| ASRock                     | 4         | 1.89%   |
| AWOW                       | 3         | 1.42%   |
| Techvision                 | 2         | 0.94%   |
| Secudos                    | 2         | 0.94%   |
| MSI                        | 2         | 0.94%   |
| IceWhale Technology        | 2         | 0.94%   |
| Hardkernel                 | 2         | 0.94%   |
| Biostar                    | 2         | 0.94%   |
| Barracuda Networks         | 2         | 0.94%   |
| Apple                      | 2         | 0.94%   |
| AAEON                      | 2         | 0.94%   |
| Winston Marriot            | 1         | 0.47%   |
| TUXEDO                     | 1         | 0.47%   |
| Silicom                    | 1         | 0.47%   |
| ShenZhen MinWin Technology | 1         | 0.47%   |
| SeeedStudio                | 1         | 0.47%   |
| Seeed Studio               | 1         | 0.47%   |
| Raspberry Pi Foundation    | 1         | 0.47%   |
| Purism                     | 1         | 0.47%   |
| Panasonic                  | 1         | 0.47%   |
| NEXCOM                     | 1         | 0.47%   |
| IP3 Tech                   | 1         | 0.47%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                             | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Unknown                                          | 29        | 13.68%  |
| PC Engines apu4                                  | 7         | 3.3%    |
| PC Engines APU2                                  | 7         | 3.3%    |
| Deciso Netboard A10 GEN2 Model G                 | 6         | 2.83%   |
| Supermicro Super Server                          | 4         | 1.89%   |
| MW GMLK-2_5G4L                                   | 4         | 1.89%   |
| Sophos SG                                        | 3         | 1.42%   |
| Protectli FW4B                                   | 3         | 1.42%   |
| Intel Q3XXG4-P V1.0                              | 3         | 1.42%   |
| ZOTAC ZBOX-CI341                                 | 2         | 0.94%   |
| ZOTAC ZBOX-CI323NANO                             | 2         | 0.94%   |
| Techvision TVI7309X                              | 2         | 0.94%   |
| Shuttle DS10U                                    | 2         | 0.94%   |
| Shuttle DH170                                    | 2         | 0.94%   |
| Lenovo ThinkPad T490 20N2CTO1WW                  | 2         | 0.94%   |
| IceWhale ZimaBoard 832 ZMB                       | 2         | 0.94%   |
| HP ProLiant DL360 G6                             | 2         | 0.94%   |
| HP EliteBook 850 G7 Notebook PC                  | 2         | 0.94%   |
| Hardkernel ODROID-H2                             | 2         | 0.94%   |
| Fujitsu FUTRO S720                               | 2         | 0.94%   |
| Fujitsu ESPRIMO C720                             | 2         | 0.94%   |
| Dell OptiPlex 5040                               | 2         | 0.94%   |
| AWOW AK34                                        | 2         | 0.94%   |
| AMI LES compact 4L                               | 2         | 0.94%   |
| AMI Aptio CRB                                    | 2         | 0.94%   |
| AAEON UP-APL01                                   | 2         | 0.94%   |
| ZOTAC ZBOXNANO-ID63/ID64/ID65                    | 1         | 0.47%   |
| ZOTAC ZBOX-CI527/CI547NANO                       | 1         | 0.47%   |
| Winston Marriot PICO PC  PICOPC                  | 1         | 0.47%   |
| TUXEDO InfinityBook Pro 14 Gen6                  | 1         | 0.47%   |
| Supermicro X10SLL-F                              | 1         | 0.47%   |
| Supermicro SYS-E301-9D-8CN8TP                    | 1         | 0.47%   |
| Supermicro IXWS-733TQ-665B-IXN                   | 1         | 0.47%   |
| Supermicro A1SAi                                 | 1         | 0.47%   |
| Supermicro 1HE Intel Single-CPU RI1102D-F Server | 1         | 0.47%   |
| Supermicro 1HE Intel Single-CPU RI1101H-F Server | 1         | 0.47%   |
| Sophos XG                                        | 1         | 0.47%   |
| Silicom Minnowboard Turbot D0/D1 PLATFORM        | 1         | 0.47%   |
| Shuttle DS61                                     | 1         | 0.47%   |
| Shuttle DS437                                    | 1         | 0.47%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Unknown                      | 29        | 13.68%  |
| Lenovo ThinkPad              | 12        | 5.66%   |
| PC Engines apu4              | 7         | 3.3%    |
| PC Engines APU2              | 7         | 3.3%    |
| Dell OptiPlex                | 6         | 2.83%   |
| Deciso Netboard              | 6         | 2.83%   |
| HP ProLiant                  | 5         | 2.36%   |
| Supermicro Super             | 4         | 1.89%   |
| MW GMLK-2                    | 4         | 1.89%   |
| HP EliteBook                 | 4         | 1.89%   |
| Sophos SG                    | 3         | 1.42%   |
| Protectli FW4B               | 3         | 1.42%   |
| Lenovo ThinkCentre           | 3         | 1.42%   |
| Intel Q3XXG4-P               | 3         | 1.42%   |
| Fujitsu FUTRO                | 3         | 1.42%   |
| Fujitsu ESPRIMO              | 3         | 1.42%   |
| ZOTAC ZBOX-CI341             | 2         | 0.94%   |
| ZOTAC ZBOX-CI323NANO         | 2         | 0.94%   |
| Techvision TVI7309X          | 2         | 0.94%   |
| Supermicro 1HE               | 2         | 0.94%   |
| Shuttle DS10U                | 2         | 0.94%   |
| Shuttle DH170                | 2         | 0.94%   |
| Lenovo IdeaPad               | 2         | 0.94%   |
| Lenovo IdeaCentre            | 2         | 0.94%   |
| IceWhale ZimaBoard           | 2         | 0.94%   |
| HP Compaq                    | 2         | 0.94%   |
| Hardkernel ODROID-H2         | 2         | 0.94%   |
| Dell Precision               | 2         | 0.94%   |
| Dell PowerEdge               | 2         | 0.94%   |
| Barracuda Networks Barracuda | 2         | 0.94%   |
| AWOW AK34                    | 2         | 0.94%   |
| ASUS 1HE                     | 2         | 0.94%   |
| AMI LES                      | 2         | 0.94%   |
| AMI Aptio                    | 2         | 0.94%   |
| AAEON UP-APL01               | 2         | 0.94%   |
| ZOTAC ZBOXNANO-ID63          | 1         | 0.47%   |
| ZOTAC ZBOX-CI527             | 1         | 0.47%   |
| Winston Marriot PICO         | 1         | 0.47%   |
| TUXEDO InfinityBook          | 1         | 0.47%   |
| Supermicro X10SLL-F          | 1         | 0.47%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 28        | 13.21%  |
| 2018    | 27        | 12.74%  |
| 2017    | 24        | 11.32%  |
| 2020    | 19        | 8.96%   |
| 2016    | 19        | 8.96%   |
| 2019    | 18        | 8.49%   |
| 2022    | 16        | 7.55%   |
| 2015    | 10        | 4.72%   |
| 2014    | 10        | 4.72%   |
| 2023    | 8         | 3.77%   |
| 2013    | 7         | 3.3%    |
| 2011    | 7         | 3.3%    |
| 2010    | 6         | 2.83%   |
| 2012    | 4         | 1.89%   |
| 2009    | 3         | 1.42%   |
| Unknown | 3         | 1.42%   |
| 2024    | 1         | 0.47%   |
| 2007    | 1         | 0.47%   |
| 2006    | 1         | 0.47%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 132       | 62.26%  |
| Notebook       | 34        | 16.04%  |
| Mini pc        | 19        | 8.96%   |
| Server         | 17        | 8.02%   |
| Firewall       | 6         | 2.83%   |
| System on chip | 2         | 0.94%   |
| Convertible    | 1         | 0.47%   |
| All in one     | 1         | 0.47%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 189       | 89.15%  |
| Yes  | 23        | 10.85%  |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 87        | 40.09%  |
| 16.01-24.0      | 46        | 21.2%   |
| 4.01-8.0        | 43        | 19.82%  |
| 32.01-64.0      | 16        | 7.37%   |
| 2.01-3.0        | 9         | 4.15%   |
| 64.01-256.0     | 6         | 2.76%   |
| 3.01-4.0        | 4         | 1.84%   |
| More than 256.0 | 3         | 1.38%   |
| 24.01-32.0      | 2         | 0.92%   |
| 1.01-2.0        | 1         | 0.46%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 0.01-0.5    | 116       | 53.21%  |
| 0.51-1.0    | 64        | 29.36%  |
| 1.01-2.0    | 22        | 10.09%  |
| 2.01-3.0    | 5         | 2.29%   |
| 4.01-8.0    | 3         | 1.38%   |
| 32.01-64.0  | 3         | 1.38%   |
| 3.01-4.0    | 1         | 0.46%   |
| 64.01-256.0 | 1         | 0.46%   |
| 16.01-24.0  | 1         | 0.46%   |
| 0           | 1         | 0.46%   |
| Unknown     | 1         | 0.46%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 168       | 77.42%  |
| 2      | 22        | 10.14%  |
| 0      | 14        | 6.45%   |
| 4      | 4         | 1.84%   |
| 3      | 4         | 1.84%   |
| 17     | 1         | 0.46%   |
| 15     | 1         | 0.46%   |
| 13     | 1         | 0.46%   |
| 7      | 1         | 0.46%   |
| 6      | 1         | 0.46%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 194       | 90.23%  |
| Yes       | 21        | 9.77%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 204       | 96.23%  |
| No        | 8         | 3.77%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 143       | 66.82%  |
| Yes       | 71        | 33.18%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 164       | 76.64%  |
| Yes       | 50        | 23.36%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Austria | 212       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                            | Computers | Percent |
|---------------------------------|-----------|---------|
| Vienna                          | 107       | 44.58%  |
| Graz                            | 19        | 7.92%   |
| Linz                            | 7         | 2.92%   |
| Innsbruck                       | 6         | 2.5%    |
| Wels                            | 5         | 2.08%   |
| Salzburg                        | 4         | 1.67%   |
| Feldkirch                       | 4         | 1.67%   |
| Stockerau                       | 2         | 0.83%   |
| Sankt Veit an der Glan          | 2         | 0.83%   |
| Rankweil                        | 2         | 0.83%   |
| Neulengbach                     | 2         | 0.83%   |
| Leoben                          | 2         | 0.83%   |
| Krems                           | 2         | 0.83%   |
| Klagenfurt                      | 2         | 0.83%   |
| Hittisau                        | 2         | 0.83%   |
| Bruck an der Mur                | 2         | 0.83%   |
| Atzenbrugg                      | 2         | 0.83%   |
| Zwettl Stadt                    | 1         | 0.42%   |
| Weidlingbach                    | 1         | 0.42%   |
| Vorchdorf                       | 1         | 0.42%   |
| Voggenberg                      | 1         | 0.42%   |
| Tulln                           | 1         | 0.42%   |
| Trausdorf an der Wulka          | 1         | 0.42%   |
| Tragwein                        | 1         | 0.42%   |
| Steyr                           | 1         | 0.42%   |
| Steinhaus                       | 1         | 0.42%   |
| Spittal an der Drau             | 1         | 0.42%   |
| Sieghartskirchen                | 1         | 0.42%   |
| Siegendorf im Burgenland        | 1         | 0.42%   |
| Seyring                         | 1         | 0.42%   |
| Schwechat                       | 1         | 0.42%   |
| Schörfling                     | 1         | 0.42%   |
| Schluesslberg                   | 1         | 0.42%   |
| Sankt PГ¶lten                 | 1         | 0.42%   |
| Sankt PÃ¶lten                 | 1         | 0.42%   |
| Sankt Pantaleon                 | 1         | 0.42%   |
| Sankt Margarethen im Burgenland | 1         | 0.42%   |
| Sankt Johann in Tirol           | 1         | 0.42%   |
| Rottenmann                      | 1         | 0.42%   |
| Pusarnitz                       | 1         | 0.42%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 38        | 59     | 15.83%  |
| Transcend           | 32        | 42     | 13.33%  |
| Kingston            | 22        | 34     | 9.17%   |
| WDC                 | 19        | 43     | 7.92%   |
| Crucial             | 17        | 25     | 7.08%   |
| Intel               | 15        | 21     | 6.25%   |
| Seagate             | 9         | 30     | 3.75%   |
| SanDisk             | 8         | 14     | 3.33%   |
| Micron Technology   | 5         | 9      | 2.08%   |
| Hoodisk             | 5         | 6      | 2.08%   |
| HGST                | 5         | 13     | 2.08%   |
| Phison              | 4         | 5      | 1.67%   |
| FORESEE             | 4         | 5      | 1.67%   |
| China               | 4         | 6      | 1.67%   |
| A-DATA Technology   | 4         | 8      | 1.67%   |
| Toshiba             | 3         | 6      | 1.25%   |
| SK hynix            | 3         | 6      | 1.25%   |
| Silicon Motion      | 3         | 3      | 1.25%   |
| Patriot             | 3         | 5      | 1.25%   |
| OCZ                 | 2         | 2      | 0.83%   |
| Innodisk            | 2         | 3      | 0.83%   |
| Hitachi             | 2         | 2      | 0.83%   |
| Hewlett-Packard     | 2         | 2      | 0.83%   |
| Dogfish             | 2         | 2      | 0.83%   |
| Dell                | 2         | 2      | 0.83%   |
| Corsair             | 2         | 5      | 0.83%   |
| BORY                | 2         | 5      | 0.83%   |
| ATP                 | 2         | 2      | 0.83%   |
| Apple               | 2         | 2      | 0.83%   |
| AirDisk             | 2         | 2      | 0.83%   |
| VICKTER             | 1         | 1      | 0.42%   |
| Verbatim            | 1         | 1      | 0.42%   |
| SYNOLOGY            | 1         | 1      | 0.42%   |
| SPCC                | 1         | 2      | 0.42%   |
| Plextor             | 1         | 1      | 0.42%   |
| LITEONIT            | 1         | 1      | 0.42%   |
| Leven               | 1         | 2      | 0.42%   |
| Kston               | 1         | 1      | 0.42%   |
| KingSpec            | 1         | 1      | 0.42%   |
| KeepData            | 1         | 1      | 0.42%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Samsung SSD 840 EVO 250GB               | 7         | 2.69%   |
| Transcend TS128GMSA370 128GB            | 6         | 2.31%   |
| Transcend TS128GMSA230S 128GB           | 5         | 1.92%   |
| Kingston SKC600MS256G 256GB             | 4         | 1.54%   |
| SanDisk SSD PLUS 120GB                  | 3         | 1.15%   |
| Kingston SUV500MS120G 120GB             | 3         | 1.15%   |
| Kingston SA400S37240G 240GB             | 3         | 1.15%   |
| Intel SSDSC2KW128G8 128GB               | 3         | 1.15%   |
| FORESEE 128GB SSD                       | 3         | 1.15%   |
| Crucial CT240BX500SSD1 240GB            | 3         | 1.15%   |
| Crucial CT120BX500SSD1 120GB            | 3         | 1.15%   |
| WDC WD60EFRX-68L0BN1 6TB                | 2         | 0.77%   |
| WDC WD40EFRX-68N32N0 4TB                | 2         | 0.77%   |
| Transcend TS64GMSA230S 64GB             | 2         | 0.77%   |
| Transcend TS256GMTS430S 256GB           | 2         | 0.77%   |
| Transcend TS256GMTE652T2 256GB          | 2         | 0.77%   |
| Transcend TS256GMSA230S 256GB           | 2         | 0.77%   |
| Transcend TS240GSSD220S 240GB           | 2         | 0.77%   |
| Transcend TS16GMSA370 16GB              | 2         | 0.77%   |
| Transcend TS128GMTS830S 128GB           | 2         | 0.77%   |
| SK hynix BC511 HFM512GDJTNI-82A0A 512GB | 2         | 0.77%   |
| Silicon Motion P10D 1TB                 | 2         | 0.77%   |
| SanDisk SSD PLUS 240GB                  | 2         | 0.77%   |
| Samsung SSD 970 EVO Plus 250GB          | 2         | 0.77%   |
| Samsung SSD 860 EVO 250GB               | 2         | 0.77%   |
| Samsung SSD 850 EVO 250GB               | 2         | 0.77%   |
| Samsung SSD 830 Series 256GB            | 2         | 0.77%   |
| Samsung MZALQ512HBLU-00BL1 512GB        | 2         | 0.77%   |
| Phison SATA SSD 16GB                    | 2         | 0.77%   |
| Kingston SA400S37120G 120GB             | 2         | 0.77%   |
| Intel SSDPEKKF512G8L 512GB              | 2         | 0.77%   |
| Hoodisk SSD 64GB                        | 2         | 0.77%   |
| Hoodisk SSD 128GB                       | 2         | 0.77%   |
| HP RAID 1(1+0) 73GB                     | 2         | 0.77%   |
| Crucial CT500MX500SSD1 500GB            | 2         | 0.77%   |
| Crucial CT250P2SSD8 250GB               | 2         | 0.77%   |
| Crucial CT250MX500SSD1 250GB            | 2         | 0.77%   |
| China SATA SSD 64GB                     | 2         | 0.77%   |
| BORY M500 128G                          | 2         | 0.77%   |
| AirDisk 128GB SSD                       | 2         | 0.77%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 16        | 37     | 39.02%  |
| Seagate             | 8         | 23     | 19.51%  |
| HGST                | 5         | 13     | 12.2%   |
| Toshiba             | 3         | 6      | 7.32%   |
| Hitachi             | 2         | 2      | 4.88%   |
| Hewlett-Packard     | 2         | 2      | 4.88%   |
| Dell                | 2         | 2      | 4.88%   |
| SYNOLOGY            | 1         | 1      | 2.44%   |
| Samsung Electronics | 1         | 1      | 2.44%   |
| Apple               | 1         | 1      | 2.44%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Transcend           | 29        | 37     | 18.35%  |
| Samsung Electronics | 25        | 37     | 15.82%  |
| Kingston            | 20        | 32     | 12.66%  |
| Crucial             | 14        | 22     | 8.86%   |
| Intel               | 10        | 13     | 6.33%   |
| SanDisk             | 8         | 14     | 5.06%   |
| Hoodisk             | 5         | 6      | 3.16%   |
| Micron Technology   | 4         | 8      | 2.53%   |
| FORESEE             | 4         | 5      | 2.53%   |
| China               | 4         | 6      | 2.53%   |
| WDC                 | 3         | 4      | 1.9%    |
| Phison              | 3         | 4      | 1.9%    |
| OCZ                 | 2         | 2      | 1.27%   |
| Innodisk            | 2         | 3      | 1.27%   |
| Dogfish             | 2         | 2      | 1.27%   |
| BORY                | 2         | 5      | 1.27%   |
| AirDisk             | 2         | 2      | 1.27%   |
| A-DATA Technology   | 2         | 3      | 1.27%   |
| VICKTER             | 1         | 1      | 0.63%   |
| Verbatim            | 1         | 1      | 0.63%   |
| SPCC                | 1         | 2      | 0.63%   |
| SK hynix            | 1         | 4      | 0.63%   |
| Seagate             | 1         | 7      | 0.63%   |
| Patriot             | 1         | 1      | 0.63%   |
| LITEONIT            | 1         | 1      | 0.63%   |
| Leven               | 1         | 2      | 0.63%   |
| Kston               | 1         | 1      | 0.63%   |
| KingSpec            | 1         | 1      | 0.63%   |
| KeepData            | 1         | 1      | 0.63%   |
| Intenso             | 1         | 1      | 0.63%   |
| GOODRAM             | 1         | 1      | 0.63%   |
| BR                  | 1         | 1      | 0.63%   |
| BIWIN               | 1         | 1      | 0.63%   |
| ATP                 | 1         | 1      | 0.63%   |
| Apple               | 1         | 1      | 0.63%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 147       | 233    | 65.63%  |
| NVMe | 42        | 66     | 18.75%  |
| HDD  | 35        | 88     | 15.63%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 165       | 321    | 79.71%  |
| NVMe | 42        | 66     | 20.29%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 151       | 243    | 81.62%  |
| 0.51-1.0   | 15        | 20     | 8.11%   |
| 4.01-10.0  | 7         | 28     | 3.78%   |
| 1.01-2.0   | 6         | 14     | 3.24%   |
| 3.01-4.0   | 4         | 13     | 2.16%   |
| 10.01-20.0 | 2         | 3      | 1.08%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 101-250    | 113       | 51.83%  |
| 251-500    | 38        | 17.43%  |
| 51-100     | 23        | 10.55%  |
| 21-50      | 21        | 9.63%   |
| 1-20       | 14        | 6.42%   |
| 501-1000   | 8         | 3.67%   |
| 1001-2000  | 1         | 0.46%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1-20     | 204       | 93.58%  |
| 21-50    | 9         | 4.13%   |
| 101-250  | 2         | 0.92%   |
| 251-500  | 1         | 0.46%   |
| 501-1000 | 1         | 0.46%   |
| 51-100   | 1         | 0.46%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| WDC WD60EFRX-68L0BN1 6TB                     | 1         | 1      | 5.88%   |
| WDC WD3200BEVT-22ZCT0 320GB                  | 1         | 1      | 5.88%   |
| WDC WD1600BEVS-00UST0 160GB                  | 1         | 1      | 5.88%   |
| WDC WD1600BEKT-08PVMT1 160GB                 | 1         | 2      | 5.88%   |
| SK hynix SC308 SATA 128GB                    | 1         | 4      | 5.88%   |
| Seagate ST9500325AS 500GB                    | 1         | 1      | 5.88%   |
| SanDisk SSD PLUS 240GB                       | 1         | 1      | 5.88%   |
| Samsung Electronics MZ7PA128HMCD-010H1 128GB | 1         | 1      | 5.88%   |
| OCZ AGILITY3 120GB                           | 1         | 1      | 5.88%   |
| Micron Technology 1100_MTFDDAV256TBN 64GB    | 1         | 2      | 5.88%   |
| Intel SSDSCKKF256G8H 256GB                   | 1         | 2      | 5.88%   |
| Intel SSDPEKKW128G7 128GB                    | 1         | 1      | 5.88%   |
| Hitachi HTS541040G9SA00 40GB                 | 1         | 1      | 5.88%   |
| Hitachi HDS721050CLA660 500GB                | 1         | 1      | 5.88%   |
| HGST HTS725050A7E630 500GB                   | 1         | 6      | 5.88%   |
| A-DATA Technology SU630 240GB                | 1         | 1      | 5.88%   |
| A-DATA Technology ASU800SS-128GT 128GB       | 1         | 1      | 5.88%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 4         | 5      | 23.53%  |
| Intel               | 2         | 3      | 11.76%  |
| Hitachi             | 2         | 2      | 11.76%  |
| A-DATA Technology   | 2         | 2      | 11.76%  |
| SK hynix            | 1         | 4      | 5.88%   |
| Seagate             | 1         | 1      | 5.88%   |
| SanDisk             | 1         | 1      | 5.88%   |
| Samsung Electronics | 1         | 1      | 5.88%   |
| OCZ                 | 1         | 1      | 5.88%   |
| Micron Technology   | 1         | 2      | 5.88%   |
| HGST                | 1         | 6      | 5.88%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 4         | 5      | 50%     |
| Hitachi | 2         | 2      | 25%     |
| Seagate | 1         | 1      | 12.5%   |
| HGST    | 1         | 6      | 12.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 8         | 13     | 47.06%  |
| HDD  | 8         | 14     | 47.06%  |
| NVMe | 1         | 1      | 5.88%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                     | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Intel SSDPEKKW128G7 128GB | 1         | 1      | 50%     |
| Crucial CT250P2SSD8 250GB | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Intel   | 1         | 1      | 50%     |
| Crucial | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 185       | 351    | 89.37%  |
| Malfunc  | 15        | 28     | 7.25%   |
| Detected | 5         | 6      | 2.42%   |
| Failed   | 2         | 2      | 0.97%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 167       | 65.49%  |
| AMD                         | 32        | 12.55%  |
| Samsung Electronics         | 13        | 5.1%    |
| Silicon Motion              | 5         | 1.96%   |
| Broadcom / LSI              | 5         | 1.96%   |
| Phison Electronics          | 4         | 1.57%   |
| Hewlett-Packard             | 4         | 1.57%   |
| Micron/Crucial Technology   | 3         | 1.18%   |
| Transcend                   | 2         | 0.78%   |
| SK hynix                    | 2         | 0.78%   |
| SanDisk                     | 2         | 0.78%   |
| Marvell Technology Group    | 2         | 0.78%   |
| Lite-On Technology          | 2         | 0.78%   |
| Kingston Technology Company | 2         | 0.78%   |
| ASMedia Technology          | 2         | 0.78%   |
| Toshiba                     | 1         | 0.39%   |
| Realtek Semiconductor       | 1         | 0.39%   |
| Micron Technology           | 1         | 0.39%   |
| MAXIO Technology (Hangzhou) | 1         | 0.39%   |
| Dell                        | 1         | 0.39%   |
| ATP ELECTRONICS             | 1         | 0.39%   |
| Apple                       | 1         | 0.39%   |
| ADATA Technology            | 1         | 0.39%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 25        | 9.09%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 16        | 5.82%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 14        | 5.09%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 13        | 4.73%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 12        | 4.36%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 10        | 3.64%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 8         | 2.91%   |
| AMD FCH SATA Controller [IDE mode]                                               | 8         | 2.91%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 6         | 2.18%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 6         | 2.18%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 6         | 2.18%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 5         | 1.82%   |
| Intel unknown                                                                    | 5         | 1.82%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 5         | 1.82%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 5         | 1.82%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 5         | 1.82%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 4         | 1.45%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 4         | 1.45%   |
| Intel Atom Processor C3000 Series SATA Controller 0                              | 4         | 1.45%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 4         | 1.45%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 3         | 1.09%   |
| Intel Comet Lake SATA AHCI Controller                                            | 3         | 1.09%   |
| Intel Atom processor C2000 AHCI SATA3 Controller                                 | 3         | 1.09%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 3         | 1.09%   |
| HP Smart Array G6 controllers                                                    | 3         | 1.09%   |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                              | 3         | 1.09%   |
| Transcend NVMe PCIe SSD 110S/112S/120S/MTE300S/MTE400S/MTE652T2 (DRAM-less)      | 2         | 0.73%   |
| SK hynix BC511 NVMe SSD                                                          | 2         | 0.73%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                              | 2         | 0.73%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)             | 2         | 0.73%   |
| Lite-On M8Pe Series NVMe SSD                                                     | 2         | 0.73%   |
| Intel Tiger Lake-LP SATA Controller                                              | 2         | 0.73%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                                 | 2         | 0.73%   |
| Intel SSD 600P Series                                                            | 2         | 0.73%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 2         | 0.73%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                    | 2         | 0.73%   |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                     | 2         | 0.73%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 2         | 0.73%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 2         | 0.73%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 2         | 0.73%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 178       | 68.46%  |
| NVMe | 47        | 18.08%  |
| IDE  | 21        | 8.08%   |
| RAID | 8         | 3.08%   |
| SAS  | 4         | 1.54%   |
| SCSI | 2         | 0.77%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 174       | 82.08%  |
| AMD     | 36        | 16.98%  |
| ARM     | 1         | 0.47%   |
| Unknown | 1         | 0.47%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| AMD GX-412TC SOC                                | 14        | 6.6%    |
| Intel Celeron CPU J3160 @ 1.60GHz               | 9         | 4.25%   |
| Intel Celeron J4125 CPU @ 2.00GHz               | 7         | 3.3%    |
| Intel Celeron N5105 @ 2.00GHz                   | 6         | 2.83%   |
| AMD GX-420MC SOC                                | 6         | 2.83%   |
| Intel N100                                      | 5         | 2.36%   |
| Intel Celeron CPU N3450 @ 1.10GHz               | 4         | 1.89%   |
| Intel Xeon CPU E5620 @ 2.40GHz                  | 3         | 1.42%   |
| Intel Core i5-7200U CPU @ 2.50GHz               | 3         | 1.42%   |
| Intel Core i5-4200U CPU @ 1.60GHz               | 3         | 1.42%   |
| Intel Celeron J4105 CPU @ 1.50GHz               | 3         | 1.42%   |
| Intel Celeron CPU N3150 @ 1.60GHz               | 3         | 1.42%   |
| Intel Atom CPU C3558 @ 2.20GHz                  | 3         | 1.42%   |
| AMD Ryzen 5 5500U with Radeon Graphics          | 3         | 1.42%   |
| Intel Pentium CPU N4200 @ 1.10GHz               | 2         | 0.94%   |
| Intel Pentium CPU G3220 @ 3.00GHz               | 2         | 0.94%   |
| Intel Core i7-8665U CPU @ 1.90GHz               | 2         | 0.94%   |
| Intel Core i7-8565U CPU @ 1.80GHz               | 2         | 0.94%   |
| Intel Core i5-6600 CPU @ 3.30GHz                | 2         | 0.94%   |
| Intel Core i5-6500 CPU @ 3.20GHz                | 2         | 0.94%   |
| Intel Core i5-6400 CPU @ 2.70GHz                | 2         | 0.94%   |
| Intel Core i5-2400 CPU @ 3.10GHz                | 2         | 0.94%   |
| Intel Core i5-10310U CPU @ 1.70GHz              | 2         | 0.94%   |
| Intel Core i5-10210U CPU @ 1.60GHz              | 2         | 0.94%   |
| Intel Core i5 CPU M 520 @ 2.40GHz               | 2         | 0.94%   |
| Intel Core i3-6100T CPU @ 3.20GHz               | 2         | 0.94%   |
| Intel Core i3-4130 CPU @ 3.40GHz                | 2         | 0.94%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz              | 2         | 0.94%   |
| Intel Celeron N4100 CPU @ 1.10GHz               | 2         | 0.94%   |
| Intel Celeron CPU J1900 @ 1.99GHz               | 2         | 0.94%   |
| Intel Atom CPU E3845 @ 1.91GHz                  | 2         | 0.94%   |
| AMD Ryzen Embedded V1500B                       | 2         | 0.94%   |
| AMD Ryzen 5 PRO 2500U w/ Radeon Vega Mobile Gfx | 2         | 0.94%   |
| AMD GX-217GA SOC with Radeon HD Graphics        | 2         | 0.94%   |
| Intel Xeon E-2236 CPU @ 3.40GHz                 | 1         | 0.47%   |
| Intel Xeon E-2136 CPU @ 3.30GHz                 | 1         | 0.47%   |
| Intel Xeon D-2146NT CPU @ 2.30GHz               | 1         | 0.47%   |
| Intel Xeon D-2123IT CPU @ 2.20GHz               | 1         | 0.47%   |
| Intel Xeon CPU L5640 @ 2.27GHz                  | 1         | 0.47%   |
| Intel Xeon CPU E5540 @ 2.53GHz                  | 1         | 0.47%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Celeron           | 49        | 23.11%  |
| Intel Core i5           | 40        | 18.87%  |
| AMD GX                  | 22        | 10.38%  |
| Intel Xeon              | 18        | 8.49%   |
| Intel Core i7           | 17        | 8.02%   |
| Intel Core i3           | 15        | 7.08%   |
| Other                   | 11        | 5.19%   |
| Intel Atom              | 11        | 5.19%   |
| Intel Pentium           | 7         | 3.3%    |
| Intel Core 2 Duo        | 3         | 1.42%   |
| AMD Ryzen 5             | 3         | 1.42%   |
| AMD Ryzen Embedded      | 2         | 0.94%   |
| AMD Ryzen 7             | 2         | 0.94%   |
| AMD Ryzen 5 PRO         | 2         | 0.94%   |
| Intel Pentium Silver    | 1         | 0.47%   |
| Intel Pentium Dual-Core | 1         | 0.47%   |
| Intel Pentium 4         | 1         | 0.47%   |
| Intel Genuine           | 1         | 0.47%   |
| Intel Core 2            | 1         | 0.47%   |
| ARM Cortex              | 1         | 0.47%   |
| AMD Ryzen Threadripper  | 1         | 0.47%   |
| AMD Opteron             | 1         | 0.47%   |
| AMD FX                  | 1         | 0.47%   |
| AMD Athlon              | 1         | 0.47%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 124       | 58.49%  |
| 2       | 54        | 25.47%  |
| 8       | 13        | 6.13%   |
| 6       | 6         | 2.83%   |
| Unknown | 6         | 2.83%   |
| 12      | 5         | 2.36%   |
| 64      | 1         | 0.47%   |
| 16      | 1         | 0.47%   |
| 14      | 1         | 0.47%   |
| 1       | 1         | 0.47%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 199       | 93.87%  |
| 2       | 7         | 3.3%    |
| Unknown | 6         | 2.83%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 133       | 62.74%  |
| 2       | 72        | 33.96%  |
| Unknown | 7         | 3.3%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 30        | 14.15%  |
| Silvermont    | 24        | 11.32%  |
| Puma          | 20        | 9.43%   |
| Unknown       | 18        | 8.49%   |
| Haswell       | 16        | 7.55%   |
| Skylake       | 15        | 7.08%   |
| Goldmont plus | 14        | 6.6%    |
| Goldmont      | 14        | 6.6%    |
| IvyBridge     | 10        | 4.72%   |
| SandyBridge   | 9         | 4.25%   |
| Westmere      | 7         | 3.3%    |
| Zen           | 6         | 2.83%   |
| Broadwell     | 6         | 2.83%   |
| Penryn        | 5         | 2.36%   |
| TigerLake     | 3         | 1.42%   |
| Excavator     | 3         | 1.42%   |
| Jaguar        | 2         | 0.94%   |
| IceLake       | 2         | 0.94%   |
| Core          | 2         | 0.94%   |
| CometLake     | 2         | 0.94%   |
| Zen+          | 1         | 0.47%   |
| Zen 2         | 1         | 0.47%   |
| NetBurst      | 1         | 0.47%   |
| Nehalem       | 1         | 0.47%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 143       | 74.48%  |
| AMD                        | 20        | 10.42%  |
| ASPEED Technology          | 16        | 8.33%   |
| Nvidia                     | 8         | 4.17%   |
| Matrox Electronics Systems | 4         | 2.08%   |
| Huawei Technologies        | 1         | 0.52%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 16        | 8.29%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 16        | 8.29%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 13        | 6.74%   |
| Intel HD Graphics 530                                                                    | 9         | 4.66%   |
| Intel HD Graphics 500                                                                    | 8         | 4.15%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 7         | 3.63%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 6         | 3.11%   |
| Intel JasperLake [UHD Graphics]                                                          | 6         | 3.11%   |
| Intel Alder Lake-N [UHD Graphics]                                                        | 6         | 3.11%   |
| AMD ES1000                                                                               | 6         | 3.11%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 2.59%   |
| Intel HD Graphics 620                                                                    | 5         | 2.59%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 2.59%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 5         | 2.59%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 2.59%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 4         | 2.07%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 3         | 1.55%   |
| Intel UHD Graphics 620                                                                   | 3         | 1.55%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 1.55%   |
| Intel HD Graphics 630                                                                    | 3         | 1.55%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 1.55%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 3         | 1.55%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 1.55%   |
| AMD Lucienne                                                                             | 3         | 1.55%   |
| Matrox Electronics Systems MGA G200EH                                                    | 2         | 1.04%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.04%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 2         | 1.04%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 1.04%   |
| Intel HD Graphics 510                                                                    | 2         | 1.04%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2         | 1.04%   |
| Intel Apollo Lake [HD Graphics 505]                                                      | 2         | 1.04%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 2         | 1.04%   |
| AMD Kabini [Radeon HD 8280E]                                                             | 2         | 1.04%   |
| Nvidia NV28 [GeForce4 Ti 4200 AGP 8x]                                                    | 1         | 0.52%   |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                                    | 1         | 0.52%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 1         | 0.52%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1         | 0.52%   |
| Nvidia GP104GLM [Quadro P4000 Mobile]                                                    | 1         | 0.52%   |
| Nvidia GP104GL [Tesla P4]                                                                | 1         | 0.52%   |
| Nvidia GM107M [GeForce GTX 860M]                                                         | 1         | 0.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| 1 x Intel                    | 136       | 64.15%  |
| Other                        | 26        | 12.26%  |
| 1 x AMD                      | 19        | 8.96%   |
| 1 x ASPEED                   | 13        | 6.13%   |
| 1 x Nvidia                   | 5         | 2.36%   |
| 1 x Matrox                   | 4         | 1.89%   |
| 2 x Intel                    | 3         | 1.42%   |
| Intel + ASPEED               | 2         | 0.94%   |
| Nvidia + Huawei Technologies | 1         | 0.47%   |
| Nvidia + ASPEED              | 1         | 0.47%   |
| Intel + Nvidia               | 1         | 0.47%   |
| Intel + AMD                  | 1         | 0.47%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 182       | 85.85%  |
| Unknown     | 26        | 12.26%  |
| Proprietary | 4         | 1.89%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 205       | 95.79%  |
| 0.51-1.0   | 3         | 1.4%    |
| 3.01-4.0   | 2         | 0.93%   |
| 1.01-2.0   | 2         | 0.93%   |
| 7.01-8.0   | 1         | 0.47%   |
| 0.01-0.5   | 1         | 0.47%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| AU Optronics        | 5         | 15.15%  |
| Samsung Electronics | 4         | 12.12%  |
| Lenovo              | 4         | 12.12%  |
| Philips             | 3         | 9.09%   |
| LG Display          | 3         | 9.09%   |
| Dell                | 3         | 9.09%   |
| Chimei Innolux      | 3         | 9.09%   |
| BOE                 | 3         | 9.09%   |
| Unknown             | 1         | 3.03%   |
| PANDA               | 1         | 3.03%   |
| Medion              | 1         | 3.03%   |
| BenQ                | 1         | 3.03%   |
| Apple               | 1         | 3.03%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics C34J79x SAM0F1E 3440x1440 800x330mm 34.1-inch    | 2         | 5.88%   |
| Philips PHL 273V7 PHLC156 1920x1080 600x340mm 27.2-inch              | 2         | 5.88%   |
| LG Display LCD Monitor LGD064C 1920x1080 340x190mm 15.3-inch         | 2         | 5.88%   |
| AU Optronics LCD Monitor AUO2036 2560x1440 310x170mm 13.9-inch       | 2         | 5.88%   |
| Unknown LCD Monitor Sharp 3840x2160                                  | 1         | 2.94%   |
| Samsung Electronics SyncMaster SAM021E 1680x1050 430x270mm 20.0-inch | 1         | 2.94%   |
| Samsung Electronics CJG9S SAM9596 3840x1080                          | 1         | 2.94%   |
| Philips PHL BDM4037U PHLC142 3840x2160 890x500mm 40.2-inch           | 1         | 2.94%   |
| PANDA LM116LF3L02 NCP000A 1920x1080 260x150mm 11.8-inch              | 1         | 2.94%   |
| Medion MD22321 MEA8302 1920x1080 700x390mm 31.5-inch                 | 1         | 2.94%   |
| LG Display LCD Monitor LGD0353 1366x768 350x190mm 15.7-inch          | 1         | 2.94%   |
| Lenovo LCD Monitor LEN40B0 1366x768 340x190mm 15.3-inch              | 1         | 2.94%   |
| Lenovo LCD Monitor LEN4043 1400x1050 300x230mm 14.9-inch             | 1         | 2.94%   |
| Lenovo LCD Monitor LEN4036 1440x900 300x190mm 14.0-inch              | 1         | 2.94%   |
| Lenovo LCD Monitor LEN4033 1440x900 300x190mm 14.0-inch              | 1         | 2.94%   |
| Dell U2715H DELD069 2560x1440 600x340mm 27.2-inch                    | 1         | 2.94%   |
| Dell U2715H DELD066 2560x1440 600x340mm 27.2-inch                    | 1         | 2.94%   |
| Dell P2719H DEL4185 1920x1080 600x340mm 27.2-inch                    | 1         | 2.94%   |
| Dell 2001FP DELA007 1600x1200 410x310mm 20.2-inch                    | 1         | 2.94%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch     | 1         | 2.94%   |
| Chimei Innolux LCD Monitor CMN1484 1600x900 310x170mm 13.9-inch      | 1         | 2.94%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch      | 1         | 2.94%   |
| BOE LCD Monitor BOE08D7 1920x1080 310x170mm 13.9-inch                | 1         | 2.94%   |
| BOE LCD Monitor BOE0791 1920x1080 310x170mm 13.9-inch                | 1         | 2.94%   |
| BOE LCD Monitor BOE0714 1920x1080 310x170mm 13.9-inch                | 1         | 2.94%   |
| BenQ GW2765 BNQ78D6 2560x1440 600x340mm 27.2-inch                    | 1         | 2.94%   |
| AU Optronics LCD Monitor AUO408D 1920x1080 310x170mm 13.9-inch       | 1         | 2.94%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 310x170mm 13.9-inch       | 1         | 2.94%   |
| AU Optronics LCD Monitor 1920x1080                                   | 1         | 2.94%   |
| Apple iMac APPA007 2560x1440 600x340mm 27.2-inch                     | 1         | 2.94%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 13        | 40.63%  |
| 2560x1440 (QHD)    | 5         | 15.63%  |
| 1366x768 (WXGA)    | 3         | 9.38%   |
| 3840x2160 (4K)     | 2         | 6.25%   |
| 3440x1440          | 2         | 6.25%   |
| 1440x900 (WXGA+)   | 2         | 6.25%   |
| 3840x1080          | 1         | 3.13%   |
| 1680x1050 (WSXGA+) | 1         | 3.13%   |
| 1600x900 (HD+)     | 1         | 3.13%   |
| 1600x1200          | 1         | 3.13%   |
| 1400x1050          | 1         | 3.13%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 9         | 27.27%  |
| 27      | 6         | 18.18%  |
| 15      | 4         | 12.12%  |
| 14      | 3         | 9.09%   |
| Unknown | 3         | 9.09%   |
| 34      | 2         | 6.06%   |
| 20      | 2         | 6.06%   |
| 11      | 2         | 6.06%   |
| 40      | 1         | 3.03%   |
| 31      | 1         | 3.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 13        | 39.39%  |
| 501-600     | 6         | 18.18%  |
| 201-300     | 5         | 15.15%  |
| Unknown     | 3         | 9.09%   |
| 701-800     | 2         | 6.06%   |
| 401-500     | 2         | 6.06%   |
| 801-900     | 1         | 3.03%   |
| 601-700     | 1         | 3.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 21        | 67.74%  |
| 16/10   | 3         | 9.68%   |
| 4/3     | 2         | 6.45%   |
| 21/9    | 2         | 6.45%   |
| Unknown | 2         | 6.45%   |
| 32/9    | 1         | 3.23%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 11        | 33.33%  |
| 301-350        | 6         | 18.18%  |
| 351-500        | 3         | 9.09%   |
| 91-100         | 3         | 9.09%   |
| Unknown        | 3         | 9.09%   |
| 51-60          | 2         | 6.06%   |
| 151-200        | 2         | 6.06%   |
| 101-110        | 2         | 6.06%   |
| 501-1000       | 1         | 3.03%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 121-160 | 12        | 36.36%  |
| 101-120 | 8         | 24.24%  |
| 51-100  | 7         | 21.21%  |
| 161-240 | 3         | 9.09%   |
| Unknown | 3         | 9.09%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 181       | 84.58%  |
| 1     | 27        | 12.62%  |
| 2     | 6         | 2.8%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 174       | 63.27%  |
| Realtek Semiconductor | 64        | 23.27%  |
| Broadcom              | 11        | 4%      |
| Qualcomm Atheros      | 7         | 2.55%   |
| TP-Link               | 2         | 0.73%   |
| LG Electronics        | 2         | 0.73%   |
| Edimax Technology     | 2         | 0.73%   |
| AMD                   | 2         | 0.73%   |
| Seeed Technology      | 1         | 0.36%   |
| QLogic                | 1         | 0.36%   |
| Mellanox Technologies | 1         | 0.36%   |
| MediaTek              | 1         | 0.36%   |
| Hewlett-Packard       | 1         | 0.36%   |
| Google                | 1         | 0.36%   |
| Dresden Elektronik    | 1         | 0.36%   |
| Dell                  | 1         | 0.36%   |
| Davicom Semiconductor | 1         | 0.36%   |
| AVM                   | 1         | 0.36%   |
| Arduino SA            | 1         | 0.36%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 56        | 15.91%  |
| Intel I211 Gigabit Network Connection                                  | 41        | 11.65%  |
| Intel I210 Gigabit Network Connection                                  | 33        | 9.38%   |
| Intel I350 Gigabit Network Connection                                  | 11        | 3.13%   |
| Intel Ethernet Controller I226-V                                       | 10        | 2.84%   |
| Intel Ethernet Controller I225-V                                       | 9         | 2.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 9         | 2.56%   |
| Intel Wireless 7265                                                    | 7         | 1.99%   |
| Intel Ethernet Connection (2) I219-LM                                  | 7         | 1.99%   |
| Intel Wireless 7260                                                    | 5         | 1.42%   |
| Intel Wireless 3165                                                    | 5         | 1.42%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                   | 5         | 1.42%   |
| Intel 82576 Gigabit Network Connection                                 | 5         | 1.42%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                         | 5         | 1.42%   |
| Intel Wireless 8265 / 8275                                             | 4         | 1.14%   |
| Intel I210 Gigabit Fiber Network Connection                            | 4         | 1.14%   |
| Intel Ethernet Connection X553 1GbE                                    | 4         | 1.14%   |
| Intel 82574L Gigabit Network Connection                                | 4         | 1.14%   |
| Realtek RTL8125 2.5GbE Controller                                      | 3         | 0.85%   |
| Intel Wireless 3160                                                    | 3         | 0.85%   |
| Intel Wi-Fi 6 AX200                                                    | 3         | 0.85%   |
| Intel Ethernet Connection I354                                         | 3         | 0.85%   |
| Intel Ethernet Connection (6) I219-LM                                  | 3         | 0.85%   |
| Intel Ethernet Connection (2) I219-V                                   | 3         | 0.85%   |
| Intel Centrino Ultimate-N 6300                                         | 3         | 0.85%   |
| Intel Centrino Advanced-N 6235                                         | 3         | 0.85%   |
| Intel 82577LM Gigabit Network Connection                               | 3         | 0.85%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                 | 2         | 0.57%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 2         | 0.57%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 2         | 0.57%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 2         | 0.57%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller      | 2         | 0.57%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                       | 2         | 0.57%   |
| LG Optimus Android Phone [USB tethering mode]                          | 2         | 0.57%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 2         | 0.57%   |
| Intel Gemini Lake PCH CNVi WiFi                                        | 2         | 0.57%   |
| Intel Ethernet Connection X722 for 10GbE SFP+                          | 2         | 0.57%   |
| Intel Ethernet Connection X722 for 10GBASE-T                           | 2         | 0.57%   |
| Intel Ethernet Connection I217-V                                       | 2         | 0.57%   |
| Intel Ethernet Connection I217-LM                                      | 2         | 0.57%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 50        | 67.57%  |
| Realtek Semiconductor | 11        | 14.86%  |
| Qualcomm Atheros      | 6         | 8.11%   |
| TP-Link               | 2         | 2.7%    |
| Edimax Technology     | 2         | 2.7%    |
| MediaTek              | 1         | 1.35%   |
| Dell                  | 1         | 1.35%   |
| Broadcom              | 1         | 1.35%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Intel Wireless 7265                                             | 7         | 9.33%   |
| Intel Wireless 7260                                             | 5         | 6.67%   |
| Intel Wireless 3165                                             | 5         | 6.67%   |
| Intel Wireless 8265 / 8275                                      | 4         | 5.33%   |
| Intel Wireless 3160                                             | 3         | 4%      |
| Intel Wi-Fi 6 AX200                                             | 3         | 4%      |
| Intel Centrino Advanced-N 6235                                  | 3         | 4%      |
| TP-Link Archer T3U [Realtek RTL8812BU]                          | 2         | 2.67%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter        | 2         | 2.67%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter        | 2         | 2.67%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter             | 2         | 2.67%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                | 2         | 2.67%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]         | 2         | 2.67%   |
| Intel Gemini Lake PCH CNVi WiFi                                 | 2         | 2.67%   |
| Intel Comet Lake PCH-LP CNVi WiFi                               | 2         | 2.67%   |
| Intel Centrino Ultimate-N 6300                                  | 2         | 2.67%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                        | 2         | 2.67%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]  | 2         | 2.67%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter        | 1         | 1.33%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter        | 1         | 1.33%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                 | 1         | 1.33%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                          | 1         | 1.33%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                         | 1         | 1.33%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                      | 1         | 1.33%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter | 1         | 1.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter      | 1         | 1.33%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                | 1         | 1.33%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)  | 1         | 1.33%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                         | 1         | 1.33%   |
| Intel Wireless 8260                                             | 1         | 1.33%   |
| Intel WiFi Link 5100                                            | 1         | 1.33%   |
| Intel Wi-Fi 6 AX201                                             | 1         | 1.33%   |
| Intel Ultimate N WiFi Link 5300                                 | 1         | 1.33%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection           | 1         | 1.33%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                 | 1         | 1.33%   |
| Intel Centrino Wireless-N 2230                                  | 1         | 1.33%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                   | 1         | 1.33%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                    | 1         | 1.33%   |
| Intel Centrino Advanced-N 6200                                  | 1         | 1.33%   |
| Dell Wireless 5550 HSPA+ Mini-Card Network Adapter              | 1         | 1.33%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 149       | 66.52%  |
| Realtek Semiconductor | 59        | 26.34%  |
| Broadcom              | 11        | 4.91%   |
| AMD                   | 2         | 0.89%   |
| Qualcomm Atheros      | 1         | 0.45%   |
| QLogic                | 1         | 0.45%   |
| Davicom Semiconductor | 1         | 0.45%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 56        | 21.05%  |
| Intel I211 Gigabit Network Connection                                  | 41        | 15.41%  |
| Intel I210 Gigabit Network Connection                                  | 33        | 12.41%  |
| Intel I350 Gigabit Network Connection                                  | 11        | 4.14%   |
| Intel Ethernet Controller I226-V                                       | 10        | 3.76%   |
| Intel Ethernet Controller I225-V                                       | 9         | 3.38%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 9         | 3.38%   |
| Intel Ethernet Connection (2) I219-LM                                  | 7         | 2.63%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                   | 5         | 1.88%   |
| Intel 82576 Gigabit Network Connection                                 | 5         | 1.88%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                         | 5         | 1.88%   |
| Intel I210 Gigabit Fiber Network Connection                            | 4         | 1.5%    |
| Intel Ethernet Connection X553 1GbE                                    | 4         | 1.5%    |
| Intel 82574L Gigabit Network Connection                                | 4         | 1.5%    |
| Realtek RTL8125 2.5GbE Controller                                      | 3         | 1.13%   |
| Intel Ethernet Connection I354                                         | 3         | 1.13%   |
| Intel Ethernet Connection (6) I219-LM                                  | 3         | 1.13%   |
| Intel Ethernet Connection (2) I219-V                                   | 3         | 1.13%   |
| Intel 82577LM Gigabit Network Connection                               | 3         | 1.13%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller      | 2         | 0.75%   |
| Intel Ethernet Connection X722 for 10GbE SFP+                          | 2         | 0.75%   |
| Intel Ethernet Connection X722 for 10GBASE-T                           | 2         | 0.75%   |
| Intel Ethernet Connection I217-V                                       | 2         | 0.75%   |
| Intel Ethernet Connection I217-LM                                      | 2         | 0.75%   |
| Intel Ethernet Connection (7) I219-LM                                  | 2         | 0.75%   |
| Intel 82583V Gigabit Network Connection                                | 2         | 0.75%   |
| Intel 82567LM Gigabit Network Connection                               | 2         | 0.75%   |
| AMD XGMAC 10GbE Controller                                             | 2         | 0.75%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 1         | 0.38%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1         | 0.38%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1         | 0.38%   |
| QLogic cLOM8214 1/10GbE Controller                                     | 1         | 0.38%   |
| Intel Ethernet Connection X552/X557-AT 10GBASE-T                       | 1         | 0.38%   |
| Intel Ethernet Connection I219-V                                       | 1         | 0.38%   |
| Intel Ethernet Connection I219-LM                                      | 1         | 0.38%   |
| Intel Ethernet Connection I218-LM                                      | 1         | 0.38%   |
| Intel Ethernet Connection (5) I219-LM                                  | 1         | 0.38%   |
| Intel Ethernet Connection (4) I219-V                                   | 1         | 0.38%   |
| Intel Ethernet Connection (4) I219-LM                                  | 1         | 0.38%   |
| Intel Ethernet Connection (3) I218-V                                   | 1         | 0.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 204       | 71.33%  |
| WiFi     | 71        | 24.83%  |
| Modem    | 6         | 2.1%    |
| Unknown  | 5         | 1.75%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 198       | 89.19%  |
| WiFi     | 23        | 10.36%  |
| Modem    | 1         | 0.45%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 55        | 25.94%  |
| 4     | 50        | 23.58%  |
| 3     | 45        | 21.23%  |
| 1     | 18        | 8.49%   |
| 6     | 17        | 8.02%   |
| 8     | 9         | 4.25%   |
| 5     | 9         | 4.25%   |
| 7     | 3         | 1.42%   |
| 9     | 2         | 0.94%   |
| 0     | 2         | 0.94%   |
| 12    | 1         | 0.47%   |
| 10    | 1         | 0.47%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 200       | 92.59%  |
| Yes  | 16        | 7.41%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 37        | 72.55%  |
| Realtek Semiconductor | 4         | 7.84%   |
| Broadcom              | 4         | 7.84%   |
| IMC Networks          | 2         | 3.92%   |
| MediaTek              | 1         | 1.96%   |
| Lite-On Technology    | 1         | 1.96%   |
| Apple                 | 1         | 1.96%   |
| Alps Electric         | 1         | 1.96%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface               | 19        | 37.25%  |
| Intel Centrino Bluetooth Wireless Transceiver    | 4         | 7.84%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)   | 4         | 7.84%   |
| Intel AX201 Bluetooth                            | 4         | 7.84%   |
| Realtek Bluetooth Adapter                        | 3         | 5.88%   |
| Intel AX200 Bluetooth                            | 3         | 5.88%   |
| Broadcom BCM2045B (BDC-2.1)                      | 3         | 5.88%   |
| Intel Wireless-AC 9260 Bluetooth Adapter         | 2         | 3.92%   |
| IMC Networks Realtek Bluetooth Adapter           | 2         | 3.92%   |
| Realtek RTL8821A Bluetooth                       | 1         | 1.96%   |
| MediaTek RZ608 Bluetooth Adapter                 | 1         | 1.96%   |
| Lite-On Atheros AR3012 Bluetooth                 | 1         | 1.96%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter | 1         | 1.96%   |
| Broadcom BCM2035 Bluetooth dongle                | 1         | 1.96%   |
| Apple Built-in Bluetooth 2.0+EDR HCI             | 1         | 1.96%   |
| Alps Electric UGTZ4 Bluetooth                    | 1         | 1.96%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 128       | 82.05%  |
| AMD                                          | 16        | 10.26%  |
| Nvidia                                       | 4         | 2.56%   |
| Plantronics                                  | 3         | 1.92%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.64%   |
| Texas Instruments                            | 1         | 0.64%   |
| Lenovo                                       | 1         | 0.64%   |
| Creative Labs                                | 1         | 0.64%   |
| Apple                                        | 1         | 0.64%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 15        | 8.29%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 14        | 7.73%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 10        | 5.52%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 9         | 4.97%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 9         | 4.97%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 8         | 4.42%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 7         | 3.87%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 7         | 3.87%   |
| Intel Jasper Lake HD Audio                                                                        | 6         | 3.31%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 6         | 3.31%   |
| Intel Alder Lake-N PCH High Definition Audio Controller                                           | 6         | 3.31%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 6         | 3.31%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 6         | 3.31%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 5         | 2.76%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 5         | 2.76%   |
| Intel 8 Series HD Audio Controller                                                                | 5         | 2.76%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4         | 2.21%   |
| Plantronics Plantronics Blackwire 315.1                                                           | 3         | 1.66%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 3         | 1.66%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 1.66%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 1.66%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 1.66%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 1.66%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 1.66%   |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 1.66%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 1.1%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 1.1%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 1.1%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 1.1%    |
| Intel 200 Series PCH HD Audio                                                                     | 2         | 1.1%    |
| AMD FCH Azalia Controller                                                                         | 2         | 1.1%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 1.1%    |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID                                    | 1         | 0.55%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 1         | 0.55%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.55%   |
| Lenovo Realtek USB Audio                                                                          | 1         | 0.55%   |
| Intel Smart Sound Technology (SST) Audio Controller                                               | 1         | 0.55%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 1         | 0.55%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.55%   |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 1         | 0.55%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 32        | 15.61%  |
| Crucial             | 28        | 13.66%  |
| Unknown             | 25        | 12.2%   |
| Kingston            | 24        | 11.71%  |
| SK hynix            | 22        | 10.73%  |
| Micron Technology   | 19        | 9.27%   |
| Unknown (ABCD)      | 11        | 5.37%   |
| Corsair             | 10        | 4.88%   |
| Unknown             | 6         | 2.93%   |
| Transcend           | 5         | 2.44%   |
| A-DATA Technology   | 4         | 1.95%   |
| G.Skill             | 3         | 1.46%   |
| Ramaxel Technology  | 2         | 0.98%   |
| Nanya Technology    | 2         | 0.98%   |
| tigo                | 1         | 0.49%   |
| Mushkin             | 1         | 0.49%   |
| Miron               | 1         | 0.49%   |
| Lexar Co Limited    | 1         | 0.49%   |
| Kingmax             | 1         | 0.49%   |
| Kimtigo             | 1         | 0.49%   |
| GOODRAM             | 1         | 0.49%   |
| GeIL                | 1         | 0.49%   |
| Elpida              | 1         | 0.49%   |
| DSL                 | 1         | 0.49%   |
| Avant               | 1         | 0.49%   |
| ATP                 | 1         | 0.49%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s | 11        | 5.24%   |
| Unknown                                                      | 6         | 2.86%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                  | 5         | 2.38%   |
| Kingston RAM CBD26D4S9S8K1C-8 8GB SODIMM DDR4 2667MT/s       | 3         | 1.43%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s      | 3         | 1.43%   |
| Crucial RAM CT16G48C40S5.M8A1 16GB SODIMM DDR5 4800MT/s      | 3         | 1.43%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                    | 2         | 0.95%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                    | 2         | 0.95%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                    | 2         | 0.95%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                    | 2         | 0.95%   |
| Unknown RAM AW24P64F8BLK0S 8GB DIMM DDR3 1600MT/s            | 2         | 0.95%   |
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s          | 2         | 0.95%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                | 2         | 0.95%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 2         | 0.95%   |
| SK hynix RAM HMT125U6BFR8C-G7 2GB DIMM DDR3 1067MT/s         | 2         | 0.95%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s               | 2         | 0.95%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s       | 2         | 0.95%   |
| Samsung RAM M471A2G44AM0-CTD 16GB SODIMM DDR4 2667MT/s       | 2         | 0.95%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s        | 2         | 0.95%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1333MT/s          | 2         | 0.95%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s         | 2         | 0.95%   |
| Crucial RAM CT8G4SFS824A.M8FRS 8GB DIMM DDR4 2400MT/s        | 2         | 0.95%   |
| Crucial RAM CT4G4SFS824A.C8FBD 4GB SODIMM DDR4 2400MT/s      | 2         | 0.95%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s      | 2         | 0.95%   |
| Unknown RAM X4B08QD8BNVFSO-7-TO1 8GB DIMM DDR4 2933MT/s      | 1         | 0.48%   |
| Unknown RAM Module 8GB SODIMM DDR4 2400MT/s                  | 1         | 0.48%   |
| Unknown RAM Module 8GB 1600MT/s                              | 1         | 0.48%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s                 | 1         | 0.48%   |
| Unknown RAM Module 4GB SODIMM DDR3 667MT/s                   | 1         | 0.48%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                    | 1         | 0.48%   |
| Unknown RAM Module 4GB DIMM DDR3 1066MT/s                    | 1         | 0.48%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                 | 1         | 0.48%   |
| Unknown RAM Module 2048MB SODIMM DDR2                        | 1         | 0.48%   |
| Unknown RAM Module 1GB DIMM DDR2 1033MT/s                    | 1         | 0.48%   |
| Unknown RAM Module 1024MB SODIMM DDR2                        | 1         | 0.48%   |
| Transcend RAM TS512MLK72V6H 4GB DIMM DDR3 1600MT/s           | 1         | 0.48%   |
| Transcend RAM TS2GSH64V1B 16GB SODIMM DDR4 2133MT/s          | 1         | 0.48%   |
| Transcend RAM JM3200HSE-16G 16GB SODIMM DDR4 3200MT/s        | 1         | 0.48%   |
| tigo RAM 1600Mhz-4G 4GB SODIMM DDR3 1600MT/s                 | 1         | 0.48%   |
| SK hynix RAM Module 2GB DIMM DDR3 1333MT/s                   | 1         | 0.48%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 84        | 45.41%  |
| DDR4    | 74        | 40%     |
| LPDDR4  | 15        | 8.11%   |
| DDR5    | 6         | 3.24%   |
| DDR2    | 3         | 1.62%   |
| LPDDR3  | 1         | 0.54%   |
| DRAM    | 1         | 0.54%   |
| Unknown | 1         | 0.54%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 95        | 51.63%  |
| DIMM         | 81        | 44.02%  |
| Row Of Chips | 5         | 2.72%   |
| Unknown      | 2         | 1.09%   |
| Chip         | 1         | 0.54%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 76        | 39.18%  |
| 4096  | 52        | 26.8%   |
| 16384 | 35        | 18.04%  |
| 2048  | 19        | 9.79%   |
| 32768 | 8         | 4.12%   |
| 1024  | 3         | 1.55%   |
| 6144  | 1         | 0.52%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 51        | 26.7%   |
| 2400    | 35        | 18.32%  |
| 1333    | 28        | 14.66%  |
| 2667    | 24        | 12.57%  |
| 3200    | 19        | 9.95%   |
| 2133    | 7         | 3.66%   |
| 4800    | 6         | 3.14%   |
| 1067    | 4         | 2.09%   |
| 2666    | 2         | 1.05%   |
| 1867    | 2         | 1.05%   |
| 1334    | 2         | 1.05%   |
| Unknown | 2         | 1.05%   |
| 65535   | 1         | 0.52%   |
| 4000    | 1         | 0.52%   |
| 3000    | 1         | 0.52%   |
| 2933    | 1         | 0.52%   |
| 1866    | 1         | 0.52%   |
| 1066    | 1         | 0.52%   |
| 1033    | 1         | 0.52%   |
| 800     | 1         | 0.52%   |
| 667     | 1         | 0.52%   |

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
| Chicony Electronics                    | 10        | 40%     |
| Microdia                               | 3         | 12%     |
| Realtek Semiconductor                  | 2         | 8%      |
| Logitech                               | 2         | 8%      |
| Cheng Uei Precision Industry (Foxlink) | 2         | 8%      |
| Bison Electronics                      | 2         | 8%      |
| Lite-On Technology                     | 1         | 4%      |
| Lenovo                                 | 1         | 4%      |
| IMC Networks                           | 1         | 4%      |
| Apple                                  | 1         | 4%      |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Realtek USB 2.0 PC Camera                                   | 2         | 8%      |
| Chicony ThinkPad T490 Webcam                                | 2         | 8%      |
| Chicony Integrated Camera                                   | 2         | 8%      |
| Chicony HP HD Camera                                        | 2         | 8%      |
| Microdia Laptop_Integrated_Webcam_HD                        | 1         | 4%      |
| Microdia Integrated Webcam HD                               | 1         | 4%      |
| Microdia Integrated Webcam                                  | 1         | 4%      |
| Logitech Webcam C170                                        | 1         | 4%      |
| Logitech HD Pro Webcam C920                                 | 1         | 4%      |
| Lite-On HP HD Camera                                        | 1         | 4%      |
| Lenovo Integrated Webcam [R5U877]                           | 1         | 4%      |
| IMC Networks Integrated Camera                              | 1         | 4%      |
| Chicony Integrated IR Camera                                | 1         | 4%      |
| Chicony Integrated HD WebCam                                | 1         | 4%      |
| Chicony Integrated Camera (1280x720@30)                     | 1         | 4%      |
| Chicony HP Universal Camera                                 | 1         | 4%      |
| Cheng Uei Precision Industry (Foxlink) Webcam               | 1         | 4%      |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam [Fixed] | 1         | 4%      |
| Bison SunplusIT Integrated Camera                           | 1         | 4%      |
| Bison Lenovo EasyCamera                                     | 1         | 4%      |
| Apple FaceTime HD camera                                    | 1         | 4%      |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 5         | 33.33%  |
| Upek                       | 3         | 20%     |
| Synaptics                  | 3         | 20%     |
| Shenzhen Goodix Technology | 2         | 13.33%  |
| STMicroelectronics         | 1         | 6.67%   |
| Elan Microelectronics      | 1         | 6.67%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader               | 3         | 20%     |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor   | 3         | 20%     |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 2         | 13.33%  |
| Shenzhen Goodix Fingerprint Reader                       | 2         | 13.33%  |
| Validity Sensors VFS5011 Fingerprint Reader              | 1         | 6.67%   |
| Validity Sensors VFS491                                  | 1         | 6.67%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader        | 1         | 6.67%   |
| STMicroelectronics Fingerprint Reader                    | 1         | 6.67%   |
| Elan Fingerprint Sensor                                  | 1         | 6.67%   |

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
| 1     | 86        | 38.91%  |
| 0     | 67        | 30.32%  |
| 2     | 40        | 18.1%   |
| 3     | 22        | 9.95%   |
| 4     | 4         | 1.81%   |
| 5     | 2         | 0.9%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 132       | 61.4%   |
| Bluetooth                | 22        | 10.23%  |
| Net/wireless             | 17        | 7.91%   |
| Card reader              | 16        | 7.44%   |
| Fingerprint reader       | 15        | 6.98%   |
| Firewire controller      | 4         | 1.86%   |
| Network                  | 3         | 1.4%    |
| Sound                    | 2         | 0.93%   |
| Graphics card            | 2         | 0.93%   |
| Storage/nvme             | 1         | 0.47%   |
| Net/ethernet             | 1         | 0.47%   |

