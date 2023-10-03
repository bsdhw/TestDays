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

Total: 431

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Lenovo        | ThinkCentre M81 5049D7G     | Desktop     | [60de9490a9](https://bsd-hardware.info/?probe=60de9490a9) | Sep 29, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [5cd50ed5b5](https://bsd-hardware.info/?probe=5cd50ed5b5) | Sep 24, 2023 |
| ASUSTek       | Z170-A                      | Desktop     | [3802fe676c](https://bsd-hardware.info/?probe=3802fe676c) | Sep 23, 2023 |
| HP            | 18E8                        | Desktop     | [7a96c7f43a](https://bsd-hardware.info/?probe=7a96c7f43a) | Sep 21, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [8a3d3b3d0d](https://bsd-hardware.info/?probe=8a3d3b3d0d) | Sep 21, 2023 |
| HP            | 83F3                        | Desktop     | [4d1df66f57](https://bsd-hardware.info/?probe=4d1df66f57) | Sep 20, 2023 |
| Dell          | 0VRWRC A01                  | Desktop     | [6c85a42e64](https://bsd-hardware.info/?probe=6c85a42e64) | Sep 19, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [211b0f3e9c](https://bsd-hardware.info/?probe=211b0f3e9c) | Sep 19, 2023 |
| AZW           | U59                         | Desktop     | [ae0d8568d1](https://bsd-hardware.info/?probe=ae0d8568d1) | Sep 15, 2023 |
| Lenovo        | ThinkPad Edge E531 68852... | Notebook    | [cc3bef6a45](https://bsd-hardware.info/?probe=cc3bef6a45) | Sep 15, 2023 |
| AZW           | U59                         | Desktop     | [7e094459f9](https://bsd-hardware.info/?probe=7e094459f9) | Sep 14, 2023 |
| Dell          | 04YP6J A02                  | Desktop     | [0933e1164a](https://bsd-hardware.info/?probe=0933e1164a) | Sep 13, 2023 |
| OEGStone      | doceo 510                   | Notebook    | [9f3b47e30f](https://bsd-hardware.info/?probe=9f3b47e30f) | Sep 13, 2023 |
| Lenovo        | 3140 NOK                    | Desktop     | [945ad170d7](https://bsd-hardware.info/?probe=945ad170d7) | Sep 10, 2023 |
| Lenovo        | 3140 NOK                    | Desktop     | [3f9dcefb8e](https://bsd-hardware.info/?probe=3f9dcefb8e) | Sep 10, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [f0fc4f47b8](https://bsd-hardware.info/?probe=f0fc4f47b8) | Sep 10, 2023 |
| Lenovo        | ThinkPad SL 2746N8G         | Notebook    | [07eda65608](https://bsd-hardware.info/?probe=07eda65608) | Sep 09, 2023 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | Notebook    | [1d5aff2e2a](https://bsd-hardware.info/?probe=1d5aff2e2a) | Sep 08, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [e3d8f34f08](https://bsd-hardware.info/?probe=e3d8f34f08) | Sep 08, 2023 |
| HP            | Pavilion g7                 | Notebook    | [4870da3b0e](https://bsd-hardware.info/?probe=4870da3b0e) | Sep 07, 2023 |
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
| amd64 | 366       | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| helloDesktop | 362       | 98.91%  |
| GNOME        | 2         | 0.55%   |
| KDE5         | 1         | 0.27%   |
| JWM          | 1         | 0.27%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 366       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| SLiM | 366       | 99.73%  |
| SDDM | 1         | 0.27%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 164       | 44.44%  |
| fr_FR   | 77        | 20.87%  |
| ru_RU   | 27        | 7.32%   |
| de_DE   | 24        | 6.5%    |
| es_ES   | 19        | 5.15%   |
| Unknown | 14        | 3.79%   |
| pt_BR   | 11        | 2.98%   |
| pl_PL   | 9         | 2.44%   |
| it_IT   | 8         | 2.17%   |
| nl_NL   | 3         | 0.81%   |
| jp_JP   | 3         | 0.81%   |
| zh_CN   | 2         | 0.54%   |
| ko_KR   | 2         | 0.54%   |
| pt_PT   | 1         | 0.27%   |
| pt      | 1         | 0.27%   |
| fr      | 1         | 0.27%   |
| fi_FI   | 1         | 0.27%   |
| es      | 1         | 0.27%   |
| en      | 1         | 0.27%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 363       | 99.18%  |
| BIOS | 3         | 0.82%   |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type   | Computers | Percent |
|--------|-----------|---------|
| Cd9660 | 196       | 52.83%  |
| Zfs    | 175       | 47.17%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 363       | 99.18%  |
| MBR  | 3         | 0.82%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 74        | 20.22%  |
| ASUSTek Computer    | 52        | 14.21%  |
| Hewlett-Packard     | 50        | 13.66%  |
| Dell                | 37        | 10.11%  |
| Gigabyte Technology | 25        | 6.83%   |
| Acer                | 15        | 4.1%    |
| MSI                 | 14        | 3.83%   |
| Intel               | 11        | 3.01%   |
| Fujitsu             | 9         | 2.46%   |
| ASRock              | 9         | 2.46%   |
| Toshiba             | 8         | 2.19%   |
| Samsung Electronics | 8         | 2.19%   |
| Apple               | 8         | 2.19%   |
| Unknown             | 5         | 1.37%   |
| Sony                | 4         | 1.09%   |
| Google              | 4         | 1.09%   |
| T-bao               | 2         | 0.55%   |
| Packard Bell        | 2         | 0.55%   |
| LG Electronics      | 2         | 0.55%   |
| Fujitsu Siemens     | 2         | 0.55%   |
| Foxconn             | 2         | 0.55%   |
| AZW                 | 2         | 0.55%   |
| TUXEDO              | 1         | 0.27%   |
| Timi                | 1         | 0.27%   |
| Plaisio             | 1         | 0.27%   |
| Pegatron            | 1         | 0.27%   |
| Panasonic           | 1         | 0.27%   |
| OEGStone            | 1         | 0.27%   |
| NVN-ED01            | 1         | 0.27%   |
| Microsoft           | 1         | 0.27%   |
| Medion              | 1         | 0.27%   |
| Irbis               | 1         | 0.27%   |
| IGEL Technology     | 1         | 0.27%   |
| HUAWEI              | 1         | 0.27%   |
| Huanan              | 1         | 0.27%   |
| ECS                 | 1         | 0.27%   |
| Dynabook Europe     | 1         | 0.27%   |
| DNS                 | 1         | 0.27%   |
| Daten Tecnologia    | 1         | 0.27%   |
| Compaq              | 1         | 0.27%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                              | Computers | Percent |
|-----------------------------------|-----------|---------|
| Unknown                           | 8         | 2.19%   |
| T-bao MINI PC                     | 2         | 0.55%   |
| MSI MS-7788                       | 2         | 0.55%   |
| Intel H81                         | 2         | 0.55%   |
| HP Laptop 14-bs0xx                | 2         | 0.55%   |
| HP EliteDesk 800 G2 DM 35W        | 2         | 0.55%   |
| HP Compaq Elite 8300 USDT         | 2         | 0.55%   |
| Dell OptiPlex 7010                | 2         | 0.55%   |
| Dell OptiPlex 3020                | 2         | 0.55%   |
| ASUS ROG STRIX B550-F GAMING      | 2         | 0.55%   |
| ASUS PRIME B250M-A                | 2         | 0.55%   |
| ASUS All Series                   | 2         | 0.55%   |
| Acer Spin SP314-21                | 2         | 0.55%   |
| TUXEDO Aura 15 Gen1               | 1         | 0.27%   |
| Toshiba Satellite P300            | 1         | 0.27%   |
| Toshiba Satellite L675D           | 1         | 0.27%   |
| Toshiba Satellite L50-B           | 1         | 0.27%   |
| Toshiba Satellite L40             | 1         | 0.27%   |
| Toshiba Satellite C845            | 1         | 0.27%   |
| Toshiba Satellite A200            | 1         | 0.27%   |
| Toshiba QOSMIO X775               | 1         | 0.27%   |
| Toshiba PORTEGE R700              | 1         | 0.27%   |
| Timi TM1701                       | 1         | 0.27%   |
| Sony VPCEG15FB                    | 1         | 0.27%   |
| Sony VGN-FZ19VN                   | 1         | 0.27%   |
| Sony SVL2412Z1EB                  | 1         | 0.27%   |
| Sony SVF14A15CBB                  | 1         | 0.27%   |
| Samsung RC530/RC730               | 1         | 0.27%   |
| Samsung R530/R730/R540            | 1         | 0.27%   |
| Samsung R520/R522/R620            | 1         | 0.27%   |
| Samsung R468/R418                 | 1         | 0.27%   |
| Samsung 370E4K                    | 1         | 0.27%   |
| Samsung 305E4A/305E5A/305E7A      | 1         | 0.27%   |
| Samsung 275E4E/275E5E             | 1         | 0.27%   |
| Samsung 270E5J/2570EJ             | 1         | 0.27%   |
| Plaisio Turbo X                   | 1         | 0.27%   |
| Pegatron Compaq dx2450 Microtower | 1         | 0.27%   |
| Panasonic CF-NX1GDHYS             | 1         | 0.27%   |
| Packard Bell EasyNote LJ65        | 1         | 0.27%   |
| Packard Bell DOT SE               | 1         | 0.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 43        | 11.75%  |
| ASUS PRIME              | 12        | 3.28%   |
| Lenovo IdeaPad          | 11        | 3.01%   |
| Dell Latitude           | 11        | 3.01%   |
| HP Pavilion             | 10        | 2.73%   |
| Dell OptiPlex           | 10        | 2.73%   |
| Lenovo ThinkCentre      | 9         | 2.46%   |
| Dell Inspiron           | 9         | 2.46%   |
| HP Compaq               | 8         | 2.19%   |
| ASUS ROG                | 8         | 2.19%   |
| Unknown                 | 8         | 2.19%   |
| Toshiba Satellite       | 6         | 1.64%   |
| HP Laptop               | 6         | 1.64%   |
| Acer Aspire             | 6         | 1.64%   |
| HP EliteDesk            | 5         | 1.37%   |
| HP ProDesk              | 4         | 1.09%   |
| HP EliteBook            | 4         | 1.09%   |
| Fujitsu LIFEBOOK        | 3         | 0.82%   |
| Dell Precision          | 3         | 0.82%   |
| T-bao MINI              | 2         | 0.55%   |
| MSI MS-7788             | 2         | 0.55%   |
| Lenovo Legion           | 2         | 0.55%   |
| Intel H81               | 2         | 0.55%   |
| Gigabyte B450M          | 2         | 0.55%   |
| Fujitsu Siemens ESPRIMO | 2         | 0.55%   |
| Fujitsu ESPRIMO         | 2         | 0.55%   |
| Dell Vostro             | 2         | 0.55%   |
| ASUS VivoBook           | 2         | 0.55%   |
| ASUS TUF                | 2         | 0.55%   |
| ASUS All                | 2         | 0.55%   |
| Acer Veriton            | 2         | 0.55%   |
| Acer Spin               | 2         | 0.55%   |
| TUXEDO Aura             | 1         | 0.27%   |
| Toshiba QOSMIO          | 1         | 0.27%   |
| Toshiba PORTEGE         | 1         | 0.27%   |
| Timi TM1701             | 1         | 0.27%   |
| Sony VPCEG15FB          | 1         | 0.27%   |
| Sony VGN-FZ19VN         | 1         | 0.27%   |
| Sony SVL2412Z1EB        | 1         | 0.27%   |
| Sony SVF14A15CBB        | 1         | 0.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2022    | 35        | 9.56%   |
| 2020    | 32        | 8.74%   |
| 2012    | 32        | 8.74%   |
| 2013    | 31        | 8.47%   |
| 2021    | 29        | 7.92%   |
| 2019    | 25        | 6.83%   |
| 2011    | 25        | 6.83%   |
| 2010    | 22        | 6.01%   |
| 2017    | 20        | 5.46%   |
| 2016    | 20        | 5.46%   |
| 2014    | 17        | 4.64%   |
| 2009    | 17        | 4.64%   |
| 2018    | 16        | 4.37%   |
| 2008    | 13        | 3.55%   |
| 2015    | 12        | 3.28%   |
| 2023    | 8         | 2.19%   |
| 2007    | 7         | 1.91%   |
| 2006    | 4         | 1.09%   |
| Unknown | 1         | 0.27%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 182       | 49.73%  |
| Desktop     | 169       | 46.17%  |
| Mini pc     | 6         | 1.64%   |
| Convertible | 5         | 1.37%   |
| All in one  | 2         | 0.55%   |
| Tablet      | 1         | 0.27%   |
| Server      | 1         | 0.27%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 360       | 98.36%  |
| Yes  | 6         | 1.64%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 131       | 35.79%  |
| 4.01-8.0    | 91        | 24.86%  |
| 16.01-24.0  | 86        | 23.5%   |
| 32.01-64.0  | 24        | 6.56%   |
| 2.01-3.0    | 18        | 4.92%   |
| 3.01-4.0    | 7         | 1.91%   |
| 64.01-256.0 | 5         | 1.37%   |
| 24.01-32.0  | 3         | 0.82%   |
| 0.51-1.0    | 1         | 0.27%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 195       | 52.99%  |
| 0.51-1.0 | 125       | 33.97%  |
| 1.01-2.0 | 33        | 8.97%   |
| 2.01-3.0 | 13        | 3.53%   |
| 3.01-4.0 | 2         | 0.54%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 226       | 61.58%  |
| 2      | 68        | 18.53%  |
| 3      | 28        | 7.63%   |
| 0      | 27        | 7.36%   |
| 5      | 8         | 2.18%   |
| 4      | 4         | 1.09%   |
| 9      | 2         | 0.54%   |
| 6      | 2         | 0.54%   |
| 13     | 1         | 0.27%   |
| 7      | 1         | 0.27%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 235       | 64.21%  |
| Yes       | 131       | 35.79%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 336       | 91.8%   |
| No        | 30        | 8.2%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 245       | 66.76%  |
| No        | 122       | 33.24%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 183       | 50%     |
| No        | 183       | 50%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country            | Computers | Percent |
|--------------------|-----------|---------|
| USA                | 53        | 14.48%  |
| Russia             | 39        | 10.66%  |
| Germany            | 30        | 8.2%    |
| Brazil             | 23        | 6.28%   |
| Poland             | 20        | 5.46%   |
| Spain              | 16        | 4.37%   |
| Italy              | 13        | 3.55%   |
| France             | 13        | 3.55%   |
| Canada             | 12        | 3.28%   |
| UK                 | 11        | 3.01%   |
| Indonesia          | 10        | 2.73%   |
| Romania            | 9         | 2.46%   |
| Hungary            | 9         | 2.46%   |
| Australia          | 9         | 2.46%   |
| Turkey             | 6         | 1.64%   |
| Serbia             | 6         | 1.64%   |
| Mexico             | 6         | 1.64%   |
| China              | 6         | 1.64%   |
| Netherlands        | 5         | 1.37%   |
| India              | 5         | 1.37%   |
| Belgium            | 5         | 1.37%   |
| Ukraine            | 4         | 1.09%   |
| South Korea        | 4         | 1.09%   |
| Bulgaria           | 4         | 1.09%   |
| Peru               | 3         | 0.82%   |
| Japan              | 3         | 0.82%   |
| Israel             | 3         | 0.82%   |
| Argentina          | 3         | 0.82%   |
| Switzerland        | 2         | 0.55%   |
| Sweden             | 2         | 0.55%   |
| Slovenia           | 2         | 0.55%   |
| Portugal           | 2         | 0.55%   |
| Lithuania          | 2         | 0.55%   |
| Dominican Republic | 2         | 0.55%   |
| Colombia           | 2         | 0.55%   |
| Chile              | 2         | 0.55%   |
| Belarus            | 2         | 0.55%   |
| Thailand           | 1         | 0.27%   |
| Syria              | 1         | 0.27%   |
| Slovakia           | 1         | 0.27%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Sao Paulo          | 5         | 1.35%   |
| Moscow             | 5         | 1.35%   |
| Berlin             | 5         | 1.35%   |
| Sydney             | 4         | 1.08%   |
| St. Jean Baptiste  | 4         | 1.08%   |
| St Petersburg      | 4         | 1.08%   |
| Wroclaw            | 3         | 0.81%   |
| Warsaw             | 3         | 0.81%   |
| Paris              | 3         | 0.81%   |
| Milan              | 3         | 0.81%   |
| Budapest           | 3         | 0.81%   |
| Brooklyn           | 3         | 0.81%   |
| Belgrade           | 3         | 0.81%   |
| Woodbridge         | 2         | 0.54%   |
| Valencia           | 2         | 0.54%   |
| Sofia              | 2         | 0.54%   |
| Shenzhen           | 2         | 0.54%   |
| Santo Domingo Este | 2         | 0.54%   |
| Santiago           | 2         | 0.54%   |
| Penza              | 2         | 0.54%   |
| Pensacola          | 2         | 0.54%   |
| Odesa              | 2         | 0.54%   |
| New York           | 2         | 0.54%   |
| Montreal           | 2         | 0.54%   |
| Melbourne          | 2         | 0.54%   |
| Madrid             | 2         | 0.54%   |
| Lisbon             | 2         | 0.54%   |
| Krasnodar          | 2         | 0.54%   |
| Krakow             | 2         | 0.54%   |
| Kirov              | 2         | 0.54%   |
| Istanbul           | 2         | 0.54%   |
| Irkutsk            | 2         | 0.54%   |
| Fleurus            | 2         | 0.54%   |
| Dresden            | 2         | 0.54%   |
| Curitiba           | 2         | 0.54%   |
| Buenos Aires       | 2         | 0.54%   |
| Brisbane           | 2         | 0.54%   |
| Bandung            | 2         | 0.54%   |
| Ankara             | 2         | 0.54%   |
| Zurich             | 1         | 0.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 76        | 94     | 15.7%   |
| WDC                 | 67        | 100    | 13.84%  |
| Seagate             | 60        | 85     | 12.4%   |
| Kingston            | 43        | 43     | 8.88%   |
| Toshiba             | 35        | 42     | 7.23%   |
| SanDisk             | 27        | 27     | 5.58%   |
| Hitachi             | 21        | 22     | 4.34%   |
| Crucial             | 20        | 24     | 4.13%   |
| A-DATA Technology   | 11        | 12     | 2.27%   |
| China               | 10        | 11     | 2.07%   |
| Micron Technology   | 8         | 9      | 1.65%   |
| Intel               | 8         | 8      | 1.65%   |
| HGST                | 7         | 10     | 1.45%   |
| Transcend           | 6         | 6      | 1.24%   |
| SK hynix            | 6         | 6      | 1.24%   |
| Patriot             | 5         | 5      | 1.03%   |
| KingSpec            | 5         | 5      | 1.03%   |
| SPCC                | 4         | 4      | 0.83%   |
| Maxtor              | 4         | 4      | 0.83%   |
| Gigabyte Technology | 4         | 5      | 0.83%   |
| Team                | 3         | 3      | 0.62%   |
| PNY                 | 3         | 3      | 0.62%   |
| OCZ                 | 3         | 3      | 0.62%   |
| Intenso             | 3         | 3      | 0.62%   |
| GOODRAM             | 3         | 3      | 0.62%   |
| Netac               | 2         | 2      | 0.41%   |
| Fujitsu             | 2         | 2      | 0.41%   |
| BHT                 | 2         | 2      | 0.41%   |
| Apple               | 2         | 2      | 0.41%   |
| Apacer              | 2         | 2      | 0.41%   |
| WALRAM              | 1         | 1      | 0.21%   |
| Verbatim            | 1         | 1      | 0.21%   |
| Vaseky              | 1         | 1      | 0.21%   |
| V-GeN               | 1         | 1      | 0.21%   |
| UMIS                | 1         | 1      | 0.21%   |
| TAMMUZ              | 1         | 1      | 0.21%   |
| SUNEAST             | 1         | 1      | 0.21%   |
| Silicon Motion      | 1         | 1      | 0.21%   |
| SETHRISE            | 1         | 1      | 0.21%   |
| RX7                 | 1         | 1      | 0.21%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB             | 10        | 1.86%   |
| Samsung SSD 860 EVO 500GB               | 8         | 1.49%   |
| Seagate ST500DM002-1BD142 500GB         | 6         | 1.12%   |
| Samsung SSD 850 EVO 250GB               | 5         | 0.93%   |
| Toshiba MQ01ABF050 500GB                | 4         | 0.74%   |
| Seagate ST3500418AS 500GB               | 4         | 0.74%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 4         | 0.74%   |
| Seagate ST1000DM010-2EP102 1TB          | 4         | 0.74%   |
| Samsung SSD 980 1TB                     | 4         | 0.74%   |
| Samsung SSD 870 EVO 500GB               | 4         | 0.74%   |
| Kingston SA400S37120G 120GB             | 4         | 0.74%   |
| Crucial CT500MX500SSD1 500GB            | 4         | 0.74%   |
| Crucial CT480BX500SSD1 480GB            | 4         | 0.74%   |
| WDC WD20EFRX-68EUZN0 2TB                | 3         | 0.56%   |
| WDC WD10EZEX-08WN4A0 1TB                | 3         | 0.56%   |
| Seagate ST2000DM008-2FR102 2TB          | 3         | 0.56%   |
| SanDisk SSD PLUS 120GB                  | 3         | 0.56%   |
| Samsung SSD 970 EVO Plus 500GB          | 3         | 0.56%   |
| Samsung SSD 970 EVO Plus 1TB            | 3         | 0.56%   |
| Kingston SHFS37A240G 240GB              | 3         | 0.56%   |
| Crucial CT240BX500SSD1 240GB            | 3         | 0.56%   |
| WDC WDS240G2G0A-00JH30 240GB            | 2         | 0.37%   |
| WDC WDS120G2G0A-00JH30 120GB            | 2         | 0.37%   |
| WDC WD5000AAKX-08U6AA0 500GB            | 2         | 0.37%   |
| WDC WD20EZRX-00D8PB0 2TB                | 2         | 0.37%   |
| WDC WD10EZEX-60WN4A1 1TB                | 2         | 0.37%   |
| WDC WD10EZEX-60WN4A0 1TB                | 2         | 0.37%   |
| WDC PC SN520 SDAPNUW-128G-1014 128GB    | 2         | 0.37%   |
| Toshiba MQ01ABD100 1TB                  | 2         | 0.37%   |
| Toshiba HDWD110 1TB                     | 2         | 0.37%   |
| Toshiba DT01ACA100 1TB                  | 2         | 0.37%   |
| Toshiba DT01ACA050 500GB                | 2         | 0.37%   |
| SPCC Solid State Disk 128GB             | 2         | 0.37%   |
| SK hynix BC501 HFM128GDJTNG-8310A 128GB | 2         | 0.37%   |
| Seagate ST9500325AS 500GB               | 2         | 0.37%   |
| Seagate ST9250410AS 250GB               | 2         | 0.37%   |
| Seagate ST500LT012-1DG142 500GB         | 2         | 0.37%   |
| Seagate ST500LM000-1EJ162 500GB         | 2         | 0.37%   |
| Seagate ST1000DM003-1CH162 1TB          | 2         | 0.37%   |
| SanDisk pSSD 256GB                      | 2         | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 60        | 85     | 32.09%  |
| WDC                 | 52        | 81     | 27.81%  |
| Toshiba             | 30        | 35     | 16.04%  |
| Hitachi             | 21        | 22     | 11.23%  |
| Samsung Electronics | 9         | 11     | 4.81%   |
| HGST                | 7         | 10     | 3.74%   |
| Maxtor              | 4         | 4      | 2.14%   |
| Fujitsu             | 2         | 2      | 1.07%   |
| QUANTUM             | 1         | 1      | 0.53%   |
| Apple               | 1         | 1      | 0.53%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 36        | 43     | 16.51%  |
| Kingston            | 33        | 33     | 15.14%  |
| SanDisk             | 27        | 27     | 12.39%  |
| Crucial             | 19        | 22     | 8.72%   |
| China               | 10        | 11     | 4.59%   |
| WDC                 | 9         | 10     | 4.13%   |
| A-DATA Technology   | 7         | 7      | 3.21%   |
| Patriot             | 5         | 5      | 2.29%   |
| KingSpec            | 5         | 5      | 2.29%   |
| Intel               | 5         | 5      | 2.29%   |
| Transcend           | 4         | 4      | 1.83%   |
| Toshiba             | 4         | 6      | 1.83%   |
| SPCC                | 3         | 3      | 1.38%   |
| PNY                 | 3         | 3      | 1.38%   |
| OCZ                 | 3         | 3      | 1.38%   |
| Micron Technology   | 3         | 3      | 1.38%   |
| Intenso             | 3         | 3      | 1.38%   |
| GOODRAM             | 3         | 3      | 1.38%   |
| Gigabyte Technology | 3         | 4      | 1.38%   |
| Team                | 2         | 2      | 0.92%   |
| BHT                 | 2         | 2      | 0.92%   |
| Apacer              | 2         | 2      | 0.92%   |
| WALRAM              | 1         | 1      | 0.46%   |
| Verbatim            | 1         | 1      | 0.46%   |
| Vaseky              | 1         | 1      | 0.46%   |
| V-GeN               | 1         | 1      | 0.46%   |
| TAMMUZ              | 1         | 1      | 0.46%   |
| SUNEAST             | 1         | 1      | 0.46%   |
| SK hynix            | 1         | 1      | 0.46%   |
| SETHRISE            | 1         | 1      | 0.46%   |
| RX7                 | 1         | 1      | 0.46%   |
| Plextor             | 1         | 1      | 0.46%   |
| Pioneer             | 1         | 1      | 0.46%   |
| Philips             | 1         | 1      | 0.46%   |
| Palit               | 1         | 1      | 0.46%   |
| Netac               | 1         | 1      | 0.46%   |
| MidasForce          | 1         | 1      | 0.46%   |
| LITEONIT            | 1         | 1      | 0.46%   |
| Kston               | 1         | 1      | 0.46%   |
| KIOXIA-EXCERIA      | 1         | 1      | 0.46%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 183       | 233    | 42.46%  |
| HDD  | 166       | 252    | 38.52%  |
| NVMe | 82        | 94     | 19.03%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 301       | 485    | 78.59%  |
| NVMe | 82        | 94     | 21.41%  |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 259       | 338    | 72.75%  |
| 0.51-1.0   | 64        | 79     | 17.98%  |
| 1.01-2.0   | 18        | 37     | 5.06%   |
| 3.01-4.0   | 8         | 12     | 2.25%   |
| 2.01-3.0   | 3         | 6      | 0.84%   |
| 4.01-10.0  | 3         | 12     | 0.84%   |
| 10.01-20.0 | 1         | 1      | 0.28%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 1-20       | 184       | 49.73%  |
| 101-250    | 59        | 15.95%  |
| 251-500    | 50        | 13.51%  |
| 51-100     | 47        | 12.7%   |
| 501-1000   | 18        | 4.86%   |
| 21-50      | 9         | 2.43%   |
| Unknown    | 2         | 0.54%   |
| 1001-2000  | 1         | 0.27%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Computers | Percent |
|---------|-----------|---------|
| 1-20    | 360       | 98.36%  |
| 21-50   | 2         | 0.55%   |
| Unknown | 2         | 0.55%   |
| 251-500 | 1         | 0.27%   |
| 101-250 | 1         | 0.27%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                                     | Computers | Drives | Percent |
|-------------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB                 | 2         | 2      | 2.44%   |
| Seagate ST500LM000-1EJ162 500GB           | 2         | 2      | 2.44%   |
| Seagate ST1000LM024 HN-M101MBB 1TB        | 2         | 3      | 2.44%   |
| Hitachi HTS542525K9A300 250GB             | 2         | 2      | 2.44%   |
| WDC WD800JD-75MSA3 80GB                   | 1         | 1      | 1.22%   |
| WDC WD6400BPVT-22HXZT3 640GB              | 1         | 1      | 1.22%   |
| WDC WD5000AAKX-08U6AA0 500GB              | 1         | 1      | 1.22%   |
| WDC WD5000AAKX-00ERMA0 500GB              | 1         | 1      | 1.22%   |
| WDC WD30PURZ-85AKKY0 3TB                  | 1         | 1      | 1.22%   |
| WDC WD30EFRX-68EUZN0 3TB                  | 1         | 1      | 1.22%   |
| WDC WD20EZRX-00D8PB0 2TB                  | 1         | 1      | 1.22%   |
| WDC WD20EARS-00MVWB0 2TB                  | 1         | 1      | 1.22%   |
| WDC WD1600YS-01SHB1 164GB                 | 1         | 1      | 1.22%   |
| WDC WD1600AAJS-60Z0A0 160GB               | 1         | 1      | 1.22%   |
| WDC WD10JPVX-60JC3T1 1TB                  | 1         | 1      | 1.22%   |
| WDC WD10EZEX-60WN4A0 1TB                  | 1         | 1      | 1.22%   |
| WDC WD10EZEX-60M2NA0 1TB                  | 1         | 1      | 1.22%   |
| WDC WD10EARS-003BB1 1TB                   | 1         | 1      | 1.22%   |
| WDC WD10EADS-11M2B2 1TB                   | 1         | 1      | 1.22%   |
| Toshiba MQ01ABF050 500GB                  | 1         | 1      | 1.22%   |
| Toshiba MQ01ABD100 1TB                    | 1         | 1      | 1.22%   |
| Toshiba MQ01ABD032 320GB                  | 1         | 1      | 1.22%   |
| Toshiba MK8052GSX 80GB                    | 1         | 1      | 1.22%   |
| Toshiba MK5059GSXP 500GB                  | 1         | 1      | 1.22%   |
| Toshiba MK3259GSXP 320GB                  | 1         | 1      | 1.22%   |
| Toshiba MK1646GSX 160GB                   | 1         | 1      | 1.22%   |
| Toshiba MK1229GSG 120GB                   | 1         | 1      | 1.22%   |
| Toshiba DT01ACA100 1TB                    | 1         | 1      | 1.22%   |
| SK hynix SC210 mSATA 256GB                | 1         | 1      | 1.22%   |
| Silicon Motion Asgard AN1TNVMe-M.2-80 1TB | 1         | 1      | 1.22%   |
| Seagate ST9250410AS 250GB                 | 1         | 1      | 1.22%   |
| Seagate ST9160827AS 160GB                 | 1         | 1      | 1.22%   |
| Seagate ST9160314AS 160GB                 | 1         | 1      | 1.22%   |
| Seagate ST750LM022 HN-M750MBB 752GB       | 1         | 1      | 1.22%   |
| Seagate ST500LM000-SSHD-8GB               | 1         | 1      | 1.22%   |
| Seagate ST500LM000-1EJ162-SSHD-8GB        | 1         | 1      | 1.22%   |
| Seagate ST500DM002-1BD142 500GB           | 1         | 1      | 1.22%   |
| Seagate ST380215AS 80GB                   | 1         | 1      | 1.22%   |
| Seagate ST3750528AS 752GB                 | 1         | 1      | 1.22%   |
| Seagate ST3500418AS 500GB                 | 1         | 1      | 1.22%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 21        | 26     | 26.58%  |
| WDC                 | 14        | 15     | 17.72%  |
| Hitachi             | 12        | 12     | 15.19%  |
| Toshiba             | 9         | 9      | 11.39%  |
| Samsung Electronics | 5         | 5      | 6.33%   |
| HGST                | 5         | 6      | 6.33%   |
| Maxtor              | 3         | 3      | 3.8%    |
| Crucial             | 3         | 4      | 3.8%    |
| Kingston            | 2         | 2      | 2.53%   |
| SK hynix            | 1         | 1      | 1.27%   |
| Silicon Motion      | 1         | 1      | 1.27%   |
| OCZ                 | 1         | 1      | 1.27%   |
| Intel               | 1         | 1      | 1.27%   |
| China               | 1         | 1      | 1.27%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 21        | 26     | 31.34%  |
| WDC                 | 14        | 15     | 20.9%   |
| Hitachi             | 12        | 12     | 17.91%  |
| Toshiba             | 9         | 9      | 13.43%  |
| HGST                | 5         | 6      | 7.46%   |
| Samsung Electronics | 3         | 3      | 4.48%   |
| Maxtor              | 3         | 3      | 4.48%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 65        | 74     | 84.42%  |
| SSD  | 10        | 11     | 12.99%  |
| NVMe | 2         | 2      | 2.6%    |

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
| Works    | 281       | 473    | 75.74%  |
| Malfunc  | 77        | 87     | 20.75%  |
| Detected | 9         | 15     | 2.43%   |
| Failed   | 4         | 4      | 1.08%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 279       | 62.28%  |
| AMD                                     | 55        | 12.28%  |
| Samsung Electronics                     | 35        | 7.81%   |
| SanDisk                                 | 12        | 2.68%   |
| Kingston Technology Company             | 10        | 2.23%   |
| Nvidia                                  | 9         | 2.01%   |
| Silicon Motion                          | 6         | 1.34%   |
| ASMedia Technology                      | 6         | 1.34%   |
| SK hynix                                | 5         | 1.12%   |
| Micron Technology                       | 5         | 1.12%   |
| Marvell Technology Group                | 5         | 1.12%   |
| Phison Electronics                      | 3         | 0.67%   |
| JMicron Technology                      | 3         | 0.67%   |
| ADATA Technology                        | 3         | 0.67%   |
| VIA Technologies                        | 2         | 0.45%   |
| Realtek Semiconductor                   | 2         | 0.45%   |
| Micron/Crucial Technology               | 2         | 0.45%   |
| Toshiba                                 | 1         | 0.22%   |
| Silicon Integrated Systems [SiS]        | 1         | 0.22%   |
| Shenzhen Unionmemory Information System | 1         | 0.22%   |
| OCZ Technology Group                    | 1         | 0.22%   |
| KIOXIA                                  | 1         | 0.22%   |
| Broadcom / LSI                          | 1         | 0.22%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 29        | 5.6%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 24        | 4.63%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 24        | 4.63%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 20        | 3.86%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 18        | 3.47%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 18        | 3.47%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 15        | 2.9%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 15        | 2.9%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 13        | 2.51%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 12        | 2.32%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 10        | 1.93%   |
| Samsung NVMe SSD Controller 980                                                         | 9         | 1.74%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 9         | 1.74%   |
| AMD 500 Series Chipset SATA Controller                                                  | 9         | 1.74%   |
| AMD 400 Series Chipset SATA Controller                                                  | 9         | 1.74%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 8         | 1.54%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 8         | 1.54%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 7         | 1.35%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 7         | 1.35%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 7         | 1.35%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 7         | 1.35%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 7         | 1.35%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 6         | 1.16%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 6         | 1.16%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 6         | 1.16%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 6         | 1.16%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 5         | 0.97%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 5         | 0.97%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 5         | 0.97%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 5         | 0.97%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 5         | 0.97%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 4         | 0.77%   |
| Nvidia MCP79 AHCI Controller                                                            | 4         | 0.77%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 4         | 0.77%   |
| Intel SATA Controller [RAID mode]                                                       | 4         | 0.77%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 4         | 0.77%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4         | 0.77%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 4         | 0.77%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 4         | 0.77%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 4         | 0.77%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 295       | 65.85%  |
| NVMe | 80        | 17.86%  |
| IDE  | 56        | 12.5%   |
| RAID | 15        | 3.35%   |
| SAS  | 1         | 0.22%   |
| SCSI | 1         | 0.22%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 300       | 81.97%  |
| AMD    | 66        | 18.03%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-6500 CPU @ 3.20GHz            | 6         | 1.64%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 6         | 1.64%   |
| Intel CPU Version                           | 5         | 1.37%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 5         | 1.37%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 5         | 1.37%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 4         | 1.09%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 4         | 1.09%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 4         | 1.09%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 3         | 0.82%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 3         | 0.82%   |
| Intel Core i7-3520M CPU @ 2.90GHz           | 3         | 0.82%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 3         | 0.82%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 3         | 0.82%   |
| Intel Core i5-3337U CPU @ 1.80GHz           | 3         | 0.82%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 3         | 0.82%   |
| Intel Core i3-9100 CPU @ 3.60GHz            | 3         | 0.82%   |
| Intel Core i3-7100 CPU @ 3.90GHz            | 3         | 0.82%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 3         | 0.82%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 3         | 0.82%   |
| Intel Core 2 Duo CPU P7350 @ 2.00GHz        | 3         | 0.82%   |
| Intel Celeron CPU N2840 @ 2.16GHz           | 3         | 0.82%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 3         | 0.82%   |
| Intel Xeon CPU E31220 @ 3.10GHz             | 2         | 0.55%   |
| Intel Pentium CPU P6200 @ 2.13GHz           | 2         | 0.55%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 2         | 0.55%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 2         | 0.55%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 2         | 0.55%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 2         | 0.55%   |
| Intel Core i7-5500U CPU @ 2.40GHz           | 2         | 0.55%   |
| Intel Core i7-2670QM CPU @ 2.20GHz          | 2         | 0.55%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 2         | 0.55%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 2         | 0.55%   |
| Intel Core i5-7300U CPU @ 2.60GHz           | 2         | 0.55%   |
| Intel Core i5-6500T CPU @ 2.50GHz           | 2         | 0.55%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 2         | 0.55%   |
| Intel Core i5-4440 CPU @ 3.10GHz            | 2         | 0.55%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 2         | 0.55%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 2         | 0.55%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 2         | 0.55%   |
| Intel Core i5-2540M CPU @ 2.60GHz           | 2         | 0.55%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 96        | 26.23%  |
| Intel Core i7           | 51        | 13.93%  |
| Intel Core i3           | 36        | 9.84%   |
| Intel Celeron           | 34        | 9.29%   |
| Intel Core 2 Duo        | 25        | 6.83%   |
| AMD Ryzen 5             | 19        | 5.19%   |
| Other                   | 16        | 4.37%   |
| Intel Xeon              | 12        | 3.28%   |
| AMD Ryzen 7             | 10        | 2.73%   |
| Intel Pentium           | 9         | 2.46%   |
| AMD Ryzen 3             | 9         | 2.46%   |
| Intel Pentium Dual-Core | 4         | 1.09%   |
| Intel Atom              | 4         | 1.09%   |
| AMD Phenom II X4        | 3         | 0.82%   |
| AMD Athlon II X2        | 3         | 0.82%   |
| AMD A4                  | 3         | 0.82%   |
| Intel Pentium Silver    | 2         | 0.55%   |
| Intel Pentium Dual      | 2         | 0.55%   |
| Intel Genuine           | 2         | 0.55%   |
| Intel Core i9           | 2         | 0.55%   |
| Intel Core 2 Quad       | 2         | 0.55%   |
| Intel Core 2            | 2         | 0.55%   |
| AMD E                   | 2         | 0.55%   |
| AMD A10                 | 2         | 0.55%   |
| Intel Pentium Gold      | 1         | 0.27%   |
| Intel Pentium 4         | 1         | 0.27%   |
| Intel Celeron D         | 1         | 0.27%   |
| AMD Ryzen Embedded      | 1         | 0.27%   |
| AMD Ryzen 9             | 1         | 0.27%   |
| AMD Phenom II X6        | 1         | 0.27%   |
| AMD Phenom II X2        | 1         | 0.27%   |
| AMD Phenom II           | 1         | 0.27%   |
| AMD FX                  | 1         | 0.27%   |
| AMD E2                  | 1         | 0.27%   |
| AMD E1                  | 1         | 0.27%   |
| AMD Athlon X2           | 1         | 0.27%   |
| AMD Athlon II X4        | 1         | 0.27%   |
| AMD Athlon 64           | 1         | 0.27%   |
| AMD Athlon              | 1         | 0.27%   |
| AMD A8                  | 1         | 0.27%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 157       | 42.9%   |
| 4       | 120       | 32.79%  |
| Unknown | 27        | 7.38%   |
| 6       | 20        | 5.46%   |
| 12      | 14        | 3.83%   |
| 8       | 13        | 3.55%   |
| 16      | 7         | 1.91%   |
| 1       | 6         | 1.64%   |
| 24      | 1         | 0.27%   |
| 10      | 1         | 0.27%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 359       | 98.09%  |
| 2      | 7         | 1.91%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 168       | 45.9%   |
| 1       | 167       | 45.63%  |
| Unknown | 31        | 8.47%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 50        | 13.66%  |
| IvyBridge     | 38        | 10.38%  |
| Haswell       | 38        | 10.38%  |
| SandyBridge   | 32        | 8.74%   |
| Skylake       | 28        | 7.65%   |
| Penryn        | 24        | 6.56%   |
| Core          | 20        | 5.46%   |
| Zen+          | 17        | 4.64%   |
| Zen 3         | 12        | 3.28%   |
| Westmere      | 12        | 3.28%   |
| Silvermont    | 12        | 3.28%   |
| K10           | 11        | 3.01%   |
| Unknown       | 9         | 2.46%   |
| Broadwell     | 8         | 2.19%   |
| Goldmont plus | 7         | 1.91%   |
| CometLake     | 7         | 1.91%   |
| Zen           | 6         | 1.64%   |
| Bonnell       | 5         | 1.37%   |
| Zen 2         | 4         | 1.09%   |
| TigerLake     | 4         | 1.09%   |
| Piledriver    | 4         | 1.09%   |
| Bobcat        | 4         | 1.09%   |
| Nehalem       | 3         | 0.82%   |
| Goldmont      | 3         | 0.82%   |
| Excavator     | 3         | 0.82%   |
| NetBurst      | 1         | 0.27%   |
| K8 Hammer     | 1         | 0.27%   |
| K10 Llano     | 1         | 0.27%   |
| IceLake       | 1         | 0.27%   |
| Bulldozer     | 1         | 0.27%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 237       | 57.95%  |
| Nvidia                           | 86        | 21.03%  |
| AMD                              | 84        | 20.54%  |
| Silicon Integrated Systems [SiS] | 1         | 0.24%   |
| Matrox Electronics Systems       | 1         | 0.24%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 26        | 6.13%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 20        | 4.72%   |
| Intel HD Graphics 530                                                                    | 13        | 3.07%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 12        | 2.83%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 11        | 2.59%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 10        | 2.36%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 10        | 2.36%   |
| Intel HD Graphics 630                                                                    | 10        | 2.36%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 10        | 2.36%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 9         | 2.12%   |
| Intel Core Processor Integrated Graphics Controller                                      | 9         | 2.12%   |
| Intel UHD Graphics 620                                                                   | 8         | 1.89%   |
| Intel HD Graphics 5500                                                                   | 8         | 1.89%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 7         | 1.65%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 7         | 1.65%   |
| Intel HD Graphics 620                                                                    | 7         | 1.65%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 7         | 1.65%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 6         | 1.42%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 6         | 1.42%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 6         | 1.42%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 6         | 1.42%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 5         | 1.18%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 5         | 1.18%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 4         | 0.94%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 0.94%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 4         | 0.94%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 4         | 0.94%   |
| AMD Renoir                                                                               | 4         | 0.94%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 4         | 0.94%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 3         | 0.71%   |
| Nvidia GT218 [GeForce 210]                                                               | 3         | 0.71%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 0.71%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 3         | 0.71%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 3         | 0.71%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 3         | 0.71%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 0.71%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 3         | 0.71%   |
| Intel HD Graphics 500                                                                    | 3         | 0.71%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 0.71%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 3         | 0.71%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 167       | 45.38%  |
| 1 x AMD        | 65        | 17.66%  |
| 1 x Nvidia     | 57        | 15.49%  |
| 2 x Intel      | 29        | 7.88%   |
| Intel + Nvidia | 26        | 7.07%   |
| Intel + AMD    | 16        | 4.35%   |
| 2 x AMD        | 2         | 0.54%   |
| AMD + Nvidia   | 2         | 0.54%   |
| Other          | 1         | 0.27%   |
| 2 x Nvidia     | 1         | 0.27%   |
| 1 x SiS        | 1         | 0.27%   |
| 1 x Matrox     | 1         | 0.27%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 309       | 84.2%   |
| Proprietary | 46        | 12.53%  |
| Unknown     | 12        | 3.27%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 284       | 77.17%  |
| 1.01-2.0   | 19        | 5.16%   |
| 0.01-0.5   | 19        | 5.16%   |
| 3.01-4.0   | 16        | 4.35%   |
| 0.51-1.0   | 14        | 3.8%    |
| 5.01-6.0   | 8         | 2.17%   |
| 7.01-8.0   | 5         | 1.36%   |
| 8.01-16.0  | 2         | 0.54%   |
| 2.01-3.0   | 1         | 0.27%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 21        | 14.19%  |
| Samsung Electronics     | 16        | 10.81%  |
| Dell                    | 10        | 6.76%   |
| Goldstar                | 9         | 6.08%   |
| LG Display              | 8         | 5.41%   |
| BOE                     | 8         | 5.41%   |
| Hewlett-Packard         | 7         | 4.73%   |
| Chimei Innolux          | 7         | 4.73%   |
| BenQ                    | 7         | 4.73%   |
| Acer                    | 7         | 4.73%   |
| Lenovo                  | 6         | 4.05%   |
| AOC                     | 5         | 3.38%   |
| Ancor Communications    | 4         | 2.7%    |
| Philips                 | 3         | 2.03%   |
| Chi Mei Optoelectronics | 3         | 2.03%   |
| Apple                   | 3         | 2.03%   |
| Unknown                 | 3         | 2.03%   |
| Sharp                   | 2         | 1.35%   |
| LG Electronics          | 2         | 1.35%   |
| InfoVision              | 2         | 1.35%   |
| ASUSTek Computer        | 2         | 1.35%   |
| Vizio                   | 1         | 0.68%   |
| Semp Toshiba            | 1         | 0.68%   |
| PKB                     | 1         | 0.68%   |
| NEC Computers           | 1         | 0.68%   |
| MStar                   | 1         | 0.68%   |
| MSI                     | 1         | 0.68%   |
| Microstep               | 1         | 0.68%   |
| LG Philips              | 1         | 0.68%   |
| ITE                     | 1         | 0.68%   |
| Idek Iiyama             | 1         | 0.68%   |
| Eizo                    | 1         | 0.68%   |
| CPT                     | 1         | 0.68%   |
| AUS                     | 1         | 0.68%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                | 3         | 2.03%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 340x190mm 15.3-inch   | 2         | 1.35%   |
| Lenovo LCD Monitor LEN4022 1400x1050 290x210mm 14.1-inch               | 2         | 1.35%   |
| Goldstar W1934 GSM4B7A 1440x900 410x260mm 19.1-inch                    | 2         | 1.35%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch          | 2         | 1.35%   |
| Acer G276HL ACR0300 1920x1080 600x340mm 27.2-inch                      | 2         | 1.35%   |
| Vizio E321VL VIZ0083 1366x768 700x400mm 31.7-inch                      | 1         | 0.68%   |
| Sharp LQ133M1JW01 SHP141B 1920x1080 290x170mm 13.2-inch                | 1         | 0.68%   |
| Sharp LCD Monitor SHP143B 3840x2160 350x190mm 15.7-inch                | 1         | 0.68%   |
| Semp Toshiba MLE1951 STI1951 1366x768 410x230mm 18.5-inch              | 1         | 0.68%   |
| Samsung Electronics SyncMaster SAM058D 1600x900 440x250mm 19.9-inch    | 1         | 0.68%   |
| Samsung Electronics SyncMaster SAM050B 1920x1080 480x270mm 21.7-inch   | 1         | 0.68%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 600x340mm 27.2-inch      | 1         | 0.68%   |
| Samsung Electronics S24C350 SAM0A3A 1920x1080 530x300mm 24.0-inch      | 1         | 0.68%   |
| Samsung Electronics S22B150 SAM08A3 1920x1080 480x270mm 21.7-inch      | 1         | 0.68%   |
| Samsung Electronics S20B300 SAM08A7 1600x900 440x250mm 19.9-inch       | 1         | 0.68%   |
| Samsung Electronics S19B150 SAM08A2 1366x768 410x230mm 18.5-inch       | 1         | 0.68%   |
| Samsung Electronics Odyssey G50A SAM7181 2560x1440 600x340mm 27.2-inch | 1         | 0.68%   |
| Samsung Electronics LF27T370F SAM711E 1920x1080 600x340mm 27.2-inch    | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SEC384A 1366x768 340x190mm 15.3-inch   | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SEC3541 1366x768 300x170mm 13.6-inch   | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SEC3050 1366x768 320x190mm 14.7-inch   | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 530x300mm 24.0-inch   | 1         | 0.68%   |
| Samsung Electronics C32HG7x SAM0E13 2560x1440 700x390mm 31.5-inch      | 1         | 0.68%   |
| PKB LCD Monitor MAE200W 1680x1050                                      | 1         | 0.68%   |
| Philips PHL 223V7 PHLC154 1920x1080 480x270mm 21.7-inch                | 1         | 0.68%   |
| Philips PHL 221S8L PHL091C 1920x1080 480x270mm 21.7-inch               | 1         | 0.68%   |
| Philips 150S PHL0820 1024x768 300x230mm 14.9-inch                      | 1         | 0.68%   |
| NEC Computers LCD Monitor 70GX2 1280x1024                              | 1         | 0.68%   |
| MStar TSB LEDTV MST0030 1920x1080 1150x650mm 52.0-inch                 | 1         | 0.68%   |
| MSI MP242 MSI30A1 1920x1080 530x300mm 24.0-inch                        | 1         | 0.68%   |
| Microstep LCD Monitor MSI MAG241C 1920x1080                            | 1         | 0.68%   |
| LG Philips LP154WX4-TLCB LPL3101 1280x800 330x210mm 15.4-inch          | 1         | 0.68%   |
| LG Electronics LCD Monitor LG FULL HD 1920x1080                        | 1         | 0.68%   |
| LG Electronics LCD Monitor L1918S 1280x1024                            | 1         | 0.68%   |
| LG Display LCD Monitor LGD0555 2736x1824 260x170mm 12.2-inch           | 1         | 0.68%   |
| LG Display LCD Monitor LGD04E8 1920x1080 380x210mm 17.1-inch           | 1         | 0.68%   |
| LG Display LCD Monitor LGD03DB 1366x768 350x190mm 15.7-inch            | 1         | 0.68%   |
| LG Display LCD Monitor LGD0384 1366x768 340x190mm 15.3-inch            | 1         | 0.68%   |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch            | 1         | 0.68%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 63        | 43.15%  |
| 1366x768 (WXGA)    | 39        | 26.71%  |
| 2560x1440 (QHD)    | 7         | 4.79%   |
| 1600x900 (HD+)     | 6         | 4.11%   |
| 3840x2160 (4K)     | 4         | 2.74%   |
| 1280x800 (WXGA)    | 4         | 2.74%   |
| 2560x1600          | 3         | 2.05%   |
| 1680x1050 (WSXGA+) | 3         | 2.05%   |
| 1440x900 (WXGA+)   | 3         | 2.05%   |
| 1280x1024 (SXGA)   | 3         | 2.05%   |
| 1920x1200 (WUXGA)  | 2         | 1.37%   |
| 1400x1050          | 2         | 1.37%   |
| Unknown            | 2         | 1.37%   |
| 5760x2160          | 1         | 0.68%   |
| 3840x1080          | 1         | 0.68%   |
| 2736x1824          | 1         | 0.68%   |
| 1024x768 (XGA)     | 1         | 0.68%   |
| 1024x600           | 1         | 0.68%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 26        | 17.93%  |
| 13      | 19        | 13.1%   |
| Unknown | 19        | 13.1%   |
| 21      | 16        | 11.03%  |
| 24      | 10        | 6.9%    |
| 27      | 9         | 6.21%   |
| 19      | 6         | 4.14%   |
| 17      | 6         | 4.14%   |
| 23      | 5         | 3.45%   |
| 18      | 5         | 3.45%   |
| 14      | 5         | 3.45%   |
| 12      | 5         | 3.45%   |
| 31      | 4         | 2.76%   |
| 20      | 3         | 2.07%   |
| 11      | 3         | 2.07%   |
| 52      | 1         | 0.69%   |
| 29      | 1         | 0.69%   |
| 22      | 1         | 0.69%   |
| 9       | 1         | 0.69%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 40        | 27.59%  |
| 401-500     | 30        | 20.69%  |
| 501-600     | 24        | 16.55%  |
| 201-300     | 19        | 13.1%   |
| Unknown     | 19        | 13.1%   |
| 351-400     | 7         | 4.83%   |
| 601-700     | 5         | 3.45%   |
| 1001-1500   | 1         | 0.69%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 103       | 73.57%  |
| Unknown | 19        | 13.57%  |
| 16/10   | 13        | 9.29%   |
| 4/3     | 3         | 2.14%   |
| 5/4     | 1         | 0.71%   |
| 3/2     | 1         | 0.71%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 31        | 21.38%  |
| 91-100         | 23        | 15.86%  |
| Unknown        | 19        | 13.1%   |
| 81-90          | 15        | 10.34%  |
| 301-350        | 9         | 6.21%   |
| 151-200        | 9         | 6.21%   |
| 101-110        | 7         | 4.83%   |
| 121-130        | 6         | 4.14%   |
| 71-80          | 5         | 3.45%   |
| 61-70          | 5         | 3.45%   |
| 351-500        | 5         | 3.45%   |
| 141-150        | 5         | 3.45%   |
| 51-60          | 3         | 2.07%   |
| More than 1000 | 1         | 0.69%   |
| 41-50          | 1         | 0.69%   |
| 251-300        | 1         | 0.69%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 43        | 29.86%  |
| 51-100        | 42        | 29.17%  |
| 121-160       | 34        | 23.61%  |
| Unknown       | 19        | 13.19%  |
| More than 240 | 2         | 1.39%   |
| 1-50          | 2         | 1.39%   |
| 161-240       | 2         | 1.39%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 309       | 84.2%   |
| 0     | 43        | 11.72%  |
| 2     | 15        | 4.09%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 186       | 35.84%  |
| Intel                             | 177       | 34.1%   |
| Qualcomm Atheros                  | 68        | 13.1%   |
| Broadcom                          | 21        | 4.05%   |
| Marvell Technology Group          | 9         | 1.73%   |
| Samsung Electronics               | 8         | 1.54%   |
| Ralink                            | 6         | 1.16%   |
| TP-Link                           | 5         | 0.96%   |
| Sierra Wireless                   | 5         | 0.96%   |
| Xiaomi                            | 4         | 0.77%   |
| Ralink Technology                 | 4         | 0.77%   |
| Nvidia                            | 4         | 0.77%   |
| MediaTek                          | 4         | 0.77%   |
| Ericsson Business Mobile Networks | 3         | 0.58%   |
| JMicron Technology                | 2         | 0.39%   |
| Huawei Technologies               | 2         | 0.39%   |
| Edimax Technology                 | 2         | 0.39%   |
| D-Link                            | 2         | 0.39%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.19%   |
| Qualcomm                          | 1         | 0.19%   |
| National Semiconductor            | 1         | 0.19%   |
| Google                            | 1         | 0.19%   |
| D-Link System                     | 1         | 0.19%   |
| Atheros                           | 1         | 0.19%   |
| Accton Technology                 | 1         | 0.19%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 135       | 21.63%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 27        | 4.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 26        | 4.17%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 13        | 2.08%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 13        | 2.08%   |
| Intel Wireless 8265 / 8275                                              | 12        | 1.92%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 12        | 1.92%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 10        | 1.6%    |
| Intel Wireless 8260                                                     | 10        | 1.6%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 9         | 1.44%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 9         | 1.44%   |
| Intel Ethernet Connection (2) I219-LM                                   | 9         | 1.44%   |
| Intel Wireless 7265                                                     | 8         | 1.28%   |
| Intel Wireless 3165                                                     | 8         | 1.28%   |
| Intel Ethernet Connection I217-LM                                       | 8         | 1.28%   |
| Intel Ethernet Controller I225-V                                        | 7         | 1.12%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 6         | 0.96%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 6         | 0.96%   |
| Intel Wireless 7260                                                     | 6         | 0.96%   |
| Intel Wi-Fi 6 AX200                                                     | 6         | 0.96%   |
| Intel Ethernet Connection I219-LM                                       | 6         | 0.96%   |
| Intel Ethernet Connection I217-V                                        | 6         | 0.96%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 5         | 0.8%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 5         | 0.8%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 5         | 0.8%    |
| Intel 82579V Gigabit Network Connection                                 | 5         | 0.8%    |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 4         | 0.64%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 0.64%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 4         | 0.64%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 4         | 0.64%   |
| Nvidia MCP79 Ethernet                                                   | 4         | 0.64%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 4         | 0.64%   |
| Intel Ethernet Connection (4) I219-LM                                   | 4         | 0.64%   |
| Intel 82574L Gigabit Network Connection                                 | 4         | 0.64%   |
| Intel 82567LM Gigabit Network Connection                                | 4         | 0.64%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 4         | 0.64%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 0.64%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 3         | 0.48%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 3         | 0.48%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 3         | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 116       | 44.79%  |
| Qualcomm Atheros      | 55        | 21.24%  |
| Realtek Semiconductor | 42        | 16.22%  |
| Broadcom              | 18        | 6.95%   |
| Ralink                | 6         | 2.32%   |
| TP-Link               | 5         | 1.93%   |
| Ralink Technology     | 4         | 1.54%   |
| Sierra Wireless       | 3         | 1.16%   |
| MediaTek              | 3         | 1.16%   |
| Edimax Technology     | 2         | 0.77%   |
| D-Link                | 2         | 0.77%   |
| D-Link System         | 1         | 0.39%   |
| Atheros               | 1         | 0.39%   |
| Accton Technology     | 1         | 0.39%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 13        | 4.92%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 13        | 4.92%   |
| Intel Wireless 8265 / 8275                                              | 12        | 4.55%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 12        | 4.55%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 10        | 3.79%   |
| Intel Wireless 8260                                                     | 10        | 3.79%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 9         | 3.41%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 9         | 3.41%   |
| Intel Wireless 7265                                                     | 8         | 3.03%   |
| Intel Wireless 3165                                                     | 8         | 3.03%   |
| Intel Wireless 7260                                                     | 6         | 2.27%   |
| Intel Wi-Fi 6 AX200                                                     | 6         | 2.27%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 5         | 1.89%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 5         | 1.89%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 5         | 1.89%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 1.52%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 4         | 1.52%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 4         | 1.52%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 4         | 1.52%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 1.52%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 3         | 1.14%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 3         | 1.14%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 3         | 1.14%   |
| Intel Wi-Fi 6 AX201                                                     | 3         | 1.14%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 3         | 1.14%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 1.14%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 1.14%   |
| Intel Centrino Wireless-N 2230                                          | 3         | 1.14%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 3         | 1.14%   |
| Intel Centrino Advanced-N 6200                                          | 3         | 1.14%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 3         | 1.14%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 0.76%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 2         | 0.76%   |
| Sierra Wireless EM7345 4G LTE                                           | 2         | 0.76%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.76%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                         | 2         | 0.76%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 2         | 0.76%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 0.76%   |
| Realtek Realtek Bluetooth 4.2 Adapter                                   | 2         | 0.76%   |
| Realtek 8811CU Wireless LAN 802.11ac USB NIC                            | 2         | 0.76%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 168       | 48.14%  |
| Intel                            | 122       | 34.96%  |
| Qualcomm Atheros                 | 20        | 5.73%   |
| Marvell Technology Group         | 9         | 2.58%   |
| Samsung Electronics              | 8         | 2.29%   |
| Broadcom                         | 6         | 1.72%   |
| Xiaomi                           | 4         | 1.15%   |
| Nvidia                           | 4         | 1.15%   |
| JMicron Technology               | 2         | 0.57%   |
| Huawei Technologies              | 2         | 0.57%   |
| Silicon Integrated Systems [SiS] | 1         | 0.29%   |
| Qualcomm                         | 1         | 0.29%   |
| National Semiconductor           | 1         | 0.29%   |
| MediaTek                         | 1         | 0.29%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 135       | 38.24%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 27        | 7.65%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 26        | 7.37%   |
| Intel Ethernet Connection (2) I219-LM                             | 9         | 2.55%   |
| Intel Ethernet Connection I217-LM                                 | 8         | 2.27%   |
| Intel Ethernet Controller I225-V                                  | 7         | 1.98%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 6         | 1.7%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 6         | 1.7%    |
| Intel Ethernet Connection I219-LM                                 | 6         | 1.7%    |
| Intel Ethernet Connection I217-V                                  | 6         | 1.7%    |
| Intel 82579V Gigabit Network Connection                           | 5         | 1.42%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 4         | 1.13%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 4         | 1.13%   |
| Nvidia MCP79 Ethernet                                             | 4         | 1.13%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 1.13%   |
| Intel 82574L Gigabit Network Connection                           | 4         | 1.13%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 1.13%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 0.85%   |
| Intel I211 Gigabit Network Connection                             | 3         | 0.85%   |
| Intel Ethernet Connection (7) I219-V                              | 3         | 0.85%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 0.85%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 0.85%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 0.85%   |
| Intel 82566MM Gigabit Network Connection                          | 3         | 0.85%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 0.57%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 0.57%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.57%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 0.57%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 0.57%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 2         | 0.57%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 2         | 0.57%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 2         | 0.57%   |
| Intel I210 Gigabit Network Connection                             | 2         | 0.57%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 0.57%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 0.57%   |
| Intel Ethernet Connection (5) I219-LM                             | 2         | 0.57%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 0.57%   |
| Intel Ethernet Connection (17) I219-V                             | 2         | 0.57%   |
| Intel 82573L Gigabit Ethernet Controller                          | 2         | 0.57%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2         | 0.57%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 336       | 57.14%  |
| WiFi     | 245       | 41.67%  |
| Unknown  | 6         | 1.02%   |
| Modem    | 1         | 0.17%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 225       | 68.39%  |
| WiFi     | 104       | 31.61%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 200       | 54.5%   |
| 1     | 156       | 42.51%  |
| 0     | 6         | 1.63%   |
| 3     | 5         | 1.36%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 343       | 92.7%   |
| Yes  | 27        | 7.3%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 78        | 41.71%  |
| Realtek Semiconductor           | 20        | 10.7%   |
| Qualcomm Atheros Communications | 16        | 8.56%   |
| Broadcom                        | 15        | 8.02%   |
| Cambridge Silicon Radio         | 11        | 5.88%   |
| Apple                           | 9         | 4.81%   |
| Foxconn / Hon Hai               | 8         | 4.28%   |
| ASUSTek Computer                | 7         | 3.74%   |
| Lite-On Technology              | 6         | 3.21%   |
| IMC Networks                    | 6         | 3.21%   |
| Hewlett-Packard                 | 3         | 1.6%    |
| TP-Link                         | 2         | 1.07%   |
| Dell                            | 2         | 1.07%   |
| Primax Electronics              | 1         | 0.53%   |
| Fujitsu                         | 1         | 0.53%   |
| Askey Computer                  | 1         | 0.53%   |
| Alps Electric                   | 1         | 0.53%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 44        | 23.53%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 11        | 5.88%   |
| Realtek Bluetooth Adapter                                   | 10        | 5.35%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 9         | 4.81%   |
| Intel AX201 Bluetooth                                       | 9         | 4.81%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 7         | 3.74%   |
| Intel Wireless-AC 3168 Bluetooth                            | 5         | 2.67%   |
| Intel AX200 Bluetooth                                       | 5         | 2.67%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 4         | 2.14%   |
| Apple Bluetooth Host Controller                             | 4         | 2.14%   |
| Realtek  Bluetooth 4.2 Adapter                              | 3         | 1.6%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 3         | 1.6%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 3         | 1.6%    |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]          | 3         | 1.6%    |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 3         | 1.6%    |
| ASUS BT-270 Bluetooth Adapter                               | 3         | 1.6%    |
| TP-Link Bluetooth 5.0 USB Adapter                           | 2         | 1.07%   |
| Realtek RTL8821A Bluetooth                                  | 2         | 1.07%   |
| Realtek Bluetooth 4.0 Adapter                               | 2         | 1.07%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 2         | 1.07%   |
| Lite-On Bluetooth USB Module                                | 2         | 1.07%   |
| Lite-On Atheros AR3012 Bluetooth                            | 2         | 1.07%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                | 2         | 1.07%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device             | 2         | 1.07%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth USB Device    | 2         | 1.07%   |
| Broadcom BCM20702A0 Bluetooth 4.0                           | 2         | 1.07%   |
| Apple Built-in iSight (no firmware loaded)                  | 2         | 1.07%   |
| Realtek Bluetooth 5.1 Adapter                               | 1         | 0.53%   |
| Realtek Bluetooth 4.2 Adapter                               | 1         | 0.53%   |
| Realtek Bluetooth 4.0 + High Speed Chip                     | 1         | 0.53%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 1         | 0.53%   |
| Qualcomm Atheros Dell Wireless 1901 Bluetooth               | 1         | 0.53%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 1         | 0.53%   |
| Qualcomm Atheros Dell Wireless 1703 Bluetooth               | 1         | 0.53%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 1         | 0.53%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)             | 1         | 0.53%   |
| Qualcomm Atheros AR3011 Bluetooth                           | 1         | 0.53%   |
| Primax Rocketfish RF-FLBTAD Bluetooth Adapter               | 1         | 0.53%   |
| Lite-On Qualcomm Atheros Bluetooth 4.0 + HS                 | 1         | 0.53%   |
| Lite-On Qualcomm Atheros Bluetooth                          | 1         | 0.53%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 286       | 59.83%  |
| AMD                               | 89        | 18.62%  |
| Nvidia                            | 59        | 12.34%  |
| C-Media Electronics               | 15        | 3.14%   |
| Texas Instruments                 | 5         | 1.05%   |
| Creative Labs                     | 3         | 0.63%   |
| Realtek Semiconductor             | 2         | 0.42%   |
| Generalplus Technology            | 2         | 0.42%   |
| Unknown                           | 2         | 0.42%   |
| Yamaha                            | 1         | 0.21%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.21%   |
| Razer USA                         | 1         | 0.21%   |
| Phison Electronics                | 1         | 0.21%   |
| OPPO Electronics                  | 1         | 0.21%   |
| KTMicro                           | 1         | 0.21%   |
| JMTek                             | 1         | 0.21%   |
| Hewlett-Packard                   | 1         | 0.21%   |
| HECATE G2 GAMING HEADSET          | 1         | 0.21%   |
| Harman                            | 1         | 0.21%   |
| GN Netcom                         | 1         | 0.21%   |
| GEMBIRD                           | 1         | 0.21%   |
| Elitegroup Computer Systems (ECS) | 1         | 0.21%   |
| Edifier Technology                | 1         | 0.21%   |
| Conexant Systems                  | 1         | 0.21%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 33        | 5.84%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 32        | 5.66%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 26        | 4.6%    |
| AMD Family 17h/19h HD Audio Controller                                                            | 26        | 4.6%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 25        | 4.42%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 21        | 3.72%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 18        | 3.19%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 17        | 3.01%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 16        | 2.83%   |
| Intel 200 Series PCH HD Audio                                                                     | 14        | 2.48%   |
| Intel Cannon Lake PCH cAVS                                                                        | 12        | 2.12%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 12        | 2.12%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 11        | 1.95%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 10        | 1.77%   |
| Intel 8 Series HD Audio Controller                                                                | 10        | 1.77%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 10        | 1.77%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 9         | 1.59%   |
| Intel Broadwell-U Audio Controller                                                                | 8         | 1.42%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 8         | 1.42%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 8         | 1.42%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 8         | 1.42%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 7         | 1.24%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 7         | 1.24%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 7         | 1.24%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 7         | 1.24%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 7         | 1.24%   |
| AMD FCH Azalia Controller                                                                         | 7         | 1.24%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 7         | 1.24%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 6         | 1.06%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 5         | 0.88%   |
| Nvidia MCP79 High Definition Audio                                                                | 5         | 0.88%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 5         | 0.88%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 5         | 0.88%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 5         | 0.88%   |
| Nvidia High Definition Audio Controller                                                           | 4         | 0.71%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 4         | 0.71%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 4         | 0.71%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 4         | 0.71%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 4         | 0.71%   |
| Nvidia MCP61 High Definition Audio                                                                | 3         | 0.53%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 89        | 20.89%  |
| SK hynix            | 61        | 14.32%  |
| Kingston            | 47        | 11.03%  |
| Unknown             | 41        | 9.62%   |
| Micron Technology   | 33        | 7.75%   |
| Corsair             | 23        | 5.4%    |
| Crucial             | 22        | 5.16%   |
| Unknown             | 21        | 4.93%   |
| Nanya Technology    | 10        | 2.35%   |
| G.Skill             | 10        | 2.35%   |
| A-DATA Technology   | 9         | 2.11%   |
| Ramaxel Technology  | 7         | 1.64%   |
| Elpida              | 6         | 1.41%   |
| Unknown (ABCD)      | 5         | 1.17%   |
| Patriot             | 5         | 1.17%   |
| Transcend           | 4         | 0.94%   |
| Smart               | 4         | 0.94%   |
| Apacer              | 3         | 0.7%    |
| Team                | 2         | 0.47%   |
| SHARETRONIC         | 2         | 0.47%   |
| Multilaser          | 2         | 0.47%   |
| Kingmax             | 2         | 0.47%   |
| GOODRAM             | 2         | 0.47%   |
| Atermiter           | 2         | 0.47%   |
| Unknown (8A02)      | 1         | 0.23%   |
| Toshiba             | 1         | 0.23%   |
| Teikon              | 1         | 0.23%   |
| Swissbit            | 1         | 0.23%   |
| Silicon Power       | 1         | 0.23%   |
| Qumo                | 1         | 0.23%   |
| MemoWise            | 1         | 0.23%   |
| Lexar               | 1         | 0.23%   |
| Lenovo              | 1         | 0.23%   |
| Juhor               | 1         | 0.23%   |
| Golden Empire       | 1         | 0.23%   |
| Avant               | 1         | 0.23%   |
| ASint Technology    | 1         | 0.23%   |
| AMD                 | 1         | 0.23%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 21        | 4.66%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 6         | 1.33%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 5         | 1.11%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 1.11%   |
| Unknown RAM Module 1GB SODIMM DDR2                               | 4         | 0.89%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 4         | 0.89%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s            | 4         | 0.89%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 3         | 0.67%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 3         | 0.67%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 3         | 0.67%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM 1067MT/s                 | 3         | 0.67%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s            | 3         | 0.67%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 3         | 0.67%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s            | 3         | 0.67%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 2         | 0.44%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 2         | 0.44%   |
| Unknown RAM Module 2GB DIMM 800MT/s                              | 2         | 0.44%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                             | 2         | 0.44%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 2         | 0.44%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s     | 2         | 0.44%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.44%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.44%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.44%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s           | 2         | 0.44%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB Row Of Chips DDR4 3200MT/s     | 2         | 0.44%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s           | 2         | 0.44%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2133MT/s           | 2         | 0.44%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 2         | 0.44%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 1333MT/s            | 2         | 0.44%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 0.44%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 0.44%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.44%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.44%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 2         | 0.44%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 2         | 0.44%   |
| Samsung RAM M471A5143EB0-CPB 4GB SODIMM DDR4 2133MT/s            | 2         | 0.44%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 0.44%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.44%   |
| Samsung RAM M4 70T5663QZ3-CF7 2GB SODIMM DDR2 2048MT/s           | 2         | 0.44%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s              | 2         | 0.44%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 155       | 42.82%  |
| DDR4    | 141       | 38.95%  |
| DDR2    | 33        | 9.12%   |
| Unknown | 17        | 4.7%    |
| LPDDR4  | 7         | 1.93%   |
| SDRAM   | 5         | 1.38%   |
| LPDDR3  | 2         | 0.55%   |
| DDR     | 2         | 0.55%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 200       | 55.4%   |
| DIMM         | 146       | 40.44%  |
| Row Of Chips | 7         | 1.94%   |
| Chip         | 4         | 1.11%   |
| Unknown      | 4         | 1.11%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 141       | 34.9%   |
| 4096  | 124       | 30.69%  |
| 2048  | 79        | 19.55%  |
| 16384 | 33        | 8.17%   |
| 1024  | 24        | 5.94%   |
| 32768 | 3         | 0.74%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 86        | 22.22%  |
| 1333    | 49        | 12.66%  |
| 2400    | 43        | 11.11%  |
| 3200    | 33        | 8.53%   |
| 2667    | 33        | 8.53%   |
| 2133    | 31        | 8.01%   |
| 667     | 22        | 5.68%   |
| 1067    | 17        | 4.39%   |
| 800     | 16        | 4.13%   |
| Unknown | 12        | 3.1%    |
| 1334    | 9         | 2.33%   |
| 3600    | 6         | 1.55%   |
| 1066    | 6         | 1.55%   |
| 1867    | 5         | 1.29%   |
| 2666    | 4         | 1.03%   |
| 3733    | 2         | 0.52%   |
| 3000    | 2         | 0.52%   |
| 2048    | 2         | 0.52%   |
| 533     | 2         | 0.52%   |
| 400     | 2         | 0.52%   |
| 4400    | 1         | 0.26%   |
| 3333    | 1         | 0.26%   |
| 1866    | 1         | 0.26%   |
| 1639    | 1         | 0.26%   |
| 1200    | 1         | 0.26%   |

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
| Chicony Electronics                    | 40        | 26.49%  |
| Bison Electronics                      | 20        | 13.25%  |
| Microdia                               | 13        | 8.61%   |
| Sunplus Innovation Technology          | 9         | 5.96%   |
| Realtek Semiconductor                  | 9         | 5.96%   |
| IMC Networks                           | 9         | 5.96%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 3.97%   |
| Syntek                                 | 4         | 2.65%   |
| Silicon Motion                         | 4         | 2.65%   |
| Quanta                                 | 4         | 2.65%   |
| Logitech                               | 4         | 2.65%   |
| Lite-On Technology                     | 4         | 2.65%   |
| Alcor Micro                            | 4         | 2.65%   |
| Suyin                                  | 3         | 1.99%   |
| Lenovo                                 | 3         | 1.99%   |
| Importek                               | 2         | 1.32%   |
| Apple                                  | 2         | 1.32%   |
| Z-Star Microelectronics                | 1         | 0.66%   |
| Y Media                                | 1         | 0.66%   |
| Trust                                  | 1         | 0.66%   |
| Supreme Electronics                    | 1         | 0.66%   |
| SHENZHEN AONI ELECTRONIC               | 1         | 0.66%   |
| Luxvisions Innotech Limited            | 1         | 0.66%   |
| Intel                                  | 1         | 0.66%   |
| Genesys Logic                          | 1         | 0.66%   |
| GEMBIRD                                | 1         | 0.66%   |
| DigiTech                               | 1         | 0.66%   |
| ALi                                    | 1         | 0.66%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                   | 13        | 8.61%   |
| Bison Integrated Camera                                     | 9         | 5.96%   |
| Microdia Integrated_Webcam_HD                               | 5         | 3.31%   |
| Realtek Integrated_Webcam_HD                                | 4         | 2.65%   |
| Microdia USB 2.0 Camera                                     | 3         | 1.99%   |
| Chicony Lenovo Integrated Camera (0.3MP)                    | 3         | 1.99%   |
| Chicony FJ Camera                                           | 3         | 1.99%   |
| Cheng Uei Precision Industry (Foxlink) Realtek DMFT RGB     | 3         | 1.99%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                    | 2         | 1.32%   |
| Sunplus Integrated_Webcam_HD                                | 2         | 1.32%   |
| Sunplus HP TrueVision HD Camera                             | 2         | 1.32%   |
| Realtek USB Camera                                          | 2         | 1.32%   |
| Logitech Webcam C270                                        | 2         | 1.32%   |
| Lite-On Integrated Camera                                   | 2         | 1.32%   |
| Lenovo Integrated Webcam                                    | 2         | 1.32%   |
| IMC Networks Integrated Webcam                              | 2         | 1.32%   |
| IMC Networks Integrated Camera                              | 2         | 1.32%   |
| Chicony USB 2.0 Camera                                      | 2         | 1.32%   |
| Chicony Integrated Camera [ThinkPad]                        | 2         | 1.32%   |
| Chicony HP Wide Vision HD Camera                            | 2         | 1.32%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam            | 2         | 1.32%   |
| Bison Lenovo EasyCamera                                     | 2         | 1.32%   |
| Bison HP Webcam-101                                         | 2         | 1.32%   |
| Alcor Micro USB 2.0 Camera                                  | 2         | 1.32%   |
| Z-Star Namuga 1.3M Webcam                                   | 1         | 0.66%   |
| Y Media USB Camera                                          | 1         | 0.66%   |
| Trust Trust Full HD Webcam                                  | 1         | 0.66%   |
| Syntek Lenovo EasyCamera                                    | 1         | 0.66%   |
| Syntek Integrated Camera                                    | 1         | 0.66%   |
| Syntek HP Webcam                                            | 1         | 0.66%   |
| Syntek EasyCamera                                           | 1         | 0.66%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 0.66%   |
| Supreme Integrated Camera                                   | 1         | 0.66%   |
| Sunplus SPCA2650 AV Camera                                  | 1         | 0.66%   |
| Sunplus Laptop Integrated WebCam HD                         | 1         | 0.66%   |
| Sunplus Integrated Camera                                   | 1         | 0.66%   |
| Sunplus HP HD Webcam [Fixed]                                | 1         | 0.66%   |
| Sunplus 1.3M HD WebCam                                      | 1         | 0.66%   |
| Silicon Motion WebCam SCX Series                            | 1         | 0.66%   |
| Silicon Motion WebCam SCB-1100N                             | 1         | 0.66%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 11        | 45.83%  |
| Upek                       | 3         | 12.5%   |
| Elan Microelectronics      | 3         | 12.5%   |
| AuthenTec                  | 3         | 12.5%   |
| STMicroelectronics         | 1         | 4.17%   |
| Shenzhen Goodix Technology | 1         | 4.17%   |
| LighTuning Technology      | 1         | 4.17%   |
| Fingerprint Cards          | 1         | 4.17%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor           | 3         | 12.5%   |
| Validity Sensors Synaptics WBDI                        | 3         | 12.5%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 3         | 12.5%   |
| Elan Fingerprint Sensor                                | 3         | 12.5%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 4.17%   |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 4.17%   |
| Validity Sensors VFS101 Fingerprint Reader             | 1         | 4.17%   |
| Validity Sensors Swipe Fingerprint Sensor              | 1         | 4.17%   |
| Validity Sensors Fingerprint scanner                   | 1         | 4.17%   |
| STMicroelectronics Fingerprint Reader                  | 1         | 4.17%   |
| Shenzhen Goodix Fingerprint Reader SGX                 | 1         | 4.17%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 4.17%   |
| Fingerprint Cards FPC Fingerprint Reader               | 1         | 4.17%   |
| AuthenTec AES2810                                      | 1         | 4.17%   |
| AuthenTec AES2660                                      | 1         | 4.17%   |
| AuthenTec AES1660                                      | 1         | 4.17%   |

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
| 1     | 176       | 47.96%  |
| 0     | 89        | 24.25%  |
| 2     | 77        | 20.98%  |
| 3     | 21        | 5.72%   |
| 4     | 4         | 1.09%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 234       | 62.07%  |
| Net/wireless             | 49        | 13%     |
| Card reader              | 26        | 6.9%    |
| Fingerprint reader       | 24        | 6.37%   |
| Bluetooth                | 20        | 5.31%   |
| Sound                    | 15        | 3.98%   |
| Storage                  | 5         | 1.33%   |
| Network                  | 2         | 0.53%   |
| Net/ethernet             | 1         | 0.27%   |
| Dvb card                 | 1         | 0.27%   |

