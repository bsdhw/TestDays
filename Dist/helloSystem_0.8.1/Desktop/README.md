helloSystem 0.8.1 - Tested Hardware & Statistics (Desktops)
-----------------------------------------------------------

A project to collect tested hardware configurations for helloSystem 0.8.1.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 254

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Dell          | 0DFRFW A01                  | [4532391ffd](https://bsd-hardware.info/?probe=4532391ffd) | May 06, 2024 |
| Unknown       | DH61BR G32662-203           | [f9ebf93574](https://bsd-hardware.info/?probe=f9ebf93574) | May 06, 2024 |
| ASUSTek       | P5N32-E SLI                 | [52ac87d342](https://bsd-hardware.info/?probe=52ac87d342) | Apr 27, 2024 |
| Dell          | 0NW6H5 A00                  | [256e25b666](https://bsd-hardware.info/?probe=256e25b666) | Apr 16, 2024 |
| Gigabyte      | B85M-D3H                    | [3f85beaa54](https://bsd-hardware.info/?probe=3f85beaa54) | Apr 05, 2024 |
| Gigabyte      | H55M-USB3                   | [748ef69c9f](https://bsd-hardware.info/?probe=748ef69c9f) | Mar 25, 2024 |
| HP            | 2B34                        | [850e6bf958](https://bsd-hardware.info/?probe=850e6bf958) | Mar 20, 2024 |
| HP            | 21D0                        | [7ca5d182a1](https://bsd-hardware.info/?probe=7ca5d182a1) | Mar 16, 2024 |
| HC Technol... | HCAR5000-MI                 | [2e83945861](https://bsd-hardware.info/?probe=2e83945861) | Mar 16, 2024 |
| HP            | dx2480 MT(FN868PA)          | [d700a91a81](https://bsd-hardware.info/?probe=d700a91a81) | Mar 14, 2024 |
| HP            | 21D0                        | [69b7737f88](https://bsd-hardware.info/?probe=69b7737f88) | Mar 12, 2024 |
| Gigabyte      | B550 GAMING X V2            | [6741cefeb7](https://bsd-hardware.info/?probe=6741cefeb7) | Mar 12, 2024 |
| ASUSTek       | PRIME J3355I-C              | [0b1cea4778](https://bsd-hardware.info/?probe=0b1cea4778) | Mar 12, 2024 |
| Dell          | 07F37C A00                  | [53928dbf53](https://bsd-hardware.info/?probe=53928dbf53) | Mar 03, 2024 |
| Gigabyte      | H81M-D3H                    | [798bfe44fe](https://bsd-hardware.info/?probe=798bfe44fe) | Feb 29, 2024 |
| Gigabyte      | P35-DS3                     | [d877d925e1](https://bsd-hardware.info/?probe=d877d925e1) | Feb 28, 2024 |
| Gigabyte      | P35-DS3                     | [dd8beb7c03](https://bsd-hardware.info/?probe=dd8beb7c03) | Feb 27, 2024 |
| Lenovo        | 30FD SDK0J40705 WIN 3425... | [87313cc66c](https://bsd-hardware.info/?probe=87313cc66c) | Feb 07, 2024 |
| Intel         | STK1AW32SC H91596-303       | [14fcea4fb9](https://bsd-hardware.info/?probe=14fcea4fb9) | Feb 06, 2024 |
| ASUSTek       | Z97M-PLUS/BR                | [cb6b8e5aef](https://bsd-hardware.info/?probe=cb6b8e5aef) | Feb 02, 2024 |
| ASUSTek       | P5E3 PRO                    | [354299e930](https://bsd-hardware.info/?probe=354299e930) | Feb 01, 2024 |
| ASUSTek       | A68HM-K                     | [f321ac1114](https://bsd-hardware.info/?probe=f321ac1114) | Jan 31, 2024 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | [5642aa5018](https://bsd-hardware.info/?probe=5642aa5018) | Jan 16, 2024 |
| ASRock        | AB350 Pro4                  | [b2f960c437](https://bsd-hardware.info/?probe=b2f960c437) | Jan 11, 2024 |
| Unknown       | Unknown                     | [514b270501](https://bsd-hardware.info/?probe=514b270501) | Jan 10, 2024 |
| Roqos         | Core RC10                   | [7561797db6](https://bsd-hardware.info/?probe=7561797db6) | Jan 06, 2024 |
| Unknown       | Unknown                     | [9fed9e1dd9](https://bsd-hardware.info/?probe=9fed9e1dd9) | Jan 04, 2024 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [4b0c5d65b0](https://bsd-hardware.info/?probe=4b0c5d65b0) | Jan 02, 2024 |
| MSI           | Z270-A PRO                  | [2f2f406aa3](https://bsd-hardware.info/?probe=2f2f406aa3) | Dec 31, 2023 |
| MSI           | MPG Z690 CARBON WIFI        | [0e31087126](https://bsd-hardware.info/?probe=0e31087126) | Dec 30, 2023 |
| Gigabyte      | B550 GAMING X V2            | [2ba0ee6609](https://bsd-hardware.info/?probe=2ba0ee6609) | Dec 21, 2023 |
| HP            | 212B                        | [d110ce488b](https://bsd-hardware.info/?probe=d110ce488b) | Dec 18, 2023 |
| ASUSTek       | P8Z77-V PRO                 | [ba2cad0d55](https://bsd-hardware.info/?probe=ba2cad0d55) | Dec 18, 2023 |
| HP            | 212B                        | [1737c1241b](https://bsd-hardware.info/?probe=1737c1241b) | Dec 16, 2023 |
| ASUSTek       | H81M-C                      | [177ffa702e](https://bsd-hardware.info/?probe=177ffa702e) | Dec 03, 2023 |
| Lenovo        | ThinkCentre M70e 0828W17    | [02c7f33254](https://bsd-hardware.info/?probe=02c7f33254) | Dec 03, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | [9f6d0c8539](https://bsd-hardware.info/?probe=9f6d0c8539) | Nov 22, 2023 |
| Gigabyte      | Z68X-UD5-B3                 | [f8fcca51ca](https://bsd-hardware.info/?probe=f8fcca51ca) | Nov 19, 2023 |
| ASUSTek       | P8Z77-V PRO                 | [e28d22b5ed](https://bsd-hardware.info/?probe=e28d22b5ed) | Nov 16, 2023 |
| Lenovo        | NOK                         | [52593923f0](https://bsd-hardware.info/?probe=52593923f0) | Nov 13, 2023 |
| HP            | 3031h                       | [a38d555974](https://bsd-hardware.info/?probe=a38d555974) | Nov 06, 2023 |
| Gigabyte      | B450M AORUS ELITE           | [e49d3f40b6](https://bsd-hardware.info/?probe=e49d3f40b6) | Nov 05, 2023 |
| Gigabyte      | B450M H                     | [69b57fab79](https://bsd-hardware.info/?probe=69b57fab79) | Nov 02, 2023 |
| HP            | 18E7                        | [a5bf30aeac](https://bsd-hardware.info/?probe=a5bf30aeac) | Nov 02, 2023 |
| Shuttle       | NC10U                       | [8a3fd4b3ee](https://bsd-hardware.info/?probe=8a3fd4b3ee) | Nov 01, 2023 |
| ASUSTek       | PRIME B250M-A               | [0caf100d71](https://bsd-hardware.info/?probe=0caf100d71) | Oct 30, 2023 |
| Gigabyte      | Z170-D3H-CF                 | [3d6569cef5](https://bsd-hardware.info/?probe=3d6569cef5) | Oct 26, 2023 |
| Gigabyte      | Z170-D3H-CF                 | [193c3e5732](https://bsd-hardware.info/?probe=193c3e5732) | Oct 22, 2023 |
| Gigabyte      | Z370 AORUS Gaming 7         | [bb82c13e39](https://bsd-hardware.info/?probe=bb82c13e39) | Oct 12, 2023 |
| HP            | 1497                        | [9ffee4ae55](https://bsd-hardware.info/?probe=9ffee4ae55) | Oct 09, 2023 |
| Gigabyte      | B250M-D3H-CF                | [02d64d7433](https://bsd-hardware.info/?probe=02d64d7433) | Oct 08, 2023 |
| ASUSTek       | M5A78L-M/USB3               | [c25c930afa](https://bsd-hardware.info/?probe=c25c930afa) | Oct 05, 2023 |
| ASUSTek       | PRIME B560-PLUS AC-HES      | [471133280c](https://bsd-hardware.info/?probe=471133280c) | Oct 03, 2023 |
| Lenovo        | ThinkCentre M81 5049D7G     | [60de9490a9](https://bsd-hardware.info/?probe=60de9490a9) | Sep 29, 2023 |
| ASUSTek       | Z170-A                      | [3802fe676c](https://bsd-hardware.info/?probe=3802fe676c) | Sep 23, 2023 |
| HP            | 18E8                        | [7a96c7f43a](https://bsd-hardware.info/?probe=7a96c7f43a) | Sep 21, 2023 |
| HP            | 83F3                        | [4d1df66f57](https://bsd-hardware.info/?probe=4d1df66f57) | Sep 20, 2023 |
| Dell          | 0VRWRC A01                  | [6c85a42e64](https://bsd-hardware.info/?probe=6c85a42e64) | Sep 19, 2023 |
| ASRock        | B450 Pro4                   | [211b0f3e9c](https://bsd-hardware.info/?probe=211b0f3e9c) | Sep 19, 2023 |
| AZW           | U59                         | [ae0d8568d1](https://bsd-hardware.info/?probe=ae0d8568d1) | Sep 15, 2023 |
| AZW           | U59                         | [7e094459f9](https://bsd-hardware.info/?probe=7e094459f9) | Sep 14, 2023 |
| Dell          | 04YP6J A02                  | [0933e1164a](https://bsd-hardware.info/?probe=0933e1164a) | Sep 13, 2023 |
| Lenovo        | 3140 NOK                    | [945ad170d7](https://bsd-hardware.info/?probe=945ad170d7) | Sep 10, 2023 |
| Lenovo        | 3140 NOK                    | [3f9dcefb8e](https://bsd-hardware.info/?probe=3f9dcefb8e) | Sep 10, 2023 |
| MSI           | X570-A PRO                  | [e3d8f34f08](https://bsd-hardware.info/?probe=e3d8f34f08) | Sep 08, 2023 |
| MSI           | Z390-A PRO                  | [57925dc8bb](https://bsd-hardware.info/?probe=57925dc8bb) | Sep 02, 2023 |
| Dell          | 0YXT71 A02                  | [b887caabe7](https://bsd-hardware.info/?probe=b887caabe7) | Aug 31, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [3dab6f4044](https://bsd-hardware.info/?probe=3dab6f4044) | Aug 28, 2023 |
| MSI           | H110M PRO-VD                | [dcbd4ebf8f](https://bsd-hardware.info/?probe=dcbd4ebf8f) | Aug 27, 2023 |
| AZW           | U59                         | [e08540ab36](https://bsd-hardware.info/?probe=e08540ab36) | Aug 25, 2023 |
| MSI           | MAG B460M BAZOOKA           | [7cf9279c14](https://bsd-hardware.info/?probe=7cf9279c14) | Aug 22, 2023 |
| Gigabyte      | GA-880GA-UD3H               | [35eb7df9a7](https://bsd-hardware.info/?probe=35eb7df9a7) | Aug 20, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [7e1d475356](https://bsd-hardware.info/?probe=7e1d475356) | Aug 18, 2023 |
| MSI           | MPG Z390 GAMING PRO CARB... | [df095be4ba](https://bsd-hardware.info/?probe=df095be4ba) | Aug 18, 2023 |
| Daten Tecn... | DH110MXV                    | [bdd9c72e7c](https://bsd-hardware.info/?probe=bdd9c72e7c) | Aug 18, 2023 |
| ASRock        | B450 Pro4                   | [c12a76c083](https://bsd-hardware.info/?probe=c12a76c083) | Aug 16, 2023 |
| ASUSTek       | P5G41T-M LX2/BR             | [f25db83457](https://bsd-hardware.info/?probe=f25db83457) | Aug 15, 2023 |
| Intel         | JSL MRD                     | [ca7024f423](https://bsd-hardware.info/?probe=ca7024f423) | Aug 10, 2023 |
| Intel         | H81                         | [80f40918ce](https://bsd-hardware.info/?probe=80f40918ce) | Aug 07, 2023 |
| HP            | 0AACh                       | [5997b1de3e](https://bsd-hardware.info/?probe=5997b1de3e) | Aug 06, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [d3fac2e3fe](https://bsd-hardware.info/?probe=d3fac2e3fe) | Aug 06, 2023 |
| ASUSTek       | M4A88TD-M/USB3              | [ce95634a53](https://bsd-hardware.info/?probe=ce95634a53) | Aug 06, 2023 |
| ASUSTek       | P5QL PRO                    | [dccefef8eb](https://bsd-hardware.info/?probe=dccefef8eb) | Aug 04, 2023 |
| Gigabyte      | Z170-HD3 DDR3-CF            | [f66f032ffe](https://bsd-hardware.info/?probe=f66f032ffe) | Aug 01, 2023 |
| HP            | 83E1                        | [b211795736](https://bsd-hardware.info/?probe=b211795736) | Jul 27, 2023 |
| HP            | 339A                        | [b770568bae](https://bsd-hardware.info/?probe=b770568bae) | Jul 25, 2023 |
| ASRock        | H61M-VG3                    | [5cebf2275e](https://bsd-hardware.info/?probe=5cebf2275e) | Jul 24, 2023 |
| ASUSTek       | P5QL PRO                    | [b51bcdf3a5](https://bsd-hardware.info/?probe=b51bcdf3a5) | Jul 20, 2023 |
| HP            | 81C5 MVB                    | [1a4fbc384d](https://bsd-hardware.info/?probe=1a4fbc384d) | Jul 19, 2023 |
| Apple         | Mac-F221BEC8                | [3a5b0b3193](https://bsd-hardware.info/?probe=3a5b0b3193) | Jul 17, 2023 |
| ECS           | H61H2-M17                   | [aa4679bee7](https://bsd-hardware.info/?probe=aa4679bee7) | Jul 14, 2023 |
| ASRock        | H61M-GS                     | [502952e73f](https://bsd-hardware.info/?probe=502952e73f) | Jul 11, 2023 |
| ASRock        | A300M-STX                   | [5d896a607e](https://bsd-hardware.info/?probe=5d896a607e) | Jul 06, 2023 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [2053dbb697](https://bsd-hardware.info/?probe=2053dbb697) | Jul 03, 2023 |
| HP            | 8055                        | [94df572de4](https://bsd-hardware.info/?probe=94df572de4) | Jun 29, 2023 |
| ASUSTek       | M2A-VM                      | [2d5a9bba42](https://bsd-hardware.info/?probe=2d5a9bba42) | Jun 28, 2023 |
| ASUSTek       | ROG Maximus X HERO          | [2dfabb3a28](https://bsd-hardware.info/?probe=2dfabb3a28) | Jun 23, 2023 |
| ASUSTek       | ROG Maximus X HERO          | [b63efe1bc2](https://bsd-hardware.info/?probe=b63efe1bc2) | Jun 23, 2023 |
| LG Electro... | R590-K.AAA9BT               | [5c3ab65e8e](https://bsd-hardware.info/?probe=5c3ab65e8e) | Jun 23, 2023 |
| ASUSTek       | PRIME B350M-A               | [29545a1054](https://bsd-hardware.info/?probe=29545a1054) | Jun 21, 2023 |
| ASUSTek       | P7P55D LE                   | [ea97ade85d](https://bsd-hardware.info/?probe=ea97ade85d) | Jun 17, 2023 |
| Dell          | 0X9X1W A00                  | [64825f4f71](https://bsd-hardware.info/?probe=64825f4f71) | Jun 08, 2023 |
| Dell          | 0X9X1W A00                  | [c9d8d9a491](https://bsd-hardware.info/?probe=c9d8d9a491) | Jun 08, 2023 |
| Dell          | 0WR7PY A03                  | [c8496622be](https://bsd-hardware.info/?probe=c8496622be) | Jun 03, 2023 |
| Dell          | 0WR7PY A03                  | [b9f7e3e209](https://bsd-hardware.info/?probe=b9f7e3e209) | Jun 03, 2023 |
| Intel         | H81                         | [e0e15704fc](https://bsd-hardware.info/?probe=e0e15704fc) | May 29, 2023 |
| HP            | 21D0                        | [4a10865d28](https://bsd-hardware.info/?probe=4a10865d28) | May 28, 2023 |
| HP            | 21D0                        | [e3d20826b3](https://bsd-hardware.info/?probe=e3d20826b3) | May 28, 2023 |
| Gigabyte      | X58A-UD3R                   | [1d43f61471](https://bsd-hardware.info/?probe=1d43f61471) | May 27, 2023 |
| Unknown       | 1.0                         | [12d6c7934e](https://bsd-hardware.info/?probe=12d6c7934e) | May 27, 2023 |
| ASUSTek       | PRIME H510M-K               | [53a2d5356d](https://bsd-hardware.info/?probe=53a2d5356d) | May 26, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [a0bff43f5c](https://bsd-hardware.info/?probe=a0bff43f5c) | May 23, 2023 |
| AZW           | GK55                        | [ef90c15915](https://bsd-hardware.info/?probe=ef90c15915) | May 23, 2023 |
| ASRock        | Z68 Pro3 Gen3               | [0a03cd86a0](https://bsd-hardware.info/?probe=0a03cd86a0) | May 21, 2023 |
| ASUSTek       | Z87M-PLUS                   | [58da7daed7](https://bsd-hardware.info/?probe=58da7daed7) | May 20, 2023 |
| ASUSTek       | PRIME A320M-K               | [8f3c5de741](https://bsd-hardware.info/?probe=8f3c5de741) | May 19, 2023 |
| Gigabyte      | Z490 VISION G               | [976e31bfbc](https://bsd-hardware.info/?probe=976e31bfbc) | May 16, 2023 |
| Gigabyte      | Z490 VISION G               | [8eeec83a4e](https://bsd-hardware.info/?probe=8eeec83a4e) | May 16, 2023 |
| ASUSTek       | PRIME A520M-K               | [bda308bc8c](https://bsd-hardware.info/?probe=bda308bc8c) | May 14, 2023 |
| Dell          | 0WN7Y6 A01                  | [a232411c74](https://bsd-hardware.info/?probe=a232411c74) | May 12, 2023 |
| ASUSTek       | PRIME B450M-K II            | [fe053db6c7](https://bsd-hardware.info/?probe=fe053db6c7) | May 10, 2023 |
| ASUSTek       | PRIME B450M-K II            | [16ca4a2aa0](https://bsd-hardware.info/?probe=16ca4a2aa0) | May 10, 2023 |
| ASRock        | Q1900M                      | [c779034e79](https://bsd-hardware.info/?probe=c779034e79) | May 09, 2023 |
| Dell          | 07F37C A00                  | [a23a95f97a](https://bsd-hardware.info/?probe=a23a95f97a) | May 07, 2023 |
| ASRock        | J4125-ITX                   | [6e34c8b22a](https://bsd-hardware.info/?probe=6e34c8b22a) | May 05, 2023 |
| Intel         | DH87RL AAG74240-400         | [7833b60865](https://bsd-hardware.info/?probe=7833b60865) | May 05, 2023 |
| Dell          | 0252PH A04                  | [0cc9ef6521](https://bsd-hardware.info/?probe=0cc9ef6521) | May 03, 2023 |
| Dell          | 0252PH A04                  | [acaf59c3d5](https://bsd-hardware.info/?probe=acaf59c3d5) | May 03, 2023 |
| HP            | 82B4                        | [244817e203](https://bsd-hardware.info/?probe=244817e203) | May 02, 2023 |
| ASUSTek       | PRIME B250M-A               | [270284972d](https://bsd-hardware.info/?probe=270284972d) | Apr 29, 2023 |
| Dell          | 0252PH A04                  | [f497e66dec](https://bsd-hardware.info/?probe=f497e66dec) | Apr 27, 2023 |
| HP            | 8056                        | [44fb168511](https://bsd-hardware.info/?probe=44fb168511) | Apr 26, 2023 |
| Dell          | 0VTC0D A02                  | [a807892254](https://bsd-hardware.info/?probe=a807892254) | Apr 19, 2023 |
| Acer          | Acadia V1.44                | [97bda17afa](https://bsd-hardware.info/?probe=97bda17afa) | Apr 19, 2023 |
| Gigabyte      | H61M-S2PH                   | [024173445b](https://bsd-hardware.info/?probe=024173445b) | Apr 18, 2023 |
| Gigabyte      | A520M DS3H AC               | [16021ac5b5](https://bsd-hardware.info/?probe=16021ac5b5) | Apr 17, 2023 |
| Pegatron      | 2A72h                       | [142340aed4](https://bsd-hardware.info/?probe=142340aed4) | Apr 15, 2023 |
| ASUSTek       | PRIME B550M-A WIFI II       | [8e77aee0e0](https://bsd-hardware.info/?probe=8e77aee0e0) | Apr 14, 2023 |
| HP            | 3397                        | [cf2d152bee](https://bsd-hardware.info/?probe=cf2d152bee) | Apr 13, 2023 |
| ASUSTek       | PRIME B550M-A WIFI II       | [e6c9c37b02](https://bsd-hardware.info/?probe=e6c9c37b02) | Apr 13, 2023 |
| Gigabyte      | H81M-S2PH                   | [b7ec959c9f](https://bsd-hardware.info/?probe=b7ec959c9f) | Apr 13, 2023 |
| ASUSTek       | PRIME B250M-A               | [0747d0a699](https://bsd-hardware.info/?probe=0747d0a699) | Apr 11, 2023 |
| Gigabyte      | M52L-S3P                    | [3a6baf7f2d](https://bsd-hardware.info/?probe=3a6baf7f2d) | Apr 09, 2023 |
| Gigabyte      | B250M-Gaming 3-CF           | [592e08cdd2](https://bsd-hardware.info/?probe=592e08cdd2) | Apr 09, 2023 |
| Acer          | Veriton M6620G              | [13f7e5c23b](https://bsd-hardware.info/?probe=13f7e5c23b) | Apr 07, 2023 |
| Lenovo        | Tilapia CRB                 | [977f089665](https://bsd-hardware.info/?probe=977f089665) | Apr 05, 2023 |
| Gigabyte      | B360M D2V                   | [6429eebbaa](https://bsd-hardware.info/?probe=6429eebbaa) | Apr 05, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | [92d0571176](https://bsd-hardware.info/?probe=92d0571176) | Apr 03, 2023 |
| Gigabyte      | B450M DS3H V2               | [096620cfac](https://bsd-hardware.info/?probe=096620cfac) | Apr 03, 2023 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | [760a744b91](https://bsd-hardware.info/?probe=760a744b91) | Apr 02, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [bcaaed4d6d](https://bsd-hardware.info/?probe=bcaaed4d6d) | Mar 31, 2023 |
| Gigabyte      | GA-880GM-USB3               | [a9bc1579c1](https://bsd-hardware.info/?probe=a9bc1579c1) | Mar 31, 2023 |
| Lenovo        | 30D0 SDK0J40697 WIN 3305... | [bde9fd671b](https://bsd-hardware.info/?probe=bde9fd671b) | Mar 30, 2023 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | [ca6badc637](https://bsd-hardware.info/?probe=ca6badc637) | Mar 30, 2023 |
| Gigabyte      | H81M-DS2V                   | [a69c208286](https://bsd-hardware.info/?probe=a69c208286) | Mar 30, 2023 |
| Dell          | 0T1D10 A01                  | [2f5592023f](https://bsd-hardware.info/?probe=2f5592023f) | Mar 29, 2023 |
| Dell          | 0T1D10 A01                  | [6316b108be](https://bsd-hardware.info/?probe=6316b108be) | Mar 29, 2023 |
| BESSTAR Te... | UM700                       | [78ee14c1a5](https://bsd-hardware.info/?probe=78ee14c1a5) | Mar 28, 2023 |
| ASRock        | H61M-HVS                    | [98777ba333](https://bsd-hardware.info/?probe=98777ba333) | Mar 27, 2023 |
| MSI           | 870-G45                     | [19cbb6e0f3](https://bsd-hardware.info/?probe=19cbb6e0f3) | Mar 26, 2023 |
| Gigabyte      | F2A85X-UP4                  | [97d37b6e2f](https://bsd-hardware.info/?probe=97d37b6e2f) | Mar 25, 2023 |
| MSI           | 870-G45                     | [14e990c885](https://bsd-hardware.info/?probe=14e990c885) | Mar 25, 2023 |
| Gigabyte      | F2A85X-UP4                  | [c0b8eb494e](https://bsd-hardware.info/?probe=c0b8eb494e) | Mar 25, 2023 |
| ASUSTek       | P5K SE                      | [646eff3292](https://bsd-hardware.info/?probe=646eff3292) | Mar 25, 2023 |
| HP            | 8055                        | [03930fa6c3](https://bsd-hardware.info/?probe=03930fa6c3) | Mar 24, 2023 |
| HP            | 8350                        | [46dedb22a0](https://bsd-hardware.info/?probe=46dedb22a0) | Mar 24, 2023 |
| Unknown       | Unknown                     | [a66dffcb5c](https://bsd-hardware.info/?probe=a66dffcb5c) | Mar 23, 2023 |
| Intel         | DB85FL AAG89861-203         | [ff97717798](https://bsd-hardware.info/?probe=ff97717798) | Mar 23, 2023 |
| Gigabyte      | H81M-H                      | [e7cadcdae1](https://bsd-hardware.info/?probe=e7cadcdae1) | Mar 23, 2023 |
| Acer          | Revo 70                     | [50d93bea69](https://bsd-hardware.info/?probe=50d93bea69) | Mar 23, 2023 |
| Unknown       | T360D11                     | [d4d69405c5](https://bsd-hardware.info/?probe=d4d69405c5) | Mar 23, 2023 |
| T-bao         | MINI PC V1.0                | [eb2bc1cd51](https://bsd-hardware.info/?probe=eb2bc1cd51) | Mar 23, 2023 |
| Dell          | 0WWJRX A00                  | [b016b1fb3c](https://bsd-hardware.info/?probe=b016b1fb3c) | Mar 22, 2023 |
| Gigabyte      | F2A55-DS3                   | [ce8775fbe5](https://bsd-hardware.info/?probe=ce8775fbe5) | Mar 22, 2023 |
| Biostar       | H61MGC                      | [94e565457c](https://bsd-hardware.info/?probe=94e565457c) | Mar 22, 2023 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [c486bbb209](https://bsd-hardware.info/?probe=c486bbb209) | Mar 22, 2023 |
| ASUSTek       | M5A97 R2.0                  | [840a902d2b](https://bsd-hardware.info/?probe=840a902d2b) | Mar 22, 2023 |
| Foxconn       | M61PMV FAB                  | [197d75cbaa](https://bsd-hardware.info/?probe=197d75cbaa) | Mar 21, 2023 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | [bcada44b09](https://bsd-hardware.info/?probe=bcada44b09) | Mar 21, 2023 |
| Intel         | X99                         | [a74c2b96ff](https://bsd-hardware.info/?probe=a74c2b96ff) | Mar 21, 2023 |
| Dell          | 0GM819                      | [9d5996dd7a](https://bsd-hardware.info/?probe=9d5996dd7a) | Mar 21, 2023 |
| HP            | 8054                        | [6e5a18f346](https://bsd-hardware.info/?probe=6e5a18f346) | Mar 20, 2023 |
| Lenovo        | 30BC SDK0J40705 WIN 3425... | [33b600b436](https://bsd-hardware.info/?probe=33b600b436) | Mar 20, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [8d0e6be5da](https://bsd-hardware.info/?probe=8d0e6be5da) | Mar 20, 2023 |
| Dell          | 0GM819                      | [da7c02c542](https://bsd-hardware.info/?probe=da7c02c542) | Mar 20, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [c07b0a75e5](https://bsd-hardware.info/?probe=c07b0a75e5) | Mar 20, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [71d2b7317c](https://bsd-hardware.info/?probe=71d2b7317c) | Mar 19, 2023 |
| ASRock        | H61M-DGS                    | [36348fa16f](https://bsd-hardware.info/?probe=36348fa16f) | Mar 19, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [acc1970543](https://bsd-hardware.info/?probe=acc1970543) | Mar 18, 2023 |
| ASUSTek       | P6X58D-E                    | [ec05209185](https://bsd-hardware.info/?probe=ec05209185) | Mar 18, 2023 |
| Gigabyte      | H110M-H-CF                  | [29b3a70374](https://bsd-hardware.info/?probe=29b3a70374) | Mar 18, 2023 |
| Unknown       | Unknown                     | [dd8a64237a](https://bsd-hardware.info/?probe=dd8a64237a) | Mar 18, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [2ceda5b586](https://bsd-hardware.info/?probe=2ceda5b586) | Mar 17, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [74cf75116d](https://bsd-hardware.info/?probe=74cf75116d) | Mar 17, 2023 |
| ASUSTek       | TUF B360M-PLUS GAMING       | [ebbd75883c](https://bsd-hardware.info/?probe=ebbd75883c) | Mar 17, 2023 |
| Unknown       | SKYBAY                      | [7399558d80](https://bsd-hardware.info/?probe=7399558d80) | Mar 17, 2023 |
| Unknown       | SKYBAY                      | [3fb2d0d992](https://bsd-hardware.info/?probe=3fb2d0d992) | Mar 17, 2023 |
| HP            | 1632                        | [8f3bb99bb4](https://bsd-hardware.info/?probe=8f3bb99bb4) | Mar 17, 2023 |
| Gigabyte      | F2A68HM-HD2                 | [da2b96de55](https://bsd-hardware.info/?probe=da2b96de55) | Mar 16, 2023 |
| Gigabyte      | Z87X-UD4H-CF                | [0bae1528b9](https://bsd-hardware.info/?probe=0bae1528b9) | Mar 16, 2023 |
| ASUSTek       | PRIME B660M-A D4            | [eb6b70b310](https://bsd-hardware.info/?probe=eb6b70b310) | Mar 16, 2023 |
| Lenovo        | SHARKBAY NOK                | [f14a448799](https://bsd-hardware.info/?probe=f14a448799) | Mar 16, 2023 |
| ASUSTek       | PRIME B660M-A WIFI D4       | [44c7f21a07](https://bsd-hardware.info/?probe=44c7f21a07) | Mar 16, 2023 |
| Gigabyte      | B450M S2H                   | [dfa4f43317](https://bsd-hardware.info/?probe=dfa4f43317) | Mar 15, 2023 |
| Gigabyte      | H61M-S2P-B3                 | [864a4017cb](https://bsd-hardware.info/?probe=864a4017cb) | Mar 15, 2023 |
| HP            | 3398                        | [b14de43688](https://bsd-hardware.info/?probe=b14de43688) | Mar 15, 2023 |
| ASUSTek       | ROG STRIX B560-F GAMING ... | [c4798050c6](https://bsd-hardware.info/?probe=c4798050c6) | Mar 15, 2023 |
| ASUSTek       | Pro B550M-C                 | [a0e38ad11b](https://bsd-hardware.info/?probe=a0e38ad11b) | Mar 14, 2023 |
| Dell          | 00V62H A00                  | [ecb9b5d004](https://bsd-hardware.info/?probe=ecb9b5d004) | Mar 14, 2023 |
| Foxconn       | H61M/H61M-S                 | [865fbff42a](https://bsd-hardware.info/?probe=865fbff42a) | Mar 14, 2023 |
| Fujitsu Si... | D2804-A1 S26361-D2804-A1    | [34c4bab715](https://bsd-hardware.info/?probe=34c4bab715) | Mar 14, 2023 |
| MSI           | 0A48                        | [815f019a8c](https://bsd-hardware.info/?probe=815f019a8c) | Mar 14, 2023 |
| Lenovo        | NO DPK                      | [8a38ed8d33](https://bsd-hardware.info/?probe=8a38ed8d33) | Mar 14, 2023 |
| ASUSTek       | B85M-G                      | [6401dd52d2](https://bsd-hardware.info/?probe=6401dd52d2) | Mar 14, 2023 |
| AZW           | U59                         | [5a6ef3fb8d](https://bsd-hardware.info/?probe=5a6ef3fb8d) | Mar 14, 2023 |
| Lenovo        | ThinkCentre M58p 6138DK1    | [293de8b0fd](https://bsd-hardware.info/?probe=293de8b0fd) | Mar 14, 2023 |
| Google        | Panther                     | [3577da7e53](https://bsd-hardware.info/?probe=3577da7e53) | Mar 13, 2023 |
| Dell          | 01TN68 A02                  | [cb6c76df00](https://bsd-hardware.info/?probe=cb6c76df00) | Mar 13, 2023 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | [b337baf50e](https://bsd-hardware.info/?probe=b337baf50e) | Mar 13, 2023 |
| Gigabyte      | B365M H                     | [7acb7cb65f](https://bsd-hardware.info/?probe=7acb7cb65f) | Mar 13, 2023 |
| ASUSTek       | PRIME H310M-A R2.0          | [e96ecce822](https://bsd-hardware.info/?probe=e96ecce822) | Mar 13, 2023 |
| HP            | 8056                        | [164b3e5c3f](https://bsd-hardware.info/?probe=164b3e5c3f) | Mar 13, 2023 |
| T-bao         | MINI PC                     | [d4440566b0](https://bsd-hardware.info/?probe=d4440566b0) | Mar 13, 2023 |
| Gigabyte      | G31M-S2L                    | [d210b12607](https://bsd-hardware.info/?probe=d210b12607) | Mar 13, 2023 |
| Gigabyte      | H110M-S2-CF                 | [6afb777789](https://bsd-hardware.info/?probe=6afb777789) | Mar 13, 2023 |
| Dell          | 0W0CHX A00                  | [85a9fddd44](https://bsd-hardware.info/?probe=85a9fddd44) | Mar 12, 2023 |
| MSI           | H310M PRO-VDH PLUS          | [0eeb0661dd](https://bsd-hardware.info/?probe=0eeb0661dd) | Mar 12, 2023 |
| Dell          | 0WMJ54 A01                  | [7949f20162](https://bsd-hardware.info/?probe=7949f20162) | Mar 12, 2023 |
| MSI           | B450-A PRO                  | [b2d29a5bbc](https://bsd-hardware.info/?probe=b2d29a5bbc) | Mar 12, 2023 |
| Gigabyte      | H61M-DS2 x.x                | [a39b128f44](https://bsd-hardware.info/?probe=a39b128f44) | Mar 12, 2023 |
| Gigabyte      | B250M-DS3H-CF               | [34afe9e044](https://bsd-hardware.info/?probe=34afe9e044) | Mar 12, 2023 |
| Axiomtek      | IMB211                      | [aebf680e82](https://bsd-hardware.info/?probe=aebf680e82) | Mar 12, 2023 |
| Axiomtek      | IMB211                      | [6c50fda85b](https://bsd-hardware.info/?probe=6c50fda85b) | Mar 12, 2023 |
| ASUSTek       | A8N-E                       | [5fc3d86bac](https://bsd-hardware.info/?probe=5fc3d86bac) | Mar 12, 2023 |
| MSI           | H61M-E22                    | [227c78f3c1](https://bsd-hardware.info/?probe=227c78f3c1) | Mar 12, 2023 |
| ASRock        | Q1900M                      | [5d0f6c2276](https://bsd-hardware.info/?probe=5d0f6c2276) | Mar 12, 2023 |
| HP            | 8768 A                      | [5ab1dadbab](https://bsd-hardware.info/?probe=5ab1dadbab) | Mar 12, 2023 |
| Lenovo        | SHARKBAY NOK                | [ad604088a2](https://bsd-hardware.info/?probe=ad604088a2) | Mar 12, 2023 |
| Acer          | Veriton N2620G              | [fa57448331](https://bsd-hardware.info/?probe=fa57448331) | Mar 12, 2023 |
| MSI           | A320M-A PRO                 | [593f6ff02d](https://bsd-hardware.info/?probe=593f6ff02d) | Mar 12, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [ededc04017](https://bsd-hardware.info/?probe=ededc04017) | Mar 12, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [37ee7b4f47](https://bsd-hardware.info/?probe=37ee7b4f47) | Mar 12, 2023 |
| Fujitsu       | JIM86YD                     | [7a69b91093](https://bsd-hardware.info/?probe=7a69b91093) | Mar 12, 2023 |
| MSI           | H61M-P31/W8                 | [5ae8ebe3cd](https://bsd-hardware.info/?probe=5ae8ebe3cd) | Mar 11, 2023 |
| HP            | 843B                        | [c1886bcd29](https://bsd-hardware.info/?probe=c1886bcd29) | Mar 11, 2023 |
| HP            | 3398                        | [20bcb682d8](https://bsd-hardware.info/?probe=20bcb682d8) | Mar 11, 2023 |
| ASUSTek       | P8Z68-V                     | [3d8ef63e18](https://bsd-hardware.info/?probe=3d8ef63e18) | Mar 11, 2023 |
| Dell          | 0C27VV A02                  | [5899533edd](https://bsd-hardware.info/?probe=5899533edd) | Feb 23, 2023 |
| Intel         | DG41TY AAE47335-300         | [7c1727d55a](https://bsd-hardware.info/?probe=7c1727d55a) | Feb 22, 2023 |
| Dell          | 0C27VV A02                  | [a10df954b7](https://bsd-hardware.info/?probe=a10df954b7) | Feb 22, 2023 |
| Huanan        | X99-TF GAMING V3.0          | [59db63fd9d](https://bsd-hardware.info/?probe=59db63fd9d) | Feb 22, 2023 |
| Huanan        | X99-TF GAMING V3.0          | [50dce9bf96](https://bsd-hardware.info/?probe=50dce9bf96) | Feb 19, 2023 |
| Gigabyte      | H81M-H                      | [8820014583](https://bsd-hardware.info/?probe=8820014583) | Feb 15, 2023 |
| Gigabyte      | H81M-H                      | [592ca6bab5](https://bsd-hardware.info/?probe=592ca6bab5) | Feb 15, 2023 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Desktops | Percent |
|-------|----------|---------|
| amd64 | 212      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| helloDesktop | 211      | 99.53%  |
| GNOME        | 1        | 0.47%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 212      | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| SLiM | 212      | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 87       | 40.65%  |
| fr_FR   | 62       | 28.97%  |
| ru_RU   | 15       | 7.01%   |
| de_DE   | 12       | 5.61%   |
| es_ES   | 10       | 4.67%   |
| Unknown | 10       | 4.67%   |
| pt_BR   | 7        | 3.27%   |
| it_IT   | 5        | 2.34%   |
| pl_PL   | 2        | 0.93%   |
| jp_JP   | 2        | 0.93%   |
| fr      | 1        | 0.47%   |
| es      | 1        | 0.47%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 208      | 98.11%  |
| BIOS | 4        | 1.89%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Desktops | Percent |
|--------|----------|---------|
| Cd9660 | 124      | 56.62%  |
| Zfs    | 95       | 43.38%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 208      | 98.11%  |
| MBR  | 4        | 1.89%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 50       | 23.58%  |
| Gigabyte Technology | 36       | 16.98%  |
| Hewlett-Packard     | 26       | 12.26%  |
| Dell                | 19       | 8.96%   |
| MSI                 | 15       | 7.08%   |
| Lenovo              | 13       | 6.13%   |
| ASRock              | 10       | 4.72%   |
| Intel               | 8        | 3.77%   |
| Unknown             | 7        | 3.3%    |
| Fujitsu             | 4        | 1.89%   |
| Acer                | 4        | 1.89%   |
| T-bao               | 2        | 0.94%   |
| Fujitsu Siemens     | 2        | 0.94%   |
| Foxconn             | 2        | 0.94%   |
| AZW                 | 2        | 0.94%   |
| Shuttle             | 1        | 0.47%   |
| Pegatron            | 1        | 0.47%   |
| LG Electronics      | 1        | 0.47%   |
| Huanan              | 1        | 0.47%   |
| HC Technology.      | 1        | 0.47%   |
| Google              | 1        | 0.47%   |
| ECS                 | 1        | 0.47%   |
| Daten Tecnologia    | 1        | 0.47%   |
| Biostar             | 1        | 0.47%   |
| BESSTAR Tech        | 1        | 0.47%   |
| Axiomtek            | 1        | 0.47%   |
| Apple               | 1        | 0.47%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                | Desktops | Percent |
|-------------------------------------|----------|---------|
| Unknown                             | 7        | 3.3%    |
| ASUS All Series                     | 4        | 1.89%   |
| ASUS PRIME B250M-A                  | 3        | 1.42%   |
| T-bao MINI PC                       | 2        | 0.94%   |
| MSI MS-7788                         | 2        | 0.94%   |
| Intel H81                           | 2        | 0.94%   |
| HP ProDesk 600 G1 DM                | 2        | 0.94%   |
| HP EliteDesk 800 G2 DM 35W          | 2        | 0.94%   |
| HP Compaq Elite 8300 USDT           | 2        | 0.94%   |
| Gigabyte B550 GAMING X V2           | 2        | 0.94%   |
| Dell OptiPlex 780                   | 2        | 0.94%   |
| Dell OptiPlex 7010                  | 2        | 0.94%   |
| Dell OptiPlex 3020                  | 2        | 0.94%   |
| ASUS ROG STRIX B550-F GAMING        | 2        | 0.94%   |
| Shuttle NC10U                       | 1        | 0.47%   |
| Pegatron Compaq dx2450 Microtower   | 1        | 0.47%   |
| MSI MS-7D30                         | 1        | 0.47%   |
| MSI MS-7C95                         | 1        | 0.47%   |
| MSI MS-7C83                         | 1        | 0.47%   |
| MSI MS-7C51                         | 1        | 0.47%   |
| MSI MS-7C37                         | 1        | 0.47%   |
| MSI MS-7C09                         | 1        | 0.47%   |
| MSI MS-7B98                         | 1        | 0.47%   |
| MSI MS-7B86                         | 1        | 0.47%   |
| MSI MS-7B17                         | 1        | 0.47%   |
| MSI MS-7A71                         | 1        | 0.47%   |
| MSI MS-7996                         | 1        | 0.47%   |
| MSI MS-7599                         | 1        | 0.47%   |
| MSI Compaq dx2200 MT                | 1        | 0.47%   |
| LG R590-K.AAA9BT                    | 1        | 0.47%   |
| Lenovo ThinkCentre M93p 10A8S0J30R  | 1        | 0.47%   |
| Lenovo ThinkCentre M900 10FLS15P00  | 1        | 0.47%   |
| Lenovo ThinkCentre M900 10FGS05C08  | 1        | 0.47%   |
| Lenovo ThinkCentre M81 5049D7G      | 1        | 0.47%   |
| Lenovo ThinkCentre M75e 5065A11     | 1        | 0.47%   |
| Lenovo ThinkCentre M73 10AYA06EIA   | 1        | 0.47%   |
| Lenovo ThinkCentre M73 10AXS34800   | 1        | 0.47%   |
| Lenovo ThinkCentre M715q 10M2S02Q00 | 1        | 0.47%   |
| Lenovo ThinkCentre M710s 10M8S0FW00 | 1        | 0.47%   |
| Lenovo ThinkCentre M70e 0828W17     | 1        | 0.47%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| ASUS PRIME              | 15       | 7.08%   |
| Lenovo ThinkCentre      | 12       | 5.66%   |
| Dell OptiPlex           | 12       | 5.66%   |
| ASUS ROG                | 8        | 3.77%   |
| HP Compaq               | 7        | 3.3%    |
| Unknown                 | 7        | 3.3%    |
| HP ProDesk              | 5        | 2.36%   |
| HP EliteDesk            | 5        | 2.36%   |
| Gigabyte B450M          | 4        | 1.89%   |
| ASUS All                | 4        | 1.89%   |
| Gigabyte B550           | 3        | 1.42%   |
| Dell Precision          | 3        | 1.42%   |
| ASUS TUF                | 3        | 1.42%   |
| T-bao MINI              | 2        | 0.94%   |
| MSI MS-7788             | 2        | 0.94%   |
| Intel H81               | 2        | 0.94%   |
| Fujitsu Siemens ESPRIMO | 2        | 0.94%   |
| Fujitsu ESPRIMO         | 2        | 0.94%   |
| Dell Vostro             | 2        | 0.94%   |
| Dell Inspiron           | 2        | 0.94%   |
| Acer Veriton            | 2        | 0.94%   |
| Shuttle NC10U           | 1        | 0.47%   |
| Pegatron Compaq         | 1        | 0.47%   |
| MSI MS-7D30             | 1        | 0.47%   |
| MSI MS-7C95             | 1        | 0.47%   |
| MSI MS-7C83             | 1        | 0.47%   |
| MSI MS-7C51             | 1        | 0.47%   |
| MSI MS-7C37             | 1        | 0.47%   |
| MSI MS-7C09             | 1        | 0.47%   |
| MSI MS-7B98             | 1        | 0.47%   |
| MSI MS-7B86             | 1        | 0.47%   |
| MSI MS-7B17             | 1        | 0.47%   |
| MSI MS-7A71             | 1        | 0.47%   |
| MSI MS-7996             | 1        | 0.47%   |
| MSI MS-7599             | 1        | 0.47%   |
| MSI Compaq              | 1        | 0.47%   |
| LG R590-K.AAA9BT        | 1        | 0.47%   |
| Lenovo IdeaCentre       | 1        | 0.47%   |
| Intel X99               | 1        | 0.47%   |
| Intel STK1AW32SC        | 1        | 0.47%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2020    | 20       | 9.43%   |
| 2021    | 19       | 8.96%   |
| 2022    | 18       | 8.49%   |
| 2019    | 17       | 8.02%   |
| 2013    | 16       | 7.55%   |
| 2012    | 16       | 7.55%   |
| 2010    | 14       | 6.6%    |
| 2018    | 13       | 6.13%   |
| 2014    | 13       | 6.13%   |
| 2011    | 12       | 5.66%   |
| 2017    | 11       | 5.19%   |
| 2016    | 9        | 4.25%   |
| 2015    | 8        | 3.77%   |
| 2023    | 7        | 3.3%    |
| 2009    | 7        | 3.3%    |
| 2008    | 7        | 3.3%    |
| 2007    | 2        | 0.94%   |
| 2006    | 2        | 0.94%   |
| Unknown | 1        | 0.47%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 212      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 211      | 99.53%  |
| Yes  | 1        | 0.47%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 74       | 34.91%  |
| 16.01-24.0  | 63       | 29.72%  |
| 4.01-8.0    | 38       | 17.92%  |
| 32.01-64.0  | 21       | 9.91%   |
| 64.01-256.0 | 6        | 2.83%   |
| 2.01-3.0    | 5        | 2.36%   |
| 24.01-32.0  | 3        | 1.42%   |
| 3.01-4.0    | 1        | 0.47%   |
| 0.51-1.0    | 1        | 0.47%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 0.01-0.5 | 100      | 46.73%  |
| 0.51-1.0 | 74       | 34.58%  |
| 1.01-2.0 | 28       | 13.08%  |
| 2.01-3.0 | 10       | 4.67%   |
| 3.01-4.0 | 2        | 0.93%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 102      | 48.11%  |
| 2      | 43       | 20.28%  |
| 3      | 28       | 13.21%  |
| 0      | 16       | 7.55%   |
| 5      | 10       | 4.72%   |
| 4      | 7        | 3.3%    |
| 9      | 2        | 0.94%   |
| 6      | 2        | 0.94%   |
| 13     | 1        | 0.47%   |
| 7      | 1        | 0.47%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 135      | 63.68%  |
| Yes       | 77       | 36.32%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 205      | 96.7%   |
| No        | 7        | 3.3%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 145      | 68.08%  |
| Yes       | 68       | 31.92%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 159      | 75%     |
| Yes       | 53       | 25%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country       | Desktops | Percent |
|---------------|----------|---------|
| USA           | 33       | 15.57%  |
| Russia        | 30       | 14.15%  |
| Brazil        | 12       | 5.66%   |
| Spain         | 11       | 5.19%   |
| Germany       | 11       | 5.19%   |
| France        | 8        | 3.77%   |
| Italy         | 7        | 3.3%    |
| Canada        | 7        | 3.3%    |
| Serbia        | 6        | 2.83%   |
| Poland        | 6        | 2.83%   |
| Hungary       | 6        | 2.83%   |
| Romania       | 5        | 2.36%   |
| Belgium       | 5        | 2.36%   |
| Australia     | 5        | 2.36%   |
| UK            | 4        | 1.89%   |
| India         | 4        | 1.89%   |
| Ukraine       | 3        | 1.42%   |
| Turkey        | 3        | 1.42%   |
| Peru          | 3        | 1.42%   |
| Netherlands   | 3        | 1.42%   |
| Mexico        | 3        | 1.42%   |
| Japan         | 3        | 1.42%   |
| Bulgaria      | 3        | 1.42%   |
| Argentina     | 3        | 1.42%   |
| Sweden        | 2        | 0.94%   |
| Indonesia     | 2        | 0.94%   |
| Estonia       | 2        | 0.94%   |
| China         | 2        | 0.94%   |
| Venezuela     | 1        | 0.47%   |
| Switzerland   | 1        | 0.47%   |
| South Korea   | 1        | 0.47%   |
| Slovenia      | 1        | 0.47%   |
| San Marino    | 1        | 0.47%   |
| Portugal      | 1        | 0.47%   |
| Panama        | 1        | 0.47%   |
| Kyrgyzstan    | 1        | 0.47%   |
| Kazakhstan    | 1        | 0.47%   |
| Israel        | 1        | 0.47%   |
| Ireland       | 1        | 0.47%   |
| French Guiana | 1        | 0.47%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| St Petersburg     | 4        | 1.86%   |
| Moscow            | 4        | 1.86%   |
| St. Jean Baptiste | 3        | 1.4%    |
| Newburgh          | 3        | 1.4%    |
| Madrid            | 3        | 1.4%    |
| Belgrade          | 3        | 1.4%    |
| Sydney            | 2        | 0.93%   |
| Sofia             | 2        | 0.93%   |
| Sao Paulo         | 2        | 0.93%   |
| Penza             | 2        | 0.93%   |
| Paris             | 2        | 0.93%   |
| Novosibirsk       | 2        | 0.93%   |
| New York          | 2        | 0.93%   |
| Melbourne         | 2        | 0.93%   |
| Kochi             | 2        | 0.93%   |
| Kirov             | 2        | 0.93%   |
| Curitiba          | 2        | 0.93%   |
| Brooklyn          | 2        | 0.93%   |
| Berlin            | 2        | 0.93%   |
| Bandung           | 2        | 0.93%   |
| Zurich            | 1        | 0.47%   |
| Zhengzhou         | 1        | 0.47%   |
| Yokohama          | 1        | 0.47%   |
| Woodbridge        | 1        | 0.47%   |
| Winnipeg          | 1        | 0.47%   |
| Warsaw            | 1        | 0.47%   |
| Volgodonsk        | 1        | 0.47%   |
| Vogogna           | 1        | 0.47%   |
| Vladimir          | 1        | 0.47%   |
| Virovitica        | 1        | 0.47%   |
| Villena           | 1        | 0.47%   |
| Vienna            | 1        | 0.47%   |
| Venice            | 1        | 0.47%   |
| Vecses            | 1        | 0.47%   |
| Vantaa            | 1        | 0.47%   |
| Valga             | 1        | 0.47%   |
| Valderrobres      | 1        | 0.47%   |
| Ubstadt-Weiher    | 1        | 0.47%   |
| Tucson            | 1        | 0.47%   |
| Trumbull          | 1        | 0.47%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 58       | 95     | 17.58%  |
| Seagate             | 53       | 79     | 16.06%  |
| Samsung Electronics | 43       | 61     | 13.03%  |
| Kingston            | 32       | 33     | 9.7%    |
| Toshiba             | 17       | 23     | 5.15%   |
| Crucial             | 11       | 13     | 3.33%   |
| A-DATA Technology   | 11       | 12     | 3.33%   |
| SanDisk             | 10       | 10     | 3.03%   |
| Hitachi             | 8        | 9      | 2.42%   |
| China               | 7        | 8      | 2.12%   |
| Transcend           | 6        | 6      | 1.82%   |
| Patriot             | 5        | 5      | 1.52%   |
| Micron Technology   | 5        | 6      | 1.52%   |
| Intel               | 5        | 5      | 1.52%   |
| Maxtor              | 4        | 4      | 1.21%   |
| KingSpec            | 4        | 4      | 1.21%   |
| SPCC                | 3        | 3      | 0.91%   |
| HGST                | 3        | 3      | 0.91%   |
| Team                | 2        | 2      | 0.61%   |
| PNY                 | 2        | 2      | 0.61%   |
| Netac               | 2        | 2      | 0.61%   |
| Lexar               | 2        | 2      | 0.61%   |
| KIOXIA-EXCERIA      | 2        | 2      | 0.61%   |
| Gigabyte Technology | 2        | 3      | 0.61%   |
| Apacer              | 2        | 2      | 0.61%   |
| AMD                 | 2        | 2      | 0.61%   |
| XPG                 | 1        | 1      | 0.3%    |
| WALRAM              | 1        | 1      | 0.3%    |
| Vaseky              | 1        | 1      | 0.3%    |
| TAMMUZ              | 1        | 1      | 0.3%    |
| SUNEAST             | 1        | 1      | 0.3%    |
| SK hynix            | 1        | 1      | 0.3%    |
| Silicon Motion      | 1        | 1      | 0.3%    |
| SETHRISE            | 1        | 1      | 0.3%    |
| RX7                 | 1        | 1      | 0.3%    |
| QUANTUM             | 1        | 1      | 0.3%    |
| Pioneer             | 1        | 1      | 0.3%    |
| Philips             | 1        | 1      | 0.3%    |
| Palit               | 1        | 1      | 0.3%    |
| OCZ                 | 1        | 1      | 0.3%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Kingston SA400S37240G 240GB     | 10       | 2.56%   |
| Seagate ST500DM002-1BD142 500GB | 6        | 1.54%   |
| Seagate ST3500418AS 500GB       | 5        | 1.28%   |
| Samsung SSD 860 EVO 500GB       | 5        | 1.28%   |
| Seagate ST1000DM010-2EP102 1TB  | 4        | 1.03%   |
| Samsung SSD 870 EVO 500GB       | 4        | 1.03%   |
| Samsung SSD 850 EVO 250GB       | 4        | 1.03%   |
| Kingston SA400S37120G 120GB     | 4        | 1.03%   |
| WDC WDS500G2B0A-00SM50 500GB    | 3        | 0.77%   |
| WDC WDS240G2G0A-00JH30 240GB    | 3        | 0.77%   |
| WDC WD20EFRX-68EUZN0 2TB        | 3        | 0.77%   |
| WDC WD10EZEX-60WN4A0 1TB        | 3        | 0.77%   |
| WDC WD10EZEX-08WN4A0 1TB        | 3        | 0.77%   |
| Toshiba HDWD110 1TB             | 3        | 0.77%   |
| Seagate ST2000DM008-2FR102 2TB  | 3        | 0.77%   |
| Samsung SSD 980 1TB             | 3        | 0.77%   |
| Samsung SSD 970 EVO Plus 500GB  | 3        | 0.77%   |
| Crucial CT500MX500SSD1 500GB    | 3        | 0.77%   |
| Crucial CT240BX500SSD1 240GB    | 3        | 0.77%   |
| A-DATA SU650 120GB              | 3        | 0.77%   |
| WDC WDS120G2G0A-00JH30 120GB    | 2        | 0.51%   |
| WDC WD5000AAKX-08U6AA0 500GB    | 2        | 0.51%   |
| WDC WD20EZRX-00D8PB0 2TB        | 2        | 0.51%   |
| WDC WD10EZEX-60WN4A1 1TB        | 2        | 0.51%   |
| Toshiba DT01ACA100 1TB          | 2        | 0.51%   |
| Toshiba DT01ACA050 500GB        | 2        | 0.51%   |
| SPCC Solid State Disk 128GB     | 2        | 0.51%   |
| Seagate ST3500312CS 500GB       | 2        | 0.51%   |
| Seagate ST3250312AS 250GB       | 2        | 0.51%   |
| Seagate ST3160815AS 160GB       | 2        | 0.51%   |
| Seagate ST250DM000-1BD141 250GB | 2        | 0.51%   |
| Seagate ST2000LM007-1R8174 2TB  | 2        | 0.51%   |
| Seagate ST1000DM003-1CH162 1TB  | 2        | 0.51%   |
| SanDisk pSSD 16GB               | 2        | 0.51%   |
| Samsung SSD 980 PRO 500GB       | 2        | 0.51%   |
| Samsung SSD 970 PRO 512GB       | 2        | 0.51%   |
| Samsung SSD 970 EVO Plus 1TB    | 2        | 0.51%   |
| Samsung SSD 860 EVO 250GB       | 2        | 0.51%   |
| Samsung HD103SJ 1TB             | 2        | 0.51%   |
| Patriot Burst Elite 120GB       | 2        | 0.51%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 52       | 78     | 37.96%  |
| WDC                 | 48       | 79     | 35.04%  |
| Toshiba             | 14       | 18     | 10.22%  |
| Hitachi             | 8        | 9      | 5.84%   |
| Samsung Electronics | 6        | 8      | 4.38%   |
| Maxtor              | 4        | 4      | 2.92%   |
| HGST                | 3        | 3      | 2.19%   |
| QUANTUM             | 1        | 1      | 0.73%   |
| Apple               | 1        | 1      | 0.73%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 23       | 30     | 16.08%  |
| Kingston            | 23       | 24     | 16.08%  |
| WDC                 | 12       | 12     | 8.39%   |
| SanDisk             | 10       | 10     | 6.99%   |
| Crucial             | 9        | 10     | 6.29%   |
| China               | 7        | 8      | 4.9%    |
| A-DATA Technology   | 7        | 7      | 4.9%    |
| Transcend           | 5        | 5      | 3.5%    |
| Patriot             | 4        | 4      | 2.8%    |
| KingSpec            | 4        | 4      | 2.8%    |
| Toshiba             | 3        | 5      | 2.1%    |
| Intel               | 3        | 3      | 2.1%    |
| SPCC                | 2        | 2      | 1.4%    |
| PNY                 | 2        | 2      | 1.4%    |
| Micron Technology   | 2        | 2      | 1.4%    |
| KIOXIA-EXCERIA      | 2        | 2      | 1.4%    |
| Apacer              | 2        | 2      | 1.4%    |
| WALRAM              | 1        | 1      | 0.7%    |
| Vaseky              | 1        | 1      | 0.7%    |
| Team                | 1        | 1      | 0.7%    |
| TAMMUZ              | 1        | 1      | 0.7%    |
| SUNEAST             | 1        | 1      | 0.7%    |
| SETHRISE            | 1        | 1      | 0.7%    |
| RX7                 | 1        | 1      | 0.7%    |
| Pioneer             | 1        | 1      | 0.7%    |
| Philips             | 1        | 1      | 0.7%    |
| Palit               | 1        | 1      | 0.7%    |
| OCZ                 | 1        | 1      | 0.7%    |
| LITEONIT            | 1        | 1      | 0.7%    |
| Lexar               | 1        | 1      | 0.7%    |
| Kston               | 1        | 1      | 0.7%    |
| Intenso             | 1        | 1      | 0.7%    |
| HEORIADY            | 1        | 1      | 0.7%    |
| GOODRAM             | 1        | 1      | 0.7%    |
| Gigabyte Technology | 1        | 2      | 0.7%    |
| EDGE                | 1        | 1      | 0.7%    |
| Drevo               | 1        | 1      | 0.7%    |
| Azerty              | 1        | 1      | 0.7%    |
| AMD                 | 1        | 1      | 0.7%    |
| addlink             | 1        | 1      | 0.7%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 115      | 201    | 40.35%  |
| SSD  | 113      | 156    | 39.65%  |
| NVMe | 57       | 68     | 20%     |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 185      | 357    | 76.45%  |
| NVMe | 57       | 68     | 23.55%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 158      | 228    | 66.39%  |
| 0.51-1.0   | 45       | 56     | 18.91%  |
| 1.01-2.0   | 20       | 42     | 8.4%    |
| 3.01-4.0   | 8        | 12     | 3.36%   |
| 2.01-3.0   | 3        | 6      | 1.26%   |
| 4.01-10.0  | 3        | 12     | 1.26%   |
| 10.01-20.0 | 1        | 1      | 0.42%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 1-20       | 117      | 53.67%  |
| 101-250    | 32       | 14.68%  |
| 251-500    | 29       | 13.3%   |
| 51-100     | 24       | 11.01%  |
| 501-1000   | 9        | 4.13%   |
| 21-50      | 5        | 2.29%   |
| 1001-2000  | 1        | 0.46%   |
| Unknown    | 1        | 0.46%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Desktops | Percent |
|---------|----------|---------|
| 1-20    | 207      | 97.64%  |
| 21-50   | 2        | 0.94%   |
| 251-500 | 1        | 0.47%   |
| 101-250 | 1        | 0.47%   |
| Unknown | 1        | 0.47%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                      | Desktops | Drives | Percent |
|--------------------------------------------|----------|--------|---------|
| Seagate ST3500418AS 500GB                  | 2        | 2      | 3.64%   |
| WDC WD800JD-75MSA3 80GB                    | 1        | 1      | 1.82%   |
| WDC WD6400BPVT-22HXZT3 640GB               | 1        | 1      | 1.82%   |
| WDC WD5000AAKX-08U6AA0 500GB               | 1        | 1      | 1.82%   |
| WDC WD5000AAKX-00ERMA0 500GB               | 1        | 1      | 1.82%   |
| WDC WD30EFRX-68EUZN0 3TB                   | 1        | 1      | 1.82%   |
| WDC WD20EZRX-00D8PB0 2TB                   | 1        | 1      | 1.82%   |
| WDC WD20EARS-00MVWB0 2TB                   | 1        | 1      | 1.82%   |
| WDC WD20EADS-00W4B0 2TB                    | 1        | 1      | 1.82%   |
| WDC WD1600YS-01SHB1 164GB                  | 1        | 1      | 1.82%   |
| WDC WD1600AAJS-60Z0A0 160GB                | 1        | 1      | 1.82%   |
| WDC WD10EZEX-60WN4A0 1TB                   | 1        | 1      | 1.82%   |
| WDC WD10EZEX-60M2NA0 1TB                   | 1        | 1      | 1.82%   |
| WDC WD10EARS-00MVWB0 1TB                   | 1        | 1      | 1.82%   |
| WDC WD10EARS-003BB1 1TB                    | 1        | 1      | 1.82%   |
| WDC WD10EADS-11M2B2 1TB                    | 1        | 1      | 1.82%   |
| Transcend TS120GSSD220S 120GB              | 1        | 1      | 1.82%   |
| Toshiba MK8052GSX 80GB                     | 1        | 1      | 1.82%   |
| Toshiba MK3259GSXP 320GB                   | 1        | 1      | 1.82%   |
| Toshiba DT01ACA100 1TB                     | 1        | 1      | 1.82%   |
| Toshiba DT01ABA200 2TB                     | 1        | 1      | 1.82%   |
| Silicon Motion Asgard AN1TNVMe-M.2-80 1TB  | 1        | 1      | 1.82%   |
| Seagate ST500LM000-1EJ162 500GB            | 1        | 1      | 1.82%   |
| Seagate ST500DM002-1BD142 500GB            | 1        | 1      | 1.82%   |
| Seagate ST380215AS 80GB                    | 1        | 1      | 1.82%   |
| Seagate ST3750528AS 752GB                  | 1        | 1      | 1.82%   |
| Seagate ST3500320AS 500GB                  | 1        | 1      | 1.82%   |
| Seagate ST3360320AS 360GB                  | 1        | 1      | 1.82%   |
| Seagate ST3320620AS 320GB                  | 1        | 1      | 1.82%   |
| Seagate ST3320418AS 320GB                  | 1        | 1      | 1.82%   |
| Seagate ST3250312AS 250GB                  | 1        | 2      | 1.82%   |
| Seagate ST250DM000-1BD141 250GB            | 1        | 1      | 1.82%   |
| Seagate ST2000DM008-2FR102 2TB             | 1        | 1      | 1.82%   |
| Seagate ST1000DM010-2EP102 1TB             | 1        | 1      | 1.82%   |
| Samsung Electronics SSD 860 EVO 500GB      | 1        | 1      | 1.82%   |
| Samsung Electronics MZVL22T0HBLB-00B00 2TB | 1        | 1      | 1.82%   |
| Samsung Electronics HD322HJ 320GB          | 1        | 1      | 1.82%   |
| Samsung Electronics HD161GJ 160GB          | 1        | 1      | 1.82%   |
| Samsung Electronics HD160JJ 160GB          | 1        | 1      | 1.82%   |
| Samsung Electronics HD103SJ 1TB            | 1        | 1      | 1.82%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 14       | 15     | 27.45%  |
| Seagate             | 12       | 15     | 23.53%  |
| Samsung Electronics | 5        | 6      | 9.8%    |
| Toshiba             | 4        | 4      | 7.84%   |
| Maxtor              | 3        | 3      | 5.88%   |
| Hitachi             | 3        | 3      | 5.88%   |
| HGST                | 2        | 2      | 3.92%   |
| Transcend           | 1        | 1      | 1.96%   |
| Silicon Motion      | 1        | 1      | 1.96%   |
| Micron Technology   | 1        | 1      | 1.96%   |
| Kingston            | 1        | 1      | 1.96%   |
| Intel               | 1        | 1      | 1.96%   |
| Crucial             | 1        | 1      | 1.96%   |
| China               | 1        | 1      | 1.96%   |
| A-DATA Technology   | 1        | 1      | 1.96%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 14       | 15     | 34.15%  |
| Seagate             | 12       | 15     | 29.27%  |
| Toshiba             | 4        | 4      | 9.76%   |
| Samsung Electronics | 3        | 4      | 7.32%   |
| Maxtor              | 3        | 3      | 7.32%   |
| Hitachi             | 3        | 3      | 7.32%   |
| HGST                | 2        | 2      | 4.88%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 41       | 46     | 80.39%  |
| SSD  | 7        | 7      | 13.73%  |
| NVMe | 3        | 3      | 5.88%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| WDC WD7501AALS-00J7B0 752GB     | 1        | 1      | 20%     |
| WDC WD1600BEVT-22ZCT0 160GB     | 1        | 1      | 20%     |
| SanDisk pSSD 16GB               | 1        | 1      | 20%     |
| Samsung Electronics HD103SJ 1TB | 1        | 1      | 20%     |
| Hitachi HDS721032CLA362 320GB   | 1        | 1      | 20%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 2        | 2      | 40%     |
| SanDisk             | 1        | 1      | 20%     |
| Samsung Electronics | 1        | 1      | 20%     |
| Hitachi             | 1        | 1      | 20%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 159      | 347    | 70.67%  |
| Malfunc  | 50       | 56     | 22.22%  |
| Detected | 11       | 17     | 4.89%   |
| Failed   | 5        | 5      | 2.22%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 154      | 52.38%  |
| AMD                         | 50       | 17.01%  |
| Samsung Electronics         | 19       | 6.46%   |
| Silicon Motion              | 9        | 3.06%   |
| Kingston Technology Company | 9        | 3.06%   |
| ASMedia Technology          | 9        | 3.06%   |
| Marvell Technology Group    | 7        | 2.38%   |
| SanDisk                     | 5        | 1.7%    |
| Nvidia                      | 5        | 1.7%    |
| JMicron Technology          | 5        | 1.7%    |
| Micron/Crucial Technology   | 3        | 1.02%   |
| Micron Technology           | 3        | 1.02%   |
| ADATA Technology            | 3        | 1.02%   |
| VIA Technologies            | 2        | 0.68%   |
| Realtek Semiconductor       | 2        | 0.68%   |
| Phison Electronics          | 2        | 0.68%   |
| MAXIO Technology (Hangzhou) | 2        | 0.68%   |
| SK hynix                    | 1        | 0.34%   |
| Seagate Technology          | 1        | 0.34%   |
| OCZ Technology Group        | 1        | 0.34%   |
| KIOXIA                      | 1        | 0.34%   |
| Broadcom / LSI              | 1        | 0.34%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 26       | 7.2%    |
| AMD FCH SATA Controller [AHCI mode]                                                     | 23       | 6.37%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 16       | 4.43%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 14       | 3.88%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 14       | 3.88%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 11       | 3.05%   |
| AMD 500 Series Chipset SATA Controller                                                  | 11       | 3.05%   |
| AMD 400 Series Chipset SATA Controller                                                  | 11       | 3.05%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 9        | 2.49%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 8        | 2.22%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 8        | 2.22%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 8        | 2.22%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 7        | 1.94%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 7        | 1.94%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 7        | 1.94%   |
| Intel SATA Controller [RAID mode]                                                       | 6        | 1.66%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 6        | 1.66%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 6        | 1.66%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 5        | 1.39%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 5        | 1.39%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 5        | 1.39%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 4        | 1.11%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 4        | 1.11%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 4        | 1.11%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4        | 1.11%   |
| Nvidia MCP61 SATA Controller                                                            | 3        | 0.83%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 3        | 0.83%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 3        | 0.83%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 3        | 0.83%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 3        | 0.83%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 3        | 0.83%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 3        | 0.83%   |
| Intel 82801JD/DO (ICH10 Family) 4-port SATA IDE Controller                              | 3        | 0.83%   |
| Intel 82801JD/DO (ICH10 Family) 2-port SATA IDE Controller                              | 3        | 0.83%   |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 3        | 0.83%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 3        | 0.83%   |
| AMD 300 Series Chipset SATA Controller                                                  | 3        | 0.83%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 2        | 0.55%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                               | 2        | 0.55%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2        | 0.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 167      | 58.8%   |
| NVMe | 57       | 20.07%  |
| IDE  | 48       | 16.9%   |
| RAID | 10       | 3.52%   |
| SAS  | 1        | 0.35%   |
| SCSI | 1        | 0.35%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 158      | 74.53%  |
| AMD    | 54       | 25.47%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| Intel Core i5-6500 CPU @ 3.20GHz              | 7        | 3.3%    |
| Intel Core i7-3770 CPU @ 3.40GHz              | 4        | 1.89%   |
| Intel Core i5-7400 CPU @ 3.00GHz              | 4        | 1.89%   |
| Intel Core i3-7100 CPU @ 3.90GHz              | 4        | 1.89%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 4        | 1.89%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 4        | 1.89%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 3        | 1.42%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 3        | 1.42%   |
| Intel Core i3-9100 CPU @ 3.60GHz              | 3        | 1.42%   |
| Intel Core i3-4160 CPU @ 3.60GHz              | 3        | 1.42%   |
| Intel Core i3-4130 CPU @ 3.40GHz              | 3        | 1.42%   |
| Intel Core i3-3220 CPU @ 3.30GHz              | 3        | 1.42%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 3        | 1.42%   |
| Intel Core i7-8700K CPU @ 3.70GHz             | 2        | 0.94%   |
| Intel Core i7-8700 CPU @ 3.20GHz              | 2        | 0.94%   |
| Intel Core i7-7700 CPU @ 3.60GHz              | 2        | 0.94%   |
| Intel Core i7-6700 CPU @ 3.40GHz              | 2        | 0.94%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 2        | 0.94%   |
| Intel Core i5-6500T CPU @ 2.50GHz             | 2        | 0.94%   |
| Intel Core i5-4570 CPU @ 3.20GHz              | 2        | 0.94%   |
| Intel Core i5-4440 CPU @ 3.10GHz              | 2        | 0.94%   |
| Intel Core i3-6100 CPU @ 3.70GHz              | 2        | 0.94%   |
| Intel Core i3-3240 CPU @ 3.40GHz              | 2        | 0.94%   |
| Intel Core i3-2100 CPU @ 3.10GHz              | 2        | 0.94%   |
| Intel Core i3-10100 CPU @ 3.60GHz             | 2        | 0.94%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 2        | 0.94%   |
| Intel Core 2 Duo                              | 2        | 0.94%   |
| Intel Celeron N5105 @ 2.00GHz                 | 2        | 0.94%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 2        | 0.94%   |
| Intel Celeron CPU J1900 @ 1.99GHz             | 2        | 0.94%   |
| Intel 12th Gen Core i5-12400                  | 2        | 0.94%   |
| AMD Ryzen 7 5700X 8-Core Processor            | 2        | 0.94%   |
| AMD Ryzen 7 3750H with Radeon Vega Mobile Gfx | 2        | 0.94%   |
| AMD Ryzen 5 5600 6-Core Processor             | 2        | 0.94%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics   | 2        | 0.94%   |
| AMD Athlon II X2 250 Processor                | 2        | 0.94%   |
| Intel Xeon W-2125 CPU @ 4.00GHz               | 1        | 0.47%   |
| Intel Xeon CPU W3670 @ 3.20GHz                | 1        | 0.47%   |
| Intel Xeon CPU E5-2690 v4 @ 2.60GHz           | 1        | 0.47%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz           | 1        | 0.47%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 44       | 20.75%  |
| Intel Core i3           | 30       | 14.15%  |
| Intel Core i7           | 24       | 11.32%  |
| AMD Ryzen 5             | 17       | 8.02%   |
| Intel Celeron           | 14       | 6.6%    |
| Intel Xeon              | 11       | 5.19%   |
| Intel Core 2 Duo        | 11       | 5.19%   |
| AMD Ryzen 7             | 9        | 4.25%   |
| Other                   | 8        | 3.77%   |
| AMD Ryzen 3             | 6        | 2.83%   |
| Intel Pentium           | 5        | 2.36%   |
| AMD Athlon II X2        | 4        | 1.89%   |
| Intel Core 2 Quad       | 3        | 1.42%   |
| AMD Phenom II X4        | 3        | 1.42%   |
| Intel Pentium Dual-Core | 2        | 0.94%   |
| Intel Core i9           | 2        | 0.94%   |
| AMD A4                  | 2        | 0.94%   |
| Intel Pentium Gold      | 1        | 0.47%   |
| Intel Pentium 4         | 1        | 0.47%   |
| Intel Core 2            | 1        | 0.47%   |
| Intel Atom              | 1        | 0.47%   |
| AMD Ryzen 9             | 1        | 0.47%   |
| AMD Ryzen 3 PRO         | 1        | 0.47%   |
| AMD PRO A10             | 1        | 0.47%   |
| AMD Phenom II X6        | 1        | 0.47%   |
| AMD Phenom II X2        | 1        | 0.47%   |
| AMD GX                  | 1        | 0.47%   |
| AMD FX                  | 1        | 0.47%   |
| AMD E                   | 1        | 0.47%   |
| AMD Athlon X2           | 1        | 0.47%   |
| AMD Athlon II X4        | 1        | 0.47%   |
| AMD Athlon 64           | 1        | 0.47%   |
| AMD A6                  | 1        | 0.47%   |
| AMD A10                 | 1        | 0.47%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 91       | 42.92%  |
| 2       | 57       | 26.89%  |
| 6       | 19       | 8.96%   |
| 12      | 13       | 6.13%   |
| 8       | 11       | 5.19%   |
| 16      | 8        | 3.77%   |
| Unknown | 8        | 3.77%   |
| 1       | 2        | 0.94%   |
| 24      | 1        | 0.47%   |
| 14      | 1        | 0.47%   |
| 10      | 1        | 0.47%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 210      | 99.06%  |
| 2      | 2        | 0.94%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 130      | 61.32%  |
| 2       | 73       | 34.43%  |
| Unknown | 9        | 4.25%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Haswell       | 32       | 15.09%  |
| KabyLake      | 26       | 12.26%  |
| IvyBridge     | 18       | 8.49%   |
| Skylake       | 17       | 8.02%   |
| SandyBridge   | 15       | 7.08%   |
| Penryn        | 14       | 6.6%    |
| Zen+          | 12       | 5.66%   |
| Zen 3         | 12       | 5.66%   |
| K10           | 11       | 5.19%   |
| Unknown       | 10       | 4.72%   |
| Zen           | 7        | 3.3%    |
| Core          | 6        | 2.83%   |
| CometLake     | 6        | 2.83%   |
| Piledriver    | 4        | 1.89%   |
| Nehalem       | 4        | 1.89%   |
| Silvermont    | 3        | 1.42%   |
| Zen 2         | 2        | 0.94%   |
| Westmere      | 2        | 0.94%   |
| Goldmont plus | 2        | 0.94%   |
| Goldmont      | 2        | 0.94%   |
| NetBurst      | 1        | 0.47%   |
| K8 Hammer     | 1        | 0.47%   |
| Jaguar        | 1        | 0.47%   |
| Excavator     | 1        | 0.47%   |
| Bulldozer     | 1        | 0.47%   |
| Broadwell     | 1        | 0.47%   |
| Bobcat        | 1        | 0.47%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 98       | 43.17%  |
| AMD                        | 67       | 29.52%  |
| Nvidia                     | 61       | 26.87%  |
| Matrox Electronics Systems | 1        | 0.44%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 16       | 6.96%   |
| Intel HD Graphics 530                                                       | 12       | 5.22%   |
| Intel HD Graphics 630                                                       | 10       | 4.35%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 9        | 3.91%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 8        | 3.48%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 7        | 3.04%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 7        | 3.04%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 7        | 3.04%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 7        | 3.04%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 7        | 3.04%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 6        | 2.61%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 4        | 1.74%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 4        | 1.74%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 3        | 1.3%    |
| Nvidia GT218 [GeForce 210]                                                  | 3        | 1.3%    |
| Nvidia GK208B [GeForce GT 730]                                              | 3        | 1.3%    |
| Nvidia GK208B [GeForce GT 710]                                              | 3        | 1.3%    |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 3        | 1.3%    |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 3        | 1.3%    |
| AMD RS880 [Radeon HD 4250]                                                  | 3        | 1.3%    |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 3        | 1.3%    |
| Nvidia TU116 [GeForce GTX 1660]                                             | 2        | 0.87%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 0.87%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 2        | 0.87%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 2        | 0.87%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 2        | 0.87%   |
| Nvidia GK104 [GeForce GTX 680]                                              | 2        | 0.87%   |
| Nvidia GF119 [GeForce GT 610]                                               | 2        | 0.87%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 2        | 0.87%   |
| Intel JasperLake [UHD Graphics]                                             | 2        | 0.87%   |
| Intel HD Graphics 500                                                       | 2        | 0.87%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 2        | 0.87%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 2        | 0.87%   |
| Intel Alder Lake-S GT1 [UHD Graphics 730]                                   | 2        | 0.87%   |
| Intel 82Q35 Express Integrated Graphics Controller                          | 2        | 0.87%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]       | 2        | 0.87%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 2        | 0.87%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 2        | 0.87%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 0.43%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1        | 0.43%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| 1 x Intel                | 78       | 36.45%  |
| 1 x AMD                  | 56       | 26.17%  |
| 1 x Nvidia               | 55       | 25.7%   |
| Intel + AMD              | 9        | 4.21%   |
| 2 x Intel                | 7        | 3.27%   |
| Intel + Nvidia           | 4        | 1.87%   |
| Other                    | 1        | 0.47%   |
| 2 x AMD                  | 1        | 0.47%   |
| 1 x Matrox               | 1        | 0.47%   |
| Intel + AMD + 1 x Nvidia | 1        | 0.47%   |
| AMD + Nvidia             | 1        | 0.47%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 167      | 78.4%   |
| Proprietary | 41       | 19.25%  |
| Unknown     | 5        | 2.35%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 136      | 63.26%  |
| 3.01-4.0   | 19       | 8.84%   |
| 1.01-2.0   | 18       | 8.37%   |
| 0.51-1.0   | 13       | 6.05%   |
| 0.01-0.5   | 10       | 4.65%   |
| 5.01-6.0   | 8        | 3.72%   |
| 7.01-8.0   | 7        | 3.26%   |
| 2.01-3.0   | 2        | 0.93%   |
| 8.01-16.0  | 2        | 0.93%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 15       | 13.76%  |
| Acer                 | 14       | 12.84%  |
| Goldstar             | 10       | 9.17%   |
| Dell                 | 10       | 9.17%   |
| Hewlett-Packard      | 9        | 8.26%   |
| BenQ                 | 9        | 8.26%   |
| Ancor Communications | 7        | 6.42%   |
| Philips              | 4        | 3.67%   |
| AOC                  | 4        | 3.67%   |
| Lenovo               | 3        | 2.75%   |
| ONN                  | 2        | 1.83%   |
| LG Electronics       | 2        | 1.83%   |
| ASUSTek Computer     | 2        | 1.83%   |
| Unknown              | 2        | 1.83%   |
| Vizio                | 1        | 0.92%   |
| ViewSonic            | 1        | 0.92%   |
| Semp Toshiba         | 1        | 0.92%   |
| PKB                  | 1        | 0.92%   |
| NEC Computers        | 1        | 0.92%   |
| MStar                | 1        | 0.92%   |
| MSI                  | 1        | 0.92%   |
| Microstep            | 1        | 0.92%   |
| ITE                  | 1        | 0.92%   |
| Idek Iiyama          | 1        | 0.92%   |
| Fujitsu Siemens      | 1        | 0.92%   |
| Eizo                 | 1        | 0.92%   |
| DENON                | 1        | 0.92%   |
| CVT                  | 1        | 0.92%   |
| AUS                  | 1        | 0.92%   |
| Apple                | 1        | 0.92%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| ONN 100002487 ONN0101 1920x1080 520x320mm 24.0-inch                    | 2        | 1.83%   |
| Acer G276HL ACR0300 1920x1080 600x340mm 27.2-inch                      | 2        | 1.83%   |
| Unknown                                                                | 2        | 1.83%   |
| Vizio E321VL VIZ0083 1366x768 700x400mm 31.7-inch                      | 1        | 0.92%   |
| ViewSonic TD2220 VSC052C 1920x1080 480x270mm 21.7-inch                 | 1        | 0.92%   |
| Semp Toshiba MLE1951 STI1951 1366x768 410x230mm 18.5-inch              | 1        | 0.92%   |
| Samsung Electronics SyncMaster SAM05FB 1920x1080 510x290mm 23.1-inch   | 1        | 0.92%   |
| Samsung Electronics SyncMaster SAM058F 1920x1080 480x270mm 21.7-inch   | 1        | 0.92%   |
| Samsung Electronics SyncMaster SAM050B 1920x1080 480x270mm 21.7-inch   | 1        | 0.92%   |
| Samsung Electronics SyncMaster SAM030D 1680x1050 470x300mm 22.0-inch   | 1        | 0.92%   |
| Samsung Electronics SMS27A850 SAM083D 2560x1440 520x320mm 24.0-inch    | 1        | 0.92%   |
| Samsung Electronics S27R35x SAM1053 1920x1080 600x340mm 27.2-inch      | 1        | 0.92%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 600x340mm 27.2-inch      | 1        | 0.92%   |
| Samsung Electronics S24E450 SAM0C80 1920x1080 520x290mm 23.4-inch      | 1        | 0.92%   |
| Samsung Electronics S24C350 SAM0A3A 1920x1080 530x300mm 24.0-inch      | 1        | 0.92%   |
| Samsung Electronics S22B150 SAM08A3 1920x1080 480x270mm 21.7-inch      | 1        | 0.92%   |
| Samsung Electronics S20B300 SAM08A7 1600x900 440x250mm 19.9-inch       | 1        | 0.92%   |
| Samsung Electronics S19B150 SAM08A2 1366x768 410x230mm 18.5-inch       | 1        | 0.92%   |
| Samsung Electronics Odyssey G50A SAM7181 2560x1440 600x340mm 27.2-inch | 1        | 0.92%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 530x300mm 24.0-inch   | 1        | 0.92%   |
| Samsung Electronics LCD Monitor SAM0509 1920x1080                      | 1        | 0.92%   |
| PKB LCD Monitor MAE200W 1680x1050                                      | 1        | 0.92%   |
| Philips PHL 223V7 PHLC154 1920x1080 480x270mm 21.7-inch                | 1        | 0.92%   |
| Philips PHL 221S8L PHL091C 1920x1080 480x270mm 21.7-inch               | 1        | 0.92%   |
| Philips 202EL PHLC05C 1600x900 440x250mm 19.9-inch                     | 1        | 0.92%   |
| Philips 150S PHL0820 1024x768 300x230mm 14.9-inch                      | 1        | 0.92%   |
| NEC Computers LCD Monitor 70GX2 1280x1024                              | 1        | 0.92%   |
| MStar TSB LEDTV MST0030 1920x1080 1150x650mm 52.0-inch                 | 1        | 0.92%   |
| MSI MP242 MSI30A1 1920x1080 530x300mm 24.0-inch                        | 1        | 0.92%   |
| Microstep LCD Monitor MSI MAG241C 1920x1080                            | 1        | 0.92%   |
| LG Electronics LCD Monitor LG FULL HD 1920x1080                        | 1        | 0.92%   |
| LG Electronics LCD Monitor L1918S 1280x1024                            | 1        | 0.92%   |
| Lenovo L24e-30 LEN66BC 1920x1080 530x300mm 24.0-inch                   | 1        | 0.92%   |
| Lenovo D27-30 LEN66B8 1920x1080 600x340mm 27.2-inch                    | 1        | 0.92%   |
| Lenovo C19-10 LEN66A0 1366x768 410x230mm 18.5-inch                     | 1        | 0.92%   |
| ITE DP2VGA V235 ITE6516 1920x1080 600x340mm 27.2-inch                  | 1        | 0.92%   |
| Idek Iiyama LCD Monitor PL2209HD 5760x2160                             | 1        | 0.92%   |
| Hewlett-Packard ZR2740w HWP2957 2560x1440 600x340mm 27.2-inch          | 1        | 0.92%   |
| Hewlett-Packard Z24nq HWP3239 2560x1440 530x300mm 24.0-inch            | 1        | 0.92%   |
| Hewlett-Packard w2007 HWP26A6 1680x1050 430x270mm 20.0-inch            | 1        | 0.92%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 60       | 56.07%  |
| 1366x768 (WXGA)    | 11       | 10.28%  |
| 2560x1440 (QHD)    | 10       | 9.35%   |
| 1280x1024 (SXGA)   | 5        | 4.67%   |
| 1680x1050 (WSXGA+) | 4        | 3.74%   |
| 3840x2160 (4K)     | 3        | 2.8%    |
| 1600x900 (HD+)     | 3        | 2.8%    |
| 1440x900 (WXGA+)   | 3        | 2.8%    |
| 1920x1200 (WUXGA)  | 2        | 1.87%   |
| Unknown            | 2        | 1.87%   |
| 5760x2160          | 1        | 0.93%   |
| 3840x1080          | 1        | 0.93%   |
| 2560x1080          | 1        | 0.93%   |
| 1024x768 (XGA)     | 1        | 0.93%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 20       | 18.87%  |
| 21      | 20       | 18.87%  |
| Unknown | 18       | 16.98%  |
| 27      | 12       | 11.32%  |
| 23      | 9        | 8.49%   |
| 18      | 9        | 8.49%   |
| 19      | 7        | 6.6%    |
| 31      | 3        | 2.83%   |
| 20      | 3        | 2.83%   |
| 22      | 2        | 1.89%   |
| 52      | 1        | 0.94%   |
| 34      | 1        | 0.94%   |
| 14      | 1        | 0.94%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 41       | 38.68%  |
| 401-500     | 37       | 34.91%  |
| Unknown     | 18       | 16.98%  |
| 351-400     | 4        | 3.77%   |
| 601-700     | 3        | 2.83%   |
| 701-800     | 1        | 0.94%   |
| 201-300     | 1        | 0.94%   |
| 1001-1500   | 1        | 0.94%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 69       | 66.99%  |
| Unknown | 17       | 16.5%   |
| 16/10   | 11       | 10.68%  |
| 5/4     | 3        | 2.91%   |
| 6/5     | 1        | 0.97%   |
| 4/3     | 1        | 0.97%   |
| 21/9    | 1        | 0.97%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 45       | 42.45%  |
| Unknown        | 18       | 16.98%  |
| 301-350        | 12       | 11.32%  |
| 151-200        | 12       | 11.32%  |
| 141-150        | 8        | 7.55%   |
| 251-300        | 5        | 4.72%   |
| 351-500        | 4        | 3.77%   |
| More than 1000 | 1        | 0.94%   |
| 101-110        | 1        | 0.94%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 56       | 53.33%  |
| 101-120 | 24       | 22.86%  |
| Unknown | 18       | 17.14%  |
| 121-160 | 5        | 4.76%   |
| 1-50    | 2        | 1.9%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 171      | 80.28%  |
| 0     | 35       | 16.43%  |
| 2     | 7        | 3.29%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 126      | 46.84%  |
| Intel                    | 88       | 32.71%  |
| Qualcomm Atheros         | 16       | 5.95%   |
| Ralink Technology        | 5        | 1.86%   |
| Marvell Technology Group | 5        | 1.86%   |
| Samsung Electronics      | 4        | 1.49%   |
| Ralink                   | 4        | 1.49%   |
| Broadcom                 | 4        | 1.49%   |
| TP-Link                  | 3        | 1.12%   |
| Edimax Technology        | 3        | 1.12%   |
| Huawei Technologies      | 2        | 0.74%   |
| D-Link                   | 2        | 0.74%   |
| Qualcomm                 | 1        | 0.37%   |
| National Semiconductor   | 1        | 0.37%   |
| MediaTek                 | 1        | 0.37%   |
| D-Link System            | 1        | 0.37%   |
| Atheros                  | 1        | 0.37%   |
| Arduino SA               | 1        | 0.37%   |
| Accton Technology        | 1        | 0.37%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 109      | 36.58%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 12       | 4.03%   |
| Intel Ethernet Controller I225-V                                       | 8        | 2.68%   |
| Intel Ethernet Connection (2) I219-LM                                  | 8        | 2.68%   |
| Intel Ethernet Connection I217-LM                                      | 7        | 2.35%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 6        | 2.01%   |
| Intel 82579V Gigabit Network Connection                                | 6        | 2.01%   |
| Intel Ethernet Connection I217-V                                       | 5        | 1.68%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 4        | 1.34%   |
| Intel I211 Gigabit Network Connection                                  | 4        | 1.34%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 4        | 1.34%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 3        | 1.01%   |
| Realtek RTL8125 2.5GbE Controller                                      | 3        | 1.01%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 3        | 1.01%   |
| Intel Wireless 3165                                                    | 3        | 1.01%   |
| Intel Ethernet Connection (7) I219-V                                   | 3        | 1.01%   |
| Intel Ethernet Connection (2) I219-V                                   | 3        | 1.01%   |
| Intel 82574L Gigabit Network Connection                                | 3        | 1.01%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 2        | 0.67%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                        | 2        | 0.67%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 2        | 0.67%   |
| Ralink RT2870/RT3070 Wireless Adapter                                  | 2        | 0.67%   |
| Ralink MT7601U Wireless Adapter                                        | 2        | 0.67%   |
| Ralink RT2500 Wireless 802.11bg                                        | 2        | 0.67%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 2        | 0.67%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 2        | 0.67%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                       | 2        | 0.67%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)         | 2        | 0.67%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 2        | 0.67%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 2        | 0.67%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                | 2        | 0.67%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 2        | 0.67%   |
| Intel Wireless 8265 / 8275                                             | 2        | 0.67%   |
| Intel Wireless 7260                                                    | 2        | 0.67%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 2        | 0.67%   |
| Intel Wi-Fi 6 AX200                                                    | 2        | 0.67%   |
| Intel Tiger Lake PCH CNVi WiFi                                         | 2        | 0.67%   |
| Intel I210 Gigabit Network Connection                                  | 2        | 0.67%   |
| Intel Ethernet Connection (7) I219-LM                                  | 2        | 0.67%   |
| Intel Ethernet Connection (5) I219-LM                                  | 2        | 0.67%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 22       | 29.33%  |
| Realtek Semiconductor | 19       | 25.33%  |
| Qualcomm Atheros      | 9        | 12%     |
| Ralink Technology     | 5        | 6.67%   |
| Ralink                | 4        | 5.33%   |
| Broadcom              | 4        | 5.33%   |
| TP-Link               | 3        | 4%      |
| Edimax Technology     | 3        | 4%      |
| D-Link                | 2        | 2.67%   |
| MediaTek              | 1        | 1.33%   |
| D-Link System         | 1        | 1.33%   |
| Atheros               | 1        | 1.33%   |
| Accton Technology     | 1        | 1.33%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 6        | 7.89%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 4        | 5.26%   |
| Intel Wireless 3165                                                        | 3        | 3.95%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                               | 2        | 2.63%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                            | 2        | 2.63%   |
| Ralink RT2870/RT3070 Wireless Adapter                                      | 2        | 2.63%   |
| Ralink MT7601U Wireless Adapter                                            | 2        | 2.63%   |
| Ralink RT2500 Wireless 802.11bg                                            | 2        | 2.63%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                 | 2        | 2.63%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                           | 2        | 2.63%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                           | 2        | 2.63%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)             | 2        | 2.63%   |
| Intel Wireless 8265 / 8275                                                 | 2        | 2.63%   |
| Intel Wireless 7260                                                        | 2        | 2.63%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                  | 2        | 2.63%   |
| Intel Wi-Fi 6 AX200                                                        | 2        | 2.63%   |
| Intel Tiger Lake PCH CNVi WiFi                                             | 2        | 2.63%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                           | 2        | 2.63%   |
| Intel Cannon Lake PCH CNVi WiFi                                            | 2        | 2.63%   |
| Intel Alder Lake-S PCH CNVi WiFi                                           | 2        | 2.63%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]             | 2        | 2.63%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                        | 1        | 1.32%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                | 1        | 1.32%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                   | 1        | 1.32%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                            | 1        | 1.32%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                   | 1        | 1.32%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                | 1        | 1.32%   |
| Realtek RTL8188EE Wireless Network Adapter                                 | 1        | 1.32%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                    | 1        | 1.32%   |
| Realtek 8811CU Wireless LAN 802.11ac USB NIC                               | 1        | 1.32%   |
| Ralink RT3072 Wireless Adapter                                             | 1        | 1.32%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                  | 1        | 1.32%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                  | 1        | 1.32%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)             | 1        | 1.32%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter              | 1        | 1.32%   |
| Intel Wireless 8260                                                        | 1        | 1.32%   |
| Intel Wireless 7265                                                        | 1        | 1.32%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                    | 1        | 1.32%   |
| Edimax EW-7711UTn nLite Wireless Adapter [Ralink RT3070]                   | 1        | 1.32%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W] | 1        | 1.32%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 118      | 54.38%  |
| Intel                    | 78       | 35.94%  |
| Qualcomm Atheros         | 7        | 3.23%   |
| Marvell Technology Group | 5        | 2.3%    |
| Samsung Electronics      | 4        | 1.84%   |
| Huawei Technologies      | 2        | 0.92%   |
| Qualcomm                 | 1        | 0.46%   |
| National Semiconductor   | 1        | 0.46%   |
| Broadcom                 | 1        | 0.46%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 109      | 49.32%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 12       | 5.43%   |
| Intel Ethernet Controller I225-V                                       | 8        | 3.62%   |
| Intel Ethernet Connection (2) I219-LM                                  | 8        | 3.62%   |
| Intel Ethernet Connection I217-LM                                      | 7        | 3.17%   |
| Intel 82579V Gigabit Network Connection                                | 6        | 2.71%   |
| Intel Ethernet Connection I217-V                                       | 5        | 2.26%   |
| Intel I211 Gigabit Network Connection                                  | 4        | 1.81%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 4        | 1.81%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 3        | 1.36%   |
| Realtek RTL8125 2.5GbE Controller                                      | 3        | 1.36%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 3        | 1.36%   |
| Intel Ethernet Connection (7) I219-V                                   | 3        | 1.36%   |
| Intel Ethernet Connection (2) I219-V                                   | 3        | 1.36%   |
| Intel 82574L Gigabit Network Connection                                | 3        | 1.36%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 2        | 0.9%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 2        | 0.9%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 2        | 0.9%    |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                | 2        | 0.9%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 2        | 0.9%    |
| Intel I210 Gigabit Network Connection                                  | 2        | 0.9%    |
| Intel Ethernet Connection (7) I219-LM                                  | 2        | 0.9%    |
| Intel Ethernet Connection (5) I219-LM                                  | 2        | 0.9%    |
| Intel Ethernet Connection (17) I219-V                                  | 2        | 0.9%    |
| Intel Ethernet Connection (14) I219-V                                  | 2        | 0.9%    |
| Intel 82567LF-3 Gigabit Network Connection                             | 2        | 0.9%    |
| Intel 82566DM-2 Gigabit Network Connection                             | 2        | 0.9%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 1        | 0.45%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller      | 1        | 0.45%   |
| Qualcomm FP3                                                           | 1        | 0.45%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                          | 1        | 0.45%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 1        | 0.45%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 1        | 0.45%   |
| National DP83815 (MacPhyter) Ethernet Controller                       | 1        | 0.45%   |
| Marvell Group 88E8070 based Ethernet Controller                        | 1        | 0.45%   |
| Intel Ethernet Controller I226-V                                       | 1        | 0.45%   |
| Intel Ethernet Connection (5) I219-V                                   | 1        | 0.45%   |
| Intel Ethernet Connection (2) I218-V                                   | 1        | 0.45%   |
| Intel Ethernet Connection (2) I218-LM                                  | 1        | 0.45%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                   | 1        | 0.45%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 205      | 74.82%  |
| WiFi     | 68       | 24.82%  |
| Modem    | 1        | 0.36%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 180      | 95.24%  |
| WiFi     | 9        | 4.76%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 146      | 68.54%  |
| 2     | 55       | 25.82%  |
| 3     | 6        | 2.82%   |
| 0     | 6        | 2.82%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 203      | 94.42%  |
| Yes  | 12       | 5.58%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 20       | 35.09%  |
| Realtek Semiconductor           | 12       | 21.05%  |
| Cambridge Silicon Radio         | 10       | 17.54%  |
| ASUSTek Computer                | 3        | 5.26%   |
| TP-Link                         | 2        | 3.51%   |
| IMC Networks                    | 2        | 3.51%   |
| Broadcom                        | 2        | 3.51%   |
| Apple                           | 2        | 3.51%   |
| Qualcomm Atheros Communications | 1        | 1.75%   |
| Primax Electronics              | 1        | 1.75%   |
| Lite-On Technology              | 1        | 1.75%   |
| Fujitsu                         | 1        | 1.75%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 10       | 17.54%  |
| Realtek Bluetooth Adapter                                   | 8        | 14.04%  |
| Intel Bluetooth wireless interface                          | 8        | 14.04%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 3        | 5.26%   |
| Intel AX201 Bluetooth                                       | 3        | 5.26%   |
| TP-Link Bluetooth 5.0 USB Adapter                           | 2        | 3.51%   |
| Realtek  Bluetooth 4.2 Adapter                              | 2        | 3.51%   |
| Intel Wireless-AC 3168 Bluetooth                            | 2        | 3.51%   |
| Intel AX210 Bluetooth                                       | 2        | 3.51%   |
| Broadcom BCM20702A0 Bluetooth 4.0                           | 2        | 3.51%   |
| Realtek Bluetooth 5.1 Adapter                               | 1        | 1.75%   |
| Realtek Bluetooth 4.2 Adapter                               | 1        | 1.75%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1        | 1.75%   |
| Primax Rocketfish RF-FLBTAD Bluetooth Adapter               | 1        | 1.75%   |
| Lite-On Atheros AR3012 Bluetooth                            | 1        | 1.75%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 1        | 1.75%   |
| Intel AX200 Bluetooth                                       | 1        | 1.75%   |
| IMC Networks Qualcomm Atheros AR9462 Bluetooth 4.0 + HS     | 1        | 1.75%   |
| IMC Networks MediaTek Bluetooth Adapter                     | 1        | 1.75%   |
| Fujitsu Qualcomm Atheros AR9462 Bluetooth 4.0 + HS Adapter  | 1        | 1.75%   |
| ASUS USB-BT500                                              | 1        | 1.75%   |
| ASUS Broadcom BCM20702A0 Bluetooth                          | 1        | 1.75%   |
| ASUS Bluetooth Controller                                   | 1        | 1.75%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 1        | 1.75%   |
| Apple Bluetooth Host Controller                             | 1        | 1.75%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 148      | 44.71%  |
| AMD                      | 80       | 24.17%  |
| Nvidia                   | 55       | 16.62%  |
| C-Media Electronics      | 18       | 5.44%   |
| Texas Instruments        | 5        | 1.51%   |
| Creative Labs            | 3        | 0.91%   |
| Realtek Semiconductor    | 2        | 0.6%    |
| JMTek                    | 2        | 0.6%    |
| Unknown                  | 2        | 0.6%    |
| Yamaha                   | 1        | 0.3%    |
| SteelSeries ApS          | 1        | 0.3%    |
| Razer USA                | 1        | 0.3%    |
| OPPO Electronics         | 1        | 0.3%    |
| Microsoft                | 1        | 0.3%    |
| Micro Star International | 1        | 0.3%    |
| M-Audio                  | 1        | 0.3%    |
| KTMicro                  | 1        | 0.3%    |
| Hewlett-Packard          | 1        | 0.3%    |
| HECATE G2 GAMING HEADSET | 1        | 0.3%    |
| Harman                   | 1        | 0.3%    |
| Generalplus Technology   | 1        | 0.3%    |
| GEMBIRD                  | 1        | 0.3%    |
| Edifier Technology       | 1        | 0.3%    |
| Creative Technology      | 1        | 0.3%    |
| Cambridge Silicon Radio  | 1        | 0.3%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 27       | 6.89%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 22       | 5.61%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 19       | 4.85%   |
| Intel 200 Series PCH HD Audio                                              | 17       | 4.34%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 15       | 3.83%   |
| AMD Family 17h/19h HD Audio Controller                                     | 15       | 3.83%   |
| AMD Starship/Matisse HD Audio Controller                                   | 11       | 2.81%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 11       | 2.81%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 10       | 2.55%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 10       | 2.55%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 9        | 2.3%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 9        | 2.3%    |
| Intel Cannon Lake PCH cAVS                                                 | 8        | 2.04%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 8        | 2.04%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 8        | 2.04%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 7        | 1.79%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 6        | 1.53%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 6        | 1.53%   |
| Nvidia TU116 High Definition Audio Controller                              | 5        | 1.28%   |
| Nvidia High Definition Audio Controller                                    | 5        | 1.28%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5        | 1.28%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 5        | 1.28%   |
| AMD FCH Azalia Controller                                                  | 5        | 1.28%   |
| Nvidia GP107GL High Definition Audio Controller                            | 4        | 1.02%   |
| Nvidia GP106 High Definition Audio Controller                              | 4        | 1.02%   |
| Nvidia GK107 HDMI Audio Controller                                         | 4        | 1.02%   |
| Intel Alder Lake-S HD Audio Controller                                     | 4        | 1.02%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 4        | 1.02%   |
| Nvidia MCP61 High Definition Audio                                         | 3        | 0.77%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 3        | 0.77%   |
| Nvidia GK104 HDMI Audio Controller                                         | 3        | 0.77%   |
| Nvidia GA104 High Definition Audio Controller                              | 3        | 0.77%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 3        | 0.77%   |
| Intel Comet Lake PCH-V cAVS                                                | 3        | 0.77%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 3        | 0.77%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3        | 0.77%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                              | 3        | 0.77%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                 | 3        | 0.77%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                               | 3        | 0.77%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 3        | 0.77%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 46       | 18.11%  |
| Samsung Electronics | 30       | 11.81%  |
| Unknown             | 27       | 10.63%  |
| Corsair             | 22       | 8.66%   |
| Micron Technology   | 21       | 8.27%   |
| SK hynix            | 18       | 7.09%   |
| Crucial             | 18       | 7.09%   |
| G.Skill             | 13       | 5.12%   |
| Unknown             | 11       | 4.33%   |
| Patriot             | 6        | 2.36%   |
| Nanya Technology    | 6        | 2.36%   |
| A-DATA Technology   | 5        | 1.97%   |
| Ramaxel Technology  | 4        | 1.57%   |
| Apacer              | 3        | 1.18%   |
| Unknown (ABCD)      | 2        | 0.79%   |
| Transcend           | 2        | 0.79%   |
| Team                | 2        | 0.79%   |
| Lexar               | 2        | 0.79%   |
| Kingmax             | 2        | 0.79%   |
| GOODRAM             | 2        | 0.79%   |
| Atermiter           | 2        | 0.79%   |
| Unknown (8A02)      | 1        | 0.39%   |
| Teikon              | 1        | 0.39%   |
| Smart               | 1        | 0.39%   |
| Qumo                | 1        | 0.39%   |
| MemoWise            | 1        | 0.39%   |
| Juhor               | 1        | 0.39%   |
| Golden Empire       | 1        | 0.39%   |
| Elpida              | 1        | 0.39%   |
| Avant               | 1        | 0.39%   |
| AMD                 | 1        | 0.39%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Unknown                                                                 | 11       | 4.01%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                                    | 5        | 1.82%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s                     | 4        | 1.46%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s                   | 4        | 1.46%   |
| Unknown RAM Module 2GB DIMM 800MT/s                                     | 3        | 1.09%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                                    | 3        | 1.09%   |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3200MT/s                     | 3        | 1.09%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                               | 2        | 0.73%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                                    | 2        | 0.73%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                                | 2        | 0.73%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                                | 2        | 0.73%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s            | 2        | 0.73%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                             | 2        | 0.73%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                   | 2        | 0.73%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s                   | 2        | 0.73%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s                     | 2        | 0.73%   |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM DDR3 1333MT/s                     | 2        | 0.73%   |
| Samsung RAM M3 78T2863DZS-CE6 1GB DIMM DDR2 667MT/s                     | 2        | 0.73%   |
| Patriot RAM 2666 C16 Series 4GB DIMM DDR4 3000MT/s                      | 2        | 0.73%   |
| Nanya RAM NT2GC64B88B0NF-CG 2GB DIMM DDR3 1333MT/s                      | 2        | 0.73%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s                     | 2        | 0.73%   |
| Micron RAM 8ATF1G64AZ-2G3H1 8GB DIMM DDR4 2400MT/s                      | 2        | 0.73%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2400MT/s                       | 2        | 0.73%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s                     | 2        | 0.73%   |
| Kingston RAM 99U5471-012.A00LF 4GB DIMM DDR3 1333MT/s                   | 2        | 0.73%   |
| Kingston RAM 202020202020202020202020202020202020 2GB DIMM DDR2 800MT/s | 2        | 0.73%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3200MT/s                    | 2        | 0.73%   |
| Corsair RAM CMK32GX4M2A2400C16 16GB DIMM DDR4 2400MT/s                  | 2        | 0.73%   |
| Unknown RAM Module 8GB DIMM DDR4 2667MT/s                               | 1        | 0.36%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                                    | 1        | 0.36%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                             | 1        | 0.36%   |
| Unknown RAM Module 2GB DIMM DDR3 1600MT/s                               | 1        | 0.36%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                               | 1        | 0.36%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                                | 1        | 0.36%   |
| Unknown RAM Module 2GB DIMM DDR 667MT/s                                 | 1        | 0.36%   |
| Unknown RAM Module 2GB DIMM 400MT/s                                     | 1        | 0.36%   |
| Unknown RAM Module 2GB DIMM 1066MT/s                                    | 1        | 0.36%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s                                | 1        | 0.36%   |
| Unknown RAM Module 1GB DIMM DDR2                                        | 1        | 0.36%   |
| Unknown RAM Module 1GB DIMM DDR 667MT/s                                 | 1        | 0.36%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 95       | 45.24%  |
| DDR3    | 76       | 36.19%  |
| Unknown | 17       | 8.1%    |
| DDR2    | 14       | 6.67%   |
| SDRAM   | 3        | 1.43%   |
| LPDDR4  | 2        | 0.95%   |
| DDR     | 2        | 0.95%   |
| DDR5    | 1        | 0.48%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 179      | 85.65%  |
| SODIMM | 30       | 14.35%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 94       | 39.66%  |
| 4096  | 62       | 26.16%  |
| 2048  | 38       | 16.03%  |
| 16384 | 26       | 10.97%  |
| 1024  | 14       | 5.91%   |
| 32768 | 3        | 1.27%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 44       | 19.64%  |
| 1333    | 41       | 18.3%   |
| 3200    | 24       | 10.71%  |
| 2133    | 22       | 9.82%   |
| 2400    | 20       | 8.93%   |
| 2667    | 18       | 8.04%   |
| 800     | 12       | 5.36%   |
| 667     | 7        | 3.13%   |
| 3600    | 6        | 2.68%   |
| 1067    | 5        | 2.23%   |
| 1066    | 4        | 1.79%   |
| 3000    | 3        | 1.34%   |
| 2666    | 3        | 1.34%   |
| Unknown | 3        | 1.34%   |
| 1867    | 2        | 0.89%   |
| 400     | 2        | 0.89%   |
| 6400    | 1        | 0.45%   |
| 4400    | 1        | 0.45%   |
| 4000    | 1        | 0.45%   |
| 3333    | 1        | 0.45%   |
| 2933    | 1        | 0.45%   |
| 1639    | 1        | 0.45%   |
| 1200    | 1        | 0.45%   |
| 533     | 1        | 0.45%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor             | Desktops | Percent |
|--------------------|----------|---------|
| Brother Industries | 3        | 75%     |
| Hewlett-Packard    | 1        | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                      | Desktops | Percent |
|----------------------------|----------|---------|
| HP LaserJet 3390           | 1        | 25%     |
| Brother HL-L3270CDW series | 1        | 25%     |
| Brother HL-L2300D series   | 1        | 25%     |
| Brother DCP-J152W          | 1        | 25%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart_bsd/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 2        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart_bsd/scanner_model.svg)


| Model                    | Desktops | Percent |
|--------------------------|----------|---------|
| Canon CanoScan LiDE 700F | 1        | 50%     |
| Canon CanoScan LiDE 120  | 1        | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 6        | 35.29%  |
| Microdia                      | 3        | 17.65%  |
| Trust                         | 1        | 5.88%   |
| Sunplus Innovation Technology | 1        | 5.88%   |
| SHENZHEN AONI ELECTRONIC      | 1        | 5.88%   |
| Importek                      | 1        | 5.88%   |
| IMC Networks                  | 1        | 5.88%   |
| Genesys Logic                 | 1        | 5.88%   |
| GEMBIRD                       | 1        | 5.88%   |
| Chicony Electronics           | 1        | 5.88%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Logitech Webcam C270                              | 3        | 17.65%  |
| Microdia USB 2.0 Camera                           | 2        | 11.76%  |
| Trust Trust Full HD Webcam                        | 1        | 5.88%   |
| Sunplus Integrated_Webcam_HD                      | 1        | 5.88%   |
| SHENZHEN AONI ELECTRONIC NexiGo N990 4K Camera    | 1        | 5.88%   |
| Microdia Webcam Vitade AF                         | 1        | 5.88%   |
| Logitech Webcam C170                              | 1        | 5.88%   |
| Logitech HD Pro Webcam C920                       | 1        | 5.88%   |
| Logitech BRIO Ultra HD Webcam                     | 1        | 5.88%   |
| Importek FJ Camera                                | 1        | 5.88%   |
| IMC Networks XHC Camera                           | 1        | 5.88%   |
| Genesys Logic Digital Microscope                  | 1        | 5.88%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 1        | 5.88%   |
| Chicony HP 2.0MP High Definition Webcam           | 1        | 5.88%   |

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
| 1     | 103      | 48.36%  |
| 0     | 69       | 32.39%  |
| 2     | 35       | 16.43%  |
| 3     | 4        | 1.88%   |
| 4     | 2        | 0.94%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 129      | 72.47%  |
| Net/wireless             | 21       | 11.8%   |
| Sound                    | 14       | 7.87%   |
| Bluetooth                | 5        | 2.81%   |
| Net/ethernet             | 3        | 1.69%   |
| Card reader              | 3        | 1.69%   |
| Storage/raid             | 1        | 0.56%   |
| Network                  | 1        | 0.56%   |
| Dvb card                 | 1        | 0.56%   |

