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

Total: 237

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
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
| amd64 | 198      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| helloDesktop | 197      | 99.49%  |
| GNOME        | 1        | 0.51%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| X11  | 198      | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Desktops | Percent |
|------|----------|---------|
| SLiM | 198      | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 80       | 40%     |
| fr_FR   | 56       | 28%     |
| ru_RU   | 15       | 7.5%    |
| de_DE   | 11       | 5.5%    |
| es_ES   | 10       | 5%      |
| Unknown | 10       | 5%      |
| pt_BR   | 7        | 3.5%    |
| it_IT   | 5        | 2.5%    |
| pl_PL   | 2        | 1%      |
| jp_JP   | 2        | 1%      |
| fr      | 1        | 0.5%    |
| es      | 1        | 0.5%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 194      | 97.98%  |
| BIOS | 4        | 2.02%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Desktops | Percent |
|--------|----------|---------|
| Cd9660 | 114      | 55.88%  |
| Zfs    | 90       | 44.12%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Desktops | Percent |
|------|----------|---------|
| GPT  | 194      | 97.98%  |
| MBR  | 4        | 2.02%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 48       | 24.24%  |
| Gigabyte Technology | 31       | 15.66%  |
| Hewlett-Packard     | 23       | 11.62%  |
| Dell                | 17       | 8.59%   |
| MSI                 | 15       | 7.58%   |
| Lenovo              | 13       | 6.57%   |
| ASRock              | 10       | 5.05%   |
| Intel               | 8        | 4.04%   |
| Unknown             | 6        | 3.03%   |
| Fujitsu             | 4        | 2.02%   |
| Acer                | 4        | 2.02%   |
| T-bao               | 2        | 1.01%   |
| Fujitsu Siemens     | 2        | 1.01%   |
| Foxconn             | 2        | 1.01%   |
| AZW                 | 2        | 1.01%   |
| Shuttle             | 1        | 0.51%   |
| Pegatron            | 1        | 0.51%   |
| LG Electronics      | 1        | 0.51%   |
| Huanan              | 1        | 0.51%   |
| Google              | 1        | 0.51%   |
| ECS                 | 1        | 0.51%   |
| Daten Tecnologia    | 1        | 0.51%   |
| Biostar             | 1        | 0.51%   |
| BESSTAR Tech        | 1        | 0.51%   |
| Axiomtek            | 1        | 0.51%   |
| Apple               | 1        | 0.51%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                   | Desktops | Percent |
|----------------------------------------|----------|---------|
| Unknown                                | 6        | 3.03%   |
| ASUS All Series                        | 4        | 2.02%   |
| ASUS PRIME B250M-A                     | 3        | 1.52%   |
| T-bao MINI PC                          | 2        | 1.01%   |
| MSI MS-7788                            | 2        | 1.01%   |
| Intel H81                              | 2        | 1.01%   |
| HP EliteDesk 800 G2 DM 35W             | 2        | 1.01%   |
| HP Compaq Elite 8300 USDT              | 2        | 1.01%   |
| Dell OptiPlex 7010                     | 2        | 1.01%   |
| Dell OptiPlex 3020                     | 2        | 1.01%   |
| ASUS ROG STRIX B550-F GAMING           | 2        | 1.01%   |
| Shuttle NC10U                          | 1        | 0.51%   |
| Pegatron Compaq dx2450 Microtower      | 1        | 0.51%   |
| MSI MS-7D30                            | 1        | 0.51%   |
| MSI MS-7C95                            | 1        | 0.51%   |
| MSI MS-7C83                            | 1        | 0.51%   |
| MSI MS-7C51                            | 1        | 0.51%   |
| MSI MS-7C37                            | 1        | 0.51%   |
| MSI MS-7C09                            | 1        | 0.51%   |
| MSI MS-7B98                            | 1        | 0.51%   |
| MSI MS-7B86                            | 1        | 0.51%   |
| MSI MS-7B17                            | 1        | 0.51%   |
| MSI MS-7A71                            | 1        | 0.51%   |
| MSI MS-7996                            | 1        | 0.51%   |
| MSI MS-7599                            | 1        | 0.51%   |
| MSI Compaq dx2200 MT                   | 1        | 0.51%   |
| LG R590-K.AAA9BT                       | 1        | 0.51%   |
| Lenovo ThinkCentre M93p 10A8S0J30R     | 1        | 0.51%   |
| Lenovo ThinkCentre M900 10FLS15P00     | 1        | 0.51%   |
| Lenovo ThinkCentre M900 10FGS05C08     | 1        | 0.51%   |
| Lenovo ThinkCentre M81 5049D7G         | 1        | 0.51%   |
| Lenovo ThinkCentre M75e 5065A11        | 1        | 0.51%   |
| Lenovo ThinkCentre M73 10AYA06EIA      | 1        | 0.51%   |
| Lenovo ThinkCentre M73 10AXS34800      | 1        | 0.51%   |
| Lenovo ThinkCentre M715q 10M2S02Q00    | 1        | 0.51%   |
| Lenovo ThinkCentre M710s 10M8S0FW00    | 1        | 0.51%   |
| Lenovo ThinkCentre M70e 0828W17        | 1        | 0.51%   |
| Lenovo ThinkCentre M58p 6138DK1        | 1        | 0.51%   |
| Lenovo ThinkCentre Edge72 34971B1      | 1        | 0.51%   |
| Lenovo IdeaCentre 510S-07ICB Type 90K8 | 1        | 0.51%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                    | Desktops | Percent |
|-------------------------|----------|---------|
| ASUS PRIME              | 14       | 7.07%   |
| Lenovo ThinkCentre      | 12       | 6.06%   |
| Dell OptiPlex           | 10       | 5.05%   |
| ASUS ROG                | 8        | 4.04%   |
| HP Compaq               | 7        | 3.54%   |
| Unknown                 | 6        | 3.03%   |
| HP EliteDesk            | 5        | 2.53%   |
| HP ProDesk              | 4        | 2.02%   |
| Gigabyte B450M          | 4        | 2.02%   |
| ASUS All                | 4        | 2.02%   |
| Dell Precision          | 3        | 1.52%   |
| ASUS TUF                | 3        | 1.52%   |
| T-bao MINI              | 2        | 1.01%   |
| MSI MS-7788             | 2        | 1.01%   |
| Intel H81               | 2        | 1.01%   |
| Gigabyte B550           | 2        | 1.01%   |
| Fujitsu Siemens ESPRIMO | 2        | 1.01%   |
| Fujitsu ESPRIMO         | 2        | 1.01%   |
| Dell Vostro             | 2        | 1.01%   |
| Dell Inspiron           | 2        | 1.01%   |
| Acer Veriton            | 2        | 1.01%   |
| Shuttle NC10U           | 1        | 0.51%   |
| Pegatron Compaq         | 1        | 0.51%   |
| MSI MS-7D30             | 1        | 0.51%   |
| MSI MS-7C95             | 1        | 0.51%   |
| MSI MS-7C83             | 1        | 0.51%   |
| MSI MS-7C51             | 1        | 0.51%   |
| MSI MS-7C37             | 1        | 0.51%   |
| MSI MS-7C09             | 1        | 0.51%   |
| MSI MS-7B98             | 1        | 0.51%   |
| MSI MS-7B86             | 1        | 0.51%   |
| MSI MS-7B17             | 1        | 0.51%   |
| MSI MS-7A71             | 1        | 0.51%   |
| MSI MS-7996             | 1        | 0.51%   |
| MSI MS-7599             | 1        | 0.51%   |
| MSI Compaq              | 1        | 0.51%   |
| LG R590-K.AAA9BT        | 1        | 0.51%   |
| Lenovo IdeaCentre       | 1        | 0.51%   |
| Intel X99               | 1        | 0.51%   |
| Intel STK1AW32SC        | 1        | 0.51%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2021    | 19       | 9.6%    |
| 2020    | 19       | 9.6%    |
| 2022    | 18       | 9.09%   |
| 2019    | 16       | 8.08%   |
| 2013    | 16       | 8.08%   |
| 2012    | 15       | 7.58%   |
| 2018    | 13       | 6.57%   |
| 2014    | 12       | 6.06%   |
| 2010    | 12       | 6.06%   |
| 2011    | 11       | 5.56%   |
| 2017    | 10       | 5.05%   |
| 2016    | 8        | 4.04%   |
| 2015    | 7        | 3.54%   |
| 2023    | 6        | 3.03%   |
| 2008    | 6        | 3.03%   |
| 2009    | 5        | 2.53%   |
| 2007    | 2        | 1.01%   |
| 2006    | 2        | 1.01%   |
| Unknown | 1        | 0.51%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 198      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 197      | 99.49%  |
| Yes  | 1        | 0.51%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 8.01-16.0   | 71       | 35.86%  |
| 16.01-24.0  | 59       | 29.8%   |
| 4.01-8.0    | 33       | 16.67%  |
| 32.01-64.0  | 20       | 10.1%   |
| 2.01-3.0    | 5        | 2.53%   |
| 64.01-256.0 | 5        | 2.53%   |
| 24.01-32.0  | 3        | 1.52%   |
| 3.01-4.0    | 1        | 0.51%   |
| 0.51-1.0    | 1        | 0.51%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Desktops | Percent |
|----------|----------|---------|
| 0.01-0.5 | 92       | 46%     |
| 0.51-1.0 | 71       | 35.5%   |
| 1.01-2.0 | 25       | 12.5%   |
| 2.01-3.0 | 10       | 5%      |
| 3.01-4.0 | 2        | 1%      |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 94       | 47.47%  |
| 2      | 43       | 21.72%  |
| 3      | 27       | 13.64%  |
| 0      | 13       | 6.57%   |
| 5      | 9        | 4.55%   |
| 4      | 6        | 3.03%   |
| 9      | 2        | 1.01%   |
| 6      | 2        | 1.01%   |
| 13     | 1        | 0.51%   |
| 7      | 1        | 0.51%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 126      | 63.64%  |
| Yes       | 72       | 36.36%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 192      | 96.97%  |
| No        | 6        | 3.03%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 135      | 67.84%  |
| Yes       | 64       | 32.16%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 147      | 74.24%  |
| Yes       | 51       | 25.76%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country            | Desktops | Percent |
|--------------------|----------|---------|
| USA                | 29       | 14.65%  |
| Russia             | 29       | 14.65%  |
| Germany            | 11       | 5.56%   |
| Brazil             | 11       | 5.56%   |
| Spain              | 10       | 5.05%   |
| France             | 8        | 4.04%   |
| Italy              | 7        | 3.54%   |
| Canada             | 7        | 3.54%   |
| Serbia             | 6        | 3.03%   |
| Hungary            | 6        | 3.03%   |
| Romania            | 5        | 2.53%   |
| Poland             | 5        | 2.53%   |
| Belgium            | 5        | 2.53%   |
| Australia          | 5        | 2.53%   |
| UK                 | 4        | 2.02%   |
| Ukraine            | 3        | 1.52%   |
| Turkey             | 3        | 1.52%   |
| Peru               | 3        | 1.52%   |
| Mexico             | 3        | 1.52%   |
| Japan              | 3        | 1.52%   |
| India              | 3        | 1.52%   |
| Bulgaria           | 3        | 1.52%   |
| Sweden             | 2        | 1.01%   |
| Netherlands        | 2        | 1.01%   |
| Indonesia          | 2        | 1.01%   |
| China              | 2        | 1.01%   |
| Argentina          | 2        | 1.01%   |
| Venezuela          | 1        | 0.51%   |
| Switzerland        | 1        | 0.51%   |
| South Korea        | 1        | 0.51%   |
| Slovenia           | 1        | 0.51%   |
| San Marino         | 1        | 0.51%   |
| Portugal           | 1        | 0.51%   |
| Panama             | 1        | 0.51%   |
| Kyrgyzstan         | 1        | 0.51%   |
| Kazakhstan         | 1        | 0.51%   |
| Israel             | 1        | 0.51%   |
| French Guiana      | 1        | 0.51%   |
| Estonia            | 1        | 0.51%   |
| Dominican Republic | 1        | 0.51%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| St Petersburg     | 4        | 1.99%   |
| Moscow            | 4        | 1.99%   |
| St. Jean Baptiste | 3        | 1.49%   |
| Belgrade          | 3        | 1.49%   |
| Sydney            | 2        | 1%      |
| Sofia             | 2        | 1%      |
| Sao Paulo         | 2        | 1%      |
| Penza             | 2        | 1%      |
| Paris             | 2        | 1%      |
| Novosibirsk       | 2        | 1%      |
| New York          | 2        | 1%      |
| Melbourne         | 2        | 1%      |
| Madrid            | 2        | 1%      |
| Kochi             | 2        | 1%      |
| Kirov             | 2        | 1%      |
| Curitiba          | 2        | 1%      |
| Brooklyn          | 2        | 1%      |
| Berlin            | 2        | 1%      |
| Bandung           | 2        | 1%      |
| Zurich            | 1        | 0.5%    |
| Zhengzhou         | 1        | 0.5%    |
| Yokohama          | 1        | 0.5%    |
| Woodbridge        | 1        | 0.5%    |
| Winnipeg          | 1        | 0.5%    |
| Warsaw            | 1        | 0.5%    |
| Volgodonsk        | 1        | 0.5%    |
| Vogogna           | 1        | 0.5%    |
| Vladimir          | 1        | 0.5%    |
| Virovitica        | 1        | 0.5%    |
| Villena           | 1        | 0.5%    |
| Vienna            | 1        | 0.5%    |
| Venice            | 1        | 0.5%    |
| Vecses            | 1        | 0.5%    |
| Valga             | 1        | 0.5%    |
| Valderrobres      | 1        | 0.5%    |
| Ubstadt-Weiher    | 1        | 0.5%    |
| Tucson            | 1        | 0.5%    |
| Trumbull          | 1        | 0.5%    |
| Trieste           | 1        | 0.5%    |
| Trekhgornyy       | 1        | 0.5%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 55       | 92     | 17.68%  |
| Seagate             | 48       | 72     | 15.43%  |
| Samsung Electronics | 43       | 61     | 13.83%  |
| Kingston            | 30       | 31     | 9.65%   |
| Toshiba             | 17       | 23     | 5.47%   |
| Crucial             | 11       | 13     | 3.54%   |
| A-DATA Technology   | 11       | 12     | 3.54%   |
| SanDisk             | 10       | 10     | 3.22%   |
| Hitachi             | 7        | 8      | 2.25%   |
| China               | 7        | 8      | 2.25%   |
| Transcend           | 6        | 6      | 1.93%   |
| Patriot             | 5        | 5      | 1.61%   |
| Micron Technology   | 5        | 6      | 1.61%   |
| Intel               | 5        | 5      | 1.61%   |
| Maxtor              | 4        | 4      | 1.29%   |
| KingSpec            | 4        | 4      | 1.29%   |
| SPCC                | 3        | 3      | 0.96%   |
| Team                | 2        | 2      | 0.64%   |
| PNY                 | 2        | 2      | 0.64%   |
| Netac               | 2        | 2      | 0.64%   |
| Gigabyte Technology | 2        | 3      | 0.64%   |
| Apacer              | 2        | 2      | 0.64%   |
| AMD                 | 2        | 2      | 0.64%   |
| WALRAM              | 1        | 1      | 0.32%   |
| Vaseky              | 1        | 1      | 0.32%   |
| TAMMUZ              | 1        | 1      | 0.32%   |
| SUNEAST             | 1        | 1      | 0.32%   |
| SK hynix            | 1        | 1      | 0.32%   |
| Silicon Motion      | 1        | 1      | 0.32%   |
| SETHRISE            | 1        | 1      | 0.32%   |
| RX7                 | 1        | 1      | 0.32%   |
| QUANTUM             | 1        | 1      | 0.32%   |
| Pioneer             | 1        | 1      | 0.32%   |
| Philips             | 1        | 1      | 0.32%   |
| Palit               | 1        | 1      | 0.32%   |
| OCZ                 | 1        | 1      | 0.32%   |
| LITEONIT            | 1        | 1      | 0.32%   |
| Kston               | 1        | 1      | 0.32%   |
| KIOXIA-EXCERIA      | 1        | 1      | 0.32%   |
| KIOXIA              | 1        | 1      | 0.32%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                           | Desktops | Percent |
|---------------------------------|----------|---------|
| Kingston SA400S37240G 240GB     | 8        | 2.16%   |
| Seagate ST500DM002-1BD142 500GB | 6        | 1.62%   |
| Seagate ST3500418AS 500GB       | 5        | 1.35%   |
| Samsung SSD 860 EVO 500GB       | 5        | 1.35%   |
| Seagate ST1000DM010-2EP102 1TB  | 4        | 1.08%   |
| Samsung SSD 870 EVO 500GB       | 4        | 1.08%   |
| Samsung SSD 850 EVO 250GB       | 4        | 1.08%   |
| Kingston SA400S37120G 120GB     | 4        | 1.08%   |
| WDC WD20EFRX-68EUZN0 2TB        | 3        | 0.81%   |
| WDC WD10EZEX-60WN4A0 1TB        | 3        | 0.81%   |
| WDC WD10EZEX-08WN4A0 1TB        | 3        | 0.81%   |
| Toshiba HDWD110 1TB             | 3        | 0.81%   |
| Seagate ST2000DM008-2FR102 2TB  | 3        | 0.81%   |
| Samsung SSD 980 1TB             | 3        | 0.81%   |
| Samsung SSD 970 EVO Plus 500GB  | 3        | 0.81%   |
| Crucial CT500MX500SSD1 500GB    | 3        | 0.81%   |
| Crucial CT240BX500SSD1 240GB    | 3        | 0.81%   |
| A-DATA SU650 120GB              | 3        | 0.81%   |
| WDC WDS500G2B0A-00SM50 500GB    | 2        | 0.54%   |
| WDC WDS240G2G0A-00JH30 240GB    | 2        | 0.54%   |
| WDC WDS120G2G0A-00JH30 120GB    | 2        | 0.54%   |
| WDC WD5000AAKX-08U6AA0 500GB    | 2        | 0.54%   |
| WDC WD20EZRX-00D8PB0 2TB        | 2        | 0.54%   |
| WDC WD10EZEX-60WN4A1 1TB        | 2        | 0.54%   |
| Toshiba DT01ACA100 1TB          | 2        | 0.54%   |
| Toshiba DT01ACA050 500GB        | 2        | 0.54%   |
| SPCC Solid State Disk 128GB     | 2        | 0.54%   |
| Seagate ST3500312CS 500GB       | 2        | 0.54%   |
| Seagate ST250DM000-1BD141 250GB | 2        | 0.54%   |
| Seagate ST1000DM003-1CH162 1TB  | 2        | 0.54%   |
| SanDisk pSSD 16GB               | 2        | 0.54%   |
| Samsung SSD 980 PRO 500GB       | 2        | 0.54%   |
| Samsung SSD 970 PRO 512GB       | 2        | 0.54%   |
| Samsung SSD 970 EVO Plus 1TB    | 2        | 0.54%   |
| Samsung SSD 860 EVO 250GB       | 2        | 0.54%   |
| Samsung HD103SJ 1TB             | 2        | 0.54%   |
| Patriot Burst Elite 120GB       | 2        | 0.54%   |
| Kingston SHFS37A240G 240GB      | 2        | 0.54%   |
| Kingston SA400S37480G 480GB     | 2        | 0.54%   |
| Crucial CT1000P3SSD8 1TB        | 2        | 0.54%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 47       | 78     | 36.72%  |
| Seagate             | 47       | 71     | 36.72%  |
| Toshiba             | 14       | 18     | 10.94%  |
| Hitachi             | 7        | 8      | 5.47%   |
| Samsung Electronics | 6        | 8      | 4.69%   |
| Maxtor              | 4        | 4      | 3.13%   |
| QUANTUM             | 1        | 1      | 0.78%   |
| HGST                | 1        | 1      | 0.78%   |
| Apple               | 1        | 1      | 0.78%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 23       | 30     | 16.91%  |
| Kingston            | 21       | 22     | 15.44%  |
| WDC                 | 10       | 10     | 7.35%   |
| SanDisk             | 10       | 10     | 7.35%   |
| Crucial             | 9        | 10     | 6.62%   |
| China               | 7        | 8      | 5.15%   |
| A-DATA Technology   | 7        | 7      | 5.15%   |
| Transcend           | 5        | 5      | 3.68%   |
| Patriot             | 4        | 4      | 2.94%   |
| KingSpec            | 4        | 4      | 2.94%   |
| Toshiba             | 3        | 5      | 2.21%   |
| Intel               | 3        | 3      | 2.21%   |
| SPCC                | 2        | 2      | 1.47%   |
| PNY                 | 2        | 2      | 1.47%   |
| Micron Technology   | 2        | 2      | 1.47%   |
| Apacer              | 2        | 2      | 1.47%   |
| WALRAM              | 1        | 1      | 0.74%   |
| Vaseky              | 1        | 1      | 0.74%   |
| Team                | 1        | 1      | 0.74%   |
| TAMMUZ              | 1        | 1      | 0.74%   |
| SUNEAST             | 1        | 1      | 0.74%   |
| SETHRISE            | 1        | 1      | 0.74%   |
| RX7                 | 1        | 1      | 0.74%   |
| Pioneer             | 1        | 1      | 0.74%   |
| Philips             | 1        | 1      | 0.74%   |
| Palit               | 1        | 1      | 0.74%   |
| OCZ                 | 1        | 1      | 0.74%   |
| LITEONIT            | 1        | 1      | 0.74%   |
| Kston               | 1        | 1      | 0.74%   |
| KIOXIA-EXCERIA      | 1        | 1      | 0.74%   |
| Intenso             | 1        | 1      | 0.74%   |
| HEORIADY            | 1        | 1      | 0.74%   |
| GOODRAM             | 1        | 1      | 0.74%   |
| Gigabyte Technology | 1        | 2      | 0.74%   |
| EDGE                | 1        | 1      | 0.74%   |
| Azerty              | 1        | 1      | 0.74%   |
| AMD                 | 1        | 1      | 0.74%   |
| addlink             | 1        | 1      | 0.74%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 108      | 190    | 40%     |
| SSD  | 107      | 149    | 39.63%  |
| NVMe | 55       | 65     | 20.37%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 175      | 339    | 76.09%  |
| NVMe | 55       | 65     | 23.91%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 148      | 214    | 65.49%  |
| 0.51-1.0   | 45       | 56     | 19.91%  |
| 1.01-2.0   | 19       | 39     | 8.41%   |
| 3.01-4.0   | 8        | 12     | 3.54%   |
| 4.01-10.0  | 3        | 12     | 1.33%   |
| 2.01-3.0   | 2        | 5      | 0.88%   |
| 10.01-20.0 | 1        | 1      | 0.44%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| 1-20       | 108      | 53.2%   |
| 101-250    | 28       | 13.79%  |
| 251-500    | 27       | 13.3%   |
| 51-100     | 24       | 11.82%  |
| 501-1000   | 9        | 4.43%   |
| 21-50      | 5        | 2.46%   |
| 1001-2000  | 1        | 0.49%   |
| Unknown    | 1        | 0.49%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Desktops | Percent |
|---------|----------|---------|
| 1-20    | 194      | 97.98%  |
| 251-500 | 1        | 0.51%   |
| 21-50   | 1        | 0.51%   |
| 101-250 | 1        | 0.51%   |
| Unknown | 1        | 0.51%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                      | Desktops | Drives | Percent |
|--------------------------------------------|----------|--------|---------|
| Seagate ST3500418AS 500GB                  | 2        | 2      | 3.7%    |
| WDC WD800JD-75MSA3 80GB                    | 1        | 1      | 1.85%   |
| WDC WD6400BPVT-22HXZT3 640GB               | 1        | 1      | 1.85%   |
| WDC WD5000AAKX-08U6AA0 500GB               | 1        | 1      | 1.85%   |
| WDC WD5000AAKX-00ERMA0 500GB               | 1        | 1      | 1.85%   |
| WDC WD30EFRX-68EUZN0 3TB                   | 1        | 1      | 1.85%   |
| WDC WD20EZRX-00D8PB0 2TB                   | 1        | 1      | 1.85%   |
| WDC WD20EARS-00MVWB0 2TB                   | 1        | 1      | 1.85%   |
| WDC WD20EADS-00W4B0 2TB                    | 1        | 1      | 1.85%   |
| WDC WD1600YS-01SHB1 164GB                  | 1        | 1      | 1.85%   |
| WDC WD1600AAJS-60Z0A0 160GB                | 1        | 1      | 1.85%   |
| WDC WD10EZEX-60WN4A0 1TB                   | 1        | 1      | 1.85%   |
| WDC WD10EZEX-60M2NA0 1TB                   | 1        | 1      | 1.85%   |
| WDC WD10EARS-00MVWB0 1TB                   | 1        | 1      | 1.85%   |
| WDC WD10EARS-003BB1 1TB                    | 1        | 1      | 1.85%   |
| WDC WD10EADS-11M2B2 1TB                    | 1        | 1      | 1.85%   |
| Transcend TS120GSSD220S 120GB              | 1        | 1      | 1.85%   |
| Toshiba MK8052GSX 80GB                     | 1        | 1      | 1.85%   |
| Toshiba MK3259GSXP 320GB                   | 1        | 1      | 1.85%   |
| Toshiba DT01ACA100 1TB                     | 1        | 1      | 1.85%   |
| Toshiba DT01ABA200 2TB                     | 1        | 1      | 1.85%   |
| Silicon Motion Asgard AN1TNVMe-M.2-80 1TB  | 1        | 1      | 1.85%   |
| Seagate ST500LM000-1EJ162 500GB            | 1        | 1      | 1.85%   |
| Seagate ST500DM002-1BD142 500GB            | 1        | 1      | 1.85%   |
| Seagate ST380215AS 80GB                    | 1        | 1      | 1.85%   |
| Seagate ST3750528AS 752GB                  | 1        | 1      | 1.85%   |
| Seagate ST3500320AS 500GB                  | 1        | 1      | 1.85%   |
| Seagate ST3360320AS 360GB                  | 1        | 1      | 1.85%   |
| Seagate ST3320620AS 320GB                  | 1        | 1      | 1.85%   |
| Seagate ST3320418AS 320GB                  | 1        | 1      | 1.85%   |
| Seagate ST3250312AS 250GB                  | 1        | 2      | 1.85%   |
| Seagate ST250DM000-1BD141 250GB            | 1        | 1      | 1.85%   |
| Seagate ST2000DM008-2FR102 2TB             | 1        | 1      | 1.85%   |
| Seagate ST1000DM010-2EP102 1TB             | 1        | 1      | 1.85%   |
| Samsung Electronics SSD 860 EVO 500GB      | 1        | 1      | 1.85%   |
| Samsung Electronics MZVL22T0HBLB-00B00 2TB | 1        | 1      | 1.85%   |
| Samsung Electronics HD322HJ 320GB          | 1        | 1      | 1.85%   |
| Samsung Electronics HD161GJ 160GB          | 1        | 1      | 1.85%   |
| Samsung Electronics HD160JJ 160GB          | 1        | 1      | 1.85%   |
| Samsung Electronics HD103SJ 1TB            | 1        | 1      | 1.85%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 14       | 15     | 28%     |
| Seagate             | 12       | 15     | 24%     |
| Samsung Electronics | 5        | 6      | 10%     |
| Toshiba             | 4        | 4      | 8%      |
| Maxtor              | 3        | 3      | 6%      |
| Hitachi             | 3        | 3      | 6%      |
| Transcend           | 1        | 1      | 2%      |
| Silicon Motion      | 1        | 1      | 2%      |
| Micron Technology   | 1        | 1      | 2%      |
| Kingston            | 1        | 1      | 2%      |
| Intel               | 1        | 1      | 2%      |
| HGST                | 1        | 1      | 2%      |
| Crucial             | 1        | 1      | 2%      |
| China               | 1        | 1      | 2%      |
| A-DATA Technology   | 1        | 1      | 2%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 14       | 15     | 35%     |
| Seagate             | 12       | 15     | 30%     |
| Toshiba             | 4        | 4      | 10%     |
| Samsung Electronics | 3        | 4      | 7.5%    |
| Maxtor              | 3        | 3      | 7.5%    |
| Hitachi             | 3        | 3      | 7.5%    |
| HGST                | 1        | 1      | 2.5%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 40       | 45     | 80%     |
| SSD  | 7        | 7      | 14%     |
| NVMe | 3        | 3      | 6%      |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                           | Desktops | Drives | Percent |
|---------------------------------|----------|--------|---------|
| WDC WD7501AALS-00J7B0 752GB     | 1        | 1      | 25%     |
| WDC WD1600BEVT-22ZCT0 160GB     | 1        | 1      | 25%     |
| SanDisk pSSD 16GB               | 1        | 1      | 25%     |
| Samsung Electronics HD103SJ 1TB | 1        | 1      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 2        | 2      | 50%     |
| SanDisk             | 1        | 1      | 25%     |
| Samsung Electronics | 1        | 1      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 150      | 329    | 70.42%  |
| Malfunc  | 49       | 55     | 23%     |
| Detected | 10       | 16     | 4.69%   |
| Failed   | 4        | 4      | 1.88%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Desktops | Percent |
|-----------------------------|----------|---------|
| Intel                       | 143      | 52%     |
| AMD                         | 48       | 17.45%  |
| Samsung Electronics         | 19       | 6.91%   |
| Kingston Technology Company | 9        | 3.27%   |
| ASMedia Technology          | 9        | 3.27%   |
| Silicon Motion              | 8        | 2.91%   |
| Marvell Technology Group    | 7        | 2.55%   |
| SanDisk                     | 5        | 1.82%   |
| Nvidia                      | 4        | 1.45%   |
| Micron/Crucial Technology   | 3        | 1.09%   |
| Micron Technology           | 3        | 1.09%   |
| JMicron Technology          | 3        | 1.09%   |
| VIA Technologies            | 2        | 0.73%   |
| Realtek Semiconductor       | 2        | 0.73%   |
| Phison Electronics          | 2        | 0.73%   |
| ADATA Technology            | 2        | 0.73%   |
| SK hynix                    | 1        | 0.36%   |
| Seagate Technology          | 1        | 0.36%   |
| OCZ Technology Group        | 1        | 0.36%   |
| MAXIO Technology (Hangzhou) | 1        | 0.36%   |
| KIOXIA                      | 1        | 0.36%   |
| Broadcom / LSI              | 1        | 0.36%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 22       | 6.51%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 22       | 6.51%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 16       | 4.73%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 14       | 4.14%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 13       | 3.85%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 11       | 3.25%   |
| AMD 400 Series Chipset SATA Controller                                                  | 11       | 3.25%   |
| AMD 500 Series Chipset SATA Controller                                                  | 10       | 2.96%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 9        | 2.66%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 8        | 2.37%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 8        | 2.37%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 8        | 2.37%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 7        | 2.07%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 7        | 2.07%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 6        | 1.78%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 6        | 1.78%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 5        | 1.48%   |
| Intel SATA Controller [RAID mode]                                                       | 5        | 1.48%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 5        | 1.48%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 5        | 1.48%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 5        | 1.48%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 4        | 1.18%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4        | 1.18%   |
| Nvidia MCP61 SATA Controller                                                            | 3        | 0.89%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 3        | 0.89%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 3        | 0.89%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 3        | 0.89%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 3        | 0.89%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 3        | 0.89%   |
| Intel 82801JD/DO (ICH10 Family) 4-port SATA IDE Controller                              | 3        | 0.89%   |
| Intel 82801JD/DO (ICH10 Family) 2-port SATA IDE Controller                              | 3        | 0.89%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 3        | 0.89%   |
| AMD 300 Series Chipset SATA Controller                                                  | 3        | 0.89%   |
| VIA VT6415 PATA IDE Host Controller                                                     | 2        | 0.59%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                               | 2        | 0.59%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2        | 0.59%   |
| Nvidia MCP61 IDE                                                                        | 2        | 0.59%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 2        | 0.59%   |
| Micron 2200S NVMe SSD [Cassandra]                                                       | 2        | 0.59%   |
| Marvell Group 88SE91A3 SATA-600 Controller                                              | 2        | 0.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 157      | 59.02%  |
| NVMe | 55       | 20.68%  |
| IDE  | 43       | 16.17%  |
| RAID | 9        | 3.38%   |
| SAS  | 1        | 0.38%   |
| SCSI | 1        | 0.38%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 146      | 73.74%  |
| AMD    | 52       | 26.26%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| Intel Core i5-6500 CPU @ 3.20GHz              | 7        | 3.54%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 4        | 2.02%   |
| Intel Core i5-7400 CPU @ 3.00GHz              | 4        | 2.02%   |
| Intel Core i3-7100 CPU @ 3.90GHz              | 4        | 2.02%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 4        | 2.02%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 4        | 2.02%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 3        | 1.52%   |
| Intel Core i3-9100 CPU @ 3.60GHz              | 3        | 1.52%   |
| Intel Core i3-4130 CPU @ 3.40GHz              | 3        | 1.52%   |
| Intel Core i3-3220 CPU @ 3.30GHz              | 3        | 1.52%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 3        | 1.52%   |
| Intel Core i7-8700K CPU @ 3.70GHz             | 2        | 1.01%   |
| Intel Core i7-8700 CPU @ 3.20GHz              | 2        | 1.01%   |
| Intel Core i7-6700 CPU @ 3.40GHz              | 2        | 1.01%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 2        | 1.01%   |
| Intel Core i5-6500T CPU @ 2.50GHz             | 2        | 1.01%   |
| Intel Core i5-4570 CPU @ 3.20GHz              | 2        | 1.01%   |
| Intel Core i5-4440 CPU @ 3.10GHz              | 2        | 1.01%   |
| Intel Core i3-6100 CPU @ 3.70GHz              | 2        | 1.01%   |
| Intel Core i3-4160 CPU @ 3.60GHz              | 2        | 1.01%   |
| Intel Core i3-3240 CPU @ 3.40GHz              | 2        | 1.01%   |
| Intel Core i3-2100 CPU @ 3.10GHz              | 2        | 1.01%   |
| Intel Core i3-10100 CPU @ 3.60GHz             | 2        | 1.01%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 2        | 1.01%   |
| Intel Celeron N5105 @ 2.00GHz                 | 2        | 1.01%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 2        | 1.01%   |
| Intel Celeron CPU J1900 @ 1.99GHz             | 2        | 1.01%   |
| Intel 12th Gen Core i5-12400                  | 2        | 1.01%   |
| AMD Ryzen 7 3750H with Radeon Vega Mobile Gfx | 2        | 1.01%   |
| AMD Ryzen 5 5600 6-Core Processor             | 2        | 1.01%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics   | 2        | 1.01%   |
| AMD Athlon II X2 250 Processor                | 2        | 1.01%   |
| Intel Xeon W-2125 CPU @ 4.00GHz               | 1        | 0.51%   |
| Intel Xeon CPU W3670 @ 3.20GHz                | 1        | 0.51%   |
| Intel Xeon CPU E5-2690 v4 @ 2.60GHz           | 1        | 0.51%   |
| Intel Xeon CPU E5-2678 v3 @ 2.50GHz           | 1        | 0.51%   |
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz           | 1        | 0.51%   |
| Intel Xeon CPU E5-2620 v3 @ 2.40GHz           | 1        | 0.51%   |
| Intel Xeon CPU E31220 @ 3.10GHz               | 1        | 0.51%   |
| Intel Xeon CPU E3-1270 v5 @ 3.60GHz           | 1        | 0.51%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 41       | 20.71%  |
| Intel Core i3           | 28       | 14.14%  |
| Intel Core i7           | 23       | 11.62%  |
| AMD Ryzen 5             | 17       | 8.59%   |
| Intel Celeron           | 13       | 6.57%   |
| Intel Xeon              | 11       | 5.56%   |
| Intel Core 2 Duo        | 9        | 4.55%   |
| Other                   | 7        | 3.54%   |
| AMD Ryzen 7             | 7        | 3.54%   |
| AMD Ryzen 3             | 6        | 3.03%   |
| Intel Pentium           | 4        | 2.02%   |
| AMD Athlon II X2        | 4        | 2.02%   |
| Intel Core 2 Quad       | 3        | 1.52%   |
| AMD Phenom II X4        | 3        | 1.52%   |
| Intel Pentium Dual-Core | 2        | 1.01%   |
| Intel Core i9           | 2        | 1.01%   |
| AMD A4                  | 2        | 1.01%   |
| Intel Pentium Gold      | 1        | 0.51%   |
| Intel Pentium 4         | 1        | 0.51%   |
| Intel Atom              | 1        | 0.51%   |
| AMD Ryzen 9             | 1        | 0.51%   |
| AMD Ryzen 3 PRO         | 1        | 0.51%   |
| AMD PRO A10             | 1        | 0.51%   |
| AMD Phenom II X6        | 1        | 0.51%   |
| AMD Phenom II X2        | 1        | 0.51%   |
| AMD GX                  | 1        | 0.51%   |
| AMD FX                  | 1        | 0.51%   |
| AMD E                   | 1        | 0.51%   |
| AMD Athlon X2           | 1        | 0.51%   |
| AMD Athlon II X4        | 1        | 0.51%   |
| AMD Athlon 64           | 1        | 0.51%   |
| AMD A6                  | 1        | 0.51%   |
| AMD A10                 | 1        | 0.51%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 86       | 43.43%  |
| 2       | 52       | 26.26%  |
| 6       | 19       | 9.6%    |
| 12      | 13       | 6.57%   |
| 8       | 10       | 5.05%   |
| 16      | 7        | 3.54%   |
| Unknown | 6        | 3.03%   |
| 1       | 2        | 1.01%   |
| 24      | 1        | 0.51%   |
| 14      | 1        | 0.51%   |
| 10      | 1        | 0.51%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 196      | 98.99%  |
| 2      | 2        | 1.01%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 1       | 122      | 61.62%  |
| 2       | 69       | 34.85%  |
| Unknown | 7        | 3.54%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Haswell       | 28       | 14.14%  |
| KabyLake      | 25       | 12.63%  |
| IvyBridge     | 18       | 9.09%   |
| Skylake       | 17       | 8.59%   |
| SandyBridge   | 14       | 7.07%   |
| Zen+          | 12       | 6.06%   |
| Penryn        | 12       | 6.06%   |
| Zen 3         | 11       | 5.56%   |
| K10           | 11       | 5.56%   |
| Unknown       | 9        | 4.55%   |
| Zen           | 7        | 3.54%   |
| CometLake     | 6        | 3.03%   |
| Piledriver    | 4        | 2.02%   |
| Core          | 4        | 2.02%   |
| Silvermont    | 3        | 1.52%   |
| Nehalem       | 3        | 1.52%   |
| Zen 2         | 2        | 1.01%   |
| Westmere      | 2        | 1.01%   |
| Goldmont plus | 2        | 1.01%   |
| NetBurst      | 1        | 0.51%   |
| K8 Hammer     | 1        | 0.51%   |
| Jaguar        | 1        | 0.51%   |
| Goldmont      | 1        | 0.51%   |
| Excavator     | 1        | 0.51%   |
| Bulldozer     | 1        | 0.51%   |
| Broadwell     | 1        | 0.51%   |
| Bobcat        | 1        | 0.51%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Intel                      | 90       | 42.25%  |
| AMD                        | 62       | 29.11%  |
| Nvidia                     | 60       | 28.17%  |
| Matrox Electronics Systems | 1        | 0.47%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 14       | 6.48%   |
| Intel HD Graphics 530                                                       | 12       | 5.56%   |
| Intel HD Graphics 630                                                       | 9        | 4.17%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 8        | 3.7%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 8        | 3.7%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 7        | 3.24%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 7        | 3.24%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 6        | 2.78%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 6        | 2.78%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 6        | 2.78%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 6        | 2.78%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 4        | 1.85%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 4        | 1.85%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 3        | 1.39%   |
| Nvidia GT218 [GeForce 210]                                                  | 3        | 1.39%   |
| Nvidia GK208B [GeForce GT 730]                                              | 3        | 1.39%   |
| Nvidia GK208B [GeForce GT 710]                                              | 3        | 1.39%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 3        | 1.39%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 3        | 1.39%   |
| AMD RS880 [Radeon HD 4250]                                                  | 3        | 1.39%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 3        | 1.39%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 2        | 0.93%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2        | 0.93%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 2        | 0.93%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 2        | 0.93%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 2        | 0.93%   |
| Nvidia GK104 [GeForce GTX 680]                                              | 2        | 0.93%   |
| Nvidia GF119 [GeForce GT 610]                                               | 2        | 0.93%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 2        | 0.93%   |
| Intel JasperLake [UHD Graphics]                                             | 2        | 0.93%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 2        | 0.93%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 2        | 0.93%   |
| Intel Alder Lake-S GT1 [UHD Graphics 730]                                   | 2        | 0.93%   |
| Intel 82Q35 Express Integrated Graphics Controller                          | 2        | 0.93%   |
| AMD Oland [Radeon HD 8570 / R5 430 OEM / R7 240/340 / Radeon 520 OEM]       | 2        | 0.93%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 2        | 0.93%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 2        | 0.93%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 1        | 0.46%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 1        | 0.46%   |
| Nvidia GT218M [GeForce 310M]                                                | 1        | 0.46%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| 1 x Intel                | 71       | 35.5%   |
| 1 x Nvidia               | 54       | 27%     |
| 1 x AMD                  | 51       | 25.5%   |
| Intel + AMD              | 9        | 4.5%    |
| 2 x Intel                | 6        | 3%      |
| Intel + Nvidia           | 4        | 2%      |
| Other                    | 1        | 0.5%    |
| 2 x AMD                  | 1        | 0.5%    |
| 1 x Matrox               | 1        | 0.5%    |
| Intel + AMD + 1 x Nvidia | 1        | 0.5%    |
| AMD + Nvidia             | 1        | 0.5%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 154      | 77.39%  |
| Proprietary | 40       | 20.1%   |
| Unknown     | 5        | 2.51%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 126      | 63%     |
| 3.01-4.0   | 18       | 9%      |
| 1.01-2.0   | 17       | 8.5%    |
| 0.51-1.0   | 12       | 6%      |
| 5.01-6.0   | 8        | 4%      |
| 0.01-0.5   | 8        | 4%      |
| 7.01-8.0   | 7        | 3.5%    |
| 2.01-3.0   | 2        | 1%      |
| 8.01-16.0  | 2        | 1%      |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 13       | 13.54%  |
| Acer                 | 10       | 10.42%  |
| Goldstar             | 9        | 9.38%   |
| Dell                 | 9        | 9.38%   |
| Hewlett-Packard      | 8        | 8.33%   |
| BenQ                 | 8        | 8.33%   |
| Ancor Communications | 7        | 7.29%   |
| Philips              | 4        | 4.17%   |
| AOC                  | 4        | 4.17%   |
| Lenovo               | 3        | 3.13%   |
| LG Electronics       | 2        | 2.08%   |
| ASUSTek Computer     | 2        | 2.08%   |
| Unknown              | 2        | 2.08%   |
| Vizio                | 1        | 1.04%   |
| Semp Toshiba         | 1        | 1.04%   |
| PKB                  | 1        | 1.04%   |
| NEC Computers        | 1        | 1.04%   |
| MStar                | 1        | 1.04%   |
| MSI                  | 1        | 1.04%   |
| Microstep            | 1        | 1.04%   |
| ITE                  | 1        | 1.04%   |
| Idek Iiyama          | 1        | 1.04%   |
| Fujitsu Siemens      | 1        | 1.04%   |
| Eizo                 | 1        | 1.04%   |
| DENON                | 1        | 1.04%   |
| CVT                  | 1        | 1.04%   |
| AUS                  | 1        | 1.04%   |
| Apple                | 1        | 1.04%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Acer G276HL ACR0300 1920x1080 600x340mm 27.2-inch                      | 2        | 2.08%   |
| Unknown                                                                | 2        | 2.08%   |
| Vizio E321VL VIZ0083 1366x768 700x400mm 31.7-inch                      | 1        | 1.04%   |
| Semp Toshiba MLE1951 STI1951 1366x768 410x230mm 18.5-inch              | 1        | 1.04%   |
| Samsung Electronics SyncMaster SAM05FB 1920x1080 510x290mm 23.1-inch   | 1        | 1.04%   |
| Samsung Electronics SyncMaster SAM058F 1920x1080 480x270mm 21.7-inch   | 1        | 1.04%   |
| Samsung Electronics SyncMaster SAM050B 1920x1080 480x270mm 21.7-inch   | 1        | 1.04%   |
| Samsung Electronics SyncMaster SAM030D 1680x1050 470x300mm 22.0-inch   | 1        | 1.04%   |
| Samsung Electronics SMS27A850 SAM083D 2560x1440 520x320mm 24.0-inch    | 1        | 1.04%   |
| Samsung Electronics S27R35x SAM1053 1920x1080 600x340mm 27.2-inch      | 1        | 1.04%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 600x340mm 27.2-inch      | 1        | 1.04%   |
| Samsung Electronics S24C350 SAM0A3A 1920x1080 530x300mm 24.0-inch      | 1        | 1.04%   |
| Samsung Electronics S22B150 SAM08A3 1920x1080 480x270mm 21.7-inch      | 1        | 1.04%   |
| Samsung Electronics S20B300 SAM08A7 1600x900 440x250mm 19.9-inch       | 1        | 1.04%   |
| Samsung Electronics S19B150 SAM08A2 1366x768 410x230mm 18.5-inch       | 1        | 1.04%   |
| Samsung Electronics Odyssey G50A SAM7181 2560x1440 600x340mm 27.2-inch | 1        | 1.04%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 530x300mm 24.0-inch   | 1        | 1.04%   |
| PKB LCD Monitor MAE200W 1680x1050                                      | 1        | 1.04%   |
| Philips PHL 223V7 PHLC154 1920x1080 480x270mm 21.7-inch                | 1        | 1.04%   |
| Philips PHL 221S8L PHL091C 1920x1080 480x270mm 21.7-inch               | 1        | 1.04%   |
| Philips 202EL PHLC05C 1600x900 440x250mm 19.9-inch                     | 1        | 1.04%   |
| Philips 150S PHL0820 1024x768 300x230mm 14.9-inch                      | 1        | 1.04%   |
| NEC Computers LCD Monitor 70GX2 1280x1024                              | 1        | 1.04%   |
| MStar TSB LEDTV MST0030 1920x1080 1150x650mm 52.0-inch                 | 1        | 1.04%   |
| MSI MP242 MSI30A1 1920x1080 530x300mm 24.0-inch                        | 1        | 1.04%   |
| Microstep LCD Monitor MSI MAG241C 1920x1080                            | 1        | 1.04%   |
| LG Electronics LCD Monitor LG FULL HD 1920x1080                        | 1        | 1.04%   |
| LG Electronics LCD Monitor L1918S 1280x1024                            | 1        | 1.04%   |
| Lenovo L24e-30 LEN66BC 1920x1080 530x300mm 24.0-inch                   | 1        | 1.04%   |
| Lenovo D27-30 LEN66B8 1920x1080 600x340mm 27.2-inch                    | 1        | 1.04%   |
| Lenovo C19-10 LEN66A0 1366x768 410x230mm 18.5-inch                     | 1        | 1.04%   |
| ITE DP2VGA V235 ITE6516 1920x1080 600x340mm 27.2-inch                  | 1        | 1.04%   |
| Idek Iiyama LCD Monitor PL2209HD 5760x2160                             | 1        | 1.04%   |
| Hewlett-Packard ZR2740w HWP2957 2560x1440 600x340mm 27.2-inch          | 1        | 1.04%   |
| Hewlett-Packard Z24nq HWP3239 2560x1440 530x300mm 24.0-inch            | 1        | 1.04%   |
| Hewlett-Packard w2007 HWP26A6 1680x1050 430x270mm 20.0-inch            | 1        | 1.04%   |
| Hewlett-Packard LV1911 HWP3005 1366x768 410x230mm 18.5-inch            | 1        | 1.04%   |
| Hewlett-Packard L1955 HWP262C 1280x1024 380x300mm 19.1-inch            | 1        | 1.04%   |
| Hewlett-Packard HPQ 600 AIO HWP108B 1920x1080 480x270mm 21.7-inch      | 1        | 1.04%   |
| Hewlett-Packard 32 Display HPN351A 1920x1080 700x390mm 31.5-inch       | 1        | 1.04%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 49       | 51.58%  |
| 1366x768 (WXGA)    | 11       | 11.58%  |
| 2560x1440 (QHD)    | 9        | 9.47%   |
| 1280x1024 (SXGA)   | 5        | 5.26%   |
| 1680x1050 (WSXGA+) | 4        | 4.21%   |
| 3840x2160 (4K)     | 3        | 3.16%   |
| 1600x900 (HD+)     | 3        | 3.16%   |
| 1440x900 (WXGA+)   | 3        | 3.16%   |
| 1920x1200 (WUXGA)  | 2        | 2.11%   |
| Unknown            | 2        | 2.11%   |
| 5760x2160          | 1        | 1.05%   |
| 3840x1080          | 1        | 1.05%   |
| 2560x1080          | 1        | 1.05%   |
| 1024x768 (XGA)     | 1        | 1.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 21      | 18       | 19.35%  |
| Unknown | 17       | 18.28%  |
| 24      | 15       | 16.13%  |
| 27      | 10       | 10.75%  |
| 18      | 9        | 9.68%   |
| 19      | 7        | 7.53%   |
| 23      | 6        | 6.45%   |
| 31      | 3        | 3.23%   |
| 20      | 3        | 3.23%   |
| 22      | 2        | 2.15%   |
| 52      | 1        | 1.08%   |
| 34      | 1        | 1.08%   |
| 14      | 1        | 1.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 401-500     | 35       | 37.63%  |
| 501-600     | 31       | 33.33%  |
| Unknown     | 17       | 18.28%  |
| 351-400     | 4        | 4.3%    |
| 601-700     | 3        | 3.23%   |
| 701-800     | 1        | 1.08%   |
| 201-300     | 1        | 1.08%   |
| 1001-1500   | 1        | 1.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 60       | 65.93%  |
| Unknown | 17       | 18.68%  |
| 16/10   | 8        | 8.79%   |
| 5/4     | 3        | 3.3%    |
| 6/5     | 1        | 1.1%    |
| 4/3     | 1        | 1.1%    |
| 21/9    | 1        | 1.1%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 38       | 40.86%  |
| Unknown        | 17       | 18.28%  |
| 151-200        | 12       | 12.9%   |
| 301-350        | 10       | 10.75%  |
| 141-150        | 8        | 8.6%    |
| 351-500        | 4        | 4.3%    |
| 251-300        | 2        | 2.15%   |
| More than 1000 | 1        | 1.08%   |
| 101-110        | 1        | 1.08%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 47       | 51.09%  |
| 101-120 | 21       | 22.83%  |
| Unknown | 17       | 18.48%  |
| 121-160 | 5        | 5.43%   |
| 1-50    | 2        | 2.17%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 159      | 79.9%   |
| 0     | 34       | 17.09%  |
| 2     | 6        | 3.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 117      | 46.8%   |
| Intel                    | 83       | 33.2%   |
| Qualcomm Atheros         | 15       | 6%      |
| Marvell Technology Group | 5        | 2%      |
| Samsung Electronics      | 4        | 1.6%    |
| Ralink Technology        | 4        | 1.6%    |
| Ralink                   | 4        | 1.6%    |
| Broadcom                 | 4        | 1.6%    |
| TP-Link                  | 3        | 1.2%    |
| Huawei Technologies      | 2        | 0.8%    |
| D-Link                   | 2        | 0.8%    |
| National Semiconductor   | 1        | 0.4%    |
| MediaTek                 | 1        | 0.4%    |
| Edimax Technology        | 1        | 0.4%    |
| D-Link System            | 1        | 0.4%    |
| Atheros                  | 1        | 0.4%    |
| Arduino SA               | 1        | 0.4%    |
| Accton Technology        | 1        | 0.4%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 100      | 36.23%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 12       | 4.35%   |
| Intel Ethernet Controller I225-V                                       | 8        | 2.9%    |
| Intel Ethernet Connection (2) I219-LM                                  | 8        | 2.9%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 6        | 2.17%   |
| Intel Ethernet Connection I217-LM                                      | 6        | 2.17%   |
| Intel Ethernet Connection I217-V                                       | 5        | 1.81%   |
| Intel 82579V Gigabit Network Connection                                | 5        | 1.81%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 4        | 1.45%   |
| Intel I211 Gigabit Network Connection                                  | 4        | 1.45%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 3        | 1.09%   |
| Realtek RTL8125 2.5GbE Controller                                      | 3        | 1.09%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 3        | 1.09%   |
| Intel Wireless 3165                                                    | 3        | 1.09%   |
| Intel Ethernet Connection (7) I219-V                                   | 3        | 1.09%   |
| Intel Ethernet Connection (2) I219-V                                   | 3        | 1.09%   |
| Intel 82574L Gigabit Network Connection                                | 3        | 1.09%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 3        | 1.09%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 2        | 0.72%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                        | 2        | 0.72%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 2        | 0.72%   |
| Ralink RT2870/RT3070 Wireless Adapter                                  | 2        | 0.72%   |
| Ralink RT2500 Wireless 802.11bg                                        | 2        | 0.72%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 2        | 0.72%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 2        | 0.72%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                       | 2        | 0.72%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)         | 2        | 0.72%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 2        | 0.72%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 2        | 0.72%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                | 2        | 0.72%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 2        | 0.72%   |
| Intel Wireless 8265 / 8275                                             | 2        | 0.72%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 2        | 0.72%   |
| Intel Wi-Fi 6 AX200                                                    | 2        | 0.72%   |
| Intel Tiger Lake PCH CNVi WiFi                                         | 2        | 0.72%   |
| Intel I210 Gigabit Network Connection                                  | 2        | 0.72%   |
| Intel Ethernet Connection (7) I219-LM                                  | 2        | 0.72%   |
| Intel Ethernet Connection (17) I219-V                                  | 2        | 0.72%   |
| Intel Ethernet Connection (14) I219-V                                  | 2        | 0.72%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 2        | 0.72%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 21       | 30.43%  |
| Realtek Semiconductor | 18       | 26.09%  |
| Qualcomm Atheros      | 8        | 11.59%  |
| Ralink Technology     | 4        | 5.8%    |
| Ralink                | 4        | 5.8%    |
| Broadcom              | 4        | 5.8%    |
| TP-Link               | 3        | 4.35%   |
| D-Link                | 2        | 2.9%    |
| MediaTek              | 1        | 1.45%   |
| Edimax Technology     | 1        | 1.45%   |
| D-Link System         | 1        | 1.45%   |
| Atheros               | 1        | 1.45%   |
| Accton Technology     | 1        | 1.45%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                   | 6        | 8.57%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                        | 4        | 5.71%   |
| Intel Wireless 3165                                                        | 3        | 4.29%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                               | 2        | 2.86%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                            | 2        | 2.86%   |
| Ralink RT2870/RT3070 Wireless Adapter                                      | 2        | 2.86%   |
| Ralink RT2500 Wireless 802.11bg                                            | 2        | 2.86%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                 | 2        | 2.86%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                           | 2        | 2.86%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                           | 2        | 2.86%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)             | 2        | 2.86%   |
| Intel Wireless 8265 / 8275                                                 | 2        | 2.86%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                  | 2        | 2.86%   |
| Intel Wi-Fi 6 AX200                                                        | 2        | 2.86%   |
| Intel Tiger Lake PCH CNVi WiFi                                             | 2        | 2.86%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                           | 2        | 2.86%   |
| Intel Cannon Lake PCH CNVi WiFi                                            | 2        | 2.86%   |
| Intel Alder Lake-S PCH CNVi WiFi                                           | 2        | 2.86%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                        | 1        | 1.43%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                   | 1        | 1.43%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                            | 1        | 1.43%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                   | 1        | 1.43%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                | 1        | 1.43%   |
| Realtek RTL8188EE Wireless Network Adapter                                 | 1        | 1.43%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                    | 1        | 1.43%   |
| Realtek 8811CU Wireless LAN 802.11ac USB NIC                               | 1        | 1.43%   |
| Ralink RT3072 Wireless Adapter                                             | 1        | 1.43%   |
| Ralink MT7601U Wireless Adapter                                            | 1        | 1.43%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                  | 1        | 1.43%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                  | 1        | 1.43%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter              | 1        | 1.43%   |
| Intel Wireless 8260                                                        | 1        | 1.43%   |
| Intel Wireless 7265                                                        | 1        | 1.43%   |
| Intel Wireless 7260                                                        | 1        | 1.43%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                    | 1        | 1.43%   |
| Edimax EW-7711UTn nLite Wireless Adapter [Ralink RT3070]                   | 1        | 1.43%   |
| D-Link System AirPlus G DWL-G122 Wireless Adapter(rev.C1) [Ralink RT2571W] | 1        | 1.43%   |
| D-Link DWA-171 AC600 DB Wireless Adapter(rev.A1) [Realtek RTL8811AU]       | 1        | 1.43%   |
| D-Link DWA-125 Wireless N 150 Adapter(rev.D1) [Realtek RTL8188ETV]         | 1        | 1.43%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter               | 1        | 1.43%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 109      | 53.96%  |
| Intel                    | 73       | 36.14%  |
| Qualcomm Atheros         | 7        | 3.47%   |
| Marvell Technology Group | 5        | 2.48%   |
| Samsung Electronics      | 4        | 1.98%   |
| Huawei Technologies      | 2        | 0.99%   |
| National Semiconductor   | 1        | 0.5%    |
| Broadcom                 | 1        | 0.5%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 100      | 48.78%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 12       | 5.85%   |
| Intel Ethernet Controller I225-V                                       | 8        | 3.9%    |
| Intel Ethernet Connection (2) I219-LM                                  | 8        | 3.9%    |
| Intel Ethernet Connection I217-LM                                      | 6        | 2.93%   |
| Intel Ethernet Connection I217-V                                       | 5        | 2.44%   |
| Intel 82579V Gigabit Network Connection                                | 5        | 2.44%   |
| Intel I211 Gigabit Network Connection                                  | 4        | 1.95%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 3        | 1.46%   |
| Realtek RTL8125 2.5GbE Controller                                      | 3        | 1.46%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 3        | 1.46%   |
| Intel Ethernet Connection (7) I219-V                                   | 3        | 1.46%   |
| Intel Ethernet Connection (2) I219-V                                   | 3        | 1.46%   |
| Intel 82574L Gigabit Network Connection                                | 3        | 1.46%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 3        | 1.46%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 2        | 0.98%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 2        | 0.98%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 2        | 0.98%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                | 2        | 0.98%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 2        | 0.98%   |
| Intel I210 Gigabit Network Connection                                  | 2        | 0.98%   |
| Intel Ethernet Connection (7) I219-LM                                  | 2        | 0.98%   |
| Intel Ethernet Connection (17) I219-V                                  | 2        | 0.98%   |
| Intel Ethernet Connection (14) I219-V                                  | 2        | 0.98%   |
| Intel 82567LF-3 Gigabit Network Connection                             | 2        | 0.98%   |
| Intel 82566DM-2 Gigabit Network Connection                             | 2        | 0.98%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 1        | 0.49%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller      | 1        | 0.49%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                          | 1        | 0.49%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 1        | 0.49%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 1        | 0.49%   |
| National DP83815 (MacPhyter) Ethernet Controller                       | 1        | 0.49%   |
| Marvell Group 88E8070 based Ethernet Controller                        | 1        | 0.49%   |
| Intel Ethernet Connection (5) I219-V                                   | 1        | 0.49%   |
| Intel Ethernet Connection (5) I219-LM                                  | 1        | 0.49%   |
| Intel Ethernet Connection (2) I218-V                                   | 1        | 0.49%   |
| Intel Ethernet Connection (2) I218-LM                                  | 1        | 0.49%   |
| Huawei USB Device                                                      | 1        | 0.49%   |
| Huawei Android ADB Interface                                           | 1        | 0.49%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                    | 1        | 0.49%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 192      | 74.71%  |
| WiFi     | 64       | 24.9%   |
| Modem    | 1        | 0.39%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 171      | 95.53%  |
| WiFi     | 8        | 4.47%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 137      | 68.84%  |
| 2     | 53       | 26.63%  |
| 0     | 5        | 2.51%   |
| 3     | 4        | 2.01%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 190      | 94.53%  |
| Yes  | 11       | 5.47%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 20       | 36.36%  |
| Realtek Semiconductor           | 11       | 20%     |
| Cambridge Silicon Radio         | 9        | 16.36%  |
| ASUSTek Computer                | 3        | 5.45%   |
| TP-Link                         | 2        | 3.64%   |
| IMC Networks                    | 2        | 3.64%   |
| Broadcom                        | 2        | 3.64%   |
| Apple                           | 2        | 3.64%   |
| Qualcomm Atheros Communications | 1        | 1.82%   |
| Primax Electronics              | 1        | 1.82%   |
| Lite-On Technology              | 1        | 1.82%   |
| Fujitsu                         | 1        | 1.82%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 9        | 16.36%  |
| Intel Bluetooth wireless interface                          | 8        | 14.55%  |
| Realtek Bluetooth Adapter                                   | 7        | 12.73%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 3        | 5.45%   |
| Intel AX201 Bluetooth                                       | 3        | 5.45%   |
| TP-Link Bluetooth 5.0 USB Adapter                           | 2        | 3.64%   |
| Realtek  Bluetooth 4.2 Adapter                              | 2        | 3.64%   |
| Intel Wireless-AC 3168 Bluetooth                            | 2        | 3.64%   |
| Intel AX210 Bluetooth                                       | 2        | 3.64%   |
| Broadcom BCM20702A0 Bluetooth 4.0                           | 2        | 3.64%   |
| Realtek Bluetooth 5.1 Adapter                               | 1        | 1.82%   |
| Realtek Bluetooth 4.2 Adapter                               | 1        | 1.82%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1        | 1.82%   |
| Primax Rocketfish RF-FLBTAD Bluetooth Adapter               | 1        | 1.82%   |
| Lite-On Atheros AR3012 Bluetooth                            | 1        | 1.82%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 1        | 1.82%   |
| Intel AX200 Bluetooth                                       | 1        | 1.82%   |
| IMC Networks Qualcomm Atheros AR9462 Bluetooth 4.0 + HS     | 1        | 1.82%   |
| IMC Networks MediaTek Bluetooth Adapter                     | 1        | 1.82%   |
| Fujitsu Qualcomm Atheros AR9462 Bluetooth 4.0 + HS Adapter  | 1        | 1.82%   |
| ASUS USB-BT500                                              | 1        | 1.82%   |
| ASUS Broadcom BCM20702A0 Bluetooth                          | 1        | 1.82%   |
| ASUS Bluetooth Controller                                   | 1        | 1.82%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 1        | 1.82%   |
| Apple Bluetooth Host Controller                             | 1        | 1.82%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 137      | 43.91%  |
| AMD                      | 75       | 24.04%  |
| Nvidia                   | 54       | 17.31%  |
| C-Media Electronics      | 17       | 5.45%   |
| Texas Instruments        | 4        | 1.28%   |
| Creative Labs            | 3        | 0.96%   |
| Realtek Semiconductor    | 2        | 0.64%   |
| JMTek                    | 2        | 0.64%   |
| Unknown                  | 2        | 0.64%   |
| Yamaha                   | 1        | 0.32%   |
| SteelSeries ApS          | 1        | 0.32%   |
| Razer USA                | 1        | 0.32%   |
| OPPO Electronics         | 1        | 0.32%   |
| Microsoft                | 1        | 0.32%   |
| Micro Star International | 1        | 0.32%   |
| M-Audio                  | 1        | 0.32%   |
| KTMicro                  | 1        | 0.32%   |
| Hewlett-Packard          | 1        | 0.32%   |
| HECATE G2 GAMING HEADSET | 1        | 0.32%   |
| Harman                   | 1        | 0.32%   |
| Generalplus Technology   | 1        | 0.32%   |
| GEMBIRD                  | 1        | 0.32%   |
| Edifier Technology       | 1        | 0.32%   |
| Creative Technology      | 1        | 0.32%   |
| Cambridge Silicon Radio  | 1        | 0.32%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 23       | 6.27%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 19       | 5.18%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 18       | 4.9%    |
| Intel 200 Series PCH HD Audio                                              | 16       | 4.36%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 15       | 4.09%   |
| AMD Family 17h/19h HD Audio Controller                                     | 14       | 3.81%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 11       | 3%      |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 10       | 2.72%   |
| AMD Starship/Matisse HD Audio Controller                                   | 10       | 2.72%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 9        | 2.45%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 9        | 2.45%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 9        | 2.45%   |
| Intel Cannon Lake PCH cAVS                                                 | 8        | 2.18%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 7        | 1.91%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 7        | 1.91%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 7        | 1.91%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 6        | 1.63%   |
| Nvidia TU116 High Definition Audio Controller                              | 5        | 1.36%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5        | 1.36%   |
| AMD FCH Azalia Controller                                                  | 5        | 1.36%   |
| Nvidia High Definition Audio Controller                                    | 4        | 1.09%   |
| Nvidia GP107GL High Definition Audio Controller                            | 4        | 1.09%   |
| Nvidia GP106 High Definition Audio Controller                              | 4        | 1.09%   |
| Nvidia GK107 HDMI Audio Controller                                         | 4        | 1.09%   |
| Intel Alder Lake-S HD Audio Controller                                     | 4        | 1.09%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 4        | 1.09%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 4        | 1.09%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4        | 1.09%   |
| Nvidia MCP61 High Definition Audio                                         | 3        | 0.82%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 3        | 0.82%   |
| Nvidia GK104 HDMI Audio Controller                                         | 3        | 0.82%   |
| Nvidia GA104 High Definition Audio Controller                              | 3        | 0.82%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 3        | 0.82%   |
| Intel Comet Lake PCH-V cAVS                                                | 3        | 0.82%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 3        | 0.82%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                              | 3        | 0.82%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                 | 3        | 0.82%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                               | 3        | 0.82%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 3        | 0.82%   |
| Nvidia GM204 High Definition Audio Controller                              | 2        | 0.54%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 43       | 17.92%  |
| Samsung Electronics | 30       | 12.5%   |
| Unknown             | 24       | 10%     |
| Corsair             | 22       | 9.17%   |
| Micron Technology   | 18       | 7.5%    |
| SK hynix            | 17       | 7.08%   |
| Crucial             | 17       | 7.08%   |
| G.Skill             | 11       | 4.58%   |
| Unknown             | 11       | 4.58%   |
| Patriot             | 6        | 2.5%    |
| Nanya Technology    | 6        | 2.5%    |
| A-DATA Technology   | 5        | 2.08%   |
| Ramaxel Technology  | 4        | 1.67%   |
| Apacer              | 3        | 1.25%   |
| Unknown (ABCD)      | 2        | 0.83%   |
| Transcend           | 2        | 0.83%   |
| Team                | 2        | 0.83%   |
| Kingmax             | 2        | 0.83%   |
| GOODRAM             | 2        | 0.83%   |
| Atermiter           | 2        | 0.83%   |
| Unknown (8A02)      | 1        | 0.42%   |
| Teikon              | 1        | 0.42%   |
| Smart               | 1        | 0.42%   |
| Qumo                | 1        | 0.42%   |
| MemoWise            | 1        | 0.42%   |
| Lexar               | 1        | 0.42%   |
| Juhor               | 1        | 0.42%   |
| Golden Empire       | 1        | 0.42%   |
| Elpida              | 1        | 0.42%   |
| Avant               | 1        | 0.42%   |
| AMD                 | 1        | 0.42%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Unknown                                                                 | 11       | 4.3%    |
| Unknown RAM Module 4GB DIMM 1333MT/s                                    | 4        | 1.56%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s                   | 4        | 1.56%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s                     | 3        | 1.17%   |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3200MT/s                     | 3        | 1.17%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                               | 2        | 0.78%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                                    | 2        | 0.78%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                                | 2        | 0.78%   |
| Unknown RAM Module 2GB DIMM 800MT/s                                     | 2        | 0.78%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                                    | 2        | 0.78%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s            | 2        | 0.78%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                             | 2        | 0.78%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                   | 2        | 0.78%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s                   | 2        | 0.78%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s                     | 2        | 0.78%   |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM DDR3 1333MT/s                     | 2        | 0.78%   |
| Samsung RAM M3 78T2863DZS-CE6 1GB DIMM DDR2 667MT/s                     | 2        | 0.78%   |
| Patriot RAM 2666 C16 Series 4GB DIMM DDR4 3000MT/s                      | 2        | 0.78%   |
| Nanya RAM NT2GC64B88B0NF-CG 2GB DIMM DDR3 1333MT/s                      | 2        | 0.78%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s                     | 2        | 0.78%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2400MT/s                       | 2        | 0.78%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s                     | 2        | 0.78%   |
| Kingston RAM 202020202020202020202020202020202020 2GB DIMM DDR2 800MT/s | 2        | 0.78%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3200MT/s                    | 2        | 0.78%   |
| Corsair RAM CMK32GX4M2A2400C16 16GB DIMM DDR4 2400MT/s                  | 2        | 0.78%   |
| Unknown RAM Module 8GB DIMM DDR4 2667MT/s                               | 1        | 0.39%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                                    | 1        | 0.39%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                             | 1        | 0.39%   |
| Unknown RAM Module 2GB DIMM DDR3 1600MT/s                               | 1        | 0.39%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                               | 1        | 0.39%   |
| Unknown RAM Module 2GB DIMM DDR 667MT/s                                 | 1        | 0.39%   |
| Unknown RAM Module 2GB DIMM 400MT/s                                     | 1        | 0.39%   |
| Unknown RAM Module 2GB DIMM 1066MT/s                                    | 1        | 0.39%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s                                | 1        | 0.39%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                                | 1        | 0.39%   |
| Unknown RAM Module 1GB DIMM DDR2                                        | 1        | 0.39%   |
| Unknown RAM Module 1GB DIMM DDR 667MT/s                                 | 1        | 0.39%   |
| Unknown RAM Module 1GB DIMM 400MT/s                                     | 1        | 0.39%   |
| Unknown (8A02) RAM Module 8GB DIMM DDR3 1600MT/s                        | 1        | 0.39%   |
| Transcend RAM JM667QLU-1G 1GB DIMM DDR2 667MT/s                         | 1        | 0.39%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 92       | 46.7%   |
| DDR3    | 69       | 35.03%  |
| Unknown | 15       | 7.61%   |
| DDR2    | 13       | 6.6%    |
| SDRAM   | 3        | 1.52%   |
| LPDDR4  | 2        | 1.02%   |
| DDR     | 2        | 1.02%   |
| DDR5    | 1        | 0.51%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 168      | 85.71%  |
| SODIMM | 28       | 14.29%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 90       | 40.72%  |
| 4096  | 57       | 25.79%  |
| 2048  | 35       | 15.84%  |
| 16384 | 24       | 10.86%  |
| 1024  | 12       | 5.43%   |
| 32768 | 3        | 1.36%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 40       | 19.05%  |
| 1333    | 37       | 17.62%  |
| 3200    | 23       | 10.95%  |
| 2133    | 22       | 10.48%  |
| 2400    | 19       | 9.05%   |
| 2667    | 18       | 8.57%   |
| 800     | 11       | 5.24%   |
| 3600    | 6        | 2.86%   |
| 667     | 6        | 2.86%   |
| 1067    | 5        | 2.38%   |
| 1066    | 4        | 1.9%    |
| 3000    | 3        | 1.43%   |
| 2666    | 3        | 1.43%   |
| Unknown | 3        | 1.43%   |
| 400     | 2        | 0.95%   |
| 6400    | 1        | 0.48%   |
| 4400    | 1        | 0.48%   |
| 3333    | 1        | 0.48%   |
| 2933    | 1        | 0.48%   |
| 1867    | 1        | 0.48%   |
| 1639    | 1        | 0.48%   |
| 1200    | 1        | 0.48%   |
| 533     | 1        | 0.48%   |

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
| Microdia REDRAGON  Live Camera                    | 2        | 11.76%  |
| Trust Trust Full HD Webcam                        | 1        | 5.88%   |
| Sunplus hama C-600 Pro Webcam                     | 1        | 5.88%   |
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
| 1     | 95       | 47.74%  |
| 0     | 66       | 33.17%  |
| 2     | 32       | 16.08%  |
| 3     | 4        | 2.01%   |
| 4     | 2        | 1.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 120      | 72.73%  |
| Net/wireless             | 19       | 11.52%  |
| Sound                    | 13       | 7.88%   |
| Bluetooth                | 5        | 3.03%   |
| Card reader              | 3        | 1.82%   |
| Net/ethernet             | 2        | 1.21%   |
| Storage/raid             | 1        | 0.61%   |
| Network                  | 1        | 0.61%   |
| Dvb card                 | 1        | 0.61%   |

