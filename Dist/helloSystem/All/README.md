helloSystem - Tested Hardware & Statistics
------------------------------------------

A project to collect tested hardware configurations for helloSystem.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/helloSystem/Desktop/README.md) and [notebooks](/Dist/helloSystem/Notebook/README.md).

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

Total: 2131

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Lenovo        | ThinkCentre M81 5049D7G     | Desktop     | [60de9490a9](https://bsd-hardware.info/?probe=60de9490a9) | Sep 29, 2023 |
| ASUSTek       | K40IN                       | Notebook    | [f98d4be34d](https://bsd-hardware.info/?probe=f98d4be34d) | Sep 29, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [e587bca33a](https://bsd-hardware.info/?probe=e587bca33a) | Sep 29, 2023 |
| Dell          | Latitude E6430              | Notebook    | [bec165c243](https://bsd-hardware.info/?probe=bec165c243) | Sep 27, 2023 |
| HP            | 8055                        | Desktop     | [b86f4f02a5](https://bsd-hardware.info/?probe=b86f4f02a5) | Sep 26, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [5cd50ed5b5](https://bsd-hardware.info/?probe=5cd50ed5b5) | Sep 24, 2023 |
| ASUSTek       | Z170-A                      | Desktop     | [3802fe676c](https://bsd-hardware.info/?probe=3802fe676c) | Sep 23, 2023 |
| HP            | 18E8                        | Desktop     | [7a96c7f43a](https://bsd-hardware.info/?probe=7a96c7f43a) | Sep 21, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [8a3d3b3d0d](https://bsd-hardware.info/?probe=8a3d3b3d0d) | Sep 21, 2023 |
| Lenovo        | ThinkPad P50 20EN0012US     | Notebook    | [a1945198c6](https://bsd-hardware.info/?probe=a1945198c6) | Sep 21, 2023 |
| HP            | 18E8                        | Desktop     | [cb4a5de309](https://bsd-hardware.info/?probe=cb4a5de309) | Sep 21, 2023 |
| Bochs         | Unknown                     | Desktop     | [65f7da4601](https://bsd-hardware.info/?probe=65f7da4601) | Sep 20, 2023 |
| HP            | 83F3                        | Desktop     | [4d1df66f57](https://bsd-hardware.info/?probe=4d1df66f57) | Sep 20, 2023 |
| Dell          | 0VRWRC A01                  | Desktop     | [6c85a42e64](https://bsd-hardware.info/?probe=6c85a42e64) | Sep 19, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [211b0f3e9c](https://bsd-hardware.info/?probe=211b0f3e9c) | Sep 19, 2023 |
| AZW           | U59                         | Desktop     | [ae0d8568d1](https://bsd-hardware.info/?probe=ae0d8568d1) | Sep 15, 2023 |
| Lenovo        | ThinkPad Edge E531 68852... | Notebook    | [cc3bef6a45](https://bsd-hardware.info/?probe=cc3bef6a45) | Sep 15, 2023 |
| AZW           | U59                         | Desktop     | [7e094459f9](https://bsd-hardware.info/?probe=7e094459f9) | Sep 14, 2023 |
| Dell          | 04YP6J A02                  | Desktop     | [0933e1164a](https://bsd-hardware.info/?probe=0933e1164a) | Sep 13, 2023 |
| Gigabyte      | H55M-S2H                    | Desktop     | [1b0fcd812e](https://bsd-hardware.info/?probe=1b0fcd812e) | Sep 13, 2023 |
| Gigabyte      | H55M-S2H                    | Desktop     | [92ce33c604](https://bsd-hardware.info/?probe=92ce33c604) | Sep 13, 2023 |
| OEGStone      | doceo 510                   | Notebook    | [9f3b47e30f](https://bsd-hardware.info/?probe=9f3b47e30f) | Sep 13, 2023 |
| Lenovo        | 3140 NOK                    | Desktop     | [945ad170d7](https://bsd-hardware.info/?probe=945ad170d7) | Sep 10, 2023 |
| Lenovo        | 3140 NOK                    | Desktop     | [3f9dcefb8e](https://bsd-hardware.info/?probe=3f9dcefb8e) | Sep 10, 2023 |
| Acer          | Monserrat                   | Notebook    | [9c79dbac8b](https://bsd-hardware.info/?probe=9c79dbac8b) | Sep 10, 2023 |
| Acer          | AOHAPPY2                    | Notebook    | [d615a8daba](https://bsd-hardware.info/?probe=d615a8daba) | Sep 10, 2023 |
| Acer          | AOHAPPY2                    | Notebook    | [6f5db06303](https://bsd-hardware.info/?probe=6f5db06303) | Sep 10, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [f0fc4f47b8](https://bsd-hardware.info/?probe=f0fc4f47b8) | Sep 10, 2023 |
| Lenovo        | ThinkPad SL 2746N8G         | Notebook    | [07eda65608](https://bsd-hardware.info/?probe=07eda65608) | Sep 09, 2023 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | Notebook    | [1d5aff2e2a](https://bsd-hardware.info/?probe=1d5aff2e2a) | Sep 08, 2023 |
| ASUSTek       | P8H61-M LX PLUS             | Desktop     | [6811f92db7](https://bsd-hardware.info/?probe=6811f92db7) | Sep 08, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [e3d8f34f08](https://bsd-hardware.info/?probe=e3d8f34f08) | Sep 08, 2023 |
| ASUSTek       | P8H61-M LX PLUS             | Desktop     | [231ef39d3b](https://bsd-hardware.info/?probe=231ef39d3b) | Sep 08, 2023 |
| HP            | Pavilion g7                 | Notebook    | [4870da3b0e](https://bsd-hardware.info/?probe=4870da3b0e) | Sep 07, 2023 |
| Intel         | HM570                       | Desktop     | [3112f263f5](https://bsd-hardware.info/?probe=3112f263f5) | Sep 07, 2023 |
| Intel         | HM570                       | Desktop     | [0e4bfa9794](https://bsd-hardware.info/?probe=0e4bfa9794) | Sep 07, 2023 |
| LG Electro... | 16U70Q-K.AAS7U1             | Notebook    | [82e3b2e5f8](https://bsd-hardware.info/?probe=82e3b2e5f8) | Sep 06, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [bd2df105c0](https://bsd-hardware.info/?probe=bd2df105c0) | Sep 06, 2023 |
| Lenovo        | ThinkPad X240 20AMA1Y3UK    | Notebook    | [8277297743](https://bsd-hardware.info/?probe=8277297743) | Sep 05, 2023 |
| HP            | G62                         | Notebook    | [b4777b6ba5](https://bsd-hardware.info/?probe=b4777b6ba5) | Sep 04, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [ed1fade3db](https://bsd-hardware.info/?probe=ed1fade3db) | Sep 04, 2023 |
| Toshiba       | QOSMIO X775                 | Notebook    | [d92a05ab1d](https://bsd-hardware.info/?probe=d92a05ab1d) | Sep 04, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [5d1dbf86d9](https://bsd-hardware.info/?probe=5d1dbf86d9) | Sep 04, 2023 |
| ASUSTek       | K40IN                       | Notebook    | [00a4f6e5a0](https://bsd-hardware.info/?probe=00a4f6e5a0) | Sep 04, 2023 |
| Samsung       | 270E5J/2570EJ               | Notebook    | [3feb685296](https://bsd-hardware.info/?probe=3feb685296) | Sep 03, 2023 |
| ASUSTek       | 1005PXD                     | Notebook    | [8dac93d19d](https://bsd-hardware.info/?probe=8dac93d19d) | Sep 03, 2023 |
| ASUSTek       | K40IN                       | Notebook    | [df0a3f55c2](https://bsd-hardware.info/?probe=df0a3f55c2) | Sep 03, 2023 |
| Lenovo        | ThinkPad P50 20EN0012US     | Notebook    | [9d1b9e7af6](https://bsd-hardware.info/?probe=9d1b9e7af6) | Sep 03, 2023 |
| Fujitsu       | LIFEBOOK S935               | Notebook    | [a6cfe011fe](https://bsd-hardware.info/?probe=a6cfe011fe) | Sep 02, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [d49b8413db](https://bsd-hardware.info/?probe=d49b8413db) | Sep 02, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [9b322dc202](https://bsd-hardware.info/?probe=9b322dc202) | Sep 02, 2023 |
| MSI           | CX62 6QD                    | Notebook    | [4356e5b30f](https://bsd-hardware.info/?probe=4356e5b30f) | Sep 02, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [57925dc8bb](https://bsd-hardware.info/?probe=57925dc8bb) | Sep 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [044910f579](https://bsd-hardware.info/?probe=044910f579) | Sep 01, 2023 |
| Dell          | 0YXT71 A02                  | Desktop     | [b887caabe7](https://bsd-hardware.info/?probe=b887caabe7) | Aug 31, 2023 |
| Intel         | NUC11TNBi5 M11904-404       | Mini pc     | [d4a4a46409](https://bsd-hardware.info/?probe=d4a4a46409) | Aug 31, 2023 |
| HP            | 2000                        | Notebook    | [6d9c442ae6](https://bsd-hardware.info/?probe=6d9c442ae6) | Aug 31, 2023 |
| Acer          | Aspire A515-55              | Notebook    | [fcbd8a3f31](https://bsd-hardware.info/?probe=fcbd8a3f31) | Aug 31, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [a308c3a87b](https://bsd-hardware.info/?probe=a308c3a87b) | Aug 31, 2023 |
| Toshiba       | Satellite S55t-B            | Notebook    | [c2ed5fa6bd](https://bsd-hardware.info/?probe=c2ed5fa6bd) | Aug 30, 2023 |
| Dell          | Latitude E4310              | Notebook    | [7645de3654](https://bsd-hardware.info/?probe=7645de3654) | Aug 30, 2023 |
| HP            | Pavilion dv3500             | Notebook    | [0c3f84b285](https://bsd-hardware.info/?probe=0c3f84b285) | Aug 29, 2023 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | Notebook    | [e74ef1d37c](https://bsd-hardware.info/?probe=e74ef1d37c) | Aug 29, 2023 |
| Fujitsu       | FMVA0803D                   | Notebook    | [36528b957c](https://bsd-hardware.info/?probe=36528b957c) | Aug 28, 2023 |
| Lenovo        | ThinkPad T490 20RYS06R00    | Notebook    | [978cd1d6bc](https://bsd-hardware.info/?probe=978cd1d6bc) | Aug 28, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [3dab6f4044](https://bsd-hardware.info/?probe=3dab6f4044) | Aug 28, 2023 |
| MSI           | H110M PRO-VD                | Desktop     | [dcbd4ebf8f](https://bsd-hardware.info/?probe=dcbd4ebf8f) | Aug 27, 2023 |
| Toshiba       | Satellite S55t-B            | Notebook    | [eb85f0b975](https://bsd-hardware.info/?probe=eb85f0b975) | Aug 27, 2023 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [5f23f0620f](https://bsd-hardware.info/?probe=5f23f0620f) | Aug 27, 2023 |
| Fujitsu       | FMVA0803D                   | Notebook    | [8ce6118bf4](https://bsd-hardware.info/?probe=8ce6118bf4) | Aug 26, 2023 |
| HP            | ENVY Notebook 13-ab0XX      | Notebook    | [3d96f4d5b4](https://bsd-hardware.info/?probe=3d96f4d5b4) | Aug 26, 2023 |
| Dell          | Latitude E6420              | Notebook    | [a085ba3865](https://bsd-hardware.info/?probe=a085ba3865) | Aug 25, 2023 |
| NVN-ED01      | Unknown                     | Notebook    | [dba43e889a](https://bsd-hardware.info/?probe=dba43e889a) | Aug 25, 2023 |
| AZW           | U59                         | Desktop     | [e08540ab36](https://bsd-hardware.info/?probe=e08540ab36) | Aug 25, 2023 |
| Lenovo        | ThinkPad P50 20EN0009MS     | Notebook    | [4b3fcfa17e](https://bsd-hardware.info/?probe=4b3fcfa17e) | Aug 25, 2023 |
| ASUSTek       | S500CA                      | Notebook    | [019366a664](https://bsd-hardware.info/?probe=019366a664) | Aug 25, 2023 |
| MSI           | MAG B460M BAZOOKA           | Desktop     | [7cf9279c14](https://bsd-hardware.info/?probe=7cf9279c14) | Aug 22, 2023 |
| HP            | 82A5                        | Mini pc     | [4b56141a3b](https://bsd-hardware.info/?probe=4b56141a3b) | Aug 21, 2023 |
| Lenovo        | ThinkPad T450 20BUS0370P    | Notebook    | [c32aad1b1f](https://bsd-hardware.info/?probe=c32aad1b1f) | Aug 20, 2023 |
| Lenovo        | ThinkPad T450 20BUS0370P    | Notebook    | [5fefc051e1](https://bsd-hardware.info/?probe=5fefc051e1) | Aug 20, 2023 |
| Gigabyte      | GA-880GA-UD3H               | Desktop     | [35eb7df9a7](https://bsd-hardware.info/?probe=35eb7df9a7) | Aug 20, 2023 |
| ASRock        | H110M-STX                   | Desktop     | [5c819b9ff1](https://bsd-hardware.info/?probe=5c819b9ff1) | Aug 20, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [7e1d475356](https://bsd-hardware.info/?probe=7e1d475356) | Aug 18, 2023 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [df095be4ba](https://bsd-hardware.info/?probe=df095be4ba) | Aug 18, 2023 |
| Star Labs     | Lite                        | Notebook    | [eabab74d7b](https://bsd-hardware.info/?probe=eabab74d7b) | Aug 18, 2023 |
| Daten Tecn... | DH110MXV                    | Desktop     | [bdd9c72e7c](https://bsd-hardware.info/?probe=bdd9c72e7c) | Aug 18, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [c12a76c083](https://bsd-hardware.info/?probe=c12a76c083) | Aug 16, 2023 |
| ASUSTek       | X553MA                      | Notebook    | [7334765d8a](https://bsd-hardware.info/?probe=7334765d8a) | Aug 16, 2023 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [30c58f7403](https://bsd-hardware.info/?probe=30c58f7403) | Aug 15, 2023 |
| ASUSTek       | GL753VD                     | Notebook    | [8ccbffdd73](https://bsd-hardware.info/?probe=8ccbffdd73) | Aug 15, 2023 |
| MSI           | B360M BAZOOKA               | Desktop     | [472c17f992](https://bsd-hardware.info/?probe=472c17f992) | Aug 15, 2023 |
| ASUSTek       | P5G41T-M LX2/BR             | Desktop     | [f25db83457](https://bsd-hardware.info/?probe=f25db83457) | Aug 15, 2023 |
| Lenovo        | ThinkPad X200 7458WNZ       | Notebook    | [3ac1d60240](https://bsd-hardware.info/?probe=3ac1d60240) | Aug 12, 2023 |
| Lenovo        | ThinkPad T60 1951CZ1        | Notebook    | [46766bc381](https://bsd-hardware.info/?probe=46766bc381) | Aug 11, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | Notebook    | [2db86b4dff](https://bsd-hardware.info/?probe=2db86b4dff) | Aug 11, 2023 |
| Intel         | JSL MRD                     | Desktop     | [ca7024f423](https://bsd-hardware.info/?probe=ca7024f423) | Aug 10, 2023 |
| MSI           | B360M BAZOOKA               | Desktop     | [4b0b4b88a7](https://bsd-hardware.info/?probe=4b0b4b88a7) | Aug 10, 2023 |
| ATOPNUC       | MA90                        | Mini pc     | [4f4c550075](https://bsd-hardware.info/?probe=4f4c550075) | Aug 10, 2023 |
| Acer          | Aspire V3-371               | Notebook    | [21c262aadb](https://bsd-hardware.info/?probe=21c262aadb) | Aug 09, 2023 |
| Acer          | Aspire V3-371               | Notebook    | [68bceee682](https://bsd-hardware.info/?probe=68bceee682) | Aug 09, 2023 |
| ASUSTek       | M5A78L-M LE/USB3            | Desktop     | [4fc1fbaba1](https://bsd-hardware.info/?probe=4fc1fbaba1) | Aug 09, 2023 |
| Acer          | Veriton N2620G              | Desktop     | [2acf1e4557](https://bsd-hardware.info/?probe=2acf1e4557) | Aug 08, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [9693a5fc69](https://bsd-hardware.info/?probe=9693a5fc69) | Aug 08, 2023 |
| HP            | 82C0                        | Mini pc     | [6ad9c871cb](https://bsd-hardware.info/?probe=6ad9c871cb) | Aug 07, 2023 |
| HP            | 82C0                        | Mini pc     | [124e7b14df](https://bsd-hardware.info/?probe=124e7b14df) | Aug 07, 2023 |
| Intel         | H81                         | Desktop     | [80f40918ce](https://bsd-hardware.info/?probe=80f40918ce) | Aug 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [9c01814bdc](https://bsd-hardware.info/?probe=9c01814bdc) | Aug 07, 2023 |
| Lenovo        | 30FD SDK0J40705 WIN 3425... | Mini pc     | [6a45c89f9c](https://bsd-hardware.info/?probe=6a45c89f9c) | Aug 06, 2023 |
| HP            | 0AACh                       | Desktop     | [5997b1de3e](https://bsd-hardware.info/?probe=5997b1de3e) | Aug 06, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [d3fac2e3fe](https://bsd-hardware.info/?probe=d3fac2e3fe) | Aug 06, 2023 |
| ASUSTek       | M4A88TD-M/USB3              | Desktop     | [ce95634a53](https://bsd-hardware.info/?probe=ce95634a53) | Aug 06, 2023 |
| Compaq        | Presario CQ-17              | Notebook    | [f97feb2db0](https://bsd-hardware.info/?probe=f97feb2db0) | Aug 04, 2023 |
| ASUSTek       | P5QL PRO                    | Desktop     | [dccefef8eb](https://bsd-hardware.info/?probe=dccefef8eb) | Aug 04, 2023 |
| HP            | 82C0                        | Mini pc     | [be2c1dd2f5](https://bsd-hardware.info/?probe=be2c1dd2f5) | Aug 03, 2023 |
| HP            | 82C0                        | Mini pc     | [6fa14d3439](https://bsd-hardware.info/?probe=6fa14d3439) | Aug 03, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [6496fe0cfe](https://bsd-hardware.info/?probe=6496fe0cfe) | Aug 03, 2023 |
| Gigabyte      | Z170-HD3 DDR3-CF            | Desktop     | [f66f032ffe](https://bsd-hardware.info/?probe=f66f032ffe) | Aug 01, 2023 |
| Lenovo        | IdeaPad S210 Touch 20257    | Notebook    | [1e372622c1](https://bsd-hardware.info/?probe=1e372622c1) | Jul 31, 2023 |
| Lenovo        | ThinkPad X270 20HNA04GCD    | Notebook    | [6547f4a73b](https://bsd-hardware.info/?probe=6547f4a73b) | Jul 31, 2023 |
| Lenovo        | ThinkPad X230 23202DG       | Notebook    | [f8ade878ce](https://bsd-hardware.info/?probe=f8ade878ce) | Jul 30, 2023 |
| HP            | Notebook                    | Notebook    | [360790274a](https://bsd-hardware.info/?probe=360790274a) | Jul 29, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [53e133857b](https://bsd-hardware.info/?probe=53e133857b) | Jul 29, 2023 |
| HP            | Pavilion g6                 | Notebook    | [bdd2349f1c](https://bsd-hardware.info/?probe=bdd2349f1c) | Jul 28, 2023 |
| ASUSTek       | P5B SE                      | Desktop     | [6361457008](https://bsd-hardware.info/?probe=6361457008) | Jul 27, 2023 |
| HP            | 83E1                        | Desktop     | [b211795736](https://bsd-hardware.info/?probe=b211795736) | Jul 27, 2023 |
| Dell          | Latitude 5480               | Notebook    | [e1521ed9d2](https://bsd-hardware.info/?probe=e1521ed9d2) | Jul 26, 2023 |
| ASUSTek       | A8N-E                       | Desktop     | [274a1e508f](https://bsd-hardware.info/?probe=274a1e508f) | Jul 26, 2023 |
| ATOPNUC       | MA90                        | Mini pc     | [e266a42fa5](https://bsd-hardware.info/?probe=e266a42fa5) | Jul 26, 2023 |
| Lenovo        | IdeaPad S145-14AST 81ST     | Notebook    | [1b3ba2b86a](https://bsd-hardware.info/?probe=1b3ba2b86a) | Jul 25, 2023 |
| HP            | 339A                        | Desktop     | [b770568bae](https://bsd-hardware.info/?probe=b770568bae) | Jul 25, 2023 |
| ASUSTek       | 1015PX                      | Notebook    | [b0745153e4](https://bsd-hardware.info/?probe=b0745153e4) | Jul 24, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [60dac781b2](https://bsd-hardware.info/?probe=60dac781b2) | Jul 24, 2023 |
| ASRock        | H61M-VG3                    | Desktop     | [5cebf2275e](https://bsd-hardware.info/?probe=5cebf2275e) | Jul 24, 2023 |
| Acer          | Spin SP314-21               | Convertible | [375c9f30cd](https://bsd-hardware.info/?probe=375c9f30cd) | Jul 22, 2023 |
| Panasonic     | CF-F9JYFNDR                 | Notebook    | [be7b261f26](https://bsd-hardware.info/?probe=be7b261f26) | Jul 21, 2023 |
| ASUSTek       | P5QL PRO                    | Desktop     | [b51bcdf3a5](https://bsd-hardware.info/?probe=b51bcdf3a5) | Jul 20, 2023 |
| Acer          | Aspire 4736Z                | Notebook    | [bccf97f694](https://bsd-hardware.info/?probe=bccf97f694) | Jul 20, 2023 |
| ASUSTek       | 1015PX                      | Notebook    | [dc06c76cf9](https://bsd-hardware.info/?probe=dc06c76cf9) | Jul 19, 2023 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [5fcffa5bd6](https://bsd-hardware.info/?probe=5fcffa5bd6) | Jul 19, 2023 |
| HP            | 81C5 MVB                    | Desktop     | [1a4fbc384d](https://bsd-hardware.info/?probe=1a4fbc384d) | Jul 19, 2023 |
| ASUSTek       | K42Jr                       | Notebook    | [256168572a](https://bsd-hardware.info/?probe=256168572a) | Jul 18, 2023 |
| Samsung       | RC530/RC730                 | Notebook    | [b76e5e8a87](https://bsd-hardware.info/?probe=b76e5e8a87) | Jul 17, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [3a5b0b3193](https://bsd-hardware.info/?probe=3a5b0b3193) | Jul 17, 2023 |
| Dell          | 04YP6J A01                  | Desktop     | [f474b9f986](https://bsd-hardware.info/?probe=f474b9f986) | Jul 16, 2023 |
| ASUSTek       | H97M-E                      | Desktop     | [82bc9b32bd](https://bsd-hardware.info/?probe=82bc9b32bd) | Jul 16, 2023 |
| Lenovo        | ThinkPad R14 Gen 4 21E5A... | Notebook    | [e0fc7135e5](https://bsd-hardware.info/?probe=e0fc7135e5) | Jul 15, 2023 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [d4265533e2](https://bsd-hardware.info/?probe=d4265533e2) | Jul 15, 2023 |
| ECS           | H61H2-M17                   | Desktop     | [aa4679bee7](https://bsd-hardware.info/?probe=aa4679bee7) | Jul 14, 2023 |
| ASRock        | P67 Pro3 SE                 | Desktop     | [a7284068da](https://bsd-hardware.info/?probe=a7284068da) | Jul 12, 2023 |
| ASRock        | H61M-GS                     | Desktop     | [502952e73f](https://bsd-hardware.info/?probe=502952e73f) | Jul 11, 2023 |
| ASUSTek       | X541UVK                     | Notebook    | [17f58b70e4](https://bsd-hardware.info/?probe=17f58b70e4) | Jul 10, 2023 |
| ASRock        | A300M-STX                   | Desktop     | [5d896a607e](https://bsd-hardware.info/?probe=5d896a607e) | Jul 06, 2023 |
| Dell          | Latitude E6420              | Notebook    | [3151e6d3bb](https://bsd-hardware.info/?probe=3151e6d3bb) | Jul 05, 2023 |
| HP            | Compaq Presario CQ61        | Notebook    | [d070292855](https://bsd-hardware.info/?probe=d070292855) | Jul 03, 2023 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [2053dbb697](https://bsd-hardware.info/?probe=2053dbb697) | Jul 03, 2023 |
| ASUSTek       | 1005PXD                     | Notebook    | [246032ee65](https://bsd-hardware.info/?probe=246032ee65) | Jul 02, 2023 |
| Lenovo        | ThinkPad T60 20076PU        | Notebook    | [cb47bfef12](https://bsd-hardware.info/?probe=cb47bfef12) | Jun 30, 2023 |
| HP            | 8055                        | Desktop     | [94df572de4](https://bsd-hardware.info/?probe=94df572de4) | Jun 29, 2023 |
| ASUSTek       | M2A-VM                      | Desktop     | [2d5a9bba42](https://bsd-hardware.info/?probe=2d5a9bba42) | Jun 28, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [17834256ca](https://bsd-hardware.info/?probe=17834256ca) | Jun 28, 2023 |
| Lenovo        | Kabini CRB 31900058 STD     | Desktop     | [127f92759b](https://bsd-hardware.info/?probe=127f92759b) | Jun 26, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [a6e959358f](https://bsd-hardware.info/?probe=a6e959358f) | Jun 25, 2023 |
| Intel         | DG41TY AAE47335-300         | Desktop     | [111b9572ba](https://bsd-hardware.info/?probe=111b9572ba) | Jun 25, 2023 |
| Dell          | Latitude E4310              | Notebook    | [9cdd4909fe](https://bsd-hardware.info/?probe=9cdd4909fe) | Jun 24, 2023 |
| HP            | Laptop 15-bs1xx             | Notebook    | [dc0d876d7b](https://bsd-hardware.info/?probe=dc0d876d7b) | Jun 24, 2023 |
| HP            | Laptop 15-ra0xx             | Notebook    | [8c31502b68](https://bsd-hardware.info/?probe=8c31502b68) | Jun 24, 2023 |
| HP            | EliteBook 750 G1            | Notebook    | [aba91c70d1](https://bsd-hardware.info/?probe=aba91c70d1) | Jun 24, 2023 |
| HP            | 250 G6 Notebook PC          | Notebook    | [f7df283c94](https://bsd-hardware.info/?probe=f7df283c94) | Jun 24, 2023 |
| Dell          | Latitude 5490               | Notebook    | [b638c1b2b1](https://bsd-hardware.info/?probe=b638c1b2b1) | Jun 23, 2023 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [2dfabb3a28](https://bsd-hardware.info/?probe=2dfabb3a28) | Jun 23, 2023 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [b63efe1bc2](https://bsd-hardware.info/?probe=b63efe1bc2) | Jun 23, 2023 |
| LG Electro... | R590-K.AAA9BT               | Desktop     | [5c3ab65e8e](https://bsd-hardware.info/?probe=5c3ab65e8e) | Jun 23, 2023 |
| Acer          | Aspire 5749                 | Notebook    | [75ad2ddb6f](https://bsd-hardware.info/?probe=75ad2ddb6f) | Jun 22, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [485ba68539](https://bsd-hardware.info/?probe=485ba68539) | Jun 22, 2023 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [29545a1054](https://bsd-hardware.info/?probe=29545a1054) | Jun 21, 2023 |
| Acer          | Aspire 5749                 | Notebook    | [1e91633580](https://bsd-hardware.info/?probe=1e91633580) | Jun 20, 2023 |
| HP            | Pavilion 15                 | Notebook    | [9ba6acdb4b](https://bsd-hardware.info/?probe=9ba6acdb4b) | Jun 18, 2023 |
| Intel         | NUC11PABi5 K90634-305       | Mini pc     | [9f41fa4740](https://bsd-hardware.info/?probe=9f41fa4740) | Jun 18, 2023 |
| Intel         | NUC11PABi5 K90634-305       | Mini pc     | [8eb0be633d](https://bsd-hardware.info/?probe=8eb0be633d) | Jun 18, 2023 |
| HP            | Stream Laptop 14-ds0xxx     | Notebook    | [81bbc73e72](https://bsd-hardware.info/?probe=81bbc73e72) | Jun 18, 2023 |
| ASUSTek       | P7P55D LE                   | Desktop     | [ea97ade85d](https://bsd-hardware.info/?probe=ea97ade85d) | Jun 17, 2023 |
| Apple         | MacBook7,1                  | Notebook    | [6412e6fb23](https://bsd-hardware.info/?probe=6412e6fb23) | Jun 16, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [d8079e6155](https://bsd-hardware.info/?probe=d8079e6155) | Jun 16, 2023 |
| Fujitsu Si... | D2804-A1 S26361-D2804-A1    | Desktop     | [70b0e8172d](https://bsd-hardware.info/?probe=70b0e8172d) | Jun 14, 2023 |
| ASUSTek       | 1015P                       | Notebook    | [c700224684](https://bsd-hardware.info/?probe=c700224684) | Jun 14, 2023 |
| MSI           | GE63 Raider RGB 8RE         | Notebook    | [ecdb80adc0](https://bsd-hardware.info/?probe=ecdb80adc0) | Jun 14, 2023 |
| HP            | Compaq 6830s                | Notebook    | [1a06917a0f](https://bsd-hardware.info/?probe=1a06917a0f) | Jun 14, 2023 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [76809610f9](https://bsd-hardware.info/?probe=76809610f9) | Jun 13, 2023 |
| Lenovo        | ThinkPad T440p 20AWS1CH0... | Notebook    | [b532f1ce9c](https://bsd-hardware.info/?probe=b532f1ce9c) | Jun 13, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [dd937d0914](https://bsd-hardware.info/?probe=dd937d0914) | Jun 12, 2023 |
| Samsung       | R530/R730/R540              | Notebook    | [b007264caa](https://bsd-hardware.info/?probe=b007264caa) | Jun 11, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [2008116e96](https://bsd-hardware.info/?probe=2008116e96) | Jun 10, 2023 |
| Dell          | 0X9X1W A00                  | Desktop     | [64825f4f71](https://bsd-hardware.info/?probe=64825f4f71) | Jun 08, 2023 |
| Dell          | 0X9X1W A00                  | Desktop     | [c9d8d9a491](https://bsd-hardware.info/?probe=c9d8d9a491) | Jun 08, 2023 |
| ASUSTek       | 1015BX                      | Notebook    | [ad05aaf9fe](https://bsd-hardware.info/?probe=ad05aaf9fe) | Jun 07, 2023 |
| Lenovo        | S10-3                       | Notebook    | [f874a66e78](https://bsd-hardware.info/?probe=f874a66e78) | Jun 05, 2023 |
| Lenovo        | S10-3                       | Notebook    | [b76483ab8b](https://bsd-hardware.info/?probe=b76483ab8b) | Jun 05, 2023 |
| HP            | 3398                        | Desktop     | [980c0fc5a8](https://bsd-hardware.info/?probe=980c0fc5a8) | Jun 04, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [e1a7d29d74](https://bsd-hardware.info/?probe=e1a7d29d74) | Jun 04, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [d0d9de7cf3](https://bsd-hardware.info/?probe=d0d9de7cf3) | Jun 04, 2023 |
| Dell          | 0TKM9Y A00                  | Mini pc     | [fdd78a8f45](https://bsd-hardware.info/?probe=fdd78a8f45) | Jun 03, 2023 |
| Dell          | 0WR7PY A03                  | Desktop     | [c8496622be](https://bsd-hardware.info/?probe=c8496622be) | Jun 03, 2023 |
| Dell          | 0WR7PY A03                  | Desktop     | [b9f7e3e209](https://bsd-hardware.info/?probe=b9f7e3e209) | Jun 03, 2023 |
| ASUSTek       | PRIME X399-A                | Desktop     | [16dd6af1a9](https://bsd-hardware.info/?probe=16dd6af1a9) | Jun 03, 2023 |
| Panasonic     | CF-NX1GDHYS                 | Notebook    | [fb1f293997](https://bsd-hardware.info/?probe=fb1f293997) | Jun 02, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [1bb0436fe5](https://bsd-hardware.info/?probe=1bb0436fe5) | May 30, 2023 |
| Intel         | H81                         | Desktop     | [e0e15704fc](https://bsd-hardware.info/?probe=e0e15704fc) | May 29, 2023 |
| ASRock        | H410M/ac                    | Desktop     | [d3e3d20cc4](https://bsd-hardware.info/?probe=d3e3d20cc4) | May 29, 2023 |
| Apple         | MacBookPro10,2              | Notebook    | [c274e2c9db](https://bsd-hardware.info/?probe=c274e2c9db) | May 29, 2023 |
| HP            | 21D0                        | Desktop     | [4a10865d28](https://bsd-hardware.info/?probe=4a10865d28) | May 28, 2023 |
| HP            | 21D0                        | Desktop     | [e3d20826b3](https://bsd-hardware.info/?probe=e3d20826b3) | May 28, 2023 |
| Fujitsu       | Unknown                     | Notebook    | [3b5c9ab914](https://bsd-hardware.info/?probe=3b5c9ab914) | May 27, 2023 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [1d43f61471](https://bsd-hardware.info/?probe=1d43f61471) | May 27, 2023 |
| Unknown       | 1.0                         | Desktop     | [12d6c7934e](https://bsd-hardware.info/?probe=12d6c7934e) | May 27, 2023 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [53a2d5356d](https://bsd-hardware.info/?probe=53a2d5356d) | May 26, 2023 |
| HP            | x360 310 G2 PC              | Convertible | [05bd720b57](https://bsd-hardware.info/?probe=05bd720b57) | May 26, 2023 |
| Gigabyte      | B360M D2V                   | Desktop     | [5960982eb3](https://bsd-hardware.info/?probe=5960982eb3) | May 25, 2023 |
| Lenovo        | Yoga 2 Pro 20266            | Notebook    | [a2726e621b](https://bsd-hardware.info/?probe=a2726e621b) | May 25, 2023 |
| Timi          | TM1701                      | Notebook    | [1dd768a721](https://bsd-hardware.info/?probe=1dd768a721) | May 25, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [a0bff43f5c](https://bsd-hardware.info/?probe=a0bff43f5c) | May 23, 2023 |
| AZW           | GK55                        | Desktop     | [ef90c15915](https://bsd-hardware.info/?probe=ef90c15915) | May 23, 2023 |
| ASUSTek       | K42Jc                       | Notebook    | [3da2928a08](https://bsd-hardware.info/?probe=3da2928a08) | May 23, 2023 |
| Google        | Sentry                      | Notebook    | [107124dd66](https://bsd-hardware.info/?probe=107124dd66) | May 22, 2023 |
| ASRock        | Z68 Pro3 Gen3               | Desktop     | [0a03cd86a0](https://bsd-hardware.info/?probe=0a03cd86a0) | May 21, 2023 |
| Sony          | VPCEG15FB                   | Notebook    | [8777493861](https://bsd-hardware.info/?probe=8777493861) | May 21, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [41ce3c5d11](https://bsd-hardware.info/?probe=41ce3c5d11) | May 21, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [643f7277de](https://bsd-hardware.info/?probe=643f7277de) | May 21, 2023 |
| HP            | ZBook 15 G3                 | Notebook    | [4965fc4251](https://bsd-hardware.info/?probe=4965fc4251) | May 21, 2023 |
| ASUSTek       | Z87M-PLUS                   | Desktop     | [58da7daed7](https://bsd-hardware.info/?probe=58da7daed7) | May 20, 2023 |
| Packard Be... | EasyNote LJ65               | Notebook    | [36d3e7aaf7](https://bsd-hardware.info/?probe=36d3e7aaf7) | May 19, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [8f3c5de741](https://bsd-hardware.info/?probe=8f3c5de741) | May 19, 2023 |
| Intel         | 945GCT-M                    | Desktop     | [047b049834](https://bsd-hardware.info/?probe=047b049834) | May 18, 2023 |
| Gigabyte      | Z490 VISION G               | Desktop     | [976e31bfbc](https://bsd-hardware.info/?probe=976e31bfbc) | May 16, 2023 |
| Gigabyte      | Z490 VISION G               | Desktop     | [8eeec83a4e](https://bsd-hardware.info/?probe=8eeec83a4e) | May 16, 2023 |
| Gigabyte      | A520M S2H                   | Desktop     | [582dc6ab9f](https://bsd-hardware.info/?probe=582dc6ab9f) | May 15, 2023 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [bda308bc8c](https://bsd-hardware.info/?probe=bda308bc8c) | May 14, 2023 |
| Sony          | SVF14A15CBB                 | Notebook    | [4ada2dca25](https://bsd-hardware.info/?probe=4ada2dca25) | May 14, 2023 |
| Dell          | 0PC5F7 A02                  | Desktop     | [b22c9a0cdf](https://bsd-hardware.info/?probe=b22c9a0cdf) | May 13, 2023 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [a7fe22ce82](https://bsd-hardware.info/?probe=a7fe22ce82) | May 13, 2023 |
| Lenovo        | B570e HuronRiver Platfor... | Notebook    | [256915976d](https://bsd-hardware.info/?probe=256915976d) | May 12, 2023 |
| Dell          | 0WN7Y6 A01                  | Desktop     | [a232411c74](https://bsd-hardware.info/?probe=a232411c74) | May 12, 2023 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [3d889e8b9b](https://bsd-hardware.info/?probe=3d889e8b9b) | May 11, 2023 |
| Intel         | NUC6i5SYB H81131-503        | Mini pc     | [4eea72e4a6](https://bsd-hardware.info/?probe=4eea72e4a6) | May 11, 2023 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [fe053db6c7](https://bsd-hardware.info/?probe=fe053db6c7) | May 10, 2023 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [16ca4a2aa0](https://bsd-hardware.info/?probe=16ca4a2aa0) | May 10, 2023 |
| ASRock        | Q1900M                      | Desktop     | [c779034e79](https://bsd-hardware.info/?probe=c779034e79) | May 09, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [da07885adb](https://bsd-hardware.info/?probe=da07885adb) | May 09, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [bb96adbb13](https://bsd-hardware.info/?probe=bb96adbb13) | May 08, 2023 |
| HP            | Laptop 14-bs0xx             | Notebook    | [98ea66d6e8](https://bsd-hardware.info/?probe=98ea66d6e8) | May 07, 2023 |
| Dell          | 07F37C A00                  | Desktop     | [a23a95f97a](https://bsd-hardware.info/?probe=a23a95f97a) | May 07, 2023 |
| Acer          | V5-131                      | Notebook    | [9d3ba324bc](https://bsd-hardware.info/?probe=9d3ba324bc) | May 06, 2023 |
| ASRock        | J4125-ITX                   | Desktop     | [6e34c8b22a](https://bsd-hardware.info/?probe=6e34c8b22a) | May 05, 2023 |
| Intel         | DH87RL AAG74240-400         | Desktop     | [7833b60865](https://bsd-hardware.info/?probe=7833b60865) | May 05, 2023 |
| Dell          | 0252PH A04                  | Desktop     | [0cc9ef6521](https://bsd-hardware.info/?probe=0cc9ef6521) | May 03, 2023 |
| Dell          | 0252PH A04                  | Desktop     | [acaf59c3d5](https://bsd-hardware.info/?probe=acaf59c3d5) | May 03, 2023 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [3773da7851](https://bsd-hardware.info/?probe=3773da7851) | May 03, 2023 |
| HP            | Compaq Presario CQ50        | Notebook    | [f296048a29](https://bsd-hardware.info/?probe=f296048a29) | May 03, 2023 |
| HP            | 82B4                        | Desktop     | [244817e203](https://bsd-hardware.info/?probe=244817e203) | May 02, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [a5a1ca2ee6](https://bsd-hardware.info/?probe=a5a1ca2ee6) | May 02, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [e4e2bba5fb](https://bsd-hardware.info/?probe=e4e2bba5fb) | May 02, 2023 |
| Dell          | 0T7D40 A00                  | Desktop     | [83ccb5ff07](https://bsd-hardware.info/?probe=83ccb5ff07) | May 02, 2023 |
| Lenovo        | ThinkPad L450 20DSS1S402    | Notebook    | [f899593f61](https://bsd-hardware.info/?probe=f899593f61) | May 01, 2023 |
| Gigabyte      | GA-MA790X-UD4               | Desktop     | [71e5f4aa1f](https://bsd-hardware.info/?probe=71e5f4aa1f) | May 01, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [3f089673e0](https://bsd-hardware.info/?probe=3f089673e0) | May 01, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [396d7f268c](https://bsd-hardware.info/?probe=396d7f268c) | May 01, 2023 |
| Intel         | NUC7i3DNB J57625-512        | Mini pc     | [50836a160a](https://bsd-hardware.info/?probe=50836a160a) | Apr 30, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [779f5f8827](https://bsd-hardware.info/?probe=779f5f8827) | Apr 30, 2023 |
| Dell          | Latitude E5570              | Notebook    | [98e3f9821b](https://bsd-hardware.info/?probe=98e3f9821b) | Apr 29, 2023 |
| HP            | ProBook 640 G4              | Notebook    | [7b44e1591f](https://bsd-hardware.info/?probe=7b44e1591f) | Apr 29, 2023 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [270284972d](https://bsd-hardware.info/?probe=270284972d) | Apr 29, 2023 |
| NCR           | Richmond BIOS.6.0           | Desktop     | [e41e1e5c70](https://bsd-hardware.info/?probe=e41e1e5c70) | Apr 28, 2023 |
| ASUSTek       | H61M-K                      | Desktop     | [e735610d5c](https://bsd-hardware.info/?probe=e735610d5c) | Apr 27, 2023 |
| ASUSTek       | H61M-K                      | Desktop     | [db767ed552](https://bsd-hardware.info/?probe=db767ed552) | Apr 27, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [52174cc0ba](https://bsd-hardware.info/?probe=52174cc0ba) | Apr 27, 2023 |
| Dell          | 0252PH A04                  | Desktop     | [f497e66dec](https://bsd-hardware.info/?probe=f497e66dec) | Apr 27, 2023 |
| Acer          | Spin SP314-21               | Convertible | [f5debc3ef8](https://bsd-hardware.info/?probe=f5debc3ef8) | Apr 27, 2023 |
| HP            | 8056                        | Desktop     | [44fb168511](https://bsd-hardware.info/?probe=44fb168511) | Apr 26, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [4c7f33d6a9](https://bsd-hardware.info/?probe=4c7f33d6a9) | Apr 25, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [cf0771c3a2](https://bsd-hardware.info/?probe=cf0771c3a2) | Apr 25, 2023 |
| ASRock        | X370 Pro4                   | Desktop     | [9678198b3b](https://bsd-hardware.info/?probe=9678198b3b) | Apr 24, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [7caed06fdb](https://bsd-hardware.info/?probe=7caed06fdb) | Apr 24, 2023 |
| Google        | Peppy                       | Notebook    | [d162160498](https://bsd-hardware.info/?probe=d162160498) | Apr 24, 2023 |
| Lenovo        | ThinkPad X270 20HMS06Q1D    | Notebook    | [2df7c991f0](https://bsd-hardware.info/?probe=2df7c991f0) | Apr 23, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [e7387bfd6e](https://bsd-hardware.info/?probe=e7387bfd6e) | Apr 23, 2023 |
| Dell          | Inspiron 3421               | Notebook    | [ef4870410f](https://bsd-hardware.info/?probe=ef4870410f) | Apr 23, 2023 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | Notebook    | [93b498fb0c](https://bsd-hardware.info/?probe=93b498fb0c) | Apr 21, 2023 |
| Packard Be... | DOT SE                      | Notebook    | [f456e964db](https://bsd-hardware.info/?probe=f456e964db) | Apr 19, 2023 |
| Dell          | Latitude 7410               | Notebook    | [d5c047907d](https://bsd-hardware.info/?probe=d5c047907d) | Apr 19, 2023 |
| Dell          | 0VTC0D A02                  | Desktop     | [a807892254](https://bsd-hardware.info/?probe=a807892254) | Apr 19, 2023 |
| Acer          | Acadia V1.44                | Desktop     | [97bda17afa](https://bsd-hardware.info/?probe=97bda17afa) | Apr 19, 2023 |
| Acer          | V5-131                      | Notebook    | [4c2332c3b8](https://bsd-hardware.info/?probe=4c2332c3b8) | Apr 19, 2023 |
| Gigabyte      | H61M-S2PH                   | Desktop     | [024173445b](https://bsd-hardware.info/?probe=024173445b) | Apr 18, 2023 |
| Acer          | Spin SP314-21               | Convertible | [820e7da3c8](https://bsd-hardware.info/?probe=820e7da3c8) | Apr 18, 2023 |
| Medion        | E15302                      | Notebook    | [f47f32e1cc](https://bsd-hardware.info/?probe=f47f32e1cc) | Apr 17, 2023 |
| Gigabyte      | A520M DS3H AC               | Desktop     | [16021ac5b5](https://bsd-hardware.info/?probe=16021ac5b5) | Apr 17, 2023 |
| Intel         | NUC7i3DNB J57625-512        | Mini pc     | [a9c8c58abc](https://bsd-hardware.info/?probe=a9c8c58abc) | Apr 16, 2023 |
| Toshiba       | PORTEGE R700                | Notebook    | [8b196955ac](https://bsd-hardware.info/?probe=8b196955ac) | Apr 15, 2023 |
| Pegatron      | 2A72h                       | Desktop     | [142340aed4](https://bsd-hardware.info/?probe=142340aed4) | Apr 15, 2023 |
| Apple         | MacBook3,1                  | Notebook    | [74986a169a](https://bsd-hardware.info/?probe=74986a169a) | Apr 15, 2023 |
| ASUSTek       | PRIME B550M-A WIFI II       | Desktop     | [8e77aee0e0](https://bsd-hardware.info/?probe=8e77aee0e0) | Apr 14, 2023 |
| HP            | 3397                        | Desktop     | [cf2d152bee](https://bsd-hardware.info/?probe=cf2d152bee) | Apr 13, 2023 |
| Google        | Terra                       | Notebook    | [ef1619f65f](https://bsd-hardware.info/?probe=ef1619f65f) | Apr 13, 2023 |
| Google        | Terra                       | Notebook    | [bf598bc5bf](https://bsd-hardware.info/?probe=bf598bc5bf) | Apr 13, 2023 |
| ASUSTek       | PRIME B550M-A WIFI II       | Desktop     | [e6c9c37b02](https://bsd-hardware.info/?probe=e6c9c37b02) | Apr 13, 2023 |
| Gigabyte      | H81M-S2PH                   | Desktop     | [b7ec959c9f](https://bsd-hardware.info/?probe=b7ec959c9f) | Apr 13, 2023 |
| Samsung       | 370E4K                      | Notebook    | [c363d008bf](https://bsd-hardware.info/?probe=c363d008bf) | Apr 13, 2023 |
| Lenovo        | ThinkPad L540 20AUA34DJP    | Notebook    | [c7e40ee8ea](https://bsd-hardware.info/?probe=c7e40ee8ea) | Apr 12, 2023 |
| Acer          | Spin SP314-21               | Convertible | [a5ee042606](https://bsd-hardware.info/?probe=a5ee042606) | Apr 12, 2023 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [0747d0a699](https://bsd-hardware.info/?probe=0747d0a699) | Apr 11, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X3C... | Notebook    | [0249b4e73f](https://bsd-hardware.info/?probe=0249b4e73f) | Apr 11, 2023 |
| Lenovo        | ThinkPad L540 20AUA34DJP    | Notebook    | [52aac5fc6f](https://bsd-hardware.info/?probe=52aac5fc6f) | Apr 11, 2023 |
| Gigabyte      | M52L-S3P                    | Desktop     | [3a6baf7f2d](https://bsd-hardware.info/?probe=3a6baf7f2d) | Apr 09, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [689c25b4f6](https://bsd-hardware.info/?probe=689c25b4f6) | Apr 09, 2023 |
| Gigabyte      | B250M-Gaming 3-CF           | Desktop     | [592e08cdd2](https://bsd-hardware.info/?probe=592e08cdd2) | Apr 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon 34487... | Notebook    | [cec90ddd1b](https://bsd-hardware.info/?probe=cec90ddd1b) | Apr 08, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [f3ac765863](https://bsd-hardware.info/?probe=f3ac765863) | Apr 08, 2023 |
| Dell          | XPS 13 9343                 | Notebook    | [8354aed46e](https://bsd-hardware.info/?probe=8354aed46e) | Apr 07, 2023 |
| Acer          | Veriton M6620G              | Desktop     | [13f7e5c23b](https://bsd-hardware.info/?probe=13f7e5c23b) | Apr 07, 2023 |
| Fujitsu       | CELSIUS H920                | Notebook    | [0551eecbcc](https://bsd-hardware.info/?probe=0551eecbcc) | Apr 06, 2023 |
| Acer          | Aspire 5250                 | Notebook    | [385751dbc3](https://bsd-hardware.info/?probe=385751dbc3) | Apr 06, 2023 |
| ASUSTek       | X200MA                      | Notebook    | [c30e92db89](https://bsd-hardware.info/?probe=c30e92db89) | Apr 06, 2023 |
| Lenovo        | Tilapia CRB                 | Desktop     | [977f089665](https://bsd-hardware.info/?probe=977f089665) | Apr 05, 2023 |
| Gigabyte      | B360M D2V                   | Desktop     | [6429eebbaa](https://bsd-hardware.info/?probe=6429eebbaa) | Apr 05, 2023 |
| Google        | Wolf                        | Notebook    | [2546416afd](https://bsd-hardware.info/?probe=2546416afd) | Apr 05, 2023 |
| HP            | Laptop 15-bw0xx             | Notebook    | [93ea83eef5](https://bsd-hardware.info/?probe=93ea83eef5) | Apr 03, 2023 |
| Lenovo        | G570 20079                  | Notebook    | [76cc1653c3](https://bsd-hardware.info/?probe=76cc1653c3) | Apr 03, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [92d0571176](https://bsd-hardware.info/?probe=92d0571176) | Apr 03, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [096620cfac](https://bsd-hardware.info/?probe=096620cfac) | Apr 03, 2023 |
| Lenovo        | ThinkBook 14-IML 20RV       | Notebook    | [48b0a1024e](https://bsd-hardware.info/?probe=48b0a1024e) | Apr 02, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [760a744b91](https://bsd-hardware.info/?probe=760a744b91) | Apr 02, 2023 |
| HP            | 8055                        | Desktop     | [acef283e7c](https://bsd-hardware.info/?probe=acef283e7c) | Apr 02, 2023 |
| ASRock        | AB350M Pro4-F               | Desktop     | [424f3a2021](https://bsd-hardware.info/?probe=424f3a2021) | Apr 02, 2023 |
| ASUSTek       | X58C                        | Notebook    | [dad28a9d36](https://bsd-hardware.info/?probe=dad28a9d36) | Apr 01, 2023 |
| Gigabyte      | F2A85X-UP4                  | Desktop     | [068773e0e8](https://bsd-hardware.info/?probe=068773e0e8) | Apr 01, 2023 |
| Fujitsu       | CELSIUS H920                | Notebook    | [e6300dc691](https://bsd-hardware.info/?probe=e6300dc691) | Mar 31, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [bcaaed4d6d](https://bsd-hardware.info/?probe=bcaaed4d6d) | Mar 31, 2023 |
| DNS           | W9x0LU                      | Notebook    | [6539659387](https://bsd-hardware.info/?probe=6539659387) | Mar 31, 2023 |
| Acer          | Aspire 5745DG               | Notebook    | [2b8bf9802e](https://bsd-hardware.info/?probe=2b8bf9802e) | Mar 31, 2023 |
| Lenovo        | ThinkPad X220 4290DK6       | Notebook    | [96c83a2846](https://bsd-hardware.info/?probe=96c83a2846) | Mar 31, 2023 |
| Gigabyte      | GA-880GM-USB3               | Desktop     | [a9bc1579c1](https://bsd-hardware.info/?probe=a9bc1579c1) | Mar 31, 2023 |
| Lenovo        | 30D0 SDK0J40697 WIN 3305... | Desktop     | [bde9fd671b](https://bsd-hardware.info/?probe=bde9fd671b) | Mar 30, 2023 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | Desktop     | [ca6badc637](https://bsd-hardware.info/?probe=ca6badc637) | Mar 30, 2023 |
| Intel         | Intel                       | Notebook    | [75e9733afd](https://bsd-hardware.info/?probe=75e9733afd) | Mar 30, 2023 |
| Dell          | Inspiron 3195               | Convertible | [2afbb563b7](https://bsd-hardware.info/?probe=2afbb563b7) | Mar 30, 2023 |
| Gigabyte      | H81M-DS2V                   | Desktop     | [a69c208286](https://bsd-hardware.info/?probe=a69c208286) | Mar 30, 2023 |
| Toshiba       | Satellite L675D             | Notebook    | [0bf578daec](https://bsd-hardware.info/?probe=0bf578daec) | Mar 30, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [ff14982ad9](https://bsd-hardware.info/?probe=ff14982ad9) | Mar 29, 2023 |
| Dell          | Latitude 5590               | Notebook    | [7e87d436df](https://bsd-hardware.info/?probe=7e87d436df) | Mar 29, 2023 |
| Fujitsu       | D3049-A1 S26361-D3049-A1... | Server      | [0eb67759f0](https://bsd-hardware.info/?probe=0eb67759f0) | Mar 29, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [0af5cebe20](https://bsd-hardware.info/?probe=0af5cebe20) | Mar 29, 2023 |
| Lenovo        | ThinkPad T540p 20BFS10W0... | Notebook    | [30c5fc2625](https://bsd-hardware.info/?probe=30c5fc2625) | Mar 29, 2023 |
| Dell          | 0T1D10 A01                  | Desktop     | [2f5592023f](https://bsd-hardware.info/?probe=2f5592023f) | Mar 29, 2023 |
| Dell          | 0T1D10 A01                  | Desktop     | [6316b108be](https://bsd-hardware.info/?probe=6316b108be) | Mar 29, 2023 |
| Irbis         | NB78                        | Notebook    | [471efbc788](https://bsd-hardware.info/?probe=471efbc788) | Mar 29, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [f4e450fed1](https://bsd-hardware.info/?probe=f4e450fed1) | Mar 29, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [dddf27cde4](https://bsd-hardware.info/?probe=dddf27cde4) | Mar 28, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [c2ba6aca7d](https://bsd-hardware.info/?probe=c2ba6aca7d) | Mar 28, 2023 |
| BESSTAR Te... | UM700                       | Desktop     | [78ee14c1a5](https://bsd-hardware.info/?probe=78ee14c1a5) | Mar 28, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [fb4eec9c34](https://bsd-hardware.info/?probe=fb4eec9c34) | Mar 27, 2023 |
| ASRock        | H61M-HVS                    | Desktop     | [98777ba333](https://bsd-hardware.info/?probe=98777ba333) | Mar 27, 2023 |
| HP            | Pavilion dv6                | Notebook    | [ce2cc6852d](https://bsd-hardware.info/?probe=ce2cc6852d) | Mar 27, 2023 |
| LG Electro... | COLUMBIA                    | Notebook    | [4872f6c377](https://bsd-hardware.info/?probe=4872f6c377) | Mar 27, 2023 |
| Dell          | Inspiron 7437               | Notebook    | [2c4de59558](https://bsd-hardware.info/?probe=2c4de59558) | Mar 27, 2023 |
| Lenovo        | IdeaPad S210 20256          | Notebook    | [2e22ee87c3](https://bsd-hardware.info/?probe=2e22ee87c3) | Mar 27, 2023 |
| Lenovo        | ThinkPad T430 2349G5P       | Notebook    | [9ea67d3893](https://bsd-hardware.info/?probe=9ea67d3893) | Mar 27, 2023 |
| Dell          | Latitude 5420               | Notebook    | [4e22bbc131](https://bsd-hardware.info/?probe=4e22bbc131) | Mar 26, 2023 |
| MSI           | 870-G45                     | Desktop     | [19cbb6e0f3](https://bsd-hardware.info/?probe=19cbb6e0f3) | Mar 26, 2023 |
| LG Electro... | E500-L.A2M4A2               | Notebook    | [8dab794233](https://bsd-hardware.info/?probe=8dab794233) | Mar 26, 2023 |
| HP            | EliteBook Folio 9470m       | Notebook    | [ea2865cbf5](https://bsd-hardware.info/?probe=ea2865cbf5) | Mar 26, 2023 |
| Gigabyte      | F2A85X-UP4                  | Desktop     | [97d37b6e2f](https://bsd-hardware.info/?probe=97d37b6e2f) | Mar 25, 2023 |
| Samsung       | R468/R418                   | Notebook    | [f620a5c6ec](https://bsd-hardware.info/?probe=f620a5c6ec) | Mar 25, 2023 |
| Lenovo        | ThinkPad X220 4291AN9       | Notebook    | [1646bb53ab](https://bsd-hardware.info/?probe=1646bb53ab) | Mar 25, 2023 |
| Apple         | Mac-F22C86C8                | Mini pc     | [7945f26073](https://bsd-hardware.info/?probe=7945f26073) | Mar 25, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [7df625b1df](https://bsd-hardware.info/?probe=7df625b1df) | Mar 25, 2023 |
| MSI           | 870-G45                     | Desktop     | [14e990c885](https://bsd-hardware.info/?probe=14e990c885) | Mar 25, 2023 |
| Gigabyte      | F2A85X-UP4                  | Desktop     | [c0b8eb494e](https://bsd-hardware.info/?probe=c0b8eb494e) | Mar 25, 2023 |
| ASUSTek       | P5K SE                      | Desktop     | [646eff3292](https://bsd-hardware.info/?probe=646eff3292) | Mar 25, 2023 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [8e798ca6ef](https://bsd-hardware.info/?probe=8e798ca6ef) | Mar 25, 2023 |
| Lenovo        | ThinkPad W541 20EF000NUS    | Notebook    | [34b156c20c](https://bsd-hardware.info/?probe=34b156c20c) | Mar 24, 2023 |
| HP            | 8055                        | Desktop     | [03930fa6c3](https://bsd-hardware.info/?probe=03930fa6c3) | Mar 24, 2023 |
| HP            | 8350                        | Desktop     | [46dedb22a0](https://bsd-hardware.info/?probe=46dedb22a0) | Mar 24, 2023 |
| Dell          | Latitude 5500               | Notebook    | [8db518ef3d](https://bsd-hardware.info/?probe=8db518ef3d) | Mar 24, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [a8f794f3fb](https://bsd-hardware.info/?probe=a8f794f3fb) | Mar 24, 2023 |
| Unknown       | Unknown                     | Desktop     | [a66dffcb5c](https://bsd-hardware.info/?probe=a66dffcb5c) | Mar 23, 2023 |
| Intel         | DB85FL AAG89861-203         | Desktop     | [ff97717798](https://bsd-hardware.info/?probe=ff97717798) | Mar 23, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [e7cadcdae1](https://bsd-hardware.info/?probe=e7cadcdae1) | Mar 23, 2023 |
| Acer          | Revo 70                     | Desktop     | [50d93bea69](https://bsd-hardware.info/?probe=50d93bea69) | Mar 23, 2023 |
| Sony          | VAIO                        | All in one  | [ef7c622d8d](https://bsd-hardware.info/?probe=ef7c622d8d) | Mar 23, 2023 |
| Sony          | VAIO                        | All in one  | [ededfcfd39](https://bsd-hardware.info/?probe=ededfcfd39) | Mar 23, 2023 |
| Lenovo        | ThinkPad T61 7658CTO        | Notebook    | [f00e571f76](https://bsd-hardware.info/?probe=f00e571f76) | Mar 23, 2023 |
| Unknown       | T360D11                     | Desktop     | [d4d69405c5](https://bsd-hardware.info/?probe=d4d69405c5) | Mar 23, 2023 |
| T-bao         | MINI PC V1.0                | Desktop     | [eb2bc1cd51](https://bsd-hardware.info/?probe=eb2bc1cd51) | Mar 23, 2023 |
| Dell          | 0WWJRX A00                  | Desktop     | [b016b1fb3c](https://bsd-hardware.info/?probe=b016b1fb3c) | Mar 22, 2023 |
| Lenovo        | ThinkPad T430s 2356CV6      | Notebook    | [d9efc1e30b](https://bsd-hardware.info/?probe=d9efc1e30b) | Mar 22, 2023 |
| ASUSTek       | X71Vn                       | Notebook    | [6e96ea55ee](https://bsd-hardware.info/?probe=6e96ea55ee) | Mar 22, 2023 |
| Gigabyte      | F2A55-DS3                   | Desktop     | [ce8775fbe5](https://bsd-hardware.info/?probe=ce8775fbe5) | Mar 22, 2023 |
| Biostar       | H61MGC                      | Desktop     | [94e565457c](https://bsd-hardware.info/?probe=94e565457c) | Mar 22, 2023 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [c486bbb209](https://bsd-hardware.info/?probe=c486bbb209) | Mar 22, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [840a902d2b](https://bsd-hardware.info/?probe=840a902d2b) | Mar 22, 2023 |
| Foxconn       | M61PMV FAB                  | Desktop     | [197d75cbaa](https://bsd-hardware.info/?probe=197d75cbaa) | Mar 21, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [136a6641be](https://bsd-hardware.info/?probe=136a6641be) | Mar 21, 2023 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | Desktop     | [bcada44b09](https://bsd-hardware.info/?probe=bcada44b09) | Mar 21, 2023 |
| Intel         | X99                         | Desktop     | [a74c2b96ff](https://bsd-hardware.info/?probe=a74c2b96ff) | Mar 21, 2023 |
| Dell          | 0GM819                      | Desktop     | [9d5996dd7a](https://bsd-hardware.info/?probe=9d5996dd7a) | Mar 21, 2023 |
| Lenovo        | ThinkPad X230 232578G       | Notebook    | [edf47cb2d4](https://bsd-hardware.info/?probe=edf47cb2d4) | Mar 21, 2023 |
| Lenovo        | ThinkPad T61 7659CA1        | Notebook    | [bba228ddc9](https://bsd-hardware.info/?probe=bba228ddc9) | Mar 20, 2023 |
| HP            | 8054                        | Desktop     | [6e5a18f346](https://bsd-hardware.info/?probe=6e5a18f346) | Mar 20, 2023 |
| Lenovo        | 30BC SDK0J40705 WIN 3425... | Desktop     | [33b600b436](https://bsd-hardware.info/?probe=33b600b436) | Mar 20, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [55dc82af1c](https://bsd-hardware.info/?probe=55dc82af1c) | Mar 20, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [8d0e6be5da](https://bsd-hardware.info/?probe=8d0e6be5da) | Mar 20, 2023 |
| ASUSTek       | 1015PX                      | Notebook    | [d6c1199165](https://bsd-hardware.info/?probe=d6c1199165) | Mar 20, 2023 |
| Dell          | 0GM819                      | Desktop     | [da7c02c542](https://bsd-hardware.info/?probe=da7c02c542) | Mar 20, 2023 |
| Lenovo        | ThinkPad E595 20NF0002BM    | Notebook    | [83ee1d297d](https://bsd-hardware.info/?probe=83ee1d297d) | Mar 20, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [c07b0a75e5](https://bsd-hardware.info/?probe=c07b0a75e5) | Mar 20, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [71d2b7317c](https://bsd-hardware.info/?probe=71d2b7317c) | Mar 19, 2023 |
| ASUSTek       | K501UQ                      | Notebook    | [b7256fddbb](https://bsd-hardware.info/?probe=b7256fddbb) | Mar 19, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [36348fa16f](https://bsd-hardware.info/?probe=36348fa16f) | Mar 19, 2023 |
| Apple         | MacBookPro5,1               | Notebook    | [9e300b5797](https://bsd-hardware.info/?probe=9e300b5797) | Mar 19, 2023 |
| MECHREVO S... | S1 Series                   | Notebook    | [58ae2c4605](https://bsd-hardware.info/?probe=58ae2c4605) | Mar 19, 2023 |
| Toshiba       | Satellite P300              | Notebook    | [81b7ca608e](https://bsd-hardware.info/?probe=81b7ca608e) | Mar 19, 2023 |
| Lenovo        | ThinkPad T520 4242PN3       | Notebook    | [3ea33f0cad](https://bsd-hardware.info/?probe=3ea33f0cad) | Mar 19, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [e35600705f](https://bsd-hardware.info/?probe=e35600705f) | Mar 19, 2023 |
| Lenovo        | ThinkPad L380 Yoga 20M8S... | Convertible | [40a4d98b9c](https://bsd-hardware.info/?probe=40a4d98b9c) | Mar 19, 2023 |
| Samsung       | R520/R522/R620              | Notebook    | [096d52b83d](https://bsd-hardware.info/?probe=096d52b83d) | Mar 18, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [be9a45f529](https://bsd-hardware.info/?probe=be9a45f529) | Mar 18, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [acc1970543](https://bsd-hardware.info/?probe=acc1970543) | Mar 18, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [a365a5b411](https://bsd-hardware.info/?probe=a365a5b411) | Mar 18, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [6f2790802d](https://bsd-hardware.info/?probe=6f2790802d) | Mar 18, 2023 |
| Lenovo        | ThinkPad A275 20KCS07010    | Notebook    | [4d6daf66c1](https://bsd-hardware.info/?probe=4d6daf66c1) | Mar 18, 2023 |
| ASUSTek       | P6X58D-E                    | Desktop     | [ec05209185](https://bsd-hardware.info/?probe=ec05209185) | Mar 18, 2023 |
| Fujitsu       | LIFEBOOK AH530              | Notebook    | [50a5ed6b41](https://bsd-hardware.info/?probe=50a5ed6b41) | Mar 18, 2023 |
| Dell          | 0Y5DDC A00                  | Desktop     | [f26bbd9dde](https://bsd-hardware.info/?probe=f26bbd9dde) | Mar 18, 2023 |
| IGEL Techn... | M350C                       | Notebook    | [a04efafd2e](https://bsd-hardware.info/?probe=a04efafd2e) | Mar 18, 2023 |
| HP            | Pavilion dv5                | Notebook    | [113fe74799](https://bsd-hardware.info/?probe=113fe74799) | Mar 18, 2023 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [29b3a70374](https://bsd-hardware.info/?probe=29b3a70374) | Mar 18, 2023 |
| Unknown       | Unknown                     | Desktop     | [dd8a64237a](https://bsd-hardware.info/?probe=dd8a64237a) | Mar 18, 2023 |
| HP            | EliteBook 850 G2            | Notebook    | [653dbe54a4](https://bsd-hardware.info/?probe=653dbe54a4) | Mar 18, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [2ceda5b586](https://bsd-hardware.info/?probe=2ceda5b586) | Mar 17, 2023 |
| Lenovo        | ThinkPad T440p              | Notebook    | [575123c3ac](https://bsd-hardware.info/?probe=575123c3ac) | Mar 17, 2023 |
| Dell          | Inspiron 3442               | Notebook    | [cbb9f6bfbb](https://bsd-hardware.info/?probe=cbb9f6bfbb) | Mar 17, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [74cf75116d](https://bsd-hardware.info/?probe=74cf75116d) | Mar 17, 2023 |
| ASUSTek       | TUF B360M-PLUS GAMING       | Desktop     | [ebbd75883c](https://bsd-hardware.info/?probe=ebbd75883c) | Mar 17, 2023 |
| Dell          | Latitude E5570              | Notebook    | [8b9aa95420](https://bsd-hardware.info/?probe=8b9aa95420) | Mar 17, 2023 |
| Toshiba       | Satellite L40               | Notebook    | [2297dcb7e7](https://bsd-hardware.info/?probe=2297dcb7e7) | Mar 17, 2023 |
| Dell          | Latitude E5570              | Notebook    | [937a7c9385](https://bsd-hardware.info/?probe=937a7c9385) | Mar 17, 2023 |
| Unknown       | SKYBAY                      | Desktop     | [7399558d80](https://bsd-hardware.info/?probe=7399558d80) | Mar 17, 2023 |
| Unknown       | SKYBAY                      | Desktop     | [3fb2d0d992](https://bsd-hardware.info/?probe=3fb2d0d992) | Mar 17, 2023 |
| Lenovo        | ThinkPad X201 36801T6       | Notebook    | [decaf0c347](https://bsd-hardware.info/?probe=decaf0c347) | Mar 17, 2023 |
| HP            | 1632                        | Desktop     | [8f3bb99bb4](https://bsd-hardware.info/?probe=8f3bb99bb4) | Mar 17, 2023 |
| Lenovo        | ThinkPad X61s 7667WQS       | Notebook    | [f1351003d1](https://bsd-hardware.info/?probe=f1351003d1) | Mar 17, 2023 |
| Dell          | Inspiron 5557               | Notebook    | [ff199c6d21](https://bsd-hardware.info/?probe=ff199c6d21) | Mar 16, 2023 |
| HP            | Unknown                     | Notebook    | [0b79535c7f](https://bsd-hardware.info/?probe=0b79535c7f) | Mar 16, 2023 |
| Gigabyte      | F2A68HM-HD2                 | Desktop     | [da2b96de55](https://bsd-hardware.info/?probe=da2b96de55) | Mar 16, 2023 |
| Gigabyte      | Z87X-UD4H-CF                | Desktop     | [0bae1528b9](https://bsd-hardware.info/?probe=0bae1528b9) | Mar 16, 2023 |
| ASUSTek       | PRIME B660M-A D4            | Desktop     | [eb6b70b310](https://bsd-hardware.info/?probe=eb6b70b310) | Mar 16, 2023 |
| Intel         | NUC7i5BNB J31144-310        | Mini pc     | [c1c53bb88b](https://bsd-hardware.info/?probe=c1c53bb88b) | Mar 16, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [f14a448799](https://bsd-hardware.info/?probe=f14a448799) | Mar 16, 2023 |
| ASUSTek       | PRIME B660M-A WIFI D4       | Desktop     | [44c7f21a07](https://bsd-hardware.info/?probe=44c7f21a07) | Mar 16, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [dfa4f43317](https://bsd-hardware.info/?probe=dfa4f43317) | Mar 15, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [564b1ccce1](https://bsd-hardware.info/?probe=564b1ccce1) | Mar 15, 2023 |
| Gigabyte      | H61M-S2P-B3                 | Desktop     | [864a4017cb](https://bsd-hardware.info/?probe=864a4017cb) | Mar 15, 2023 |
| HP            | 3398                        | Desktop     | [b14de43688](https://bsd-hardware.info/?probe=b14de43688) | Mar 15, 2023 |
| Acer          | Aspire E5-571G              | Notebook    | [ca34dac813](https://bsd-hardware.info/?probe=ca34dac813) | Mar 15, 2023 |
| Samsung       | 275E4E/275E5E               | Notebook    | [dd4f7ef594](https://bsd-hardware.info/?probe=dd4f7ef594) | Mar 15, 2023 |
| HP            | 81B7                        | All in one  | [fa5eb6a694](https://bsd-hardware.info/?probe=fa5eb6a694) | Mar 15, 2023 |
| HP            | Pavilion TS Sleekbook 14    | Notebook    | [d57e5b1b88](https://bsd-hardware.info/?probe=d57e5b1b88) | Mar 15, 2023 |
| ASUSTek       | ROG STRIX B560-F GAMING ... | Desktop     | [c4798050c6](https://bsd-hardware.info/?probe=c4798050c6) | Mar 15, 2023 |
| ASUSTek       | Pro B550M-C                 | Desktop     | [a0e38ad11b](https://bsd-hardware.info/?probe=a0e38ad11b) | Mar 14, 2023 |
| Dell          | 00V62H A00                  | Desktop     | [ecb9b5d004](https://bsd-hardware.info/?probe=ecb9b5d004) | Mar 14, 2023 |
| Intel         | NUC8BEB J72692-308          | Mini pc     | [25256b1698](https://bsd-hardware.info/?probe=25256b1698) | Mar 14, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [89a5ee25f9](https://bsd-hardware.info/?probe=89a5ee25f9) | Mar 14, 2023 |
| Acer          | TravelMate P249-G2-M        | Notebook    | [090f37a821](https://bsd-hardware.info/?probe=090f37a821) | Mar 14, 2023 |
| Foxconn       | H61M/H61M-S                 | Desktop     | [865fbff42a](https://bsd-hardware.info/?probe=865fbff42a) | Mar 14, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [cb6b586564](https://bsd-hardware.info/?probe=cb6b586564) | Mar 14, 2023 |
| Fujitsu Si... | D2804-A1 S26361-D2804-A1    | Desktop     | [34c4bab715](https://bsd-hardware.info/?probe=34c4bab715) | Mar 14, 2023 |
| MSI           | 0A48                        | Desktop     | [815f019a8c](https://bsd-hardware.info/?probe=815f019a8c) | Mar 14, 2023 |
| Dell          | Latitude D630               | Notebook    | [da1fa73418](https://bsd-hardware.info/?probe=da1fa73418) | Mar 14, 2023 |
| HP            | Laptop 14-bs0xx             | Notebook    | [cd76713b75](https://bsd-hardware.info/?probe=cd76713b75) | Mar 14, 2023 |
| Dynabook E... | Satellite Pro E10-G-101     | Notebook    | [c58a37ef03](https://bsd-hardware.info/?probe=c58a37ef03) | Mar 14, 2023 |
| Lenovo        | NO DPK                      | Desktop     | [8a38ed8d33](https://bsd-hardware.info/?probe=8a38ed8d33) | Mar 14, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [6401dd52d2](https://bsd-hardware.info/?probe=6401dd52d2) | Mar 14, 2023 |
| AZW           | U59                         | Desktop     | [5a6ef3fb8d](https://bsd-hardware.info/?probe=5a6ef3fb8d) | Mar 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3448A... | Notebook    | [eaaf0fc8c7](https://bsd-hardware.info/?probe=eaaf0fc8c7) | Mar 14, 2023 |
| Toshiba       | Satellite L50-B             | Notebook    | [7052b38ba8](https://bsd-hardware.info/?probe=7052b38ba8) | Mar 14, 2023 |
| Lenovo        | ThinkCentre M58p 6138DK1    | Desktop     | [293de8b0fd](https://bsd-hardware.info/?probe=293de8b0fd) | Mar 14, 2023 |
| Lenovo        | ThinkPad L450 20DSS1S402    | Notebook    | [b4893ae18f](https://bsd-hardware.info/?probe=b4893ae18f) | Mar 14, 2023 |
| Toshiba       | Satellite A200              | Notebook    | [c49985d00b](https://bsd-hardware.info/?probe=c49985d00b) | Mar 13, 2023 |
| Lenovo        | ThinkPad P51 20HH001RMX     | Notebook    | [d9d7368322](https://bsd-hardware.info/?probe=d9d7368322) | Mar 13, 2023 |
| Google        | Panther                     | Desktop     | [3577da7e53](https://bsd-hardware.info/?probe=3577da7e53) | Mar 13, 2023 |
| Dell          | 01TN68 A02                  | Desktop     | [cb6c76df00](https://bsd-hardware.info/?probe=cb6c76df00) | Mar 13, 2023 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | Desktop     | [b337baf50e](https://bsd-hardware.info/?probe=b337baf50e) | Mar 13, 2023 |
| Samsung       | R468/R418                   | Notebook    | [af44a29d38](https://bsd-hardware.info/?probe=af44a29d38) | Mar 13, 2023 |
| Dell          | Inspiron 7520               | Notebook    | [8b259d99ec](https://bsd-hardware.info/?probe=8b259d99ec) | Mar 13, 2023 |
| Gigabyte      | B365M H                     | Desktop     | [7acb7cb65f](https://bsd-hardware.info/?probe=7acb7cb65f) | Mar 13, 2023 |
| ASUSTek       | PRIME H310M-A R2.0          | Desktop     | [e96ecce822](https://bsd-hardware.info/?probe=e96ecce822) | Mar 13, 2023 |
| HP            | 8056                        | Desktop     | [164b3e5c3f](https://bsd-hardware.info/?probe=164b3e5c3f) | Mar 13, 2023 |
| T-bao         | MINI PC                     | Desktop     | [d4440566b0](https://bsd-hardware.info/?probe=d4440566b0) | Mar 13, 2023 |
| Gigabyte      | G31M-S2L                    | Desktop     | [d210b12607](https://bsd-hardware.info/?probe=d210b12607) | Mar 13, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | Notebook    | [5ce3dfe4a2](https://bsd-hardware.info/?probe=5ce3dfe4a2) | Mar 13, 2023 |
| Gigabyte      | H110M-S2-CF                 | Desktop     | [6afb777789](https://bsd-hardware.info/?probe=6afb777789) | Mar 13, 2023 |
| Lenovo        | ThinkPad X200 74591P0       | Notebook    | [882cc7fc62](https://bsd-hardware.info/?probe=882cc7fc62) | Mar 13, 2023 |
| ASUSTek       | G74Sx                       | Notebook    | [6b7cf8fcac](https://bsd-hardware.info/?probe=6b7cf8fcac) | Mar 13, 2023 |
| Toshiba       | Satellite C845              | Notebook    | [0b680543b7](https://bsd-hardware.info/?probe=0b680543b7) | Mar 13, 2023 |
| Sony          | VGN-FZ19VN                  | Notebook    | [73809d943a](https://bsd-hardware.info/?probe=73809d943a) | Mar 13, 2023 |
| Dell          | 0W0CHX A00                  | Desktop     | [85a9fddd44](https://bsd-hardware.info/?probe=85a9fddd44) | Mar 12, 2023 |
| Intel         | NUC7i5BNB J31144-310        | Mini pc     | [de20e463ea](https://bsd-hardware.info/?probe=de20e463ea) | Mar 12, 2023 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [0eeb0661dd](https://bsd-hardware.info/?probe=0eeb0661dd) | Mar 12, 2023 |
| Fujitsu       | LIFEBOOK E736               | Notebook    | [1040a34321](https://bsd-hardware.info/?probe=1040a34321) | Mar 12, 2023 |
| Dell          | 0WMJ54 A00                  | Desktop     | [8a41ff57c2](https://bsd-hardware.info/?probe=8a41ff57c2) | Mar 12, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [9c1172aa29](https://bsd-hardware.info/?probe=9c1172aa29) | Mar 12, 2023 |
| HP            | Laptop 14-bs1xx             | Notebook    | [99446c8dd0](https://bsd-hardware.info/?probe=99446c8dd0) | Mar 12, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [7949f20162](https://bsd-hardware.info/?probe=7949f20162) | Mar 12, 2023 |
| MSI           | B450-A PRO                  | Desktop     | [b2d29a5bbc](https://bsd-hardware.info/?probe=b2d29a5bbc) | Mar 12, 2023 |
| Gigabyte      | H61M-DS2 x.x                | Desktop     | [a39b128f44](https://bsd-hardware.info/?probe=a39b128f44) | Mar 12, 2023 |
| Lenovo        | ThinkPad X200 2024AY7       | Notebook    | [bb432faf36](https://bsd-hardware.info/?probe=bb432faf36) | Mar 12, 2023 |
| Lenovo        | ZIUS6                       | Notebook    | [d387825f01](https://bsd-hardware.info/?probe=d387825f01) | Mar 12, 2023 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [34afe9e044](https://bsd-hardware.info/?probe=34afe9e044) | Mar 12, 2023 |
| Axiomtek      | IMB211                      | Desktop     | [aebf680e82](https://bsd-hardware.info/?probe=aebf680e82) | Mar 12, 2023 |
| Dell          | Latitude E6330              | Notebook    | [5c60cd3d04](https://bsd-hardware.info/?probe=5c60cd3d04) | Mar 12, 2023 |
| Axiomtek      | IMB211                      | Desktop     | [6c50fda85b](https://bsd-hardware.info/?probe=6c50fda85b) | Mar 12, 2023 |
| Lenovo        | ThinkPad T440p              | Notebook    | [6d372db804](https://bsd-hardware.info/?probe=6d372db804) | Mar 12, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [5bcd236c4a](https://bsd-hardware.info/?probe=5bcd236c4a) | Mar 12, 2023 |
| ASUSTek       | A8N-E                       | Desktop     | [5fc3d86bac](https://bsd-hardware.info/?probe=5fc3d86bac) | Mar 12, 2023 |
| MSI           | H61M-E22                    | Desktop     | [227c78f3c1](https://bsd-hardware.info/?probe=227c78f3c1) | Mar 12, 2023 |
| ASRock        | Q1900M                      | Desktop     | [5d0f6c2276](https://bsd-hardware.info/?probe=5d0f6c2276) | Mar 12, 2023 |
| HP            | 8768 A                      | Desktop     | [5ab1dadbab](https://bsd-hardware.info/?probe=5ab1dadbab) | Mar 12, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [ad604088a2](https://bsd-hardware.info/?probe=ad604088a2) | Mar 12, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [6e97a003ec](https://bsd-hardware.info/?probe=6e97a003ec) | Mar 12, 2023 |
| Acer          | Veriton N2620G              | Desktop     | [fa57448331](https://bsd-hardware.info/?probe=fa57448331) | Mar 12, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [593f6ff02d](https://bsd-hardware.info/?probe=593f6ff02d) | Mar 12, 2023 |
| Acer          | Swift SF314-42              | Notebook    | [aa89c48cb7](https://bsd-hardware.info/?probe=aa89c48cb7) | Mar 12, 2023 |
| Apple         | MacBookAir1,1               | Notebook    | [2142f08b3f](https://bsd-hardware.info/?probe=2142f08b3f) | Mar 12, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [ededc04017](https://bsd-hardware.info/?probe=ededc04017) | Mar 12, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [37ee7b4f47](https://bsd-hardware.info/?probe=37ee7b4f47) | Mar 12, 2023 |
| Fujitsu       | JIM86YD                     | Desktop     | [7a69b91093](https://bsd-hardware.info/?probe=7a69b91093) | Mar 12, 2023 |
| MSI           | H61M-P31/W8                 | Desktop     | [5ae8ebe3cd](https://bsd-hardware.info/?probe=5ae8ebe3cd) | Mar 11, 2023 |
| HP            | 843B                        | Desktop     | [c1886bcd29](https://bsd-hardware.info/?probe=c1886bcd29) | Mar 11, 2023 |
| HP            | Laptop 15-bs1xx             | Notebook    | [1df045ffd0](https://bsd-hardware.info/?probe=1df045ffd0) | Mar 11, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2BR0... | Notebook    | [56fa0d4656](https://bsd-hardware.info/?probe=56fa0d4656) | Mar 11, 2023 |
| Dell          | Latitude E5450              | Notebook    | [4bb2040221](https://bsd-hardware.info/?probe=4bb2040221) | Mar 11, 2023 |
| HP            | 3398                        | Desktop     | [20bcb682d8](https://bsd-hardware.info/?probe=20bcb682d8) | Mar 11, 2023 |
| ASUSTek       | P8Z68-V                     | Desktop     | [3d8ef63e18](https://bsd-hardware.info/?probe=3d8ef63e18) | Mar 11, 2023 |
| Lenovo        | ThinkPad L590 20Q7U04602    | Notebook    | [64a11e18da](https://bsd-hardware.info/?probe=64a11e18da) | Mar 11, 2023 |
| Lenovo        | ThinkPad X230 23252G8       | Notebook    | [2ff46d6b7c](https://bsd-hardware.info/?probe=2ff46d6b7c) | Mar 10, 2023 |
| Clevo         | W240EL/W250ELQ/W270ELQ      | Notebook    | [aafc670aa7](https://bsd-hardware.info/?probe=aafc670aa7) | Mar 08, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [d05a143723](https://bsd-hardware.info/?probe=d05a143723) | Mar 08, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3444F... | Notebook    | [1a31b27b2a](https://bsd-hardware.info/?probe=1a31b27b2a) | Mar 08, 2023 |
| ASUSTek       | 1201N                       | Notebook    | [5dc595eb79](https://bsd-hardware.info/?probe=5dc595eb79) | Mar 05, 2023 |
| ASUSTek       | 1201N                       | Notebook    | [daa787f637](https://bsd-hardware.info/?probe=daa787f637) | Mar 05, 2023 |
| Lenovo        | G400s 20244                 | Notebook    | [215f16c5d9](https://bsd-hardware.info/?probe=215f16c5d9) | Mar 05, 2023 |
| Gigabyte      | X570 UD                     | Desktop     | [13e4d3ce10](https://bsd-hardware.info/?probe=13e4d3ce10) | Mar 05, 2023 |
| Lenovo        | IdeaPad 310-14IKB 80TU      | Notebook    | [8037475831](https://bsd-hardware.info/?probe=8037475831) | Mar 05, 2023 |
| HP            | EliteBook 2730p             | Notebook    | [3c404c9d20](https://bsd-hardware.info/?probe=3c404c9d20) | Mar 05, 2023 |
| Acer          | TravelMate TX50-G2          | Notebook    | [81ab6d240f](https://bsd-hardware.info/?probe=81ab6d240f) | Mar 05, 2023 |
| ASUSTek       | PRIME A320M-E               | Desktop     | [ca70bceb83](https://bsd-hardware.info/?probe=ca70bceb83) | Mar 05, 2023 |
| ASUSTek       | P7H55                       | Desktop     | [3c78171104](https://bsd-hardware.info/?probe=3c78171104) | Mar 04, 2023 |
| ASUSTek       | P7H55                       | Desktop     | [5ce8dbf5f3](https://bsd-hardware.info/?probe=5ce8dbf5f3) | Mar 04, 2023 |
| HP            | G62                         | Notebook    | [18487b3ab2](https://bsd-hardware.info/?probe=18487b3ab2) | Mar 02, 2023 |
| Sony          | SVE1511C5E                  | Notebook    | [0e972db389](https://bsd-hardware.info/?probe=0e972db389) | Mar 02, 2023 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [29290b1b9c](https://bsd-hardware.info/?probe=29290b1b9c) | Mar 01, 2023 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [5eb87a21db](https://bsd-hardware.info/?probe=5eb87a21db) | Mar 01, 2023 |
| Sony          | SVE1511C5E                  | Notebook    | [6aa87871c2](https://bsd-hardware.info/?probe=6aa87871c2) | Mar 01, 2023 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [a919e85270](https://bsd-hardware.info/?probe=a919e85270) | Feb 28, 2023 |
| Notebook      | N2x0WU                      | Notebook    | [9545f36dee](https://bsd-hardware.info/?probe=9545f36dee) | Feb 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [115bd3bc38](https://bsd-hardware.info/?probe=115bd3bc38) | Feb 26, 2023 |
| Fujitsu       | D3009-A1 S26361-D3009-A1    | Desktop     | [66739867ed](https://bsd-hardware.info/?probe=66739867ed) | Feb 26, 2023 |
| Dell          | Inspiron 15 3515            | Notebook    | [b480a98b22](https://bsd-hardware.info/?probe=b480a98b22) | Feb 26, 2023 |
| Lenovo        | ThinkPad P51 20HH001RMX     | Notebook    | [59e609fbb2](https://bsd-hardware.info/?probe=59e609fbb2) | Feb 26, 2023 |
| Intel         | NUC11PABi5 K90634-305       | Mini pc     | [33330ade31](https://bsd-hardware.info/?probe=33330ade31) | Feb 25, 2023 |
| Samsung       | 270E5K/270E5Q/271E5K/257... | Notebook    | [45549e4faf](https://bsd-hardware.info/?probe=45549e4faf) | Feb 25, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [be81f2675f](https://bsd-hardware.info/?probe=be81f2675f) | Feb 25, 2023 |
| Toshiba       | dynabook R63/P              | Notebook    | [c41c3adfa4](https://bsd-hardware.info/?probe=c41c3adfa4) | Feb 25, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [b3e56e9656](https://bsd-hardware.info/?probe=b3e56e9656) | Feb 25, 2023 |
| ASRock        | X470 Gaming K4              | Desktop     | [fbff29a62a](https://bsd-hardware.info/?probe=fbff29a62a) | Feb 25, 2023 |
| Dell          | Latitude 5591               | Notebook    | [fb33d7a0c4](https://bsd-hardware.info/?probe=fb33d7a0c4) | Feb 25, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [0480ce43f2](https://bsd-hardware.info/?probe=0480ce43f2) | Feb 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | Notebook    | [95c66df5a4](https://bsd-hardware.info/?probe=95c66df5a4) | Feb 24, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [31122bd298](https://bsd-hardware.info/?probe=31122bd298) | Feb 24, 2023 |
| Plaisio       | Turbo X                     | Notebook    | [e0a8a02bb9](https://bsd-hardware.info/?probe=e0a8a02bb9) | Feb 23, 2023 |
| Dell          | 0C27VV A02                  | Desktop     | [5899533edd](https://bsd-hardware.info/?probe=5899533edd) | Feb 23, 2023 |
| Intel         | DG41TY AAE47335-300         | Desktop     | [7c1727d55a](https://bsd-hardware.info/?probe=7c1727d55a) | Feb 22, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [77c17e4a2f](https://bsd-hardware.info/?probe=77c17e4a2f) | Feb 22, 2023 |
| Dell          | 0C27VV A02                  | Desktop     | [a10df954b7](https://bsd-hardware.info/?probe=a10df954b7) | Feb 22, 2023 |
| Huanan        | X99-TF GAMING V3.0          | Desktop     | [59db63fd9d](https://bsd-hardware.info/?probe=59db63fd9d) | Feb 22, 2023 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | Notebook    | [d04d402809](https://bsd-hardware.info/?probe=d04d402809) | Feb 21, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [02970305db](https://bsd-hardware.info/?probe=02970305db) | Feb 21, 2023 |
| Lenovo        | ThinkPad L450 20DSS1S402    | Notebook    | [06e5309c55](https://bsd-hardware.info/?probe=06e5309c55) | Feb 20, 2023 |
| Lenovo        | ThinkPad T410 2537B94       | Notebook    | [9f9cb3e201](https://bsd-hardware.info/?probe=9f9cb3e201) | Feb 19, 2023 |
| Acer          | Aspire E1-421               | Notebook    | [db00abb833](https://bsd-hardware.info/?probe=db00abb833) | Feb 19, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [92bca4d026](https://bsd-hardware.info/?probe=92bca4d026) | Feb 19, 2023 |
| Huanan        | X99-TF GAMING V3.0          | Desktop     | [50dce9bf96](https://bsd-hardware.info/?probe=50dce9bf96) | Feb 19, 2023 |
| Lenovo        | G400s 20244                 | Notebook    | [f2c258a0ae](https://bsd-hardware.info/?probe=f2c258a0ae) | Feb 19, 2023 |
| Lenovo        | ThinkPad T520 4243F39       | Notebook    | [d8ba5b3157](https://bsd-hardware.info/?probe=d8ba5b3157) | Feb 19, 2023 |
| Gigabyte      | GB-BSi3A-6100               | Notebook    | [e7ef795b9b](https://bsd-hardware.info/?probe=e7ef795b9b) | Feb 19, 2023 |
| Gigabyte      | GB-BSi3A-6100               | Notebook    | [cd2273037f](https://bsd-hardware.info/?probe=cd2273037f) | Feb 19, 2023 |
| Lenovo        | ThinkPad T520 4243F39       | Notebook    | [820596f359](https://bsd-hardware.info/?probe=820596f359) | Feb 18, 2023 |
| Dell          | Inspiron 5767               | Notebook    | [39b4581223](https://bsd-hardware.info/?probe=39b4581223) | Feb 18, 2023 |
| Lenovo        | ThinkPad T61p 6457UN2       | Notebook    | [67b2e8db2b](https://bsd-hardware.info/?probe=67b2e8db2b) | Feb 18, 2023 |
| Dell          | Inspiron 5767               | Notebook    | [fd58d235b3](https://bsd-hardware.info/?probe=fd58d235b3) | Feb 18, 2023 |
| Lenovo        | ThinkPad T61p 6457UN2       | Notebook    | [f7646f9d7f](https://bsd-hardware.info/?probe=f7646f9d7f) | Feb 18, 2023 |
| Gigabyte      | B450M AORUS ELITE           | Desktop     | [6af537ff20](https://bsd-hardware.info/?probe=6af537ff20) | Feb 18, 2023 |
| ASUSTek       | PRIME H310M-C R2.0          | Desktop     | [9761fb446b](https://bsd-hardware.info/?probe=9761fb446b) | Feb 18, 2023 |
| Lenovo        | ThinkPad T430u 33522D5      | Notebook    | [d5bbbb8cbe](https://bsd-hardware.info/?probe=d5bbbb8cbe) | Feb 17, 2023 |
| ASRock        | A320M-DGS                   | Desktop     | [032d7f0c91](https://bsd-hardware.info/?probe=032d7f0c91) | Feb 17, 2023 |
| Google        | Lulu                        | Notebook    | [cf598483cf](https://bsd-hardware.info/?probe=cf598483cf) | Feb 17, 2023 |
| Unknown       | CMB-A9SC2                   | Server      | [6d3e23081c](https://bsd-hardware.info/?probe=6d3e23081c) | Feb 17, 2023 |
| ASUSTek       | P8Z68-V LX                  | Desktop     | [99ede66a89](https://bsd-hardware.info/?probe=99ede66a89) | Feb 16, 2023 |
| HP            | 3398                        | Desktop     | [186e63e8fe](https://bsd-hardware.info/?probe=186e63e8fe) | Feb 15, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [8820014583](https://bsd-hardware.info/?probe=8820014583) | Feb 15, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [592ca6bab5](https://bsd-hardware.info/?probe=592ca6bab5) | Feb 15, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [35aa7d7f04](https://bsd-hardware.info/?probe=35aa7d7f04) | Feb 15, 2023 |
| HP            | OMEN by Gaming Laptop 16... | Notebook    | [00142b4e4c](https://bsd-hardware.info/?probe=00142b4e4c) | Feb 14, 2023 |
| MECHREVO S... | S1 Series                   | Notebook    | [26c3b9bf4f](https://bsd-hardware.info/?probe=26c3b9bf4f) | Feb 14, 2023 |
| MECHREVO S... | S1 Series                   | Notebook    | [1d948a1a23](https://bsd-hardware.info/?probe=1d948a1a23) | Feb 14, 2023 |
| Lenovo        | ThinkPad T520 4243F39       | Notebook    | [9137c7933c](https://bsd-hardware.info/?probe=9137c7933c) | Feb 13, 2023 |
| Dell          | 0D28YY A03                  | Desktop     | [b8dc69069d](https://bsd-hardware.info/?probe=b8dc69069d) | Feb 12, 2023 |
| Medion        | S4401 MD61519               | Convertible | [6cd6b15a60](https://bsd-hardware.info/?probe=6cd6b15a60) | Feb 12, 2023 |
| Intel         | NUC11TNBi5 M11904-404       | Mini pc     | [ba1b9f0010](https://bsd-hardware.info/?probe=ba1b9f0010) | Feb 12, 2023 |
| Intel         | NUC7i5BNB J31144-305        | Mini pc     | [60f03e1dec](https://bsd-hardware.info/?probe=60f03e1dec) | Feb 12, 2023 |
| Dell          | 0PU052                      | Desktop     | [03bcc500c0](https://bsd-hardware.info/?probe=03bcc500c0) | Feb 12, 2023 |
| Dell          | 0PU052                      | Desktop     | [035408150f](https://bsd-hardware.info/?probe=035408150f) | Feb 11, 2023 |
| ASUSTek       | P8Z68-V                     | Desktop     | [74ebc950e2](https://bsd-hardware.info/?probe=74ebc950e2) | Feb 11, 2023 |
| ASRock        | H61M/U3S3                   | Desktop     | [48c80bbb1f](https://bsd-hardware.info/?probe=48c80bbb1f) | Feb 11, 2023 |
| HP            | 83EE                        | Desktop     | [cf914f58eb](https://bsd-hardware.info/?probe=cf914f58eb) | Feb 10, 2023 |
| ASRock        | A770DE+                     | Desktop     | [cf1c018ede](https://bsd-hardware.info/?probe=cf1c018ede) | Feb 10, 2023 |
| MSI           | GF76 12UE                   | Notebook    | [371f734e07](https://bsd-hardware.info/?probe=371f734e07) | Feb 10, 2023 |
| Apple         | Mac-4B682C642B45593E iMa... | All in one  | [367edc6620](https://bsd-hardware.info/?probe=367edc6620) | Feb 10, 2023 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [d6be869761](https://bsd-hardware.info/?probe=d6be869761) | Feb 09, 2023 |
| Apple         | Mac-4B682C642B45593E iMa... | All in one  | [1d8b9a30c5](https://bsd-hardware.info/?probe=1d8b9a30c5) | Feb 09, 2023 |
| AZW           | GTR V01                     | Mini pc     | [0cfac4d34d](https://bsd-hardware.info/?probe=0cfac4d34d) | Feb 09, 2023 |
| Sony          | SVF1421E4E                  | Notebook    | [d0a9e97993](https://bsd-hardware.info/?probe=d0a9e97993) | Feb 09, 2023 |
| Biostar       | TA970                       | Desktop     | [8c1a7aedf1](https://bsd-hardware.info/?probe=8c1a7aedf1) | Feb 09, 2023 |
| HP            | Laptop 14-df0xxx            | Notebook    | [1dc503f21d](https://bsd-hardware.info/?probe=1dc503f21d) | Feb 09, 2023 |
| Acer          | Aspire 4739Z                | Notebook    | [1e97a0b938](https://bsd-hardware.info/?probe=1e97a0b938) | Feb 09, 2023 |
| Intel         | NUC10i7FNB K61360-304       | Mini pc     | [5c2047356d](https://bsd-hardware.info/?probe=5c2047356d) | Feb 08, 2023 |
| ASUSTek       | N76VZ                       | Notebook    | [3b7e2ee70b](https://bsd-hardware.info/?probe=3b7e2ee70b) | Feb 08, 2023 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [9af803f850](https://bsd-hardware.info/?probe=9af803f850) | Feb 08, 2023 |
| ASUSTek       | K84L                        | Notebook    | [d58c178c51](https://bsd-hardware.info/?probe=d58c178c51) | Feb 08, 2023 |
| HP            | Notebook                    | Notebook    | [507e85c092](https://bsd-hardware.info/?probe=507e85c092) | Feb 08, 2023 |
| ASUSTek       | 1201N                       | Notebook    | [3f44d6ed3f](https://bsd-hardware.info/?probe=3f44d6ed3f) | Feb 08, 2023 |
| MSI           | Z97 GAMING 3                | Desktop     | [bbe7b327fd](https://bsd-hardware.info/?probe=bbe7b327fd) | Feb 06, 2023 |
| Lenovo        | IdeaPad 3 15IML05 82BS      | Notebook    | [3345f50844](https://bsd-hardware.info/?probe=3345f50844) | Feb 06, 2023 |
| HP            | Notebook                    | Notebook    | [8d8e5c294a](https://bsd-hardware.info/?probe=8d8e5c294a) | Feb 06, 2023 |
| AOpen         | D1007 0BBA                  | Desktop     | [0873652381](https://bsd-hardware.info/?probe=0873652381) | Feb 06, 2023 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [8083410c50](https://bsd-hardware.info/?probe=8083410c50) | Feb 06, 2023 |
| ASUSTek       | P8Z77-M                     | Desktop     | [627bdfafb7](https://bsd-hardware.info/?probe=627bdfafb7) | Feb 06, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | Notebook    | [78a978a8d4](https://bsd-hardware.info/?probe=78a978a8d4) | Feb 06, 2023 |
| Biostar       | H61MLV3                     | Desktop     | [dee9a22461](https://bsd-hardware.info/?probe=dee9a22461) | Feb 06, 2023 |
| Lenovo        | ThinkPad X380 Yoga 20LH0... | Convertible | [27702234cc](https://bsd-hardware.info/?probe=27702234cc) | Feb 06, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [c04d9caf55](https://bsd-hardware.info/?probe=c04d9caf55) | Feb 06, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3448A... | Notebook    | [80f8e59cab](https://bsd-hardware.info/?probe=80f8e59cab) | Feb 05, 2023 |
| Gigabyte      | H510M S2H V2                | Desktop     | [85628154a2](https://bsd-hardware.info/?probe=85628154a2) | Feb 05, 2023 |
| HP            | 2000                        | Notebook    | [7c997ce022](https://bsd-hardware.info/?probe=7c997ce022) | Feb 05, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [c771b7daf4](https://bsd-hardware.info/?probe=c771b7daf4) | Feb 05, 2023 |
| Notebook      | NV4XMB,ME,MZ                | Notebook    | [8a2bba8635](https://bsd-hardware.info/?probe=8a2bba8635) | Feb 05, 2023 |
| Dell          | 0PC5F7 A02                  | Desktop     | [5512097fd0](https://bsd-hardware.info/?probe=5512097fd0) | Feb 05, 2023 |
| Lenovo        | G70-70 80HW006AGE           | Notebook    | [a52e13cf4e](https://bsd-hardware.info/?probe=a52e13cf4e) | Feb 04, 2023 |
| Lenovo        | B50-80 80EW                 | Notebook    | [97da411601](https://bsd-hardware.info/?probe=97da411601) | Feb 04, 2023 |
| Lenovo        | B50-80 80EW                 | Notebook    | [a8ec146fc6](https://bsd-hardware.info/?probe=a8ec146fc6) | Feb 04, 2023 |
| Lenovo        | ThinkPad T520 4243F39       | Notebook    | [c0a6490fc8](https://bsd-hardware.info/?probe=c0a6490fc8) | Feb 03, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [7c56590eaa](https://bsd-hardware.info/?probe=7c56590eaa) | Feb 03, 2023 |
| Lenovo        | SKYBAY 31900002 WIN 1801... | All in one  | [725797b27e](https://bsd-hardware.info/?probe=725797b27e) | Feb 02, 2023 |
| Monster       | ABRA A7 V11.2               | Notebook    | [3e58da5c30](https://bsd-hardware.info/?probe=3e58da5c30) | Feb 02, 2023 |
| Unknown       | Unknown                     | Notebook    | [a7d54d41c8](https://bsd-hardware.info/?probe=a7d54d41c8) | Feb 02, 2023 |
| Monster       | ABRA A7 V11.2               | Notebook    | [3309453ed5](https://bsd-hardware.info/?probe=3309453ed5) | Feb 02, 2023 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [fa88a5ce31](https://bsd-hardware.info/?probe=fa88a5ce31) | Feb 02, 2023 |
| HP            | Mini 210-1000               | Notebook    | [eaabd2a89d](https://bsd-hardware.info/?probe=eaabd2a89d) | Feb 02, 2023 |
| HP            | ENVY TS m6 Sleekbook        | Notebook    | [402494618a](https://bsd-hardware.info/?probe=402494618a) | Feb 01, 2023 |
| HP            | ENVY TS m6 Sleekbook        | Notebook    | [63d90da096](https://bsd-hardware.info/?probe=63d90da096) | Feb 01, 2023 |
| Gigabyte      | Z390 AORUS ELITE-CF         | Desktop     | [161dad9f5d](https://bsd-hardware.info/?probe=161dad9f5d) | Jan 31, 2023 |
| Acer          | Aspire ES1-520              | Notebook    | [efac696b1a](https://bsd-hardware.info/?probe=efac696b1a) | Jan 31, 2023 |
| MSI           | Modern 15 A5M               | Notebook    | [afda1bcf60](https://bsd-hardware.info/?probe=afda1bcf60) | Jan 31, 2023 |
| HP            | EliteBook 8440p             | Notebook    | [d732f4d6c4](https://bsd-hardware.info/?probe=d732f4d6c4) | Jan 31, 2023 |
| HP            | 1496                        | Desktop     | [fae90baa23](https://bsd-hardware.info/?probe=fae90baa23) | Jan 31, 2023 |
| MSI           | Modern 15 A5M               | Notebook    | [26d140b290](https://bsd-hardware.info/?probe=26d140b290) | Jan 31, 2023 |
| MACHINIST     | X99-K9 V2.0                 | Desktop     | [eb8a6cb004](https://bsd-hardware.info/?probe=eb8a6cb004) | Jan 30, 2023 |
| Dell          | 0F373D A00                  | Desktop     | [cd4202e58b](https://bsd-hardware.info/?probe=cd4202e58b) | Jan 30, 2023 |
| Dell          | Precision 5540              | Notebook    | [de7ac2f8d1](https://bsd-hardware.info/?probe=de7ac2f8d1) | Jan 30, 2023 |
| Apple         | MacBookAir5,1               | Notebook    | [eeed92ab62](https://bsd-hardware.info/?probe=eeed92ab62) | Jan 29, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3448A... | Notebook    | [6da773c078](https://bsd-hardware.info/?probe=6da773c078) | Jan 29, 2023 |
| Unknown       | TJ41G-A80 v2 Series         | All in one  | [c44ac785cc](https://bsd-hardware.info/?probe=c44ac785cc) | Jan 29, 2023 |
| Unknown       | TJ41G-A80 v2 Series         | All in one  | [a5bc81b507](https://bsd-hardware.info/?probe=a5bc81b507) | Jan 29, 2023 |
| Razer         | Blade Stealth               | Notebook    | [c0b9641604](https://bsd-hardware.info/?probe=c0b9641604) | Jan 29, 2023 |
| Lenovo        | IdeaPad 110-14AST 80TQ      | Notebook    | [aed5292edc](https://bsd-hardware.info/?probe=aed5292edc) | Jan 28, 2023 |
| Packard Be... | DOT S                       | Notebook    | [09a2057767](https://bsd-hardware.info/?probe=09a2057767) | Jan 28, 2023 |
| Razer         | Blade Stealth               | Notebook    | [14760d0c64](https://bsd-hardware.info/?probe=14760d0c64) | Jan 28, 2023 |
| ASUSTek       | M4A89TD PRO USB3            | Desktop     | [1328d01296](https://bsd-hardware.info/?probe=1328d01296) | Jan 28, 2023 |
| Lenovo        | ThinkPad T460 20FMS06V00    | Notebook    | [6914f6aab5](https://bsd-hardware.info/?probe=6914f6aab5) | Jan 28, 2023 |
| Lenovo        | ThinkPad E585 20KV0010US    | Notebook    | [9cfe2dd858](https://bsd-hardware.info/?probe=9cfe2dd858) | Jan 28, 2023 |
| Acer          | ES1-131-C2BM                | Notebook    | [400ef90a79](https://bsd-hardware.info/?probe=400ef90a79) | Jan 28, 2023 |
| Dell          | Latitude 5400               | Notebook    | [a266199ace](https://bsd-hardware.info/?probe=a266199ace) | Jan 27, 2023 |
| Acer          | Aspire E3-112               | Notebook    | [513c7ff4be](https://bsd-hardware.info/?probe=513c7ff4be) | Jan 27, 2023 |
| Acidanther... | Mac-AA95B1DDAB278B95 iMa... | All in one  | [3492d9a849](https://bsd-hardware.info/?probe=3492d9a849) | Jan 27, 2023 |
| Gigabyte      | GA-MA770T-UD3               | Desktop     | [6b63a16799](https://bsd-hardware.info/?probe=6b63a16799) | Jan 26, 2023 |
| Gigabyte      | B360M D2V                   | Desktop     | [6685066b6e](https://bsd-hardware.info/?probe=6685066b6e) | Jan 26, 2023 |
| ASUSTek       | H81M-D R2.0                 | Desktop     | [07982549ac](https://bsd-hardware.info/?probe=07982549ac) | Jan 26, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [9a307961ed](https://bsd-hardware.info/?probe=9a307961ed) | Jan 26, 2023 |
| Google        | Cave                        | Notebook    | [76ac12f1e2](https://bsd-hardware.info/?probe=76ac12f1e2) | Jan 25, 2023 |
| ASUSTek       | PRIME H310M-K               | Desktop     | [1c97950ce9](https://bsd-hardware.info/?probe=1c97950ce9) | Jan 25, 2023 |
| Lenovo        | ThinkPad X1 Tablet 20GHS... | Tablet      | [cd05b84425](https://bsd-hardware.info/?probe=cd05b84425) | Jan 25, 2023 |
| ASRock        | X299E-ITX/ac                | Desktop     | [0b7dacf902](https://bsd-hardware.info/?probe=0b7dacf902) | Jan 25, 2023 |
| HP            | EliteBook 2560p             | Notebook    | [80c808de34](https://bsd-hardware.info/?probe=80c808de34) | Jan 25, 2023 |
| ASUSTek       | P7P55D LE                   | Desktop     | [5da1e71837](https://bsd-hardware.info/?probe=5da1e71837) | Jan 25, 2023 |
| Timi          | TM1607                      | Notebook    | [57113d2886](https://bsd-hardware.info/?probe=57113d2886) | Jan 25, 2023 |
| Dell          | 0D02VH A01                  | Desktop     | [ad7dd00eeb](https://bsd-hardware.info/?probe=ad7dd00eeb) | Jan 25, 2023 |
| HP            | 802E                        | Desktop     | [1f3bf517af](https://bsd-hardware.info/?probe=1f3bf517af) | Jan 25, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [081d22fbe2](https://bsd-hardware.info/?probe=081d22fbe2) | Jan 24, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [a35053ad38](https://bsd-hardware.info/?probe=a35053ad38) | Jan 24, 2023 |
| Google        | Panther                     | Desktop     | [73d3147166](https://bsd-hardware.info/?probe=73d3147166) | Jan 24, 2023 |
| Biostar       | TB250-BTC+                  | Desktop     | [0a39ffa716](https://bsd-hardware.info/?probe=0a39ffa716) | Jan 24, 2023 |
| MSI           | PS63 Modern 8M              | Notebook    | [f740e313e5](https://bsd-hardware.info/?probe=f740e313e5) | Jan 24, 2023 |
| Timi          | TM1607                      | Notebook    | [27db14fdbd](https://bsd-hardware.info/?probe=27db14fdbd) | Jan 24, 2023 |
| Fujitsu       | LIFEBOOK S935               | Notebook    | [5c07c1a47e](https://bsd-hardware.info/?probe=5c07c1a47e) | Jan 24, 2023 |
| Dell          | Latitude 3540               | Notebook    | [a180a149f5](https://bsd-hardware.info/?probe=a180a149f5) | Jan 24, 2023 |
| Dell          | 0DFRFW A01                  | Desktop     | [23415b954f](https://bsd-hardware.info/?probe=23415b954f) | Jan 24, 2023 |
| Dell          | Latitude 5580               | Notebook    | [90cd22ad55](https://bsd-hardware.info/?probe=90cd22ad55) | Jan 24, 2023 |
| HP            | 1495                        | Desktop     | [69faf0563a](https://bsd-hardware.info/?probe=69faf0563a) | Jan 24, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [556e872ffe](https://bsd-hardware.info/?probe=556e872ffe) | Jan 24, 2023 |
| Toshiba       | PORTEGE Z930                | Notebook    | [476203ee86](https://bsd-hardware.info/?probe=476203ee86) | Jan 23, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [aaccb6df1a](https://bsd-hardware.info/?probe=aaccb6df1a) | Jan 23, 2023 |
| Toshiba       | PORTEGE Z930                | Notebook    | [4af2cc1909](https://bsd-hardware.info/?probe=4af2cc1909) | Jan 23, 2023 |
| Gigabyte      | GA-990X-Gaming SLI-CF       | Desktop     | [9cd4d2810a](https://bsd-hardware.info/?probe=9cd4d2810a) | Jan 23, 2023 |
| ASUSTek       | K50IN                       | Notebook    | [6f7a8f3338](https://bsd-hardware.info/?probe=6f7a8f3338) | Jan 23, 2023 |
| Lenovo        | ThinkPad W541 20EF000NUS    | Notebook    | [200a92d510](https://bsd-hardware.info/?probe=200a92d510) | Jan 23, 2023 |
| Star Labs     | StarBook                    | Notebook    | [d222f381b0](https://bsd-hardware.info/?probe=d222f381b0) | Jan 23, 2023 |
| Star Labs     | StarBook                    | Notebook    | [045d4bb6e8](https://bsd-hardware.info/?probe=045d4bb6e8) | Jan 23, 2023 |
| ASRock        | Z390 Pro4                   | Desktop     | [b9d64a7496](https://bsd-hardware.info/?probe=b9d64a7496) | Jan 23, 2023 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [6cf4f6761e](https://bsd-hardware.info/?probe=6cf4f6761e) | Jan 23, 2023 |
| Gigabyte      | A520M S2H                   | Desktop     | [803a152afc](https://bsd-hardware.info/?probe=803a152afc) | Jan 23, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [cdad2f0001](https://bsd-hardware.info/?probe=cdad2f0001) | Jan 23, 2023 |
| Dell          | Inspiron 15-7568            | Notebook    | [44e36adfa4](https://bsd-hardware.info/?probe=44e36adfa4) | Jan 23, 2023 |
| ASUSTek       | J1800I-C                    | Desktop     | [27ea626000](https://bsd-hardware.info/?probe=27ea626000) | Jan 23, 2023 |
| ASUSTek       | J1800I-C                    | Desktop     | [abc17c6fc6](https://bsd-hardware.info/?probe=abc17c6fc6) | Jan 23, 2023 |
| Lenovo        | ThinkPad S1 Yoga 20CD003... | Notebook    | [17fd94a4c0](https://bsd-hardware.info/?probe=17fd94a4c0) | Jan 23, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [d03f9c19f8](https://bsd-hardware.info/?probe=d03f9c19f8) | Jan 23, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [840145eb80](https://bsd-hardware.info/?probe=840145eb80) | Jan 23, 2023 |
| Dell          | Inspiron 3442               | Notebook    | [8b137bca84](https://bsd-hardware.info/?probe=8b137bca84) | Jan 23, 2023 |
| Timi          | TM1607                      | Notebook    | [7636a0ef8f](https://bsd-hardware.info/?probe=7636a0ef8f) | Jan 23, 2023 |
| Timi          | TM1607                      | Notebook    | [1ca46404a1](https://bsd-hardware.info/?probe=1ca46404a1) | Jan 23, 2023 |
| Dell          | 0HHV7N A00                  | Desktop     | [771f2c4d96](https://bsd-hardware.info/?probe=771f2c4d96) | Jan 23, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [881e97e41c](https://bsd-hardware.info/?probe=881e97e41c) | Jan 23, 2023 |
| ASUSTek       | X99-A/USB                   | Desktop     | [006553f965](https://bsd-hardware.info/?probe=006553f965) | Jan 23, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [4b3a05fc2a](https://bsd-hardware.info/?probe=4b3a05fc2a) | Jan 22, 2023 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [6dc0fddda1](https://bsd-hardware.info/?probe=6dc0fddda1) | Jan 22, 2023 |
| Acer          | Aspire ES1-533              | Notebook    | [d2652b76cf](https://bsd-hardware.info/?probe=d2652b76cf) | Jan 22, 2023 |
| ASUSTek       | Q405UA                      | Convertible | [6662cab62d](https://bsd-hardware.info/?probe=6662cab62d) | Jan 22, 2023 |
| ASUSTek       | Q405UA                      | Convertible | [2b94c3efae](https://bsd-hardware.info/?probe=2b94c3efae) | Jan 22, 2023 |
| Dell          | 03KWTV A02                  | Desktop     | [28088f7e94](https://bsd-hardware.info/?probe=28088f7e94) | Jan 22, 2023 |
| Lenovo        | ThinkPad P50 20EN0041MX     | Notebook    | [c27f1f53f2](https://bsd-hardware.info/?probe=c27f1f53f2) | Jan 22, 2023 |
| HP            | Laptop 15-bs0xx             | Notebook    | [7bd5f0c2e9](https://bsd-hardware.info/?probe=7bd5f0c2e9) | Jan 22, 2023 |
| Intel         | H61                         | Desktop     | [7faeca8300](https://bsd-hardware.info/?probe=7faeca8300) | Jan 22, 2023 |
| Panasonic     | CF-C1BWFAZ1M                | Notebook    | [d129d929ac](https://bsd-hardware.info/?probe=d129d929ac) | Jan 22, 2023 |
| Lenovo        | ThinkPad P51 20HH001RMX     | Notebook    | [ab38c51298](https://bsd-hardware.info/?probe=ab38c51298) | Jan 22, 2023 |
| Lenovo        | IdeaPad 110-14AST 80TQ      | Notebook    | [8ae819f673](https://bsd-hardware.info/?probe=8ae819f673) | Jan 21, 2023 |
| Lenovo        | ThinkPad T61 64644YG        | Notebook    | [3497ee2fcc](https://bsd-hardware.info/?probe=3497ee2fcc) | Jan 21, 2023 |
| Dell          | 0K240Y A01                  | Desktop     | [d9f16ef94b](https://bsd-hardware.info/?probe=d9f16ef94b) | Jan 18, 2023 |
| Lenovo        | B40-70 80F30005BR           | Notebook    | [17333d88cf](https://bsd-hardware.info/?probe=17333d88cf) | Jan 17, 2023 |
| Gigabyte      | H270M-DS3H-CF               | Desktop     | [d0e2e85346](https://bsd-hardware.info/?probe=d0e2e85346) | Jan 17, 2023 |
| HP            | Pavilion dv6                | Notebook    | [9d87e4009a](https://bsd-hardware.info/?probe=9d87e4009a) | Jan 16, 2023 |
| HP            | ZBook 15 G4                 | Notebook    | [e98d329586](https://bsd-hardware.info/?probe=e98d329586) | Jan 15, 2023 |
| HP            | ZBook 15 G4                 | Notebook    | [86875f01c2](https://bsd-hardware.info/?probe=86875f01c2) | Jan 15, 2023 |
| HP            | Pavilion dv6                | Notebook    | [e42082b1c1](https://bsd-hardware.info/?probe=e42082b1c1) | Jan 15, 2023 |
| Lenovo        | ThinkPad P15v Gen 2i 21A... | Notebook    | [035f9afc5d](https://bsd-hardware.info/?probe=035f9afc5d) | Jan 14, 2023 |
| Lenovo        | ThinkPad P15v Gen 2i 21A... | Notebook    | [9ded9cc6ec](https://bsd-hardware.info/?probe=9ded9cc6ec) | Jan 14, 2023 |
| HP            | Pavilion g6                 | Notebook    | [ceb79702f2](https://bsd-hardware.info/?probe=ceb79702f2) | Jan 13, 2023 |
| Razer         | Blade Stealth               | Notebook    | [2464314a65](https://bsd-hardware.info/?probe=2464314a65) | Jan 11, 2023 |
| Gigabyte      | G1.Sniper A88X-CF           | Desktop     | [2372c973c8](https://bsd-hardware.info/?probe=2372c973c8) | Jan 11, 2023 |
| HP            | 2000                        | Notebook    | [7f29899321](https://bsd-hardware.info/?probe=7f29899321) | Jan 09, 2023 |
| Lenovo        | ThinkPad T400 2764CTO       | Notebook    | [26f8459193](https://bsd-hardware.info/?probe=26f8459193) | Jan 06, 2023 |
| Dell          | 0K240Y A02                  | Desktop     | [379b59f079](https://bsd-hardware.info/?probe=379b59f079) | Jan 05, 2023 |
| Lenovo        | ThinkPad T61 64644YG        | Notebook    | [0657433463](https://bsd-hardware.info/?probe=0657433463) | Jan 03, 2023 |
| Apple         | MacBookAir5,1               | Notebook    | [0d398d5c59](https://bsd-hardware.info/?probe=0d398d5c59) | Dec 27, 2022 |
| Gigabyte      | X399 AORUS Gaming 7         | Desktop     | [1769da5143](https://bsd-hardware.info/?probe=1769da5143) | Dec 25, 2022 |
| Sony          | VPCSB11FX                   | Notebook    | [966183e570](https://bsd-hardware.info/?probe=966183e570) | Dec 23, 2022 |
| Acer          | Aspire ES1-533              | Notebook    | [570b96d0f7](https://bsd-hardware.info/?probe=570b96d0f7) | Dec 23, 2022 |
| Dell          | Inspiron 15-3552            | Notebook    | [eea4262af2](https://bsd-hardware.info/?probe=eea4262af2) | Dec 22, 2022 |
| Dell          | Inspiron 15-3552            | Notebook    | [cae00eb4d6](https://bsd-hardware.info/?probe=cae00eb4d6) | Dec 22, 2022 |
| Dell          | 0UW457 A03                  | Desktop     | [47b66a0d86](https://bsd-hardware.info/?probe=47b66a0d86) | Dec 21, 2022 |
| Gigabyte      | H81M-DS2                    | Desktop     | [29ad5ee336](https://bsd-hardware.info/?probe=29ad5ee336) | Dec 19, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [d19db2828c](https://bsd-hardware.info/?probe=d19db2828c) | Dec 16, 2022 |
| Lenovo        | G510 20238                  | Notebook    | [e5c4d51eab](https://bsd-hardware.info/?probe=e5c4d51eab) | Dec 15, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [bc15367e9f](https://bsd-hardware.info/?probe=bc15367e9f) | Dec 14, 2022 |
| HP            | Pavilion dv4                | Notebook    | [ee94a86a43](https://bsd-hardware.info/?probe=ee94a86a43) | Dec 12, 2022 |
| Apple         | MacBook3,1                  | Notebook    | [7aef0a996b](https://bsd-hardware.info/?probe=7aef0a996b) | Dec 10, 2022 |
| HP            | 2000                        | Notebook    | [5414b7c943](https://bsd-hardware.info/?probe=5414b7c943) | Dec 09, 2022 |
| HP            | 3397                        | Desktop     | [bc9e5c3ab7](https://bsd-hardware.info/?probe=bc9e5c3ab7) | Dec 09, 2022 |
| Pegatron      | 2A72h                       | Desktop     | [87e76fd095](https://bsd-hardware.info/?probe=87e76fd095) | Dec 09, 2022 |
| HP            | 245 G6                      | Notebook    | [49ce6aa725](https://bsd-hardware.info/?probe=49ce6aa725) | Dec 07, 2022 |
| ASUSTek       | CM1530                      | Desktop     | [902c77b5dc](https://bsd-hardware.info/?probe=902c77b5dc) | Dec 06, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [5441995e7b](https://bsd-hardware.info/?probe=5441995e7b) | Dec 05, 2022 |
| Gigabyte      | M68MT-S2P                   | Desktop     | [2fe00838c3](https://bsd-hardware.info/?probe=2fe00838c3) | Dec 05, 2022 |
| Gigabyte      | M68MT-S2P                   | Desktop     | [71f95dafb4](https://bsd-hardware.info/?probe=71f95dafb4) | Dec 05, 2022 |
| HASEE Comp... | N95XKP6                     | Notebook    | [0bc2996a6d](https://bsd-hardware.info/?probe=0bc2996a6d) | Dec 02, 2022 |
| ASUSTek       | PRIME H310T2 R2.0           | All in one  | [d1cc7c07e0](https://bsd-hardware.info/?probe=d1cc7c07e0) | Dec 02, 2022 |
| Dell          | Latitude 5590               | Notebook    | [0a17f04eba](https://bsd-hardware.info/?probe=0a17f04eba) | Dec 02, 2022 |
| Intel         | X99                         | Desktop     | [c21a466fc1](https://bsd-hardware.info/?probe=c21a466fc1) | Dec 01, 2022 |
| Dell          | Inspiron 3442               | Notebook    | [529cbab9aa](https://bsd-hardware.info/?probe=529cbab9aa) | Dec 01, 2022 |
| Acidanther... | MacBookPro15,1              | Notebook    | [57c3a4005a](https://bsd-hardware.info/?probe=57c3a4005a) | Dec 01, 2022 |
| GPD           | P3 MAX                      | Notebook    | [4a467c9616](https://bsd-hardware.info/?probe=4a467c9616) | Nov 30, 2022 |
| QIYIDA        | X99-H9 V2.0                 | Desktop     | [43163b0170](https://bsd-hardware.info/?probe=43163b0170) | Nov 28, 2022 |
| QIYIDA        | X99-H9 V2.0                 | Desktop     | [d00aa0021e](https://bsd-hardware.info/?probe=d00aa0021e) | Nov 28, 2022 |
| Lenovo        | ThinkPad T460 20FMS0XL23    | Notebook    | [bc7585ec56](https://bsd-hardware.info/?probe=bc7585ec56) | Nov 28, 2022 |
| Toshiba       | TECRA Z40-C-12Z             | Notebook    | [149e5c3de3](https://bsd-hardware.info/?probe=149e5c3de3) | Nov 28, 2022 |
| ASUSTek       | PRIME Z390M-PLUS            | Desktop     | [7329e04c22](https://bsd-hardware.info/?probe=7329e04c22) | Nov 27, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [3541df7dd2](https://bsd-hardware.info/?probe=3541df7dd2) | Nov 27, 2022 |
| Dell          | 09M8Y8 A02                  | Desktop     | [2299b7c270](https://bsd-hardware.info/?probe=2299b7c270) | Nov 27, 2022 |
| ASRock        | N68-S                       | Desktop     | [3813c8856e](https://bsd-hardware.info/?probe=3813c8856e) | Nov 27, 2022 |
| Dell          | Inspiron 5558               | Notebook    | [10bece0518](https://bsd-hardware.info/?probe=10bece0518) | Nov 27, 2022 |
| Acer          | Aspire 5738                 | Notebook    | [067e8e4d58](https://bsd-hardware.info/?probe=067e8e4d58) | Nov 26, 2022 |
| Dell          | 0M017G A00                  | Desktop     | [3acaad9a7d](https://bsd-hardware.info/?probe=3acaad9a7d) | Nov 26, 2022 |
| HP            | 3048h                       | Desktop     | [3f43816a5d](https://bsd-hardware.info/?probe=3f43816a5d) | Nov 25, 2022 |
| Lenovo        | ThinkStation S30 0569A93    | Desktop     | [dd545fb588](https://bsd-hardware.info/?probe=dd545fb588) | Nov 25, 2022 |
| Pegatron      | IPM41-D3                    | Desktop     | [898f645e32](https://bsd-hardware.info/?probe=898f645e32) | Nov 25, 2022 |
| MSI           | Z170A GAMING M5             | Desktop     | [5740972ddc](https://bsd-hardware.info/?probe=5740972ddc) | Nov 25, 2022 |
| Dell          | 009Y81 A01                  | All in one  | [75132e6886](https://bsd-hardware.info/?probe=75132e6886) | Nov 25, 2022 |
| ASUSTek       | K55VD                       | Notebook    | [6fa29c4e4d](https://bsd-hardware.info/?probe=6fa29c4e4d) | Nov 24, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3c11fc31b2](https://bsd-hardware.info/?probe=3c11fc31b2) | Nov 24, 2022 |
| MSI           | A320M-A PRO                 | Desktop     | [fc71b97d90](https://bsd-hardware.info/?probe=fc71b97d90) | Nov 24, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [e32a104392](https://bsd-hardware.info/?probe=e32a104392) | Nov 24, 2022 |
| Gigabyte      | E2500N                      | Desktop     | [64b937b551](https://bsd-hardware.info/?probe=64b937b551) | Nov 23, 2022 |
| Gigabyte      | G31M-S2L                    | Desktop     | [d376385d80](https://bsd-hardware.info/?probe=d376385d80) | Nov 23, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [a4d92a3b73](https://bsd-hardware.info/?probe=a4d92a3b73) | Nov 23, 2022 |
| ASUSTek       | A55BM-K                     | Desktop     | [dc487b5779](https://bsd-hardware.info/?probe=dc487b5779) | Nov 23, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [9701222998](https://bsd-hardware.info/?probe=9701222998) | Nov 23, 2022 |
| Intel         | H61                         | Desktop     | [689ebf0e57](https://bsd-hardware.info/?probe=689ebf0e57) | Nov 22, 2022 |
| Gigabyte      | P61-USB3-B3                 | Desktop     | [1ec1683acd](https://bsd-hardware.info/?probe=1ec1683acd) | Nov 21, 2022 |
| Gigabyte      | P61-USB3-B3                 | Desktop     | [5f442f0c65](https://bsd-hardware.info/?probe=5f442f0c65) | Nov 21, 2022 |
| Gigabyte      | H61M-S1                     | Desktop     | [2b851dbbc1](https://bsd-hardware.info/?probe=2b851dbbc1) | Nov 21, 2022 |
| Gigabyte      | 970A-D3P                    | Desktop     | [cced487ec5](https://bsd-hardware.info/?probe=cced487ec5) | Nov 21, 2022 |
| Gigabyte      | 970A-D3P                    | Desktop     | [c28a22ecb5](https://bsd-hardware.info/?probe=c28a22ecb5) | Nov 21, 2022 |
| ASUSTek       | P5KPL-VM-TWPC               | Desktop     | [6a5ff282a7](https://bsd-hardware.info/?probe=6a5ff282a7) | Nov 21, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [92eab8d065](https://bsd-hardware.info/?probe=92eab8d065) | Nov 19, 2022 |
| Dell          | Latitude D630               | Notebook    | [1c600cc283](https://bsd-hardware.info/?probe=1c600cc283) | Nov 18, 2022 |
| Acer          | Aspire 5251                 | Notebook    | [046bc722cb](https://bsd-hardware.info/?probe=046bc722cb) | Nov 16, 2022 |
| HP            | 1998                        | Desktop     | [9239fe7437](https://bsd-hardware.info/?probe=9239fe7437) | Nov 15, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [7650f7619d](https://bsd-hardware.info/?probe=7650f7619d) | Nov 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3448A... | Notebook    | [1d2be7d46a](https://bsd-hardware.info/?probe=1d2be7d46a) | Nov 13, 2022 |
| ASUSTek       | P5E-VM SE                   | Desktop     | [910dc6412e](https://bsd-hardware.info/?probe=910dc6412e) | Nov 10, 2022 |
| Dell          | Inspiron 3421               | Notebook    | [5c37012f33](https://bsd-hardware.info/?probe=5c37012f33) | Nov 10, 2022 |
| MSI           | Z370I GAMING PRO CARBON ... | Desktop     | [dd9f7679b5](https://bsd-hardware.info/?probe=dd9f7679b5) | Nov 09, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [2294352c5a](https://bsd-hardware.info/?probe=2294352c5a) | Nov 08, 2022 |
| Dell          | 0F428D A00                  | Desktop     | [0a9ca655d3](https://bsd-hardware.info/?probe=0a9ca655d3) | Nov 08, 2022 |
| ASUSTek       | Z97-A                       | Desktop     | [6a2b1c8105](https://bsd-hardware.info/?probe=6a2b1c8105) | Nov 05, 2022 |
| Gigabyte      | H270M-DS3H-CF               | Desktop     | [5784d8bed6](https://bsd-hardware.info/?probe=5784d8bed6) | Nov 04, 2022 |
| HP            | 8053                        | Desktop     | [92583639f6](https://bsd-hardware.info/?probe=92583639f6) | Nov 02, 2022 |
| HP            | Pavilion g6                 | Notebook    | [c4e84b8104](https://bsd-hardware.info/?probe=c4e84b8104) | Oct 30, 2022 |
| Lenovo        | 3106 SDK0J40705 WIN 3425... | Desktop     | [d20bfb6d64](https://bsd-hardware.info/?probe=d20bfb6d64) | Oct 30, 2022 |
| Lenovo        | ThinkPad W530 24491A0       | Notebook    | [4a700f43f8](https://bsd-hardware.info/?probe=4a700f43f8) | Oct 30, 2022 |
| HP            | 843B                        | Desktop     | [d7d572f9ad](https://bsd-hardware.info/?probe=d7d572f9ad) | Oct 29, 2022 |
| Samsung       | Q430/Q530                   | Notebook    | [fb98c8c797](https://bsd-hardware.info/?probe=fb98c8c797) | Oct 29, 2022 |
| Intel         | NUC8BEB J72688-306          | Mini pc     | [17f444775b](https://bsd-hardware.info/?probe=17f444775b) | Oct 28, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [015f0a0a6d](https://bsd-hardware.info/?probe=015f0a0a6d) | Oct 27, 2022 |
| Samsung       | Q430/Q530                   | Notebook    | [4965215a13](https://bsd-hardware.info/?probe=4965215a13) | Oct 25, 2022 |
| HP            | 843B                        | Desktop     | [9ea2590610](https://bsd-hardware.info/?probe=9ea2590610) | Oct 23, 2022 |
| Google        | Edgar                       | Notebook    | [318a750368](https://bsd-hardware.info/?probe=318a750368) | Oct 22, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [8a4e3767e9](https://bsd-hardware.info/?probe=8a4e3767e9) | Oct 22, 2022 |
| MSI           | B450M PRO-VDH PLUS          | Desktop     | [54e4202bc7](https://bsd-hardware.info/?probe=54e4202bc7) | Oct 21, 2022 |
| MSI           | B450M PRO-VDH PLUS          | Desktop     | [c6ee09790d](https://bsd-hardware.info/?probe=c6ee09790d) | Oct 20, 2022 |
| MSI           | PS63 Modern 8M              | Notebook    | [949e472db5](https://bsd-hardware.info/?probe=949e472db5) | Oct 19, 2022 |
| ASUSTek       | N3050I-C                    | Desktop     | [4a83b0953e](https://bsd-hardware.info/?probe=4a83b0953e) | Oct 18, 2022 |
| Lenovo        | ThinkPad T61 765912G        | Notebook    | [50c3c93790](https://bsd-hardware.info/?probe=50c3c93790) | Oct 17, 2022 |
| HP            | SpectreXT Pro 13-b000 PC    | Notebook    | [f45ea42873](https://bsd-hardware.info/?probe=f45ea42873) | Oct 16, 2022 |
| HP            | 8169                        | Desktop     | [86b1fbf917](https://bsd-hardware.info/?probe=86b1fbf917) | Oct 15, 2022 |
| HP            | Laptop 15q-bu0xx            | Notebook    | [99c01654a2](https://bsd-hardware.info/?probe=99c01654a2) | Oct 15, 2022 |
| Lenovo        | ThinkCentre M57p 6078AJ6    | Desktop     | [a808a7360d](https://bsd-hardware.info/?probe=a808a7360d) | Oct 14, 2022 |
| ASUSTek       | H110M-PLUS                  | Desktop     | [ba30f2772b](https://bsd-hardware.info/?probe=ba30f2772b) | Oct 12, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [dec7108b53](https://bsd-hardware.info/?probe=dec7108b53) | Oct 11, 2022 |
| Acer          | Aspire 5336                 | Notebook    | [127ddc93fb](https://bsd-hardware.info/?probe=127ddc93fb) | Oct 10, 2022 |
| Acer          | Aspire E5-722G              | Notebook    | [7a4eb565fe](https://bsd-hardware.info/?probe=7a4eb565fe) | Oct 10, 2022 |
| Dell          | Latitude E6420              | Notebook    | [48c26d2a17](https://bsd-hardware.info/?probe=48c26d2a17) | Oct 10, 2022 |
| Fujitsu       | LIFEBOOK U904               | Notebook    | [3a86733538](https://bsd-hardware.info/?probe=3a86733538) | Oct 09, 2022 |
| HP            | 86FC MVB                    | Desktop     | [56453b00c8](https://bsd-hardware.info/?probe=56453b00c8) | Oct 08, 2022 |
| HP            | 86FC MVB                    | Desktop     | [c542b16d75](https://bsd-hardware.info/?probe=c542b16d75) | Oct 08, 2022 |
| Apple         | Mac-7BA5B2794B2CDB12 Mac... | Mini pc     | [b164bfcf33](https://bsd-hardware.info/?probe=b164bfcf33) | Oct 06, 2022 |
| Acer          | Aspire F5-573               | Notebook    | [9c092c9cd7](https://bsd-hardware.info/?probe=9c092c9cd7) | Oct 05, 2022 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [a49ac2701d](https://bsd-hardware.info/?probe=a49ac2701d) | Oct 02, 2022 |
| HP            | ProBook 4540s               | Notebook    | [df94757940](https://bsd-hardware.info/?probe=df94757940) | Oct 02, 2022 |
| Lenovo        | ThinkPad E15 2ORES4XJ00     | Notebook    | [323a95e6a9](https://bsd-hardware.info/?probe=323a95e6a9) | Oct 01, 2022 |
| Dell          | 0T10XW A01                  | Desktop     | [c2ff0bc0b9](https://bsd-hardware.info/?probe=c2ff0bc0b9) | Sep 30, 2022 |
| Kraftway      | KW10T                       | Notebook    | [db27da2e88](https://bsd-hardware.info/?probe=db27da2e88) | Sep 29, 2022 |
| Lenovo        | Legion Y540-17IRH 81Q4      | Notebook    | [62b9a56103](https://bsd-hardware.info/?probe=62b9a56103) | Sep 29, 2022 |
| ASRock        | A320M-HD                    | Desktop     | [6418fd0b23](https://bsd-hardware.info/?probe=6418fd0b23) | Sep 28, 2022 |
| Lenovo        | ThinkPad X61 Tablet 7763... | Notebook    | [1f37ebf2bb](https://bsd-hardware.info/?probe=1f37ebf2bb) | Sep 28, 2022 |
| Lenovo        | ThinkPad X250 20CLS1WP01    | Notebook    | [1b75ee6295](https://bsd-hardware.info/?probe=1b75ee6295) | Sep 19, 2022 |
| Dell          | Precision 7710              | Notebook    | [4c4937d824](https://bsd-hardware.info/?probe=4c4937d824) | Sep 18, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [da4bd87fee](https://bsd-hardware.info/?probe=da4bd87fee) | Sep 17, 2022 |
| Lenovo        | ThinkPad X270 20HMS2LL00    | Notebook    | [12f6a8866f](https://bsd-hardware.info/?probe=12f6a8866f) | Sep 14, 2022 |
| Apple         | Mac-7BA5B2D9E42DDD94        | Desktop     | [d2e169b8ad](https://bsd-hardware.info/?probe=d2e169b8ad) | Sep 13, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [79503c0635](https://bsd-hardware.info/?probe=79503c0635) | Sep 10, 2022 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [7c9c1db9d7](https://bsd-hardware.info/?probe=7c9c1db9d7) | Sep 10, 2022 |
| Apple         | MacBook5,2                  | Notebook    | [9c7a64970c](https://bsd-hardware.info/?probe=9c7a64970c) | Sep 10, 2022 |
| Lenovo        | ThinkPad T440 20B7S2LT00    | Notebook    | [5104875f94](https://bsd-hardware.info/?probe=5104875f94) | Sep 06, 2022 |
| Pegatron      | IPM41-D3                    | Desktop     | [2d3a5a5260](https://bsd-hardware.info/?probe=2d3a5a5260) | Sep 06, 2022 |
| Dell          | 0Y7WYT A00                  | Desktop     | [2870b9e4c7](https://bsd-hardware.info/?probe=2870b9e4c7) | Sep 05, 2022 |
| HP            | 8719                        | Desktop     | [f3132fc160](https://bsd-hardware.info/?probe=f3132fc160) | Sep 05, 2022 |
| Apple         | MacBookPro5,1               | Notebook    | [f4d84edb3b](https://bsd-hardware.info/?probe=f4d84edb3b) | Sep 04, 2022 |
| ASUSTek       | H81M-A                      | Desktop     | [11ac5a7932](https://bsd-hardware.info/?probe=11ac5a7932) | Sep 02, 2022 |
| Dell          | Latitude E5550              | Notebook    | [867e56fb52](https://bsd-hardware.info/?probe=867e56fb52) | Sep 01, 2022 |
| Dell          | Precision 7710              | Notebook    | [339099bbf0](https://bsd-hardware.info/?probe=339099bbf0) | Sep 01, 2022 |
| ASRock        | ConRoeXFire-eSATA2          | Desktop     | [caf005ed95](https://bsd-hardware.info/?probe=caf005ed95) | Sep 01, 2022 |
| Dell          | Precision 5540              | Notebook    | [0c5089634d](https://bsd-hardware.info/?probe=0c5089634d) | Aug 30, 2022 |
| Dell          | Precision 5540              | Notebook    | [afb80a84fb](https://bsd-hardware.info/?probe=afb80a84fb) | Aug 30, 2022 |
| Lenovo        | ThinkPad T420 4178A72       | Notebook    | [18a105546b](https://bsd-hardware.info/?probe=18a105546b) | Aug 29, 2022 |
| Lenovo        | ThinkPad T420 4178A72       | Notebook    | [1433351032](https://bsd-hardware.info/?probe=1433351032) | Aug 29, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [079adb24f8](https://bsd-hardware.info/?probe=079adb24f8) | Aug 28, 2022 |
| Toshiba       | Satellite S55t-B            | Notebook    | [df9971d3aa](https://bsd-hardware.info/?probe=df9971d3aa) | Aug 27, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [2c7586b0ed](https://bsd-hardware.info/?probe=2c7586b0ed) | Aug 25, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [17f4ac1979](https://bsd-hardware.info/?probe=17f4ac1979) | Aug 23, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [5ea9441653](https://bsd-hardware.info/?probe=5ea9441653) | Aug 19, 2022 |
| Dell          | Studio 1537                 | Notebook    | [a185649600](https://bsd-hardware.info/?probe=a185649600) | Aug 17, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [f8c10bf25a](https://bsd-hardware.info/?probe=f8c10bf25a) | Aug 15, 2022 |
| Intel         | NUC8BEB J72688-304          | Mini pc     | [3de3724488](https://bsd-hardware.info/?probe=3de3724488) | Aug 12, 2022 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [a45977c76b](https://bsd-hardware.info/?probe=a45977c76b) | Aug 10, 2022 |
| ASRock        | Z370 Pro4                   | Desktop     | [038c5f8763](https://bsd-hardware.info/?probe=038c5f8763) | Aug 10, 2022 |
| TUXEDO        | Pulse 14 Gen1               | Notebook    | [5edf8a1bef](https://bsd-hardware.info/?probe=5edf8a1bef) | Aug 09, 2022 |
| ASUSTek       | F6A                         | Notebook    | [6626d18284](https://bsd-hardware.info/?probe=6626d18284) | Aug 08, 2022 |
| HP            | ProBook 4540s               | Notebook    | [0a7891d53f](https://bsd-hardware.info/?probe=0a7891d53f) | Aug 06, 2022 |
| eMachines     | eME728                      | Notebook    | [96d745589c](https://bsd-hardware.info/?probe=96d745589c) | Aug 06, 2022 |
| ASUSTek       | P5QL-ASUS-SE                | Desktop     | [50a0d392e7](https://bsd-hardware.info/?probe=50a0d392e7) | Aug 06, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [af241a5384](https://bsd-hardware.info/?probe=af241a5384) | Aug 06, 2022 |
| ASUSTek       | K30AM-J                     | Desktop     | [470ced8f30](https://bsd-hardware.info/?probe=470ced8f30) | Aug 05, 2022 |
| ASUSTek       | P5GC-MX/CKD/SI              | Desktop     | [d61693dffb](https://bsd-hardware.info/?probe=d61693dffb) | Aug 05, 2022 |
| ASUSTek       | K30AM-J                     | Desktop     | [e032724bc2](https://bsd-hardware.info/?probe=e032724bc2) | Aug 05, 2022 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [850198c512](https://bsd-hardware.info/?probe=850198c512) | Aug 05, 2022 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [cddf42b097](https://bsd-hardware.info/?probe=cddf42b097) | Aug 05, 2022 |
| HP            | 1497                        | Desktop     | [c6f6ddf728](https://bsd-hardware.info/?probe=c6f6ddf728) | Aug 04, 2022 |
| Acer          | Aspire 5930                 | Notebook    | [4bd9ec4253](https://bsd-hardware.info/?probe=4bd9ec4253) | Aug 02, 2022 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [ad56307789](https://bsd-hardware.info/?probe=ad56307789) | Aug 01, 2022 |
| Lenovo        | ThinkPad T61 7661GY9        | Notebook    | [7ab5339eee](https://bsd-hardware.info/?probe=7ab5339eee) | Jul 30, 2022 |
| HP            | ProBook 430 G4              | Notebook    | [2a9d4e9b0b](https://bsd-hardware.info/?probe=2a9d4e9b0b) | Jul 30, 2022 |
| Apple         | MacBook6,1                  | Notebook    | [55ab4bc8d6](https://bsd-hardware.info/?probe=55ab4bc8d6) | Jul 29, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [6d5bfb02a0](https://bsd-hardware.info/?probe=6d5bfb02a0) | Jul 28, 2022 |
| Dell          | Latitude E7440              | Notebook    | [03497b7b2a](https://bsd-hardware.info/?probe=03497b7b2a) | Jul 27, 2022 |
| Gigabyte      | AB350N-Gaming WIFI-CF       | Desktop     | [f50526a6d6](https://bsd-hardware.info/?probe=f50526a6d6) | Jul 27, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [511d057c70](https://bsd-hardware.info/?probe=511d057c70) | Jul 27, 2022 |
| MAXSUN        | MS-H110D4L FS M.2           | Desktop     | [39d06b12fd](https://bsd-hardware.info/?probe=39d06b12fd) | Jul 25, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [e2a5a65135](https://bsd-hardware.info/?probe=e2a5a65135) | Jul 23, 2022 |
| HP            | ProBook 4730s               | Notebook    | [e70725dd32](https://bsd-hardware.info/?probe=e70725dd32) | Jul 23, 2022 |
| Lenovo        | ThinkPad L450 20DSS1S402    | Notebook    | [b779706b7a](https://bsd-hardware.info/?probe=b779706b7a) | Jul 21, 2022 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [a96e41f99e](https://bsd-hardware.info/?probe=a96e41f99e) | Jul 20, 2022 |
| Lenovo        | ThinkPad L412 0585AD9       | Notebook    | [cba0fc2340](https://bsd-hardware.info/?probe=cba0fc2340) | Jul 20, 2022 |
| ASUSTek       | P8B WS                      | Desktop     | [dd7f8123d2](https://bsd-hardware.info/?probe=dd7f8123d2) | Jul 19, 2022 |
| Lenovo        | ThinkPad X61s 76693KG       | Notebook    | [445446cc28](https://bsd-hardware.info/?probe=445446cc28) | Jul 18, 2022 |
| HP            | OMEN by Laptop              | Notebook    | [25e43be096](https://bsd-hardware.info/?probe=25e43be096) | Jul 17, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [a80b1c4f3c](https://bsd-hardware.info/?probe=a80b1c4f3c) | Jul 17, 2022 |
| HP            | 8055                        | Desktop     | [269b4f3210](https://bsd-hardware.info/?probe=269b4f3210) | Jul 17, 2022 |
| Apple         | Mac-F2218EA9                | All in one  | [64b17b1b35](https://bsd-hardware.info/?probe=64b17b1b35) | Jul 17, 2022 |
| Apple         | Mac-F2218EA9                | All in one  | [3c7cfd537b](https://bsd-hardware.info/?probe=3c7cfd537b) | Jul 17, 2022 |
| Shuttle       | FH170                       | Desktop     | [a156048964](https://bsd-hardware.info/?probe=a156048964) | Jul 16, 2022 |
| Shuttle       | FH170                       | Desktop     | [81b62c2839](https://bsd-hardware.info/?probe=81b62c2839) | Jul 16, 2022 |
| Dell          | Inspiron MP061              | Notebook    | [56a7002cc5](https://bsd-hardware.info/?probe=56a7002cc5) | Jul 16, 2022 |
| HP            | 1998                        | Desktop     | [e4fda48283](https://bsd-hardware.info/?probe=e4fda48283) | Jul 15, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [db03ba8975](https://bsd-hardware.info/?probe=db03ba8975) | Jul 14, 2022 |
| Dell          | Latitude E5450              | Notebook    | [5f1183ab0b](https://bsd-hardware.info/?probe=5f1183ab0b) | Jul 14, 2022 |
| Dell          | Latitude E5450              | Notebook    | [1080ed5654](https://bsd-hardware.info/?probe=1080ed5654) | Jul 14, 2022 |
| ASUSTek       | Maximus IX HERO             | Desktop     | [ea2f21a15f](https://bsd-hardware.info/?probe=ea2f21a15f) | Jul 12, 2022 |
| MSI           | GF63 Thin 10SC              | Notebook    | [139855ab73](https://bsd-hardware.info/?probe=139855ab73) | Jul 12, 2022 |
| Acer          | Aspire E1-522               | Notebook    | [d680e0d05d](https://bsd-hardware.info/?probe=d680e0d05d) | Jul 10, 2022 |
| Acer          | Aspire E5-571G              | Notebook    | [56fae2295e](https://bsd-hardware.info/?probe=56fae2295e) | Jul 08, 2022 |
| ASUSTek       | Maximus IX HERO             | Desktop     | [81668557c6](https://bsd-hardware.info/?probe=81668557c6) | Jul 08, 2022 |
| Fujitsu       | LIFEBOOK A555               | Notebook    | [1062220932](https://bsd-hardware.info/?probe=1062220932) | Jul 07, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [bbe1d21883](https://bsd-hardware.info/?probe=bbe1d21883) | Jul 07, 2022 |
| Pegatron      | IPM41-D3                    | Desktop     | [8b2af1b843](https://bsd-hardware.info/?probe=8b2af1b843) | Jul 06, 2022 |
| Lenovo        | NO DPK                      | Desktop     | [2c79a92fc4](https://bsd-hardware.info/?probe=2c79a92fc4) | Jul 06, 2022 |
| Dell          | 0F9NPY A02                  | Server      | [f1bb207022](https://bsd-hardware.info/?probe=f1bb207022) | Jul 06, 2022 |
| Dell          | 0F9NPY A02                  | Server      | [919d608fda](https://bsd-hardware.info/?probe=919d608fda) | Jul 05, 2022 |
| Pegatron      | IPM41-D3                    | Desktop     | [1cd93cd5d3](https://bsd-hardware.info/?probe=1cd93cd5d3) | Jul 04, 2022 |
| Intel         | NUC8i5BESB K75953-303       | Mini pc     | [b0a9749159](https://bsd-hardware.info/?probe=b0a9749159) | Jul 01, 2022 |
| Biostar       | G41D3C                      | Desktop     | [118bd083bf](https://bsd-hardware.info/?probe=118bd083bf) | Jul 01, 2022 |
| Dell          | Inspiron 15-3552            | Notebook    | [8cdc3bd7ab](https://bsd-hardware.info/?probe=8cdc3bd7ab) | Jul 01, 2022 |
| Lenovo        | ThinkPad T430s 2356CV6      | Notebook    | [20df9d5df2](https://bsd-hardware.info/?probe=20df9d5df2) | Jun 29, 2022 |
| Toshiba       | PORTEGE R700                | Notebook    | [d9c359c2ab](https://bsd-hardware.info/?probe=d9c359c2ab) | Jun 28, 2022 |
| Lenovo        | ThinkPad T460 20FN004CUK    | Notebook    | [18b5875c95](https://bsd-hardware.info/?probe=18b5875c95) | Jun 26, 2022 |
| Lenovo        | ThinkPad T410 2522CS7       | Notebook    | [a1561dacb2](https://bsd-hardware.info/?probe=a1561dacb2) | Jun 26, 2022 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [4d4993a732](https://bsd-hardware.info/?probe=4d4993a732) | Jun 24, 2022 |
| ALLEGIANCE... | X79 V3.3F                   | Desktop     | [190560a4f4](https://bsd-hardware.info/?probe=190560a4f4) | Jun 23, 2022 |
| ASUSTek       | P8B75-M LX PLUS             | Desktop     | [346bc6f0ae](https://bsd-hardware.info/?probe=346bc6f0ae) | Jun 20, 2022 |
| Apple         | MacBook6,1                  | Notebook    | [a6d3cf9a30](https://bsd-hardware.info/?probe=a6d3cf9a30) | Jun 20, 2022 |
| Lenovo        | 300e 81FY                   | Convertible | [eb136e5d7e](https://bsd-hardware.info/?probe=eb136e5d7e) | Jun 20, 2022 |
| Acer          | Aspire A315-34              | Notebook    | [90927fa85a](https://bsd-hardware.info/?probe=90927fa85a) | Jun 20, 2022 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [a094c1c53b](https://bsd-hardware.info/?probe=a094c1c53b) | Jun 20, 2022 |
| HP            | Unknown                     | Notebook    | [11ef8f9a92](https://bsd-hardware.info/?probe=11ef8f9a92) | Jun 19, 2022 |
| HP            | Compaq tc4400 (EN357UT#A... | Notebook    | [f4e4e3826b](https://bsd-hardware.info/?probe=f4e4e3826b) | Jun 19, 2022 |
| HP            | 304Bh                       | Desktop     | [8a3151b3cd](https://bsd-hardware.info/?probe=8a3151b3cd) | Jun 16, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [aaf7ed146a](https://bsd-hardware.info/?probe=aaf7ed146a) | Jun 16, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [6116216a6d](https://bsd-hardware.info/?probe=6116216a6d) | Jun 15, 2022 |
| Alienware     | M18xR2                      | Notebook    | [6d55881f6a](https://bsd-hardware.info/?probe=6d55881f6a) | Jun 15, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [8ba77d7208](https://bsd-hardware.info/?probe=8ba77d7208) | Jun 13, 2022 |
| Lenovo        | G40-30 80FY                 | Notebook    | [f478f5edc1](https://bsd-hardware.info/?probe=f478f5edc1) | Jun 13, 2022 |
| Lenovo        | ThinkPad X260 20F5S45W00    | Notebook    | [acfa5c94d5](https://bsd-hardware.info/?probe=acfa5c94d5) | Jun 12, 2022 |
| HP            | ProBook 4230s               | Notebook    | [8c853f8ca9](https://bsd-hardware.info/?probe=8c853f8ca9) | Jun 11, 2022 |
| Acer          | Aspire E5-571               | Notebook    | [4be2393c8d](https://bsd-hardware.info/?probe=4be2393c8d) | Jun 11, 2022 |
| Lenovo        | ThinkCentre XXXX Y          | Desktop     | [162bbe4eac](https://bsd-hardware.info/?probe=162bbe4eac) | Jun 10, 2022 |
| Apple         | Mac-F2218EA9                | All in one  | [d1a197ec53](https://bsd-hardware.info/?probe=d1a197ec53) | Jun 09, 2022 |
| ASUSTek       | TUF B360M-E GAMING          | Desktop     | [26375bae48](https://bsd-hardware.info/?probe=26375bae48) | Jun 08, 2022 |
| Acer          | EM61SM/EM61PM               | Desktop     | [3b8d6cb36e](https://bsd-hardware.info/?probe=3b8d6cb36e) | Jun 07, 2022 |
| Lenovo        | ThinkPad T420 4236MY0       | Notebook    | [94095d4c11](https://bsd-hardware.info/?probe=94095d4c11) | Jun 06, 2022 |
| Lenovo        | ThinkPad T440p 20AWS0DU0... | Notebook    | [8029eb2018](https://bsd-hardware.info/?probe=8029eb2018) | Jun 04, 2022 |
| HP            | Pavilion g4                 | Notebook    | [79d8ca2681](https://bsd-hardware.info/?probe=79d8ca2681) | Jun 04, 2022 |
| Lenovo        | ThinkPad X250 20CLS23500    | Notebook    | [6a8b44bc47](https://bsd-hardware.info/?probe=6a8b44bc47) | Jun 03, 2022 |
| Positivo      | POS-PIQ77CL POSITIVO        | Desktop     | [848361c724](https://bsd-hardware.info/?probe=848361c724) | May 31, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/helloSystem/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| helloSystem 0.7.0       | 447       | 25.46%  |
| helloSystem 0.8.1       | 366       | 20.84%  |
| helloSystem 0.8.0       | 254       | 14.46%  |
| helloSystem 0.5.0       | 245       | 13.95%  |
| helloSystem 0.4.0       | 190       | 10.82%  |
| helloSystem 0.6.0       | 138       | 7.86%   |
| helloSystem 0.8.2       | 67        | 3.82%   |
| helloSystem 0.3.0       | 25        | 1.42%   |
| helloSystem 0.9.0       | 18        | 1.03%   |
| helloSystem 13.1-p2     | 2         | 0.11%   |
| helloSystem 13.1        | 1         | 0.06%   |
| helloSystem 13.0-STABLE | 1         | 0.06%   |
| helloSystem 13.0-p11    | 1         | 0.06%   |
| helloSystem             | 1         | 0.06%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| helloSystem | 1627      | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 1625      | 99.88%  |
| arm64 | 2         | 0.12%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| helloDesktop | 1607      | 98.35%  |
| GNOME        | 10        | 0.61%   |
| KDE5         | 8         | 0.49%   |
| XFCE         | 4         | 0.24%   |
| Cinnamon     | 2         | 0.12%   |
| Window Maker | 1         | 0.06%   |
| JWM          | 1         | 0.06%   |
| IceWM        | 1         | 0.06%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 1627      | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SLiM    | 1621      | 99.39%  |
| SDDM    | 3         | 0.18%   |
| GDM     | 3         | 0.18%   |
| Console | 3         | 0.18%   |
| LightDM | 1         | 0.06%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 1218      | 72.63%  |
| fr_FR   | 94        | 5.61%   |
| en      | 92        | 5.49%   |
| Unknown | 38        | 2.27%   |
| de_DE   | 36        | 2.15%   |
| ru_RU   | 35        | 2.09%   |
| es_ES   | 33        | 1.97%   |
| fr      | 17        | 1.01%   |
| pt_BR   | 13        | 0.78%   |
| ru      | 12        | 0.72%   |
| it_IT   | 11        | 0.66%   |
| pt      | 9         | 0.54%   |
| pl_PL   | 9         | 0.54%   |
| es      | 9         | 0.54%   |
| C       | 9         | 0.54%   |
| de      | 7         | 0.42%   |
| zh_CN   | 5         | 0.3%    |
| nl_NL   | 4         | 0.24%   |
| jp_JP   | 4         | 0.24%   |
| it      | 3         | 0.18%   |
| zh_TW   | 2         | 0.12%   |
| tr_TR   | 2         | 0.12%   |
| pl      | 2         | 0.12%   |
| nl      | 2         | 0.12%   |
| ko_KR   | 2         | 0.12%   |
| en_GB   | 2         | 0.12%   |
| uk_UA   | 1         | 0.06%   |
| sv      | 1         | 0.06%   |
| pt_PT   | 1         | 0.06%   |
| ko      | 1         | 0.06%   |
| fi_FI   | 1         | 0.06%   |
| es_AR   | 1         | 0.06%   |
| en_UK   | 1         | 0.06%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 1525      | 93.22%  |
| BIOS | 111       | 6.78%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Computers | Percent |
|--------|-----------|---------|
| Zfs    | 1045      | 62.17%  |
| Cd9660 | 633       | 37.66%  |
| Ufs    | 3         | 0.18%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 1615      | 99.26%  |
| MBR  | 12        | 0.74%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 292       | 17.95%  |
| ASUSTek Computer    | 260       | 15.98%  |
| Hewlett-Packard     | 195       | 11.99%  |
| Dell                | 194       | 11.92%  |
| Gigabyte Technology | 113       | 6.95%   |
| Apple               | 72        | 4.43%   |
| Acer                | 65        | 4%      |
| ASRock              | 63        | 3.87%   |
| MSI                 | 55        | 3.38%   |
| Intel               | 48        | 2.95%   |
| Toshiba             | 26        | 1.6%    |
| Samsung Electronics | 22        | 1.35%   |
| Fujitsu             | 22        | 1.35%   |
| Sony                | 14        | 0.86%   |
| Unknown             | 14        | 0.86%   |
| Google              | 10        | 0.61%   |
| Biostar             | 10        | 0.61%   |
| Packard Bell        | 9         | 0.55%   |
| Pegatron            | 8         | 0.49%   |
| Acidanthera         | 7         | 0.43%   |
| LG Electronics      | 6         | 0.37%   |
| Foxconn             | 6         | 0.37%   |
| Panasonic           | 5         | 0.31%   |
| Medion              | 5         | 0.31%   |
| Fujitsu Siemens     | 5         | 0.31%   |
| TUXEDO              | 4         | 0.25%   |
| Timi                | 4         | 0.25%   |
| Notebook            | 4         | 0.25%   |
| AZW                 | 4         | 0.25%   |
| Shuttle             | 3         | 0.18%   |
| Itautec             | 3         | 0.18%   |
| Gateway             | 3         | 0.18%   |
| eMachines           | 3         | 0.18%   |
| T-bao               | 2         | 0.12%   |
| Supermicro          | 2         | 0.12%   |
| Star Labs           | 2         | 0.12%   |
| Razer               | 2         | 0.12%   |
| Positivo            | 2         | 0.12%   |
| Microsoft           | 2         | 0.12%   |
| MECHREVO S1 Series  | 2         | 0.12%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Unknown                        | 20        | 1.23%   |
| ASUS All Series                | 13        | 0.8%    |
| Apple iMac9,1                  | 7         | 0.43%   |
| HP EliteDesk 800 G2 DM 35W     | 6         | 0.37%   |
| Apple MacPro5,1                | 6         | 0.37%   |
| Apple MacBook4,1               | 6         | 0.37%   |
| HP Pavilion dv6                | 5         | 0.31%   |
| Dell OptiPlex 9020             | 5         | 0.31%   |
| Dell OptiPlex 3020             | 5         | 0.31%   |
| Dell Inspiron 3442             | 5         | 0.31%   |
| Apple MacBookPro9,2            | 5         | 0.31%   |
| MSI MS-7C37                    | 4         | 0.25%   |
| Intel H61                      | 4         | 0.25%   |
| HP Compaq Elite 8300 USDT      | 4         | 0.25%   |
| HP 2000                        | 4         | 0.25%   |
| Dell OptiPlex 755              | 4         | 0.25%   |
| Dell OptiPlex 7010             | 4         | 0.25%   |
| Dell Latitude E6420            | 4         | 0.25%   |
| Dell Latitude E5570            | 4         | 0.25%   |
| ASUS ROG STRIX B550-F GAMING   | 4         | 0.25%   |
| Apple MacBookAir5,1            | 4         | 0.25%   |
| Acer Aspire ES1-533            | 4         | 0.25%   |
| MSI MS-7B86                    | 3         | 0.18%   |
| Lenovo IdeaPad 110S-11IBR 80WG | 3         | 0.18%   |
| Intel H81                      | 3         | 0.18%   |
| HP Pavilion Notebook           | 3         | 0.18%   |
| HP Pavilion g6                 | 3         | 0.18%   |
| HP Notebook                    | 3         | 0.18%   |
| HP EliteDesk 800 G2 SFF        | 3         | 0.18%   |
| HP EliteBook 840 G3            | 3         | 0.18%   |
| HP Compaq Elite 8300 SFF       | 3         | 0.18%   |
| Gigabyte F2A88XM-D3H           | 3         | 0.18%   |
| Dell Precision Tower 5810      | 3         | 0.18%   |
| Dell Precision 7710            | 3         | 0.18%   |
| Dell OptiPlex 780              | 3         | 0.18%   |
| Dell OptiPlex 760              | 3         | 0.18%   |
| Dell Latitude E4310            | 3         | 0.18%   |
| Dell Latitude D630             | 3         | 0.18%   |
| Dell Latitude 7280             | 3         | 0.18%   |
| Dell Inspiron 7520             | 3         | 0.18%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 172       | 10.57%  |
| Dell Latitude           | 59        | 3.63%   |
| Dell OptiPlex           | 48        | 2.95%   |
| Dell Inspiron           | 45        | 2.77%   |
| Acer Aspire             | 45        | 2.77%   |
| HP Pavilion             | 36        | 2.21%   |
| Lenovo IdeaPad          | 33        | 2.03%   |
| ASUS PRIME              | 33        | 2.03%   |
| Lenovo ThinkCentre      | 31        | 1.91%   |
| ASUS ROG                | 26        | 1.6%    |
| HP Compaq               | 24        | 1.48%   |
| Dell Precision          | 20        | 1.23%   |
| Unknown                 | 20        | 1.23%   |
| HP EliteBook            | 19        | 1.17%   |
| HP EliteDesk            | 17        | 1.04%   |
| Toshiba Satellite       | 15        | 0.92%   |
| HP Laptop               | 15        | 0.92%   |
| ASUS All                | 13        | 0.8%    |
| HP ProDesk              | 11        | 0.68%   |
| HP ProBook              | 11        | 0.68%   |
| ASUS TUF                | 11        | 0.68%   |
| Fujitsu LIFEBOOK        | 9         | 0.55%   |
| ASUS VivoBook           | 9         | 0.55%   |
| ASUS M5A78L-M           | 7         | 0.43%   |
| Apple iMac9             | 7         | 0.43%   |
| Packard Bell EasyNote   | 6         | 0.37%   |
| Lenovo Legion           | 6         | 0.37%   |
| Gigabyte X570           | 6         | 0.37%   |
| Dell Vostro             | 6         | 0.37%   |
| ASUS P8Z77-V            | 6         | 0.37%   |
| Apple MacPro5           | 6         | 0.37%   |
| Apple MacBook4          | 6         | 0.37%   |
| Toshiba PORTEGE         | 5         | 0.31%   |
| Lenovo Yoga             | 5         | 0.31%   |
| Gigabyte B450M          | 5         | 0.31%   |
| Gigabyte B450           | 5         | 0.31%   |
| Fujitsu Siemens ESPRIMO | 5         | 0.31%   |
| Apple MacBookPro9       | 5         | 0.31%   |
| Apple MacBookPro5       | 5         | 0.31%   |
| Apple MacBook5          | 5         | 0.31%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 146       | 8.97%   |
| 2013    | 142       | 8.73%   |
| 2012    | 140       | 8.6%    |
| 2020    | 134       | 8.24%   |
| 2018    | 129       | 7.93%   |
| 2021    | 116       | 7.13%   |
| 2010    | 102       | 6.27%   |
| 2016    | 101       | 6.21%   |
| 2014    | 101       | 6.21%   |
| 2011    | 101       | 6.21%   |
| 2009    | 81        | 4.98%   |
| 2015    | 78        | 4.79%   |
| 2017    | 77        | 4.73%   |
| 2022    | 73        | 4.49%   |
| 2008    | 53        | 3.26%   |
| 2007    | 30        | 1.84%   |
| 2023    | 13        | 0.8%    |
| 2006    | 7         | 0.43%   |
| Unknown | 3         | 0.18%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 814       | 50.03%  |
| Desktop        | 720       | 44.25%  |
| Mini pc        | 36        | 2.21%   |
| All in one     | 28        | 1.72%   |
| Convertible    | 16        | 0.98%   |
| Server         | 7         | 0.43%   |
| Tablet         | 4         | 0.25%   |
| System on chip | 2         | 0.12%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1613      | 99.14%  |
| Yes  | 14        | 0.86%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 566       | 34.6%   |
| 4.01-8.0    | 454       | 27.75%  |
| 16.01-24.0  | 374       | 22.86%  |
| 32.01-64.0  | 113       | 6.91%   |
| 2.01-3.0    | 56        | 3.42%   |
| 64.01-256.0 | 30        | 1.83%   |
| 3.01-4.0    | 19        | 1.16%   |
| 24.01-32.0  | 19        | 1.16%   |
| 0.51-1.0    | 3         | 0.18%   |
| 1.01-2.0    | 2         | 0.12%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 0.01-0.5  | 889       | 54.14%  |
| 0.51-1.0  | 519       | 31.61%  |
| 1.01-2.0  | 170       | 10.35%  |
| 2.01-3.0  | 47        | 2.86%   |
| 3.01-4.0  | 10        | 0.61%   |
| 8.01-16.0 | 4         | 0.24%   |
| 4.01-8.0  | 3         | 0.18%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1031      | 61.63%  |
| 2      | 340       | 20.32%  |
| 3      | 116       | 6.93%   |
| 0      | 92        | 5.5%    |
| 4      | 50        | 2.99%   |
| 5      | 21        | 1.26%   |
| 6      | 13        | 0.78%   |
| 9      | 3         | 0.18%   |
| 7      | 3         | 0.18%   |
| 10     | 2         | 0.12%   |
| 13     | 1         | 0.06%   |
| 8      | 1         | 0.06%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1003      | 61.5%   |
| Yes       | 628       | 38.5%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1490      | 91.58%  |
| No        | 137       | 8.42%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1103      | 67.67%  |
| No        | 527       | 32.33%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 822       | 50.18%  |
| No        | 816       | 49.82%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 263       | 16.14%  |
| Germany     | 141       | 8.66%   |
| Russia      | 139       | 8.53%   |
| Brazil      | 104       | 6.38%   |
| Spain       | 71        | 4.36%   |
| Italy       | 61        | 3.74%   |
| UK          | 58        | 3.56%   |
| China       | 54        | 3.31%   |
| Poland      | 51        | 3.13%   |
| Canada      | 51        | 3.13%   |
| France      | 44        | 2.7%    |
| Netherlands | 38        | 2.33%   |
| Indonesia   | 33        | 2.03%   |
| Australia   | 33        | 2.03%   |
| Ukraine     | 31        | 1.9%    |
| Hungary     | 31        | 1.9%    |
| India       | 29        | 1.78%   |
| Mexico      | 27        | 1.66%   |
| Romania     | 21        | 1.29%   |
| Taiwan      | 18        | 1.1%    |
| Turkey      | 15        | 0.92%   |
| Sweden      | 15        | 0.92%   |
| South Korea | 13        | 0.8%    |
| Portugal    | 13        | 0.8%    |
| Bulgaria    | 13        | 0.8%    |
| Belgium     | 13        | 0.8%    |
| Argentina   | 13        | 0.8%    |
| Japan       | 11        | 0.68%   |
| Greece      | 11        | 0.68%   |
| Switzerland | 10        | 0.61%   |
| Peru        | 10        | 0.61%   |
| Norway      | 10        | 0.61%   |
| Chile       | 10        | 0.61%   |
| Serbia      | 8         | 0.49%   |
| Finland     | 8         | 0.49%   |
| Colombia    | 8         | 0.49%   |
| Vietnam     | 7         | 0.43%   |
| Lithuania   | 7         | 0.43%   |
| Czechia     | 7         | 0.43%   |
| Venezuela   | 6         | 0.37%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City          | Computers | Percent |
|---------------|-----------|---------|
| Moscow        | 26        | 1.52%   |
| St Petersburg | 13        | 0.76%   |
| Berlin        | 11        | 0.64%   |
| Sao Paulo     | 10        | 0.59%   |
| Guangzhou     | 10        | 0.59%   |
| Paris         | 9         | 0.53%   |
| New York      | 9         | 0.53%   |
| Curitiba      | 9         | 0.53%   |
| Budapest      | 9         | 0.53%   |
| Wroclaw       | 8         | 0.47%   |
| Madrid        | 8         | 0.47%   |
| Jakarta       | 8         | 0.47%   |
| Lima          | 7         | 0.41%   |
| Kyiv          | 7         | 0.41%   |
| Krakow        | 7         | 0.41%   |
| Brisbane      | 7         | 0.41%   |
| Warsaw        | 6         | 0.35%   |
| Valencia      | 6         | 0.35%   |
| Utrecht       | 6         | 0.35%   |
| Sydney        | 6         | 0.35%   |
| Santiago      | 6         | 0.35%   |
| Munich        | 6         | 0.35%   |
| Manchester    | 6         | 0.35%   |
| Krasnodar     | 6         | 0.35%   |
| Hanoi         | 6         | 0.35%   |
| Chelyabinsk   | 6         | 0.35%   |
| Bucharest     | 6         | 0.35%   |
| Yekaterinburg | 5         | 0.29%   |
| Temple        | 5         | 0.29%   |
| SГЈo Paulo  | 5         | 0.29%   |
| Surabaya      | 5         | 0.29%   |
| Stuttgart     | 5         | 0.29%   |
| Perth         | 5         | 0.29%   |
| Milan         | 5         | 0.29%   |
| Melbourne     | 5         | 0.29%   |
| Los Angeles   | 5         | 0.29%   |
| Istanbul      | 5         | 0.29%   |
| Bengaluru     | 5         | 0.29%   |
| Athens        | 5         | 0.29%   |
| Ankara        | 5         | 0.29%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 366       | 499    | 16.39%  |
| Samsung Electronics | 344       | 475    | 15.41%  |
| Seagate             | 324       | 448    | 14.51%  |
| Kingston            | 157       | 181    | 7.03%   |
| Toshiba             | 152       | 184    | 6.81%   |
| Crucial             | 111       | 145    | 4.97%   |
| SanDisk             | 100       | 107    | 4.48%   |
| Hitachi             | 99        | 119    | 4.43%   |
| Intel               | 55        | 61     | 2.46%   |
| A-DATA Technology   | 50        | 61     | 2.24%   |
| HGST                | 32        | 39     | 1.43%   |
| Micron Technology   | 25        | 26     | 1.12%   |
| SPCC                | 23        | 30     | 1.03%   |
| SK hynix            | 23        | 26     | 1.03%   |
| Apple               | 22        | 25     | 0.99%   |
| Patriot             | 19        | 22     | 0.85%   |
| China               | 18        | 19     | 0.81%   |
| PNY                 | 17        | 28     | 0.76%   |
| Transcend           | 16        | 17     | 0.72%   |
| OCZ                 | 15        | 17     | 0.67%   |
| KingSpec            | 15        | 19     | 0.67%   |
| Phison              | 13        | 17     | 0.58%   |
| Goodram             | 13        | 14     | 0.58%   |
| Fujitsu             | 13        | 15     | 0.58%   |
| Corsair             | 13        | 13     | 0.58%   |
| Intenso             | 12        | 15     | 0.54%   |
| Gigabyte Technology | 12        | 16     | 0.54%   |
| Hewlett-Packard     | 9         | 10     | 0.4%    |
| Silicon Motion      | 8         | 9      | 0.36%   |
| Apacer              | 8         | 8      | 0.36%   |
| Team                | 7         | 8      | 0.31%   |
| Plextor             | 7         | 7      | 0.31%   |
| LITEON              | 7         | 8      | 0.31%   |
| KIOXIA              | 7         | 7      | 0.31%   |
| Maxtor              | 6         | 7      | 0.27%   |
| Lexar               | 6         | 7      | 0.27%   |
| LITEONIT            | 5         | 5      | 0.22%   |
| XPG                 | 4         | 4      | 0.18%   |
| SSSTC               | 4         | 4      | 0.18%   |
| Pioneer             | 4         | 4      | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB         | 30        | 1.23%   |
| Samsung SSD 860 EVO 500GB           | 26        | 1.06%   |
| Crucial CT500MX500SSD1 500GB        | 23        | 0.94%   |
| Samsung SSD 850 EVO 250GB           | 21        | 0.86%   |
| Kingston SA400S37120G 120GB         | 21        | 0.86%   |
| Seagate ST500DM002-1BD142 500GB     | 19        | 0.78%   |
| Seagate ST1000LM035-1RK172 1TB      | 16        | 0.65%   |
| Toshiba MQ01ABD100 1TB              | 15        | 0.61%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 15        | 0.61%   |
| Samsung SSD 860 EVO 250GB           | 15        | 0.61%   |
| Samsung SSD 860 EVO 1TB             | 15        | 0.61%   |
| Samsung SSD 970 EVO Plus 500GB      | 14        | 0.57%   |
| Toshiba MQ01ABF050 500GB            | 13        | 0.53%   |
| Seagate ST1000DM010-2EP102 1TB      | 13        | 0.53%   |
| Crucial CT240BX500SSD1 240GB        | 13        | 0.53%   |
| Toshiba DT01ACA100 1TB              | 12        | 0.49%   |
| Seagate ST1000DM003-1ER162 1TB      | 12        | 0.49%   |
| Kingston SV300S37A120G 120GB        | 12        | 0.49%   |
| WDC WDS240G2G0A-00JH30 240GB        | 11        | 0.45%   |
| Seagate ST9500325AS 500GB           | 10        | 0.41%   |
| Seagate ST2000DM008-2FR102 2TB      | 10        | 0.41%   |
| Samsung SSD 840 EVO 250GB           | 10        | 0.41%   |
| WDC WDS120G2G0A-00JH30 120GB        | 9         | 0.37%   |
| Seagate ST3500418AS 500GB           | 9         | 0.37%   |
| Samsung SSD 970 EVO Plus 1TB        | 9         | 0.37%   |
| Samsung SSD 870 EVO 500GB           | 9         | 0.37%   |
| Kingston SA400S37480G 480GB         | 9         | 0.37%   |
| Toshiba HDWD110 1TB                 | 8         | 0.33%   |
| Samsung SSD 980 PRO 1TB             | 8         | 0.33%   |
| Samsung SSD 980 1TB                 | 8         | 0.33%   |
| Samsung SSD 850 EVO 500GB           | 8         | 0.33%   |
| Crucial CT480BX500SSD1 480GB        | 8         | 0.33%   |
| Crucial CT120BX500SSD1 120GB        | 8         | 0.33%   |
| A-DATA SU650 120GB                  | 8         | 0.33%   |
| Toshiba DT01ACA050 500GB            | 7         | 0.29%   |
| Seagate ST9320325AS 320GB           | 7         | 0.29%   |
| Seagate ST500LT012-1DG142 500GB     | 7         | 0.29%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 7         | 0.29%   |
| SanDisk pSSD 256GB                  | 7         | 0.29%   |
| Samsung SSD 970 EVO Plus 250GB      | 7         | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 322       | 443    | 33.86%  |
| WDC                 | 291       | 388    | 30.6%   |
| Toshiba             | 121       | 147    | 12.72%  |
| Hitachi             | 99        | 119    | 10.41%  |
| Samsung Electronics | 56        | 72     | 5.89%   |
| HGST                | 32        | 39     | 3.36%   |
| Fujitsu             | 12        | 13     | 1.26%   |
| Apple               | 7         | 7      | 0.74%   |
| Maxtor              | 6         | 7      | 0.63%   |
| Hewlett-Packard     | 3         | 3      | 0.32%   |
| QUANTUM             | 1         | 1      | 0.11%   |
| CLOVER              | 1         | 2      | 0.11%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 195       | 245    | 20.02%  |
| Kingston            | 125       | 145    | 12.83%  |
| SanDisk             | 100       | 107    | 10.27%  |
| Crucial             | 100       | 129    | 10.27%  |
| WDC                 | 55        | 64     | 5.65%   |
| A-DATA Technology   | 38        | 41     | 3.9%    |
| Intel               | 33        | 38     | 3.39%   |
| Toshiba             | 20        | 26     | 2.05%   |
| SPCC                | 20        | 27     | 2.05%   |
| Patriot             | 19        | 22     | 1.95%   |
| China               | 18        | 19     | 1.85%   |
| PNY                 | 17        | 26     | 1.75%   |
| OCZ                 | 15        | 17     | 1.54%   |
| KingSpec            | 15        | 19     | 1.54%   |
| Transcend           | 14        | 15     | 1.44%   |
| Micron Technology   | 14        | 14     | 1.44%   |
| Apple               | 14        | 17     | 1.44%   |
| Goodram             | 13        | 14     | 1.33%   |
| Intenso             | 12        | 15     | 1.23%   |
| Apacer              | 8         | 8      | 0.82%   |
| Plextor             | 7         | 7      | 0.72%   |
| LITEON              | 7         | 8      | 0.72%   |
| Gigabyte Technology | 7         | 9      | 0.72%   |
| Corsair             | 7         | 7      | 0.72%   |
| SK hynix            | 6         | 6      | 0.62%   |
| LITEONIT            | 5         | 5      | 0.51%   |
| Lexar               | 5         | 5      | 0.51%   |
| Team                | 4         | 5      | 0.41%   |
| Pioneer             | 4         | 4      | 0.41%   |
| Hewlett-Packard     | 4         | 5      | 0.41%   |
| XrayDisk            | 3         | 3      | 0.31%   |
| Smartbuy            | 3         | 3      | 0.31%   |
| Leven               | 3         | 4      | 0.31%   |
| Zheino              | 2         | 2      | 0.21%   |
| Verbatim            | 2         | 4      | 0.21%   |
| V-GeN               | 2         | 2      | 0.21%   |
| SETHRISE            | 2         | 2      | 0.21%   |
| OWC                 | 2         | 2      | 0.21%   |
| Netac               | 2         | 2      | 0.21%   |
| MyDigitalSSD        | 2         | 2      | 0.21%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 826       | 1155   | 41.99%  |
| HDD  | 807       | 1241   | 41.03%  |
| NVMe | 334       | 435    | 16.98%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1400      | 2396   | 80.74%  |
| NVMe | 334       | 435    | 19.26%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1173      | 1697   | 70.11%  |
| 0.51-1.0   | 346       | 452    | 20.68%  |
| 1.01-2.0   | 88        | 129    | 5.26%   |
| 3.01-4.0   | 30        | 47     | 1.79%   |
| 4.01-10.0  | 18        | 32     | 1.08%   |
| 2.01-3.0   | 16        | 35     | 0.96%   |
| 10.01-20.0 | 2         | 4      | 0.12%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 962       | 56.59%  |
| 101-250        | 316       | 18.59%  |
| 251-500        | 203       | 11.94%  |
| 501-1000       | 89        | 5.24%   |
| 51-100         | 81        | 4.76%   |
| 21-50          | 32        | 1.88%   |
| 1001-2000      | 10        | 0.59%   |
| Unknown        | 4         | 0.24%   |
| More than 3000 | 3         | 0.18%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1601      | 98.1%   |
| 101-250        | 10        | 0.61%   |
| 21-50          | 9         | 0.55%   |
| Unknown        | 4         | 0.25%   |
| 51-100         | 3         | 0.18%   |
| 251-500        | 2         | 0.12%   |
| More than 3000 | 1         | 0.06%   |
| 1001-2000      | 1         | 0.06%   |
| 501-1000       | 1         | 0.06%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB     | 7         | 9      | 1.65%   |
| Toshiba MQ01ABD100 1TB              | 6         | 6      | 1.41%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 6         | 9      | 1.41%   |
| Seagate ST9500325AS 500GB           | 5         | 7      | 1.18%   |
| Seagate ST9320325AS 320GB           | 5         | 5      | 1.18%   |
| Hitachi HTS545050A7E380 500GB       | 5         | 5      | 1.18%   |
| WDC WD5000AAKX-00ERMA0 500GB        | 4         | 4      | 0.94%   |
| Toshiba DT01ACA100 1TB              | 4         | 7      | 0.94%   |
| Seagate ST3500418AS 500GB           | 4         | 4      | 0.94%   |
| Hitachi HTS545050B9A300 500GB       | 4         | 4      | 0.94%   |
| HGST HTS725050A7E630 500GB          | 4         | 5      | 0.94%   |
| Toshiba MQ01ABF050 500GB            | 3         | 5      | 0.71%   |
| Toshiba MK3261GSYN 320GB            | 3         | 5      | 0.71%   |
| Seagate ST9500420AS 500GB           | 3         | 3      | 0.71%   |
| Seagate ST9160412AS 160GB           | 3         | 3      | 0.71%   |
| Seagate ST750LM022 HN-M750MBB 752GB | 3         | 3      | 0.71%   |
| Seagate ST500LT012-9WS142 500GB     | 3         | 3      | 0.71%   |
| Seagate ST500LM000-1EJ162 500GB     | 3         | 3      | 0.71%   |
| Seagate ST3250410AS 250GB           | 3         | 3      | 0.71%   |
| Seagate ST320LT020-9YG142 320GB     | 3         | 4      | 0.71%   |
| Seagate ST31000528AS 1TB            | 3         | 4      | 0.71%   |
| SanDisk SSD PLUS 240GB              | 3         | 3      | 0.71%   |
| Samsung Electronics HD322HJ 320GB   | 3         | 4      | 0.71%   |
| Hitachi HTS542525K9A300 250GB       | 3         | 3      | 0.71%   |
| Hitachi HTS541612J9SA00 120GB       | 3         | 3      | 0.71%   |
| HGST HTS545032A7E380 320GB          | 3         | 3      | 0.71%   |
| HGST HTS541010A9E680 1TB            | 3         | 4      | 0.71%   |
| WDC WD5000LPCX-60VHAT0 500GB        | 2         | 3      | 0.47%   |
| WDC WD5000AAKX-60U6AA0 500GB        | 2         | 2      | 0.47%   |
| WDC WD3200BEVT-22ZCT0 320GB         | 2         | 2      | 0.47%   |
| WDC WD30EFRX-68EUZN0 3TB            | 2         | 2      | 0.47%   |
| WDC WD20EARS-00MVWB0 2TB            | 2         | 2      | 0.47%   |
| WDC WD10JMVW-11AJGS0 1TB            | 2         | 2      | 0.47%   |
| WDC WD10EARS-003BB1 1TB             | 2         | 2      | 0.47%   |
| Toshiba MQ01ABD075 752GB            | 2         | 2      | 0.47%   |
| Toshiba MQ01ABD032 320GB            | 2         | 2      | 0.47%   |
| Toshiba MK8034GSX 80GB              | 2         | 3      | 0.47%   |
| Toshiba MK1255GSX H 120GB           | 2         | 2      | 0.47%   |
| Seagate ST9320423AS 320GB           | 2         | 2      | 0.47%   |
| Seagate ST9160821AS 160GB           | 2         | 2      | 0.47%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 109       | 136    | 26.52%  |
| WDC                 | 89        | 95     | 21.65%  |
| Hitachi             | 50        | 57     | 12.17%  |
| Toshiba             | 48        | 59     | 11.68%  |
| Samsung Electronics | 32        | 41     | 7.79%   |
| HGST                | 17        | 20     | 4.14%   |
| Kingston            | 11        | 11     | 2.68%   |
| SanDisk             | 7         | 7      | 1.7%    |
| Intel               | 7         | 7      | 1.7%    |
| Crucial             | 7         | 12     | 1.7%    |
| Maxtor              | 4         | 5      | 0.97%   |
| Fujitsu             | 4         | 4      | 0.97%   |
| Apple               | 4         | 4      | 0.97%   |
| Corsair             | 3         | 3      | 0.73%   |
| OCZ                 | 2         | 2      | 0.49%   |
| Micron Technology   | 2         | 2      | 0.49%   |
| LITEON              | 2         | 2      | 0.49%   |
| China               | 2         | 2      | 0.49%   |
| A-DATA Technology   | 2         | 2      | 0.49%   |
| XrayDisk            | 1         | 1      | 0.24%   |
| SSSTC               | 1         | 1      | 0.24%   |
| SK hynix            | 1         | 1      | 0.24%   |
| Silicon Motion      | 1         | 1      | 0.24%   |
| Pioneer             | 1         | 1      | 0.24%   |
| MidasForce          | 1         | 1      | 0.24%   |
| KingSpec            | 1         | 1      | 0.24%   |
| Hewlett-Packard     | 1         | 1      | 0.24%   |
| AGI                 | 1         | 1      | 0.24%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 109       | 136    | 31.78%  |
| WDC                 | 87        | 93     | 25.36%  |
| Hitachi             | 50        | 57     | 14.58%  |
| Toshiba             | 46        | 57     | 13.41%  |
| Samsung Electronics | 22        | 26     | 6.41%   |
| HGST                | 17        | 20     | 4.96%   |
| Maxtor              | 4         | 5      | 1.17%   |
| Fujitsu             | 4         | 4      | 1.17%   |
| Apple               | 4         | 4      | 1.17%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 318       | 402    | 82.17%  |
| SSD  | 61        | 69     | 15.76%  |
| NVMe | 8         | 9      | 2.07%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| SanDisk pSSD 256GB                | 3         | 3      | 23.08%  |
| WDC WD7501AALS-00J7B0 752GB       | 1         | 1      | 7.69%   |
| WDC WD3200AAJS-00YZCA0 320GB      | 1         | 1      | 7.69%   |
| WDC WD1600BEVT-22ZCT0 160GB       | 1         | 1      | 7.69%   |
| Seagate ST3250310AS 250GB         | 1         | 1      | 7.69%   |
| Samsung Electronics HM500JJ 500GB | 1         | 1      | 7.69%   |
| Samsung Electronics HD103SJ 1TB   | 1         | 1      | 7.69%   |
| HPE MK000480GWUGF 480GB           | 1         | 1      | 7.69%   |
| Hitachi HTS545025B9A300 250GB     | 1         | 1      | 7.69%   |
| Hitachi HDS721010DLE630 1TB       | 1         | 1      | 7.69%   |
| HGST HTS725050A7E630 500GB        | 1         | 1      | 7.69%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 3         | 3      | 23.08%  |
| SanDisk             | 3         | 3      | 23.08%  |
| Samsung Electronics | 2         | 2      | 15.38%  |
| Hitachi             | 2         | 2      | 15.38%  |
| Seagate             | 1         | 1      | 7.69%   |
| HPE                 | 1         | 1      | 7.69%   |
| HGST                | 1         | 1      | 7.69%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 1291      | 2283   | 75.1%   |
| Malfunc  | 379       | 480    | 22.05%  |
| Detected | 36        | 55     | 2.09%   |
| Failed   | 13        | 13     | 0.76%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 1236      | 62.02%  |
| AMD                                     | 273       | 13.7%   |
| Samsung Electronics                     | 129       | 6.47%   |
| SanDisk                                 | 45        | 2.26%   |
| Nvidia                                  | 42        | 2.11%   |
| Kingston Technology Company             | 33        | 1.66%   |
| Phison Electronics                      | 28        | 1.4%    |
| ASMedia Technology                      | 27        | 1.35%   |
| Silicon Motion                          | 21        | 1.05%   |
| JMicron Technology                      | 18        | 0.9%    |
| SK hynix                                | 16        | 0.8%    |
| Marvell Technology Group                | 15        | 0.75%   |
| Micron/Crucial Technology               | 13        | 0.65%   |
| Broadcom / LSI                          | 12        | 0.6%    |
| Micron Technology                       | 11        | 0.55%   |
| ADATA Technology                        | 11        | 0.55%   |
| Toshiba                                 | 9         | 0.45%   |
| KIOXIA                                  | 9         | 0.45%   |
| Realtek Semiconductor                   | 8         | 0.4%    |
| VIA Technologies                        | 7         | 0.35%   |
| Silicon Integrated Systems [SiS]        | 4         | 0.2%    |
| Shenzhen Longsys Electronics            | 4         | 0.2%    |
| Solid State Storage Technology          | 3         | 0.15%   |
| Seagate Technology                      | 3         | 0.15%   |
| Adaptec                                 | 3         | 0.15%   |
| Lite-On IT Corp. / Plextor              | 2         | 0.1%    |
| Hewlett-Packard                         | 2         | 0.1%    |
| Biwin Storage Technology                | 2         | 0.1%    |
| Silicon Image                           | 1         | 0.05%   |
| Shenzhen Unionmemory Information System | 1         | 0.05%   |
| OCZ Technology Group                    | 1         | 0.05%   |
| Lenovo                                  | 1         | 0.05%   |
| Enmotus                                 | 1         | 0.05%   |
| Broadcom                                | 1         | 0.05%   |
| Apple                                   | 1         | 0.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 168       | 7.27%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 117       | 5.06%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 110       | 4.76%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 81        | 3.5%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 72        | 3.12%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 64        | 2.77%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 62        | 2.68%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 57        | 2.47%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 55        | 2.38%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 48        | 2.08%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 41        | 1.77%   |
| AMD 400 Series Chipset SATA Controller                                                  | 40        | 1.73%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 39        | 1.69%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 37        | 1.6%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 36        | 1.56%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 35        | 1.51%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 35        | 1.51%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 34        | 1.47%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 34        | 1.47%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 33        | 1.43%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 31        | 1.34%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 29        | 1.25%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 28        | 1.21%   |
| Intel SATA Controller [RAID mode]                                                       | 28        | 1.21%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 28        | 1.21%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 27        | 1.17%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 25        | 1.08%   |
| Nvidia MCP79 AHCI Controller                                                            | 24        | 1.04%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 23        | 1%      |
| Samsung NVMe SSD Controller 980                                                         | 20        | 0.87%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 18        | 0.78%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 18        | 0.78%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 18        | 0.78%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 18        | 0.78%   |
| AMD 500 Series Chipset SATA Controller                                                  | 18        | 0.78%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 17        | 0.74%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 16        | 0.69%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 16        | 0.69%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 16        | 0.69%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 15        | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1321      | 65.56%  |
| NVMe | 337       | 16.72%  |
| IDE  | 255       | 12.66%  |
| RAID | 86        | 4.27%   |
| SAS  | 9         | 0.45%   |
| SCSI | 7         | 0.35%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 1315      | 80.82%  |
| AMD      | 309       | 18.99%  |
| Rockchip | 1         | 0.06%   |
| Bochs    | 1         | 0.06%   |
| ARM      | 1         | 0.06%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz           | 21        | 1.29%   |
| Intel CPU Version                           | 20        | 1.23%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 19        | 1.17%   |
| Intel Core 2 Duo                            | 17        | 1.04%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 16        | 0.98%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 16        | 0.98%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 15        | 0.92%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 14        | 0.86%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 14        | 0.86%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 14        | 0.86%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 12        | 0.74%   |
| Intel Core i5-3317U CPU @ 1.70GHz           | 11        | 0.67%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 10        | 0.61%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 10        | 0.61%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 9         | 0.55%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 9         | 0.55%   |
| Intel Core i3-6006U CPU @ 2.00GHz           | 9         | 0.55%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 9         | 0.55%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 8         | 0.49%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 8         | 0.49%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 8         | 0.49%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 8         | 0.49%   |
| Intel Core i3-4005U CPU @ 1.70GHz           | 8         | 0.49%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 8         | 0.49%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 8         | 0.49%   |
| AMD Ryzen 5 3600 6-Core Processor           | 8         | 0.49%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 8         | 0.49%   |
| Intel Xeon                                  | 7         | 0.43%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 7         | 0.43%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 7         | 0.43%   |
| Intel Core i7-3520M CPU @ 2.90GHz           | 7         | 0.43%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 7         | 0.43%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 7         | 0.43%   |
| Intel Core i3-5005U CPU @ 2.00GHz           | 7         | 0.43%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz        | 7         | 0.43%   |
| Intel Core 2 Duo CPU P7350 @ 2.00GHz        | 7         | 0.43%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 7         | 0.43%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 7         | 0.43%   |
| Intel Genuine CPU                           | 6         | 0.37%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 6         | 0.37%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 434       | 26.63%  |
| Intel Core i7           | 230       | 14.11%  |
| Intel Core i3           | 167       | 10.25%  |
| Intel Core 2 Duo        | 120       | 7.36%   |
| Intel Celeron           | 90        | 5.52%   |
| AMD Ryzen 5             | 73        | 4.48%   |
| Intel Xeon              | 71        | 4.36%   |
| Other                   | 60        | 3.68%   |
| Intel Pentium           | 50        | 3.07%   |
| AMD Ryzen 7             | 46        | 2.82%   |
| AMD Ryzen 3             | 27        | 1.66%   |
| AMD FX                  | 23        | 1.41%   |
| Intel Pentium Dual-Core | 22        | 1.35%   |
| Intel Atom              | 20        | 1.23%   |
| AMD Phenom II X4        | 18        | 1.1%    |
| Intel Core 2 Quad       | 15        | 0.92%   |
| AMD Ryzen 9             | 11        | 0.67%   |
| Intel Genuine           | 10        | 0.61%   |
| AMD E1                  | 10        | 0.61%   |
| AMD A10                 | 10        | 0.61%   |
| AMD A6                  | 9         | 0.55%   |
| AMD A8                  | 8         | 0.49%   |
| Intel Pentium Silver    | 7         | 0.43%   |
| Intel Core 2            | 7         | 0.43%   |
| AMD Athlon II X2        | 7         | 0.43%   |
| Intel Core i9           | 6         | 0.37%   |
| AMD Ryzen Threadripper  | 6         | 0.37%   |
| AMD E                   | 6         | 0.37%   |
| AMD A4                  | 6         | 0.37%   |
| AMD Athlon II X4        | 5         | 0.31%   |
| Intel Pentium Dual      | 4         | 0.25%   |
| AMD E2                  | 4         | 0.25%   |
| AMD Athlon 64 X2        | 4         | 0.25%   |
| AMD Athlon              | 4         | 0.25%   |
| Intel Core m3           | 3         | 0.18%   |
| AMD Ryzen 5 PRO         | 3         | 0.18%   |
| AMD Phenom II X6        | 3         | 0.18%   |
| Intel Pentium Gold      | 2         | 0.12%   |
| Intel Pentium 4         | 2         | 0.12%   |
| Intel Core M            | 2         | 0.12%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 715       | 43.89%  |
| 4       | 490       | 30.08%  |
| Unknown | 122       | 7.49%   |
| 6       | 92        | 5.65%   |
| 8       | 74        | 4.54%   |
| 12      | 55        | 3.38%   |
| 16      | 43        | 2.64%   |
| 1       | 17        | 1.04%   |
| 24      | 8         | 0.49%   |
| 10      | 4         | 0.25%   |
| 64      | 2         | 0.12%   |
| 48      | 2         | 0.12%   |
| 32      | 2         | 0.12%   |
| 18      | 1         | 0.06%   |
| 14      | 1         | 0.06%   |
| 3       | 1         | 0.06%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1573      | 96.68%  |
| 2       | 49        | 3.01%   |
| Unknown | 3         | 0.18%   |
| 8       | 2         | 0.12%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 790       | 48.56%  |
| 1       | 709       | 43.58%  |
| Unknown | 128       | 7.87%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 225       | 13.82%  |
| IvyBridge     | 174       | 10.69%  |
| Haswell       | 171       | 10.5%   |
| SandyBridge   | 142       | 8.72%   |
| Penryn        | 139       | 8.54%   |
| Skylake       | 127       | 7.8%    |
| Westmere      | 67        | 4.12%   |
| Core          | 63        | 3.87%   |
| Zen+          | 54        | 3.32%   |
| Zen 2         | 45        | 2.76%   |
| Broadwell     | 42        | 2.58%   |
| K10           | 39        | 2.4%    |
| Silvermont    | 38        | 2.33%   |
| Piledriver    | 37        | 2.27%   |
| Zen 3         | 34        | 2.09%   |
| Zen           | 33        | 2.03%   |
| CometLake     | 27        | 1.66%   |
| Unknown       | 27        | 1.66%   |
| Bonnell       | 19        | 1.17%   |
| Nehalem       | 18        | 1.11%   |
| Goldmont plus | 17        | 1.04%   |
| Excavator     | 16        | 0.98%   |
| Bobcat        | 15        | 0.92%   |
| TigerLake     | 12        | 0.74%   |
| Goldmont      | 12        | 0.74%   |
| K8 Hammer     | 9         | 0.55%   |
| Jaguar        | 9         | 0.55%   |
| Bulldozer     | 5         | 0.31%   |
| NetBurst      | 3         | 0.18%   |
| K10 Llano     | 3         | 0.18%   |
| IceLake       | 3         | 0.18%   |
| Puma          | 2         | 0.12%   |
| Steamroller   | 1         | 0.06%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 989       | 54.1%   |
| Nvidia                           | 477       | 26.09%  |
| AMD                              | 354       | 19.37%  |
| Silicon Integrated Systems [SiS] | 3         | 0.16%   |
| Matrox Electronics Systems       | 3         | 0.16%   |
| Red Hat                          | 1         | 0.05%   |
| ASPEED Technology                | 1         | 0.05%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 112       | 5.99%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 102       | 5.45%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 58        | 3.1%    |
| Intel HD Graphics 530                                                                    | 49        | 2.62%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 47        | 2.51%   |
| Intel HD Graphics 620                                                                    | 45        | 2.41%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 44        | 2.35%   |
| Intel Core Processor Integrated Graphics Controller                                      | 44        | 2.35%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 36        | 1.93%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 35        | 1.87%   |
| Intel HD Graphics 5500                                                                   | 34        | 1.82%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 34        | 1.82%   |
| Intel UHD Graphics 620                                                                   | 30        | 1.6%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 27        | 1.44%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 27        | 1.44%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 27        | 1.44%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 26        | 1.39%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 23        | 1.23%   |
| Intel HD Graphics 630                                                                    | 23        | 1.23%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 21        | 1.12%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 19        | 1.02%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 18        | 0.96%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 16        | 0.86%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 16        | 0.86%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 16        | 0.86%   |
| AMD Renoir                                                                               | 15        | 0.8%    |
| Nvidia GT218 [GeForce 210]                                                               | 14        | 0.75%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 13        | 0.7%    |
| Nvidia GF119 [GeForce GT 610]                                                            | 13        | 0.7%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 13        | 0.7%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 13        | 0.7%    |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 13        | 0.7%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 12        | 0.64%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 12        | 0.64%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 12        | 0.64%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 11        | 0.59%   |
| Nvidia C79 [GeForce 9400M]                                                               | 11        | 0.59%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 11        | 0.59%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 11        | 0.59%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 11        | 0.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 710       | 43.29%  |
| 1 x Nvidia     | 338       | 20.61%  |
| 1 x AMD        | 283       | 17.26%  |
| Intel + Nvidia | 125       | 7.62%   |
| 2 x Intel      | 97        | 5.91%   |
| Intel + AMD    | 56        | 3.41%   |
| AMD + Nvidia   | 12        | 0.73%   |
| 2 x AMD        | 5         | 0.3%    |
| Other          | 3         | 0.18%   |
| 2 x Nvidia     | 3         | 0.18%   |
| 1 x SiS        | 3         | 0.18%   |
| 1 x Matrox     | 3         | 0.18%   |
| 1 x Red Hat    | 1         | 0.06%   |
| AMD + ASPEED   | 1         | 0.06%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1299      | 79.01%  |
| Proprietary | 258       | 15.69%  |
| Unknown     | 87        | 5.29%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1184      | 71.67%  |
| 0.01-0.5   | 114       | 6.9%    |
| 1.01-2.0   | 112       | 6.78%   |
| 0.51-1.0   | 85        | 5.15%   |
| 3.01-4.0   | 73        | 4.42%   |
| 7.01-8.0   | 40        | 2.42%   |
| 5.01-6.0   | 31        | 1.88%   |
| 2.01-3.0   | 8         | 0.48%   |
| 8.01-16.0  | 5         | 0.3%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 131       | 11.13%  |
| AU Optronics            | 121       | 10.28%  |
| LG Display              | 118       | 10.03%  |
| Chimei Innolux          | 86        | 7.31%   |
| Goldstar                | 73        | 6.2%    |
| Dell                    | 72        | 6.12%   |
| BOE                     | 66        | 5.61%   |
| Lenovo                  | 53        | 4.5%    |
| Hewlett-Packard         | 46        | 3.91%   |
| Acer                    | 46        | 3.91%   |
| Apple                   | 42        | 3.57%   |
| BenQ                    | 40        | 3.4%    |
| AOC                     | 35        | 2.97%   |
| Philips                 | 27        | 2.29%   |
| Ancor Communications    | 25        | 2.12%   |
| Chi Mei Optoelectronics | 20        | 1.7%    |
| ViewSonic               | 13        | 1.1%    |
| Sharp                   | 11        | 0.93%   |
| InfoVision              | 11        | 0.93%   |
| Iiyama                  | 10        | 0.85%   |
| ASUSTek Computer        | 10        | 0.85%   |
| Sony                    | 8         | 0.68%   |
| Fujitsu Siemens         | 8         | 0.68%   |
| NEC Computers           | 6         | 0.51%   |
| MSI                     | 6         | 0.51%   |
| LG Philips              | 6         | 0.51%   |
| HannStar                | 6         | 0.51%   |
| PANDA                   | 5         | 0.42%   |
| Eizo                    | 5         | 0.42%   |
| Vizio                   | 4         | 0.34%   |
| Toshiba                 | 4         | 0.34%   |
| LG Electronics          | 4         | 0.34%   |
| Unknown                 | 4         | 0.34%   |
| Vestel Elektronik       | 3         | 0.25%   |
| Packard Bell            | 3         | 0.25%   |
| RS                      | 2         | 0.17%   |
| Medion                  | 2         | 0.17%   |
| Lenovo Group Limited    | 2         | 0.17%   |
| LED                     | 2         | 0.17%   |
| Insignia                | 2         | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Lenovo LCD Monitor LEN4031 1280x800 300x190mm 14.0-inch               | 7         | 0.59%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch           | 6         | 0.5%    |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch         | 6         | 0.5%    |
| Lenovo LCD Monitor LEN4035 1280x800 300x190mm 14.0-inch               | 5         | 0.42%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 340x190mm 15.3-inch         | 5         | 0.42%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 340x190mm 15.3-inch  | 4         | 0.34%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 340x190mm 15.3-inch | 4         | 0.34%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch           | 4         | 0.34%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x130mm 10.1-inch             | 4         | 0.34%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch             | 4         | 0.34%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 340x190mm 15.3-inch       | 4         | 0.34%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch      | 4         | 0.34%   |
| BenQ GW2780 BNQ78E6 1920x1080 600x340mm 27.2-inch                     | 4         | 0.34%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 340x190mm 15.3-inch         | 4         | 0.34%   |
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                  | 4         | 0.34%   |
| Acer G227HQL ACR03DE 1920x1080 480x270mm 21.7-inch                    | 4         | 0.34%   |
| Unknown                                                               | 4         | 0.34%   |
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 710x400mm 32.1-inch    | 3         | 0.25%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 340x190mm 15.3-inch  | 3         | 0.25%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch  | 3         | 0.25%   |
| Philips PHL 193V5 PHLC0CD 1366x768 410x230mm 18.5-inch                | 3         | 0.25%   |
| MSI G32C4 MSI3DA6 1920x1080 700x390mm 31.5-inch                       | 3         | 0.25%   |
| LG Display LCD Monitor LGD0459 1920x1080 380x210mm 17.1-inch          | 3         | 0.25%   |
| LG Display LCD Monitor LGD0385 1366x768 310x170mm 13.9-inch           | 3         | 0.25%   |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch           | 3         | 0.25%   |
| LG Display LCD Monitor LGD024D 1366x768 290x170mm 13.2-inch           | 3         | 0.25%   |
| Lenovo LCD Monitor LEN40B0 1366x768 340x190mm 15.3-inch               | 3         | 0.25%   |
| Lenovo LCD Monitor LEN4050 1280x800 330x210mm 15.4-inch               | 3         | 0.25%   |
| Lenovo LCD Monitor LEN4000 1024x768 250x180mm 12.1-inch               | 3         | 0.25%   |
| InfoVision LCD Monitor IVO04E3 1366x768 280x160mm 12.7-inch           | 3         | 0.25%   |
| InfoVision LCD Monitor IVO03F4 1024x600 220x130mm 10.1-inch           | 3         | 0.25%   |
| Goldstar W1934 GSM4B7A 1440x900 410x260mm 19.1-inch                   | 3         | 0.25%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch          | 3         | 0.25%   |
| Goldstar LG FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch             | 3         | 0.25%   |
| Dell U2412M DELA07A 1920x1200 520x320mm 24.0-inch                     | 3         | 0.25%   |
| Dell S2418HN/NX DEL4123 1920x1080 530x300mm 24.0-inch                 | 3         | 0.25%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 340x190mm 15.3-inch      | 3         | 0.25%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 340x190mm 15.3-inch       | 3         | 0.25%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 340x190mm 15.3-inch       | 3         | 0.25%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 310x170mm 13.9-inch      | 3         | 0.25%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 437       | 37.7%   |
| 1366x768 (WXGA)    | 304       | 26.23%  |
| 1600x900 (HD+)     | 57        | 4.92%   |
| 1280x800 (WXGA)    | 54        | 4.66%   |
| 2560x1440 (QHD)    | 48        | 4.14%   |
| 1280x1024 (SXGA)   | 42        | 3.62%   |
| 3840x2160 (4K)     | 41        | 3.54%   |
| 1680x1050 (WSXGA+) | 41        | 3.54%   |
| 1440x900 (WXGA+)   | 33        | 2.85%   |
| 1920x1200 (WUXGA)  | 21        | 1.81%   |
| 2560x1080          | 13        | 1.12%   |
| 1024x600           | 12        | 1.04%   |
| 1024x768 (XGA)     | 9         | 0.78%   |
| 3440x1440          | 7         | 0.6%    |
| 1920x540           | 6         | 0.52%   |
| 1360x768           | 6         | 0.52%   |
| 2560x1600          | 5         | 0.43%   |
| 3200x1800 (QHD+)   | 4         | 0.35%   |
| Unknown            | 3         | 0.26%   |
| 3840x1080          | 2         | 0.17%   |
| 2048x1152          | 2         | 0.17%   |
| 1600x1200          | 2         | 0.17%   |
| 1400x1050          | 2         | 0.17%   |
| 5760x2160          | 1         | 0.09%   |
| 3840x2400          | 1         | 0.09%   |
| 3520x1080          | 1         | 0.09%   |
| 3200x2000          | 1         | 0.09%   |
| 2880x1800          | 1         | 0.09%   |
| 2736x1824          | 1         | 0.09%   |
| 2160x1440          | 1         | 0.09%   |
| 1800x1200          | 1         | 0.09%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 240       | 20.34%  |
| 13      | 190       | 16.1%   |
| 24      | 96        | 8.14%   |
| 21      | 88        | 7.46%   |
| 27      | 79        | 6.69%   |
| 19      | 67        | 5.68%   |
| 23      | 66        | 5.59%   |
| 12      | 52        | 4.41%   |
| 17      | 45        | 3.81%   |
| Unknown | 42        | 3.56%   |
| 18      | 31        | 2.63%   |
| 14      | 31        | 2.63%   |
| 31      | 28        | 2.37%   |
| 11      | 24        | 2.03%   |
| 20      | 19        | 1.61%   |
| 22      | 18        | 1.53%   |
| 34      | 14        | 1.19%   |
| 10      | 12        | 1.02%   |
| 42      | 4         | 0.34%   |
| 29      | 4         | 0.34%   |
| 50      | 3         | 0.25%   |
| 40      | 3         | 0.25%   |
| 28      | 3         | 0.25%   |
| 16      | 3         | 0.25%   |
| 9       | 3         | 0.25%   |
| 64      | 2         | 0.17%   |
| 54      | 2         | 0.17%   |
| 52      | 2         | 0.17%   |
| 33      | 2         | 0.17%   |
| 41      | 1         | 0.08%   |
| 39      | 1         | 0.08%   |
| 36      | 1         | 0.08%   |
| 32      | 1         | 0.08%   |
| 30      | 1         | 0.08%   |
| 26      | 1         | 0.08%   |
| 25      | 1         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 388       | 33.19%  |
| 501-600     | 226       | 19.33%  |
| 401-500     | 198       | 16.94%  |
| 201-300     | 180       | 15.4%   |
| 351-400     | 56        | 4.79%   |
| 601-700     | 43        | 3.68%   |
| Unknown     | 42        | 3.59%   |
| 701-800     | 18        | 1.54%   |
| 1001-1500   | 9         | 0.77%   |
| 901-1000    | 5         | 0.43%   |
| 801-900     | 4         | 0.34%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 864       | 76.33%  |
| 16/10   | 151       | 13.34%  |
| 5/4     | 38        | 3.36%   |
| Unknown | 30        | 2.65%   |
| 21/9    | 20        | 1.77%   |
| 4/3     | 15        | 1.33%   |
| 3/2     | 14        | 1.24%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 235       | 20.07%  |
| 91-100         | 190       | 16.23%  |
| 81-90          | 177       | 15.12%  |
| 151-200        | 91        | 7.77%   |
| 301-350        | 82        | 7%      |
| 101-110        | 58        | 4.95%   |
| 61-70          | 52        | 4.44%   |
| 351-500        | 48        | 4.1%    |
| 141-150        | 43        | 3.67%   |
| Unknown        | 42        | 3.59%   |
| 71-80          | 35        | 2.99%   |
| 251-300        | 27        | 2.31%   |
| 121-130        | 26        | 2.22%   |
| 51-60          | 22        | 1.88%   |
| 41-50          | 15        | 1.28%   |
| 501-1000       | 10        | 0.85%   |
| More than 1000 | 9         | 0.77%   |
| 111-120        | 5         | 0.43%   |
| 131-140        | 4         | 0.34%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 421       | 36.26%  |
| 101-120       | 380       | 32.73%  |
| 121-160       | 257       | 22.14%  |
| 161-240       | 44        | 3.79%   |
| Unknown       | 42        | 3.62%   |
| More than 240 | 11        | 0.95%   |
| 1-50          | 6         | 0.52%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1317      | 79.87%  |
| 0     | 245       | 14.86%  |
| 2     | 85        | 5.15%   |
| 3     | 2         | 0.12%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 812       | 35.06%  |
| Realtek Semiconductor                  | 795       | 34.33%  |
| Qualcomm Atheros                       | 270       | 11.66%  |
| Broadcom                               | 167       | 7.21%   |
| Marvell Technology Group               | 34        | 1.47%   |
| Ralink                                 | 27        | 1.17%   |
| Nvidia                                 | 25        | 1.08%   |
| Ralink Technology                      | 23        | 0.99%   |
| Samsung Electronics                    | 18        | 0.78%   |
| TP-Link                                | 14        | 0.6%    |
| Sierra Wireless                        | 11        | 0.47%   |
| Xiaomi                                 | 9         | 0.39%   |
| MediaTek                               | 9         | 0.39%   |
| JMicron Technology                     | 9         | 0.39%   |
| Google                                 | 9         | 0.39%   |
| Ericsson Business Mobile Networks      | 9         | 0.39%   |
| Edimax Technology                      | 8         | 0.35%   |
| Dell                                   | 8         | 0.35%   |
| D-Link System                          | 7         | 0.3%    |
| Huawei Technologies                    | 6         | 0.26%   |
| D-Link                                 | 5         | 0.22%   |
| Silicon Integrated Systems [SiS]       | 4         | 0.17%   |
| NetGear                                | 4         | 0.17%   |
| Hewlett-Packard                        | 3         | 0.13%   |
| Qualcomm                               | 2         | 0.09%   |
| OPPO Electronics                       | 2         | 0.09%   |
| Mellanox Technologies                  | 2         | 0.09%   |
| IMC Networks                           | 2         | 0.09%   |
| Belkin Components                      | 2         | 0.09%   |
| ASUSTek Computer                       | 2         | 0.09%   |
| VIA Technologies                       | 1         | 0.04%   |
| Toshiba                                | 1         | 0.04%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.04%   |
| Qualcomm Atheros Communications        | 1         | 0.04%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.04%   |
| National Semiconductor                 | 1         | 0.04%   |
| Napatech A/S                           | 1         | 0.04%   |
| Motorola PCS                           | 1         | 0.04%   |
| Microchip Technology                   | 1         | 0.04%   |
| Mercucys                               | 1         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 593       | 21.13%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 111       | 3.96%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 103       | 3.67%   |
| Intel Wireless 8265 / 8275                                        | 58        | 2.07%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 56        | 2%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 49        | 1.75%   |
| Intel Wireless 7260                                               | 48        | 1.71%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 48        | 1.71%   |
| Intel Wireless 7265                                               | 46        | 1.64%   |
| Intel Ethernet Connection I217-LM                                 | 46        | 1.64%   |
| Intel Wireless 8260                                               | 42        | 1.5%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 41        | 1.46%   |
| Intel I211 Gigabit Network Connection                             | 37        | 1.32%   |
| Intel Wi-Fi 6 AX200                                               | 34        | 1.21%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 33        | 1.18%   |
| Intel Ethernet Connection (2) I219-LM                             | 33        | 1.18%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 26        | 0.93%   |
| Intel Ethernet Connection I219-LM                                 | 25        | 0.89%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 25        | 0.89%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 24        | 0.86%   |
| Intel Wireless 3165                                               | 24        | 0.86%   |
| Nvidia MCP79 Ethernet                                             | 23        | 0.82%   |
| Intel Ethernet Connection (7) I219-V                              | 23        | 0.82%   |
| Intel 82577LM Gigabit Network Connection                          | 21        | 0.75%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 19        | 0.68%   |
| Intel Ethernet Connection (2) I219-V                              | 19        | 0.68%   |
| Intel 82574L Gigabit Network Connection                           | 19        | 0.68%   |
| Intel Centrino Advanced-N 6200                                    | 18        | 0.64%   |
| Intel Ethernet Connection (4) I219-LM                             | 17        | 0.61%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 16        | 0.57%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 16        | 0.57%   |
| Intel Ethernet Connection I218-LM                                 | 15        | 0.53%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 15        | 0.53%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 14        | 0.5%    |
| Intel Ethernet Controller I225-V                                  | 14        | 0.5%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 14        | 0.5%    |
| Intel 82579V Gigabit Network Connection                           | 14        | 0.5%    |
| Broadcom BCM43224 802.11a/b/g/n                                   | 14        | 0.5%    |
| Broadcom BCM4321 802.11a/b/g/n                                    | 14        | 0.5%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 13        | 0.46%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 554       | 46.48%  |
| Qualcomm Atheros                | 223       | 18.71%  |
| Realtek Semiconductor           | 177       | 14.85%  |
| Broadcom                        | 123       | 10.32%  |
| Ralink                          | 27        | 2.27%   |
| Ralink Technology               | 23        | 1.93%   |
| TP-Link                         | 14        | 1.17%   |
| Sierra Wireless                 | 8         | 0.67%   |
| Edimax Technology               | 8         | 0.67%   |
| MediaTek                        | 7         | 0.59%   |
| D-Link                          | 5         | 0.42%   |
| NetGear                         | 4         | 0.34%   |
| D-Link System                   | 4         | 0.34%   |
| Dell                            | 3         | 0.25%   |
| IMC Networks                    | 2         | 0.17%   |
| Belkin Components               | 2         | 0.17%   |
| ASUSTek Computer                | 2         | 0.17%   |
| Qualcomm Atheros Communications | 1         | 0.08%   |
| Mercucys                        | 1         | 0.08%   |
| BUFFALO                         | 1         | 0.08%   |
| Atheros                         | 1         | 0.08%   |
| Accton Technology               | 1         | 0.08%   |
| AboCom Systems                  | 1         | 0.08%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                              | 58        | 4.79%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 56        | 4.63%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 49        | 4.05%   |
| Intel Wireless 7260                                                     | 48        | 3.97%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 48        | 3.97%   |
| Intel Wireless 7265                                                     | 46        | 3.8%    |
| Intel Wireless 8260                                                     | 42        | 3.47%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 41        | 3.39%   |
| Intel Wi-Fi 6 AX200                                                     | 34        | 2.81%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 33        | 2.73%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 26        | 2.15%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 25        | 2.07%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 24        | 1.98%   |
| Intel Wireless 3165                                                     | 24        | 1.98%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 19        | 1.57%   |
| Intel Centrino Advanced-N 6200                                          | 18        | 1.49%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 16        | 1.32%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 16        | 1.32%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 15        | 1.24%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 14        | 1.16%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 14        | 1.16%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 14        | 1.16%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 14        | 1.16%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 13        | 1.07%   |
| Intel WiFi Link 5100                                                    | 13        | 1.07%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 13        | 1.07%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 13        | 1.07%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 12        | 0.99%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 12        | 0.99%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 12        | 0.99%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 11        | 0.91%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 11        | 0.91%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 11        | 0.91%   |
| Intel Centrino Advanced-N 6235                                          | 11        | 0.91%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 10        | 0.83%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 10        | 0.83%   |
| Intel Wi-Fi 6 AX201                                                     | 10        | 0.83%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 10        | 0.83%   |
| Intel Centrino Wireless-N 2230                                          | 10        | 0.83%   |
| Broadcom BCM43142 802.11b/g/n                                           | 10        | 0.83%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 724       | 46.98%  |
| Intel                                  | 542       | 35.17%  |
| Qualcomm Atheros                       | 84        | 5.45%   |
| Broadcom                               | 69        | 4.48%   |
| Marvell Technology Group               | 34        | 2.21%   |
| Nvidia                                 | 25        | 1.62%   |
| Samsung Electronics                    | 18        | 1.17%   |
| Xiaomi                                 | 9         | 0.58%   |
| JMicron Technology                     | 9         | 0.58%   |
| Google                                 | 5         | 0.32%   |
| Silicon Integrated Systems [SiS]       | 4         | 0.26%   |
| Huawei Technologies                    | 4         | 0.26%   |
| Qualcomm                               | 2         | 0.13%   |
| OPPO Electronics                       | 2         | 0.13%   |
| MediaTek                               | 2         | 0.13%   |
| D-Link System                          | 2         | 0.13%   |
| VIA Technologies                       | 1         | 0.06%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.06%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.06%   |
| National Semiconductor                 | 1         | 0.06%   |
| Motorola PCS                           | 1         | 0.06%   |
| Aquantia                               | 1         | 0.06%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 593       | 38.09%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 111       | 7.13%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 103       | 6.62%   |
| Intel Ethernet Connection I217-LM                                 | 46        | 2.95%   |
| Intel I211 Gigabit Network Connection                             | 37        | 2.38%   |
| Intel Ethernet Connection (2) I219-LM                             | 33        | 2.12%   |
| Intel Ethernet Connection I219-LM                                 | 25        | 1.61%   |
| Nvidia MCP79 Ethernet                                             | 23        | 1.48%   |
| Intel Ethernet Connection (7) I219-V                              | 23        | 1.48%   |
| Intel 82577LM Gigabit Network Connection                          | 21        | 1.35%   |
| Intel Ethernet Connection (2) I219-V                              | 19        | 1.22%   |
| Intel 82574L Gigabit Network Connection                           | 19        | 1.22%   |
| Intel Ethernet Connection (4) I219-LM                             | 17        | 1.09%   |
| Intel Ethernet Connection I218-LM                                 | 15        | 0.96%   |
| Intel Ethernet Controller I225-V                                  | 14        | 0.9%    |
| Intel 82579V Gigabit Network Connection                           | 14        | 0.9%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 13        | 0.83%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 13        | 0.83%   |
| Intel Ethernet Connection I217-V                                  | 13        | 0.83%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 12        | 0.77%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 12        | 0.77%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 12        | 0.77%   |
| Intel 82566MM Gigabit Network Connection                          | 12        | 0.77%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 11        | 0.71%   |
| Intel Ethernet Connection (4) I219-V                              | 11        | 0.71%   |
| Intel Ethernet Connection (3) I218-LM                             | 11        | 0.71%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 11        | 0.71%   |
| Intel 82567LM Gigabit Network Connection                          | 11        | 0.71%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 10        | 0.64%   |
| Intel Ethernet Connection (6) I219-V                              | 9         | 0.58%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 8         | 0.51%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 7         | 0.45%   |
| Realtek RTL8125 2.5GbE Controller                                 | 7         | 0.45%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 7         | 0.45%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 7         | 0.45%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 7         | 0.45%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 6         | 0.39%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 6         | 0.39%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 6         | 0.39%   |
| Intel I210 Gigabit Network Connection                             | 6         | 0.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1492      | 56.64%  |
| WiFi     | 1103      | 41.88%  |
| Unknown  | 27        | 1.03%   |
| Modem    | 12        | 0.46%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1225      | 64.3%   |
| WiFi     | 668       | 35.07%  |
| Unknown  | 7         | 0.37%   |
| Modem    | 5         | 0.26%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 916       | 56.23%  |
| 1     | 663       | 40.7%   |
| 3     | 30        | 1.84%   |
| 0     | 16        | 0.98%   |
| 4     | 4         | 0.25%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1566      | 95.2%   |
| Yes  | 79        | 4.8%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 372       | 44.55%  |
| Apple                           | 69        | 8.26%   |
| Realtek Semiconductor           | 68        | 8.14%   |
| Broadcom                        | 67        | 8.02%   |
| Cambridge Silicon Radio         | 60        | 7.19%   |
| Qualcomm Atheros Communications | 58        | 6.95%   |
| IMC Networks                    | 27        | 3.23%   |
| Foxconn / Hon Hai               | 23        | 2.75%   |
| ASUSTek Computer                | 21        | 2.51%   |
| Lite-On Technology              | 20        | 2.4%    |
| Hewlett-Packard                 | 12        | 1.44%   |
| Dell                            | 11        | 1.32%   |
| Ralink                          | 8         | 0.96%   |
| Alps Electric                   | 4         | 0.48%   |
| TP-Link                         | 3         | 0.36%   |
| Integrated System Solution      | 3         | 0.36%   |
| Fujitsu                         | 2         | 0.24%   |
| Toshiba                         | 1         | 0.12%   |
| Silicon Wave                    | 1         | 0.12%   |
| Primax Electronics              | 1         | 0.12%   |
| MediaTek                        | 1         | 0.12%   |
| HTC (High Tech Computer)        | 1         | 0.12%   |
| Edimax Technology               | 1         | 0.12%   |
| Askey Computer                  | 1         | 0.12%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 207       | 24.7%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 60        | 7.16%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 37        | 4.42%   |
| Intel AX201 Bluetooth                                       | 33        | 3.94%   |
| Intel AX200 Bluetooth                                       | 32        | 3.82%   |
| Apple Bluetooth Host Controller                             | 26        | 3.1%    |
| Intel Wireless-AC 3168 Bluetooth                            | 25        | 2.98%   |
| Realtek Bluetooth Adapter                                   | 22        | 2.63%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 20        | 2.39%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 19        | 2.27%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 16        | 1.91%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 14        | 1.67%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 14        | 1.67%   |
| Realtek  Bluetooth 4.2 Adapter                              | 13        | 1.55%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 11        | 1.31%   |
| Apple Broadcom Built-in Bluetooth                           | 11        | 1.31%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 10        | 1.19%   |
| Realtek Bluetooth 4.0 Adapter                               | 9         | 1.07%   |
| Ralink RT3290 Bluetooth                                     | 8         | 0.95%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 8         | 0.95%   |
| Apple Built-in iSight (no firmware loaded)                  | 8         | 0.95%   |
| Realtek RTL8821A Bluetooth                                  | 7         | 0.84%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 7         | 0.84%   |
| Lite-On Atheros AR3012 Bluetooth                            | 7         | 0.84%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 7         | 0.84%   |
| Intel AX210 Bluetooth                                       | 7         | 0.84%   |
| IMC Networks Realtek Bluetooth Adapter                      | 6         | 0.72%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 6         | 0.72%   |
| ASUS USB-BT500                                              | 6         | 0.72%   |
| Realtek RTL8723B Bluetooth                                  | 5         | 0.6%    |
| Qualcomm Atheros Dell Wireless 1703 Bluetooth               | 5         | 0.6%    |
| HP Broadcom 2070 Bluetooth Combo                            | 5         | 0.6%    |
| Dell DW375 Bluetooth Module                                 | 5         | 0.6%    |
| Broadcom BCM20702A0 Bluetooth 4.0                           | 5         | 0.6%    |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]          | 5         | 0.6%    |
| Lite-On Qualcomm Atheros Bluetooth 4.0 + HS                 | 4         | 0.48%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 4         | 0.48%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 4         | 0.48%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                 | 4         | 0.48%   |
| ASUS Broadcom BCM20702A0 Bluetooth                          | 4         | 0.48%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1259      | 58.67%  |
| AMD                              | 385       | 17.94%  |
| Nvidia                           | 339       | 15.8%   |
| C-Media Electronics              | 43        | 2%      |
| Texas Instruments                | 18        | 0.84%   |
| GN Netcom                        | 10        | 0.47%   |
| Creative Labs                    | 9         | 0.42%   |
| Generalplus Technology           | 6         | 0.28%   |
| Logitech                         | 5         | 0.23%   |
| SteelSeries ApS                  | 4         | 0.19%   |
| Silicon Integrated Systems [SiS] | 4         | 0.19%   |
| JMTek                            | 4         | 0.19%   |
| Hewlett-Packard                  | 4         | 0.19%   |
| Creative Technology              | 4         | 0.19%   |
| Yamaha                           | 3         | 0.14%   |
| Realtek Semiconductor            | 3         | 0.14%   |
| Kingston Technology              | 3         | 0.14%   |
| XMOS                             | 2         | 0.09%   |
| VIA Technologies                 | 2         | 0.09%   |
| Razer USA                        | 2         | 0.09%   |
| Google                           | 2         | 0.09%   |
| Focusrite-Novation               | 2         | 0.09%   |
| BEHRINGER International          | 2         | 0.09%   |
| ASUSTek Computer                 | 2         | 0.09%   |
| Unknown                          | 2         | 0.09%   |
| ZOOM                             | 1         | 0.05%   |
| Steinberg Soft-und Hardware      | 1         | 0.05%   |
| RME                              | 1         | 0.05%   |
| Plantronics                      | 1         | 0.05%   |
| Phison Electronics               | 1         | 0.05%   |
| OPPO Electronics                 | 1         | 0.05%   |
| Nektar                           | 1         | 0.05%   |
| Lenovo                           | 1         | 0.05%   |
| KTMicro                          | 1         | 0.05%   |
| KORG                             | 1         | 0.05%   |
| HECATE G2 GAMING HEADSET         | 1         | 0.05%   |
| Harman                           | 1         | 0.05%   |
| Griffin Technology               | 1         | 0.05%   |
| Giga-Byte Technology             | 1         | 0.05%   |
| GEMBIRD                          | 1         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 165       | 6.52%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 136       | 5.38%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 130       | 5.14%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 94        | 3.72%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 89        | 3.52%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 77        | 3.04%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 72        | 2.85%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 67        | 2.65%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 64        | 2.53%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 61        | 2.41%   |
| Intel 8 Series HD Audio Controller                                                                | 59        | 2.33%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 57        | 2.25%   |
| Intel Cannon Lake PCH cAVS                                                                        | 57        | 2.25%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 55        | 2.17%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 47        | 1.86%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 46        | 1.82%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 45        | 1.78%   |
| AMD FCH Azalia Controller                                                                         | 41        | 1.62%   |
| Intel Broadwell-U Audio Controller                                                                | 39        | 1.54%   |
| Intel 200 Series PCH HD Audio                                                                     | 39        | 1.54%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 36        | 1.42%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 36        | 1.42%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 35        | 1.38%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 33        | 1.3%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 29        | 1.15%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 25        | 0.99%   |
| Nvidia MCP79 High Definition Audio                                                                | 25        | 0.99%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 22        | 0.87%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 22        | 0.87%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 21        | 0.83%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 21        | 0.83%   |
| Nvidia High Definition Audio Controller                                                           | 19        | 0.75%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 19        | 0.75%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 19        | 0.75%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 19        | 0.75%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 18        | 0.71%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 18        | 0.71%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 17        | 0.67%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 16        | 0.63%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 16        | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 364       | 18.89%  |
| SK hynix            | 279       | 14.48%  |
| Kingston            | 257       | 13.34%  |
| Unknown             | 202       | 10.48%  |
| Micron Technology   | 170       | 8.82%   |
| Crucial             | 112       | 5.81%   |
| Corsair             | 71        | 3.68%   |
| Unknown             | 59        | 3.06%   |
| G.Skill             | 57        | 2.96%   |
| Elpida              | 40        | 2.08%   |
| Ramaxel Technology  | 37        | 1.92%   |
| A-DATA Technology   | 37        | 1.92%   |
| Nanya Technology    | 36        | 1.87%   |
| Smart               | 23        | 1.19%   |
| Team                | 22        | 1.14%   |
| Transcend           | 18        | 0.93%   |
| Patriot             | 16        | 0.83%   |
| Unknown (ABCD)      | 10        | 0.52%   |
| Apacer              | 9         | 0.47%   |
| Teikon              | 8         | 0.42%   |
| Avant               | 8         | 0.42%   |
| PNY                 | 6         | 0.31%   |
| GOODRAM             | 6         | 0.31%   |
| AMD                 | 6         | 0.31%   |
| Smart Brazil        | 5         | 0.26%   |
| High Bridge         | 5         | 0.26%   |
| ASint Technology    | 5         | 0.26%   |
| Atermiter           | 4         | 0.21%   |
| Silicon Power       | 3         | 0.16%   |
| Kingmax             | 3         | 0.16%   |
| Toshiba             | 2         | 0.1%    |
| SHARETRONIC         | 2         | 0.1%    |
| Sesame              | 2         | 0.1%    |
| Multilaser          | 2         | 0.1%    |
| Goldkey             | 2         | 0.1%    |
| GeIL                | 2         | 0.1%    |
| 48spaces            | 2         | 0.1%    |
| Wodposit            | 1         | 0.05%   |
| V-GeN               | 1         | 0.05%   |
| Unknown (D386)      | 1         | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Unknown                                                | 59        | 2.85%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s  | 22        | 1.06%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s             | 21        | 1.01%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s | 17        | 0.82%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s  | 16        | 0.77%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s | 14        | 0.68%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s  | 13        | 0.63%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s | 12        | 0.58%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s  | 12        | 0.58%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                   | 11        | 0.53%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s  | 11        | 0.53%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                   | 10        | 0.48%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s  | 10        | 0.48%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s | 9         | 0.43%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 1333MT/s  | 9         | 0.43%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s  | 9         | 0.43%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s               | 8         | 0.39%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s             | 8         | 0.39%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s  | 8         | 0.39%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s  | 8         | 0.39%   |
| Unknown RAM Module 4GB SODIMM DDR3                     | 7         | 0.34%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s           | 7         | 0.34%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s | 7         | 0.34%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s | 7         | 0.34%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s  | 7         | 0.34%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s  | 7         | 0.34%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s  | 7         | 0.34%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s    | 7         | 0.34%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3200MT/s   | 7         | 0.34%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s            | 6         | 0.29%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s              | 6         | 0.29%   |
| Unknown RAM Module 2GB SODIMM DDR2                     | 6         | 0.29%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3200MT/s    | 6         | 0.29%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s | 6         | 0.29%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s | 6         | 0.29%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s            | 6         | 0.29%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s | 6         | 0.29%   |
| Micron RAM 16ATF2G64HZ-2G6E1 16GB SODIMM DDR4 2667MT/s | 6         | 0.29%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s    | 6         | 0.29%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s            | 5         | 0.24%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 754       | 46.83%  |
| DDR4    | 577       | 35.84%  |
| DDR2    | 139       | 8.63%   |
| Unknown | 67        | 4.16%   |
| SDRAM   | 24        | 1.49%   |
| LPDDR3  | 18        | 1.12%   |
| LPDDR4  | 17        | 1.06%   |
| DDR     | 7         | 0.43%   |
| DRAM    | 3         | 0.19%   |
| DDR5    | 3         | 0.19%   |
| RAM     | 1         | 0.06%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 890       | 55.28%  |
| DIMM         | 655       | 40.68%  |
| Row Of Chips | 32        | 1.99%   |
| Chip         | 17        | 1.06%   |
| Unknown      | 9         | 0.56%   |
| FB-DIMM      | 4         | 0.25%   |
| RIMM         | 3         | 0.19%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 636       | 35.14%  |
| 8192  | 549       | 30.33%  |
| 2048  | 380       | 20.99%  |
| 16384 | 156       | 8.62%   |
| 1024  | 63        | 3.48%   |
| 32768 | 23        | 1.27%   |
| 512   | 2         | 0.11%   |
| 1491  | 1         | 0.06%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 436       | 24.96%  |
| 1333    | 241       | 13.8%   |
| 2400    | 177       | 10.13%  |
| 2667    | 145       | 8.3%    |
| 3200    | 137       | 7.84%   |
| 2133    | 130       | 7.44%   |
| 667     | 89        | 5.09%   |
| 800     | 67        | 3.84%   |
| 1067    | 65        | 3.72%   |
| 1334    | 54        | 3.09%   |
| Unknown | 45        | 2.58%   |
| 1867    | 33        | 1.89%   |
| 2666    | 26        | 1.49%   |
| 1066    | 23        | 1.32%   |
| 3600    | 12        | 0.69%   |
| 1866    | 11        | 0.63%   |
| 3000    | 9         | 0.52%   |
| 533     | 9         | 0.52%   |
| 400     | 8         | 0.46%   |
| 2048    | 4         | 0.23%   |
| 975     | 4         | 0.23%   |
| 333     | 4         | 0.23%   |
| 4800    | 3         | 0.17%   |
| 3733    | 3         | 0.17%   |
| 2933    | 3         | 0.17%   |
| 4267    | 2         | 0.11%   |
| 4400    | 1         | 0.06%   |
| 4266    | 1         | 0.06%   |
| 3400    | 1         | 0.06%   |
| 3333    | 1         | 0.06%   |
| 2866    | 1         | 0.06%   |
| 1639    | 1         | 0.06%   |
| 1200    | 1         | 0.06%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 8         | 36.36%  |
| Brother Industries    | 8         | 36.36%  |
| Lexmark International | 2         | 9.09%   |
| Seiko Epson           | 1         | 4.55%   |
| Ricoh                 | 1         | 4.55%   |
| Prolific Technology   | 1         | 4.55%   |
| Kyocera               | 1         | 4.55%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                                                                                                             | Computers | Percent |
|-------------------------------------------------------------------------------------------------------------------|-----------|---------|
| Seiko Epson USB2.0 Printer (Hi-speed)                                                                             | 1         | 4.35%   |
| Ricoh SP 112                                                                                                      | 1         | 4.35%   |
| Prolific PL2305 Parallel Port                                                                                     | 1         | 4.35%   |
| Lexmark International SINDOH A603_A608 Print                                                                      | 1         | 4.35%   |
| Lexmark International Lexmark MS710 Print                                                                         | 1         | 4.35%   |
| Kyocera FS-1025MFP                                                                                                | 1         | 4.35%   |
| HP LaserJet P3005                                                                                                 | 1         | 4.35%   |
| HP LaserJet 3390                                                                                                  | 1         | 4.35%   |
| HP LaserJet 2200                                                                                                  | 1         | 4.35%   |
| HP LaserJet 1200                                                                                                  | 1         | 4.35%   |
| HP LaserJet 1020                                                                                                  | 1         | 4.35%   |
| HP HP LaserJet P2035 HP Print                                                                                     | 1         | 4.35%   |
| HP HP LaserJet MFP E52645 LaserJet 0 LaserJet 0 LaserJet 1 LaserJet 1 LaserJet 2 LaserJet 2 LaserJet 3 LaserJet 3 | 1         | 4.35%   |
| HP DeskJet 5850c                                                                                                  | 1         | 4.35%   |
| HP Color LaserJet CP1215                                                                                          | 1         | 4.35%   |
| Brother MFC-L2685DW                                                                                               | 1         | 4.35%   |
| Brother MFC-J200                                                                                                  | 1         | 4.35%   |
| Brother MFC-7360N                                                                                                 | 1         | 4.35%   |
| Brother HL-L2310D series                                                                                          | 1         | 4.35%   |
| Brother HL-L2300D series                                                                                          | 1         | 4.35%   |
| Brother HL-1430 Laser Printer                                                                                     | 1         | 4.35%   |
| Brother DCP-J152W                                                                                                 | 1         | 4.35%   |
| Brother DCP-J100                                                                                                  | 1         | 4.35%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart_bsd/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Canon       | 6         | 85.71%  |
| Seiko Epson | 1         | 14.29%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart_bsd/scanner_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                                                             | 2         | 28.57%  |
| Seiko Epson WF-2860 Series EPSON Scanner USB2.0 Printer EPSON Utility USB2.0 Faxout | 1         | 14.29%  |
| Canon CanoScan LiDE 700F                                                            | 1         | 14.29%  |
| Canon CanoScan LiDE 220                                                             | 1         | 14.29%  |
| Canon CanoScan LiDE 120                                                             | 1         | 14.29%  |
| Canon CanoScan LiDE 100                                                             | 1         | 14.29%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 173       | 24.71%  |
| Bison Electronics                      | 68        | 9.71%   |
| Realtek Semiconductor                  | 58        | 8.29%   |
| Microdia                               | 58        | 8.29%   |
| IMC Networks                           | 57        | 8.14%   |
| Sunplus Innovation Technology          | 39        | 5.57%   |
| Suyin                                  | 25        | 3.57%   |
| Logitech                               | 23        | 3.29%   |
| Syntek                                 | 19        | 2.71%   |
| Cheng Uei Precision Industry (Foxlink) | 19        | 2.71%   |
| Lite-On Technology                     | 18        | 2.57%   |
| Apple                                  | 18        | 2.57%   |
| Quanta                                 | 16        | 2.29%   |
| Alcor Micro                            | 15        | 2.14%   |
| Silicon Motion                         | 12        | 1.71%   |
| Z-Star Microelectronics                | 11        | 1.57%   |
| Lenovo                                 | 10        | 1.43%   |
| Luxvisions Innotech Limited            | 7         | 1%      |
| ALi                                    | 7         | 1%      |
| Importek                               | 5         | 0.71%   |
| ARC International                      | 4         | 0.57%   |
| Ricoh                                  | 3         | 0.43%   |
| Arkmicro Technologies                  | 3         | 0.43%   |
| Supreme Electronics                    | 2         | 0.29%   |
| Primax Electronics                     | 2         | 0.29%   |
| Intel                                  | 2         | 0.29%   |
| Hewlett-Packard                        | 2         | 0.29%   |
| Genesys Logic                          | 2         | 0.29%   |
| Generalplus Technology                 | 2         | 0.29%   |
| GEMBIRD                                | 2         | 0.29%   |
| DigiTech                               | 2         | 0.29%   |
| Creative Technology                    | 2         | 0.29%   |
| Y Media                                | 1         | 0.14%   |
| ValueHD                                | 1         | 0.14%   |
| USB Camera                             | 1         | 0.14%   |
| Unknown                                | 1         | 0.14%   |
| Trust                                  | 1         | 0.14%   |
| Tripath Technology                     | 1         | 0.14%   |
| SHENZHEN AONI ELECTRONIC               | 1         | 0.14%   |
| Nanchang BYD Electronics               | 1         | 0.14%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                     | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Chicony Integrated Camera                 | 43        | 6.11%   |
| Bison Integrated Camera                   | 24        | 3.41%   |
| Microdia Integrated_Webcam_HD             | 15        | 2.13%   |
| Realtek Integrated_Webcam_HD              | 14        | 1.99%   |
| Realtek USB 2.0 PC Camera                 | 12        | 1.7%    |
| Chicony HD WebCam                         | 12        | 1.7%    |
| Sunplus Integrated_Webcam_HD              | 11        | 1.56%   |
| Lite-On Integrated Camera                 | 11        | 1.56%   |
| IMC Networks Integrated Camera            | 11        | 1.56%   |
| Bison Lenovo EasyCamera                   | 11        | 1.56%   |
| Chicony Lenovo Integrated Camera (0.3MP)  | 10        | 1.42%   |
| Microdia Integrated Webcam                | 9         | 1.28%   |
| Apple FaceTime HD Camera (Built-in)       | 9         | 1.28%   |
| Syntek Lenovo EasyCamera                  | 8         | 1.14%   |
| Realtek USB Camera                        | 8         | 1.14%   |
| IMC Networks Realtek PC Camera            | 8         | 1.14%   |
| Apple FaceTime HD Camera                  | 8         | 1.14%   |
| Microdia Dell Laptop Integrated Webcam HD | 7         | 0.99%   |
| Logitech Webcam C270                      | 7         | 0.99%   |
| Chicony HP HD Webcam [Fixed]              | 7         | 0.99%   |
| Chicony FJ Camera                         | 7         | 0.99%   |
| Syntek EasyCamera                         | 6         | 0.85%   |
| Microdia USB 2.0 Camera                   | 6         | 0.85%   |
| IMC Networks EasyCamera                   | 6         | 0.85%   |
| Chicony Realtek DMFT RGB                  | 6         | 0.85%   |
| Chicony Lenovo EasyCamera                 | 6         | 0.85%   |
| Bison HD Webcam                           | 6         | 0.85%   |
| Suyin Integrated_Webcam_HD                | 5         | 0.71%   |
| Lenovo Integrated Webcam [R5U877]         | 5         | 0.71%   |
| Chicony USB2.0 VGA UVC WebCam             | 5         | 0.71%   |
| Chicony Integrated Camera [ThinkPad]      | 5         | 0.71%   |
| Bison ThinkPad Integrated Camera          | 5         | 0.71%   |
| Alcor Micro USB 2.0 Camera                | 5         | 0.71%   |
| Suyin Acer/HP Integrated Webcam [CN0314]  | 4         | 0.57%   |
| Realtek Dell EasyCamera                   | 4         | 0.57%   |
| Quanta HP TrueVision HD Camera            | 4         | 0.57%   |
| Microdia Laptop_Integrated_Webcam_HD      | 4         | 0.57%   |
| Logitech HD Pro Webcam C920               | 4         | 0.57%   |
| Lenovo Integrated Webcam                  | 4         | 0.57%   |
| IMC Networks UVC VGA Webcam               | 4         | 0.57%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 64        | 44.44%  |
| AuthenTec                  | 20        | 13.89%  |
| Upek                       | 18        | 12.5%   |
| Synaptics                  | 11        | 7.64%   |
| STMicroelectronics         | 9         | 6.25%   |
| Elan Microelectronics      | 7         | 4.86%   |
| Broadcom                   | 6         | 4.17%   |
| Shenzhen Goodix Technology | 4         | 2.78%   |
| LighTuning Technology      | 4         | 2.78%   |
| Fingerprint Cards          | 1         | 0.69%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 16        | 11.11%  |
| Validity Sensors VFS 5011 fingerprint sensor                                 | 14        | 9.72%   |
| Validity Sensors VFS495 Fingerprint Reader                                   | 10        | 6.94%   |
| Validity Sensors Synaptics WBDI                                              | 9         | 6.25%   |
| STMicroelectronics Fingerprint Reader                                        | 9         | 6.25%   |
| Validity Sensors VFS5011 Fingerprint Reader                                  | 8         | 5.56%   |
| Elan Fingerprint Sensor                                                      | 7         | 4.86%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 6         | 4.17%   |
| AuthenTec AES2810                                                            | 5         | 3.47%   |
| AuthenTec AES1600                                                            | 5         | 3.47%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 4         | 2.78%   |
| Validity Sensors Fingerprint scanner                                         | 4         | 2.78%   |
| Synaptics WBDI Fingerprint Reader USB 086                                    | 4         | 2.78%   |
| AuthenTec AES1660                                                            | 4         | 2.78%   |
| Validity Sensors VFS491                                                      | 3         | 2.08%   |
| Validity Sensors VFS471 Fingerprint Reader                                   | 3         | 2.08%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 3         | 2.08%   |
| Shenzhen Goodix Fingerprint Reader                                           | 3         | 2.08%   |
| AuthenTec AES2501 Fingerprint Sensor                                         | 3         | 2.08%   |
| Validity Sensors VFS451 Fingerprint Reader                                   | 2         | 1.39%   |
| Validity Sensors VFS101 Fingerprint Reader                                   | 2         | 1.39%   |
| Validity Sensors Swipe Fingerprint Sensor                                    | 2         | 1.39%   |
| Upek TCS5B Fingerprint sensor                                                | 2         | 1.39%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                             | 2         | 1.39%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                  | 2         | 1.39%   |
| AuthenTec AES2660                                                            | 2         | 1.39%   |
| Validity Sensors VFS301 Fingerprint Reader                                   | 1         | 0.69%   |
| Validity Sensors VFS Fingerprint sensor                                      | 1         | 0.69%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint   | 1         | 0.69%   |
| Synaptics WBDI                                                               | 1         | 0.69%   |
| Synaptics UWP WBDI Device                                                    | 1         | 0.69%   |
| Shenzhen Goodix Fingerprint Reader SGX                                       | 1         | 0.69%   |
| LighTuning Fingerprint Sensor                                                | 1         | 0.69%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                    | 1         | 0.69%   |
| Fingerprint Cards FPC Fingerprint Reader                                     | 1         | 0.69%   |
| AuthenTec AES1660 Fingerprint Sensor                                         | 1         | 0.69%   |

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
| 1     | 665       | 40.16%  |
| 0     | 422       | 25.48%  |
| 2     | 372       | 22.46%  |
| 3     | 142       | 8.57%   |
| 4     | 44        | 2.66%   |
| 5     | 9         | 0.54%   |
| 6     | 2         | 0.12%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 1022      | 53.23%  |
| Net/wireless             | 253       | 13.18%  |
| Card reader              | 217       | 11.3%   |
| Bluetooth                | 157       | 8.18%   |
| Fingerprint reader       | 141       | 7.34%   |
| Sound                    | 46        | 2.4%    |
| Firewire controller      | 29        | 1.51%   |
| Network                  | 22        | 1.15%   |
| Storage                  | 15        | 0.78%   |
| Net/ethernet             | 9         | 0.47%   |
| Storage/raid             | 4         | 0.21%   |
| Dvb card                 | 4         | 0.21%   |
| Storage/nvme             | 1         | 0.05%   |

