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

Total: 327

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
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

![OS](./All/images/pie_chart_bsd/os_name.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| OPNsense 21.7.3      | 9         | 3.3%    |
| OPNsense 22.1.1      | 8         | 2.93%   |
| OPNsense 23.7.5      | 7         | 2.56%   |
| OPNsense 21.7.7      | 7         | 2.56%   |
| OPNsense 22.4.3      | 6         | 2.2%    |
| OPNsense 21.1.4      | 6         | 2.2%    |
| OPNsense 20.7.8      | 6         | 2.2%    |
| FreeBSD 13.1         | 6         | 2.2%    |
| OPNsense 23.7.10     | 5         | 1.83%   |
| OPNsense 23.1.6      | 5         | 1.83%   |
| OPNsense 23.1.5      | 5         | 1.83%   |
| OPNsense 22.7.9      | 5         | 1.83%   |
| OPNsense 22.7.11     | 5         | 1.83%   |
| OPNsense 22.1        | 5         | 1.83%   |
| OPNsense 21.7.6      | 5         | 1.83%   |
| OPNsense 21.1.5      | 5         | 1.83%   |
| OPNsense 21.1.3      | 5         | 1.83%   |
| OPNsense 21.1.2      | 5         | 1.83%   |
| OPNsense 21.1        | 5         | 1.83%   |
| OpenBSD 6.8          | 5         | 1.83%   |
| OPNsense 23.7.9      | 4         | 1.47%   |
| OPNsense 23.7.8      | 4         | 1.47%   |
| OPNsense 23.1.7      | 4         | 1.47%   |
| OPNsense 23.1.11     | 4         | 1.47%   |
| OPNsense 23.1        | 4         | 1.47%   |
| OPNsense 22.7.2      | 4         | 1.47%   |
| OPNsense 22.7.10     | 4         | 1.47%   |
| OPNsense 22.1.9      | 4         | 1.47%   |
| OPNsense 22.1.7      | 4         | 1.47%   |
| OPNsense 22.1.4      | 4         | 1.47%   |
| OPNsense 21.7        | 4         | 1.47%   |
| OPNsense 21.1.8      | 4         | 1.47%   |
| FreeBSD 14.0-CURRENT | 4         | 1.47%   |
| FreeBSD 13.1-p5      | 4         | 1.47%   |
| OPNsense 23.7.7      | 3         | 1.1%    |
| OPNsense 23.7.1      | 3         | 1.1%    |
| OPNsense 22.1.10     | 3         | 1.1%    |
| OPNsense 21.7.8      | 3         | 1.1%    |
| OPNsense 21.1.1      | 3         | 1.1%    |
| FreeBSD 12.2         | 3         | 1.1%    |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| OPNsense    | 153       | 73.91%  |
| FreeBSD     | 38        | 18.36%  |
| OpenBSD     | 8         | 3.86%   |
| helloSystem | 4         | 1.93%   |
| FreeNAS     | 3         | 1.45%   |
| TrueNAS     | 1         | 0.48%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 204       | 98.55%  |
| arm64 | 2         | 0.97%   |
| i386  | 1         | 0.48%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Console      | 170       | 81.34%  |
| KDE5         | 10        | 4.78%   |
| XFCE         | 6         | 2.87%   |
| helloDesktop | 6         | 2.87%   |
| MATE         | 3         | 1.44%   |
| Cinnamon     | 3         | 1.44%   |
| LXQt         | 2         | 0.96%   |
| i3           | 2         | 0.96%   |
| fvwm         | 2         | 0.96%   |
| xinitrc      | 1         | 0.48%   |
| TWM          | 1         | 0.48%   |
| Openbox      | 1         | 0.48%   |
| Lumina       | 1         | 0.48%   |
| GNOME        | 1         | 0.48%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 173       | 82.78%  |
| X11     | 34        | 16.27%  |
| Wayland | 2         | 0.96%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 183       | 87.56%  |
| SDDM    | 14        | 6.7%    |
| SLiM    | 7         | 3.35%   |
| LightDM | 3         | 1.44%   |
| XDM     | 1         | 0.48%   |
| GDM     | 1         | 0.48%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 166       | 78.3%   |
| C       | 22        | 10.38%  |
| en_US   | 17        | 8.02%   |
| de_DE   | 4         | 1.89%   |
| cs_CZ   | 2         | 0.94%   |
| de_AT   | 1         | 0.47%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 183       | 88.41%  |
| BIOS | 24        | 11.59%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ufs     | 116       | 55.5%   |
| Zfs     | 83        | 39.71%  |
| Ffs     | 8         | 3.83%   |
| Cd9660  | 1         | 0.48%   |
| Unknown | 1         | 0.48%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 194       | 93.72%  |
| MBR     | 9         | 4.35%   |
| Unknown | 4         | 1.93%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Unknown                    | 24        | 11.59%  |
| Lenovo                     | 20        | 9.66%   |
| Hewlett-Packard            | 15        | 7.25%   |
| PC Engines                 | 14        | 6.76%   |
| Dell                       | 13        | 6.28%   |
| Intel                      | 10        | 4.83%   |
| Supermicro                 | 9         | 4.35%   |
| Fujitsu                    | 8         | 3.86%   |
| Deciso                     | 8         | 3.86%   |
| ZOTAC                      | 7         | 3.38%   |
| Gigabyte Technology        | 6         | 2.9%    |
| BESSTAR Tech               | 6         | 2.9%    |
| Shuttle                    | 5         | 2.42%   |
| ASUSTek Computer           | 5         | 2.42%   |
| AMI                        | 5         | 2.42%   |
| Sophos                     | 4         | 1.93%   |
| Protectli                  | 4         | 1.93%   |
| MW                         | 4         | 1.93%   |
| ASRock                     | 4         | 1.93%   |
| AWOW                       | 3         | 1.45%   |
| Techvision                 | 2         | 0.97%   |
| Secudos                    | 2         | 0.97%   |
| MSI                        | 2         | 0.97%   |
| IceWhale Technology        | 2         | 0.97%   |
| Hardkernel                 | 2         | 0.97%   |
| Biostar                    | 2         | 0.97%   |
| Barracuda Networks         | 2         | 0.97%   |
| AAEON                      | 2         | 0.97%   |
| Winston Marriot            | 1         | 0.48%   |
| TUXEDO                     | 1         | 0.48%   |
| Silicom                    | 1         | 0.48%   |
| ShenZhen MinWin Technology | 1         | 0.48%   |
| SeeedStudio                | 1         | 0.48%   |
| Seeed Studio               | 1         | 0.48%   |
| Raspberry Pi Foundation    | 1         | 0.48%   |
| Purism                     | 1         | 0.48%   |
| Panasonic                  | 1         | 0.48%   |
| NEXCOM                     | 1         | 0.48%   |
| IP3 Tech                   | 1         | 0.48%   |
| HUAWEI                     | 1         | 0.48%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                                             | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Unknown                                          | 27        | 13.04%  |
| PC Engines apu4                                  | 7         | 3.38%   |
| PC Engines APU2                                  | 7         | 3.38%   |
| Deciso Netboard A10 GEN2 Model G                 | 6         | 2.9%    |
| Supermicro Super Server                          | 4         | 1.93%   |
| MW GMLK-2_5G4L                                   | 4         | 1.93%   |
| Sophos SG                                        | 3         | 1.45%   |
| Protectli FW4B                                   | 3         | 1.45%   |
| Intel Q3XXG4-P V1.0                              | 3         | 1.45%   |
| ZOTAC ZBOX-CI341                                 | 2         | 0.97%   |
| ZOTAC ZBOX-CI323NANO                             | 2         | 0.97%   |
| Techvision TVI7309X                              | 2         | 0.97%   |
| Shuttle DS10U                                    | 2         | 0.97%   |
| Lenovo ThinkPad T490 20N2CTO1WW                  | 2         | 0.97%   |
| IceWhale ZimaBoard 832 ZMB                       | 2         | 0.97%   |
| HP ProLiant DL360 G6                             | 2         | 0.97%   |
| HP EliteBook 850 G7 Notebook PC                  | 2         | 0.97%   |
| Hardkernel ODROID-H2                             | 2         | 0.97%   |
| Fujitsu FUTRO S720                               | 2         | 0.97%   |
| Fujitsu ESPRIMO C720                             | 2         | 0.97%   |
| Dell OptiPlex 5040                               | 2         | 0.97%   |
| AWOW AK34                                        | 2         | 0.97%   |
| AMI LES compact 4L                               | 2         | 0.97%   |
| AMI Aptio CRB                                    | 2         | 0.97%   |
| AAEON UP-APL01                                   | 2         | 0.97%   |
| ZOTAC ZBOXNANO-ID63/ID64/ID65                    | 1         | 0.48%   |
| ZOTAC ZBOX-CI527/CI547NANO                       | 1         | 0.48%   |
| Winston Marriot PICO PC  PICOPC                  | 1         | 0.48%   |
| TUXEDO InfinityBook Pro 14 Gen6                  | 1         | 0.48%   |
| Supermicro X10SLL-F                              | 1         | 0.48%   |
| Supermicro IXWS-733TQ-665B-IXN                   | 1         | 0.48%   |
| Supermicro A1SAi                                 | 1         | 0.48%   |
| Supermicro 1HE Intel Single-CPU RI1102D-F Server | 1         | 0.48%   |
| Supermicro 1HE Intel Single-CPU RI1101H-F Server | 1         | 0.48%   |
| Sophos XG                                        | 1         | 0.48%   |
| Silicom Minnowboard Turbot D0/D1 PLATFORM        | 1         | 0.48%   |
| Shuttle DS61                                     | 1         | 0.48%   |
| Shuttle DS437                                    | 1         | 0.48%   |
| Shuttle DH170                                    | 1         | 0.48%   |
| ShenZhen MinWin 3865U-6L                         | 1         | 0.48%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Unknown                        | 27        | 13.04%  |
| Lenovo ThinkPad                | 12        | 5.8%    |
| PC Engines apu4                | 7         | 3.38%   |
| PC Engines APU2                | 7         | 3.38%   |
| Dell OptiPlex                  | 6         | 2.9%    |
| Deciso Netboard                | 6         | 2.9%    |
| HP ProLiant                    | 5         | 2.42%   |
| Supermicro Super               | 4         | 1.93%   |
| MW GMLK-2                      | 4         | 1.93%   |
| HP EliteBook                   | 4         | 1.93%   |
| Sophos SG                      | 3         | 1.45%   |
| Protectli FW4B                 | 3         | 1.45%   |
| Lenovo ThinkCentre             | 3         | 1.45%   |
| Intel Q3XXG4-P                 | 3         | 1.45%   |
| Fujitsu FUTRO                  | 3         | 1.45%   |
| Fujitsu ESPRIMO                | 3         | 1.45%   |
| ZOTAC ZBOX-CI341               | 2         | 0.97%   |
| ZOTAC ZBOX-CI323NANO           | 2         | 0.97%   |
| Techvision TVI7309X            | 2         | 0.97%   |
| Supermicro 1HE                 | 2         | 0.97%   |
| Shuttle DS10U                  | 2         | 0.97%   |
| Lenovo IdeaPad                 | 2         | 0.97%   |
| Lenovo IdeaCentre              | 2         | 0.97%   |
| IceWhale ZimaBoard             | 2         | 0.97%   |
| HP Compaq                      | 2         | 0.97%   |
| Hardkernel ODROID-H2           | 2         | 0.97%   |
| Dell Precision                 | 2         | 0.97%   |
| Dell PowerEdge                 | 2         | 0.97%   |
| Barracuda Networks Barracuda   | 2         | 0.97%   |
| AWOW AK34                      | 2         | 0.97%   |
| ASUS 1HE                       | 2         | 0.97%   |
| AMI LES                        | 2         | 0.97%   |
| AMI Aptio                      | 2         | 0.97%   |
| AAEON UP-APL01                 | 2         | 0.97%   |
| ZOTAC ZBOXNANO-ID63            | 1         | 0.48%   |
| ZOTAC ZBOX-CI527               | 1         | 0.48%   |
| Winston Marriot PICO           | 1         | 0.48%   |
| TUXEDO InfinityBook            | 1         | 0.48%   |
| Supermicro X10SLL-F            | 1         | 0.48%   |
| Supermicro IXWS-733TQ-665B-IXN | 1         | 0.48%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 28        | 13.53%  |
| 2021    | 27        | 13.04%  |
| 2017    | 22        | 10.63%  |
| 2016    | 20        | 9.66%   |
| 2020    | 19        | 9.18%   |
| 2019    | 18        | 8.7%    |
| 2022    | 16        | 7.73%   |
| 2014    | 10        | 4.83%   |
| 2015    | 9         | 4.35%   |
| 2013    | 7         | 3.38%   |
| 2011    | 7         | 3.38%   |
| 2023    | 6         | 2.9%    |
| 2010    | 6         | 2.9%    |
| 2012    | 4         | 1.93%   |
| 2009    | 3         | 1.45%   |
| Unknown | 3         | 1.45%   |
| 2007    | 1         | 0.48%   |
| 2006    | 1         | 0.48%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 128       | 61.84%  |
| Notebook       | 34        | 16.43%  |
| Mini pc        | 18        | 8.7%    |
| Server         | 17        | 8.21%   |
| Firewall       | 6         | 2.9%    |
| System on chip | 2         | 0.97%   |
| Convertible    | 1         | 0.48%   |
| All in one     | 1         | 0.48%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 184       | 88.89%  |
| Yes  | 23        | 11.11%  |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 85        | 40.28%  |
| 4.01-8.0        | 43        | 20.38%  |
| 16.01-24.0      | 43        | 20.38%  |
| 32.01-64.0      | 16        | 7.58%   |
| 2.01-3.0        | 9         | 4.27%   |
| 64.01-256.0     | 5         | 2.37%   |
| 3.01-4.0        | 4         | 1.9%    |
| More than 256.0 | 3         | 1.42%   |
| 24.01-32.0      | 2         | 0.95%   |
| 1.01-2.0        | 1         | 0.47%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 0.01-0.5    | 115       | 53.99%  |
| 0.51-1.0    | 62        | 29.11%  |
| 1.01-2.0    | 22        | 10.33%  |
| 2.01-3.0    | 4         | 1.88%   |
| 4.01-8.0    | 3         | 1.41%   |
| 32.01-64.0  | 3         | 1.41%   |
| 3.01-4.0    | 1         | 0.47%   |
| 64.01-256.0 | 1         | 0.47%   |
| 16.01-24.0  | 1         | 0.47%   |
| 0           | 1         | 0.47%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 165       | 77.83%  |
| 2      | 21        | 9.91%   |
| 0      | 13        | 6.13%   |
| 4      | 4         | 1.89%   |
| 3      | 4         | 1.89%   |
| 17     | 1         | 0.47%   |
| 15     | 1         | 0.47%   |
| 13     | 1         | 0.47%   |
| 7      | 1         | 0.47%   |
| 6      | 1         | 0.47%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 189       | 90%     |
| Yes       | 21        | 10%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 199       | 96.14%  |
| No        | 8         | 3.86%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 139       | 66.51%  |
| Yes       | 70        | 33.49%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 159       | 76.08%  |
| Yes       | 50        | 23.92%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Austria | 207       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City                            | Computers | Percent |
|---------------------------------|-----------|---------|
| Vienna                          | 103       | 44.59%  |
| Graz                            | 17        | 7.36%   |
| Linz                            | 6         | 2.6%    |
| Innsbruck                       | 6         | 2.6%    |
| Wels                            | 5         | 2.16%   |
| Salzburg                        | 4         | 1.73%   |
| Feldkirch                       | 4         | 1.73%   |
| Stockerau                       | 2         | 0.87%   |
| Sankt Veit an der Glan          | 2         | 0.87%   |
| Rankweil                        | 2         | 0.87%   |
| Neulengbach                     | 2         | 0.87%   |
| Leoben                          | 2         | 0.87%   |
| Krems                           | 2         | 0.87%   |
| Klagenfurt                      | 2         | 0.87%   |
| Hittisau                        | 2         | 0.87%   |
| Bruck an der Mur                | 2         | 0.87%   |
| Atzenbrugg                      | 2         | 0.87%   |
| Zwettl Stadt                    | 1         | 0.43%   |
| Weidlingbach                    | 1         | 0.43%   |
| Vorchdorf                       | 1         | 0.43%   |
| Voggenberg                      | 1         | 0.43%   |
| Tulln                           | 1         | 0.43%   |
| Trausdorf an der Wulka          | 1         | 0.43%   |
| Tragwein                        | 1         | 0.43%   |
| Steyr                           | 1         | 0.43%   |
| Steinhaus                       | 1         | 0.43%   |
| Spittal an der Drau             | 1         | 0.43%   |
| Sieghartskirchen                | 1         | 0.43%   |
| Siegendorf im Burgenland        | 1         | 0.43%   |
| Seyring                         | 1         | 0.43%   |
| Schwechat                       | 1         | 0.43%   |
| Schörfling                     | 1         | 0.43%   |
| Schluesslberg                   | 1         | 0.43%   |
| Sankt PГ¶lten                 | 1         | 0.43%   |
| Sankt PÃ¶lten                 | 1         | 0.43%   |
| Sankt Pantaleon                 | 1         | 0.43%   |
| Sankt Margarethen im Burgenland | 1         | 0.43%   |
| Sankt Johann in Tirol           | 1         | 0.43%   |
| Rottenmann                      | 1         | 0.43%   |
| Pusarnitz                       | 1         | 0.43%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 35        | 54     | 14.96%  |
| Transcend           | 31        | 41     | 13.25%  |
| Kingston            | 21        | 33     | 8.97%   |
| WDC                 | 19        | 43     | 8.12%   |
| Crucial             | 17        | 25     | 7.26%   |
| Intel               | 15        | 19     | 6.41%   |
| Seagate             | 9         | 30     | 3.85%   |
| SanDisk             | 8         | 14     | 3.42%   |
| Micron Technology   | 5         | 9      | 2.14%   |
| Hoodisk             | 5         | 6      | 2.14%   |
| HGST                | 5         | 12     | 2.14%   |
| Phison              | 4         | 5      | 1.71%   |
| FORESEE             | 4         | 5      | 1.71%   |
| China               | 4         | 6      | 1.71%   |
| A-DATA Technology   | 4         | 8      | 1.71%   |
| Toshiba             | 3         | 6      | 1.28%   |
| SK hynix            | 3         | 5      | 1.28%   |
| Patriot             | 3         | 5      | 1.28%   |
| Silicon Motion      | 2         | 2      | 0.85%   |
| OCZ                 | 2         | 2      | 0.85%   |
| Innodisk            | 2         | 3      | 0.85%   |
| Hitachi             | 2         | 2      | 0.85%   |
| Hewlett-Packard     | 2         | 2      | 0.85%   |
| Dogfish             | 2         | 2      | 0.85%   |
| Dell                | 2         | 2      | 0.85%   |
| Corsair             | 2         | 5      | 0.85%   |
| BORY                | 2         | 4      | 0.85%   |
| ATP                 | 2         | 2      | 0.85%   |
| Apple               | 2         | 2      | 0.85%   |
| AirDisk             | 2         | 2      | 0.85%   |
| VICKTER             | 1         | 1      | 0.43%   |
| Verbatim            | 1         | 1      | 0.43%   |
| SYNOLOGY            | 1         | 1      | 0.43%   |
| SPCC                | 1         | 2      | 0.43%   |
| Plextor             | 1         | 1      | 0.43%   |
| LITEONIT            | 1         | 1      | 0.43%   |
| Leven               | 1         | 2      | 0.43%   |
| Kston               | 1         | 1      | 0.43%   |
| KingSpec            | 1         | 1      | 0.43%   |
| KeepData            | 1         | 1      | 0.43%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Samsung SSD 840 EVO 250GB               | 7         | 2.76%   |
| Transcend TS128GMSA370 128GB            | 6         | 2.36%   |
| Transcend TS128GMSA230S 128GB           | 5         | 1.97%   |
| SanDisk SSD PLUS 120GB                  | 3         | 1.18%   |
| Kingston SUV500MS120G 120GB             | 3         | 1.18%   |
| Kingston SKC600MS256G 256GB             | 3         | 1.18%   |
| Kingston SA400S37240G 240GB             | 3         | 1.18%   |
| Intel SSDSC2KW128G8 128GB               | 3         | 1.18%   |
| FORESEE 128GB SSD                       | 3         | 1.18%   |
| Crucial CT240BX500SSD1 240GB            | 3         | 1.18%   |
| Crucial CT120BX500SSD1 120GB            | 3         | 1.18%   |
| WDC WD60EFRX-68L0BN1 6TB                | 2         | 0.79%   |
| WDC WD40EFRX-68N32N0 4TB                | 2         | 0.79%   |
| Transcend TS64GMSA230S 64GB             | 2         | 0.79%   |
| Transcend TS256GMTE652T2 256GB          | 2         | 0.79%   |
| Transcend TS256GMSA230S 256GB           | 2         | 0.79%   |
| Transcend TS240GSSD220S 240GB           | 2         | 0.79%   |
| Transcend TS16GMSA370 16GB              | 2         | 0.79%   |
| Transcend TS128GMTS830S 128GB           | 2         | 0.79%   |
| SK hynix BC511 HFM512GDJTNI-82A0A 512GB | 2         | 0.79%   |
| Silicon Motion P10D 1TB                 | 2         | 0.79%   |
| SanDisk SSD PLUS 240GB                  | 2         | 0.79%   |
| Samsung SSD 860 EVO 250GB               | 2         | 0.79%   |
| Samsung SSD 850 EVO 250GB               | 2         | 0.79%   |
| Samsung MZALQ512HBLU-00BL1 512GB        | 2         | 0.79%   |
| Phison SATA SSD 16GB                    | 2         | 0.79%   |
| Kingston SA400S37120G 120GB             | 2         | 0.79%   |
| Intel SSDPEKKF512G8L 512GB              | 2         | 0.79%   |
| Hoodisk SSD 64GB                        | 2         | 0.79%   |
| Hoodisk SSD 128GB                       | 2         | 0.79%   |
| HP RAID 1(1+0) 304GB                    | 2         | 0.79%   |
| Crucial CT500MX500SSD1 500GB            | 2         | 0.79%   |
| Crucial CT250P2SSD8 250GB               | 2         | 0.79%   |
| Crucial CT250MX500SSD1 250GB            | 2         | 0.79%   |
| China SATA SSD 64GB                     | 2         | 0.79%   |
| BORY M500 128G                          | 2         | 0.79%   |
| AirDisk 128GB SSD                       | 2         | 0.79%   |
| WDC WDS500G2B0A-00SM50 500GB            | 1         | 0.39%   |
| WDC WDS240G2G0B-00EPW0 240GB            | 1         | 0.39%   |
| WDC WDS240G2G0A-00JH30 240GB            | 1         | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 16        | 37     | 39.02%  |
| Seagate             | 8         | 23     | 19.51%  |
| HGST                | 5         | 12     | 12.2%   |
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

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Transcend           | 28        | 36     | 18.06%  |
| Samsung Electronics | 24        | 34     | 15.48%  |
| Kingston            | 19        | 31     | 12.26%  |
| Crucial             | 14        | 22     | 9.03%   |
| Intel               | 10        | 13     | 6.45%   |
| SanDisk             | 8         | 14     | 5.16%   |
| Hoodisk             | 5         | 6      | 3.23%   |
| Micron Technology   | 4         | 8      | 2.58%   |
| FORESEE             | 4         | 5      | 2.58%   |
| China               | 4         | 6      | 2.58%   |
| WDC                 | 3         | 4      | 1.94%   |
| Phison              | 3         | 4      | 1.94%   |
| OCZ                 | 2         | 2      | 1.29%   |
| Innodisk            | 2         | 3      | 1.29%   |
| Dogfish             | 2         | 2      | 1.29%   |
| BORY                | 2         | 4      | 1.29%   |
| AirDisk             | 2         | 2      | 1.29%   |
| A-DATA Technology   | 2         | 3      | 1.29%   |
| VICKTER             | 1         | 1      | 0.65%   |
| Verbatim            | 1         | 1      | 0.65%   |
| SPCC                | 1         | 2      | 0.65%   |
| SK hynix            | 1         | 3      | 0.65%   |
| Seagate             | 1         | 7      | 0.65%   |
| Patriot             | 1         | 1      | 0.65%   |
| LITEONIT            | 1         | 1      | 0.65%   |
| Leven               | 1         | 2      | 0.65%   |
| Kston               | 1         | 1      | 0.65%   |
| KingSpec            | 1         | 1      | 0.65%   |
| KeepData            | 1         | 1      | 0.65%   |
| Intenso             | 1         | 1      | 0.65%   |
| GOODRAM             | 1         | 1      | 0.65%   |
| BR                  | 1         | 1      | 0.65%   |
| BIWIN               | 1         | 1      | 0.65%   |
| ATP                 | 1         | 1      | 0.65%   |
| Apple               | 1         | 1      | 0.65%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 145       | 226    | 66.21%  |
| NVMe | 39        | 61     | 17.81%  |
| HDD  | 35        | 87     | 15.98%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 163       | 313    | 80.69%  |
| NVMe | 39        | 61     | 19.31%  |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 149       | 236    | 81.42%  |
| 0.51-1.0   | 15        | 20     | 8.2%    |
| 4.01-10.0  | 7         | 28     | 3.83%   |
| 1.01-2.0   | 6         | 13     | 3.28%   |
| 3.01-4.0   | 4         | 13     | 2.19%   |
| 10.01-20.0 | 2         | 3      | 1.09%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 101-250    | 107       | 50.95%  |
| 251-500    | 38        | 18.1%   |
| 51-100     | 23        | 10.95%  |
| 21-50      | 20        | 9.52%   |
| 1-20       | 13        | 6.19%   |
| 501-1000   | 8         | 3.81%   |
| 1001-2000  | 1         | 0.48%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 1-20     | 199       | 93.87%  |
| 21-50    | 8         | 3.77%   |
| 101-250  | 2         | 0.94%   |
| 251-500  | 1         | 0.47%   |
| 501-1000 | 1         | 0.47%   |
| 51-100   | 1         | 0.47%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| WDC WD60EFRX-68L0BN1 6TB                     | 1         | 1      | 5.88%   |
| WDC WD3200BEVT-22ZCT0 320GB                  | 1         | 1      | 5.88%   |
| WDC WD1600BEVS-00UST0 160GB                  | 1         | 1      | 5.88%   |
| WDC WD1600BEKT-08PVMT1 160GB                 | 1         | 2      | 5.88%   |
| SK hynix SC308 SATA 128GB                    | 1         | 3      | 5.88%   |
| Seagate ST9500325AS 500GB                    | 1         | 1      | 5.88%   |
| SanDisk SSD PLUS 240GB                       | 1         | 1      | 5.88%   |
| Samsung Electronics MZ7PA128HMCD-010H1 128GB | 1         | 1      | 5.88%   |
| OCZ AGILITY3 120GB                           | 1         | 1      | 5.88%   |
| Micron Technology 1100_MTFDDAV256TBN 64GB    | 1         | 2      | 5.88%   |
| Intel SSDSCKKF256G8H 256GB                   | 1         | 2      | 5.88%   |
| Intel SSDPEKKW128G7 128GB                    | 1         | 1      | 5.88%   |
| Hitachi HTS541040G9SA00 40GB                 | 1         | 1      | 5.88%   |
| Hitachi HDS721050CLA660 500GB                | 1         | 1      | 5.88%   |
| HGST HTS725050A7E630 500GB                   | 1         | 5      | 5.88%   |
| A-DATA Technology SU630 240GB                | 1         | 1      | 5.88%   |
| A-DATA Technology ASU800SS-128GT 128GB       | 1         | 1      | 5.88%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 4         | 5      | 23.53%  |
| Intel               | 2         | 3      | 11.76%  |
| Hitachi             | 2         | 2      | 11.76%  |
| A-DATA Technology   | 2         | 2      | 11.76%  |
| SK hynix            | 1         | 3      | 5.88%   |
| Seagate             | 1         | 1      | 5.88%   |
| SanDisk             | 1         | 1      | 5.88%   |
| Samsung Electronics | 1         | 1      | 5.88%   |
| OCZ                 | 1         | 1      | 5.88%   |
| Micron Technology   | 1         | 2      | 5.88%   |
| HGST                | 1         | 5      | 5.88%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 4         | 5      | 50%     |
| Hitachi | 2         | 2      | 25%     |
| Seagate | 1         | 1      | 12.5%   |
| HGST    | 1         | 5      | 12.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 8         | 12     | 47.06%  |
| HDD  | 8         | 13     | 47.06%  |
| NVMe | 1         | 1      | 5.88%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart_bsd/drive_failed.svg)


