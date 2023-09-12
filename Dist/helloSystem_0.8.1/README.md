helloSystem 0.8.1 - Tested Hardware & Statistics
------------------------------------------------

A project to collect tested hardware configurations for helloSystem 0.8.1.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/helloSystem_0.8.1/Desktop/README.md) and [notebooks](/Dist/helloSystem_0.8.1/Notebook/README.md).

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

Total: 411

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Lenovo        | ThinkPad X240 20AMA1Y3UK    | Notebook    | [8277297743](https://bsd-hardware.info/?probe=8277297743) | Sep 05, 2023 |
| HP            | G62                         | Notebook    | [b4777b6ba5](https://bsd-hardware.info/?probe=b4777b6ba5) | Sep 04, 2023 |
| Toshiba       | QOSMIO X775                 | Notebook    | [d92a05ab1d](https://bsd-hardware.info/?probe=d92a05ab1d) | Sep 04, 2023 |
| Samsung       | 270E5J/2570EJ               | Notebook    | [3feb685296](https://bsd-hardware.info/?probe=3feb685296) | Sep 03, 2023 |
| Fujitsu       | LIFEBOOK S935               | Notebook    | [a6cfe011fe](https://bsd-hardware.info/?probe=a6cfe011fe) | Sep 02, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [57925dc8bb](https://bsd-hardware.info/?probe=57925dc8bb) | Sep 02, 2023 |
| Dell          | 0YXT71 A02                  | Desktop     | [b887caabe7](https://bsd-hardware.info/?probe=b887caabe7) | Aug 31, 2023 |
| HP            | 2000                        | Notebook    | [6d9c442ae6](https://bsd-hardware.info/?probe=6d9c442ae6) | Aug 31, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [a308c3a87b](https://bsd-hardware.info/?probe=a308c3a87b) | Aug 31, 2023 |
| HP            | Pavilion dv3500             | Notebook    | [0c3f84b285](https://bsd-hardware.info/?probe=0c3f84b285) | Aug 29, 2023 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | Notebook    | [e74ef1d37c](https://bsd-hardware.info/?probe=e74ef1d37c) | Aug 29, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [3dab6f4044](https://bsd-hardware.info/?probe=3dab6f4044) | Aug 28, 2023 |
| MSI           | H110M PRO-VD                | Desktop     | [dcbd4ebf8f](https://bsd-hardware.info/?probe=dcbd4ebf8f) | Aug 27, 2023 |
| NVN-ED01      | Unknown                     | Notebook    | [dba43e889a](https://bsd-hardware.info/?probe=dba43e889a) | Aug 25, 2023 |
| AZW           | U59                         | Desktop     | [e08540ab36](https://bsd-hardware.info/?probe=e08540ab36) | Aug 25, 2023 |
| Lenovo        | ThinkPad P50 20EN0009MS     | Notebook    | [4b3fcfa17e](https://bsd-hardware.info/?probe=4b3fcfa17e) | Aug 25, 2023 |
| ASUSTek       | S500CA                      | Notebook    | [019366a664](https://bsd-hardware.info/?probe=019366a664) | Aug 25, 2023 |
| MSI           | MAG B460M BAZOOKA           | Desktop     | [7cf9279c14](https://bsd-hardware.info/?probe=7cf9279c14) | Aug 22, 2023 |
| HP            | 82A5                        | Mini pc     | [4b56141a3b](https://bsd-hardware.info/?probe=4b56141a3b) | Aug 21, 2023 |
| Lenovo        | ThinkPad T450 20BUS0370P    | Notebook    | [5fefc051e1](https://bsd-hardware.info/?probe=5fefc051e1) | Aug 20, 2023 |
| Gigabyte      | GA-880GA-UD3H               | Desktop     | [35eb7df9a7](https://bsd-hardware.info/?probe=35eb7df9a7) | Aug 20, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [7e1d475356](https://bsd-hardware.info/?probe=7e1d475356) | Aug 18, 2023 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [df095be4ba](https://bsd-hardware.info/?probe=df095be4ba) | Aug 18, 2023 |
| Daten Tecn... | DH110MXV                    | Desktop     | [bdd9c72e7c](https://bsd-hardware.info/?probe=bdd9c72e7c) | Aug 18, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [c12a76c083](https://bsd-hardware.info/?probe=c12a76c083) | Aug 16, 2023 |
| ASUSTek       | X553MA                      | Notebook    | [7334765d8a](https://bsd-hardware.info/?probe=7334765d8a) | Aug 16, 2023 |
| ASUSTek       | GL753VD                     | Notebook    | [8ccbffdd73](https://bsd-hardware.info/?probe=8ccbffdd73) | Aug 15, 2023 |
| ASUSTek       | P5G41T-M LX2/BR             | Desktop     | [f25db83457](https://bsd-hardware.info/?probe=f25db83457) | Aug 15, 2023 |
| Lenovo        | ThinkPad X200 7458WNZ       | Notebook    | [3ac1d60240](https://bsd-hardware.info/?probe=3ac1d60240) | Aug 12, 2023 |
| Lenovo        | ThinkPad T60 1951CZ1        | Notebook    | [46766bc381](https://bsd-hardware.info/?probe=46766bc381) | Aug 11, 2023 |
| Intel         | JSL MRD                     | Desktop     | [ca7024f423](https://bsd-hardware.info/?probe=ca7024f423) | Aug 10, 2023 |
| Acer          | Aspire V3-371               | Notebook    | [21c262aadb](https://bsd-hardware.info/?probe=21c262aadb) | Aug 09, 2023 |
| Acer          | Aspire V3-371               | Notebook    | [68bceee682](https://bsd-hardware.info/?probe=68bceee682) | Aug 09, 2023 |
| HP            | 82C0                        | Mini pc     | [124e7b14df](https://bsd-hardware.info/?probe=124e7b14df) | Aug 07, 2023 |
| Intel         | H81                         | Desktop     | [80f40918ce](https://bsd-hardware.info/?probe=80f40918ce) | Aug 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [9c01814bdc](https://bsd-hardware.info/?probe=9c01814bdc) | Aug 07, 2023 |
| HP            | 0AACh                       | Desktop     | [5997b1de3e](https://bsd-hardware.info/?probe=5997b1de3e) | Aug 06, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [d3fac2e3fe](https://bsd-hardware.info/?probe=d3fac2e3fe) | Aug 06, 2023 |
| ASUSTek       | M4A88TD-M/USB3              | Desktop     | [ce95634a53](https://bsd-hardware.info/?probe=ce95634a53) | Aug 06, 2023 |
| Compaq        | Presario CQ-17              | Notebook    | [f97feb2db0](https://bsd-hardware.info/?probe=f97feb2db0) | Aug 04, 2023 |
| ASUSTek       | P5QL PRO                    | Desktop     | [dccefef8eb](https://bsd-hardware.info/?probe=dccefef8eb) | Aug 04, 2023 |
| HP            | 82C0                        | Mini pc     | [6fa14d3439](https://bsd-hardware.info/?probe=6fa14d3439) | Aug 03, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [6496fe0cfe](https://bsd-hardware.info/?probe=6496fe0cfe) | Aug 03, 2023 |
| Gigabyte      | Z170-HD3 DDR3-CF            | Desktop     | [f66f032ffe](https://bsd-hardware.info/?probe=f66f032ffe) | Aug 01, 2023 |
| Lenovo        | IdeaPad S210 Touch 20257    | Notebook    | [1e372622c1](https://bsd-hardware.info/?probe=1e372622c1) | Jul 31, 2023 |
| Lenovo        | ThinkPad X270 20HNA04GCD    | Notebook    | [6547f4a73b](https://bsd-hardware.info/?probe=6547f4a73b) | Jul 31, 2023 |
| Lenovo        | ThinkPad X230 23202DG       | Notebook    | [f8ade878ce](https://bsd-hardware.info/?probe=f8ade878ce) | Jul 30, 2023 |
| HP            | Notebook                    | Notebook    | [360790274a](https://bsd-hardware.info/?probe=360790274a) | Jul 29, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [53e133857b](https://bsd-hardware.info/?probe=53e133857b) | Jul 29, 2023 |
| HP            | Pavilion g6                 | Notebook    | [bdd2349f1c](https://bsd-hardware.info/?probe=bdd2349f1c) | Jul 28, 2023 |
| HP            | 83E1                        | Desktop     | [b211795736](https://bsd-hardware.info/?probe=b211795736) | Jul 27, 2023 |
| Dell          | Latitude 5480               | Notebook    | [e1521ed9d2](https://bsd-hardware.info/?probe=e1521ed9d2) | Jul 26, 2023 |
| HP            | 339A                        | Desktop     | [b770568bae](https://bsd-hardware.info/?probe=b770568bae) | Jul 25, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [60dac781b2](https://bsd-hardware.info/?probe=60dac781b2) | Jul 24, 2023 |
| ASRock        | H61M-VG3                    | Desktop     | [5cebf2275e](https://bsd-hardware.info/?probe=5cebf2275e) | Jul 24, 2023 |
| ASUSTek       | P5QL PRO                    | Desktop     | [b51bcdf3a5](https://bsd-hardware.info/?probe=b51bcdf3a5) | Jul 20, 2023 |
| Acer          | Aspire 4736Z                | Notebook    | [bccf97f694](https://bsd-hardware.info/?probe=bccf97f694) | Jul 20, 2023 |
| ASUSTek       | 1015PX                      | Notebook    | [dc06c76cf9](https://bsd-hardware.info/?probe=dc06c76cf9) | Jul 19, 2023 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [5fcffa5bd6](https://bsd-hardware.info/?probe=5fcffa5bd6) | Jul 19, 2023 |
| HP            | 81C5 MVB                    | Desktop     | [1a4fbc384d](https://bsd-hardware.info/?probe=1a4fbc384d) | Jul 19, 2023 |
| ASUSTek       | K42Jr                       | Notebook    | [256168572a](https://bsd-hardware.info/?probe=256168572a) | Jul 18, 2023 |
| Samsung       | RC530/RC730                 | Notebook    | [b76e5e8a87](https://bsd-hardware.info/?probe=b76e5e8a87) | Jul 17, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [3a5b0b3193](https://bsd-hardware.info/?probe=3a5b0b3193) | Jul 17, 2023 |
| Lenovo        | ThinkPad R14 Gen 4 21E5A... | Notebook    | [e0fc7135e5](https://bsd-hardware.info/?probe=e0fc7135e5) | Jul 15, 2023 |
| ECS           | H61H2-M17                   | Desktop     | [aa4679bee7](https://bsd-hardware.info/?probe=aa4679bee7) | Jul 14, 2023 |
| ASRock        | H61M-GS                     | Desktop     | [502952e73f](https://bsd-hardware.info/?probe=502952e73f) | Jul 11, 2023 |
| ASUSTek       | X541UVK                     | Notebook    | [17f58b70e4](https://bsd-hardware.info/?probe=17f58b70e4) | Jul 10, 2023 |
| ASRock        | A300M-STX                   | Desktop     | [5d896a607e](https://bsd-hardware.info/?probe=5d896a607e) | Jul 06, 2023 |
| HP            | Compaq Presario CQ61        | Notebook    | [d070292855](https://bsd-hardware.info/?probe=d070292855) | Jul 03, 2023 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [2053dbb697](https://bsd-hardware.info/?probe=2053dbb697) | Jul 03, 2023 |
| Lenovo        | ThinkPad T60 20076PU        | Notebook    | [cb47bfef12](https://bsd-hardware.info/?probe=cb47bfef12) | Jun 30, 2023 |
| HP            | 8055                        | Desktop     | [94df572de4](https://bsd-hardware.info/?probe=94df572de4) | Jun 29, 2023 |
| ASUSTek       | M2A-VM                      | Desktop     | [2d5a9bba42](https://bsd-hardware.info/?probe=2d5a9bba42) | Jun 28, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [17834256ca](https://bsd-hardware.info/?probe=17834256ca) | Jun 28, 2023 |
| Dell          | Latitude E4310              | Notebook    | [9cdd4909fe](https://bsd-hardware.info/?probe=9cdd4909fe) | Jun 24, 2023 |
| HP            | Laptop 15-ra0xx             | Notebook    | [8c31502b68](https://bsd-hardware.info/?probe=8c31502b68) | Jun 24, 2023 |
| HP            | EliteBook 750 G1            | Notebook    | [aba91c70d1](https://bsd-hardware.info/?probe=aba91c70d1) | Jun 24, 2023 |
| Dell          | Latitude 5490               | Notebook    | [b638c1b2b1](https://bsd-hardware.info/?probe=b638c1b2b1) | Jun 23, 2023 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [2dfabb3a28](https://bsd-hardware.info/?probe=2dfabb3a28) | Jun 23, 2023 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [b63efe1bc2](https://bsd-hardware.info/?probe=b63efe1bc2) | Jun 23, 2023 |
| LG Electro... | R590-K.AAA9BT               | Desktop     | [5c3ab65e8e](https://bsd-hardware.info/?probe=5c3ab65e8e) | Jun 23, 2023 |
| Acer          | Aspire 5749                 | Notebook    | [75ad2ddb6f](https://bsd-hardware.info/?probe=75ad2ddb6f) | Jun 22, 2023 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [29545a1054](https://bsd-hardware.info/?probe=29545a1054) | Jun 21, 2023 |
| Acer          | Aspire 5749                 | Notebook    | [1e91633580](https://bsd-hardware.info/?probe=1e91633580) | Jun 20, 2023 |
| HP            | Pavilion 15                 | Notebook    | [9ba6acdb4b](https://bsd-hardware.info/?probe=9ba6acdb4b) | Jun 18, 2023 |
| HP            | Stream Laptop 14-ds0xxx     | Notebook    | [81bbc73e72](https://bsd-hardware.info/?probe=81bbc73e72) | Jun 18, 2023 |
| ASUSTek       | P7P55D LE                   | Desktop     | [ea97ade85d](https://bsd-hardware.info/?probe=ea97ade85d) | Jun 17, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [d8079e6155](https://bsd-hardware.info/?probe=d8079e6155) | Jun 16, 2023 |
| MSI           | GE63 Raider RGB 8RE         | Notebook    | [ecdb80adc0](https://bsd-hardware.info/?probe=ecdb80adc0) | Jun 14, 2023 |
| HP            | Compaq 6830s                | Notebook    | [1a06917a0f](https://bsd-hardware.info/?probe=1a06917a0f) | Jun 14, 2023 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [76809610f9](https://bsd-hardware.info/?probe=76809610f9) | Jun 13, 2023 |
| Lenovo        | ThinkPad T440p 20AWS1CH0... | Notebook    | [b532f1ce9c](https://bsd-hardware.info/?probe=b532f1ce9c) | Jun 13, 2023 |
| Samsung       | R530/R730/R540              | Notebook    | [b007264caa](https://bsd-hardware.info/?probe=b007264caa) | Jun 11, 2023 |
| Dell          | 0X9X1W A00                  | Desktop     | [64825f4f71](https://bsd-hardware.info/?probe=64825f4f71) | Jun 08, 2023 |
| Dell          | 0X9X1W A00                  | Desktop     | [c9d8d9a491](https://bsd-hardware.info/?probe=c9d8d9a491) | Jun 08, 2023 |
| Lenovo        | S10-3                       | Notebook    | [f874a66e78](https://bsd-hardware.info/?probe=f874a66e78) | Jun 05, 2023 |
| Lenovo        | S10-3                       | Notebook    | [b76483ab8b](https://bsd-hardware.info/?probe=b76483ab8b) | Jun 05, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [e1a7d29d74](https://bsd-hardware.info/?probe=e1a7d29d74) | Jun 04, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [d0d9de7cf3](https://bsd-hardware.info/?probe=d0d9de7cf3) | Jun 04, 2023 |
| Dell          | 0TKM9Y A00                  | Mini pc     | [fdd78a8f45](https://bsd-hardware.info/?probe=fdd78a8f45) | Jun 03, 2023 |
| Dell          | 0WR7PY A03                  | Desktop     | [c8496622be](https://bsd-hardware.info/?probe=c8496622be) | Jun 03, 2023 |
| Dell          | 0WR7PY A03                  | Desktop     | [b9f7e3e209](https://bsd-hardware.info/?probe=b9f7e3e209) | Jun 03, 2023 |
| Panasonic     | CF-NX1GDHYS                 | Notebook    | [fb1f293997](https://bsd-hardware.info/?probe=fb1f293997) | Jun 02, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [1bb0436fe5](https://bsd-hardware.info/?probe=1bb0436fe5) | May 30, 2023 |
| Intel         | H81                         | Desktop     | [e0e15704fc](https://bsd-hardware.info/?probe=e0e15704fc) | May 29, 2023 |
| Apple         | MacBookPro10,2              | Notebook    | [c274e2c9db](https://bsd-hardware.info/?probe=c274e2c9db) | May 29, 2023 |
| HP            | 21D0                        | Desktop     | [4a10865d28](https://bsd-hardware.info/?probe=4a10865d28) | May 28, 2023 |
| HP            | 21D0                        | Desktop     | [e3d20826b3](https://bsd-hardware.info/?probe=e3d20826b3) | May 28, 2023 |
| Fujitsu       | Unknown                     | Notebook    | [3b5c9ab914](https://bsd-hardware.info/?probe=3b5c9ab914) | May 27, 2023 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [1d43f61471](https://bsd-hardware.info/?probe=1d43f61471) | May 27, 2023 |
| Unknown       | 1.0                         | Desktop     | [12d6c7934e](https://bsd-hardware.info/?probe=12d6c7934e) | May 27, 2023 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [53a2d5356d](https://bsd-hardware.info/?probe=53a2d5356d) | May 26, 2023 |
| HP            | x360 310 G2 PC              | Convertible | [05bd720b57](https://bsd-hardware.info/?probe=05bd720b57) | May 26, 2023 |
| Timi          | TM1701                      | Notebook    | [1dd768a721](https://bsd-hardware.info/?probe=1dd768a721) | May 25, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [a0bff43f5c](https://bsd-hardware.info/?probe=a0bff43f5c) | May 23, 2023 |
| AZW           | GK55                        | Desktop     | [ef90c15915](https://bsd-hardware.info/?probe=ef90c15915) | May 23, 2023 |
| ASUSTek       | K42Jc                       | Notebook    | [3da2928a08](https://bsd-hardware.info/?probe=3da2928a08) | May 23, 2023 |
| Google        | Sentry                      | Notebook    | [107124dd66](https://bsd-hardware.info/?probe=107124dd66) | May 22, 2023 |
| ASRock        | Z68 Pro3 Gen3               | Desktop     | [0a03cd86a0](https://bsd-hardware.info/?probe=0a03cd86a0) | May 21, 2023 |
| Sony          | VPCEG15FB                   | Notebook    | [8777493861](https://bsd-hardware.info/?probe=8777493861) | May 21, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [41ce3c5d11](https://bsd-hardware.info/?probe=41ce3c5d11) | May 21, 2023 |
| ASUSTek       | Z87M-PLUS                   | Desktop     | [58da7daed7](https://bsd-hardware.info/?probe=58da7daed7) | May 20, 2023 |
| Packard Be... | EasyNote LJ65               | Notebook    | [36d3e7aaf7](https://bsd-hardware.info/?probe=36d3e7aaf7) | May 19, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [8f3c5de741](https://bsd-hardware.info/?probe=8f3c5de741) | May 19, 2023 |
| Gigabyte      | Z490 VISION G               | Desktop     | [976e31bfbc](https://bsd-hardware.info/?probe=976e31bfbc) | May 16, 2023 |
| Gigabyte      | Z490 VISION G               | Desktop     | [8eeec83a4e](https://bsd-hardware.info/?probe=8eeec83a4e) | May 16, 2023 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [bda308bc8c](https://bsd-hardware.info/?probe=bda308bc8c) | May 14, 2023 |
| Sony          | SVF14A15CBB                 | Notebook    | [4ada2dca25](https://bsd-hardware.info/?probe=4ada2dca25) | May 14, 2023 |
| Lenovo        | B570e HuronRiver Platfor... | Notebook    | [256915976d](https://bsd-hardware.info/?probe=256915976d) | May 12, 2023 |
| Dell          | 0WN7Y6 A01                  | Desktop     | [a232411c74](https://bsd-hardware.info/?probe=a232411c74) | May 12, 2023 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [3d889e8b9b](https://bsd-hardware.info/?probe=3d889e8b9b) | May 11, 2023 |
| Intel         | NUC6i5SYB H81131-503        | Mini pc     | [4eea72e4a6](https://bsd-hardware.info/?probe=4eea72e4a6) | May 11, 2023 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [fe053db6c7](https://bsd-hardware.info/?probe=fe053db6c7) | May 10, 2023 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [16ca4a2aa0](https://bsd-hardware.info/?probe=16ca4a2aa0) | May 10, 2023 |
| ASRock        | Q1900M                      | Desktop     | [c779034e79](https://bsd-hardware.info/?probe=c779034e79) | May 09, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [da07885adb](https://bsd-hardware.info/?probe=da07885adb) | May 09, 2023 |
| HP            | Laptop 14-bs0xx             | Notebook    | [98ea66d6e8](https://bsd-hardware.info/?probe=98ea66d6e8) | May 07, 2023 |
| Dell          | 07F37C A00                  | Desktop     | [a23a95f97a](https://bsd-hardware.info/?probe=a23a95f97a) | May 07, 2023 |
| ASRock        | J4125-ITX                   | Desktop     | [6e34c8b22a](https://bsd-hardware.info/?probe=6e34c8b22a) | May 05, 2023 |
| Intel         | DH87RL AAG74240-400         | Desktop     | [7833b60865](https://bsd-hardware.info/?probe=7833b60865) | May 05, 2023 |
| Dell          | 0252PH A04                  | Desktop     | [0cc9ef6521](https://bsd-hardware.info/?probe=0cc9ef6521) | May 03, 2023 |
| Dell          | 0252PH A04                  | Desktop     | [acaf59c3d5](https://bsd-hardware.info/?probe=acaf59c3d5) | May 03, 2023 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [3773da7851](https://bsd-hardware.info/?probe=3773da7851) | May 03, 2023 |
| HP            | Compaq Presario CQ50        | Notebook    | [f296048a29](https://bsd-hardware.info/?probe=f296048a29) | May 03, 2023 |
| HP            | 82B4                        | Desktop     | [244817e203](https://bsd-hardware.info/?probe=244817e203) | May 02, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [a5a1ca2ee6](https://bsd-hardware.info/?probe=a5a1ca2ee6) | May 02, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [e4e2bba5fb](https://bsd-hardware.info/?probe=e4e2bba5fb) | May 02, 2023 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [270284972d](https://bsd-hardware.info/?probe=270284972d) | Apr 29, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [52174cc0ba](https://bsd-hardware.info/?probe=52174cc0ba) | Apr 27, 2023 |
| Dell          | 0252PH A04                  | Desktop     | [f497e66dec](https://bsd-hardware.info/?probe=f497e66dec) | Apr 27, 2023 |
| Acer          | Spin SP314-21               | Convertible | [f5debc3ef8](https://bsd-hardware.info/?probe=f5debc3ef8) | Apr 27, 2023 |
| HP            | 8056                        | Desktop     | [44fb168511](https://bsd-hardware.info/?probe=44fb168511) | Apr 26, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [4c7f33d6a9](https://bsd-hardware.info/?probe=4c7f33d6a9) | Apr 25, 2023 |
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
| Gigabyte      | B250M-Gaming 3-CF           | Desktop     | [592e08cdd2](https://bsd-hardware.info/?probe=592e08cdd2) | Apr 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon 34487... | Notebook    | [cec90ddd1b](https://bsd-hardware.info/?probe=cec90ddd1b) | Apr 08, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [f3ac765863](https://bsd-hardware.info/?probe=f3ac765863) | Apr 08, 2023 |
| Dell          | XPS 13 9343                 | Notebook    | [8354aed46e](https://bsd-hardware.info/?probe=8354aed46e) | Apr 07, 2023 |
| Acer          | Veriton M6620G              | Desktop     | [13f7e5c23b](https://bsd-hardware.info/?probe=13f7e5c23b) | Apr 07, 2023 |
| Fujitsu       | CELSIUS H920                | Notebook    | [0551eecbcc](https://bsd-hardware.info/?probe=0551eecbcc) | Apr 06, 2023 |
| Acer          | Aspire 5250                 | Notebook    | [385751dbc3](https://bsd-hardware.info/?probe=385751dbc3) | Apr 06, 2023 |
| Lenovo        | Tilapia CRB                 | Desktop     | [977f089665](https://bsd-hardware.info/?probe=977f089665) | Apr 05, 2023 |
| Gigabyte      | B360M D2V                   | Desktop     | [6429eebbaa](https://bsd-hardware.info/?probe=6429eebbaa) | Apr 05, 2023 |
| Google        | Wolf                        | Notebook    | [2546416afd](https://bsd-hardware.info/?probe=2546416afd) | Apr 05, 2023 |
| HP            | Laptop 15-bw0xx             | Notebook    | [93ea83eef5](https://bsd-hardware.info/?probe=93ea83eef5) | Apr 03, 2023 |
| Lenovo        | G570 20079                  | Notebook    | [76cc1653c3](https://bsd-hardware.info/?probe=76cc1653c3) | Apr 03, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [92d0571176](https://bsd-hardware.info/?probe=92d0571176) | Apr 03, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [096620cfac](https://bsd-hardware.info/?probe=096620cfac) | Apr 03, 2023 |
| Lenovo        | ThinkBook 14-IML 20RV       | Notebook    | [48b0a1024e](https://bsd-hardware.info/?probe=48b0a1024e) | Apr 02, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [760a744b91](https://bsd-hardware.info/?probe=760a744b91) | Apr 02, 2023 |
| ASUSTek       | X58C                        | Notebook    | [dad28a9d36](https://bsd-hardware.info/?probe=dad28a9d36) | Apr 01, 2023 |
| Fujitsu       | CELSIUS H920                | Notebook    | [e6300dc691](https://bsd-hardware.info/?probe=e6300dc691) | Mar 31, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [bcaaed4d6d](https://bsd-hardware.info/?probe=bcaaed4d6d) | Mar 31, 2023 |
| DNS           | W9x0LU                      | Notebook    | [6539659387](https://bsd-hardware.info/?probe=6539659387) | Mar 31, 2023 |
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
| Dell          | Inspiron 7437               | Notebook    | [2c4de59558](https://bsd-hardware.info/?probe=2c4de59558) | Mar 27, 2023 |
| Lenovo        | IdeaPad S210 20256          | Notebook    | [2e22ee87c3](https://bsd-hardware.info/?probe=2e22ee87c3) | Mar 27, 2023 |
| Lenovo        | ThinkPad T430 2349G5P       | Notebook    | [9ea67d3893](https://bsd-hardware.info/?probe=9ea67d3893) | Mar 27, 2023 |
| Dell          | Latitude 5420               | Notebook    | [4e22bbc131](https://bsd-hardware.info/?probe=4e22bbc131) | Mar 26, 2023 |
| MSI           | 870-G45                     | Desktop     | [19cbb6e0f3](https://bsd-hardware.info/?probe=19cbb6e0f3) | Mar 26, 2023 |
| LG Electro... | E500-L.A2M4A2               | Notebook    | [8dab794233](https://bsd-hardware.info/?probe=8dab794233) | Mar 26, 2023 |
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
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [c07b0a75e5](https://bsd-hardware.info/?probe=c07b0a75e5) | Mar 20, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [71d2b7317c](https://bsd-hardware.info/?probe=71d2b7317c) | Mar 19, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [36348fa16f](https://bsd-hardware.info/?probe=36348fa16f) | Mar 19, 2023 |
| Apple         | MacBookPro5,1               | Notebook    | [9e300b5797](https://bsd-hardware.info/?probe=9e300b5797) | Mar 19, 2023 |
| Toshiba       | Satellite P300              | Notebook    | [81b7ca608e](https://bsd-hardware.info/?probe=81b7ca608e) | Mar 19, 2023 |
| Lenovo        | ThinkPad T520 4242PN3       | Notebook    | [3ea33f0cad](https://bsd-hardware.info/?probe=3ea33f0cad) | Mar 19, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [e35600705f](https://bsd-hardware.info/?probe=e35600705f) | Mar 19, 2023 |
| Lenovo        | ThinkPad L380 Yoga 20M8S... | Convertible | [40a4d98b9c](https://bsd-hardware.info/?probe=40a4d98b9c) | Mar 19, 2023 |
| Samsung       | R520/R522/R620              | Notebook    | [096d52b83d](https://bsd-hardware.info/?probe=096d52b83d) | Mar 18, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [be9a45f529](https://bsd-hardware.info/?probe=be9a45f529) | Mar 18, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [acc1970543](https://bsd-hardware.info/?probe=acc1970543) | Mar 18, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [a365a5b411](https://bsd-hardware.info/?probe=a365a5b411) | Mar 18, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [6f2790802d](https://bsd-hardware.info/?probe=6f2790802d) | Mar 18, 2023 |
| ASUSTek       | P6X58D-E                    | Desktop     | [ec05209185](https://bsd-hardware.info/?probe=ec05209185) | Mar 18, 2023 |
| Fujitsu       | LIFEBOOK AH530              | Notebook    | [50a5ed6b41](https://bsd-hardware.info/?probe=50a5ed6b41) | Mar 18, 2023 |
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
| ASUSTek       | 1201N                       | Notebook    | [5dc595eb79](https://bsd-hardware.info/?probe=5dc595eb79) | Mar 05, 2023 |
| ASUSTek       | 1201N                       | Notebook    | [daa787f637](https://bsd-hardware.info/?probe=daa787f637) | Mar 05, 2023 |
| HP            | EliteBook 2730p             | Notebook    | [3c404c9d20](https://bsd-hardware.info/?probe=3c404c9d20) | Mar 05, 2023 |
| Dell          | Inspiron 15 3515            | Notebook    | [b480a98b22](https://bsd-hardware.info/?probe=b480a98b22) | Feb 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | Notebook    | [95c66df5a4](https://bsd-hardware.info/?probe=95c66df5a4) | Feb 24, 2023 |
| Plaisio       | Turbo X                     | Notebook    | [e0a8a02bb9](https://bsd-hardware.info/?probe=e0a8a02bb9) | Feb 23, 2023 |
| Dell          | 0C27VV A02                  | Desktop     | [5899533edd](https://bsd-hardware.info/?probe=5899533edd) | Feb 23, 2023 |
| Intel         | DG41TY AAE47335-300         | Desktop     | [7c1727d55a](https://bsd-hardware.info/?probe=7c1727d55a) | Feb 22, 2023 |
| Dell          | 0C27VV A02                  | Desktop     | [a10df954b7](https://bsd-hardware.info/?probe=a10df954b7) | Feb 22, 2023 |
| Huanan        | X99-TF GAMING V3.0          | Desktop     | [59db63fd9d](https://bsd-hardware.info/?probe=59db63fd9d) | Feb 22, 2023 |
| Huanan        | X99-TF GAMING V3.0          | Desktop     | [50dce9bf96](https://bsd-hardware.info/?probe=50dce9bf96) | Feb 19, 2023 |
| Lenovo        | ThinkPad T520 4243F39       | Notebook    | [d8ba5b3157](https://bsd-hardware.info/?probe=d8ba5b3157) | Feb 19, 2023 |
| Lenovo        | ThinkPad T520 4243F39       | Notebook    | [820596f359](https://bsd-hardware.info/?probe=820596f359) | Feb 18, 2023 |
| Lenovo        | ThinkPad T430u 33522D5      | Notebook    | [d5bbbb8cbe](https://bsd-hardware.info/?probe=d5bbbb8cbe) | Feb 17, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [8820014583](https://bsd-hardware.info/?probe=8820014583) | Feb 15, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [592ca6bab5](https://bsd-hardware.info/?probe=592ca6bab5) | Feb 15, 2023 |
| Lenovo        | ThinkPad T520 4243F39       | Notebook    | [9137c7933c](https://bsd-hardware.info/?probe=9137c7933c) | Feb 13, 2023 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 350       | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| helloDesktop | 346       | 98.86%  |
| GNOME        | 2         | 0.57%   |
| KDE5         | 1         | 0.29%   |
| JWM          | 1         | 0.29%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 350       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| SLiM | 350       | 99.72%  |
| SDDM | 1         | 0.28%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 157       | 44.48%  |
| fr_FR   | 75        | 21.25%  |
| ru_RU   | 24        | 6.8%    |
| de_DE   | 23        | 6.52%   |
| es_ES   | 18        | 5.1%    |
| Unknown | 13        | 3.68%   |
| pt_BR   | 10        | 2.83%   |
| pl_PL   | 9         | 2.55%   |
| it_IT   | 8         | 2.27%   |
| nl_NL   | 3         | 0.85%   |
| jp_JP   | 3         | 0.85%   |
| zh_CN   | 2         | 0.57%   |
| ko_KR   | 2         | 0.57%   |
| pt_PT   | 1         | 0.28%   |
| pt      | 1         | 0.28%   |
| fr      | 1         | 0.28%   |
| fi_FI   | 1         | 0.28%   |
| es      | 1         | 0.28%   |
| en      | 1         | 0.28%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 347       | 99.14%  |
| BIOS | 3         | 0.86%   |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type   | Computers | Percent |
|--------|-----------|---------|
| Cd9660 | 186       | 52.54%  |
| Zfs    | 168       | 47.46%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 347       | 99.14%  |
| MBR  | 3         | 0.86%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 67        | 19.14%  |
| ASUSTek Computer    | 51        | 14.57%  |
| Hewlett-Packard     | 46        | 13.14%  |
| Dell                | 35        | 10%     |
| Gigabyte Technology | 25        | 7.14%   |
| Acer                | 15        | 4.29%   |
| MSI                 | 13        | 3.71%   |
| Intel               | 11        | 3.14%   |
| Fujitsu             | 9         | 2.57%   |
| ASRock              | 9         | 2.57%   |
| Toshiba             | 8         | 2.29%   |
| Samsung Electronics | 8         | 2.29%   |
| Apple               | 8         | 2.29%   |
| Unknown             | 5         | 1.43%   |
| Sony                | 4         | 1.14%   |
| Google              | 4         | 1.14%   |
| T-bao               | 2         | 0.57%   |
| Packard Bell        | 2         | 0.57%   |
| LG Electronics      | 2         | 0.57%   |
| Fujitsu Siemens     | 2         | 0.57%   |
| Foxconn             | 2         | 0.57%   |
| AZW                 | 2         | 0.57%   |
| TUXEDO              | 1         | 0.29%   |
| Timi                | 1         | 0.29%   |
| Plaisio             | 1         | 0.29%   |
| Pegatron            | 1         | 0.29%   |
| Panasonic           | 1         | 0.29%   |
| NVN-ED01            | 1         | 0.29%   |
| Microsoft           | 1         | 0.29%   |
| Medion              | 1         | 0.29%   |
| Irbis               | 1         | 0.29%   |
| IGEL Technology     | 1         | 0.29%   |
| HUAWEI              | 1         | 0.29%   |
| Huanan              | 1         | 0.29%   |
| ECS                 | 1         | 0.29%   |
| Dynabook Europe     | 1         | 0.29%   |
| DNS                 | 1         | 0.29%   |
| Daten Tecnologia    | 1         | 0.29%   |
| Compaq              | 1         | 0.29%   |
| Biostar             | 1         | 0.29%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                              | Computers | Percent |
|-----------------------------------|-----------|---------|
| Unknown                           | 8         | 2.29%   |
| T-bao MINI PC                     | 2         | 0.57%   |
| MSI MS-7788                       | 2         | 0.57%   |
| Intel H81                         | 2         | 0.57%   |
| HP Laptop 14-bs0xx                | 2         | 0.57%   |
| HP EliteDesk 800 G2 DM 35W        | 2         | 0.57%   |
| HP Compaq Elite 8300 USDT         | 2         | 0.57%   |
| Dell OptiPlex 7010                | 2         | 0.57%   |
| ASUS ROG STRIX B550-F GAMING      | 2         | 0.57%   |
| ASUS PRIME B250M-A                | 2         | 0.57%   |
| ASUS All Series                   | 2         | 0.57%   |
| Acer Spin SP314-21                | 2         | 0.57%   |
| TUXEDO Aura 15 Gen1               | 1         | 0.29%   |
| Toshiba Satellite P300            | 1         | 0.29%   |
| Toshiba Satellite L675D           | 1         | 0.29%   |
| Toshiba Satellite L50-B           | 1         | 0.29%   |
| Toshiba Satellite L40             | 1         | 0.29%   |
| Toshiba Satellite C845            | 1         | 0.29%   |
| Toshiba Satellite A200            | 1         | 0.29%   |
| Toshiba QOSMIO X775               | 1         | 0.29%   |
| Toshiba PORTEGE R700              | 1         | 0.29%   |
| Timi TM1701                       | 1         | 0.29%   |
| Sony VPCEG15FB                    | 1         | 0.29%   |
| Sony VGN-FZ19VN                   | 1         | 0.29%   |
| Sony SVL2412Z1EB                  | 1         | 0.29%   |
| Sony SVF14A15CBB                  | 1         | 0.29%   |
| Samsung RC530/RC730               | 1         | 0.29%   |
| Samsung R530/R730/R540            | 1         | 0.29%   |
| Samsung R520/R522/R620            | 1         | 0.29%   |
| Samsung R468/R418                 | 1         | 0.29%   |
| Samsung 370E4K                    | 1         | 0.29%   |
| Samsung 305E4A/305E5A/305E7A      | 1         | 0.29%   |
| Samsung 275E4E/275E5E             | 1         | 0.29%   |
| Samsung 270E5J/2570EJ             | 1         | 0.29%   |
| Plaisio Turbo X                   | 1         | 0.29%   |
| Pegatron Compaq dx2450 Microtower | 1         | 0.29%   |
| Panasonic CF-NX1GDHYS             | 1         | 0.29%   |
| Packard Bell EasyNote LJ65        | 1         | 0.29%   |
| Packard Bell DOT SE               | 1         | 0.29%   |
| MSI MS-7C95                       | 1         | 0.29%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 40        | 11.43%  |
| ASUS PRIME              | 12        | 3.43%   |
| Dell Latitude           | 11        | 3.14%   |
| Lenovo IdeaPad          | 9         | 2.57%   |
| HP Pavilion             | 9         | 2.57%   |
| Dell Inspiron           | 9         | 2.57%   |
| Lenovo ThinkCentre      | 8         | 2.29%   |
| HP Compaq               | 8         | 2.29%   |
| Dell OptiPlex           | 8         | 2.29%   |
| ASUS ROG                | 8         | 2.29%   |
| Unknown                 | 8         | 2.29%   |
| Toshiba Satellite       | 6         | 1.71%   |
| HP Laptop               | 6         | 1.71%   |
| Acer Aspire             | 6         | 1.71%   |
| HP EliteDesk            | 5         | 1.43%   |
| HP EliteBook            | 4         | 1.14%   |
| HP ProDesk              | 3         | 0.86%   |
| Fujitsu LIFEBOOK        | 3         | 0.86%   |
| Dell Precision          | 3         | 0.86%   |
| T-bao MINI              | 2         | 0.57%   |
| MSI MS-7788             | 2         | 0.57%   |
| Lenovo Legion           | 2         | 0.57%   |
| Intel H81               | 2         | 0.57%   |
| Gigabyte B450M          | 2         | 0.57%   |
| Fujitsu Siemens ESPRIMO | 2         | 0.57%   |
| Fujitsu ESPRIMO         | 2         | 0.57%   |
| Dell Vostro             | 2         | 0.57%   |
| ASUS VivoBook           | 2         | 0.57%   |
| ASUS TUF                | 2         | 0.57%   |
| ASUS All                | 2         | 0.57%   |
| Acer Veriton            | 2         | 0.57%   |
| Acer Spin               | 2         | 0.57%   |
| TUXEDO Aura             | 1         | 0.29%   |
| Toshiba QOSMIO          | 1         | 0.29%   |
| Toshiba PORTEGE         | 1         | 0.29%   |
| Timi TM1701             | 1         | 0.29%   |
| Sony VPCEG15FB          | 1         | 0.29%   |
| Sony VGN-FZ19VN         | 1         | 0.29%   |
| Sony SVL2412Z1EB        | 1         | 0.29%   |
| Sony SVF14A15CBB        | 1         | 0.29%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2022    | 33        | 9.43%   |
| 2012    | 32        | 9.14%   |
| 2020    | 29        | 8.29%   |
| 2013    | 29        | 8.29%   |
| 2021    | 28        | 8%      |
| 2011    | 25        | 7.14%   |
| 2019    | 23        | 6.57%   |
| 2010    | 21        | 6%      |
| 2017    | 20        | 5.71%   |
| 2016    | 19        | 5.43%   |
| 2018    | 16        | 4.57%   |
| 2014    | 16        | 4.57%   |
| 2009    | 15        | 4.29%   |
| 2008    | 13        | 3.71%   |
| 2015    | 11        | 3.14%   |
| 2023    | 8         | 2.29%   |
| 2007    | 7         | 2%      |
| 2006    | 4         | 1.14%   |
| Unknown | 1         | 0.29%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 174       | 49.71%  |
| Desktop     | 161       | 46%     |
| Mini pc     | 6         | 1.71%   |
| Convertible | 5         | 1.43%   |
| All in one  | 2         | 0.57%   |
| Tablet      | 1         | 0.29%   |
| Server      | 1         | 0.29%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 344       | 98.29%  |
| Yes  | 6         | 1.71%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 126       | 36%     |
| 4.01-8.0    | 87        | 24.86%  |
| 16.01-24.0  | 81        | 23.14%  |
| 32.01-64.0  | 23        | 6.57%   |
| 2.01-3.0    | 18        | 5.14%   |
| 3.01-4.0    | 6         | 1.71%   |
| 64.01-256.0 | 5         | 1.43%   |
| 24.01-32.0  | 3         | 0.86%   |
| 0.51-1.0    | 1         | 0.29%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 188       | 53.41%  |
| 0.51-1.0 | 117       | 33.24%  |
| 1.01-2.0 | 32        | 9.09%   |
| 2.01-3.0 | 13        | 3.69%   |
| 3.01-4.0 | 2         | 0.57%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 216       | 61.54%  |
| 2      | 65        | 18.52%  |
| 3      | 27        | 7.69%   |
| 0      | 26        | 7.41%   |
| 5      | 7         | 1.99%   |
| 4      | 4         | 1.14%   |
| 9      | 2         | 0.57%   |
| 6      | 2         | 0.57%   |
| 13     | 1         | 0.28%   |
| 7      | 1         | 0.28%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 226       | 64.57%  |
| Yes       | 124       | 35.43%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 321       | 91.71%  |
| No        | 29        | 8.29%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 234       | 66.67%  |
| No        | 117       | 33.33%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 175       | 50%     |
| No        | 175       | 50%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country            | Computers | Percent |
|--------------------|-----------|---------|
| USA                | 50        | 14.29%  |
| Russia             | 37        | 10.57%  |
| Germany            | 28        | 8%      |
| Brazil             | 22        | 6.29%   |
| Poland             | 20        | 5.71%   |
| Spain              | 16        | 4.57%   |
| Italy              | 13        | 3.71%   |
| France             | 13        | 3.71%   |
| Canada             | 12        | 3.43%   |
| UK                 | 10        | 2.86%   |
| Romania            | 9         | 2.57%   |
| Indonesia          | 9         | 2.57%   |
| Hungary            | 9         | 2.57%   |
| Australia          | 9         | 2.57%   |
| Turkey             | 6         | 1.71%   |
| Mexico             | 6         | 1.71%   |
| China              | 6         | 1.71%   |
| Serbia             | 5         | 1.43%   |
| India              | 5         | 1.43%   |
| Ukraine            | 4         | 1.14%   |
| South Korea        | 4         | 1.14%   |
| Netherlands        | 4         | 1.14%   |
| Bulgaria           | 4         | 1.14%   |
| Belgium            | 4         | 1.14%   |
| Peru               | 3         | 0.86%   |
| Argentina          | 3         | 0.86%   |
| Switzerland        | 2         | 0.57%   |
| Sweden             | 2         | 0.57%   |
| Slovenia           | 2         | 0.57%   |
| Portugal           | 2         | 0.57%   |
| Lithuania          | 2         | 0.57%   |
| Japan              | 2         | 0.57%   |
| Israel             | 2         | 0.57%   |
| Dominican Republic | 2         | 0.57%   |
| Chile              | 2         | 0.57%   |
| Belarus            | 2         | 0.57%   |
| Thailand           | 1         | 0.29%   |
| Syria              | 1         | 0.29%   |
| Slovakia           | 1         | 0.29%   |
| San Marino         | 1         | 0.29%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Sao Paulo          | 5         | 1.42%   |
| Moscow             | 5         | 1.42%   |
| Berlin             | 5         | 1.42%   |
| Sydney             | 4         | 1.13%   |
| St. Jean Baptiste  | 4         | 1.13%   |
| St Petersburg      | 4         | 1.13%   |
| Wroclaw            | 3         | 0.85%   |
| Warsaw             | 3         | 0.85%   |
| Paris              | 3         | 0.85%   |
| Milan              | 3         | 0.85%   |
| Budapest           | 3         | 0.85%   |
| Brooklyn           | 3         | 0.85%   |
| Belgrade           | 3         | 0.85%   |
| Woodbridge         | 2         | 0.57%   |
| Valencia           | 2         | 0.57%   |
| Sofia              | 2         | 0.57%   |
| Shenzhen           | 2         | 0.57%   |
| Santo Domingo Este | 2         | 0.57%   |
| Santiago           | 2         | 0.57%   |
| Penza              | 2         | 0.57%   |
| Pensacola          | 2         | 0.57%   |
| Odesa              | 2         | 0.57%   |
| Montreal           | 2         | 0.57%   |
| Melbourne          | 2         | 0.57%   |
| Madrid             | 2         | 0.57%   |
| Lisbon             | 2         | 0.57%   |
| Krasnodar          | 2         | 0.57%   |
| Krakow             | 2         | 0.57%   |
| Kirov              | 2         | 0.57%   |
| Istanbul           | 2         | 0.57%   |
| Irkutsk            | 2         | 0.57%   |
| Dresden            | 2         | 0.57%   |
| Curitiba           | 2         | 0.57%   |
| Buenos Aires       | 2         | 0.57%   |
| Brisbane           | 2         | 0.57%   |
| Ankara             | 2         | 0.57%   |
| Zurich             | 1         | 0.28%   |
| Zhengzhou          | 1         | 0.28%   |
| Zarautz            | 1         | 0.28%   |
| Yuseong-gu         | 1         | 0.28%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 72        | 89     | 15.58%  |
| WDC                 | 65        | 92     | 14.07%  |
| Seagate             | 57        | 74     | 12.34%  |
| Kingston            | 40        | 40     | 8.66%   |
| Toshiba             | 34        | 40     | 7.36%   |
| SanDisk             | 25        | 25     | 5.41%   |
| Hitachi             | 20        | 21     | 4.33%   |
| Crucial             | 19        | 23     | 4.11%   |
| China               | 10        | 11     | 2.16%   |
| A-DATA Technology   | 10        | 11     | 2.16%   |
| Micron Technology   | 8         | 9      | 1.73%   |
| Intel               | 8         | 8      | 1.73%   |
| HGST                | 7         | 10     | 1.52%   |
| Transcend           | 6         | 6      | 1.3%    |
| SK hynix            | 5         | 5      | 1.08%   |
| Patriot             | 5         | 5      | 1.08%   |
| KingSpec            | 5         | 5      | 1.08%   |
| SPCC                | 4         | 4      | 0.87%   |
| Maxtor              | 4         | 4      | 0.87%   |
| Gigabyte Technology | 4         | 5      | 0.87%   |
| Team                | 3         | 3      | 0.65%   |
| PNY                 | 3         | 3      | 0.65%   |
| OCZ                 | 3         | 3      | 0.65%   |
| Intenso             | 3         | 3      | 0.65%   |
| GOODRAM             | 3         | 3      | 0.65%   |
| Netac               | 2         | 2      | 0.43%   |
| Fujitsu             | 2         | 2      | 0.43%   |
| BHT                 | 2         | 2      | 0.43%   |
| Apple               | 2         | 2      | 0.43%   |
| WALRAM              | 1         | 1      | 0.22%   |
| Verbatim            | 1         | 1      | 0.22%   |
| Vaseky              | 1         | 1      | 0.22%   |
| V-GeN               | 1         | 1      | 0.22%   |
| UMIS                | 1         | 1      | 0.22%   |
| TAMMUZ              | 1         | 1      | 0.22%   |
| Silicon Motion      | 1         | 1      | 0.22%   |
| SETHRISE            | 1         | 1      | 0.22%   |
| QUANTUM             | 1         | 1      | 0.22%   |
| Plextor             | 1         | 1      | 0.22%   |
| Pioneer             | 1         | 1      | 0.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB          | 10        | 1.95%   |
| Samsung SSD 860 EVO 500GB            | 8         | 1.56%   |
| Seagate ST500DM002-1BD142 500GB      | 5         | 0.97%   |
| Samsung SSD 850 EVO 250GB            | 5         | 0.97%   |
| Toshiba MQ01ABF050 500GB             | 4         | 0.78%   |
| Seagate ST3500418AS 500GB            | 4         | 0.78%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 4         | 0.78%   |
| Seagate ST1000DM010-2EP102 1TB       | 4         | 0.78%   |
| Samsung SSD 980 1TB                  | 4         | 0.78%   |
| Crucial CT500MX500SSD1 500GB         | 4         | 0.78%   |
| Crucial CT480BX500SSD1 480GB         | 4         | 0.78%   |
| WDC WD10EZEX-08WN4A0 1TB             | 3         | 0.58%   |
| Seagate ST2000DM008-2FR102 2TB       | 3         | 0.58%   |
| Samsung SSD 970 EVO Plus 1TB         | 3         | 0.58%   |
| Samsung SSD 870 EVO 500GB            | 3         | 0.58%   |
| Kingston SHFS37A240G 240GB           | 3         | 0.58%   |
| Kingston SA400S37120G 120GB          | 3         | 0.58%   |
| Crucial CT240BX500SSD1 240GB         | 3         | 0.58%   |
| WDC WDS240G2G0A-00JH30 240GB         | 2         | 0.39%   |
| WDC WDS120G2G0A-00JH30 120GB         | 2         | 0.39%   |
| WDC WD5000AAKX-08U6AA0 500GB         | 2         | 0.39%   |
| WDC WD20EZRX-00D8PB0 2TB             | 2         | 0.39%   |
| WDC WD20EFRX-68EUZN0 2TB             | 2         | 0.39%   |
| WDC WD10EZEX-60WN4A1 1TB             | 2         | 0.39%   |
| WDC WD10EZEX-60WN4A0 1TB             | 2         | 0.39%   |
| WDC PC SN520 SDAPNUW-128G-1014 128GB | 2         | 0.39%   |
| Toshiba MQ01ABD100 1TB               | 2         | 0.39%   |
| Toshiba HDWD110 1TB                  | 2         | 0.39%   |
| Toshiba DT01ACA100 1TB               | 2         | 0.39%   |
| Toshiba DT01ACA050 500GB             | 2         | 0.39%   |
| SPCC Solid State Disk 128GB          | 2         | 0.39%   |
| Seagate ST9500325AS 500GB            | 2         | 0.39%   |
| Seagate ST9250410AS 250GB            | 2         | 0.39%   |
| Seagate ST500LT012-1DG142 500GB      | 2         | 0.39%   |
| Seagate ST500LM000-1EJ162 500GB      | 2         | 0.39%   |
| Seagate ST1000DM003-1CH162 1TB       | 2         | 0.39%   |
| SanDisk SSD PLUS 120GB               | 2         | 0.39%   |
| SanDisk pSSD 256GB                   | 2         | 0.39%   |
| Samsung SSD 980 PRO 500GB            | 2         | 0.39%   |
| Samsung SSD 980 500GB                | 2         | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 57        | 74     | 31.67%  |
| WDC                 | 51        | 75     | 28.33%  |
| Toshiba             | 29        | 34     | 16.11%  |
| Hitachi             | 20        | 21     | 11.11%  |
| Samsung Electronics | 8         | 10     | 4.44%   |
| HGST                | 7         | 10     | 3.89%   |
| Maxtor              | 4         | 4      | 2.22%   |
| Fujitsu             | 2         | 2      | 1.11%   |
| QUANTUM             | 1         | 1      | 0.56%   |
| Apple               | 1         | 1      | 0.56%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 35        | 42     | 16.91%  |
| Kingston            | 30        | 30     | 14.49%  |
| SanDisk             | 25        | 25     | 12.08%  |
| Crucial             | 18        | 21     | 8.7%    |
| China               | 10        | 11     | 4.83%   |
| WDC                 | 9         | 10     | 4.35%   |
| A-DATA Technology   | 6         | 6      | 2.9%    |
| Patriot             | 5         | 5      | 2.42%   |
| KingSpec            | 5         | 5      | 2.42%   |
| Intel               | 5         | 5      | 2.42%   |
| Transcend           | 4         | 4      | 1.93%   |
| Toshiba             | 4         | 5      | 1.93%   |
| SPCC                | 3         | 3      | 1.45%   |
| PNY                 | 3         | 3      | 1.45%   |
| OCZ                 | 3         | 3      | 1.45%   |
| Micron Technology   | 3         | 3      | 1.45%   |
| Intenso             | 3         | 3      | 1.45%   |
| GOODRAM             | 3         | 3      | 1.45%   |
| Gigabyte Technology | 3         | 4      | 1.45%   |
| Team                | 2         | 2      | 0.97%   |
| BHT                 | 2         | 2      | 0.97%   |
| WALRAM              | 1         | 1      | 0.48%   |
| Verbatim            | 1         | 1      | 0.48%   |
| Vaseky              | 1         | 1      | 0.48%   |
| V-GeN               | 1         | 1      | 0.48%   |
| TAMMUZ              | 1         | 1      | 0.48%   |
| SK hynix            | 1         | 1      | 0.48%   |
| SETHRISE            | 1         | 1      | 0.48%   |
| Plextor             | 1         | 1      | 0.48%   |
| Pioneer             | 1         | 1      | 0.48%   |
| Philips             | 1         | 1      | 0.48%   |
| Palit               | 1         | 1      | 0.48%   |
| Netac               | 1         | 1      | 0.48%   |
| MidasForce          | 1         | 1      | 0.48%   |
| LITEONIT            | 1         | 1      | 0.48%   |
| Kston               | 1         | 1      | 0.48%   |
| KIOXIA-EXCERIA      | 1         | 1      | 0.48%   |
| Kingmax             | 1         | 1      | 0.48%   |
| HEORIADY            | 1         | 1      | 0.48%   |
| Goldenfir           | 1         | 1      | 0.48%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 174       | 221    | 42.34%  |
| HDD  | 160       | 232    | 38.93%  |
| NVMe | 77        | 88     | 18.73%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 288       | 453    | 78.9%   |
| NVMe | 77        | 88     | 21.1%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 247       | 321    | 72.43%  |
| 0.51-1.0   | 62        | 77     | 18.18%  |
| 1.01-2.0   | 17        | 31     | 4.99%   |
| 3.01-4.0   | 8         | 10     | 2.35%   |
| 2.01-3.0   | 3         | 6      | 0.88%   |
| 4.01-10.0  | 3         | 7      | 0.88%   |
| 10.01-20.0 | 1         | 1      | 0.29%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 1-20       | 176       | 49.86%  |
| 101-250    | 54        | 15.3%   |
| 251-500    | 47        | 13.31%  |
| 51-100     | 46        | 13.03%  |
| 501-1000   | 18        | 5.1%    |
| 21-50      | 9         | 2.55%   |
| Unknown    | 2         | 0.57%   |
| 1001-2000  | 1         | 0.28%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Computers | Percent |
|---------|-----------|---------|
| 1-20    | 344       | 98.29%  |
| 21-50   | 2         | 0.57%   |
| Unknown | 2         | 0.57%   |
| 251-500 | 1         | 0.29%   |
| 101-250 | 1         | 0.29%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                                     | Computers | Drives | Percent |
|-------------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB                 | 2         | 2      | 2.5%    |
| Seagate ST500LM000-1EJ162 500GB           | 2         | 2      | 2.5%    |
| Seagate ST1000LM024 HN-M101MBB 1TB        | 2         | 3      | 2.5%    |
| Hitachi HTS542525K9A300 250GB             | 2         | 2      | 2.5%    |
| WDC WD800JD-75MSA3 80GB                   | 1         | 1      | 1.25%   |
| WDC WD6400BPVT-22HXZT3 640GB              | 1         | 1      | 1.25%   |
| WDC WD5000AAKX-08U6AA0 500GB              | 1         | 1      | 1.25%   |
| WDC WD5000AAKX-00ERMA0 500GB              | 1         | 1      | 1.25%   |
| WDC WD30PURZ-85AKKY0 3TB                  | 1         | 1      | 1.25%   |
| WDC WD30EFRX-68EUZN0 3TB                  | 1         | 1      | 1.25%   |
| WDC WD20EZRX-00D8PB0 2TB                  | 1         | 1      | 1.25%   |
| WDC WD20EARS-00MVWB0 2TB                  | 1         | 1      | 1.25%   |
| WDC WD1600YS-01SHB1 164GB                 | 1         | 1      | 1.25%   |
| WDC WD1600AAJS-60Z0A0 160GB               | 1         | 1      | 1.25%   |
| WDC WD10JPVX-60JC3T1 1TB                  | 1         | 1      | 1.25%   |
| WDC WD10EZEX-60WN4A0 1TB                  | 1         | 1      | 1.25%   |
| WDC WD10EZEX-60M2NA0 1TB                  | 1         | 1      | 1.25%   |
| WDC WD10EARS-003BB1 1TB                   | 1         | 1      | 1.25%   |
| WDC WD10EADS-11M2B2 1TB                   | 1         | 1      | 1.25%   |
| Toshiba MQ01ABF050 500GB                  | 1         | 1      | 1.25%   |
| Toshiba MQ01ABD100 1TB                    | 1         | 1      | 1.25%   |
| Toshiba MQ01ABD032 320GB                  | 1         | 1      | 1.25%   |
| Toshiba MK5059GSXP 500GB                  | 1         | 1      | 1.25%   |
| Toshiba MK3259GSXP 320GB                  | 1         | 1      | 1.25%   |
| Toshiba MK1646GSX 160GB                   | 1         | 1      | 1.25%   |
| Toshiba MK1229GSG 120GB                   | 1         | 1      | 1.25%   |
| Toshiba DT01ACA100 1TB                    | 1         | 1      | 1.25%   |
| SK hynix SC210 mSATA 256GB                | 1         | 1      | 1.25%   |
| Silicon Motion Asgard AN1TNVMe-M.2-80 1TB | 1         | 1      | 1.25%   |
| Seagate ST9250410AS 250GB                 | 1         | 1      | 1.25%   |
| Seagate ST9160827AS 160GB                 | 1         | 1      | 1.25%   |
| Seagate ST9160314AS 160GB                 | 1         | 1      | 1.25%   |
| Seagate ST750LM022 HN-M750MBB 752GB       | 1         | 1      | 1.25%   |
| Seagate ST500LM000-SSHD-8GB               | 1         | 1      | 1.25%   |
| Seagate ST500LM000-1EJ162-SSHD-8GB        | 1         | 1      | 1.25%   |
| Seagate ST500DM002-1BD142 500GB           | 1         | 1      | 1.25%   |
| Seagate ST380215AS 80GB                   | 1         | 1      | 1.25%   |
| Seagate ST3750528AS 752GB                 | 1         | 1      | 1.25%   |
| Seagate ST3500418AS 500GB                 | 1         | 1      | 1.25%   |
| Seagate ST3500320AS 500GB                 | 1         | 1      | 1.25%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 21        | 26     | 27.27%  |
| WDC                 | 14        | 15     | 18.18%  |
| Hitachi             | 12        | 12     | 15.58%  |
| Toshiba             | 8         | 8      | 10.39%  |
| HGST                | 5         | 6      | 6.49%   |
| Samsung Electronics | 4         | 4      | 5.19%   |
| Maxtor              | 3         | 3      | 3.9%    |
| Crucial             | 3         | 4      | 3.9%    |
| Kingston            | 2         | 2      | 2.6%    |
| SK hynix            | 1         | 1      | 1.3%    |
| Silicon Motion      | 1         | 1      | 1.3%    |
| OCZ                 | 1         | 1      | 1.3%    |
| Intel               | 1         | 1      | 1.3%    |
| China               | 1         | 1      | 1.3%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 21        | 26     | 32.31%  |
| WDC                 | 14        | 15     | 21.54%  |
| Hitachi             | 12        | 12     | 18.46%  |
| Toshiba             | 8         | 8      | 12.31%  |
| HGST                | 5         | 6      | 7.69%   |
| Maxtor              | 3         | 3      | 4.62%   |
| Samsung Electronics | 2         | 2      | 3.08%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 63        | 72     | 84%     |
| SSD  | 10        | 11     | 13.33%  |
| NVMe | 2         | 2      | 2.67%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart_bsd/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD7501AALS-00J7B0 752GB       | 1         | 1      | 25%     |
| WDC WD1600BEVT-22ZCT0 160GB       | 1         | 1      | 25%     |
| SanDisk pSSD 256GB                | 1         | 1      | 25%     |
| Samsung Electronics HM500JJ 500GB | 1         | 1      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 2         | 2      | 50%     |
| SanDisk             | 1         | 1      | 25%     |
| Samsung Electronics | 1         | 1      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 268       | 437    | 75.28%  |
| Malfunc  | 75        | 85     | 21.07%  |
| Detected | 9         | 15     | 2.53%   |
| Failed   | 4         | 4      | 1.12%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 266       | 62.3%   |
| AMD                                     | 54        | 12.65%  |
| Samsung Electronics                     | 32        | 7.49%   |
| Sandisk                                 | 11        | 2.58%   |
| Kingston Technology Company             | 10        | 2.34%   |
| Nvidia                                  | 8         | 1.87%   |
| Silicon Motion                          | 6         | 1.41%   |
| Micron Technology                       | 5         | 1.17%   |
| Marvell Technology Group                | 5         | 1.17%   |
| ASMedia Technology                      | 5         | 1.17%   |
| SK hynix                                | 4         | 0.94%   |
| Phison Electronics                      | 3         | 0.7%    |
| JMicron Technology                      | 3         | 0.7%    |
| ADATA Technology                        | 3         | 0.7%    |
| VIA Technologies                        | 2         | 0.47%   |
| Realtek Semiconductor                   | 2         | 0.47%   |
| Micron/Crucial Technology               | 2         | 0.47%   |
| Toshiba                                 | 1         | 0.23%   |
| Silicon Integrated Systems [SiS]        | 1         | 0.23%   |
| Shenzhen Unionmemory Information System | 1         | 0.23%   |
| OCZ Technology Group                    | 1         | 0.23%   |
| KIOXIA                                  | 1         | 0.23%   |
| Broadcom / LSI                          | 1         | 0.23%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 28        | 5.63%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 23        | 4.63%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 21        | 4.23%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 20        | 4.02%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 17        | 3.42%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 15        | 3.02%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 15        | 3.02%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 14        | 2.82%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 12        | 2.41%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 12        | 2.41%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 10        | 2.01%   |
| Samsung NVMe SSD Controller 980                                                         | 9         | 1.81%   |
| AMD 500 Series Chipset SATA Controller                                                  | 9         | 1.81%   |
| AMD 400 Series Chipset SATA Controller                                                  | 9         | 1.81%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 8         | 1.61%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 8         | 1.61%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 7         | 1.41%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 7         | 1.41%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 7         | 1.41%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 7         | 1.41%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 6         | 1.21%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 6         | 1.21%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 6         | 1.21%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 6         | 1.21%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 6         | 1.21%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 5         | 1.01%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 5         | 1.01%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 5         | 1.01%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 5         | 1.01%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 5         | 1.01%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 4         | 0.8%    |
| Intel Volume Management Device NVMe RAID Controller                                     | 4         | 0.8%    |
| Intel SATA Controller [RAID mode]                                                       | 4         | 0.8%    |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 4         | 0.8%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 4         | 0.8%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4         | 0.8%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 4         | 0.8%    |
| Intel 4 Series Chipset PT IDER Controller                                               | 4         | 0.8%    |
| Nvidia MCP79 AHCI Controller                                                            | 3         | 0.6%    |
| Nvidia MCP61 SATA Controller                                                            | 3         | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 281       | 65.65%  |
| NVMe | 75        | 17.52%  |
| IDE  | 56        | 13.08%  |
| RAID | 14        | 3.27%   |
| SAS  | 1         | 0.23%   |
| SCSI | 1         | 0.23%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 286       | 81.71%  |
| AMD    | 64        | 18.29%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-6300U CPU @ 2.40GHz           | 6         | 1.71%   |
| Intel CPU Version                           | 5         | 1.43%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 5         | 1.43%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 5         | 1.43%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 5         | 1.43%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 4         | 1.14%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 4         | 1.14%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 4         | 1.14%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 3         | 0.86%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 3         | 0.86%   |
| Intel Core i7-3520M CPU @ 2.90GHz           | 3         | 0.86%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 3         | 0.86%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 3         | 0.86%   |
| Intel Core i5-3337U CPU @ 1.80GHz           | 3         | 0.86%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 3         | 0.86%   |
| Intel Core i3-7100 CPU @ 3.90GHz            | 3         | 0.86%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 3         | 0.86%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 3         | 0.86%   |
| Intel Core 2 Duo CPU P7350 @ 2.00GHz        | 3         | 0.86%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 3         | 0.86%   |
| Intel Xeon CPU E31220 @ 3.10GHz             | 2         | 0.57%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 2         | 0.57%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 2         | 0.57%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 2         | 0.57%   |
| Intel Core i7-5500U CPU @ 2.40GHz           | 2         | 0.57%   |
| Intel Core i7-2670QM CPU @ 2.20GHz          | 2         | 0.57%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 2         | 0.57%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 2         | 0.57%   |
| Intel Core i5-7300U CPU @ 2.60GHz           | 2         | 0.57%   |
| Intel Core i5-6500T CPU @ 2.50GHz           | 2         | 0.57%   |
| Intel Core i5-4440 CPU @ 3.10GHz            | 2         | 0.57%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 2         | 0.57%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 2         | 0.57%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 2         | 0.57%   |
| Intel Core i5-2540M CPU @ 2.60GHz           | 2         | 0.57%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 2         | 0.57%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 2         | 0.57%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 2         | 0.57%   |
| Intel Core i3-9100 CPU @ 3.60GHz            | 2         | 0.57%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 2         | 0.57%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 91        | 26%     |
| Intel Core i7           | 49        | 14%     |
| Intel Core i3           | 34        | 9.71%   |
| Intel Celeron           | 33        | 9.43%   |
| Intel Core 2 Duo        | 24        | 6.86%   |
| AMD Ryzen 5             | 18        | 5.14%   |
| Other                   | 16        | 4.57%   |
| Intel Xeon              | 12        | 3.43%   |
| AMD Ryzen 7             | 10        | 2.86%   |
| Intel Pentium           | 8         | 2.29%   |
| AMD Ryzen 3             | 8         | 2.29%   |
| Intel Pentium Dual-Core | 4         | 1.14%   |
| Intel Atom              | 4         | 1.14%   |
| AMD Phenom II X4        | 3         | 0.86%   |
| AMD Athlon II X2        | 3         | 0.86%   |
| AMD A4                  | 3         | 0.86%   |
| Intel Genuine           | 2         | 0.57%   |
| Intel Core i9           | 2         | 0.57%   |
| Intel Core 2 Quad       | 2         | 0.57%   |
| Intel Core 2            | 2         | 0.57%   |
| AMD E                   | 2         | 0.57%   |
| AMD A10                 | 2         | 0.57%   |
| Intel Pentium Silver    | 1         | 0.29%   |
| Intel Pentium Gold      | 1         | 0.29%   |
| Intel Pentium Dual      | 1         | 0.29%   |
| Intel Pentium 4         | 1         | 0.29%   |
| Intel Celeron D         | 1         | 0.29%   |
| AMD Ryzen Embedded      | 1         | 0.29%   |
| AMD Ryzen 9             | 1         | 0.29%   |
| AMD Phenom II X6        | 1         | 0.29%   |
| AMD Phenom II X2        | 1         | 0.29%   |
| AMD Phenom II           | 1         | 0.29%   |
| AMD FX                  | 1         | 0.29%   |
| AMD E2                  | 1         | 0.29%   |
| AMD E1                  | 1         | 0.29%   |
| AMD Athlon X2           | 1         | 0.29%   |
| AMD Athlon II X4        | 1         | 0.29%   |
| AMD Athlon 64           | 1         | 0.29%   |
| AMD Athlon              | 1         | 0.29%   |
| AMD A8                  | 1         | 0.29%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 152       | 43.43%  |
| 4       | 113       | 32.29%  |
| Unknown | 26        | 7.43%   |
| 6       | 18        | 5.14%   |
| 12      | 13        | 3.71%   |
| 8       | 13        | 3.71%   |
| 16      | 7         | 2%      |
| 1       | 6         | 1.71%   |
| 24      | 1         | 0.29%   |
| 10      | 1         | 0.29%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 343       | 98%     |
| 2      | 7         | 2%      |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 164       | 46.86%  |
| 1       | 156       | 44.57%  |
| Unknown | 30        | 8.57%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 47        | 13.43%  |
| IvyBridge     | 37        | 10.57%  |
| Haswell       | 35        | 10%     |
| SandyBridge   | 31        | 8.86%   |
| Skylake       | 27        | 7.71%   |
| Penryn        | 23        | 6.57%   |
| Core          | 19        | 5.43%   |
| Zen+          | 17        | 4.86%   |
| Zen 3         | 11        | 3.14%   |
| Westmere      | 11        | 3.14%   |
| Silvermont    | 11        | 3.14%   |
| K10           | 11        | 3.14%   |
| Unknown       | 9         | 2.57%   |
| Broadwell     | 8         | 2.29%   |
| CometLake     | 7         | 2%      |
| Zen           | 6         | 1.71%   |
| Goldmont plus | 6         | 1.71%   |
| Bonnell       | 5         | 1.43%   |
| TigerLake     | 4         | 1.14%   |
| Piledriver    | 4         | 1.14%   |
| Bobcat        | 4         | 1.14%   |
| Zen 2         | 3         | 0.86%   |
| Nehalem       | 3         | 0.86%   |
| Goldmont      | 3         | 0.86%   |
| Excavator     | 3         | 0.86%   |
| NetBurst      | 1         | 0.29%   |
| K8 Hammer     | 1         | 0.29%   |
| K10 Llano     | 1         | 0.29%   |
| IceLake       | 1         | 0.29%   |
| Bulldozer     | 1         | 0.29%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 224       | 57.44%  |
| Nvidia                           | 83        | 21.28%  |
| AMD                              | 81        | 20.77%  |
| Silicon Integrated Systems [SiS] | 1         | 0.26%   |
| Matrox Electronics Systems       | 1         | 0.26%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 25        | 6.17%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 19        | 4.69%   |
| Intel HD Graphics 530                                                                    | 12        | 2.96%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 12        | 2.96%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 10        | 2.47%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 10        | 2.47%   |
| Intel HD Graphics 630                                                                    | 10        | 2.47%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 10        | 2.47%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 8         | 1.98%   |
| Intel UHD Graphics 620                                                                   | 8         | 1.98%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 8         | 1.98%   |
| Intel HD Graphics 5500                                                                   | 8         | 1.98%   |
| Intel Core Processor Integrated Graphics Controller                                      | 8         | 1.98%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 7         | 1.73%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 7         | 1.73%   |
| Intel HD Graphics 620                                                                    | 7         | 1.73%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 7         | 1.73%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 6         | 1.48%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 6         | 1.48%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 5         | 1.23%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 5         | 1.23%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 5         | 1.23%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 4         | 0.99%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 4         | 0.99%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 4         | 0.99%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 4         | 0.99%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 3         | 0.74%   |
| Nvidia GT218 [GeForce 210]                                                               | 3         | 0.74%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 3         | 0.74%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 3         | 0.74%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 3         | 0.74%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 0.74%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 3         | 0.74%   |
| Intel HD Graphics 500                                                                    | 3         | 0.74%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 0.74%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 0.74%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 0.74%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 3         | 0.74%   |
| AMD RS880 [Radeon HD 4250]                                                               | 3         | 0.74%   |
| AMD Renoir                                                                               | 3         | 0.74%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 157       | 44.6%   |
| 1 x AMD        | 64        | 18.18%  |
| 1 x Nvidia     | 56        | 15.91%  |
| 2 x Intel      | 28        | 7.95%   |
| Intel + Nvidia | 25        | 7.1%    |
| Intel + AMD    | 15        | 4.26%   |
| 2 x AMD        | 2         | 0.57%   |
| Other          | 1         | 0.28%   |
| 2 x Nvidia     | 1         | 0.28%   |
| 1 x SiS        | 1         | 0.28%   |
| 1 x Matrox     | 1         | 0.28%   |
| AMD + Nvidia   | 1         | 0.28%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 295       | 84.05%  |
| Proprietary | 45        | 12.82%  |
| Unknown     | 11        | 3.13%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 269       | 76.42%  |
| 1.01-2.0   | 19        | 5.4%    |
| 0.01-0.5   | 19        | 5.4%    |
| 3.01-4.0   | 16        | 4.55%   |
| 0.51-1.0   | 14        | 3.98%   |
| 5.01-6.0   | 8         | 2.27%   |
| 7.01-8.0   | 4         | 1.14%   |
| 8.01-16.0  | 2         | 0.57%   |
| 2.01-3.0   | 1         | 0.28%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 20        | 15.04%  |
| Samsung Electronics     | 15        | 11.28%  |
| Dell                    | 8         | 6.02%   |
| BOE                     | 8         | 6.02%   |
| Goldstar                | 7         | 5.26%   |
| Acer                    | 7         | 5.26%   |
| LG Display              | 6         | 4.51%   |
| Hewlett-Packard         | 6         | 4.51%   |
| BenQ                    | 6         | 4.51%   |
| Lenovo                  | 5         | 3.76%   |
| Chimei Innolux          | 5         | 3.76%   |
| AOC                     | 5         | 3.76%   |
| Ancor Communications    | 4         | 3.01%   |
| Philips                 | 3         | 2.26%   |
| Chi Mei Optoelectronics | 3         | 2.26%   |
| Apple                   | 3         | 2.26%   |
| Unknown                 | 3         | 2.26%   |
| Sharp                   | 2         | 1.5%    |
| LG Electronics          | 2         | 1.5%    |
| InfoVision              | 2         | 1.5%    |
| ASUSTek Computer        | 2         | 1.5%    |
| Vizio                   | 1         | 0.75%   |
| Semp Toshiba            | 1         | 0.75%   |
| PKB                     | 1         | 0.75%   |
| NEC Computers           | 1         | 0.75%   |
| Microstep               | 1         | 0.75%   |
| LG Philips              | 1         | 0.75%   |
| ITE                     | 1         | 0.75%   |
| Idek Iiyama             | 1         | 0.75%   |
| Eizo                    | 1         | 0.75%   |
| CPT                     | 1         | 0.75%   |
| AUS                     | 1         | 0.75%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                | 3         | 2.26%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 340x190mm 15.3-inch   | 2         | 1.5%    |
| Lenovo LCD Monitor LEN4022 1400x1050 290x210mm 14.1-inch               | 2         | 1.5%    |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch          | 2         | 1.5%    |
| Acer G276HL ACR0300 1920x1080 600x340mm 27.2-inch                      | 2         | 1.5%    |
| Vizio E321VL VIZ0083 1366x768 700x400mm 31.7-inch                      | 1         | 0.75%   |
| Sharp LQ133M1JW01 SHP141B 1920x1080 290x170mm 13.2-inch                | 1         | 0.75%   |
| Sharp LCD Monitor SHP143B 3840x2160 350x190mm 15.7-inch                | 1         | 0.75%   |
| Semp Toshiba MLE1951 STI1951 1366x768 410x230mm 18.5-inch              | 1         | 0.75%   |
| Samsung Electronics SyncMaster SAM058D 1600x900 440x250mm 19.9-inch    | 1         | 0.75%   |
| Samsung Electronics SyncMaster SAM050B 1920x1080 480x270mm 21.7-inch   | 1         | 0.75%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 600x340mm 27.2-inch      | 1         | 0.75%   |
| Samsung Electronics S24C350 SAM0A3A 1920x1080 530x300mm 24.0-inch      | 1         | 0.75%   |
| Samsung Electronics S20B300 SAM08A7 1600x900 440x250mm 19.9-inch       | 1         | 0.75%   |
| Samsung Electronics S19B150 SAM08A2 1366x768 410x230mm 18.5-inch       | 1         | 0.75%   |
| Samsung Electronics Odyssey G50A SAM7181 2560x1440 600x340mm 27.2-inch | 1         | 0.75%   |
| Samsung Electronics LF27T370F SAM711E 1920x1080 600x340mm 27.2-inch    | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SEC384A 1366x768 340x190mm 15.3-inch   | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SEC3541 1366x768 300x170mm 13.6-inch   | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SEC3050 1366x768 320x190mm 14.7-inch   | 1         | 0.75%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 530x300mm 24.0-inch   | 1         | 0.75%   |
| Samsung Electronics C32HG7x SAM0E13 2560x1440 700x390mm 31.5-inch      | 1         | 0.75%   |
| PKB LCD Monitor MAE200W 1680x1050                                      | 1         | 0.75%   |
| Philips PHL 223V7 PHLC154 1920x1080 480x270mm 21.7-inch                | 1         | 0.75%   |
| Philips PHL 221S8L PHL091C 1920x1080 480x270mm 21.7-inch               | 1         | 0.75%   |
| Philips 150S PHL0820 1024x768 300x230mm 14.9-inch                      | 1         | 0.75%   |
| NEC Computers LCD Monitor 70GX2 1280x1024                              | 1         | 0.75%   |
| Microstep LCD Monitor MSI MAG241C 1920x1080                            | 1         | 0.75%   |
| LG Philips LP154WX4-TLCB LPL3101 1280x800 330x210mm 15.4-inch          | 1         | 0.75%   |
| LG Electronics LCD Monitor LG FULL HD 1920x1080                        | 1         | 0.75%   |
| LG Electronics LCD Monitor L1918S 1280x1024                            | 1         | 0.75%   |
| LG Display LCD Monitor LGD0555 2736x1824 260x170mm 12.2-inch           | 1         | 0.75%   |
| LG Display LCD Monitor LGD04E8 1920x1080 380x210mm 17.1-inch           | 1         | 0.75%   |
| LG Display LCD Monitor LGD0384 1366x768 340x190mm 15.3-inch            | 1         | 0.75%   |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch            | 1         | 0.75%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch            | 1         | 0.75%   |
| LG Display LCD Monitor LGD024D 1366x768 290x170mm 13.2-inch            | 1         | 0.75%   |
| Lenovo LCD Monitor LEN4010 1280x800 260x160mm 12.0-inch                | 1         | 0.75%   |
| Lenovo L24e-30 LEN66BC 1920x1080 530x300mm 24.0-inch                   | 1         | 0.75%   |
| Lenovo D27-30 LEN66B8 1920x1080 600x340mm 27.2-inch                    | 1         | 0.75%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 56        | 42.75%  |
| 1366x768 (WXGA)    | 36        | 27.48%  |
| 2560x1440 (QHD)    | 7         | 5.34%   |
| 1600x900 (HD+)     | 5         | 3.82%   |
| 3840x2160 (4K)     | 4         | 3.05%   |
| 2560x1600          | 3         | 2.29%   |
| 1280x800 (WXGA)    | 3         | 2.29%   |
| 1280x1024 (SXGA)   | 3         | 2.29%   |
| 1680x1050 (WSXGA+) | 2         | 1.53%   |
| 1440x900 (WXGA+)   | 2         | 1.53%   |
| 1400x1050          | 2         | 1.53%   |
| Unknown            | 2         | 1.53%   |
| 5760x2160          | 1         | 0.76%   |
| 3840x1080          | 1         | 0.76%   |
| 2736x1824          | 1         | 0.76%   |
| 1920x1200 (WUXGA)  | 1         | 0.76%   |
| 1024x768 (XGA)     | 1         | 0.76%   |
| 1024x600           | 1         | 0.76%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 24        | 18.46%  |
| Unknown | 19        | 14.62%  |
| 13      | 17        | 13.08%  |
| 21      | 13        | 10%     |
| 27      | 9         | 6.92%   |
| 24      | 8         | 6.15%   |
| 23      | 5         | 3.85%   |
| 19      | 5         | 3.85%   |
| 14      | 5         | 3.85%   |
| 12      | 5         | 3.85%   |
| 31      | 4         | 3.08%   |
| 18      | 4         | 3.08%   |
| 17      | 4         | 3.08%   |
| 11      | 3         | 2.31%   |
| 20      | 2         | 1.54%   |
| 29      | 1         | 0.77%   |
| 22      | 1         | 0.77%   |
| 9       | 1         | 0.77%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 36        | 27.69%  |
| 401-500     | 24        | 18.46%  |
| 501-600     | 22        | 16.92%  |
| 201-300     | 19        | 14.62%  |
| Unknown     | 19        | 14.62%  |
| 601-700     | 5         | 3.85%   |
| 351-400     | 5         | 3.85%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 93        | 73.81%  |
| Unknown | 19        | 15.08%  |
| 16/10   | 9         | 7.14%   |
| 4/3     | 3         | 2.38%   |
| 5/4     | 1         | 0.79%   |
| 3/2     | 1         | 0.79%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 27        | 20.77%  |
| 91-100         | 23        | 17.69%  |
| Unknown        | 19        | 14.62%  |
| 81-90          | 13        | 10%     |
| 301-350        | 9         | 6.92%   |
| 151-200        | 7         | 5.38%   |
| 71-80          | 5         | 3.85%   |
| 61-70          | 5         | 3.85%   |
| 351-500        | 5         | 3.85%   |
| 101-110        | 5         | 3.85%   |
| 141-150        | 4         | 3.08%   |
| 121-130        | 4         | 3.08%   |
| 51-60          | 3         | 2.31%   |
| 41-50          | 1         | 0.77%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 38        | 29.23%  |
| 51-100        | 36        | 27.69%  |
| 121-160       | 32        | 24.62%  |
| Unknown       | 19        | 14.62%  |
| More than 240 | 2         | 1.54%   |
| 161-240       | 2         | 1.54%   |
| 1-50          | 1         | 0.77%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 296       | 84.33%  |
| 0     | 41        | 11.68%  |
| 2     | 14        | 3.99%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 174       | 35.15%  |
| Intel                             | 170       | 34.34%  |
| Qualcomm Atheros                  | 67        | 13.54%  |
| Broadcom                          | 20        | 4.04%   |
| Marvell Technology Group          | 9         | 1.82%   |
| Samsung Electronics               | 8         | 1.62%   |
| TP-Link                           | 5         | 1.01%   |
| Sierra Wireless                   | 5         | 1.01%   |
| Ralink                            | 5         | 1.01%   |
| Xiaomi                            | 4         | 0.81%   |
| Ralink Technology                 | 4         | 0.81%   |
| MediaTek                          | 4         | 0.81%   |
| Nvidia                            | 3         | 0.61%   |
| Ericsson Business Mobile Networks | 3         | 0.61%   |
| JMicron Technology                | 2         | 0.4%    |
| Huawei Technologies               | 2         | 0.4%    |
| Edimax Technology                 | 2         | 0.4%    |
| D-Link                            | 2         | 0.4%    |
| Silicon Integrated Systems [SiS]  | 1         | 0.2%    |
| Qualcomm                          | 1         | 0.2%    |
| National Semiconductor            | 1         | 0.2%    |
| Google                            | 1         | 0.2%    |
| Atheros                           | 1         | 0.2%    |
| Accton Technology                 | 1         | 0.2%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 126       | 21.07%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 25        | 4.18%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 25        | 4.18%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 13        | 2.17%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 13        | 2.17%   |
| Intel Wireless 8265 / 8275                                              | 12        | 2.01%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 12        | 2.01%   |
| Intel Wireless 8260                                                     | 10        | 1.67%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 9         | 1.51%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 9         | 1.51%   |
| Intel Ethernet Connection (2) I219-LM                                   | 9         | 1.51%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 8         | 1.34%   |
| Intel Wireless 7265                                                     | 8         | 1.34%   |
| Intel Wireless 3165                                                     | 8         | 1.34%   |
| Intel Ethernet Controller I225-V                                        | 7         | 1.17%   |
| Intel Ethernet Connection I217-LM                                       | 7         | 1.17%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 6         | 1%      |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 6         | 1%      |
| Intel Wireless 7260                                                     | 6         | 1%      |
| Intel Ethernet Connection I219-LM                                       | 6         | 1%      |
| Intel Ethernet Connection I217-V                                        | 6         | 1%      |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 5         | 0.84%   |
| Intel Wi-Fi 6 AX200                                                     | 5         | 0.84%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 5         | 0.84%   |
| Intel 82579V Gigabit Network Connection                                 | 5         | 0.84%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 4         | 0.67%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 0.67%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 4         | 0.67%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 4         | 0.67%   |
| Intel Ethernet Connection (4) I219-LM                                   | 4         | 0.67%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 4         | 0.67%   |
| Intel 82574L Gigabit Network Connection                                 | 4         | 0.67%   |
| Intel 82567LM Gigabit Network Connection                                | 4         | 0.67%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 4         | 0.67%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 3         | 0.5%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 3         | 0.5%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 3         | 0.5%    |
| Nvidia MCP79 Ethernet                                                   | 3         | 0.5%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 3         | 0.5%    |
| Intel Wi-Fi 6 AX201                                                     | 3         | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 112       | 45.16%  |
| Qualcomm Atheros      | 54        | 21.77%  |
| Realtek Semiconductor | 39        | 15.73%  |
| Broadcom              | 17        | 6.85%   |
| TP-Link               | 5         | 2.02%   |
| Ralink                | 5         | 2.02%   |
| Ralink Technology     | 4         | 1.61%   |
| Sierra Wireless       | 3         | 1.21%   |
| MediaTek              | 3         | 1.21%   |
| Edimax Technology     | 2         | 0.81%   |
| D-Link                | 2         | 0.81%   |
| Atheros               | 1         | 0.4%    |
| Accton Technology     | 1         | 0.4%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 13        | 5.14%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 13        | 5.14%   |
| Intel Wireless 8265 / 8275                                              | 12        | 4.74%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 12        | 4.74%   |
| Intel Wireless 8260                                                     | 10        | 3.95%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 9         | 3.56%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 9         | 3.56%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 8         | 3.16%   |
| Intel Wireless 7265                                                     | 8         | 3.16%   |
| Intel Wireless 3165                                                     | 8         | 3.16%   |
| Intel Wireless 7260                                                     | 6         | 2.37%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 5         | 1.98%   |
| Intel Wi-Fi 6 AX200                                                     | 5         | 1.98%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 5         | 1.98%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 1.58%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 4         | 1.58%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 4         | 1.58%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 4         | 1.58%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 3         | 1.19%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 3         | 1.19%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 3         | 1.19%   |
| Intel Wi-Fi 6 AX201                                                     | 3         | 1.19%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 3         | 1.19%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 3         | 1.19%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 1.19%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 1.19%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 3         | 1.19%   |
| Intel Centrino Advanced-N 6200                                          | 3         | 1.19%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 3         | 1.19%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 3         | 1.19%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 0.79%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 2         | 0.79%   |
| Sierra Wireless EM7345 4G LTE                                           | 2         | 0.79%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.79%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                         | 2         | 0.79%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 2         | 0.79%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 0.79%   |
| Realtek Realtek Bluetooth 4.2 Adapter                                   | 2         | 0.79%   |
| Realtek 8811CU Wireless LAN 802.11ac USB NIC                            | 2         | 0.79%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 2         | 0.79%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 157       | 47.01%  |
| Intel                            | 119       | 35.63%  |
| Qualcomm Atheros                 | 20        | 5.99%   |
| Marvell Technology Group         | 9         | 2.69%   |
| Samsung Electronics              | 8         | 2.4%    |
| Broadcom                         | 6         | 1.8%    |
| Xiaomi                           | 4         | 1.2%    |
| Nvidia                           | 3         | 0.9%    |
| JMicron Technology               | 2         | 0.6%    |
| Huawei Technologies              | 2         | 0.6%    |
| Silicon Integrated Systems [SiS] | 1         | 0.3%    |
| Qualcomm                         | 1         | 0.3%    |
| National Semiconductor           | 1         | 0.3%    |
| MediaTek                         | 1         | 0.3%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 126       | 37.28%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 25        | 7.4%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 25        | 7.4%    |
| Intel Ethernet Connection (2) I219-LM                             | 9         | 2.66%   |
| Intel Ethernet Controller I225-V                                  | 7         | 2.07%   |
| Intel Ethernet Connection I217-LM                                 | 7         | 2.07%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 6         | 1.78%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 6         | 1.78%   |
| Intel Ethernet Connection I219-LM                                 | 6         | 1.78%   |
| Intel Ethernet Connection I217-V                                  | 6         | 1.78%   |
| Intel 82579V Gigabit Network Connection                           | 5         | 1.48%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 4         | 1.18%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 4         | 1.18%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 1.18%   |
| Intel 82574L Gigabit Network Connection                           | 4         | 1.18%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 1.18%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 0.89%   |
| Nvidia MCP79 Ethernet                                             | 3         | 0.89%   |
| Intel I211 Gigabit Network Connection                             | 3         | 0.89%   |
| Intel Ethernet Connection (7) I219-V                              | 3         | 0.89%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 0.89%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 0.89%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 0.89%   |
| Intel 82566MM Gigabit Network Connection                          | 3         | 0.89%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 0.59%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 0.59%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.59%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 0.59%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 0.59%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 2         | 0.59%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 2         | 0.59%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 2         | 0.59%   |
| Intel I210 Gigabit Network Connection                             | 2         | 0.59%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 0.59%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 0.59%   |
| Intel Ethernet Connection (5) I219-LM                             | 2         | 0.59%   |
| Intel Ethernet Connection (17) I219-V                             | 2         | 0.59%   |
| Intel 82573L Gigabit Ethernet Controller                          | 2         | 0.59%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2         | 0.59%   |
| Intel 82567LF-3 Gigabit Network Connection                        | 2         | 0.59%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 321       | 57.12%  |
| WiFi     | 234       | 41.64%  |
| Unknown  | 6         | 1.07%   |
| Modem    | 1         | 0.18%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 214       | 67.94%  |
| WiFi     | 101       | 32.06%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 192       | 54.7%   |
| 1     | 148       | 42.17%  |
| 0     | 6         | 1.71%   |
| 3     | 5         | 1.42%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 327       | 92.37%  |
| Yes  | 27        | 7.63%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 75        | 41.9%   |
| Realtek Semiconductor           | 18        | 10.06%  |
| Qualcomm Atheros Communications | 16        | 8.94%   |
| Broadcom                        | 13        | 7.26%   |
| Cambridge Silicon Radio         | 11        | 6.15%   |
| Apple                           | 9         | 5.03%   |
| Foxconn / Hon Hai               | 8         | 4.47%   |
| ASUSTek Computer                | 7         | 3.91%   |
| IMC Networks                    | 6         | 3.35%   |
| Lite-On Technology              | 5         | 2.79%   |
| Hewlett-Packard                 | 3         | 1.68%   |
| TP-Link                         | 2         | 1.12%   |
| Dell                            | 2         | 1.12%   |
| Primax Electronics              | 1         | 0.56%   |
| Fujitsu                         | 1         | 0.56%   |
| Askey Computer                  | 1         | 0.56%   |
| Alps Electric                   | 1         | 0.56%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 44        | 24.58%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 11        | 6.15%   |
| Realtek Bluetooth Adapter                                   | 9         | 5.03%   |
| Intel AX201 Bluetooth                                       | 9         | 5.03%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 8         | 4.47%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 7         | 3.91%   |
| Intel Wireless-AC 3168 Bluetooth                            | 5         | 2.79%   |
| Intel AX200 Bluetooth                                       | 4         | 2.23%   |
| Apple Bluetooth Host Controller                             | 4         | 2.23%   |
| Realtek  Bluetooth 4.2 Adapter                              | 3         | 1.68%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 3         | 1.68%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 3         | 1.68%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 3         | 1.68%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 3         | 1.68%   |
| ASUS BT-270 Bluetooth Adapter                               | 3         | 1.68%   |
| TP-Link Bluetooth 5.0 USB Adapter                           | 2         | 1.12%   |
| Realtek RTL8821A Bluetooth                                  | 2         | 1.12%   |
| Realtek Bluetooth 4.0 Adapter                               | 2         | 1.12%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 2         | 1.12%   |
| Lite-On Bluetooth USB Module                                | 2         | 1.12%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                | 2         | 1.12%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device             | 2         | 1.12%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth USB Device    | 2         | 1.12%   |
| Broadcom BCM20702A0 Bluetooth 4.0                           | 2         | 1.12%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]          | 2         | 1.12%   |
| Apple Built-in iSight (no firmware loaded)                  | 2         | 1.12%   |
| Realtek Bluetooth 4.2 Adapter                               | 1         | 0.56%   |
| Realtek Bluetooth 4.0 + High Speed Chip                     | 1         | 0.56%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 1         | 0.56%   |
| Qualcomm Atheros Dell Wireless 1901 Bluetooth               | 1         | 0.56%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 1         | 0.56%   |
| Qualcomm Atheros Dell Wireless 1703 Bluetooth               | 1         | 0.56%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 1         | 0.56%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)             | 1         | 0.56%   |
| Qualcomm Atheros AR3011 Bluetooth                           | 1         | 0.56%   |
| Primax Rocketfish RF-FLBTAD Bluetooth Adapter               | 1         | 0.56%   |
| Lite-On Qualcomm Atheros Bluetooth 4.0 + HS                 | 1         | 0.56%   |
| Lite-On Qualcomm Atheros Bluetooth                          | 1         | 0.56%   |
| Lite-On Atheros AR3012 Bluetooth                            | 1         | 0.56%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 1         | 0.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 273       | 59.35%  |
| AMD                               | 86        | 18.7%   |
| Nvidia                            | 58        | 12.61%  |
| C-Media Electronics               | 14        | 3.04%   |
| Texas Instruments                 | 5         | 1.09%   |
| Creative Labs                     | 3         | 0.65%   |
| Realtek Semiconductor             | 2         | 0.43%   |
| Generalplus Technology            | 2         | 0.43%   |
| Unknown                           | 2         | 0.43%   |
| Yamaha                            | 1         | 0.22%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.22%   |
| Razer USA                         | 1         | 0.22%   |
| Phison Electronics                | 1         | 0.22%   |
| OPPO Electronics                  | 1         | 0.22%   |
| KTMicro                           | 1         | 0.22%   |
| JMTek                             | 1         | 0.22%   |
| Hewlett-Packard                   | 1         | 0.22%   |
| HECATE G2 GAMING HEADSET          | 1         | 0.22%   |
| Harman                            | 1         | 0.22%   |
| GN Netcom                         | 1         | 0.22%   |
| GEMBIRD                           | 1         | 0.22%   |
| Elitegroup Computer Systems (ECS) | 1         | 0.22%   |
| Edifier Technology                | 1         | 0.22%   |
| Conexant Systems                  | 1         | 0.22%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 32        | 5.89%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 31        | 5.71%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 26        | 4.79%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 25        | 4.6%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 23        | 4.24%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 18        | 3.31%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 17        | 3.13%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 16        | 2.95%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 16        | 2.95%   |
| Intel 200 Series PCH HD Audio                                                                     | 14        | 2.58%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 11        | 2.03%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 11        | 2.03%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 10        | 1.84%   |
| Intel 8 Series HD Audio Controller                                                                | 10        | 1.84%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 10        | 1.84%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 9         | 1.66%   |
| Intel Cannon Lake PCH cAVS                                                                        | 9         | 1.66%   |
| Intel Broadwell-U Audio Controller                                                                | 8         | 1.47%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 8         | 1.47%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 7         | 1.29%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 7         | 1.29%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 7         | 1.29%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 7         | 1.29%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 7         | 1.29%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 7         | 1.29%   |
| AMD FCH Azalia Controller                                                                         | 7         | 1.29%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 6         | 1.1%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 6         | 1.1%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 6         | 1.1%    |
| Nvidia TU116 High Definition Audio Controller                                                     | 5         | 0.92%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 5         | 0.92%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 5         | 0.92%   |
| Nvidia MCP79 High Definition Audio                                                                | 4         | 0.74%   |
| Nvidia High Definition Audio Controller                                                           | 4         | 0.74%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 4         | 0.74%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 0.74%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 4         | 0.74%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 4         | 0.74%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 4         | 0.74%   |
| Nvidia MCP61 High Definition Audio                                                                | 3         | 0.55%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 86        | 20.98%  |
| SK hynix            | 59        | 14.39%  |
| Kingston            | 44        | 10.73%  |
| Unknown             | 40        | 9.76%   |
| Micron Technology   | 31        | 7.56%   |
| Corsair             | 23        | 5.61%   |
| Crucial             | 22        | 5.37%   |
| Unknown             | 20        | 4.88%   |
| Nanya Technology    | 10        | 2.44%   |
| G.Skill             | 10        | 2.44%   |
| A-DATA Technology   | 8         | 1.95%   |
| Ramaxel Technology  | 6         | 1.46%   |
| Elpida              | 6         | 1.46%   |
| Unknown (ABCD)      | 5         | 1.22%   |
| Transcend           | 4         | 0.98%   |
| Smart               | 4         | 0.98%   |
| Patriot             | 4         | 0.98%   |
| Apacer              | 3         | 0.73%   |
| Team                | 2         | 0.49%   |
| SHARETRONIC         | 2         | 0.49%   |
| Multilaser          | 2         | 0.49%   |
| Kingmax             | 2         | 0.49%   |
| GOODRAM             | 2         | 0.49%   |
| Atermiter           | 2         | 0.49%   |
| Unknown (8A02)      | 1         | 0.24%   |
| Toshiba             | 1         | 0.24%   |
| Swissbit            | 1         | 0.24%   |
| Silicon Power       | 1         | 0.24%   |
| Qumo                | 1         | 0.24%   |
| MemoWise            | 1         | 0.24%   |
| Lexar               | 1         | 0.24%   |
| Lenovo              | 1         | 0.24%   |
| Juhor               | 1         | 0.24%   |
| Golden Empire       | 1         | 0.24%   |
| Avant               | 1         | 0.24%   |
| ASint Technology    | 1         | 0.24%   |
| AMD                 | 1         | 0.24%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 20        | 4.61%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 6         | 1.38%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 5         | 1.15%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 1.15%   |
| Unknown RAM Module 1GB SODIMM DDR2                               | 4         | 0.92%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 4         | 0.92%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s            | 4         | 0.92%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s | 3         | 0.69%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 3         | 0.69%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM 1067MT/s                 | 3         | 0.69%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s            | 3         | 0.69%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 3         | 0.69%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s            | 3         | 0.69%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 2         | 0.46%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 2         | 0.46%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 2         | 0.46%   |
| Unknown RAM Module 2GB DIMM 800MT/s                              | 2         | 0.46%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                             | 2         | 0.46%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 2         | 0.46%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s   | 2         | 0.46%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.46%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.46%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.46%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s           | 2         | 0.46%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB Row Of Chips DDR4 3200MT/s     | 2         | 0.46%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s           | 2         | 0.46%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2133MT/s           | 2         | 0.46%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 2         | 0.46%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 1333MT/s            | 2         | 0.46%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 0.46%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 0.46%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.46%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.46%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 2         | 0.46%   |
| Samsung RAM M471A5143EB0-CPB 4GB SODIMM DDR4 2133MT/s            | 2         | 0.46%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.46%   |
| Samsung RAM M4 70T5663QZ3-CF7 2GB SODIMM DDR2 2048MT/s           | 2         | 0.46%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s              | 2         | 0.46%   |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM DDR3 1333MT/s              | 2         | 0.46%   |
| Samsung RAM M3 78T2863DZS-CE6 1GB DIMM DDR2 667MT/s              | 2         | 0.46%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 149       | 42.82%  |
| DDR4    | 134       | 38.51%  |
| DDR2    | 32        | 9.2%    |
| Unknown | 17        | 4.89%   |
| LPDDR4  | 7         | 2.01%   |
| SDRAM   | 5         | 1.44%   |
| LPDDR3  | 2         | 0.57%   |
| DDR     | 2         | 0.57%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 192       | 55.33%  |
| DIMM         | 141       | 40.63%  |
| Row Of Chips | 6         | 1.73%   |
| Chip         | 4         | 1.15%   |
| Unknown      | 4         | 1.15%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 134       | 34.45%  |
| 4096  | 121       | 31.11%  |
| 2048  | 76        | 19.54%  |
| 16384 | 32        | 8.23%   |
| 1024  | 23        | 5.91%   |
| 32768 | 3         | 0.77%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 83        | 22.25%  |
| 1333    | 47        | 12.6%   |
| 2400    | 41        | 10.99%  |
| 3200    | 32        | 8.58%   |
| 2667    | 30        | 8.04%   |
| 2133    | 30        | 8.04%   |
| 667     | 22        | 5.9%    |
| 1067    | 16        | 4.29%   |
| 800     | 16        | 4.29%   |
| Unknown | 11        | 2.95%   |
| 1334    | 9         | 2.41%   |
| 3600    | 6         | 1.61%   |
| 1066    | 6         | 1.61%   |
| 1867    | 5         | 1.34%   |
| 2666    | 4         | 1.07%   |
| 3733    | 2         | 0.54%   |
| 3000    | 2         | 0.54%   |
| 2048    | 2         | 0.54%   |
| 533     | 2         | 0.54%   |
| 400     | 2         | 0.54%   |
| 4400    | 1         | 0.27%   |
| 3333    | 1         | 0.27%   |
| 1866    | 1         | 0.27%   |
| 1639    | 1         | 0.27%   |
| 1200    | 1         | 0.27%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart_bsd/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 2         | 50%     |
| Brother Industries | 2         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart_bsd/printer_model.svg)


| Model                    | Computers | Percent |
|--------------------------|-----------|---------|
| HP LaserJet 3390         | 1         | 25%     |
| HP LaserJet 1020         | 1         | 25%     |
| Brother HL-L2300D series | 1         | 25%     |
| Brother DCP-J152W        | 1         | 25%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart_bsd/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 2         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart_bsd/scanner_model.svg)


| Model                    | Computers | Percent |
|--------------------------|-----------|---------|
| Canon CanoScan LiDE 700F | 1         | 50%     |
| Canon CanoScan LiDE 120  | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart_bsd/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 36        | 25%     |
| Bison Electronics                      | 19        | 13.19%  |
| Microdia                               | 13        | 9.03%   |
| Sunplus Innovation Technology          | 9         | 6.25%   |
| Realtek Semiconductor                  | 9         | 6.25%   |
| IMC Networks                           | 9         | 6.25%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 4.17%   |
| Silicon Motion                         | 4         | 2.78%   |
| Quanta                                 | 4         | 2.78%   |
| Logitech                               | 4         | 2.78%   |
| Lite-On Technology                     | 4         | 2.78%   |
| Alcor Micro                            | 4         | 2.78%   |
| Syntek                                 | 3         | 2.08%   |
| Suyin                                  | 3         | 2.08%   |
| Lenovo                                 | 2         | 1.39%   |
| Importek                               | 2         | 1.39%   |
| Apple                                  | 2         | 1.39%   |
| Z-Star Microelectronics                | 1         | 0.69%   |
| Y Media                                | 1         | 0.69%   |
| Trust                                  | 1         | 0.69%   |
| Supreme Electronics                    | 1         | 0.69%   |
| SHENZHEN AONI ELECTRONIC               | 1         | 0.69%   |
| Luxvisions Innotech Limited            | 1         | 0.69%   |
| Intel                                  | 1         | 0.69%   |
| Genesys Logic                          | 1         | 0.69%   |
| GEMBIRD                                | 1         | 0.69%   |
| DigiTech                               | 1         | 0.69%   |
| ALi                                    | 1         | 0.69%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                   | 11        | 7.64%   |
| Bison Integrated Camera                                     | 8         | 5.56%   |
| Microdia Integrated_Webcam_HD                               | 5         | 3.47%   |
| Realtek Integrated_Webcam_HD                                | 4         | 2.78%   |
| Chicony Lenovo Integrated Camera (0.3MP)                    | 3         | 2.08%   |
| Chicony FJ Camera                                           | 3         | 2.08%   |
| Cheng Uei Precision Industry (Foxlink) Realtek DMFT RGB     | 3         | 2.08%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                    | 2         | 1.39%   |
| Sunplus Integrated_Webcam_HD                                | 2         | 1.39%   |
| Sunplus HP TrueVision HD Camera                             | 2         | 1.39%   |
| Realtek USB Camera                                          | 2         | 1.39%   |
| Microdia REDRAGON Live Camera Audio                         | 2         | 1.39%   |
| Logitech Webcam C270                                        | 2         | 1.39%   |
| Lite-On Integrated Camera                                   | 2         | 1.39%   |
| Lenovo Integrated Webcam                                    | 2         | 1.39%   |
| IMC Networks Integrated Webcam                              | 2         | 1.39%   |
| IMC Networks Integrated Camera                              | 2         | 1.39%   |
| Chicony USB 2.0 Camera                                      | 2         | 1.39%   |
| Chicony Integrated Camera [ThinkPad]                        | 2         | 1.39%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam            | 2         | 1.39%   |
| Bison Lenovo EasyCamera                                     | 2         | 1.39%   |
| Bison HP Webcam-101                                         | 2         | 1.39%   |
| Alcor Micro USB 2.0 Camera                                  | 2         | 1.39%   |
| Z-Star Namuga 1.3M Webcam                                   | 1         | 0.69%   |
| Y Media USB Camera                                          | 1         | 0.69%   |
| Trust Trust Full HD Webcam                                  | 1         | 0.69%   |
| Syntek Integrated Camera                                    | 1         | 0.69%   |
| Syntek HP Webcam                                            | 1         | 0.69%   |
| Syntek EasyCamera                                           | 1         | 0.69%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 0.69%   |
| Supreme Integrated Camera                                   | 1         | 0.69%   |
| Sunplus SPCA2650 AV Camera                                  | 1         | 0.69%   |
| Sunplus Laptop Integrated WebCam HD                         | 1         | 0.69%   |
| Sunplus Integrated Camera                                   | 1         | 0.69%   |
| Sunplus HP HD Webcam [Fixed]                                | 1         | 0.69%   |
| Sunplus 1.3M HD WebCam                                      | 1         | 0.69%   |
| Silicon Motion WebCam SCX Series                            | 1         | 0.69%   |
| Silicon Motion WebCam SCB-1100N                             | 1         | 0.69%   |
| Silicon Motion Realtek USB 2.0 PC Camera                    | 1         | 0.69%   |
| Silicon Motion ATIV VGA Camera                              | 1         | 0.69%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 10        | 45.45%  |
| Elan Microelectronics      | 3         | 13.64%  |
| AuthenTec                  | 3         | 13.64%  |
| Upek                       | 2         | 9.09%   |
| STMicroelectronics         | 1         | 4.55%   |
| Shenzhen Goodix Technology | 1         | 4.55%   |
| LighTuning Technology      | 1         | 4.55%   |
| Fingerprint Cards          | 1         | 4.55%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor           | 3         | 13.64%  |
| Validity Sensors Synaptics WBDI                        | 3         | 13.64%  |
| Elan Fingerprint Sensor                                | 3         | 13.64%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 2         | 9.09%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 4.55%   |
| Validity Sensors VFS101 Fingerprint Reader             | 1         | 4.55%   |
| Validity Sensors Swipe Fingerprint Sensor              | 1         | 4.55%   |
| Validity Sensors Fingerprint scanner                   | 1         | 4.55%   |
| STMicroelectronics Fingerprint Reader                  | 1         | 4.55%   |
| Shenzhen Goodix Fingerprint Reader SGX                 | 1         | 4.55%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 4.55%   |
| Fingerprint Cards FPC Fingerprint Reader               | 1         | 4.55%   |
| AuthenTec AES2810                                      | 1         | 4.55%   |
| AuthenTec AES2660                                      | 1         | 4.55%   |
| AuthenTec AES1660                                      | 1         | 4.55%   |

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
| 1     | 167       | 47.58%  |
| 0     | 86        | 24.5%   |
| 2     | 73        | 20.8%   |
| 3     | 21        | 5.98%   |
| 4     | 4         | 1.14%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 223       | 61.77%  |
| Net/wireless             | 47        | 13.02%  |
| Card reader              | 26        | 7.2%    |
| Fingerprint reader       | 22        | 6.09%   |
| Bluetooth                | 20        | 5.54%   |
| Sound                    | 15        | 4.16%   |
| Storage                  | 4         | 1.11%   |
| Network                  | 2         | 0.55%   |
| Net/ethernet             | 1         | 0.28%   |
| Dvb card                 | 1         | 0.28%   |

