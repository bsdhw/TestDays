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

Total: 318

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
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
| amd64 | 268       | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| helloDesktop | 265       | 98.88%  |
| GNOME        | 2         | 0.75%   |
| KDE5         | 1         | 0.37%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 268       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| SLiM | 268       | 99.63%  |
| SDDM | 1         | 0.37%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 122       | 45.19%  |
| fr_FR   | 63        | 23.33%  |
| de_DE   | 18        | 6.67%   |
| ru_RU   | 17        | 6.3%    |
| es_ES   | 14        | 5.19%   |
| Unknown | 8         | 2.96%   |
| pt_BR   | 6         | 2.22%   |
| pl_PL   | 6         | 2.22%   |
| it_IT   | 5         | 1.85%   |
| ko_KR   | 2         | 0.74%   |
| jp_JP   | 2         | 0.74%   |
| zh_CN   | 1         | 0.37%   |
| pt      | 1         | 0.37%   |
| nl_NL   | 1         | 0.37%   |
| fr      | 1         | 0.37%   |
| fi_FI   | 1         | 0.37%   |
| es      | 1         | 0.37%   |
| en      | 1         | 0.37%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 265       | 98.88%  |
| BIOS | 3         | 1.12%   |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type   | Computers | Percent |
|--------|-----------|---------|
| Cd9660 | 144       | 53.14%  |
| Zfs    | 127       | 46.86%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 265       | 98.88%  |
| MBR  | 3         | 1.12%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 52        | 19.4%   |
| ASUSTek Computer    | 37        | 13.81%  |
| Dell                | 31        | 11.57%  |
| Hewlett-Packard     | 28        | 10.45%  |
| Gigabyte Technology | 22        | 8.21%   |
| Acer                | 12        | 4.48%   |
| Intel               | 9         | 3.36%   |
| MSI                 | 8         | 2.99%   |
| Toshiba             | 7         | 2.61%   |
| Fujitsu             | 7         | 2.61%   |
| Apple               | 6         | 2.24%   |
| Samsung Electronics | 5         | 1.87%   |
| ASRock              | 5         | 1.87%   |
| Unknown             | 5         | 1.87%   |
| Sony                | 4         | 1.49%   |
| Google              | 4         | 1.49%   |
| T-bao               | 2         | 0.75%   |
| Packard Bell        | 2         | 0.75%   |
| Fujitsu Siemens     | 2         | 0.75%   |
| Foxconn             | 2         | 0.75%   |
| AZW                 | 2         | 0.75%   |
| TUXEDO              | 1         | 0.37%   |
| Timi                | 1         | 0.37%   |
| Plaisio             | 1         | 0.37%   |
| Pegatron            | 1         | 0.37%   |
| Panasonic           | 1         | 0.37%   |
| Microsoft           | 1         | 0.37%   |
| Medion              | 1         | 0.37%   |
| LG Electronics      | 1         | 0.37%   |
| Irbis               | 1         | 0.37%   |
| IGEL Technology     | 1         | 0.37%   |
| Huanan              | 1         | 0.37%   |
| Dynabook Europe     | 1         | 0.37%   |
| DNS                 | 1         | 0.37%   |
| Biostar             | 1         | 0.37%   |
| BESSTAR Tech        | 1         | 0.37%   |
| Axiomtek            | 1         | 0.37%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                              | Computers | Percent |
|-----------------------------------|-----------|---------|
| Unknown                           | 7         | 2.61%   |
| T-bao MINI PC                     | 2         | 0.75%   |
| MSI MS-7788                       | 2         | 0.75%   |
| HP Laptop 14-bs0xx                | 2         | 0.75%   |
| HP Compaq Elite 8300 USDT         | 2         | 0.75%   |
| ASUS ROG STRIX B550-F GAMING      | 2         | 0.75%   |
| ASUS PRIME B250M-A                | 2         | 0.75%   |
| ASUS All Series                   | 2         | 0.75%   |
| Acer Spin SP314-21                | 2         | 0.75%   |
| TUXEDO Aura 15 Gen1               | 1         | 0.37%   |
| Toshiba Satellite P300            | 1         | 0.37%   |
| Toshiba Satellite L675D           | 1         | 0.37%   |
| Toshiba Satellite L50-B           | 1         | 0.37%   |
| Toshiba Satellite L40             | 1         | 0.37%   |
| Toshiba Satellite C845            | 1         | 0.37%   |
| Toshiba Satellite A200            | 1         | 0.37%   |
| Toshiba PORTEGE R700              | 1         | 0.37%   |
| Timi TM1701                       | 1         | 0.37%   |
| Sony VPCEG15FB                    | 1         | 0.37%   |
| Sony VGN-FZ19VN                   | 1         | 0.37%   |
| Sony SVL2412Z1EB                  | 1         | 0.37%   |
| Sony SVF14A15CBB                  | 1         | 0.37%   |
| Samsung R520/R522/R620            | 1         | 0.37%   |
| Samsung R468/R418                 | 1         | 0.37%   |
| Samsung 370E4K                    | 1         | 0.37%   |
| Samsung 305E4A/305E5A/305E7A      | 1         | 0.37%   |
| Samsung 275E4E/275E5E             | 1         | 0.37%   |
| Plaisio Turbo X                   | 1         | 0.37%   |
| Pegatron Compaq dx2450 Microtower | 1         | 0.37%   |
| Panasonic CF-NX1GDHYS             | 1         | 0.37%   |
| Packard Bell EasyNote LJ65        | 1         | 0.37%   |
| Packard Bell DOT SE               | 1         | 0.37%   |
| MSI MS-7C95                       | 1         | 0.37%   |
| MSI MS-7C51                       | 1         | 0.37%   |
| MSI MS-7C09                       | 1         | 0.37%   |
| MSI MS-7B86                       | 1         | 0.37%   |
| MSI MS-7599                       | 1         | 0.37%   |
| MSI Compaq dx2200 MT              | 1         | 0.37%   |
| Microsoft Surface Pro 7           | 1         | 0.37%   |
| Medion E15302                     | 1         | 0.37%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 31        | 11.57%  |
| ASUS PRIME              | 10        | 3.73%   |
| Dell Inspiron           | 9         | 3.36%   |
| Lenovo ThinkCentre      | 8         | 2.99%   |
| Dell Latitude           | 8         | 2.99%   |
| Dell OptiPlex           | 7         | 2.61%   |
| Unknown                 | 7         | 2.61%   |
| Toshiba Satellite       | 6         | 2.24%   |
| HP Pavilion             | 6         | 2.24%   |
| ASUS ROG                | 6         | 2.24%   |
| HP Laptop               | 5         | 1.87%   |
| Lenovo IdeaPad          | 4         | 1.49%   |
| HP Compaq               | 4         | 1.49%   |
| HP EliteDesk            | 3         | 1.12%   |
| Dell Precision          | 3         | 1.12%   |
| Acer Aspire             | 3         | 1.12%   |
| T-bao MINI              | 2         | 0.75%   |
| MSI MS-7788             | 2         | 0.75%   |
| HP ProDesk              | 2         | 0.75%   |
| HP EliteBook            | 2         | 0.75%   |
| Gigabyte B450M          | 2         | 0.75%   |
| Fujitsu Siemens ESPRIMO | 2         | 0.75%   |
| Fujitsu LIFEBOOK        | 2         | 0.75%   |
| Dell Vostro             | 2         | 0.75%   |
| ASUS VivoBook           | 2         | 0.75%   |
| ASUS TUF                | 2         | 0.75%   |
| ASUS All                | 2         | 0.75%   |
| Acer Veriton            | 2         | 0.75%   |
| Acer Spin               | 2         | 0.75%   |
| TUXEDO Aura             | 1         | 0.37%   |
| Toshiba PORTEGE         | 1         | 0.37%   |
| Timi TM1701             | 1         | 0.37%   |
| Sony VPCEG15FB          | 1         | 0.37%   |
| Sony VGN-FZ19VN         | 1         | 0.37%   |
| Sony SVL2412Z1EB        | 1         | 0.37%   |
| Sony SVF14A15CBB        | 1         | 0.37%   |
| Samsung R520            | 1         | 0.37%   |
| Samsung R468            | 1         | 0.37%   |
| Samsung 370E4K          | 1         | 0.37%   |
| Samsung 305E4A          | 1         | 0.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2022    | 26        | 9.7%    |
| 2020    | 25        | 9.33%   |
| 2013    | 25        | 9.33%   |
| 2021    | 24        | 8.96%   |
| 2012    | 24        | 8.96%   |
| 2011    | 19        | 7.09%   |
| 2019    | 17        | 6.34%   |
| 2017    | 14        | 5.22%   |
| 2014    | 14        | 5.22%   |
| 2018    | 12        | 4.48%   |
| 2010    | 12        | 4.48%   |
| 2009    | 12        | 4.48%   |
| 2008    | 11        | 4.1%    |
| 2016    | 9         | 3.36%   |
| 2015    | 9         | 3.36%   |
| 2023    | 6         | 2.24%   |
| 2007    | 6         | 2.24%   |
| 2006    | 2         | 0.75%   |
| Unknown | 1         | 0.37%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Desktop     | 128       | 47.76%  |
| Notebook    | 126       | 47.01%  |
| Convertible | 5         | 1.87%   |
| Mini pc     | 5         | 1.87%   |
| All in one  | 2         | 0.75%   |
| Tablet      | 1         | 0.37%   |
| Server      | 1         | 0.37%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 262       | 97.76%  |
| Yes  | 6         | 2.24%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 97        | 36.19%  |
| 4.01-8.0    | 66        | 24.63%  |
| 16.01-24.0  | 61        | 22.76%  |
| 32.01-64.0  | 18        | 6.72%   |
| 2.01-3.0    | 17        | 6.34%   |
| 64.01-256.0 | 4         | 1.49%   |
| 3.01-4.0    | 2         | 0.75%   |
| 24.01-32.0  | 2         | 0.75%   |
| 0.51-1.0    | 1         | 0.37%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 144       | 53.33%  |
| 0.51-1.0 | 89        | 32.96%  |
| 1.01-2.0 | 26        | 9.63%   |
| 2.01-3.0 | 10        | 3.7%    |
| 3.01-4.0 | 1         | 0.37%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 166       | 61.71%  |
| 2      | 49        | 18.22%  |
| 3      | 23        | 8.55%   |
| 0      | 20        | 7.43%   |
| 5      | 5         | 1.86%   |
| 9      | 2         | 0.74%   |
| 4      | 2         | 0.74%   |
| 7      | 1         | 0.37%   |
| 6      | 1         | 0.37%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 174       | 64.93%  |
| Yes       | 94        | 35.07%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 243       | 90.67%  |
| No        | 25        | 9.33%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 175       | 65.06%  |
| No        | 94        | 34.94%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 141       | 52.61%  |
| Yes       | 127       | 47.39%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country            | Computers | Percent |
|--------------------|-----------|---------|
| USA                | 37        | 13.81%  |
| Russia             | 27        | 10.07%  |
| Germany            | 23        | 8.58%   |
| Brazil             | 17        | 6.34%   |
| Poland             | 16        | 5.97%   |
| Spain              | 14        | 5.22%   |
| Italy              | 10        | 3.73%   |
| France             | 10        | 3.73%   |
| Romania            | 9         | 3.36%   |
| Canada             | 9         | 3.36%   |
| Indonesia          | 7         | 2.61%   |
| UK                 | 6         | 2.24%   |
| Hungary            | 6         | 2.24%   |
| Turkey             | 5         | 1.87%   |
| India              | 5         | 1.87%   |
| Australia          | 5         | 1.87%   |
| Serbia             | 4         | 1.49%   |
| Mexico             | 4         | 1.49%   |
| China              | 4         | 1.49%   |
| Bulgaria           | 4         | 1.49%   |
| South Korea        | 3         | 1.12%   |
| Peru               | 3         | 1.12%   |
| Belgium            | 3         | 1.12%   |
| Switzerland        | 2         | 0.75%   |
| Sweden             | 2         | 0.75%   |
| Slovenia           | 2         | 0.75%   |
| Netherlands        | 2         | 0.75%   |
| Lithuania          | 2         | 0.75%   |
| Japan              | 2         | 0.75%   |
| Dominican Republic | 2         | 0.75%   |
| Chile              | 2         | 0.75%   |
| Belarus            | 2         | 0.75%   |
| Argentina          | 2         | 0.75%   |
| Ukraine            | 1         | 0.37%   |
| Thailand           | 1         | 0.37%   |
| Slovakia           | 1         | 0.37%   |
| San Marino         | 1         | 0.37%   |
| Portugal           | 1         | 0.37%   |
| Philippines        | 1         | 0.37%   |
| Kosovo             | 1         | 0.37%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Sao Paulo          | 5         | 1.85%   |
| Berlin             | 5         | 1.85%   |
| Sydney             | 4         | 1.48%   |
| St. Jean Baptiste  | 4         | 1.48%   |
| Moscow             | 4         | 1.48%   |
| Warsaw             | 3         | 1.11%   |
| Milan              | 3         | 1.11%   |
| Wroclaw            | 2         | 0.74%   |
| Valencia           | 2         | 0.74%   |
| St Petersburg      | 2         | 0.74%   |
| Sofia              | 2         | 0.74%   |
| Santo Domingo Este | 2         | 0.74%   |
| Santiago           | 2         | 0.74%   |
| Pensacola          | 2         | 0.74%   |
| Paris              | 2         | 0.74%   |
| Montreal           | 2         | 0.74%   |
| Madrid             | 2         | 0.74%   |
| Krasnodar          | 2         | 0.74%   |
| Krakow             | 2         | 0.74%   |
| Kirov              | 2         | 0.74%   |
| Irkutsk            | 2         | 0.74%   |
| Dresden            | 2         | 0.74%   |
| Budapest           | 2         | 0.74%   |
| Brooklyn           | 2         | 0.74%   |
| Belgrade           | 2         | 0.74%   |
| Ankara             | 2         | 0.74%   |
| Zurich             | 1         | 0.37%   |
| Zhengzhou          | 1         | 0.37%   |
| Yokohama           | 1         | 0.37%   |
| Yeosu              | 1         | 0.37%   |
| Yekaterinburg      | 1         | 0.37%   |
| Woodbridge         | 1         | 0.37%   |
| Witkow             | 1         | 0.37%   |
| West Plains        | 1         | 0.37%   |
| Wausau             | 1         | 0.37%   |
| Volgodonsk         | 1         | 0.37%   |
| Vogogna            | 1         | 0.37%   |
| Vitória           | 1         | 0.37%   |
| Vitebsk            | 1         | 0.37%   |
| Virovitica         | 1         | 0.37%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 54        | 75     | 15.43%  |
| Samsung Electronics | 54        | 71     | 15.43%  |
| Seagate             | 43        | 50     | 12.29%  |
| Kingston            | 31        | 31     | 8.86%   |
| Toshiba             | 25        | 28     | 7.14%   |
| SanDisk             | 19        | 19     | 5.43%   |
| Hitachi             | 14        | 14     | 4%      |
| Crucial             | 13        | 16     | 3.71%   |
| China               | 8         | 9      | 2.29%   |
| Micron Technology   | 7         | 8      | 2%      |
| A-DATA Technology   | 7         | 8      | 2%      |
| Intel               | 6         | 6      | 1.71%   |
| HGST                | 6         | 9      | 1.71%   |
| Transcend           | 5         | 5      | 1.43%   |
| SK hynix            | 4         | 4      | 1.14%   |
| Patriot             | 4         | 4      | 1.14%   |
| Maxtor              | 4         | 4      | 1.14%   |
| KingSpec            | 4         | 4      | 1.14%   |
| PNY                 | 3         | 3      | 0.86%   |
| Gigabyte Technology | 3         | 4      | 0.86%   |
| SPCC                | 2         | 2      | 0.57%   |
| OCZ                 | 2         | 2      | 0.57%   |
| Netac               | 2         | 2      | 0.57%   |
| Intenso             | 2         | 2      | 0.57%   |
| GOODRAM             | 2         | 2      | 0.57%   |
| Apple               | 2         | 2      | 0.57%   |
| Verbatim            | 1         | 1      | 0.29%   |
| Vaseky              | 1         | 1      | 0.29%   |
| V-GeN               | 1         | 1      | 0.29%   |
| Silicon Motion      | 1         | 1      | 0.29%   |
| QUANTUM             | 1         | 1      | 0.29%   |
| Plextor             | 1         | 1      | 0.29%   |
| Pioneer             | 1         | 1      | 0.29%   |
| Philips             | 1         | 1      | 0.29%   |
| Palit               | 1         | 1      | 0.29%   |
| LITEONIT            | 1         | 1      | 0.29%   |
| Kston               | 1         | 1      | 0.29%   |
| KIOXIA-EXCERIA      | 1         | 1      | 0.29%   |
| KIOXIA              | 1         | 1      | 0.29%   |
| Kingmax             | 1         | 1      | 0.29%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB          | 8         | 2.05%   |
| Seagate ST500DM002-1BD142 500GB      | 5         | 1.28%   |
| Samsung SSD 860 EVO 500GB            | 5         | 1.28%   |
| Samsung SSD 850 EVO 250GB            | 5         | 1.28%   |
| Seagate ST3500418AS 500GB            | 4         | 1.03%   |
| Samsung SSD 980 1TB                  | 4         | 1.03%   |
| WDC WD10EZEX-08WN4A0 1TB             | 3         | 0.77%   |
| Seagate ST2000DM008-2FR102 2TB       | 3         | 0.77%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 3         | 0.77%   |
| Seagate ST1000DM010-2EP102 1TB       | 3         | 0.77%   |
| Samsung SSD 970 EVO Plus 1TB         | 3         | 0.77%   |
| Kingston SHFS37A240G 240GB           | 3         | 0.77%   |
| Crucial CT480BX500SSD1 480GB         | 3         | 0.77%   |
| WDC WDS240G2G0A-00JH30 240GB         | 2         | 0.51%   |
| WDC WDS120G2G0A-00JH30 120GB         | 2         | 0.51%   |
| WDC WD5000AAKX-08U6AA0 500GB         | 2         | 0.51%   |
| WDC WD10EZEX-60WN4A0 1TB             | 2         | 0.51%   |
| WDC PC SN520 SDAPNUW-128G-1014 128GB | 2         | 0.51%   |
| Toshiba DT01ACA100 1TB               | 2         | 0.51%   |
| Toshiba DT01ACA050 500GB             | 2         | 0.51%   |
| Seagate ST9500325AS 500GB            | 2         | 0.51%   |
| Seagate ST500LM000-1EJ162 500GB      | 2         | 0.51%   |
| SanDisk SSD PLUS 120GB               | 2         | 0.51%   |
| Samsung SSD 980 PRO 500GB            | 2         | 0.51%   |
| Samsung SSD 980 500GB                | 2         | 0.51%   |
| Samsung SSD 970 PRO 512GB            | 2         | 0.51%   |
| Samsung SSD 870 EVO 500GB            | 2         | 0.51%   |
| Samsung SSD 840 EVO 250GB            | 2         | 0.51%   |
| Samsung MZVLQ512HALU-00000 512GB     | 2         | 0.51%   |
| PNY CS900 240GB SSD                  | 2         | 0.51%   |
| Patriot Burst 240GB                  | 2         | 0.51%   |
| Kingston SV300S37A60G 64GB           | 2         | 0.51%   |
| Kingston SA400S37480G 480GB          | 2         | 0.51%   |
| Kingston SA400S37120G 120GB          | 2         | 0.51%   |
| Intenso SSD 120GB                    | 2         | 0.51%   |
| Hitachi HTS545050B9A300 500GB        | 2         | 0.51%   |
| HGST HTS725050A7E630 500GB           | 2         | 0.51%   |
| HGST HTS545050A7E680 500GB           | 2         | 0.51%   |
| Gigabyte GP-GSTFS31120GNTD 120GB     | 2         | 0.51%   |
| Crucial CT240BX500SSD1 240GB         | 2         | 0.51%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 43        | 62     | 30.71%  |
| Seagate             | 43        | 50     | 30.71%  |
| Toshiba             | 21        | 24     | 15%     |
| Hitachi             | 14        | 14     | 10%     |
| Samsung Electronics | 6         | 8      | 4.29%   |
| HGST                | 6         | 9      | 4.29%   |
| Maxtor              | 4         | 4      | 2.86%   |
| QUANTUM             | 1         | 1      | 0.71%   |
| Fujitsu             | 1         | 1      | 0.71%   |
| Apple               | 1         | 1      | 0.71%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 27        | 34     | 17.2%   |
| Kingston            | 23        | 23     | 14.65%  |
| SanDisk             | 19        | 19     | 12.1%   |
| Crucial             | 12        | 15     | 7.64%   |
| WDC                 | 8         | 9      | 5.1%    |
| China               | 8         | 9      | 5.1%    |
| Intel               | 5         | 5      | 3.18%   |
| Transcend           | 4         | 4      | 2.55%   |
| Patriot             | 4         | 4      | 2.55%   |
| KingSpec            | 4         | 4      | 2.55%   |
| Toshiba             | 3         | 3      | 1.91%   |
| PNY                 | 3         | 3      | 1.91%   |
| Micron Technology   | 3         | 3      | 1.91%   |
| Gigabyte Technology | 3         | 4      | 1.91%   |
| A-DATA Technology   | 3         | 3      | 1.91%   |
| SPCC                | 2         | 2      | 1.27%   |
| OCZ                 | 2         | 2      | 1.27%   |
| Intenso             | 2         | 2      | 1.27%   |
| GOODRAM             | 2         | 2      | 1.27%   |
| Verbatim            | 1         | 1      | 0.64%   |
| Vaseky              | 1         | 1      | 0.64%   |
| V-GeN               | 1         | 1      | 0.64%   |
| SK hynix            | 1         | 1      | 0.64%   |
| Plextor             | 1         | 1      | 0.64%   |
| Pioneer             | 1         | 1      | 0.64%   |
| Philips             | 1         | 1      | 0.64%   |
| Palit               | 1         | 1      | 0.64%   |
| Netac               | 1         | 1      | 0.64%   |
| LITEONIT            | 1         | 1      | 0.64%   |
| Kston               | 1         | 1      | 0.64%   |
| KIOXIA-EXCERIA      | 1         | 1      | 0.64%   |
| Kingmax             | 1         | 1      | 0.64%   |
| Goldenfir           | 1         | 1      | 0.64%   |
| EDGE                | 1         | 1      | 0.64%   |
| Dogfish             | 1         | 1      | 0.64%   |
| Biostar             | 1         | 1      | 0.64%   |
| Apple               | 1         | 1      | 0.64%   |
| Apacer              | 1         | 1      | 0.64%   |
| AMD                 | 1         | 1      | 0.64%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 132       | 170    | 42.17%  |
| HDD  | 125       | 174    | 39.94%  |
| NVMe | 56        | 64     | 17.89%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 222       | 344    | 79.86%  |
| NVMe | 56        | 64     | 20.14%  |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 190       | 251    | 72.8%   |
| 0.51-1.0   | 45        | 55     | 17.24%  |
| 1.01-2.0   | 13        | 21     | 4.98%   |
| 3.01-4.0   | 7         | 8      | 2.68%   |
| 2.01-3.0   | 3         | 6      | 1.15%   |
| 4.01-10.0  | 2         | 2      | 0.77%   |
| 10.01-20.0 | 1         | 1      | 0.38%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 1-20       | 139       | 51.48%  |
| 101-250    | 44        | 16.3%   |
| 51-100     | 34        | 12.59%  |
| 251-500    | 33        | 12.22%  |
| 501-1000   | 15        | 5.56%   |
| 21-50      | 3         | 1.11%   |
| Unknown    | 2         | 0.74%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Computers | Percent |
|---------|-----------|---------|
| 1-20    | 263       | 98.13%  |
| 21-50   | 2         | 0.75%   |
| Unknown | 2         | 0.75%   |
| 101-250 | 1         | 0.37%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                                      | Computers | Drives | Percent |
|--------------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB                  | 2         | 2      | 3.08%   |
| Seagate ST500LM000-1EJ162 500GB            | 2         | 2      | 3.08%   |
| WDC WD800JD-75MSA3 80GB                    | 1         | 1      | 1.54%   |
| WDC WD6400BPVT-22HXZT3 640GB               | 1         | 1      | 1.54%   |
| WDC WD5000AAKX-08U6AA0 500GB               | 1         | 1      | 1.54%   |
| WDC WD5000AAKX-00ERMA0 500GB               | 1         | 1      | 1.54%   |
| WDC WD30PURZ-85AKKY0 3TB                   | 1         | 1      | 1.54%   |
| WDC WD30EFRX-68EUZN0 3TB                   | 1         | 1      | 1.54%   |
| WDC WD20EZRX-00D8PB0 2TB                   | 1         | 1      | 1.54%   |
| WDC WD1600YS-01SHB1 164GB                  | 1         | 1      | 1.54%   |
| WDC WD1600AAJS-60Z0A0 160GB                | 1         | 1      | 1.54%   |
| WDC WD10JPVX-60JC3T1 1TB                   | 1         | 1      | 1.54%   |
| WDC WD10EZEX-60WN4A0 1TB                   | 1         | 1      | 1.54%   |
| WDC WD10EARS-003BB1 1TB                    | 1         | 1      | 1.54%   |
| Toshiba MQ01ABD100 1TB                     | 1         | 1      | 1.54%   |
| Toshiba MQ01ABD032 320GB                   | 1         | 1      | 1.54%   |
| Toshiba MK5059GSXP 500GB                   | 1         | 1      | 1.54%   |
| Toshiba MK3259GSXP 320GB                   | 1         | 1      | 1.54%   |
| Toshiba MK1646GSX 160GB                    | 1         | 1      | 1.54%   |
| Toshiba MK1229GSG 120GB                    | 1         | 1      | 1.54%   |
| Toshiba DT01ACA100 1TB                     | 1         | 1      | 1.54%   |
| SK hynix SC210 mSATA 256GB                 | 1         | 1      | 1.54%   |
| Silicon Motion Asgard AN1TNVMe-M.2-80 1TB  | 1         | 1      | 1.54%   |
| Seagate ST9250410AS 250GB                  | 1         | 1      | 1.54%   |
| Seagate ST9160827AS 160GB                  | 1         | 1      | 1.54%   |
| Seagate ST9160314AS 160GB                  | 1         | 1      | 1.54%   |
| Seagate ST500LM000-SSHD-8GB                | 1         | 1      | 1.54%   |
| Seagate ST500DM002-1BD142 500GB            | 1         | 1      | 1.54%   |
| Seagate ST380215AS 80GB                    | 1         | 1      | 1.54%   |
| Seagate ST3500418AS 500GB                  | 1         | 1      | 1.54%   |
| Seagate ST3500320AS 500GB                  | 1         | 1      | 1.54%   |
| Seagate ST3320620AS 320GB                  | 1         | 1      | 1.54%   |
| Seagate ST320LT020-9YG142 320GB            | 1         | 1      | 1.54%   |
| Seagate ST320LT012-9WS14C 320GB            | 1         | 2      | 1.54%   |
| Seagate ST2000DM008-2FR102 2TB             | 1         | 1      | 1.54%   |
| Seagate ST1000LM024 HN-M101MBB 1TB         | 1         | 2      | 1.54%   |
| Seagate ST1000DM010-2EP102 1TB             | 1         | 1      | 1.54%   |
| Samsung Electronics MZVL22T0HBLB-00B00 2TB | 1         | 1      | 1.54%   |
| Samsung Electronics HM321HI 320GB          | 1         | 1      | 1.54%   |
| Samsung Electronics HD103SJ 1TB            | 1         | 1      | 1.54%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 16        | 20     | 25.4%   |
| WDC                 | 12        | 12     | 19.05%  |
| Hitachi             | 8         | 8      | 12.7%   |
| Toshiba             | 7         | 7      | 11.11%  |
| HGST                | 5         | 6      | 7.94%   |
| Samsung Electronics | 3         | 3      | 4.76%   |
| Maxtor              | 3         | 3      | 4.76%   |
| Crucial             | 3         | 4      | 4.76%   |
| Kingston            | 2         | 2      | 3.17%   |
| SK hynix            | 1         | 1      | 1.59%   |
| Silicon Motion      | 1         | 1      | 1.59%   |
| Intel               | 1         | 1      | 1.59%   |
| China               | 1         | 1      | 1.59%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 16        | 20     | 30.19%  |
| WDC                 | 12        | 12     | 22.64%  |
| Hitachi             | 8         | 8      | 15.09%  |
| Toshiba             | 7         | 7      | 13.21%  |
| HGST                | 5         | 6      | 9.43%   |
| Maxtor              | 3         | 3      | 5.66%   |
| Samsung Electronics | 2         | 2      | 3.77%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 52        | 58     | 83.87%  |
| SSD  | 8         | 9      | 12.9%   |
| NVMe | 2         | 2      | 3.23%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart_bsd/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD7501AALS-00J7B0 752GB       | 1         | 1      | 25%     |
| WDC WD1600BEVT-22ZCT0 160GB       | 1         | 1      | 25%     |
| SanDisk pSSD 128GB                | 1         | 1      | 25%     |
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
| Works    | 202       | 324    | 73.99%  |
| Malfunc  | 62        | 69     | 22.71%  |
| Detected | 5         | 11     | 1.83%   |
| Failed   | 4         | 4      | 1.47%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 199       | 61.8%   |
| AMD                              | 42        | 13.04%  |
| Samsung Electronics              | 24        | 7.45%   |
| SanDisk                          | 8         | 2.48%   |
| Nvidia                           | 8         | 2.48%   |
| Kingston Technology Company      | 8         | 2.48%   |
| Silicon Motion                   | 4         | 1.24%   |
| Micron Technology                | 4         | 1.24%   |
| Marvell Technology Group         | 4         | 1.24%   |
| ASMedia Technology               | 4         | 1.24%   |
| SK hynix                         | 3         | 0.93%   |
| ADATA Technology                 | 3         | 0.93%   |
| Realtek Semiconductor            | 2         | 0.62%   |
| VIA Technologies                 | 1         | 0.31%   |
| Toshiba                          | 1         | 0.31%   |
| Silicon Integrated Systems [SiS] | 1         | 0.31%   |
| Phison Electronics               | 1         | 0.31%   |
| OCZ Technology Group             | 1         | 0.31%   |
| Micron/Crucial Technology        | 1         | 0.31%   |
| KIOXIA                           | 1         | 0.31%   |
| JMicron Technology               | 1         | 0.31%   |
| Broadcom / LSI                   | 1         | 0.31%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 20        | 5.33%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 19        | 5.07%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 19        | 5.07%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 14        | 3.73%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 13        | 3.47%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 12        | 3.2%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 12        | 3.2%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 10        | 2.67%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 9         | 2.4%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 9         | 2.4%    |
| Samsung NVMe SSD Controller 980                                                         | 8         | 2.13%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 8         | 2.13%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 8         | 2.13%   |
| AMD 500 Series Chipset SATA Controller                                                  | 8         | 2.13%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 7         | 1.87%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 7         | 1.87%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 7         | 1.87%   |
| AMD 400 Series Chipset SATA Controller                                                  | 6         | 1.6%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 5         | 1.33%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 5         | 1.33%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 4         | 1.07%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 4         | 1.07%   |
| Micron NVMe Storage Controller                                                          | 4         | 1.07%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 4         | 1.07%   |
| Intel SATA Controller [RAID mode]                                                       | 4         | 1.07%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 4         | 1.07%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 4         | 1.07%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 4         | 1.07%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 4         | 1.07%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 4         | 1.07%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 4         | 1.07%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 4         | 1.07%   |
| Unknown                                                                                 | 4         | 1.07%   |
| Nvidia MCP79 AHCI Controller                                                            | 3         | 0.8%    |
| Nvidia MCP61 SATA Controller                                                            | 3         | 0.8%    |
| Intel Volume Management Device NVMe RAID Controller                                     | 3         | 0.8%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 3         | 0.8%    |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 3         | 0.8%    |
| Intel 82801JD/DO (ICH10 Family) 4-port SATA IDE Controller                              | 3         | 0.8%    |
| Intel 82801JD/DO (ICH10 Family) 2-port SATA IDE Controller                              | 3         | 0.8%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 211       | 65.33%  |
| NVMe | 55        | 17.03%  |
| IDE  | 44        | 13.62%  |
| RAID | 11        | 3.41%   |
| SAS  | 1         | 0.31%   |
| SCSI | 1         | 0.31%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 217       | 80.97%  |
| AMD    | 51        | 19.03%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel CPU Version                             | 5         | 1.87%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 5         | 1.87%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 5         | 1.87%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 4         | 1.49%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 3         | 1.12%   |
| Intel Core i5-7400 CPU @ 3.00GHz              | 3         | 1.12%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 3         | 1.12%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 3         | 1.12%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 3         | 1.12%   |
| Intel Core i3-7100 CPU @ 3.90GHz              | 3         | 1.12%   |
| Intel Core i3-3220 CPU @ 3.30GHz              | 3         | 1.12%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 3         | 1.12%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 3         | 1.12%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 3         | 1.12%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 0.75%   |
| Intel Core i7-6700 CPU @ 3.40GHz              | 2         | 0.75%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 0.75%   |
| Intel Core i5-6500T CPU @ 2.50GHz             | 2         | 0.75%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 2         | 0.75%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 0.75%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 2         | 0.75%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 2         | 0.75%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 2         | 0.75%   |
| Intel Core i3-9100 CPU @ 3.60GHz              | 2         | 0.75%   |
| Intel Core i3-4160 CPU @ 3.60GHz              | 2         | 0.75%   |
| Intel Core i3-4130 CPU @ 3.40GHz              | 2         | 0.75%   |
| Intel Core i3-3240 CPU @ 3.40GHz              | 2         | 0.75%   |
| Intel Core i3-10100 CPU @ 3.60GHz             | 2         | 0.75%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz          | 2         | 0.75%   |
| Intel Core 2 Duo CPU T7100 @ 1.80GHz          | 2         | 0.75%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 2         | 0.75%   |
| Intel Core 2 Duo CPU P7350 @ 2.00GHz          | 2         | 0.75%   |
| Intel Core 2 Duo                              | 2         | 0.75%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 2         | 0.75%   |
| Intel Celeron CPU J1900 @ 1.99GHz             | 2         | 0.75%   |
| Intel Celeron 2955U @ 1.40GHz                 | 2         | 0.75%   |
| Intel Atom CPU N570 @ 1.66GHz                 | 2         | 0.75%   |
| Intel 12th Gen Core i5-12400                  | 2         | 0.75%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 2         | 0.75%   |
| AMD Ryzen 7 3750H with Radeon Vega Mobile Gfx | 2         | 0.75%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 71        | 26.49%  |
| Intel Core i7           | 35        | 13.06%  |
| Intel Core i3           | 28        | 10.45%  |
| Intel Celeron           | 26        | 9.7%    |
| Intel Core 2 Duo        | 18        | 6.72%   |
| Other                   | 14        | 5.22%   |
| AMD Ryzen 5             | 12        | 4.48%   |
| AMD Ryzen 7             | 10        | 3.73%   |
| Intel Xeon              | 8         | 2.99%   |
| AMD Ryzen 3             | 7         | 2.61%   |
| Intel Pentium           | 4         | 1.49%   |
| Intel Atom              | 4         | 1.49%   |
| Intel Pentium Dual-Core | 2         | 0.75%   |
| Intel Core 2 Quad       | 2         | 0.75%   |
| AMD Phenom II X4        | 2         | 0.75%   |
| AMD E                   | 2         | 0.75%   |
| AMD Athlon II X2        | 2         | 0.75%   |
| AMD A4                  | 2         | 0.75%   |
| Intel Pentium Silver    | 1         | 0.37%   |
| Intel Pentium Gold      | 1         | 0.37%   |
| Intel Pentium Dual      | 1         | 0.37%   |
| Intel Pentium 4         | 1         | 0.37%   |
| Intel Genuine           | 1         | 0.37%   |
| Intel Core i9           | 1         | 0.37%   |
| Intel Celeron D         | 1         | 0.37%   |
| AMD Ryzen Embedded      | 1         | 0.37%   |
| AMD Ryzen 9             | 1         | 0.37%   |
| AMD Phenom II X2        | 1         | 0.37%   |
| AMD Phenom II           | 1         | 0.37%   |
| AMD FX                  | 1         | 0.37%   |
| AMD E1                  | 1         | 0.37%   |
| AMD Athlon X2           | 1         | 0.37%   |
| AMD Athlon II X4        | 1         | 0.37%   |
| AMD Athlon 64           | 1         | 0.37%   |
| AMD Athlon              | 1         | 0.37%   |
| AMD A8                  | 1         | 0.37%   |
| AMD A10                 | 1         | 0.37%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 117       | 43.66%  |
| 4       | 88        | 32.84%  |
| Unknown | 19        | 7.09%   |
| 6       | 11        | 4.1%    |
| 8       | 10        | 3.73%   |
| 12      | 9         | 3.36%   |
| 16      | 6         | 2.24%   |
| 1       | 6         | 2.24%   |
| 24      | 1         | 0.37%   |
| 10      | 1         | 0.37%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 261       | 97.39%  |
| 2      | 7         | 2.61%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 124       | 46.27%  |
| 1       | 121       | 45.15%  |
| Unknown | 23        | 8.58%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 32        | 11.94%  |
| IvyBridge     | 31        | 11.57%  |
| Haswell       | 30        | 11.19%  |
| SandyBridge   | 24        | 8.96%   |
| Skylake       | 20        | 7.46%   |
| Penryn        | 17        | 6.34%   |
| Core          | 15        | 5.6%    |
| Zen+          | 14        | 5.22%   |
| Zen 3         | 10        | 3.73%   |
| Silvermont    | 8         | 2.99%   |
| K10           | 8         | 2.99%   |
| Broadwell     | 6         | 2.24%   |
| Unknown       | 6         | 2.24%   |
| Westmere      | 5         | 1.87%   |
| Goldmont plus | 5         | 1.87%   |
| CometLake     | 5         | 1.87%   |
| Bonnell       | 5         | 1.87%   |
| Zen           | 4         | 1.49%   |
| Zen 2         | 3         | 1.12%   |
| TigerLake     | 3         | 1.12%   |
| Piledriver    | 3         | 1.12%   |
| Bobcat        | 3         | 1.12%   |
| Nehalem       | 2         | 0.75%   |
| Goldmont      | 2         | 0.75%   |
| Excavator     | 2         | 0.75%   |
| NetBurst      | 1         | 0.37%   |
| K8 Hammer     | 1         | 0.37%   |
| K10 Llano     | 1         | 0.37%   |
| IceLake       | 1         | 0.37%   |
| Bulldozer     | 1         | 0.37%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 174       | 58.39%  |
| Nvidia                           | 63        | 21.14%  |
| AMD                              | 59        | 19.8%   |
| Silicon Integrated Systems [SiS] | 1         | 0.34%   |
| Matrox Electronics Systems       | 1         | 0.34%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 21        | 6.75%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 16        | 5.14%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 10        | 3.22%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 10        | 3.22%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 10        | 3.22%   |
| Intel HD Graphics 530                                                                    | 9         | 2.89%   |
| Intel HD Graphics 630                                                                    | 8         | 2.57%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 7         | 2.25%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 7         | 2.25%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 6         | 1.93%   |
| Intel UHD Graphics 620                                                                   | 6         | 1.93%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 6         | 1.93%   |
| Intel HD Graphics 5500                                                                   | 6         | 1.93%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 6         | 1.93%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 5         | 1.61%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 1.61%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 1.61%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 5         | 1.61%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 1.61%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 1.29%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 4         | 1.29%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 4         | 1.29%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                    | 3         | 0.96%   |
| Nvidia GT218 [GeForce 210]                                                               | 3         | 0.96%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 3         | 0.96%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 3         | 0.96%   |
| AMD Renoir                                                                               | 3         | 0.96%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 0.96%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 3         | 0.96%   |
| Nvidia TU116 [GeForce GTX 1660]                                                          | 2         | 0.64%   |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 0.64%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 2         | 0.64%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 0.64%   |
| Nvidia GK107 [GeForce GTX 650]                                                           | 2         | 0.64%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 2         | 0.64%   |
| Nvidia C79 [GeForce 9400M]                                                               | 2         | 0.64%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 0.64%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 0.64%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 2         | 0.64%   |
| Intel HD Graphics 620                                                                    | 2         | 0.64%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 123       | 45.56%  |
| 1 x AMD        | 45        | 16.67%  |
| 1 x Nvidia     | 44        | 16.3%   |
| 2 x Intel      | 23        | 8.52%   |
| Intel + Nvidia | 17        | 6.3%    |
| Intel + AMD    | 12        | 4.44%   |
| 2 x AMD        | 2         | 0.74%   |
| 2 x Nvidia     | 1         | 0.37%   |
| 1 x SiS        | 1         | 0.37%   |
| 1 x Matrox     | 1         | 0.37%   |
| AMD + Nvidia   | 1         | 0.37%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 223       | 82.9%   |
| Proprietary | 37        | 13.75%  |
| Unknown     | 9         | 3.35%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 205       | 76.21%  |
| 0.01-0.5   | 15        | 5.58%   |
| 3.01-4.0   | 14        | 5.2%    |
| 1.01-2.0   | 14        | 5.2%    |
| 0.51-1.0   | 10        | 3.72%   |
| 5.01-6.0   | 6         | 2.23%   |
| 7.01-8.0   | 3         | 1.12%   |
| 2.01-3.0   | 1         | 0.37%   |
| 8.01-16.0  | 1         | 0.37%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 7         | 11.29%  |
| Dell                    | 6         | 9.68%   |
| AU Optronics            | 6         | 9.68%   |
| Acer                    | 5         | 8.06%   |
| Hewlett-Packard         | 4         | 6.45%   |
| BenQ                    | 4         | 6.45%   |
| Philips                 | 3         | 4.84%   |
| Ancor Communications    | 3         | 4.84%   |
| Unknown                 | 3         | 4.84%   |
| LG Electronics          | 2         | 3.23%   |
| LG Display              | 2         | 3.23%   |
| AOC                     | 2         | 3.23%   |
| Semp Toshiba            | 1         | 1.61%   |
| PKB                     | 1         | 1.61%   |
| NEC Computers           | 1         | 1.61%   |
| Microstep               | 1         | 1.61%   |
| LG Philips              | 1         | 1.61%   |
| Lenovo                  | 1         | 1.61%   |
| InfoVision              | 1         | 1.61%   |
| Idek Iiyama             | 1         | 1.61%   |
| CPT                     | 1         | 1.61%   |
| Chimei Innolux          | 1         | 1.61%   |
| Chi Mei Optoelectronics | 1         | 1.61%   |
| BOE                     | 1         | 1.61%   |
| AUS                     | 1         | 1.61%   |
| ASUSTek Computer        | 1         | 1.61%   |
| Apple                   | 1         | 1.61%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                  | 3         | 4.84%   |
| Semp Toshiba MLE1951 STI1951 1366x768 410x230mm 18.5-inch                | 1         | 1.61%   |
| Samsung Electronics SyncMaster SAM058D 1600x900 440x250mm 19.9-inch      | 1         | 1.61%   |
| Samsung Electronics SyncMaster SAM050B 1920x1080 480x270mm 21.7-inch     | 1         | 1.61%   |
| Samsung Electronics S27F350 SAM0D22 1920x1080 600x340mm 27.2-inch        | 1         | 1.61%   |
| Samsung Electronics S24C350 SAM0A3A 1920x1080 530x300mm 24.0-inch        | 1         | 1.61%   |
| Samsung Electronics S20B300 SAM08A7 1600x900 440x250mm 19.9-inch         | 1         | 1.61%   |
| Samsung Electronics LCD Monitor SEC3541 1366x768 300x170mm 13.6-inch     | 1         | 1.61%   |
| Samsung Electronics C32HG7x SAM0E13 2560x1440 700x390mm 31.5-inch        | 1         | 1.61%   |
| PKB LCD Monitor MAE200W 1680x1050                                        | 1         | 1.61%   |
| Philips PHL 223V7 PHLC154 1920x1080 480x270mm 21.7-inch                  | 1         | 1.61%   |
| Philips PHL 221S8L PHL091C 1920x1080 480x270mm 21.7-inch                 | 1         | 1.61%   |
| Philips 150S PHL0820 1024x768 300x230mm 14.9-inch                        | 1         | 1.61%   |
| NEC Computers LCD Monitor 70GX2 1280x1024                                | 1         | 1.61%   |
| Microstep LCD Monitor MSI MAG241C 1920x1080                              | 1         | 1.61%   |
| LG Philips LP154WX4-TLCB LPL3101 1280x800 330x210mm 15.4-inch            | 1         | 1.61%   |
| LG Electronics LCD Monitor LG FULL HD 1920x1080                          | 1         | 1.61%   |
| LG Electronics LCD Monitor L1918S 1280x1024                              | 1         | 1.61%   |
| LG Display LCD Monitor LGD0555 2736x1824 260x170mm 12.2-inch             | 1         | 1.61%   |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch              | 1         | 1.61%   |
| Lenovo L24e-30 LEN66BC 1920x1080 530x300mm 24.0-inch                     | 1         | 1.61%   |
| InfoVision LCD Monitor IVO0533 1366x768 290x170mm 13.2-inch              | 1         | 1.61%   |
| Idek Iiyama LCD Monitor PL2209HD 5760x2160                               | 1         | 1.61%   |
| Hewlett-Packard ZR2740w HWP2957 2560x1440 600x340mm 27.2-inch            | 1         | 1.61%   |
| Hewlett-Packard Z24nq HWP3239 2560x1440 530x300mm 24.0-inch              | 1         | 1.61%   |
| Hewlett-Packard L1955 HWP262C 1280x1024 380x300mm 19.1-inch              | 1         | 1.61%   |
| Hewlett-Packard 27o HPN342C 1920x1080 600x340mm 27.2-inch                | 1         | 1.61%   |
| Dell U3014 DEL4081 2560x1600 640x400mm 29.7-inch                         | 1         | 1.61%   |
| Dell P2312H DEL4077 1920x1080 510x290mm 23.1-inch                        | 1         | 1.61%   |
| Dell LCD Monitor U2419HC 1920x1080                                       | 1         | 1.61%   |
| Dell LCD Monitor S2721D 2560x1440                                        | 1         | 1.61%   |
| Dell LCD Monitor E2211H 1920x1080                                        | 1         | 1.61%   |
| Dell E2220H DELF119 1920x1080 480x270mm 21.7-inch                        | 1         | 1.61%   |
| CPT LCD Monitor CPT1BC0 1024x600 220x120mm 9.9-inch                      | 1         | 1.61%   |
| Chimei Innolux LCD Monitor CMN15D7 1920x1080 340x190mm 15.3-inch         | 1         | 1.61%   |
| Chi Mei Optoelectronics LCD Monitor CMO1465 1366x768 310x180mm 14.1-inch | 1         | 1.61%   |
| BOE LCD Monitor BOE0747 1920x1080 340x190mm 15.3-inch                    | 1         | 1.61%   |
| BenQ LCD Monitor GW2780 1920x1080                                        | 1         | 1.61%   |
| BenQ LCD Monitor GW2260 1920x1080                                        | 1         | 1.61%   |
| BenQ GW2250H BNQ78BD 1920x1080 480x270mm 21.7-inch                       | 1         | 1.61%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 26        | 41.94%  |
| 1366x768 (WXGA)    | 10        | 16.13%  |
| 2560x1440 (QHD)    | 5         | 8.06%   |
| 2560x1600          | 3         | 4.84%   |
| 1600x900 (HD+)     | 3         | 4.84%   |
| 1280x1024 (SXGA)   | 3         | 4.84%   |
| 3840x2160 (4K)     | 2         | 3.23%   |
| Unknown            | 2         | 3.23%   |
| 5760x2160          | 1         | 1.61%   |
| 3840x1080          | 1         | 1.61%   |
| 2736x1824          | 1         | 1.61%   |
| 1680x1050 (WSXGA+) | 1         | 1.61%   |
| 1440x900 (WXGA+)   | 1         | 1.61%   |
| 1280x800 (WXGA)    | 1         | 1.61%   |
| 1024x768 (XGA)     | 1         | 1.61%   |
| 1024x600           | 1         | 1.61%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| Unknown | 19        | 31.67%  |
| 21      | 6         | 10%     |
| 13      | 6         | 10%     |
| 15      | 5         | 8.33%   |
| 27      | 4         | 6.67%   |
| 19      | 4         | 6.67%   |
| 24      | 3         | 5%      |
| 23      | 3         | 5%      |
| 18      | 2         | 3.33%   |
| 14      | 2         | 3.33%   |
| 31      | 1         | 1.67%   |
| 29      | 1         | 1.67%   |
| 17      | 1         | 1.67%   |
| 12      | 1         | 1.67%   |
| 11      | 1         | 1.67%   |
| 9       | 1         | 1.67%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| Unknown     | 19        | 31.67%  |
| 401-500     | 11        | 18.33%  |
| 501-600     | 10        | 16.67%  |
| 301-350     | 9         | 15%     |
| 201-300     | 7         | 11.67%  |
| 601-700     | 2         | 3.33%   |
| 351-400     | 2         | 3.33%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 32        | 55.17%  |
| Unknown | 19        | 32.76%  |
| 16/10   | 4         | 6.9%    |
| 5/4     | 1         | 1.72%   |
| 4/3     | 1         | 1.72%   |
| 3/2     | 1         | 1.72%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 19        | 31.67%  |
| 201-250        | 12        | 20%     |
| 81-90          | 5         | 8.33%   |
| 301-350        | 4         | 6.67%   |
| 151-200        | 4         | 6.67%   |
| 91-100         | 4         | 6.67%   |
| 71-80          | 2         | 3.33%   |
| 351-500        | 2         | 3.33%   |
| 141-150        | 2         | 3.33%   |
| 101-110        | 2         | 3.33%   |
| 61-70          | 1         | 1.67%   |
| 51-60          | 1         | 1.67%   |
| 41-50          | 1         | 1.67%   |
| 121-130        | 1         | 1.67%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| Unknown       | 19        | 31.67%  |
| 51-100        | 17        | 28.33%  |
| 101-120       | 14        | 23.33%  |
| 121-160       | 8         | 13.33%  |
| More than 240 | 1         | 1.67%   |
| 161-240       | 1         | 1.67%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 230       | 85.82%  |
| 0     | 29        | 10.82%  |
| 2     | 9         | 3.36%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 135       | 35.9%   |
| Intel                             | 133       | 35.37%  |
| Qualcomm Atheros                  | 46        | 12.23%  |
| Broadcom                          | 15        | 3.99%   |
| Marvell Technology Group          | 7         | 1.86%   |
| TP-Link                           | 5         | 1.33%   |
| Samsung Electronics               | 5         | 1.33%   |
| Sierra Wireless                   | 3         | 0.8%    |
| Ralink Technology                 | 3         | 0.8%    |
| Ralink                            | 3         | 0.8%    |
| Nvidia                            | 3         | 0.8%    |
| MediaTek                          | 3         | 0.8%    |
| Ericsson Business Mobile Networks | 3         | 0.8%    |
| Xiaomi                            | 2         | 0.53%   |
| Huawei Technologies               | 2         | 0.53%   |
| Edimax Technology                 | 2         | 0.53%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.27%   |
| JMicron Technology                | 1         | 0.27%   |
| Google                            | 1         | 0.27%   |
| D-Link                            | 1         | 0.27%   |
| Atheros                           | 1         | 0.27%   |
| Accton Technology                 | 1         | 0.27%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 100       | 22.12%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 22        | 4.87%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 16        | 3.54%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 11        | 2.43%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 8         | 1.77%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 8         | 1.77%   |
| Intel Wireless 8265 / 8275                                              | 8         | 1.77%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 7         | 1.55%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 7         | 1.55%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 7         | 1.55%   |
| Intel Wireless 8260                                                     | 7         | 1.55%   |
| Intel Ethernet Controller I225-V                                        | 7         | 1.55%   |
| Intel Wireless 7265                                                     | 6         | 1.33%   |
| Intel Wireless 3165                                                     | 6         | 1.33%   |
| Intel Ethernet Connection I217-V                                        | 6         | 1.33%   |
| Intel Ethernet Connection I217-LM                                       | 6         | 1.33%   |
| Intel Ethernet Connection (2) I219-LM                                   | 6         | 1.33%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 5         | 1.11%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 5         | 1.11%   |
| Intel Wireless 7260                                                     | 5         | 1.11%   |
| Intel Wi-Fi 6 AX200                                                     | 5         | 1.11%   |
| Intel Ethernet Connection I219-LM                                       | 5         | 1.11%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 5         | 1.11%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 4         | 0.88%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 4         | 0.88%   |
| Intel 82579V Gigabit Network Connection                                 | 4         | 0.88%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 0.66%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 3         | 0.66%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 3         | 0.66%   |
| Nvidia MCP79 Ethernet                                                   | 3         | 0.66%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 3         | 0.66%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 3         | 0.66%   |
| Intel 82574L Gigabit Network Connection                                 | 3         | 0.66%   |
| Intel 82567LM Gigabit Network Connection                                | 3         | 0.66%   |
| Intel 82566MM Gigabit Network Connection                                | 3         | 0.66%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 3         | 0.66%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 3         | 0.66%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 2         | 0.44%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 0.44%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 2         | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 85        | 45.45%  |
| Qualcomm Atheros      | 39        | 20.86%  |
| Realtek Semiconductor | 31        | 16.58%  |
| Broadcom              | 12        | 6.42%   |
| TP-Link               | 5         | 2.67%   |
| Ralink Technology     | 3         | 1.6%    |
| Ralink                | 3         | 1.6%    |
| Sierra Wireless       | 2         | 1.07%   |
| MediaTek              | 2         | 1.07%   |
| Edimax Technology     | 2         | 1.07%   |
| D-Link                | 1         | 0.53%   |
| Atheros               | 1         | 0.53%   |
| Accton Technology     | 1         | 0.53%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 11        | 5.76%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 8         | 4.19%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 8         | 4.19%   |
| Intel Wireless 8265 / 8275                                              | 8         | 4.19%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 7         | 3.66%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 7         | 3.66%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 7         | 3.66%   |
| Intel Wireless 8260                                                     | 7         | 3.66%   |
| Intel Wireless 7265                                                     | 6         | 3.14%   |
| Intel Wireless 3165                                                     | 6         | 3.14%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 5         | 2.62%   |
| Intel Wireless 7260                                                     | 5         | 2.62%   |
| Intel Wi-Fi 6 AX200                                                     | 5         | 2.62%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 5         | 2.62%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 1.57%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 3         | 1.57%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 3         | 1.57%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 3         | 1.57%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 3         | 1.57%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 3         | 1.57%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 3         | 1.57%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 1.05%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 2         | 1.05%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 1.05%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                         | 2         | 1.05%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 1.05%   |
| Realtek 8811CU Wireless LAN 802.11ac USB NIC                            | 2         | 1.05%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 2         | 1.05%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 2         | 1.05%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 2         | 1.05%   |
| Intel WiFi Link 5100                                                    | 2         | 1.05%   |
| Intel Wi-Fi 6 AX201                                                     | 2         | 1.05%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 2         | 1.05%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 1.05%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 1.05%   |
| Intel Centrino Wireless-N 2230                                          | 2         | 1.05%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 1.05%   |
| Intel Alder Lake-S PCH CNVi WiFi                                        | 2         | 1.05%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2         | 1.05%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                     | 1         | 0.52%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 121       | 48.02%  |
| Intel                            | 92        | 36.51%  |
| Qualcomm Atheros                 | 12        | 4.76%   |
| Marvell Technology Group         | 7         | 2.78%   |
| Samsung Electronics              | 5         | 1.98%   |
| Broadcom                         | 5         | 1.98%   |
| Nvidia                           | 3         | 1.19%   |
| Xiaomi                           | 2         | 0.79%   |
| Huawei Technologies              | 2         | 0.79%   |
| Silicon Integrated Systems [SiS] | 1         | 0.4%    |
| MediaTek                         | 1         | 0.4%    |
| JMicron Technology               | 1         | 0.4%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 100       | 39.22%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 22        | 8.63%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 16        | 6.27%   |
| Intel Ethernet Controller I225-V                                  | 7         | 2.75%   |
| Intel Ethernet Connection I217-V                                  | 6         | 2.35%   |
| Intel Ethernet Connection I217-LM                                 | 6         | 2.35%   |
| Intel Ethernet Connection (2) I219-LM                             | 6         | 2.35%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 5         | 1.96%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 1.96%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 4         | 1.57%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 4         | 1.57%   |
| Intel 82579V Gigabit Network Connection                           | 4         | 1.57%   |
| Nvidia MCP79 Ethernet                                             | 3         | 1.18%   |
| Intel 82574L Gigabit Network Connection                           | 3         | 1.18%   |
| Intel 82567LM Gigabit Network Connection                          | 3         | 1.18%   |
| Intel 82566MM Gigabit Network Connection                          | 3         | 1.18%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.78%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 0.78%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 2         | 0.78%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 2         | 0.78%   |
| Intel I211 Gigabit Network Connection                             | 2         | 0.78%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 0.78%   |
| Intel Ethernet Connection (5) I219-LM                             | 2         | 0.78%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.78%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 0.78%   |
| Intel Ethernet Connection (17) I219-V                             | 2         | 0.78%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.78%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2         | 0.78%   |
| Intel 82567LF-3 Gigabit Network Connection                        | 2         | 0.78%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.39%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.39%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.39%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.39%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1         | 0.39%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.39%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.39%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.39%   |
| MediaTek USB Ethernet-RNDIS                                       | 1         | 0.39%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1         | 0.39%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller             | 1         | 0.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 243       | 57.31%  |
| WiFi     | 175       | 41.27%  |
| Unknown  | 5         | 1.18%   |
| Modem    | 1         | 0.24%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 163       | 67.36%  |
| WiFi     | 79        | 32.64%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 142       | 52.79%  |
| 1     | 119       | 44.24%  |
| 0     | 5         | 1.86%   |
| 3     | 3         | 1.12%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 249       | 91.54%  |
| Yes  | 23        | 8.46%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 54        | 41.86%  |
| Realtek Semiconductor           | 13        | 10.08%  |
| Qualcomm Atheros Communications | 13        | 10.08%  |
| Cambridge Silicon Radio         | 8         | 6.2%    |
| Broadcom                        | 8         | 6.2%    |
| Foxconn / Hon Hai               | 7         | 5.43%   |
| Apple                           | 6         | 4.65%   |
| IMC Networks                    | 5         | 3.88%   |
| ASUSTek Computer                | 4         | 3.1%    |
| Lite-On Technology              | 3         | 2.33%   |
| TP-Link                         | 2         | 1.55%   |
| Primax Electronics              | 1         | 0.78%   |
| Hewlett-Packard                 | 1         | 0.78%   |
| Fujitsu                         | 1         | 0.78%   |
| Dell                            | 1         | 0.78%   |
| Askey Computer                  | 1         | 0.78%   |
| Alps Electric                   | 1         | 0.78%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 31        | 24.03%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 8         | 6.2%    |
| Realtek Bluetooth Adapter                                   | 7         | 5.43%   |
| Intel AX201 Bluetooth                                       | 6         | 4.65%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 5         | 3.88%   |
| Intel Wireless-AC 3168 Bluetooth                            | 5         | 3.88%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 4         | 3.1%    |
| Intel AX200 Bluetooth                                       | 4         | 3.1%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 3         | 2.33%   |
| Apple Bluetooth Host Controller                             | 3         | 2.33%   |
| TP-Link Bluetooth 5.0 USB Adapter                           | 2         | 1.55%   |
| Realtek  Bluetooth 4.2 Adapter                              | 2         | 1.55%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 2         | 1.55%   |
| Lite-On Bluetooth USB Module                                | 2         | 1.55%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 2         | 1.55%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device             | 2         | 1.55%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth USB Device    | 2         | 1.55%   |
| ASUS BT-270 Bluetooth Adapter                               | 2         | 1.55%   |
| Apple Built-in iSight (no firmware loaded)                  | 2         | 1.55%   |
| Realtek RTL8821A Bluetooth                                  | 1         | 0.78%   |
| Realtek Bluetooth 4.2 Adapter                               | 1         | 0.78%   |
| Realtek Bluetooth 4.0 Adapter                               | 1         | 0.78%   |
| Realtek Bluetooth 4.0 + High Speed Chip                     | 1         | 0.78%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 1         | 0.78%   |
| Qualcomm Atheros Dell Wireless 1901 Bluetooth               | 1         | 0.78%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 1         | 0.78%   |
| Qualcomm Atheros Dell Wireless 1703 Bluetooth               | 1         | 0.78%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 1         | 0.78%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)             | 1         | 0.78%   |
| Primax Rocketfish RF-FLBTAD Bluetooth Adapter               | 1         | 0.78%   |
| Lite-On Qualcomm Atheros Bluetooth                          | 1         | 0.78%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 1         | 0.78%   |
| Intel AX210 Bluetooth                                       | 1         | 0.78%   |
| IMC Networks Realtek Bluetooth Adapter                      | 1         | 0.78%   |
| IMC Networks Qualcomm Atheros AR9462 Bluetooth 4.0 + HS     | 1         | 0.78%   |
| IMC Networks MediaTek Bluetooth Adapter                     | 1         | 0.78%   |
| IMC Networks Bluetooth module                               | 1         | 0.78%   |
| IMC Networks Asus Integrated Bluetooth module [AR3011]      | 1         | 0.78%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 1         | 0.78%   |
| Fujitsu Qualcomm Atheros AR9462 Bluetooth 4.0 + HS Adapter  | 1         | 0.78%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 205       | 57.75%  |
| AMD                               | 66        | 18.59%  |
| Nvidia                            | 47        | 13.24%  |
| C-Media Electronics               | 12        | 3.38%   |
| Texas Instruments                 | 5         | 1.41%   |
| Creative Labs                     | 3         | 0.85%   |
| Realtek Semiconductor             | 2         | 0.56%   |
| Generalplus Technology            | 2         | 0.56%   |
| Yamaha                            | 1         | 0.28%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.28%   |
| Razer USA                         | 1         | 0.28%   |
| Phison Electronics                | 1         | 0.28%   |
| OPPO Electronics                  | 1         | 0.28%   |
| KTMicro                           | 1         | 0.28%   |
| Hewlett-Packard                   | 1         | 0.28%   |
| GN Netcom                         | 1         | 0.28%   |
| GEMBIRD                           | 1         | 0.28%   |
| Elitegroup Computer Systems (ECS) | 1         | 0.28%   |
| Edifier Technology                | 1         | 0.28%   |
| Conexant Systems                  | 1         | 0.28%   |
| Unknown                           | 1         | 0.28%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 25        | 5.95%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 25        | 5.95%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 21        | 5%      |
| AMD Family 17h/19h HD Audio Controller                                                            | 21        | 5%      |
| Intel Sunrise Point-LP HD Audio                                                                   | 18        | 4.29%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 16        | 3.81%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 13        | 3.1%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 11        | 2.62%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 11        | 2.62%   |
| Intel 200 Series PCH HD Audio                                                                     | 11        | 2.62%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 11        | 2.62%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 8         | 1.9%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 8         | 1.9%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 7         | 1.67%   |
| Intel 8 Series HD Audio Controller                                                                | 7         | 1.67%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 6         | 1.43%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 1.43%   |
| Intel Broadwell-U Audio Controller                                                                | 6         | 1.43%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 6         | 1.43%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 6         | 1.43%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 6         | 1.43%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 5         | 1.19%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 5         | 1.19%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 5         | 1.19%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 5         | 1.19%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 5         | 1.19%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 5         | 1.19%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 5         | 1.19%   |
| AMD FCH Azalia Controller                                                                         | 5         | 1.19%   |
| Nvidia MCP79 High Definition Audio                                                                | 4         | 0.95%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 4         | 0.95%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 4         | 0.95%   |
| Nvidia MCP61 High Definition Audio                                                                | 3         | 0.71%   |
| Nvidia High Definition Audio Controller                                                           | 3         | 0.71%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 3         | 0.71%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 3         | 0.71%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 3         | 0.71%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 0.71%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 0.71%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 0.71%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 62        | 19.87%  |
| SK hynix            | 41        | 13.14%  |
| Kingston            | 39        | 12.5%   |
| Unknown             | 32        | 10.26%  |
| Micron Technology   | 21        | 6.73%   |
| Crucial             | 20        | 6.41%   |
| Corsair             | 18        | 5.77%   |
| Unknown             | 16        | 5.13%   |
| G.Skill             | 9         | 2.88%   |
| Nanya Technology    | 7         | 2.24%   |
| Ramaxel Technology  | 6         | 1.92%   |
| A-DATA Technology   | 5         | 1.6%    |
| Unknown (ABCD)      | 4         | 1.28%   |
| Smart               | 4         | 1.28%   |
| Elpida              | 4         | 1.28%   |
| Patriot             | 3         | 0.96%   |
| Transcend           | 2         | 0.64%   |
| Apacer              | 2         | 0.64%   |
| Toshiba             | 1         | 0.32%   |
| Team                | 1         | 0.32%   |
| Swissbit            | 1         | 0.32%   |
| Silicon Power       | 1         | 0.32%   |
| SHARETRONIC         | 1         | 0.32%   |
| Qumo                | 1         | 0.32%   |
| Multilaser          | 1         | 0.32%   |
| MemoWise            | 1         | 0.32%   |
| Lexar               | 1         | 0.32%   |
| Kingmax             | 1         | 0.32%   |
| Juhor               | 1         | 0.32%   |
| GOODRAM             | 1         | 0.32%   |
| Golden Empire       | 1         | 0.32%   |
| Avant               | 1         | 0.32%   |
| Atermiter           | 1         | 0.32%   |
| ASint Technology    | 1         | 0.32%   |
| AMD                 | 1         | 0.32%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                 | 16        | 4.88%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                              | 5         | 1.52%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s                  | 4         | 1.22%   |
| Unknown RAM Module 1GB SODIMM DDR2                                      | 3         | 0.91%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                   | 3         | 0.91%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s                   | 3         | 0.91%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s                   | 3         | 0.91%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s                 | 3         | 0.91%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                                    | 2         | 0.61%   |
| Unknown RAM Module 2GB DIMM 800MT/s                                     | 2         | 0.61%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                                    | 2         | 0.61%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                              | 2         | 0.61%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2133MT/s        | 2         | 0.61%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s          | 2         | 0.61%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s                  | 2         | 0.61%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB Row Of Chips DDR4 3200MT/s            | 2         | 0.61%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2133MT/s                  | 2         | 0.61%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s                   | 2         | 0.61%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s                   | 2         | 0.61%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s                   | 2         | 0.61%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2400MT/s                   | 2         | 0.61%   |
| Samsung RAM M4 70T5663QZ3-CF7 2GB SODIMM DDR 2048MT/s                   | 2         | 0.61%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s                   | 2         | 0.61%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2400MT/s                       | 2         | 0.61%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s                     | 2         | 0.61%   |
| Kingston RAM 99U5428-040.A01LF 4GB SODIMM 1333MT/s                      | 2         | 0.61%   |
| Kingston RAM 202020202020202020202020202020202020 2GB DIMM DDR2 800MT/s | 2         | 0.61%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s                 | 2         | 0.61%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s                   | 2         | 0.61%   |
| Unknown RAM Module 8GB DIMM DDR4 2667MT/s                               | 1         | 0.3%    |
| Unknown RAM Module 8GB DIMM 1333MT/s                                    | 1         | 0.3%    |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                             | 1         | 0.3%    |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s                             | 1         | 0.3%    |
| Unknown RAM Module 4GB SODIMM DDR3                                      | 1         | 0.3%    |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                               | 1         | 0.3%    |
| Unknown RAM Module 2GB SODIMM DDR3 667MT/s                              | 1         | 0.3%    |
| Unknown RAM Module 2GB SODIMM DDR3                                      | 1         | 0.3%    |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                              | 1         | 0.3%    |
| Unknown RAM Module 2GB SODIMM 667MT/s                                   | 1         | 0.3%    |
| Unknown RAM Module 2GB DIMM DDR3 1600MT/s                               | 1         | 0.3%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 113       | 42.64%  |
| DDR4    | 102       | 38.49%  |
| DDR2    | 25        | 9.43%   |
| Unknown | 13        | 4.91%   |
| LPDDR4  | 6         | 2.26%   |
| SDRAM   | 4         | 1.51%   |
| LPDDR3  | 2         | 0.75%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 142       | 53.38%  |
| DIMM         | 111       | 41.73%  |
| Row Of Chips | 5         | 1.88%   |
| Chip         | 4         | 1.5%    |
| Unknown      | 4         | 1.5%    |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 101       | 34.35%  |
| 4096  | 92        | 31.29%  |
| 2048  | 58        | 19.73%  |
| 16384 | 26        | 8.84%   |
| 1024  | 16        | 5.44%   |
| 32768 | 1         | 0.34%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 61        | 21.86%  |
| 1333    | 37        | 13.26%  |
| 2400    | 34        | 12.19%  |
| 3200    | 24        | 8.6%    |
| 2133    | 23        | 8.24%   |
| 2667    | 20        | 7.17%   |
| 667     | 17        | 6.09%   |
| 800     | 11        | 3.94%   |
| 1067    | 9         | 3.23%   |
| 1334    | 7         | 2.51%   |
| Unknown | 7         | 2.51%   |
| 1867    | 5         | 1.79%   |
| 3600    | 3         | 1.08%   |
| 2666    | 3         | 1.08%   |
| 1066    | 3         | 1.08%   |
| 3733    | 2         | 0.72%   |
| 3000    | 2         | 0.72%   |
| 2048    | 2         | 0.72%   |
| 533     | 2         | 0.72%   |
| 400     | 2         | 0.72%   |
| 4400    | 1         | 0.36%   |
| 3333    | 1         | 0.36%   |
| 1866    | 1         | 0.36%   |
| 1639    | 1         | 0.36%   |
| 1200    | 1         | 0.36%   |

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
| Chicony Electronics                    | 26        | 25.24%  |
| Bison Electronics                      | 13        | 12.62%  |
| Microdia                               | 11        | 10.68%  |
| Sunplus Innovation Technology          | 8         | 7.77%   |
| Realtek Semiconductor                  | 6         | 5.83%   |
| IMC Networks                           | 6         | 5.83%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 3.88%   |
| Silicon Motion                         | 3         | 2.91%   |
| Logitech                               | 3         | 2.91%   |
| Lite-On Technology                     | 3         | 2.91%   |
| Syntek                                 | 2         | 1.94%   |
| Suyin                                  | 2         | 1.94%   |
| Quanta                                 | 2         | 1.94%   |
| Lenovo                                 | 2         | 1.94%   |
| Z-Star Microelectronics                | 1         | 0.97%   |
| Y Media                                | 1         | 0.97%   |
| Trust                                  | 1         | 0.97%   |
| Supreme Electronics                    | 1         | 0.97%   |
| SHENZHEN AONI ELECTRONIC               | 1         | 0.97%   |
| Luxvisions Innotech Limited            | 1         | 0.97%   |
| Intel                                  | 1         | 0.97%   |
| Importek                               | 1         | 0.97%   |
| Genesys Logic                          | 1         | 0.97%   |
| GEMBIRD                                | 1         | 0.97%   |
| Apple                                  | 1         | 0.97%   |
| Alcor Micro                            | 1         | 0.97%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Bison Integrated Camera                                     | 8         | 7.77%   |
| Chicony Integrated Camera                                   | 6         | 5.83%   |
| Microdia Integrated_Webcam_HD                               | 5         | 4.85%   |
| Realtek Integrated_Webcam_HD                                | 4         | 3.88%   |
| Chicony Lenovo Integrated Camera (0.3MP)                    | 3         | 2.91%   |
| Sunplus Integrated_Webcam_HD                                | 2         | 1.94%   |
| Sunplus HP TrueVision HD Camera                             | 2         | 1.94%   |
| Microdia REDRAGON Live Camera Audio                         | 2         | 1.94%   |
| Lite-On Integrated Camera                                   | 2         | 1.94%   |
| Lenovo Integrated Webcam                                    | 2         | 1.94%   |
| IMC Networks Integrated Webcam                              | 2         | 1.94%   |
| Chicony USB 2.0 Camera                                      | 2         | 1.94%   |
| Chicony FJ Camera                                           | 2         | 1.94%   |
| Cheng Uei Precision Industry (Foxlink) Realtek DMFT RGB     | 2         | 1.94%   |
| Bison Lenovo EasyCamera                                     | 2         | 1.94%   |
| Z-Star Namuga 1.3M Webcam                                   | 1         | 0.97%   |
| Y Media USB Camera                                          | 1         | 0.97%   |
| Trust Trust Full HD Webcam                                  | 1         | 0.97%   |
| Syntek HP Webcam                                            | 1         | 0.97%   |
| Syntek EasyCamera                                           | 1         | 0.97%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                    | 1         | 0.97%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 0.97%   |
| Supreme Integrated Camera                                   | 1         | 0.97%   |
| Sunplus SPCA2650 AV Camera                                  | 1         | 0.97%   |
| Sunplus Integrated Camera                                   | 1         | 0.97%   |
| Sunplus HP HD Webcam [Fixed]                                | 1         | 0.97%   |
| Sunplus 1.3M HD WebCam                                      | 1         | 0.97%   |
| Silicon Motion WebCam SCX Series                            | 1         | 0.97%   |
| Silicon Motion Realtek USB 2.0 PC Camera                    | 1         | 0.97%   |
| Silicon Motion ATIV VGA Camera                              | 1         | 0.97%   |
| SHENZHEN AONI ELECTRONIC NexiGo N990 4K Camera              | 1         | 0.97%   |
| Realtek USB 2.0 PC Camera                                   | 1         | 0.97%   |
| Realtek Dell EasyCamera                                     | 1         | 0.97%   |
| Quanta Realtek PC Camera                                    | 1         | 0.97%   |
| Quanta HD WebCam                                            | 1         | 0.97%   |
| Microdia USB 2.0 Camera                                     | 1         | 0.97%   |
| Microdia Sonix USB 2.0 Camera                               | 1         | 0.97%   |
| Microdia Integrated Webcam                                  | 1         | 0.97%   |
| Microdia Dell Laptop Integrated Webcam HD                   | 1         | 0.97%   |
| Luxvisions Innotech Limited Integrated Camera               | 1         | 0.97%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 4         | 28.57%  |
| Elan Microelectronics      | 3         | 21.43%  |
| AuthenTec                  | 3         | 21.43%  |
| Upek                       | 2         | 14.29%  |
| Shenzhen Goodix Technology | 1         | 7.14%   |
| LighTuning Technology      | 1         | 7.14%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Elan Fingerprint Sensor                                | 3         | 21.43%  |
| Validity Sensors Synaptics WBDI                        | 2         | 14.29%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 2         | 14.29%  |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 7.14%   |
| Validity Sensors Fingerprint scanner                   | 1         | 7.14%   |
| Shenzhen Goodix Fingerprint Reader SGX                 | 1         | 7.14%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 7.14%   |
| AuthenTec AES2810                                      | 1         | 7.14%   |
| AuthenTec AES2660                                      | 1         | 7.14%   |
| AuthenTec AES1660                                      | 1         | 7.14%   |

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
| 1     | 131       | 48.7%   |
| 0     | 66        | 24.54%  |
| 2     | 56        | 20.82%  |
| 3     | 13        | 4.83%   |
| 4     | 3         | 1.12%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 170       | 63.2%   |
| Net/wireless             | 34        | 12.64%  |
| Card reader              | 16        | 5.95%   |
| Bluetooth                | 16        | 5.95%   |
| Fingerprint reader       | 14        | 5.2%    |
| Sound                    | 12        | 4.46%   |
| Storage                  | 4         | 1.49%   |
| Network                  | 1         | 0.37%   |
| Net/ethernet             | 1         | 0.37%   |
| Dvb card                 | 1         | 0.37%   |