| Model                     | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Intel SSDPEKKW128G7 128GB | 1         | 1      | 50%     |
| Crucial CT250P2SSD8 250GB | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Intel   | 1         | 1      | 50%     |
| Crucial | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 181       | 340    | 89.16%  |
| Malfunc  | 15        | 26     | 7.39%   |
| Detected | 5         | 6      | 2.46%   |
| Failed   | 2         | 2      | 0.99%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 163       | 65.99%  |
| AMD                         | 32        | 12.96%  |
| Samsung Electronics         | 11        | 4.45%   |
| Broadcom / LSI              | 5         | 2.02%   |
| Silicon Motion              | 4         | 1.62%   |
| Phison Electronics          | 4         | 1.62%   |
| Hewlett-Packard             | 4         | 1.62%   |
| Micron/Crucial Technology   | 3         | 1.21%   |
| Transcend                   | 2         | 0.81%   |
| SK hynix                    | 2         | 0.81%   |
| SanDisk                     | 2         | 0.81%   |
| Marvell Technology Group    | 2         | 0.81%   |
| Lite-On Technology          | 2         | 0.81%   |
| Kingston Technology Company | 2         | 0.81%   |
| ASMedia Technology          | 2         | 0.81%   |
| Toshiba                     | 1         | 0.4%    |
| Realtek Semiconductor       | 1         | 0.4%    |
| Micron Technology           | 1         | 0.4%    |
| MAXIO Technology (Hangzhou) | 1         | 0.4%    |
| Dell                        | 1         | 0.4%    |
| ATP ELECTRONICS             | 1         | 0.4%    |
| ADATA Technology            | 1         | 0.4%    |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 25        | 9.4%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 16        | 6.02%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 14        | 5.26%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 12        | 4.51%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 12        | 4.51%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 10        | 3.76%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 8         | 3.01%   |
| AMD FCH SATA Controller [IDE mode]                                               | 8         | 3.01%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 6         | 2.26%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 6         | 2.26%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 5         | 1.88%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 5         | 1.88%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 5         | 1.88%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 5         | 1.88%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 5         | 1.88%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 4         | 1.5%    |
| Intel Atom Processor C3000 Series SATA Controller 0                              | 4         | 1.5%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 4         | 1.5%    |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 3         | 1.13%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 3         | 1.13%   |
| Intel unknown                                                                    | 3         | 1.13%   |
| Intel Comet Lake SATA AHCI Controller                                            | 3         | 1.13%   |
| Intel Atom processor C2000 AHCI SATA3 Controller                                 | 3         | 1.13%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 3         | 1.13%   |
| HP Smart Array G6 controllers                                                    | 3         | 1.13%   |
| Broadcom / LSI SAS2308 PCI-Express Fusion-MPT SAS-2                              | 3         | 1.13%   |
| Transcend NVMe PCIe SSD 110S/112S/120S/MTE300S/MTE400S/MTE652T2 (DRAM-less)      | 2         | 0.75%   |
| SK hynix BC511 NVMe SSD                                                          | 2         | 0.75%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                              | 2         | 0.75%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)             | 2         | 0.75%   |
| Lite-On M8Pe Series NVMe SSD                                                     | 2         | 0.75%   |
| Intel Tiger Lake-LP SATA Controller                                              | 2         | 0.75%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                                 | 2         | 0.75%   |
| Intel SSD 600P Series                                                            | 2         | 0.75%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 2         | 0.75%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 2         | 0.75%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                       | 2         | 0.75%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 2         | 0.75%   |
| Intel 631xESB/632xESB IDE Controller                                             | 2         | 0.75%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 2         | 0.75%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 174       | 69.05%  |
| NVMe | 43        | 17.06%  |
| IDE  | 21        | 8.33%   |
| RAID | 8         | 3.17%   |
| SAS  | 4         | 1.59%   |
| SCSI | 2         | 0.79%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 169       | 81.64%  |
| AMD     | 36        | 17.39%  |
| ARM     | 1         | 0.48%   |
| Unknown | 1         | 0.48%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| AMD GX-412TC SOC                                | 14        | 6.76%   |
| Intel Celeron CPU J3160 @ 1.60GHz               | 9         | 4.35%   |
| Intel Celeron J4125 CPU @ 2.00GHz               | 7         | 3.38%   |
| Intel Celeron N5105 @ 2.00GHz                   | 6         | 2.9%    |
| AMD GX-420MC SOC                                | 6         | 2.9%    |
| Intel Celeron CPU N3450 @ 1.10GHz               | 4         | 1.93%   |
| Intel Xeon CPU E5620 @ 2.40GHz                  | 3         | 1.45%   |
| Intel N100                                      | 3         | 1.45%   |
| Intel Core i5-7200U CPU @ 2.50GHz               | 3         | 1.45%   |
| Intel Core i5-4200U CPU @ 1.60GHz               | 3         | 1.45%   |
| Intel Celeron J4105 CPU @ 1.50GHz               | 3         | 1.45%   |
| Intel Celeron CPU N3150 @ 1.60GHz               | 3         | 1.45%   |
| Intel Atom CPU C3558 @ 2.20GHz                  | 3         | 1.45%   |
| AMD Ryzen 5 5500U with Radeon Graphics          | 3         | 1.45%   |
| Intel Pentium CPU N4200 @ 1.10GHz               | 2         | 0.97%   |
| Intel Pentium CPU G3220 @ 3.00GHz               | 2         | 0.97%   |
| Intel Core i7-8665U CPU @ 1.90GHz               | 2         | 0.97%   |
| Intel Core i7-8565U CPU @ 1.80GHz               | 2         | 0.97%   |
| Intel Core i5-6600 CPU @ 3.30GHz                | 2         | 0.97%   |
| Intel Core i5-6500 CPU @ 3.20GHz                | 2         | 0.97%   |
| Intel Core i5-6400 CPU @ 2.70GHz                | 2         | 0.97%   |
| Intel Core i5-2400 CPU @ 3.10GHz                | 2         | 0.97%   |
| Intel Core i5-10310U CPU @ 1.70GHz              | 2         | 0.97%   |
| Intel Core i5-10210U CPU @ 1.60GHz              | 2         | 0.97%   |
| Intel Core i5 CPU M 520 @ 2.40GHz               | 2         | 0.97%   |
| Intel Core i3-4130 CPU @ 3.40GHz                | 2         | 0.97%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz              | 2         | 0.97%   |
| Intel Celeron N4100 CPU @ 1.10GHz               | 2         | 0.97%   |
| Intel Celeron CPU J1900 @ 1.99GHz               | 2         | 0.97%   |
| Intel Atom CPU E3845 @ 1.91GHz                  | 2         | 0.97%   |
| AMD Ryzen Embedded V1500B                       | 2         | 0.97%   |
| AMD Ryzen 5 PRO 2500U w/ Radeon Vega Mobile Gfx | 2         | 0.97%   |
| AMD GX-217GA SOC with Radeon HD Graphics        | 2         | 0.97%   |
| Intel Xeon E-2236 CPU @ 3.40GHz                 | 1         | 0.48%   |
| Intel Xeon E-2136 CPU @ 3.30GHz                 | 1         | 0.48%   |
| Intel Xeon D-2123IT CPU @ 2.20GHz               | 1         | 0.48%   |
| Intel Xeon CPU L5640 @ 2.27GHz                  | 1         | 0.48%   |
| Intel Xeon CPU E5540 @ 2.53GHz                  | 1         | 0.48%   |
| Intel Xeon CPU E5420 @ 2.50GHz                  | 1         | 0.48%   |
| Intel Xeon CPU E5320 @ 1.86GHz                  | 1         | 0.48%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Celeron           | 49        | 23.67%  |
| Intel Core i5           | 39        | 18.84%  |
| AMD GX                  | 22        | 10.63%  |
| Intel Xeon              | 17        | 8.21%   |
| Intel Core i7           | 17        | 8.21%   |
| Intel Core i3           | 14        | 6.76%   |
| Intel Atom              | 11        | 5.31%   |
| Other                   | 9         | 4.35%   |
| Intel Pentium           | 7         | 3.38%   |
| Intel Core 2 Duo        | 3         | 1.45%   |
| AMD Ryzen 5             | 3         | 1.45%   |
| AMD Ryzen Embedded      | 2         | 0.97%   |
| AMD Ryzen 7             | 2         | 0.97%   |
| AMD Ryzen 5 PRO         | 2         | 0.97%   |
| Intel Pentium Silver    | 1         | 0.48%   |
| Intel Pentium Dual-Core | 1         | 0.48%   |
| Intel Pentium 4         | 1         | 0.48%   |
| Intel Genuine           | 1         | 0.48%   |
| Intel Core 2            | 1         | 0.48%   |
| ARM Cortex              | 1         | 0.48%   |
| AMD Ryzen Threadripper  | 1         | 0.48%   |
| AMD Opteron             | 1         | 0.48%   |
| AMD FX                  | 1         | 0.48%   |
| AMD Athlon              | 1         | 0.48%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 122       | 58.94%  |
| 2       | 53        | 25.6%   |
| 8       | 12        | 5.8%    |
| Unknown | 6         | 2.9%    |
| 12      | 5         | 2.42%   |
| 6       | 5         | 2.42%   |
| 64      | 1         | 0.48%   |
| 16      | 1         | 0.48%   |
| 14      | 1         | 0.48%   |
| 1       | 1         | 0.48%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 194       | 93.72%  |
| 2       | 7         | 3.38%   |
| Unknown | 6         | 2.9%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 130       | 62.8%   |
| 2       | 70        | 33.82%  |
| Unknown | 7         | 3.38%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 29        | 14.01%  |
| Silvermont    | 24        | 11.59%  |
| Puma          | 20        | 9.66%   |
| Haswell       | 16        | 7.73%   |
| Unknown       | 16        | 7.73%   |
| Goldmont plus | 14        | 6.76%   |
| Goldmont      | 14        | 6.76%   |
| Skylake       | 13        | 6.28%   |
| IvyBridge     | 10        | 4.83%   |
| SandyBridge   | 9         | 4.35%   |
| Westmere      | 7         | 3.38%   |
| Zen           | 6         | 2.9%    |
| Broadwell     | 6         | 2.9%    |
| Penryn        | 5         | 2.42%   |
| TigerLake     | 3         | 1.45%   |
| Excavator     | 3         | 1.45%   |
| Jaguar        | 2         | 0.97%   |
| IceLake       | 2         | 0.97%   |
| Core          | 2         | 0.97%   |
| CometLake     | 2         | 0.97%   |
| Zen+          | 1         | 0.48%   |
| Zen 2         | 1         | 0.48%   |
| NetBurst      | 1         | 0.48%   |
| Nehalem       | 1         | 0.48%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 139       | 74.33%  |
| AMD                        | 20        | 10.7%   |
| ASPEED Technology          | 15        | 8.02%   |
| Nvidia                     | 8         | 4.28%   |
| Matrox Electronics Systems | 4         | 2.14%   |
| Huawei Technologies        | 1         | 0.53%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 16        | 8.51%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 15        | 7.98%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 13        | 6.91%   |
| Intel HD Graphics 530                                                                    | 8         | 4.26%   |
| Intel HD Graphics 500                                                                    | 8         | 4.26%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 7         | 3.72%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 6         | 3.19%   |
| Intel JasperLake [UHD Graphics]                                                          | 6         | 3.19%   |
| AMD ES1000                                                                               | 6         | 3.19%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 2.66%   |
| Intel HD Graphics 620                                                                    | 5         | 2.66%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 2.66%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 5         | 2.66%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 2.66%   |
| Intel Alder Lake-N [UHD Graphics]                                                        | 4         | 2.13%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 4         | 2.13%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 3         | 1.6%    |
| Intel UHD Graphics 620                                                                   | 3         | 1.6%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 1.6%    |
| Intel HD Graphics 630                                                                    | 3         | 1.6%    |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 1.6%    |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 3         | 1.6%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 1.6%    |
| AMD Lucienne                                                                             | 3         | 1.6%    |
| Matrox Electronics Systems MGA G200EH                                                    | 2         | 1.06%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 1.06%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 2         | 1.06%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 1.06%   |
| Intel HD Graphics 510                                                                    | 2         | 1.06%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2         | 1.06%   |
| Intel Apollo Lake [HD Graphics 505]                                                      | 2         | 1.06%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 2         | 1.06%   |
| AMD Kabini [Radeon HD 8280E]                                                             | 2         | 1.06%   |
| Nvidia NV28 [GeForce4 Ti 4200 AGP 8x]                                                    | 1         | 0.53%   |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                                    | 1         | 0.53%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 1         | 0.53%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1         | 0.53%   |
| Nvidia GP104GLM [Quadro P4000 Mobile]                                                    | 1         | 0.53%   |
| Nvidia GP104GL [Tesla P4]                                                                | 1         | 0.53%   |
| Nvidia GM107M [GeForce GTX 860M]                                                         | 1         | 0.53%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| 1 x Intel                    | 132       | 63.77%  |
| Other                        | 26        | 12.56%  |
| 1 x AMD                      | 19        | 9.18%   |
| 1 x ASPEED                   | 12        | 5.8%    |
| 1 x Nvidia                   | 5         | 2.42%   |
| 1 x Matrox                   | 4         | 1.93%   |
| 2 x Intel                    | 3         | 1.45%   |
| Intel + ASPEED               | 2         | 0.97%   |
| Nvidia + Huawei Technologies | 1         | 0.48%   |
| Nvidia + ASPEED              | 1         | 0.48%   |
| Intel + Nvidia               | 1         | 0.48%   |
| Intel + AMD                  | 1         | 0.48%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 177       | 85.51%  |
| Unknown     | 26        | 12.56%  |
| Proprietary | 4         | 1.93%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 200       | 95.69%  |
| 0.51-1.0   | 3         | 1.44%   |
| 3.01-4.0   | 2         | 0.96%   |
| 1.01-2.0   | 2         | 0.96%   |
| 7.01-8.0   | 1         | 0.48%   |
| 0.01-0.5   | 1         | 0.48%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| AU Optronics        | 5         | 15.63%  |
| Samsung Electronics | 4         | 12.5%   |
| Lenovo              | 4         | 12.5%   |
| LG Display          | 3         | 9.38%   |
| Dell                | 3         | 9.38%   |
| Chimei Innolux      | 3         | 9.38%   |
| BOE                 | 3         | 9.38%   |
| Philips             | 2         | 6.25%   |
| Unknown             | 1         | 3.13%   |
| PANDA               | 1         | 3.13%   |
| Medion              | 1         | 3.13%   |
| BenQ                | 1         | 3.13%   |
| Apple               | 1         | 3.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics C34J79x SAM0F1E 3440x1440 800x330mm 34.1-inch    | 2         | 6.06%   |
| LG Display LCD Monitor LGD064C 1920x1080 340x190mm 15.3-inch         | 2         | 6.06%   |
| AU Optronics LCD Monitor AUO2036 2560x1440 310x170mm 13.9-inch       | 2         | 6.06%   |
| Unknown LCD Monitor Sharp 3840x2160                                  | 1         | 3.03%   |
| Samsung Electronics SyncMaster SAM021E 1680x1050 430x270mm 20.0-inch | 1         | 3.03%   |
| Samsung Electronics CJG9S SAM9596 3840x1080                          | 1         | 3.03%   |
| Philips PHL BDM4037U PHLC142 3840x2160 890x500mm 40.2-inch           | 1         | 3.03%   |
| Philips PHL 273V7 PHLC156 1920x1080 600x340mm 27.2-inch              | 1         | 3.03%   |
| PANDA LM116LF3L02 NCP000A 1920x1080 260x150mm 11.8-inch              | 1         | 3.03%   |
| Medion MD22321 MEA8302 1920x1080 700x390mm 31.5-inch                 | 1         | 3.03%   |
| LG Display LCD Monitor LGD0353 1366x768 350x190mm 15.7-inch          | 1         | 3.03%   |
| Lenovo LCD Monitor LEN40B0 1366x768 340x190mm 15.3-inch              | 1         | 3.03%   |
| Lenovo LCD Monitor LEN4043 1400x1050 300x230mm 14.9-inch             | 1         | 3.03%   |
| Lenovo LCD Monitor LEN4036 1440x900 300x190mm 14.0-inch              | 1         | 3.03%   |
| Lenovo LCD Monitor LEN4033 1440x900 300x190mm 14.0-inch              | 1         | 3.03%   |
| Dell U2715H DELD069 2560x1440 600x340mm 27.2-inch                    | 1         | 3.03%   |
| Dell U2715H DELD066 2560x1440 600x340mm 27.2-inch                    | 1         | 3.03%   |
| Dell P2719H DEL4185 1920x1080 600x340mm 27.2-inch                    | 1         | 3.03%   |
| Dell 2001FP DELA007 1600x1200 410x310mm 20.2-inch                    | 1         | 3.03%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch     | 1         | 3.03%   |
| Chimei Innolux LCD Monitor CMN1484 1600x900 310x170mm 13.9-inch      | 1         | 3.03%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch      | 1         | 3.03%   |
| BOE LCD Monitor BOE08D7 1920x1080 310x170mm 13.9-inch                | 1         | 3.03%   |
| BOE LCD Monitor BOE0791 1920x1080 310x170mm 13.9-inch                | 1         | 3.03%   |
| BOE LCD Monitor BOE0714 1920x1080 310x170mm 13.9-inch                | 1         | 3.03%   |
| BenQ GW2765 BNQ78D6 2560x1440 600x340mm 27.2-inch                    | 1         | 3.03%   |
| AU Optronics LCD Monitor AUO408D 1920x1080 310x170mm 13.9-inch       | 1         | 3.03%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 310x170mm 13.9-inch       | 1         | 3.03%   |
| AU Optronics LCD Monitor 1920x1080                                   | 1         | 3.03%   |
| Apple iMac APPA007 2560x1440 600x340mm 27.2-inch                     | 1         | 3.03%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 12        | 38.71%  |
| 2560x1440 (QHD)    | 5         | 16.13%  |
| 1366x768 (WXGA)    | 3         | 9.68%   |
| 3840x2160 (4K)     | 2         | 6.45%   |
| 3440x1440          | 2         | 6.45%   |
| 1440x900 (WXGA+)   | 2         | 6.45%   |
| 3840x1080          | 1         | 3.23%   |
| 1680x1050 (WSXGA+) | 1         | 3.23%   |
| 1600x900 (HD+)     | 1         | 3.23%   |
| 1600x1200          | 1         | 3.23%   |
| 1400x1050          | 1         | 3.23%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 9         | 28.13%  |
| 27      | 5         | 15.63%  |
| 15      | 4         | 12.5%   |
| 14      | 3         | 9.38%   |
| Unknown | 3         | 9.38%   |
| 34      | 2         | 6.25%   |
| 20      | 2         | 6.25%   |
| 11      | 2         | 6.25%   |
| 40      | 1         | 3.13%   |
| 31      | 1         | 3.13%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 13        | 40.63%  |
| 501-600     | 5         | 15.63%  |
| 201-300     | 5         | 15.63%  |
| Unknown     | 3         | 9.38%   |
| 701-800     | 2         | 6.25%   |
| 401-500     | 2         | 6.25%   |
| 801-900     | 1         | 3.13%   |
| 601-700     | 1         | 3.13%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 20        | 66.67%  |
| 16/10   | 3         | 10%     |
| 4/3     | 2         | 6.67%   |
| 21/9    | 2         | 6.67%   |
| Unknown | 2         | 6.67%   |
| 32/9    | 1         | 3.33%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 11        | 34.38%  |
| 301-350        | 5         | 15.63%  |
| 351-500        | 3         | 9.38%   |
| 91-100         | 3         | 9.38%   |
| Unknown        | 3         | 9.38%   |
| 51-60          | 2         | 6.25%   |
| 151-200        | 2         | 6.25%   |
| 101-110        | 2         | 6.25%   |
| 501-1000       | 1         | 3.13%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 121-160 | 12        | 37.5%   |
| 101-120 | 8         | 25%     |
| 51-100  | 6         | 18.75%  |
| 161-240 | 3         | 9.38%   |
| Unknown | 3         | 9.38%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 176       | 84.62%  |
| 1     | 26        | 12.5%   |
| 2     | 6         | 2.88%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 170       | 63.2%   |
| Realtek Semiconductor | 64        | 23.79%  |
| Broadcom              | 10        | 3.72%   |
| Qualcomm Atheros      | 6         | 2.23%   |
| TP-Link               | 2         | 0.74%   |
| LG Electronics        | 2         | 0.74%   |
| Edimax Technology     | 2         | 0.74%   |
| AMD                   | 2         | 0.74%   |
| Seeed Technology      | 1         | 0.37%   |
| QLogic                | 1         | 0.37%   |
| Mellanox Technologies | 1         | 0.37%   |
| MediaTek              | 1         | 0.37%   |
| Hewlett-Packard       | 1         | 0.37%   |
| Google                | 1         | 0.37%   |
| Dresden Elektronik    | 1         | 0.37%   |
| Dell                  | 1         | 0.37%   |
| Davicom Semiconductor | 1         | 0.37%   |
| AVM                   | 1         | 0.37%   |
| Arduino SA            | 1         | 0.37%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 56        | 16.47%  |
| Intel I211 Gigabit Network Connection                             | 40        | 11.76%  |
| Intel I210 Gigabit Network Connection                             | 33        | 9.71%   |
| Intel I350 Gigabit Network Connection                             | 10        | 2.94%   |
| Intel Ethernet Controller I225-V                                  | 9         | 2.65%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9         | 2.65%   |
| Intel Ethernet Controller I226-V                                  | 8         | 2.35%   |
| Intel Wireless 7265                                               | 7         | 2.06%   |
| Intel Ethernet Connection (2) I219-LM                             | 6         | 1.76%   |
| Intel Wireless 7260                                               | 5         | 1.47%   |
| Intel Wireless 3165                                               | 5         | 1.47%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 5         | 1.47%   |
| Intel 82576 Gigabit Network Connection                            | 5         | 1.47%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 5         | 1.47%   |
| Intel Wireless 8265 / 8275                                        | 4         | 1.18%   |
| Intel I210 Gigabit Fiber Network Connection                       | 4         | 1.18%   |
| Intel Ethernet Connection X553 1GbE                               | 4         | 1.18%   |
| Intel 82574L Gigabit Network Connection                           | 4         | 1.18%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 0.88%   |
| Intel Wireless 3160                                               | 3         | 0.88%   |
| Intel Wi-Fi 6 AX200                                               | 3         | 0.88%   |
| Intel Ethernet Connection I354                                    | 3         | 0.88%   |
| Intel Ethernet Connection (6) I219-LM                             | 3         | 0.88%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 0.88%   |
| Intel Centrino Ultimate-N 6300                                    | 3         | 0.88%   |
| Intel Centrino Advanced-N 6235                                    | 3         | 0.88%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 0.88%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                            | 2         | 0.59%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 2         | 0.59%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.59%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 2         | 0.59%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 2         | 0.59%   |
| LG Optimus Android Phone [USB tethering mode]                     | 2         | 0.59%   |
| Intel Wireless-AC 9260                                            | 2         | 0.59%   |
| Intel Gemini Lake PCH CNVi WiFi                                   | 2         | 0.59%   |
| Intel Ethernet Connection I217-V                                  | 2         | 0.59%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 0.59%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 0.59%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 0.59%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 0.59%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 50        | 68.49%  |
| Realtek Semiconductor | 11        | 15.07%  |
| Qualcomm Atheros      | 6         | 8.22%   |
| TP-Link               | 2         | 2.74%   |
| Edimax Technology     | 2         | 2.74%   |
| MediaTek              | 1         | 1.37%   |
| Dell                  | 1         | 1.37%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Intel Wireless 7265                                             | 7         | 9.46%   |
| Intel Wireless 7260                                             | 5         | 6.76%   |
| Intel Wireless 3165                                             | 5         | 6.76%   |
| Intel Wireless 8265 / 8275                                      | 4         | 5.41%   |
| Intel Wireless 3160                                             | 3         | 4.05%   |
| Intel Wi-Fi 6 AX200                                             | 3         | 4.05%   |
| Intel Centrino Advanced-N 6235                                  | 3         | 4.05%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                          | 2         | 2.7%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter        | 2         | 2.7%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter        | 2         | 2.7%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter             | 2         | 2.7%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter                | 2         | 2.7%    |
| Intel Wireless-AC 9260                                          | 2         | 2.7%    |
| Intel Gemini Lake PCH CNVi WiFi                                 | 2         | 2.7%    |
| Intel Comet Lake PCH-LP CNVi WiFi                               | 2         | 2.7%    |
| Intel Centrino Ultimate-N 6300                                  | 2         | 2.7%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                        | 2         | 2.7%    |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]  | 2         | 2.7%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter        | 1         | 1.35%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter        | 1         | 1.35%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                 | 1         | 1.35%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                          | 1         | 1.35%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                         | 1         | 1.35%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                      | 1         | 1.35%   |
| Qualcomm Atheros QCA986x/988x 802.11ac Wireless Network Adapter | 1         | 1.35%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter      | 1         | 1.35%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                | 1         | 1.35%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)  | 1         | 1.35%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                         | 1         | 1.35%   |
| Intel Wireless 8260                                             | 1         | 1.35%   |
| Intel WiFi Link 5100                                            | 1         | 1.35%   |
| Intel Wi-Fi 6 AX201                                             | 1         | 1.35%   |
| Intel Ultimate N WiFi Link 5300                                 | 1         | 1.35%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection           | 1         | 1.35%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                 | 1         | 1.35%   |
| Intel Centrino Wireless-N 2230                                  | 1         | 1.35%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                   | 1         | 1.35%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                    | 1         | 1.35%   |
| Intel Centrino Advanced-N 6200                                  | 1         | 1.35%   |
| Dell Wireless 5550 HSPA+ Mini-Card Network Adapter              | 1         | 1.35%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 145       | 66.51%  |
| Realtek Semiconductor | 59        | 27.06%  |
| Broadcom              | 10        | 4.59%   |
| AMD                   | 2         | 0.92%   |
| QLogic                | 1         | 0.46%   |
| Davicom Semiconductor | 1         | 0.46%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 56        | 21.96%  |
| Intel I211 Gigabit Network Connection                             | 40        | 15.69%  |
| Intel I210 Gigabit Network Connection                             | 33        | 12.94%  |
| Intel I350 Gigabit Network Connection                             | 10        | 3.92%   |
| Intel Ethernet Controller I225-V                                  | 9         | 3.53%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9         | 3.53%   |
| Intel Ethernet Controller I226-V                                  | 8         | 3.14%   |
| Intel Ethernet Connection (2) I219-LM                             | 6         | 2.35%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 5         | 1.96%   |
| Intel 82576 Gigabit Network Connection                            | 5         | 1.96%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 5         | 1.96%   |
| Intel I210 Gigabit Fiber Network Connection                       | 4         | 1.57%   |
| Intel Ethernet Connection X553 1GbE                               | 4         | 1.57%   |
| Intel 82574L Gigabit Network Connection                           | 4         | 1.57%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 1.18%   |
| Intel Ethernet Connection I354                                    | 3         | 1.18%   |
| Intel Ethernet Connection (6) I219-LM                             | 3         | 1.18%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 1.18%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 1.18%   |
| Intel Ethernet Connection I217-V                                  | 2         | 0.78%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 0.78%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 0.78%   |
| Intel 82583V Gigabit Network Connection                           | 2         | 0.78%   |
| Intel 82567LM Gigabit Network Connection                          | 2         | 0.78%   |
| AMD XGMAC 10GbE Controller                                        | 2         | 0.78%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 0.39%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.39%   |
| QLogic cLOM8214 1/10GbE Controller                                | 1         | 0.39%   |
| Intel Ethernet Connection X722 for 10GbE SFP+                     | 1         | 0.39%   |
| Intel Ethernet Connection X722 for 10GBASE-T                      | 1         | 0.39%   |
| Intel Ethernet Connection X552/X557-AT 10GBASE-T                  | 1         | 0.39%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.39%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.39%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.39%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.39%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.39%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 0.39%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 0.39%   |
| Intel Ethernet Connection (14) I219-V                             | 1         | 0.39%   |
| Intel Ethernet Connection (12) I219-V                             | 1         | 0.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 199       | 71.07%  |
| WiFi     | 70        | 25%     |
| Modem    | 6         | 2.14%   |
| Unknown  | 5         | 1.79%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 193       | 88.94%  |
| WiFi     | 23        | 10.6%   |
| Modem    | 1         | 0.46%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 53        | 25.6%   |
| 4     | 49        | 23.67%  |
| 3     | 45        | 21.74%  |
| 1     | 18        | 8.7%    |
| 6     | 17        | 8.21%   |
| 8     | 9         | 4.35%   |
| 5     | 8         | 3.86%   |
| 7     | 3         | 1.45%   |
| 9     | 2         | 0.97%   |
| 0     | 2         | 0.97%   |
| 10    | 1         | 0.48%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 197       | 93.36%  |
| Yes  | 14        | 6.64%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


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

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


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

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 125       | 82.78%  |
| AMD                                          | 16        | 10.6%   |
| Nvidia                                       | 4         | 2.65%   |
| Plantronics                                  | 3         | 1.99%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.66%   |
| Lenovo                                       | 1         | 0.66%   |
| Creative Labs                                | 1         | 0.66%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 15        | 8.52%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 14        | 7.95%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 10        | 5.68%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 9         | 5.11%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 9         | 5.11%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 8         | 4.55%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 7         | 3.98%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 7         | 3.98%   |
| Intel Jasper Lake HD Audio                                                                        | 6         | 3.41%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 6         | 3.41%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 6         | 3.41%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 6         | 3.41%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 5         | 2.84%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 5         | 2.84%   |
| Intel 8 Series HD Audio Controller                                                                | 5         | 2.84%   |
| Intel Alder Lake-N HD Graphics SGPC                                                               | 4         | 2.27%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4         | 2.27%   |
| Plantronics Plantronics Blackwire 315.1                                                           | 3         | 1.7%    |
| Nvidia GP107GL High Definition Audio Controller                                                   | 3         | 1.7%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 1.7%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 1.7%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 1.7%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 1.7%    |
| AMD Kabini HDMI/DP Audio                                                                          | 3         | 1.7%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 2         | 1.14%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 1.14%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 1.14%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 1.14%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 1.14%   |
| Intel 200 Series PCH HD Audio                                                                     | 2         | 1.14%   |
| AMD FCH Azalia Controller                                                                         | 2         | 1.14%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 1.14%   |
| Zoran Co. Personal Media Division (Nogatech) USB Audio and HID                                    | 1         | 0.57%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.57%   |
| Lenovo Realtek USB Audio                                                                          | 1         | 0.57%   |
| Intel Smart Sound Technology (SST) Audio Controller                                               | 1         | 0.57%   |
| Intel Comet Lake PCH-V cAVS                                                                       | 1         | 0.57%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.57%   |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 1         | 0.57%   |
| Intel Broadwell-U Audio Controller                                                                | 1         | 0.57%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 31        | 15.5%   |
| Crucial             | 27        | 13.5%   |
| Unknown             | 24        | 12%     |
| Kingston            | 23        | 11.5%   |
| SK hynix            | 21        | 10.5%   |
| Micron Technology   | 19        | 9.5%    |
| Unknown (ABCD)      | 11        | 5.5%    |
| Corsair             | 10        | 5%      |
| Unknown             | 6         | 3%      |
| Transcend           | 5         | 2.5%    |
| A-DATA Technology   | 4         | 2%      |
| G.Skill             | 3         | 1.5%    |
| Ramaxel Technology  | 2         | 1%      |
| Nanya Technology    | 2         | 1%      |
| tigo                | 1         | 0.5%    |
| Mushkin             | 1         | 0.5%    |
| Miron               | 1         | 0.5%    |
| Lexar Co Limited    | 1         | 0.5%    |
| Kingmax             | 1         | 0.5%    |
| Kimtigo             | 1         | 0.5%    |
| GOODRAM             | 1         | 0.5%    |
| GeIL                | 1         | 0.5%    |
| Elpida              | 1         | 0.5%    |
| DSL                 | 1         | 0.5%    |
| Avant               | 1         | 0.5%    |
| ATP                 | 1         | 0.5%    |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR3 2400MT/s | 11        | 5.37%   |
| Unknown                                                           | 6         | 2.93%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                       | 5         | 2.44%   |
| Kingston RAM CBD26D4S9S8K1C-8 8GB SODIMM DDR4 2667MT/s            | 3         | 1.46%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                         | 2         | 0.98%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                         | 2         | 0.98%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                         | 2         | 0.98%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                         | 2         | 0.98%   |
| Unknown RAM AW24P64F8BLK0S 8GB DIMM DDR3 1600MT/s                 | 2         | 0.98%   |
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s               | 2         | 0.98%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                     | 2         | 0.98%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s            | 2         | 0.98%   |
| SK hynix RAM HMT125U6BFR8C-G7 2GB DIMM DDR3 1067MT/s              | 2         | 0.98%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                    | 2         | 0.98%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s            | 2         | 0.98%   |
| Samsung RAM M471A2G44AM0-CTD 16GB SODIMM DDR4 2667MT/s            | 2         | 0.98%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s             | 2         | 0.98%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1333MT/s               | 2         | 0.98%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s              | 2         | 0.98%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s           | 2         | 0.98%   |
| Crucial RAM CT8G4SFS824A.M8FRS 8GB DIMM DDR4 2400MT/s             | 2         | 0.98%   |
| Crucial RAM CT4G4SFS824A.C8FBD 4GB SODIMM DDR4 2400MT/s           | 2         | 0.98%   |
| Crucial RAM CT16G48C40S5.M8A1 16GB SODIMM DDR5 4800MT/s           | 2         | 0.98%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s           | 2         | 0.98%   |
| Unknown RAM X4B08QD8BNVFSO-7-TO1 8GB DIMM DDR4 2933MT/s           | 1         | 0.49%   |
| Unknown RAM Module 8GB 1600MT/s                                   | 1         | 0.49%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s                      | 1         | 0.49%   |
| Unknown RAM Module 4GB SODIMM DDR3 667MT/s                        | 1         | 0.49%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                         | 1         | 0.49%   |
| Unknown RAM Module 4GB DIMM DDR3 1066MT/s                         | 1         | 0.49%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                      | 1         | 0.49%   |
| Unknown RAM Module 2048MB SODIMM DDR2                             | 1         | 0.49%   |
| Unknown RAM Module 1GB DIMM DDR2 1033MT/s                         | 1         | 0.49%   |
| Unknown RAM Module 1024MB SODIMM DDR2                             | 1         | 0.49%   |
| Transcend RAM TS512MLK72V6H 4GB DIMM DDR3 1600MT/s                | 1         | 0.49%   |
| Transcend RAM TS2GSH64V1B 16GB SODIMM DDR4 2133MT/s               | 1         | 0.49%   |
| Transcend RAM JM3200HSE-16G 16GB SODIMM DDR4 3200MT/s             | 1         | 0.49%   |
| tigo RAM 1600Mhz-4G 4GB SODIMM DDR3 1600MT/s                      | 1         | 0.49%   |
| SK hynix RAM Module 2GB DIMM DDR3 1333MT/s                        | 1         | 0.49%   |
| SK hynix RAM HMT451U6DFR8A-PB 4GB DIMM DDR3 1600MT/s              | 1         | 0.49%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 83        | 46.11%  |
| DDR4    | 72        | 40%     |
| LPDDR4  | 15        | 8.33%   |
| DDR5    | 4         | 2.22%   |
| DDR2    | 3         | 1.67%   |
| LPDDR3  | 1         | 0.56%   |
| DRAM    | 1         | 0.56%   |
| Unknown | 1         | 0.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 91        | 50.84%  |
| DIMM         | 80        | 44.69%  |
| Row Of Chips | 5         | 2.79%   |
| Unknown      | 2         | 1.12%   |
| Chip         | 1         | 0.56%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 74        | 39.15%  |
| 4096  | 52        | 27.51%  |
| 16384 | 33        | 17.46%  |
| 2048  | 19        | 10.05%  |
| 32768 | 7         | 3.7%    |
| 1024  | 3         | 1.59%   |
| 6144  | 1         | 0.53%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 50        | 26.88%  |
| 2400    | 34        | 18.28%  |
| 1333    | 28        | 15.05%  |
| 2667    | 24        | 12.9%   |
| 3200    | 19        | 10.22%  |
| 2133    | 7         | 3.76%   |
| 4800    | 4         | 2.15%   |
| 1067    | 4         | 2.15%   |
| 1867    | 2         | 1.08%   |
| 1334    | 2         | 1.08%   |
| Unknown | 2         | 1.08%   |
| 65535   | 1         | 0.54%   |
| 4000    | 1         | 0.54%   |
| 3000    | 1         | 0.54%   |
| 2933    | 1         | 0.54%   |
| 2666    | 1         | 0.54%   |
| 1866    | 1         | 0.54%   |
| 1066    | 1         | 0.54%   |
| 1033    | 1         | 0.54%   |
| 800     | 1         | 0.54%   |
| 667     | 1         | 0.54%   |

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

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


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

![Fingerprint Vendor](./All/images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 5         | 35.71%  |
| Upek                       | 3         | 21.43%  |
| Synaptics                  | 3         | 21.43%  |
| Shenzhen Goodix Technology | 2         | 14.29%  |
| STMicroelectronics         | 1         | 7.14%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader               | 3         | 21.43%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor   | 3         | 21.43%  |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 2         | 14.29%  |
| Shenzhen Goodix Fingerprint Reader                       | 2         | 14.29%  |
| Validity Sensors VFS5011 Fingerprint Reader              | 1         | 7.14%   |
| Validity Sensors VFS491                                  | 1         | 7.14%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader        | 1         | 7.14%   |
| STMicroelectronics Fingerprint Reader                    | 1         | 7.14%   |

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
| 1     | 84        | 38.89%  |
| 0     | 67        | 31.02%  |
| 2     | 39        | 18.06%  |
| 3     | 21        | 9.72%   |
| 4     | 4         | 1.85%   |
| 5     | 1         | 0.46%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 127       | 61.65%  |
| Bluetooth                | 22        | 10.68%  |
| Net/wireless             | 16        | 7.77%   |
| Card reader              | 16        | 7.77%   |
| Fingerprint reader       | 14        | 6.8%    |
| Firewire controller      | 4         | 1.94%   |
| Network                  | 3         | 1.46%   |
| Graphics card            | 2         | 0.97%   |
| Sound                    | 1         | 0.49%   |
| Net/ethernet             | 1         | 0.49%   |

