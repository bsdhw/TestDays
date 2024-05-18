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

Total: 2386

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T530 2394EE9       | Notebook    | [9bc81955aa](https://bsd-hardware.info/?probe=9bc81955aa) | May 08, 2024 |
| Lenovo        | ThinkPad T530 2394EE9       | Notebook    | [651bd2de24](https://bsd-hardware.info/?probe=651bd2de24) | May 08, 2024 |
| Acer          | Aspire R3-131T              | Notebook    | [dec4102ec0](https://bsd-hardware.info/?probe=dec4102ec0) | May 07, 2024 |
| Dell          | 0DFRFW A01                  | Desktop     | [4532391ffd](https://bsd-hardware.info/?probe=4532391ffd) | May 06, 2024 |
| Unknown       | DH61BR G32662-203           | Desktop     | [f9ebf93574](https://bsd-hardware.info/?probe=f9ebf93574) | May 06, 2024 |
| Lenovo        | ThinkPad L420 7827W27       | Notebook    | [5231c79a27](https://bsd-hardware.info/?probe=5231c79a27) | May 05, 2024 |
| Apple         | MacBook4,1                  | Notebook    | [5916d9274d](https://bsd-hardware.info/?probe=5916d9274d) | May 05, 2024 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [d87059c342](https://bsd-hardware.info/?probe=d87059c342) | May 04, 2024 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [35ab248dd4](https://bsd-hardware.info/?probe=35ab248dd4) | May 04, 2024 |
| Apple         | MacBookPro5,5               | Notebook    | [ffd31a143f](https://bsd-hardware.info/?probe=ffd31a143f) | May 04, 2024 |
| MSI           | GE75 Raider 10SFS           | Notebook    | [227924f274](https://bsd-hardware.info/?probe=227924f274) | May 03, 2024 |
| Shenzhen M... | PHBRC                       | Mini pc     | [f657134100](https://bsd-hardware.info/?probe=f657134100) | Apr 30, 2024 |
| Lenovo        | Legion Y7000P 81HC          | Notebook    | [3dff76a9dd](https://bsd-hardware.info/?probe=3dff76a9dd) | Apr 27, 2024 |
| ASUSTek       | P5N32-E SLI                 | Desktop     | [52ac87d342](https://bsd-hardware.info/?probe=52ac87d342) | Apr 27, 2024 |
| Apple         | MacBookAir4,1               | Notebook    | [a6e153110d](https://bsd-hardware.info/?probe=a6e153110d) | Apr 22, 2024 |
| Lenovo        | B51-30 80LK                 | Notebook    | [c1435ee19d](https://bsd-hardware.info/?probe=c1435ee19d) | Apr 21, 2024 |
| HP            | OMEN by Laptop              | Notebook    | [e2bce481c8](https://bsd-hardware.info/?probe=e2bce481c8) | Apr 21, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [6778d6844d](https://bsd-hardware.info/?probe=6778d6844d) | Apr 17, 2024 |
| LG Electro... | 17Z90Q-K.AAC7U1             | Notebook    | [8e3f536127](https://bsd-hardware.info/?probe=8e3f536127) | Apr 16, 2024 |
| Dell          | 0NW6H5 A00                  | Desktop     | [256e25b666](https://bsd-hardware.info/?probe=256e25b666) | Apr 16, 2024 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [0de254980a](https://bsd-hardware.info/?probe=0de254980a) | Apr 16, 2024 |
| Wistron       | ProLiant ML110 G6           | Desktop     | [6ad215125a](https://bsd-hardware.info/?probe=6ad215125a) | Apr 14, 2024 |
| ASUSTek       | VivoBook S14 X430UA         | Notebook    | [12764b3dba](https://bsd-hardware.info/?probe=12764b3dba) | Apr 14, 2024 |
| MAXSUN        | MS-Challenger B450M         | Desktop     | [e3d38c06bf](https://bsd-hardware.info/?probe=e3d38c06bf) | Apr 13, 2024 |
| ASUSTek       | N76VZ                       | Notebook    | [c1af06bf99](https://bsd-hardware.info/?probe=c1af06bf99) | Apr 12, 2024 |
| Acer          | Aspire A314-35              | Notebook    | [6d4fa8616c](https://bsd-hardware.info/?probe=6d4fa8616c) | Apr 09, 2024 |
| MSI           | B360M BAZOOKA               | Desktop     | [af945cd1ad](https://bsd-hardware.info/?probe=af945cd1ad) | Apr 09, 2024 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [227f0ffb18](https://bsd-hardware.info/?probe=227f0ffb18) | Apr 09, 2024 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [426677818b](https://bsd-hardware.info/?probe=426677818b) | Apr 07, 2024 |
| Gigabyte      | B85M-D3H                    | Desktop     | [3f85beaa54](https://bsd-hardware.info/?probe=3f85beaa54) | Apr 05, 2024 |
| HP            | 8056                        | Desktop     | [a9e956a80b](https://bsd-hardware.info/?probe=a9e956a80b) | Apr 05, 2024 |
| F-Plus Mob... | FLAPTOP r                   | Notebook    | [21768f1b7a](https://bsd-hardware.info/?probe=21768f1b7a) | Apr 04, 2024 |
| Acer          | Aspire V5-431               | Notebook    | [9abe9b5007](https://bsd-hardware.info/?probe=9abe9b5007) | Apr 03, 2024 |
| Dell          | 06HR05 A00                  | Desktop     | [9505b5cf4f](https://bsd-hardware.info/?probe=9505b5cf4f) | Apr 02, 2024 |
| Lenovo        | ThinkPad W530 2447GH2       | Notebook    | [0cb3f41765](https://bsd-hardware.info/?probe=0cb3f41765) | Apr 01, 2024 |
| Apple         | MacBookAir3,1               | Notebook    | [b6dc892e24](https://bsd-hardware.info/?probe=b6dc892e24) | Mar 31, 2024 |
| Apple         | MacBookAir3,1               | Notebook    | [4a80e4b570](https://bsd-hardware.info/?probe=4a80e4b570) | Mar 31, 2024 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [b46f6ead5d](https://bsd-hardware.info/?probe=b46f6ead5d) | Mar 28, 2024 |
| Lenovo        | N22 80S6                    | Notebook    | [7f8b876a83](https://bsd-hardware.info/?probe=7f8b876a83) | Mar 26, 2024 |
| Gigabyte      | H55M-USB3                   | Desktop     | [748ef69c9f](https://bsd-hardware.info/?probe=748ef69c9f) | Mar 25, 2024 |
| Lenovo        | G510 20238                  | Notebook    | [faf771068a](https://bsd-hardware.info/?probe=faf771068a) | Mar 25, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [0fbac8264b](https://bsd-hardware.info/?probe=0fbac8264b) | Mar 23, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [25a92fc367](https://bsd-hardware.info/?probe=25a92fc367) | Mar 22, 2024 |
| HP            | 2B34                        | Desktop     | [850e6bf958](https://bsd-hardware.info/?probe=850e6bf958) | Mar 20, 2024 |
| ASUSTek       | X550CA                      | Notebook    | [ff92192d22](https://bsd-hardware.info/?probe=ff92192d22) | Mar 19, 2024 |
| HP            | 2B5E                        | Desktop     | [35b1572267](https://bsd-hardware.info/?probe=35b1572267) | Mar 17, 2024 |
| HP            | EliteBook 8470p             | Notebook    | [51841c9dfd](https://bsd-hardware.info/?probe=51841c9dfd) | Mar 17, 2024 |
| Lenovo        | 310B SDK0J40697 WIN 3305... | Mini pc     | [8bcd2d01e2](https://bsd-hardware.info/?probe=8bcd2d01e2) | Mar 16, 2024 |
| HP            | 21D0                        | Desktop     | [7ca5d182a1](https://bsd-hardware.info/?probe=7ca5d182a1) | Mar 16, 2024 |
| HC Technol... | HCAR5000-MI                 | Desktop     | [2e83945861](https://bsd-hardware.info/?probe=2e83945861) | Mar 16, 2024 |
| Apple         | MacBookPro11,1              | Notebook    | [58369a2ff3](https://bsd-hardware.info/?probe=58369a2ff3) | Mar 16, 2024 |
| Lenovo        | G580 20150                  | Notebook    | [1a072e681a](https://bsd-hardware.info/?probe=1a072e681a) | Mar 15, 2024 |
| Lenovo        | ThinkPad X220 429147U       | Notebook    | [0644799933](https://bsd-hardware.info/?probe=0644799933) | Mar 15, 2024 |
| HP            | dx2480 MT(FN868PA)          | Desktop     | [d700a91a81](https://bsd-hardware.info/?probe=d700a91a81) | Mar 14, 2024 |
| HP            | 21D0                        | Desktop     | [69b7737f88](https://bsd-hardware.info/?probe=69b7737f88) | Mar 12, 2024 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [6741cefeb7](https://bsd-hardware.info/?probe=6741cefeb7) | Mar 12, 2024 |
| ASUSTek       | PRIME J3355I-C              | Desktop     | [0b1cea4778](https://bsd-hardware.info/?probe=0b1cea4778) | Mar 12, 2024 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [fd60868096](https://bsd-hardware.info/?probe=fd60868096) | Mar 10, 2024 |
| Dell          | Latitude E6220              | Notebook    | [5a42aa442f](https://bsd-hardware.info/?probe=5a42aa442f) | Mar 09, 2024 |
| Maibenben     | MaiBook X series            | Notebook    | [2a58491971](https://bsd-hardware.info/?probe=2a58491971) | Mar 03, 2024 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [3653895b8e](https://bsd-hardware.info/?probe=3653895b8e) | Mar 03, 2024 |
| Dell          | 07F37C A00                  | Desktop     | [53928dbf53](https://bsd-hardware.info/?probe=53928dbf53) | Mar 03, 2024 |
| Acer          | Aspire A715-75G             | Notebook    | [415aa43c5c](https://bsd-hardware.info/?probe=415aa43c5c) | Mar 02, 2024 |
| ASUSTek       | X550EA                      | Notebook    | [42b10a3b6a](https://bsd-hardware.info/?probe=42b10a3b6a) | Mar 01, 2024 |
| Gigabyte      | H81M-D3H                    | Desktop     | [798bfe44fe](https://bsd-hardware.info/?probe=798bfe44fe) | Feb 29, 2024 |
| Gigabyte      | P35-DS3                     | Desktop     | [d877d925e1](https://bsd-hardware.info/?probe=d877d925e1) | Feb 28, 2024 |
| Itautec       | Infoway                     | Notebook    | [35399f6e75](https://bsd-hardware.info/?probe=35399f6e75) | Feb 28, 2024 |
| Trigkey       | S5 V2.0                     | Mini pc     | [ec927cc965](https://bsd-hardware.info/?probe=ec927cc965) | Feb 27, 2024 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [9c88473675](https://bsd-hardware.info/?probe=9c88473675) | Feb 27, 2024 |
| Gigabyte      | P35-DS3                     | Desktop     | [dd8beb7c03](https://bsd-hardware.info/?probe=dd8beb7c03) | Feb 27, 2024 |
| Roqos         | Core RC10                   | Desktop     | [5aeeba64ff](https://bsd-hardware.info/?probe=5aeeba64ff) | Feb 26, 2024 |
| HP            | 213D A01                    | Desktop     | [eef6db0d05](https://bsd-hardware.info/?probe=eef6db0d05) | Feb 26, 2024 |
| Dell          | 0G261D A00                  | Desktop     | [34a8d8ab2f](https://bsd-hardware.info/?probe=34a8d8ab2f) | Feb 25, 2024 |
| ASUSTek       | X550EA                      | Notebook    | [a49aa7d3d8](https://bsd-hardware.info/?probe=a49aa7d3d8) | Feb 24, 2024 |
| Lenovo        | ThinkPad X220 4290KV8       | Notebook    | [9bc55d7f8a](https://bsd-hardware.info/?probe=9bc55d7f8a) | Feb 23, 2024 |
| Gigabyte      | B85-HD3                     | Desktop     | [49b226f804](https://bsd-hardware.info/?probe=49b226f804) | Feb 23, 2024 |
| Lenovo        | XiaoXinAir 14+ ACN 2021 ... | Notebook    | [5702ec8e8e](https://bsd-hardware.info/?probe=5702ec8e8e) | Feb 22, 2024 |
| HP            | 802E                        | Desktop     | [6ef690a057](https://bsd-hardware.info/?probe=6ef690a057) | Feb 17, 2024 |
| ASUSTek       | B85M-G                      | Desktop     | [0fc891ba64](https://bsd-hardware.info/?probe=0fc891ba64) | Feb 17, 2024 |
| ASRock        | B360M Xtreme                | Desktop     | [e84af03816](https://bsd-hardware.info/?probe=e84af03816) | Feb 16, 2024 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [afe2427e9d](https://bsd-hardware.info/?probe=afe2427e9d) | Feb 15, 2024 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [191c41587b](https://bsd-hardware.info/?probe=191c41587b) | Feb 12, 2024 |
| Notebook      | N960Kx                      | Notebook    | [4e83c12f96](https://bsd-hardware.info/?probe=4e83c12f96) | Feb 12, 2024 |
| Lenovo        | Yoga 900S-12ISK 80ML        | Notebook    | [47f57b0893](https://bsd-hardware.info/?probe=47f57b0893) | Feb 11, 2024 |
| Lenovo        | Yoga 900S-12ISK 80ML        | Notebook    | [5315513827](https://bsd-hardware.info/?probe=5315513827) | Feb 11, 2024 |
| Gigabyte      | H170-D3HP-CF                | Desktop     | [32822eef4c](https://bsd-hardware.info/?probe=32822eef4c) | Feb 11, 2024 |
| Gigabyte      | X299 AORUS Gaming-CF        | Desktop     | [47e91ddd92](https://bsd-hardware.info/?probe=47e91ddd92) | Feb 08, 2024 |
| Lenovo        | ThinkPad T480 20L6SDA400    | Notebook    | [4934e88205](https://bsd-hardware.info/?probe=4934e88205) | Feb 07, 2024 |
| Lenovo        | 30FD SDK0J40705 WIN 3425... | Desktop     | [87313cc66c](https://bsd-hardware.info/?probe=87313cc66c) | Feb 07, 2024 |
| Intel         | STK1AW32SC H91596-303       | Desktop     | [14fcea4fb9](https://bsd-hardware.info/?probe=14fcea4fb9) | Feb 06, 2024 |
| Gigabyte      | Z68X-UD3H-B3                | Desktop     | [a2c1b1addb](https://bsd-hardware.info/?probe=a2c1b1addb) | Feb 06, 2024 |
| ASUSTek       | K52F                        | Notebook    | [bc31c4707c](https://bsd-hardware.info/?probe=bc31c4707c) | Feb 04, 2024 |
| Panasonic     | CF-52PGNBX2M                | Notebook    | [401aeae642](https://bsd-hardware.info/?probe=401aeae642) | Feb 03, 2024 |
| ASUSTek       | F8Vr                        | Notebook    | [2f3b6a6089](https://bsd-hardware.info/?probe=2f3b6a6089) | Feb 03, 2024 |
| ASUSTek       | K52F                        | Notebook    | [9022031518](https://bsd-hardware.info/?probe=9022031518) | Feb 03, 2024 |
| ASUSTek       | Z97M-PLUS/BR                | Desktop     | [cb6b8e5aef](https://bsd-hardware.info/?probe=cb6b8e5aef) | Feb 02, 2024 |
| Dell          | XPS 15 9530                 | Notebook    | [f9481e59b6](https://bsd-hardware.info/?probe=f9481e59b6) | Feb 01, 2024 |
| Lenovo        | V14 G2 ITL 82NM             | Notebook    | [952fa413fe](https://bsd-hardware.info/?probe=952fa413fe) | Feb 01, 2024 |
| ASUSTek       | P5E3 PRO                    | Desktop     | [354299e930](https://bsd-hardware.info/?probe=354299e930) | Feb 01, 2024 |
| ASUSTek       | K50IJ                       | Notebook    | [b5cc2ab7ff](https://bsd-hardware.info/?probe=b5cc2ab7ff) | Jan 31, 2024 |
| ASUSTek       | K50IJ                       | Notebook    | [a952b43f14](https://bsd-hardware.info/?probe=a952b43f14) | Jan 31, 2024 |
| Lenovo        | V14 G2 ITL 82NM             | Notebook    | [b66edf2033](https://bsd-hardware.info/?probe=b66edf2033) | Jan 31, 2024 |
| ASUSTek       | A68HM-K                     | Desktop     | [f321ac1114](https://bsd-hardware.info/?probe=f321ac1114) | Jan 31, 2024 |
| Fujitsu       | LIFEBOOK LH772              | Notebook    | [afe4fb6608](https://bsd-hardware.info/?probe=afe4fb6608) | Jan 30, 2024 |
| Fujitsu       | LIFEBOOK LH772              | Notebook    | [491823db1e](https://bsd-hardware.info/?probe=491823db1e) | Jan 30, 2024 |
| HP            | OMEN by Laptop 17-ck0xxx    | Notebook    | [8cad8e084d](https://bsd-hardware.info/?probe=8cad8e084d) | Jan 28, 2024 |
| Lenovo        | ThinkPad T460 20FMS1VA1D    | Notebook    | [03d11c45e9](https://bsd-hardware.info/?probe=03d11c45e9) | Jan 28, 2024 |
| Acer          | Nitro AN515-54              | Notebook    | [94f04895fe](https://bsd-hardware.info/?probe=94f04895fe) | Jan 27, 2024 |
| HP            | Pavilion x360 2-in-1 Lap... | Convertible | [f0db40d2f4](https://bsd-hardware.info/?probe=f0db40d2f4) | Jan 24, 2024 |
| Dell          | Precision M4700             | Notebook    | [05a9a26c16](https://bsd-hardware.info/?probe=05a9a26c16) | Jan 24, 2024 |
| Acer          | Nitro AN515-54              | Notebook    | [28539d7eb4](https://bsd-hardware.info/?probe=28539d7eb4) | Jan 24, 2024 |
| Acer          | TravelMate B115-M           | Notebook    | [d7a78aa2cf](https://bsd-hardware.info/?probe=d7a78aa2cf) | Jan 22, 2024 |
| Apple         | MacBookAir4,1               | Notebook    | [f51a396e5e](https://bsd-hardware.info/?probe=f51a396e5e) | Jan 21, 2024 |
| Dell          | 0YNVJG A01                  | Desktop     | [7c9f213d88](https://bsd-hardware.info/?probe=7c9f213d88) | Jan 20, 2024 |
| MSI           | PRO Z790-A WIFI DDR4        | Desktop     | [e52e1e182e](https://bsd-hardware.info/?probe=e52e1e182e) | Jan 20, 2024 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [2065609a0c](https://bsd-hardware.info/?probe=2065609a0c) | Jan 19, 2024 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [62abffe402](https://bsd-hardware.info/?probe=62abffe402) | Jan 19, 2024 |
| Dell          | Latitude 7480               | Notebook    | [d9b4d836e7](https://bsd-hardware.info/?probe=d9b4d836e7) | Jan 17, 2024 |
| HP            | Mini 210-1000               | Notebook    | [f25c646418](https://bsd-hardware.info/?probe=f25c646418) | Jan 16, 2024 |
| Star Labs     | StarBook                    | Notebook    | [1e903acb93](https://bsd-hardware.info/?probe=1e903acb93) | Jan 16, 2024 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | Desktop     | [5642aa5018](https://bsd-hardware.info/?probe=5642aa5018) | Jan 16, 2024 |
| HP            | Mini 210-1000               | Notebook    | [fb086c3baa](https://bsd-hardware.info/?probe=fb086c3baa) | Jan 15, 2024 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [20090cb5c6](https://bsd-hardware.info/?probe=20090cb5c6) | Jan 15, 2024 |
| HP            | Pavilion x360 2-in-1 Lap... | Convertible | [b56a8b041a](https://bsd-hardware.info/?probe=b56a8b041a) | Jan 14, 2024 |
| Apple         | MacBookAir4,1               | Notebook    | [b9653bc7d3](https://bsd-hardware.info/?probe=b9653bc7d3) | Jan 14, 2024 |
| ASUSTek       | TUF Gaming H470-PRO         | Desktop     | [e0d9f347e9](https://bsd-hardware.info/?probe=e0d9f347e9) | Jan 13, 2024 |
| ASRock        | AB350 Pro4                  | Desktop     | [b2f960c437](https://bsd-hardware.info/?probe=b2f960c437) | Jan 11, 2024 |
| Unknown       | Unknown                     | Desktop     | [514b270501](https://bsd-hardware.info/?probe=514b270501) | Jan 10, 2024 |
| Dell          | Inspiron 14-3452            | Notebook    | [47ac3f7eaa](https://bsd-hardware.info/?probe=47ac3f7eaa) | Jan 09, 2024 |
| HP            | Compaq 6510b (GM108UC#AB... | Notebook    | [7ed7da2383](https://bsd-hardware.info/?probe=7ed7da2383) | Jan 08, 2024 |
| Lenovo        | ThinkPad L450 20DSS1S402    | Notebook    | [40b8a056f7](https://bsd-hardware.info/?probe=40b8a056f7) | Jan 07, 2024 |
| Dell          | XPS 15 9530                 | Notebook    | [13f09671ce](https://bsd-hardware.info/?probe=13f09671ce) | Jan 07, 2024 |
| ASUSTek       | X551MA                      | Notebook    | [91eda59c82](https://bsd-hardware.info/?probe=91eda59c82) | Jan 06, 2024 |
| Roqos         | Core RC10                   | Desktop     | [7561797db6](https://bsd-hardware.info/?probe=7561797db6) | Jan 06, 2024 |
| HP            | 1905                        | Desktop     | [9e67ddf10b](https://bsd-hardware.info/?probe=9e67ddf10b) | Jan 05, 2024 |
| Unknown       | Unknown                     | Desktop     | [9fed9e1dd9](https://bsd-hardware.info/?probe=9fed9e1dd9) | Jan 04, 2024 |
| Lenovo        | ThinkPad X250 20CMS01M00    | Notebook    | [1f52525bb9](https://bsd-hardware.info/?probe=1f52525bb9) | Jan 04, 2024 |
| ASUSTek       | X555LB                      | Notebook    | [45a80466a3](https://bsd-hardware.info/?probe=45a80466a3) | Jan 04, 2024 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [4b0c5d65b0](https://bsd-hardware.info/?probe=4b0c5d65b0) | Jan 02, 2024 |
| Samsung       | R510/P510                   | Notebook    | [920e7e2d14](https://bsd-hardware.info/?probe=920e7e2d14) | Dec 31, 2023 |
| MSI           | Z270-A PRO                  | Desktop     | [2f2f406aa3](https://bsd-hardware.info/?probe=2f2f406aa3) | Dec 31, 2023 |
| Dell          | Vostro V130                 | Notebook    | [44e78243c2](https://bsd-hardware.info/?probe=44e78243c2) | Dec 30, 2023 |
| MSI           | MPG Z690 CARBON WIFI        | Desktop     | [0e31087126](https://bsd-hardware.info/?probe=0e31087126) | Dec 30, 2023 |
| Acer          | Aspire E5-574               | Notebook    | [8b71e16af3](https://bsd-hardware.info/?probe=8b71e16af3) | Dec 27, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [d08712b71d](https://bsd-hardware.info/?probe=d08712b71d) | Dec 26, 2023 |
| Lenovo        | ThinkPad X131e 33672T9      | Notebook    | [93f964da45](https://bsd-hardware.info/?probe=93f964da45) | Dec 25, 2023 |
| AMI           | Intel                       | Notebook    | [df557e3915](https://bsd-hardware.info/?probe=df557e3915) | Dec 25, 2023 |
| Lenovo        | ThinkPad X250 20CLS8Q601    | Notebook    | [2c52684baa](https://bsd-hardware.info/?probe=2c52684baa) | Dec 25, 2023 |
| eMachines     | eM350                       | Notebook    | [00d1d0c359](https://bsd-hardware.info/?probe=00d1d0c359) | Dec 23, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [7ca1ae0c93](https://bsd-hardware.info/?probe=7ca1ae0c93) | Dec 23, 2023 |
| Unknown       | Unknown                     | Desktop     | [84a9704b97](https://bsd-hardware.info/?probe=84a9704b97) | Dec 21, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [2ba0ee6609](https://bsd-hardware.info/?probe=2ba0ee6609) | Dec 21, 2023 |
| Intel         | NUC11ATBPE M49844-303       | Mini pc     | [1e083d16ac](https://bsd-hardware.info/?probe=1e083d16ac) | Dec 21, 2023 |
| Gigabyte      | F2A85X-UP4                  | Desktop     | [bd9dd3d647](https://bsd-hardware.info/?probe=bd9dd3d647) | Dec 19, 2023 |
| HP            | 212B                        | Desktop     | [d110ce488b](https://bsd-hardware.info/?probe=d110ce488b) | Dec 18, 2023 |
| Lenovo        | ThinkPad X220 4291H77       | Notebook    | [2fe3ff7e06](https://bsd-hardware.info/?probe=2fe3ff7e06) | Dec 18, 2023 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [ba2cad0d55](https://bsd-hardware.info/?probe=ba2cad0d55) | Dec 18, 2023 |
| HP            | 212B                        | Desktop     | [1737c1241b](https://bsd-hardware.info/?probe=1737c1241b) | Dec 16, 2023 |
| Acer          | V5-131                      | Notebook    | [76e88ee5df](https://bsd-hardware.info/?probe=76e88ee5df) | Dec 14, 2023 |
| Pegatron      | 2AF0                        | Desktop     | [61aea25165](https://bsd-hardware.info/?probe=61aea25165) | Dec 10, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [2b600594af](https://bsd-hardware.info/?probe=2b600594af) | Dec 07, 2023 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | Notebook    | [b5bbc08efe](https://bsd-hardware.info/?probe=b5bbc08efe) | Dec 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [7a1ab6fd47](https://bsd-hardware.info/?probe=7a1ab6fd47) | Dec 06, 2023 |
| ASUSTek       | H81M-C                      | Desktop     | [177ffa702e](https://bsd-hardware.info/?probe=177ffa702e) | Dec 03, 2023 |
| Lenovo        | ThinkCentre M70e 0828W17    | Desktop     | [02c7f33254](https://bsd-hardware.info/?probe=02c7f33254) | Dec 03, 2023 |
| Intel         | H81U                        | Notebook    | [b74cca91df](https://bsd-hardware.info/?probe=b74cca91df) | Dec 01, 2023 |
| Samsung       | N150P/N210P/N220P           | Notebook    | [b394563830](https://bsd-hardware.info/?probe=b394563830) | Nov 30, 2023 |
| Intel         | DH67CL AAG10212-206         | Desktop     | [818a6b3f2c](https://bsd-hardware.info/?probe=818a6b3f2c) | Nov 29, 2023 |
| Lenovo        | Yoga 2 Pro 20266            | Notebook    | [1096dc8160](https://bsd-hardware.info/?probe=1096dc8160) | Nov 27, 2023 |
| Lenovo        | Yoga 2 Pro 20266            | Notebook    | [1bfc57a019](https://bsd-hardware.info/?probe=1bfc57a019) | Nov 27, 2023 |
| MSI           | B350 PC MATE                | Desktop     | [87351f500b](https://bsd-hardware.info/?probe=87351f500b) | Nov 26, 2023 |
| Gigabyte      | F2A85X-UP4                  | Desktop     | [bf23ac0d57](https://bsd-hardware.info/?probe=bf23ac0d57) | Nov 26, 2023 |
| Dell          | Latitude E5540              | Notebook    | [d12acc0425](https://bsd-hardware.info/?probe=d12acc0425) | Nov 25, 2023 |
| Lenovo        | IdeaPad S145-14AST 81ST     | Notebook    | [a44d6afa76](https://bsd-hardware.info/?probe=a44d6afa76) | Nov 24, 2023 |
| Lenovo        | IdeaPad S145-14AST 81ST     | Notebook    | [b67644f2b3](https://bsd-hardware.info/?probe=b67644f2b3) | Nov 24, 2023 |
| Acer          | Aspire E5-574               | Notebook    | [b11a972371](https://bsd-hardware.info/?probe=b11a972371) | Nov 24, 2023 |
| ASRock        | X399 Professional Gaming    | Desktop     | [9c9645e87a](https://bsd-hardware.info/?probe=9c9645e87a) | Nov 23, 2023 |
| Dell          | 00P8G1 A00                  | All in one  | [daca9b37fd](https://bsd-hardware.info/?probe=daca9b37fd) | Nov 23, 2023 |
| Gigabyte      | X399 DESIGNARE EX-CF        | Desktop     | [81faa8cbd2](https://bsd-hardware.info/?probe=81faa8cbd2) | Nov 22, 2023 |
| Fujitsu       | D3313-A1 S26361-D3313-A1    | Desktop     | [9f6d0c8539](https://bsd-hardware.info/?probe=9f6d0c8539) | Nov 22, 2023 |
| Acer          | Aspire E5-574               | Notebook    | [a4eded7a52](https://bsd-hardware.info/?probe=a4eded7a52) | Nov 22, 2023 |
| HP            | Laptop 14-fq0xxx            | Notebook    | [4c5aa5c3ea](https://bsd-hardware.info/?probe=4c5aa5c3ea) | Nov 22, 2023 |
| Toshiba       | Satellite C40-A             | Notebook    | [0c545b75e9](https://bsd-hardware.info/?probe=0c545b75e9) | Nov 21, 2023 |
| ATOPNUC       | MA90                        | Mini pc     | [9f690594a0](https://bsd-hardware.info/?probe=9f690594a0) | Nov 21, 2023 |
| Toshiba       | Satellite C40-A             | Notebook    | [cecd389c82](https://bsd-hardware.info/?probe=cecd389c82) | Nov 21, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [9b3cb9cbd6](https://bsd-hardware.info/?probe=9b3cb9cbd6) | Nov 21, 2023 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [797f393ce0](https://bsd-hardware.info/?probe=797f393ce0) | Nov 19, 2023 |
| Gigabyte      | Z68X-UD5-B3                 | Desktop     | [f8fcca51ca](https://bsd-hardware.info/?probe=f8fcca51ca) | Nov 19, 2023 |
| Lenovo        | ThinkPad T60 8744HDG        | Notebook    | [fc54b10db3](https://bsd-hardware.info/?probe=fc54b10db3) | Nov 18, 2023 |
| Acer          | Aspire ES1-572              | Notebook    | [2aa8175a33](https://bsd-hardware.info/?probe=2aa8175a33) | Nov 17, 2023 |
| ASUSTek       | ROG Maximus XII APEX        | Desktop     | [204ee8891b](https://bsd-hardware.info/?probe=204ee8891b) | Nov 16, 2023 |
| Dell          | Precision 7720              | Notebook    | [65a0287ad6](https://bsd-hardware.info/?probe=65a0287ad6) | Nov 16, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [984f5f2f4b](https://bsd-hardware.info/?probe=984f5f2f4b) | Nov 16, 2023 |
| Lenovo        | ThinkPad X230 2320A5U       | Notebook    | [48f8b6a93a](https://bsd-hardware.info/?probe=48f8b6a93a) | Nov 16, 2023 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [e28d22b5ed](https://bsd-hardware.info/?probe=e28d22b5ed) | Nov 16, 2023 |
| ASRock        | A300M-STX                   | Desktop     | [e5f0053202](https://bsd-hardware.info/?probe=e5f0053202) | Nov 15, 2023 |
| Lenovo        | NOK                         | Desktop     | [6d55a75c4d](https://bsd-hardware.info/?probe=6d55a75c4d) | Nov 15, 2023 |
| Lenovo        | NOK                         | Desktop     | [52593923f0](https://bsd-hardware.info/?probe=52593923f0) | Nov 13, 2023 |
| Dell          | Inspiron 3442               | Notebook    | [3f63ee5447](https://bsd-hardware.info/?probe=3f63ee5447) | Nov 13, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [b85df96058](https://bsd-hardware.info/?probe=b85df96058) | Nov 11, 2023 |
| Lenovo        | ThinkPad E14 20RA0016RT     | Notebook    | [83b87dac52](https://bsd-hardware.info/?probe=83b87dac52) | Nov 10, 2023 |
| Gateway       | NV79                        | Notebook    | [2a7dd49956](https://bsd-hardware.info/?probe=2a7dd49956) | Nov 09, 2023 |
| Dell          | 0DPRF9 A00                  | All in one  | [6ee8baf52b](https://bsd-hardware.info/?probe=6ee8baf52b) | Nov 08, 2023 |
| Dell          | 0DPRF9 A00                  | All in one  | [abaff39583](https://bsd-hardware.info/?probe=abaff39583) | Nov 08, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [1f6c70fd78](https://bsd-hardware.info/?probe=1f6c70fd78) | Nov 07, 2023 |
| HP            | Pavilion g6                 | Notebook    | [6e2c3d13a4](https://bsd-hardware.info/?probe=6e2c3d13a4) | Nov 07, 2023 |
| Dell          | Precision 7720              | Notebook    | [45614f0ff9](https://bsd-hardware.info/?probe=45614f0ff9) | Nov 06, 2023 |
| HP            | 3031h                       | Desktop     | [a38d555974](https://bsd-hardware.info/?probe=a38d555974) | Nov 06, 2023 |
| Dell          | Inspiron N4050              | Notebook    | [9bc3c5e163](https://bsd-hardware.info/?probe=9bc3c5e163) | Nov 05, 2023 |
| Gigabyte      | B450M AORUS ELITE           | Desktop     | [e49d3f40b6](https://bsd-hardware.info/?probe=e49d3f40b6) | Nov 05, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | Desktop     | [a217880b63](https://bsd-hardware.info/?probe=a217880b63) | Nov 05, 2023 |
| Dell          | Precision 7720              | Notebook    | [ef59e0f80d](https://bsd-hardware.info/?probe=ef59e0f80d) | Nov 05, 2023 |
| Dell          | 0XCR8D A03                  | Desktop     | [cc58b2f58f](https://bsd-hardware.info/?probe=cc58b2f58f) | Nov 05, 2023 |
| Lenovo        | Z50-70 20354                | Notebook    | [641e875b3b](https://bsd-hardware.info/?probe=641e875b3b) | Nov 04, 2023 |
| Gigabyte      | B450M H                     | Desktop     | [69b57fab79](https://bsd-hardware.info/?probe=69b57fab79) | Nov 02, 2023 |
| HP            | 18E7                        | Desktop     | [a5bf30aeac](https://bsd-hardware.info/?probe=a5bf30aeac) | Nov 02, 2023 |
| Dell          | Precision 7720              | Notebook    | [cc321f8dea](https://bsd-hardware.info/?probe=cc321f8dea) | Nov 01, 2023 |
| Shuttle       | NC10U                       | Desktop     | [8a3fd4b3ee](https://bsd-hardware.info/?probe=8a3fd4b3ee) | Nov 01, 2023 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [0caf100d71](https://bsd-hardware.info/?probe=0caf100d71) | Oct 30, 2023 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [534dc363f2](https://bsd-hardware.info/?probe=534dc363f2) | Oct 30, 2023 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [7a6b4537f3](https://bsd-hardware.info/?probe=7a6b4537f3) | Oct 29, 2023 |
| HP            | Pavilion g6                 | Notebook    | [6aee98fb1a](https://bsd-hardware.info/?probe=6aee98fb1a) | Oct 29, 2023 |
| HP            | ZBook 15 G3                 | Notebook    | [74c3cbd1a3](https://bsd-hardware.info/?probe=74c3cbd1a3) | Oct 29, 2023 |
| Lenovo        | Z50-70 20354                | Notebook    | [f3d9534b2d](https://bsd-hardware.info/?probe=f3d9534b2d) | Oct 28, 2023 |
| Lenovo        | ThinkPad T520 42405FG       | Notebook    | [e6aca7e0c8](https://bsd-hardware.info/?probe=e6aca7e0c8) | Oct 28, 2023 |
| Intel         | DB75EN AAG39650-302         | Desktop     | [5d64d42233](https://bsd-hardware.info/?probe=5d64d42233) | Oct 27, 2023 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [3d6569cef5](https://bsd-hardware.info/?probe=3d6569cef5) | Oct 26, 2023 |
| Toshiba       | Unknown                     | Notebook    | [de44a16738](https://bsd-hardware.info/?probe=de44a16738) | Oct 24, 2023 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [193c3e5732](https://bsd-hardware.info/?probe=193c3e5732) | Oct 22, 2023 |
| Acer          | Aspire 5336                 | Notebook    | [ebfed0efbc](https://bsd-hardware.info/?probe=ebfed0efbc) | Oct 18, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [0ae4cee8b3](https://bsd-hardware.info/?probe=0ae4cee8b3) | Oct 17, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [5f364ec930](https://bsd-hardware.info/?probe=5f364ec930) | Oct 17, 2023 |
| Dell          | Latitude 3440               | Notebook    | [3e6826570c](https://bsd-hardware.info/?probe=3e6826570c) | Oct 16, 2023 |
| Lenovo        | ThinkPad T480 20L5000UUS    | Notebook    | [20fe904881](https://bsd-hardware.info/?probe=20fe904881) | Oct 15, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [0aa91c2a5c](https://bsd-hardware.info/?probe=0aa91c2a5c) | Oct 15, 2023 |
| Gigabyte      | Z370 AORUS Gaming 7         | Desktop     | [8b0d009cc4](https://bsd-hardware.info/?probe=8b0d009cc4) | Oct 13, 2023 |
| Acer          | Aspire ES1-571              | Notebook    | [f3036a27e5](https://bsd-hardware.info/?probe=f3036a27e5) | Oct 13, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [fbc9fe11b1](https://bsd-hardware.info/?probe=fbc9fe11b1) | Oct 13, 2023 |
| Gigabyte      | Z370 AORUS Gaming 7         | Desktop     | [bb82c13e39](https://bsd-hardware.info/?probe=bb82c13e39) | Oct 12, 2023 |
| Toshiba       | Satellite C55-A             | Notebook    | [f27ea283cf](https://bsd-hardware.info/?probe=f27ea283cf) | Oct 12, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [518658e176](https://bsd-hardware.info/?probe=518658e176) | Oct 11, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [c88d8880ea](https://bsd-hardware.info/?probe=c88d8880ea) | Oct 11, 2023 |
| Dell          | Latitude D830               | Notebook    | [4cf27e5d29](https://bsd-hardware.info/?probe=4cf27e5d29) | Oct 09, 2023 |
| HP            | 1497                        | Desktop     | [9ffee4ae55](https://bsd-hardware.info/?probe=9ffee4ae55) | Oct 09, 2023 |
| Gigabyte      | B250M-D3H-CF                | Desktop     | [02d64d7433](https://bsd-hardware.info/?probe=02d64d7433) | Oct 08, 2023 |
| Lenovo        | IdeaPad 3 17ITL6 82H9       | Notebook    | [5be3eb1296](https://bsd-hardware.info/?probe=5be3eb1296) | Oct 08, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [c646a3b663](https://bsd-hardware.info/?probe=c646a3b663) | Oct 07, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [66a1e081e6](https://bsd-hardware.info/?probe=66a1e081e6) | Oct 07, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [c25c930afa](https://bsd-hardware.info/?probe=c25c930afa) | Oct 05, 2023 |
| ASUSTek       | K73E                        | Notebook    | [ce5fcbdc3e](https://bsd-hardware.info/?probe=ce5fcbdc3e) | Oct 04, 2023 |
| ASUSTek       | PRIME B560-PLUS AC-HES      | Desktop     | [471133280c](https://bsd-hardware.info/?probe=471133280c) | Oct 03, 2023 |
| Gigabyte      | H55M-S2H                    | Desktop     | [5c6c241347](https://bsd-hardware.info/?probe=5c6c241347) | Oct 02, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [05dc7174b1](https://bsd-hardware.info/?probe=05dc7174b1) | Oct 01, 2023 |
| Gigabyte      | H55M-S2H                    | Desktop     | [14ead4227b](https://bsd-hardware.info/?probe=14ead4227b) | Oct 01, 2023 |
| Apple         | MacBookPro9,1               | Notebook    | [9b9f826560](https://bsd-hardware.info/?probe=9b9f826560) | Oct 01, 2023 |
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
| HP            | Pavilion x360 2-in-1 Lap... | Convertible | [6cd6b15a60](https://bsd-hardware.info/?probe=6cd6b15a60) | Feb 12, 2023 |
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
| helloSystem 0.8.1       | 476       | 24.26%  |
| helloSystem 0.7.0       | 450       | 22.94%  |
| helloSystem 0.8.0       | 254       | 12.95%  |
| helloSystem 0.5.0       | 245       | 12.49%  |
| helloSystem 0.4.0       | 190       | 9.68%   |
| helloSystem 0.6.0       | 139       | 7.08%   |
| helloSystem 0.9.0       | 109       | 5.56%   |
| helloSystem 0.8.2       | 68        | 3.47%   |
| helloSystem 0.3.0       | 25        | 1.27%   |
| helloSystem 13.1-p2     | 2         | 0.1%    |
| helloSystem 13.1        | 1         | 0.05%   |
| helloSystem 13.0-STABLE | 1         | 0.05%   |
| helloSystem 13.0-p11    | 1         | 0.05%   |
| helloSystem             | 1         | 0.05%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| helloSystem | 1813      | 100%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 1811      | 99.89%  |
| arm64 | 2         | 0.11%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| helloDesktop | 1793      | 98.41%  |
| GNOME        | 10        | 0.55%   |
| KDE5         | 8         | 0.44%   |
| XFCE         | 4         | 0.22%   |
| Cinnamon     | 2         | 0.11%   |
| Window Maker | 1         | 0.05%   |
| TWM          | 1         | 0.05%   |
| LXQt         | 1         | 0.05%   |
| JWM          | 1         | 0.05%   |
| IceWM        | 1         | 0.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 1813      | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SLiM    | 1807      | 99.45%  |
| SDDM    | 3         | 0.17%   |
| GDM     | 3         | 0.17%   |
| Console | 3         | 0.17%   |
| LightDM | 1         | 0.06%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 1278      | 67.98%  |
| fr_FR   | 120       | 6.38%   |
| Unknown | 111       | 5.9%    |
| en      | 92        | 4.89%   |
| ru_RU   | 46        | 2.45%   |
| de_DE   | 43        | 2.29%   |
| es_ES   | 38        | 2.02%   |
| it_IT   | 17        | 0.9%    |
| fr      | 17        | 0.9%    |
| pt_BR   | 16        | 0.85%   |
| ru      | 12        | 0.64%   |
| pl_PL   | 11        | 0.59%   |
| C       | 11        | 0.59%   |
| pt      | 9         | 0.48%   |
| es      | 9         | 0.48%   |
| zh_CN   | 7         | 0.37%   |
| de      | 7         | 0.37%   |
| nl_NL   | 5         | 0.27%   |
| jp_JP   | 4         | 0.21%   |
| en_GB   | 4         | 0.21%   |
| tr_TR   | 3         | 0.16%   |
| it      | 3         | 0.16%   |
| zh_TW   | 2         | 0.11%   |
| pl      | 2         | 0.11%   |
| nl      | 2         | 0.11%   |
| ko_KR   | 2         | 0.11%   |
| fi_FI   | 2         | 0.11%   |
| uk_UA   | 1         | 0.05%   |
| sv      | 1         | 0.05%   |
| pt_PT   | 1         | 0.05%   |
| ko      | 1         | 0.05%   |
| fi_DK   | 1         | 0.05%   |
| es_AR   | 1         | 0.05%   |
| en_UK   | 1         | 0.05%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 1710      | 93.8%   |
| BIOS | 113       | 6.2%    |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Computers | Percent |
|--------|-----------|---------|
| Zfs    | 1131      | 60.35%  |
| Cd9660 | 740       | 39.49%  |
| Ufs    | 3         | 0.16%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 1799      | 99.23%  |
| MBR  | 14        | 0.77%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 331       | 18.26%  |
| ASUSTek Computer    | 286       | 15.77%  |
| Dell                | 220       | 12.13%  |
| Hewlett-Packard     | 212       | 11.69%  |
| Gigabyte Technology | 132       | 7.28%   |
| Apple               | 83        | 4.58%   |
| Acer                | 74        | 4.08%   |
| ASRock              | 69        | 3.81%   |
| MSI                 | 60        | 3.31%   |
| Intel               | 52        | 2.87%   |
| Toshiba             | 29        | 1.6%    |
| Samsung Electronics | 25        | 1.38%   |
| Fujitsu             | 24        | 1.32%   |
| Unknown             | 17        | 0.94%   |
| Sony                | 14        | 0.77%   |
| Google              | 10        | 0.55%   |
| Biostar             | 10        | 0.55%   |
| Pegatron            | 9         | 0.5%    |
| Packard Bell        | 9         | 0.5%    |
| LG Electronics      | 7         | 0.39%   |
| Panasonic           | 6         | 0.33%   |
| Foxconn             | 6         | 0.33%   |
| Acidanthera         | 6         | 0.33%   |
| Notebook            | 5         | 0.28%   |
| Fujitsu Siemens     | 5         | 0.28%   |
| TUXEDO              | 4         | 0.22%   |
| Timi                | 4         | 0.22%   |
| Medion              | 4         | 0.22%   |
| Itautec             | 4         | 0.22%   |
| Gateway             | 4         | 0.22%   |
| AZW                 | 4         | 0.22%   |
| Star Labs           | 3         | 0.17%   |
| Shuttle             | 3         | 0.17%   |
| HUAWEI              | 3         | 0.17%   |
| eMachines           | 3         | 0.17%   |
| T-bao               | 2         | 0.11%   |
| Supermicro          | 2         | 0.11%   |
| Razer               | 2         | 0.11%   |
| Positivo            | 2         | 0.11%   |
| Microsoft           | 2         | 0.11%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Unknown                        | 24        | 1.32%   |
| ASUS All Series                | 16        | 0.88%   |
| Apple MacBook4,1               | 7         | 0.39%   |
| Apple iMac9,1                  | 7         | 0.39%   |
| HP EliteDesk 800 G2 DM 35W     | 6         | 0.33%   |
| Dell OptiPlex 9020             | 6         | 0.33%   |
| Dell Inspiron 3442             | 6         | 0.33%   |
| Apple MacPro5,1                | 6         | 0.33%   |
| Apple MacBookPro9,2            | 6         | 0.33%   |
| HP Pavilion dv6                | 5         | 0.28%   |
| Dell OptiPlex 3020             | 5         | 0.28%   |
| MSI MS-7C37                    | 4         | 0.22%   |
| Intel H61                      | 4         | 0.22%   |
| HP Compaq Elite 8300 USDT      | 4         | 0.22%   |
| HP 2000                        | 4         | 0.22%   |
| Dell OptiPlex 780              | 4         | 0.22%   |
| Dell OptiPlex 755              | 4         | 0.22%   |
| Dell OptiPlex 7010             | 4         | 0.22%   |
| Dell Latitude E6420            | 4         | 0.22%   |
| Dell Latitude E5570            | 4         | 0.22%   |
| ASUS ROG STRIX B550-F GAMING   | 4         | 0.22%   |
| ASUS M5A78L-M/USB3             | 4         | 0.22%   |
| Apple MacBookPro5,5            | 4         | 0.22%   |
| Apple MacBookAir5,1            | 4         | 0.22%   |
| Apple MacBook5,1               | 4         | 0.22%   |
| Acer Aspire ES1-533            | 4         | 0.22%   |
| MSI MS-7B86                    | 3         | 0.17%   |
| Lenovo Z50-70 20354            | 3         | 0.17%   |
| Lenovo IdeaPad 110S-11IBR 80WG | 3         | 0.17%   |
| Intel H81                      | 3         | 0.17%   |
| HP ProDesk 600 G1 SFF          | 3         | 0.17%   |
| HP Pavilion Notebook           | 3         | 0.17%   |
| HP Pavilion g6                 | 3         | 0.17%   |
| HP Notebook                    | 3         | 0.17%   |
| HP EliteDesk 800 G2 SFF        | 3         | 0.17%   |
| HP EliteBook 840 G3            | 3         | 0.17%   |
| HP Compaq Elite 8300 SFF       | 3         | 0.17%   |
| Gigabyte X570 AORUS ELITE      | 3         | 0.17%   |
| Gigabyte F2A88XM-D3H           | 3         | 0.17%   |
| Gigabyte F2A85X-UP4            | 3         | 0.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 192       | 10.59%  |
| Dell Latitude         | 65        | 3.59%   |
| Dell OptiPlex         | 54        | 2.98%   |
| Dell Inspiron         | 52        | 2.87%   |
| Acer Aspire           | 52        | 2.87%   |
| Lenovo ThinkCentre    | 37        | 2.04%   |
| Lenovo IdeaPad        | 37        | 2.04%   |
| HP Pavilion           | 37        | 2.04%   |
| ASUS PRIME            | 36        | 1.99%   |
| HP Compaq             | 27        | 1.49%   |
| ASUS ROG              | 27        | 1.49%   |
| Unknown               | 24        | 1.32%   |
| Dell Precision        | 22        | 1.21%   |
| HP EliteBook          | 20        | 1.1%    |
| HP EliteDesk          | 18        | 0.99%   |
| Toshiba Satellite     | 17        | 0.94%   |
| HP Laptop             | 16        | 0.88%   |
| ASUS All              | 16        | 0.88%   |
| HP ProDesk            | 13        | 0.72%   |
| ASUS TUF              | 13        | 0.72%   |
| ASUS VivoBook         | 12        | 0.66%   |
| HP ProBook            | 11        | 0.61%   |
| Fujitsu LIFEBOOK      | 10        | 0.55%   |
| Dell XPS              | 8         | 0.44%   |
| ASUS M5A78L-M         | 8         | 0.44%   |
| Lenovo Yoga           | 7         | 0.39%   |
| Lenovo Legion         | 7         | 0.39%   |
| Gigabyte X570         | 7         | 0.39%   |
| Dell Vostro           | 7         | 0.39%   |
| ASUS P8Z77-V          | 7         | 0.39%   |
| Apple MacBookPro9     | 7         | 0.39%   |
| Apple MacBook5        | 7         | 0.39%   |
| Apple MacBook4        | 7         | 0.39%   |
| Apple iMac9           | 7         | 0.39%   |
| Packard Bell EasyNote | 6         | 0.33%   |
| Gigabyte B450M        | 6         | 0.33%   |
| Apple MacPro5         | 6         | 0.33%   |
| Apple MacBookPro5     | 6         | 0.33%   |
| Toshiba PORTEGE       | 5         | 0.28%   |
| HP OMEN               | 5         | 0.28%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2013    | 152       | 8.38%   |
| 2020    | 151       | 8.33%   |
| 2012    | 151       | 8.33%   |
| 2019    | 150       | 8.27%   |
| 2018    | 141       | 7.78%   |
| 2021    | 124       | 6.84%   |
| 2011    | 120       | 6.62%   |
| 2014    | 113       | 6.23%   |
| 2016    | 109       | 6.01%   |
| 2010    | 108       | 5.96%   |
| 2015    | 94        | 5.18%   |
| 2017    | 92        | 5.07%   |
| 2009    | 87        | 4.8%    |
| 2022    | 83        | 4.58%   |
| 2008    | 64        | 3.53%   |
| 2007    | 32        | 1.77%   |
| 2023    | 30        | 1.65%   |
| 2006    | 8         | 0.44%   |
| Unknown | 3         | 0.17%   |
| 2024    | 1         | 0.06%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 916       | 50.52%  |
| Desktop        | 796       | 43.91%  |
| Mini pc        | 40        | 2.21%   |
| All in one     | 31        | 1.71%   |
| Convertible    | 17        | 0.94%   |
| Server         | 7         | 0.39%   |
| Tablet         | 4         | 0.22%   |
| System on chip | 2         | 0.11%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1798      | 99.17%  |
| Yes  | 15        | 0.83%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 626       | 34.3%   |
| 4.01-8.0    | 487       | 26.68%  |
| 16.01-24.0  | 428       | 23.45%  |
| 32.01-64.0  | 133       | 7.29%   |
| 2.01-3.0    | 63        | 3.45%   |
| 64.01-256.0 | 37        | 2.03%   |
| 24.01-32.0  | 23        | 1.26%   |
| 3.01-4.0    | 22        | 1.21%   |
| 1.01-2.0    | 3         | 0.16%   |
| 0.51-1.0    | 3         | 0.16%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 0.01-0.5  | 976       | 53.22%  |
| 0.51-1.0  | 580       | 31.62%  |
| 1.01-2.0  | 200       | 10.91%  |
| 2.01-3.0  | 54        | 2.94%   |
| 3.01-4.0  | 12        | 0.65%   |
| 4.01-8.0  | 7         | 0.38%   |
| 8.01-16.0 | 5         | 0.27%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1141      | 61.05%  |
| 2      | 369       | 19.74%  |
| 3      | 132       | 7.06%   |
| 0      | 128       | 6.85%   |
| 4      | 52        | 2.78%   |
| 5      | 24        | 1.28%   |
| 6      | 13        | 0.7%    |
| 9      | 3         | 0.16%   |
| 7      | 3         | 0.16%   |
| 10     | 2         | 0.11%   |
| 13     | 1         | 0.05%   |
| 8      | 1         | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1127      | 61.99%  |
| Yes       | 691       | 38.01%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1651      | 91.06%  |
| No        | 162       | 8.94%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1228      | 67.62%  |
| No        | 588       | 32.38%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 926       | 50.74%  |
| No        | 899       | 49.26%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 301       | 16.58%  |
| Russia      | 161       | 8.87%   |
| Germany     | 151       | 8.32%   |
| Brazil      | 115       | 6.34%   |
| Spain       | 76        | 4.19%   |
| Italy       | 70        | 3.86%   |
| UK          | 63        | 3.47%   |
| China       | 59        | 3.25%   |
| Poland      | 57        | 3.14%   |
| Canada      | 55        | 3.03%   |
| France      | 52        | 2.87%   |
| Netherlands | 42        | 2.31%   |
| Indonesia   | 35        | 1.93%   |
| India       | 34        | 1.87%   |
| Hungary     | 34        | 1.87%   |
| Australia   | 33        | 1.82%   |
| Ukraine     | 32        | 1.76%   |
| Mexico      | 28        | 1.54%   |
| Romania     | 22        | 1.21%   |
| Taiwan      | 21        | 1.16%   |
| Turkey      | 18        | 0.99%   |
| Sweden      | 17        | 0.94%   |
| Argentina   | 17        | 0.94%   |
| Belgium     | 16        | 0.88%   |
| Switzerland | 14        | 0.77%   |
| Portugal    | 14        | 0.77%   |
| Bulgaria    | 14        | 0.77%   |
| South Korea | 13        | 0.72%   |
| Greece      | 12        | 0.66%   |
| Japan       | 11        | 0.61%   |
| Finland     | 11        | 0.61%   |
| Chile       | 11        | 0.61%   |
| Peru        | 10        | 0.55%   |
| Norway      | 10        | 0.55%   |
| Serbia      | 9         | 0.5%    |
| Czechia     | 9         | 0.5%    |
| Lithuania   | 8         | 0.44%   |
| Colombia    | 8         | 0.44%   |
| Vietnam     | 7         | 0.39%   |
| Venezuela   | 7         | 0.39%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City          | Computers | Percent |
|---------------|-----------|---------|
| Moscow        | 29        | 1.52%   |
| St Petersburg | 20        | 1.05%   |
| Berlin        | 13        | 0.68%   |
| Sao Paulo     | 12        | 0.63%   |
| Paris         | 11        | 0.58%   |
| Guangzhou     | 11        | 0.58%   |
| Budapest      | 11        | 0.58%   |
| Madrid        | 10        | 0.52%   |
| Wroclaw       | 9         | 0.47%   |
| New York      | 9         | 0.47%   |
| Curitiba      | 9         | 0.47%   |
| Jakarta       | 8         | 0.42%   |
| Yekaterinburg | 7         | 0.37%   |
| Warsaw        | 7         | 0.37%   |
| Munich        | 7         | 0.37%   |
| Manchester    | 7         | 0.37%   |
| Los Angeles   | 7         | 0.37%   |
| Lima          | 7         | 0.37%   |
| Kyiv          | 7         | 0.37%   |
| Krakow        | 7         | 0.37%   |
| Brisbane      | 7         | 0.37%   |
| Zurich        | 6         | 0.31%   |
| Valencia      | 6         | 0.31%   |
| Utrecht       | 6         | 0.31%   |
| Temple        | 6         | 0.31%   |
| Taichung      | 6         | 0.31%   |
| Sydney        | 6         | 0.31%   |
| Stuttgart     | 6         | 0.31%   |
| Santiago      | 6         | 0.31%   |
| Rome          | 6         | 0.31%   |
| Krasnodar     | 6         | 0.31%   |
| Istanbul      | 6         | 0.31%   |
| Hanoi         | 6         | 0.31%   |
| Chelyabinsk   | 6         | 0.31%   |
| Buenos Aires  | 6         | 0.31%   |
| Bucharest     | 6         | 0.31%   |
| Ankara        | 6         | 0.31%   |
| Winnipeg      | 5         | 0.26%   |
| Vilnius       | 5         | 0.26%   |
| Toronto       | 5         | 0.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 391       | 535    | 15.94%  |
| Samsung Electronics | 372       | 514    | 15.17%  |
| Seagate             | 356       | 489    | 14.51%  |
| Kingston            | 172       | 199    | 7.01%   |
| Toshiba             | 167       | 200    | 6.81%   |
| Crucial             | 121       | 157    | 4.93%   |
| SanDisk             | 110       | 120    | 4.48%   |
| Hitachi             | 104       | 128    | 4.24%   |
| Intel               | 60        | 66     | 2.45%   |
| A-DATA Technology   | 59        | 72     | 2.41%   |
| HGST                | 36        | 43     | 1.47%   |
| Micron Technology   | 29        | 30     | 1.18%   |
| Apple               | 27        | 31     | 1.1%    |
| SK hynix            | 26        | 29     | 1.06%   |
| SPCC                | 25        | 32     | 1.02%   |
| Patriot             | 22        | 25     | 0.9%    |
| China               | 19        | 20     | 0.77%   |
| Transcend           | 18        | 20     | 0.73%   |
| PNY                 | 18        | 30     | 0.73%   |
| OCZ                 | 16        | 18     | 0.65%   |
| GOODRAM             | 16        | 17     | 0.65%   |
| KingSpec            | 15        | 19     | 0.61%   |
| Phison              | 14        | 18     | 0.57%   |
| Gigabyte Technology | 14        | 18     | 0.57%   |
| Fujitsu             | 14        | 16     | 0.57%   |
| Corsair             | 13        | 13     | 0.53%   |
| Intenso             | 12        | 15     | 0.49%   |
| Silicon Motion      | 10        | 11     | 0.41%   |
| Hewlett-Packard     | 10        | 11     | 0.41%   |
| Apacer              | 10        | 10     | 0.41%   |
| Maxtor              | 9         | 10     | 0.37%   |
| LITEON              | 8         | 9      | 0.33%   |
| Lexar               | 8         | 9      | 0.33%   |
| KIOXIA              | 8         | 8      | 0.33%   |
| Team                | 7         | 8      | 0.29%   |
| Plextor             | 7         | 8      | 0.29%   |
| LITEONIT            | 6         | 6      | 0.24%   |
| XPG                 | 5         | 5      | 0.2%    |
| SSSTC               | 5         | 5      | 0.2%    |
| Pioneer             | 5         | 5      | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB        | 35        | 1.3%    |
| Samsung SSD 860 EVO 500GB          | 27        | 1.01%   |
| Crucial CT500MX500SSD1 500GB       | 23        | 0.86%   |
| Kingston SA400S37120G 120GB        | 22        | 0.82%   |
| Samsung SSD 850 EVO 250GB          | 21        | 0.78%   |
| Seagate ST500DM002-1BD142 500GB    | 20        | 0.75%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 18        | 0.67%   |
| Seagate ST1000LM035-1RK172 1TB     | 17        | 0.63%   |
| Samsung SSD 860 EVO 250GB          | 17        | 0.63%   |
| Samsung SSD 860 EVO 1TB            | 17        | 0.63%   |
| Toshiba MQ01ABF050 500GB           | 15        | 0.56%   |
| Toshiba MQ01ABD100 1TB             | 15        | 0.56%   |
| Seagate ST9500325AS 500GB          | 14        | 0.52%   |
| Samsung SSD 970 EVO Plus 500GB     | 14        | 0.52%   |
| WDC WDS240G2G0A-00JH30 240GB       | 13        | 0.48%   |
| Toshiba DT01ACA100 1TB             | 13        | 0.48%   |
| Seagate ST1000DM010-2EP102 1TB     | 13        | 0.48%   |
| Kingston SV300S37A120G 120GB       | 13        | 0.48%   |
| Crucial CT240BX500SSD1 240GB       | 13        | 0.48%   |
| Seagate ST1000DM003-1ER162 1TB     | 12        | 0.45%   |
| Kingston SA400S37480G 480GB        | 12        | 0.45%   |
| Seagate ST3500418AS 500GB          | 11        | 0.41%   |
| WDC WDS120G2G0A-00JH30 120GB       | 10        | 0.37%   |
| Toshiba HDWD110 1TB                | 10        | 0.37%   |
| Seagate ST2000DM008-2FR102 2TB     | 10        | 0.37%   |
| Samsung SSD 970 EVO Plus 1TB       | 10        | 0.37%   |
| Samsung SSD 870 EVO 500GB          | 10        | 0.37%   |
| Samsung SSD 840 EVO 250GB          | 10        | 0.37%   |
| A-DATA SU650 120GB                 | 10        | 0.37%   |
| Crucial CT480BX500SSD1 480GB       | 9         | 0.34%   |
| Crucial CT120BX500SSD1 120GB       | 9         | 0.34%   |
| WDC WDS500G2B0A-00SM50 500GB       | 8         | 0.3%    |
| Seagate ST500LT012-1DG142 500GB    | 8         | 0.3%    |
| Samsung SSD 980 PRO 1TB            | 8         | 0.3%    |
| Samsung SSD 980 1TB                | 8         | 0.3%    |
| Samsung SSD 850 EVO 500GB          | 8         | 0.3%    |
| Samsung HD322HJ 320GB              | 8         | 0.3%    |
| HGST HTS725050A7E630 500GB         | 8         | 0.3%    |
| HGST HTS545050A7E680 500GB         | 8         | 0.3%    |
| Toshiba DT01ACA050 500GB           | 7         | 0.26%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 353       | 483    | 34.04%  |
| WDC                 | 310       | 414    | 29.89%  |
| Toshiba             | 135       | 162    | 13.02%  |
| Hitachi             | 104       | 128    | 10.03%  |
| Samsung Electronics | 62        | 80     | 5.98%   |
| HGST                | 36        | 43     | 3.47%   |
| Fujitsu             | 13        | 14     | 1.25%   |
| Maxtor              | 9         | 10     | 0.87%   |
| Apple               | 9         | 9      | 0.87%   |
| Hewlett-Packard     | 3         | 3      | 0.29%   |
| QUANTUM             | 1         | 1      | 0.1%    |
| LSI                 | 1         | 1      | 0.1%    |
| CLOVER              | 1         | 2      | 0.1%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 211       | 266    | 19.61%  |
| Kingston            | 138       | 161    | 12.83%  |
| SanDisk             | 110       | 120    | 10.22%  |
| Crucial             | 106       | 137    | 9.85%   |
| WDC                 | 61        | 72     | 5.67%   |
| A-DATA Technology   | 45        | 50     | 4.18%   |
| Intel               | 37        | 42     | 3.44%   |
| SPCC                | 22        | 29     | 2.04%   |
| Patriot             | 21        | 24     | 1.95%   |
| Toshiba             | 20        | 26     | 1.86%   |
| China               | 19        | 20     | 1.77%   |
| PNY                 | 18        | 28     | 1.67%   |
| Micron Technology   | 18        | 18     | 1.67%   |
| Apple               | 17        | 21     | 1.58%   |
| Transcend           | 16        | 18     | 1.49%   |
| OCZ                 | 16        | 18     | 1.49%   |
| GOODRAM             | 16        | 17     | 1.49%   |
| KingSpec            | 15        | 19     | 1.39%   |
| Intenso             | 12        | 15     | 1.12%   |
| Apacer              | 10        | 10     | 0.93%   |
| Gigabyte Technology | 9         | 11     | 0.84%   |
| LITEON              | 8         | 9      | 0.74%   |
| Plextor             | 7         | 8      | 0.65%   |
| Corsair             | 7         | 7      | 0.65%   |
| SK hynix            | 6         | 6      | 0.56%   |
| LITEONIT            | 6         | 6      | 0.56%   |
| Lexar               | 6         | 6      | 0.56%   |
| Pioneer             | 5         | 5      | 0.46%   |
| Hewlett-Packard     | 5         | 6      | 0.46%   |
| Team                | 4         | 5      | 0.37%   |
| XrayDisk            | 3         | 3      | 0.28%   |
| Smartbuy            | 3         | 3      | 0.28%   |
| OWC                 | 3         | 3      | 0.28%   |
| MidasForce          | 3         | 3      | 0.28%   |
| Leven               | 3         | 4      | 0.28%   |
| KIOXIA-EXCERIA      | 3         | 3      | 0.28%   |
| Zheino              | 2         | 2      | 0.19%   |
| Verbatim            | 2         | 4      | 0.19%   |
| Vaseky              | 2         | 2      | 0.19%   |
| V-GeN               | 2         | 2      | 0.19%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 918       | 1279   | 42.5%   |
| HDD  | 876       | 1350   | 40.56%  |
| NVMe | 366       | 473    | 16.94%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1537      | 2629   | 80.77%  |
| NVMe | 366       | 473    | 19.23%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1288      | 1868   | 70.38%  |
| 0.51-1.0   | 379       | 499    | 20.71%  |
| 1.01-2.0   | 94        | 145    | 5.14%   |
| 3.01-4.0   | 33        | 51     | 1.8%    |
| 4.01-10.0  | 18        | 32     | 0.98%   |
| 2.01-3.0   | 16        | 30     | 0.87%   |
| 10.01-20.0 | 2         | 4      | 0.11%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1044      | 54.98%  |
| 101-250        | 352       | 18.54%  |
| 251-500        | 238       | 12.53%  |
| 501-1000       | 102       | 5.37%   |
| 51-100         | 98        | 5.16%   |
| 21-50          | 42        | 2.21%   |
| 1001-2000      | 12        | 0.63%   |
| More than 3000 | 5         | 0.26%   |
| Unknown        | 5         | 0.26%   |
| 2001-3000      | 1         | 0.05%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1769      | 97.25%  |
| 101-250        | 16        | 0.88%   |
| 21-50          | 13        | 0.71%   |
| 251-500        | 6         | 0.33%   |
| Unknown        | 5         | 0.27%   |
| 51-100         | 4         | 0.22%   |
| More than 3000 | 2         | 0.11%   |
| 1001-2000      | 2         | 0.11%   |
| 501-1000       | 2         | 0.11%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB           | 8         | 10     | 1.71%   |
| Seagate ST500DM002-1BD142 500GB     | 7         | 9      | 1.49%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 7         | 11     | 1.49%   |
| Toshiba MQ01ABD100 1TB              | 6         | 6      | 1.28%   |
| Seagate ST9320325AS 320GB           | 5         | 5      | 1.07%   |
| Seagate ST3500418AS 500GB           | 5         | 5      | 1.07%   |
| Hitachi HTS545050A7E380 500GB       | 5         | 5      | 1.07%   |
| HGST HTS725050A7E630 500GB          | 5         | 6      | 1.07%   |
| WDC WD5000AAKX-00ERMA0 500GB        | 4         | 4      | 0.85%   |
| Toshiba DT01ACA100 1TB              | 4         | 7      | 0.85%   |
| Samsung Electronics HD322HJ 320GB   | 4         | 5      | 0.85%   |
| Hitachi HTS545050B9A300 500GB       | 4         | 4      | 0.85%   |
| Toshiba MQ01ABF050 500GB            | 3         | 5      | 0.64%   |
| Toshiba MQ01ABD050 500GB            | 3         | 3      | 0.64%   |
| Toshiba MK3261GSYN 320GB            | 3         | 5      | 0.64%   |
| Seagate ST9500420AS 500GB           | 3         | 3      | 0.64%   |
| Seagate ST9160412AS 160GB           | 3         | 3      | 0.64%   |
| Seagate ST750LM022 HN-M750MBB 752GB | 3         | 3      | 0.64%   |
| Seagate ST500LT012-9WS142 500GB     | 3         | 3      | 0.64%   |
| Seagate ST500LM000-1EJ162 500GB     | 3         | 3      | 0.64%   |
| Seagate ST3320418AS 320GB           | 3         | 3      | 0.64%   |
| Seagate ST3250410AS 250GB           | 3         | 3      | 0.64%   |
| Seagate ST320LT020-9YG142 320GB     | 3         | 4      | 0.64%   |
| Seagate ST31000528AS 1TB            | 3         | 4      | 0.64%   |
| SanDisk SSD PLUS 240GB              | 3         | 3      | 0.64%   |
| Samsung Electronics HD161HJ 160GB   | 3         | 3      | 0.64%   |
| Hitachi HTS542525K9A300 250GB       | 3         | 3      | 0.64%   |
| Hitachi HTS541612J9SA00 120GB       | 3         | 3      | 0.64%   |
| HGST HTS545032A7E380 320GB          | 3         | 3      | 0.64%   |
| HGST HTS541010A9E680 1TB            | 3         | 4      | 0.64%   |
| WDC WDS240G2G0A-00JH30 240GB        | 2         | 2      | 0.43%   |
| WDC WD5000LPCX-60VHAT0 500GB        | 2         | 3      | 0.43%   |
| WDC WD5000AAKX-60U6AA0 500GB        | 2         | 2      | 0.43%   |
| WDC WD3200BEVT-22ZCT0 320GB         | 2         | 2      | 0.43%   |
| WDC WD30EFRX-68EUZN0 3TB            | 2         | 2      | 0.43%   |
| WDC WD20EARS-00MVWB0 2TB            | 2         | 2      | 0.43%   |
| WDC WD10JPVX-22JC3T0 1TB            | 2         | 2      | 0.43%   |
| WDC WD10JMVW-11AJGS0 1TB            | 2         | 2      | 0.43%   |
| WDC WD10EARS-003BB1 1TB             | 2         | 2      | 0.43%   |
| Toshiba MQ01ABD075 752GB            | 2         | 2      | 0.43%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 120       | 149    | 26.49%  |
| WDC                 | 96        | 104    | 21.19%  |
| Toshiba             | 55        | 66     | 12.14%  |
| Hitachi             | 52        | 60     | 11.48%  |
| Samsung Electronics | 36        | 48     | 7.95%   |
| HGST                | 18        | 21     | 3.97%   |
| Kingston            | 11        | 11     | 2.43%   |
| Intel               | 9         | 9      | 1.99%   |
| SanDisk             | 8         | 8      | 1.77%   |
| Crucial             | 8         | 13     | 1.77%   |
| Apple               | 5         | 5      | 1.1%    |
| Maxtor              | 4         | 5      | 0.88%   |
| Fujitsu             | 4         | 4      | 0.88%   |
| Micron Technology   | 3         | 3      | 0.66%   |
| Corsair             | 3         | 3      | 0.66%   |
| A-DATA Technology   | 3         | 3      | 0.66%   |
| SSSTC               | 2         | 2      | 0.44%   |
| SK hynix            | 2         | 2      | 0.44%   |
| OCZ                 | 2         | 2      | 0.44%   |
| LITEON              | 2         | 2      | 0.44%   |
| China               | 2         | 2      | 0.44%   |
| XrayDisk            | 1         | 1      | 0.22%   |
| Transcend           | 1         | 1      | 0.22%   |
| Silicon Motion      | 1         | 1      | 0.22%   |
| Pioneer             | 1         | 1      | 0.22%   |
| MidasForce          | 1         | 1      | 0.22%   |
| KingSpec            | 1         | 1      | 0.22%   |
| Hewlett-Packard     | 1         | 1      | 0.22%   |
| AGI                 | 1         | 1      | 0.22%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 120       | 149    | 32.09%  |
| WDC                 | 93        | 101    | 24.87%  |
| Toshiba             | 53        | 64     | 14.17%  |
| Hitachi             | 52        | 60     | 13.9%   |
| Samsung Electronics | 26        | 31     | 6.95%   |
| HGST                | 18        | 21     | 4.81%   |
| Maxtor              | 4         | 5      | 1.07%   |
| Fujitsu             | 4         | 4      | 1.07%   |
| Apple               | 4         | 4      | 1.07%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 347       | 439    | 81.26%  |
| SSD  | 70        | 80     | 16.39%  |
| NVMe | 10        | 11     | 2.34%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| SanDisk pSSD 16GB                 | 3         | 3      | 21.43%  |
| WDC WD7501AALS-00J7B0 752GB       | 1         | 1      | 7.14%   |
| WDC WD3200AAJS-00YZCA0 320GB      | 1         | 1      | 7.14%   |
| WDC WD1600BEVT-22ZCT0 160GB       | 1         | 1      | 7.14%   |
| Seagate ST3250310AS 250GB         | 1         | 1      | 7.14%   |
| Samsung Electronics HM500JJ 500GB | 1         | 1      | 7.14%   |
| Samsung Electronics HD103SJ 1TB   | 1         | 2      | 7.14%   |
| HPE MK000480GWUGF 480GB           | 1         | 1      | 7.14%   |
| Hitachi HTS545025B9A300 250GB     | 1         | 1      | 7.14%   |
| Hitachi HDS721032CLA362 320GB     | 1         | 1      | 7.14%   |
| Hitachi HDS721010DLE630 1TB       | 1         | 1      | 7.14%   |
| HGST HTS725050A7E630 500GB        | 1         | 1      | 7.14%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 3         | 3      | 21.43%  |
| SanDisk             | 3         | 3      | 21.43%  |
| Hitachi             | 3         | 3      | 21.43%  |
| Samsung Electronics | 2         | 3      | 14.29%  |
| Seagate             | 1         | 1      | 7.14%   |
| HPE                 | 1         | 1      | 7.14%   |
| HGST                | 1         | 1      | 7.14%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 1415      | 2493   | 74.83%  |
| Malfunc  | 418       | 530    | 22.1%   |
| Detected | 44        | 64     | 2.33%   |
| Failed   | 14        | 15     | 0.74%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 1370      | 61.16%  |
| AMD                                     | 303       | 13.53%  |
| Samsung Electronics                     | 147       | 6.56%   |
| SanDisk                                 | 54        | 2.41%   |
| Nvidia                                  | 48        | 2.14%   |
| Kingston Technology Company             | 36        | 1.61%   |
| Phison Electronics                      | 32        | 1.43%   |
| ASMedia Technology                      | 32        | 1.43%   |
| Silicon Motion                          | 27        | 1.21%   |
| SK hynix                                | 20        | 0.89%   |
| JMicron Technology                      | 20        | 0.89%   |
| Micron/Crucial Technology               | 17        | 0.76%   |
| Marvell Technology Group                | 17        | 0.76%   |
| ADATA Technology                        | 14        | 0.63%   |
| KIOXIA                                  | 13        | 0.58%   |
| Broadcom / LSI                          | 12        | 0.54%   |
| Toshiba                                 | 11        | 0.49%   |
| Micron Technology                       | 11        | 0.49%   |
| Realtek Semiconductor                   | 9         | 0.4%    |
| VIA Technologies                        | 7         | 0.31%   |
| Shenzhen Longsys Electronics            | 5         | 0.22%   |
| MAXIO Technology (Hangzhou)             | 5         | 0.22%   |
| Solid State Storage Technology          | 4         | 0.18%   |
| Silicon Integrated Systems [SiS]        | 4         | 0.18%   |
| Seagate Technology                      | 4         | 0.18%   |
| Adaptec                                 | 3         | 0.13%   |
| Lite-On IT Corp. / Plextor              | 2         | 0.09%   |
| Hewlett-Packard                         | 2         | 0.09%   |
| Biwin Storage Technology                | 2         | 0.09%   |
| Silicon Image                           | 1         | 0.04%   |
| Shenzhen Unionmemory Information System | 1         | 0.04%   |
| OCZ Technology Group                    | 1         | 0.04%   |
| Lenovo                                  | 1         | 0.04%   |
| INNOGRIT                                | 1         | 0.04%   |
| Enmotus                                 | 1         | 0.04%   |
| Chelsio Communications                  | 1         | 0.04%   |
| Broadcom                                | 1         | 0.04%   |
| Apple                                   | 1         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 189       | 7.29%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 132       | 5.09%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 118       | 4.55%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 91        | 3.51%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 80        | 3.09%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 72        | 2.78%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 72        | 2.78%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 62        | 2.39%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 58        | 2.24%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 51        | 1.97%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 44        | 1.7%    |
| AMD 400 Series Chipset SATA Controller                                                  | 43        | 1.66%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 42        | 1.62%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 41        | 1.58%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 40        | 1.54%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 39        | 1.51%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 38        | 1.47%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 38        | 1.47%   |
| Intel SATA Controller [RAID mode]                                                       | 37        | 1.43%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 37        | 1.43%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 34        | 1.31%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 33        | 1.27%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 33        | 1.27%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 31        | 1.2%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 31        | 1.2%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 28        | 1.08%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 28        | 1.08%   |
| Nvidia MCP79 AHCI Controller                                                            | 27        | 1.04%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 27        | 1.04%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 24        | 0.93%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 22        | 0.85%   |
| AMD 500 Series Chipset SATA Controller                                                  | 21        | 0.81%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 19        | 0.73%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 19        | 0.73%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 19        | 0.73%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 19        | 0.73%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 19        | 0.73%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 18        | 0.69%   |
| Phison E12 NVMe Controller                                                              | 16        | 0.62%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 16        | 0.62%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1470      | 65.04%  |
| NVMe | 400       | 17.7%   |
| IDE  | 277       | 12.26%  |
| RAID | 96        | 4.25%   |
| SAS  | 9         | 0.4%    |
| SCSI | 8         | 0.35%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 1466      | 80.86%  |
| AMD      | 344       | 18.97%  |
| Rockchip | 1         | 0.06%   |
| Bochs    | 1         | 0.06%   |
| ARM      | 1         | 0.06%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel CPU Version                           | 21        | 1.16%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 21        | 1.16%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 20        | 1.1%    |
| Intel Core 2 Duo                            | 20        | 1.1%    |
| Intel Core i5-6500 CPU @ 3.20GHz            | 18        | 0.99%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 17        | 0.94%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 17        | 0.94%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 16        | 0.88%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 16        | 0.88%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 14        | 0.77%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 14        | 0.77%   |
| Intel Core i5-3317U CPU @ 1.70GHz           | 11        | 0.61%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 10        | 0.55%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 10        | 0.55%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 10        | 0.55%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 10        | 0.55%   |
| AMD Ryzen 5 3600 6-Core Processor           | 10        | 0.55%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 9         | 0.5%    |
| Intel Core i7-8550U CPU @ 1.80GHz           | 9         | 0.5%    |
| Intel Core i7-3770 CPU @ 3.40GHz            | 9         | 0.5%    |
| Intel Core i3-6006U CPU @ 2.00GHz           | 9         | 0.5%    |
| Intel Core i3-4005U CPU @ 1.70GHz           | 9         | 0.5%    |
| Intel Core 2 Duo CPU P7350 @ 2.00GHz        | 9         | 0.5%    |
| Intel Celeron CPU N3050 @ 1.60GHz           | 9         | 0.5%    |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 9         | 0.5%    |
| Intel Core i7-7500U CPU @ 2.70GHz           | 8         | 0.44%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 8         | 0.44%   |
| Intel Core i7-3520M CPU @ 2.90GHz           | 8         | 0.44%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 8         | 0.44%   |
| Intel Core i5-5300U CPU @ 2.30GHz           | 8         | 0.44%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 8         | 0.44%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 8         | 0.44%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 8         | 0.44%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz        | 8         | 0.44%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 8         | 0.44%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 8         | 0.44%   |
| Intel Xeon                                  | 7         | 0.39%   |
| Intel Genuine CPU                           | 7         | 0.39%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 7         | 0.39%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 7         | 0.39%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 475       | 26.14%  |
| Intel Core i7           | 257       | 14.14%  |
| Intel Core i3           | 189       | 10.4%   |
| Intel Core 2 Duo        | 133       | 7.32%   |
| Intel Celeron           | 101       | 5.56%   |
| AMD Ryzen 5             | 79        | 4.35%   |
| Other                   | 76        | 4.18%   |
| Intel Xeon              | 74        | 4.07%   |
| AMD Ryzen 7             | 56        | 3.08%   |
| Intel Pentium           | 55        | 3.03%   |
| AMD Ryzen 3             | 28        | 1.54%   |
| Intel Pentium Dual-Core | 24        | 1.32%   |
| AMD FX                  | 23        | 1.27%   |
| Intel Atom              | 22        | 1.21%   |
| AMD Phenom II X4        | 18        | 0.99%   |
| Intel Core 2 Quad       | 17        | 0.94%   |
| AMD E1                  | 12        | 0.66%   |
| AMD A10                 | 12        | 0.66%   |
| Intel Genuine           | 11        | 0.61%   |
| AMD Ryzen 9             | 11        | 0.61%   |
| AMD A6                  | 11        | 0.61%   |
| Intel Core 2            | 9         | 0.5%    |
| AMD Athlon II X2        | 9         | 0.5%    |
| Intel Pentium Silver    | 8         | 0.44%   |
| Intel Core i9           | 8         | 0.44%   |
| AMD Ryzen Threadripper  | 8         | 0.44%   |
| AMD A8                  | 8         | 0.44%   |
| AMD A4                  | 7         | 0.39%   |
| AMD E                   | 6         | 0.33%   |
| AMD Athlon              | 6         | 0.33%   |
| AMD Athlon II X4        | 5         | 0.28%   |
| Intel Pentium Dual      | 4         | 0.22%   |
| AMD Ryzen 5 PRO         | 4         | 0.22%   |
| AMD E2                  | 4         | 0.22%   |
| AMD Athlon 64 X2        | 4         | 0.22%   |
| Intel Pentium Gold      | 3         | 0.17%   |
| Intel Core m3           | 3         | 0.17%   |
| AMD Phenom II X6        | 3         | 0.17%   |
| Intel Pentium 4         | 2         | 0.11%   |
| Intel Core m7           | 2         | 0.11%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 792       | 43.64%  |
| 4       | 548       | 30.19%  |
| Unknown | 134       | 7.38%   |
| 6       | 100       | 5.51%   |
| 8       | 79        | 4.35%   |
| 12      | 62        | 3.42%   |
| 16      | 54        | 2.98%   |
| 1       | 18        | 0.99%   |
| 24      | 9         | 0.5%    |
| 10      | 5         | 0.28%   |
| 32      | 3         | 0.17%   |
| 20      | 3         | 0.17%   |
| 64      | 2         | 0.11%   |
| 48      | 2         | 0.11%   |
| 14      | 2         | 0.11%   |
| 18      | 1         | 0.06%   |
| 3       | 1         | 0.06%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1753      | 96.69%  |
| 2       | 54        | 2.98%   |
| Unknown | 4         | 0.22%   |
| 8       | 2         | 0.11%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 880       | 48.54%  |
| 1       | 793       | 43.74%  |
| Unknown | 140       | 7.72%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 247       | 13.6%   |
| IvyBridge     | 190       | 10.46%  |
| Haswell       | 190       | 10.46%  |
| SandyBridge   | 160       | 8.81%   |
| Penryn        | 154       | 8.48%   |
| Skylake       | 142       | 7.82%   |
| Westmere      | 72        | 3.96%   |
| Core          | 69        | 3.8%    |
| Zen+          | 57        | 3.14%   |
| Zen 2         | 48        | 2.64%   |
| Broadwell     | 47        | 2.59%   |
| Zen 3         | 44        | 2.42%   |
| Silvermont    | 44        | 2.42%   |
| Unknown       | 43        | 2.37%   |
| Piledriver    | 41        | 2.26%   |
| K10           | 41        | 2.26%   |
| Zen           | 37        | 2.04%   |
| CometLake     | 31        | 1.71%   |
| Nehalem       | 20        | 1.1%    |
| Bonnell       | 20        | 1.1%    |
| Excavator     | 18        | 0.99%   |
| Goldmont plus | 17        | 0.94%   |
| TigerLake     | 16        | 0.88%   |
| Bobcat        | 16        | 0.88%   |
| Goldmont      | 13        | 0.72%   |
| Jaguar        | 12        | 0.66%   |
| K8 Hammer     | 10        | 0.55%   |
| Bulldozer     | 5         | 0.28%   |
| NetBurst      | 3         | 0.17%   |
| K10 Llano     | 3         | 0.17%   |
| IceLake       | 3         | 0.17%   |
| Puma          | 2         | 0.11%   |
| Steamroller   | 1         | 0.06%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1103      | 54.12%  |
| Nvidia                           | 527       | 25.86%  |
| AMD                              | 400       | 19.63%  |
| Silicon Integrated Systems [SiS] | 3         | 0.15%   |
| Matrox Electronics Systems       | 3         | 0.15%   |
| Red Hat                          | 1         | 0.05%   |
| ASPEED Technology                | 1         | 0.05%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 127       | 6.09%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 114       | 5.47%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 65        | 3.12%   |
| Intel HD Graphics 530                                                                    | 54        | 2.59%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 52        | 2.49%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 49        | 2.35%   |
| Intel Core Processor Integrated Graphics Controller                                      | 48        | 2.3%    |
| Intel HD Graphics 620                                                                    | 47        | 2.25%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 39        | 1.87%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 38        | 1.82%   |
| Intel HD Graphics 5500                                                                   | 38        | 1.82%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 37        | 1.77%   |
| Intel UHD Graphics 620                                                                   | 35        | 1.68%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 30        | 1.44%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 30        | 1.44%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 29        | 1.39%   |
| Intel HD Graphics 630                                                                    | 28        | 1.34%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 27        | 1.29%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 24        | 1.15%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 23        | 1.1%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 21        | 1.01%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 20        | 0.96%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 19        | 0.91%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 19        | 0.91%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 17        | 0.81%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 17        | 0.81%   |
| Nvidia GT218 [GeForce 210]                                                               | 15        | 0.72%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 15        | 0.72%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 15        | 0.72%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 14        | 0.67%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 14        | 0.67%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 14        | 0.67%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 14        | 0.67%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 13        | 0.62%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 13        | 0.62%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 13        | 0.62%   |
| Nvidia C79 [GeForce 9400M]                                                               | 13        | 0.62%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 13        | 0.62%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 13        | 0.62%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 13        | 0.62%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 796       | 43.57%  |
| 1 x Nvidia               | 366       | 20.03%  |
| 1 x AMD                  | 325       | 17.79%  |
| Intel + Nvidia           | 144       | 7.88%   |
| 2 x Intel                | 105       | 5.75%   |
| Intel + AMD              | 56        | 3.07%   |
| AMD + Nvidia             | 14        | 0.77%   |
| 2 x AMD                  | 6         | 0.33%   |
| Other                    | 3         | 0.16%   |
| 2 x Nvidia               | 3         | 0.16%   |
| 1 x SiS                  | 3         | 0.16%   |
| 1 x Matrox               | 3         | 0.16%   |
| 1 x Red Hat              | 1         | 0.05%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.05%   |
| AMD + ASPEED             | 1         | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1462      | 79.67%  |
| Proprietary | 277       | 15.1%   |
| Unknown     | 96        | 5.23%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1332      | 72.16%  |
| 0.01-0.5   | 126       | 6.83%   |
| 1.01-2.0   | 117       | 6.34%   |
| 0.51-1.0   | 97        | 5.25%   |
| 3.01-4.0   | 79        | 4.28%   |
| 7.01-8.0   | 45        | 2.44%   |
| 5.01-6.0   | 33        | 1.79%   |
| 2.01-3.0   | 10        | 0.54%   |
| 8.01-16.0  | 6         | 0.33%   |
| 4.01-5.0   | 1         | 0.05%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 157       | 11.72%  |
| AU Optronics            | 138       | 10.3%   |
| LG Display              | 135       | 10.07%  |
| Chimei Innolux          | 98        | 7.31%   |
| Dell                    | 82        | 6.12%   |
| Goldstar                | 81        | 6.04%   |
| BOE                     | 80        | 5.97%   |
| Lenovo                  | 57        | 4.25%   |
| Acer                    | 57        | 4.25%   |
| Hewlett-Packard         | 53        | 3.96%   |
| Apple                   | 47        | 3.51%   |
| BenQ                    | 44        | 3.28%   |
| AOC                     | 35        | 2.61%   |
| Philips                 | 29        | 2.16%   |
| Ancor Communications    | 29        | 2.16%   |
| Chi Mei Optoelectronics | 22        | 1.64%   |
| ViewSonic               | 16        | 1.19%   |
| Sharp                   | 13        | 0.97%   |
| InfoVision              | 13        | 0.97%   |
| Iiyama                  | 10        | 0.75%   |
| ASUSTek Computer        | 10        | 0.75%   |
| Fujitsu Siemens         | 9         | 0.67%   |
| Sony                    | 8         | 0.6%    |
| PANDA                   | 6         | 0.45%   |
| NEC Computers           | 6         | 0.45%   |
| MSI                     | 6         | 0.45%   |
| LG Philips              | 6         | 0.45%   |
| HannStar                | 6         | 0.45%   |
| Toshiba                 | 5         | 0.37%   |
| Eizo                    | 5         | 0.37%   |
| Vizio                   | 4         | 0.3%    |
| Vestel Elektronik       | 4         | 0.3%    |
| LG Electronics          | 4         | 0.3%    |
| Unknown                 | 4         | 0.3%    |
| Packard Bell            | 3         | 0.22%   |
| RS                      | 2         | 0.15%   |
| ONN                     | 2         | 0.15%   |
| Medion                  | 2         | 0.15%   |
| Lenovo Group Limited    | 2         | 0.15%   |
| LED                     | 2         | 0.15%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch           | 7         | 0.52%   |
| Lenovo LCD Monitor LEN4031 1280x800 300x190mm 14.0-inch               | 7         | 0.52%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch         | 7         | 0.52%   |
| Acer G227HQL ACR03DE 1920x1080 480x270mm 21.7-inch                    | 6         | 0.44%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 340x190mm 15.3-inch  | 5         | 0.37%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch  | 5         | 0.37%   |
| Lenovo LCD Monitor LEN4035 1280x800 300x190mm 14.0-inch               | 5         | 0.37%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch      | 5         | 0.37%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 340x190mm 15.3-inch         | 5         | 0.37%   |
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 710x400mm 32.1-inch    | 4         | 0.29%   |
| Samsung Electronics LCD Monitor SEC3245 1280x800 330x210mm 15.4-inch  | 4         | 0.29%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 340x190mm 15.3-inch | 4         | 0.29%   |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch           | 4         | 0.29%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch           | 4         | 0.29%   |
| InfoVision LCD Monitor IVO04E3 1366x768 280x160mm 12.7-inch           | 4         | 0.29%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x130mm 10.1-inch             | 4         | 0.29%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch             | 4         | 0.29%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 340x190mm 15.3-inch       | 4         | 0.29%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 310x170mm 13.9-inch      | 4         | 0.29%   |
| BOE LCD Monitor BOE06CE 1366x768 280x160mm 12.7-inch                  | 4         | 0.29%   |
| BenQ GW2780 BNQ78E6 1920x1080 600x340mm 27.2-inch                     | 4         | 0.29%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 340x190mm 15.3-inch         | 4         | 0.29%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 340x190mm 15.3-inch        | 4         | 0.29%   |
| AU Optronics LCD Monitor AUO183C 1366x768 310x170mm 13.9-inch         | 4         | 0.29%   |
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                  | 4         | 0.29%   |
| Unknown                                                               | 4         | 0.29%   |
| Toshiba TV TSB0108 1360x768 890x500mm 40.2-inch                       | 3         | 0.22%   |
| Samsung Electronics SyncMaster SAM05C5 1920x1080                      | 3         | 0.22%   |
| Philips PHL 193V5 PHLC0CD 1366x768 410x230mm 18.5-inch                | 3         | 0.22%   |
| MSI G32C4 MSI3DA6 1920x1080 700x390mm 31.5-inch                       | 3         | 0.22%   |
| LG Display LCD Monitor LGD0459 1920x1080 380x210mm 17.1-inch          | 3         | 0.22%   |
| LG Display LCD Monitor LGD0385 1366x768 310x170mm 13.9-inch           | 3         | 0.22%   |
| LG Display LCD Monitor LGD032C 1920x1080 340x190mm 15.3-inch          | 3         | 0.22%   |
| LG Display LCD Monitor LGD024D 1366x768 290x170mm 13.2-inch           | 3         | 0.22%   |
| Lenovo LCD Monitor LEN40B0 1366x768 340x190mm 15.3-inch               | 3         | 0.22%   |
| Lenovo LCD Monitor LEN4050 1280x800 330x210mm 15.4-inch               | 3         | 0.22%   |
| Lenovo LCD Monitor LEN4000 1024x768 250x180mm 12.1-inch               | 3         | 0.22%   |
| InfoVision LCD Monitor IVO03F4 1024x600 220x130mm 10.1-inch           | 3         | 0.22%   |
| Goldstar W1934 GSM4B7A 1440x900 410x260mm 19.1-inch                   | 3         | 0.22%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 580x240mm 24.7-inch           | 3         | 0.22%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 503       | 38.11%  |
| 1366x768 (WXGA)    | 347       | 26.29%  |
| 1600x900 (HD+)     | 63        | 4.77%   |
| 2560x1440 (QHD)    | 57        | 4.32%   |
| 1280x800 (WXGA)    | 57        | 4.32%   |
| 1280x1024 (SXGA)   | 47        | 3.56%   |
| 3840x2160 (4K)     | 46        | 3.48%   |
| 1680x1050 (WSXGA+) | 45        | 3.41%   |
| 1440x900 (WXGA+)   | 40        | 3.03%   |
| 1920x1200 (WUXGA)  | 23        | 1.74%   |
| 2560x1080          | 15        | 1.14%   |
| 1024x600           | 13        | 0.98%   |
| 1024x768 (XGA)     | 10        | 0.76%   |
| 1920x540           | 8         | 0.61%   |
| 3440x1440          | 7         | 0.53%   |
| 3200x1800 (QHD+)   | 6         | 0.45%   |
| 2560x1600          | 6         | 0.45%   |
| 1360x768           | 6         | 0.45%   |
| Unknown            | 3         | 0.23%   |
| 3840x1080          | 2         | 0.15%   |
| 2048x1152          | 2         | 0.15%   |
| 1600x1200          | 2         | 0.15%   |
| 1400x1050          | 2         | 0.15%   |
| 5760x2160          | 1         | 0.08%   |
| 3840x2400          | 1         | 0.08%   |
| 3520x1080          | 1         | 0.08%   |
| 3200x2000          | 1         | 0.08%   |
| 2880x1800          | 1         | 0.08%   |
| 2736x1824          | 1         | 0.08%   |
| 2240x1400          | 1         | 0.08%   |
| 2160x1440          | 1         | 0.08%   |
| 1920x515           | 1         | 0.08%   |
| 1800x1200          | 1         | 0.08%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 271       | 20.16%  |
| 13      | 222       | 16.52%  |
| 24      | 112       | 8.33%   |
| 21      | 100       | 7.44%   |
| 27      | 89        | 6.62%   |
| 23      | 78        | 5.8%    |
| 19      | 74        | 5.51%   |
| 12      | 62        | 4.61%   |
| 17      | 53        | 3.94%   |
| Unknown | 44        | 3.27%   |
| 18      | 35        | 2.6%    |
| 14      | 34        | 2.53%   |
| 11      | 29        | 2.16%   |
| 31      | 27        | 2.01%   |
| 22      | 20        | 1.49%   |
| 20      | 20        | 1.49%   |
| 34      | 15        | 1.12%   |
| 10      | 13        | 0.97%   |
| 40      | 6         | 0.45%   |
| 42      | 5         | 0.37%   |
| 29      | 4         | 0.3%    |
| 28      | 4         | 0.3%    |
| 16      | 4         | 0.3%    |
| 50      | 3         | 0.22%   |
| 9       | 3         | 0.22%   |
| 64      | 2         | 0.15%   |
| 54      | 2         | 0.15%   |
| 52      | 2         | 0.15%   |
| 33      | 2         | 0.15%   |
| 25      | 2         | 0.15%   |
| 43      | 1         | 0.07%   |
| 41      | 1         | 0.07%   |
| 39      | 1         | 0.07%   |
| 36      | 1         | 0.07%   |
| 32      | 1         | 0.07%   |
| 30      | 1         | 0.07%   |
| 26      | 1         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 444       | 33.36%  |
| 501-600     | 263       | 19.76%  |
| 401-500     | 223       | 16.75%  |
| 201-300     | 204       | 15.33%  |
| 351-400     | 68        | 5.11%   |
| Unknown     | 44        | 3.31%   |
| 601-700     | 43        | 3.23%   |
| 701-800     | 19        | 1.43%   |
| 1001-1500   | 9         | 0.68%   |
| 801-900     | 7         | 0.53%   |
| 901-1000    | 7         | 0.53%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 987       | 76.45%  |
| 16/10   | 175       | 13.56%  |
| 5/4     | 40        | 3.1%    |
| Unknown | 30        | 2.32%   |
| 21/9    | 22        | 1.7%    |
| 4/3     | 18        | 1.39%   |
| 3/2     | 17        | 1.32%   |
| 6/5     | 1         | 0.08%   |
| 3.88    | 1         | 0.08%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 268       | 20.09%  |
| 91-100         | 210       | 15.74%  |
| 81-90          | 207       | 15.52%  |
| 151-200        | 102       | 7.65%   |
| 301-350        | 92        | 6.9%    |
| 101-110        | 69        | 5.17%   |
| 61-70          | 61        | 4.57%   |
| 351-500        | 48        | 3.6%    |
| 141-150        | 46        | 3.45%   |
| Unknown        | 44        | 3.3%    |
| 71-80          | 38        | 2.85%   |
| 251-300        | 35        | 2.62%   |
| 121-130        | 33        | 2.47%   |
| 51-60          | 27        | 2.02%   |
| 41-50          | 16        | 1.2%    |
| 501-1000       | 15        | 1.12%   |
| More than 1000 | 9         | 0.67%   |
| 111-120        | 8         | 0.6%    |
| 131-140        | 5         | 0.37%   |
| 1-40           | 1         | 0.07%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 476       | 35.95%  |
| 101-120       | 426       | 32.18%  |
| 121-160       | 306       | 23.11%  |
| 161-240       | 50        | 3.78%   |
| Unknown       | 44        | 3.32%   |
| More than 240 | 13        | 0.98%   |
| 1-50          | 9         | 0.68%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1470      | 79.98%  |
| 0     | 276       | 15.02%  |
| 2     | 90        | 4.9%    |
| 3     | 2         | 0.11%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 904       | 34.81%  |
| Realtek Semiconductor                  | 885       | 34.08%  |
| Qualcomm Atheros                       | 299       | 11.51%  |
| Broadcom                               | 190       | 7.32%   |
| Marvell Technology Group               | 41        | 1.58%   |
| Ralink                                 | 29        | 1.12%   |
| Nvidia                                 | 28        | 1.08%   |
| Ralink Technology                      | 27        | 1.04%   |
| Samsung Electronics                    | 25        | 0.96%   |
| TP-Link                                | 16        | 0.62%   |
| Sierra Wireless                        | 12        | 0.46%   |
| Xiaomi                                 | 11        | 0.42%   |
| MediaTek                               | 11        | 0.42%   |
| JMicron Technology                     | 10        | 0.39%   |
| Google                                 | 10        | 0.39%   |
| Edimax Technology                      | 10        | 0.39%   |
| Ericsson Business Mobile Networks      | 9         | 0.35%   |
| Dell                                   | 8         | 0.31%   |
| D-Link System                          | 7         | 0.27%   |
| Huawei Technologies                    | 6         | 0.23%   |
| D-Link                                 | 5         | 0.19%   |
| Silicon Integrated Systems [SiS]       | 4         | 0.15%   |
| Qualcomm                               | 4         | 0.15%   |
| OPPO Electronics                       | 4         | 0.15%   |
| NetGear                                | 4         | 0.15%   |
| Hewlett-Packard                        | 3         | 0.12%   |
| ASUSTek Computer                       | 3         | 0.12%   |
| T & A Mobile Phones                    | 2         | 0.08%   |
| Motorola PCS                           | 2         | 0.08%   |
| Mellanox Technologies                  | 2         | 0.08%   |
| IMC Networks                           | 2         | 0.08%   |
| Belkin Components                      | 2         | 0.08%   |
| Aquantia                               | 2         | 0.08%   |
| VIA Technologies                       | 1         | 0.04%   |
| Toshiba                                | 1         | 0.04%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.04%   |
| Raspberry Pi                           | 1         | 0.04%   |
| Qualcomm Technologies                  | 1         | 0.04%   |
| Qualcomm Atheros Communications        | 1         | 0.04%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 664       | 21.23%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 115       | 3.68%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 114       | 3.64%   |
| Intel Wireless 8265 / 8275                                             | 64        | 2.05%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 59        | 1.89%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 55        | 1.76%   |
| Intel Wireless 7260                                                    | 52        | 1.66%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 52        | 1.66%   |
| Intel Ethernet Connection I217-LM                                      | 51        | 1.63%   |
| Intel Wireless 7265                                                    | 48        | 1.53%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 47        | 1.5%    |
| Intel Wireless 8260                                                    | 46        | 1.47%   |
| Intel I211 Gigabit Network Connection                                  | 40        | 1.28%   |
| Intel Wi-Fi 6 AX200                                                    | 39        | 1.25%   |
| Intel Ethernet Connection (2) I219-LM                                  | 37        | 1.18%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 33        | 1.05%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                 | 29        | 0.93%   |
| Intel Wireless 3165                                                    | 27        | 0.86%   |
| Intel Ethernet Connection I219-LM                                      | 27        | 0.86%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 27        | 0.86%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 26        | 0.83%   |
| Nvidia MCP79 Ethernet                                                  | 26        | 0.83%   |
| Intel Ethernet Connection (7) I219-V                                   | 25        | 0.8%    |
| Intel Ethernet Connection (2) I219-V                                   | 24        | 0.77%   |
| Intel 82577LM Gigabit Network Connection                               | 22        | 0.7%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 21        | 0.67%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 21        | 0.67%   |
| Intel Ethernet Connection (4) I219-LM                                  | 19        | 0.61%   |
| Intel 82574L Gigabit Network Connection                                | 19        | 0.61%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 18        | 0.58%   |
| Intel Centrino Advanced-N 6200                                         | 18        | 0.58%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 17        | 0.54%   |
| Intel 82579V Gigabit Network Connection                                | 17        | 0.54%   |
| Broadcom BCM4331 802.11a/b/g/n                                         | 17        | 0.54%   |
| Broadcom BCM43224 802.11a/b/g/n                                        | 17        | 0.54%   |
| Intel Ethernet Controller I225-V                                       | 16        | 0.51%   |
| Intel Ethernet Connection I218-LM                                      | 16        | 0.51%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                | 15        | 0.48%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 15        | 0.48%   |
| Broadcom BCM4321 802.11a/b/g/n                                         | 15        | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 614       | 46.27%  |
| Qualcomm Atheros                | 247       | 18.61%  |
| Realtek Semiconductor           | 193       | 14.54%  |
| Broadcom                        | 143       | 10.78%  |
| Ralink                          | 29        | 2.19%   |
| Ralink Technology               | 27        | 2.03%   |
| TP-Link                         | 16        | 1.21%   |
| Edimax Technology               | 10        | 0.75%   |
| Sierra Wireless                 | 9         | 0.68%   |
| MediaTek                        | 9         | 0.68%   |
| D-Link                          | 5         | 0.38%   |
| NetGear                         | 4         | 0.3%    |
| D-Link System                   | 4         | 0.3%    |
| Dell                            | 3         | 0.23%   |
| ASUSTek Computer                | 3         | 0.23%   |
| IMC Networks                    | 2         | 0.15%   |
| Belkin Components               | 2         | 0.15%   |
| Qualcomm Technologies           | 1         | 0.08%   |
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
| Intel Wireless 8265 / 8275                                              | 64        | 4.75%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 59        | 4.38%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 55        | 4.09%   |
| Intel Wireless 7260                                                     | 52        | 3.86%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 52        | 3.86%   |
| Intel Wireless 7265                                                     | 48        | 3.57%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 47        | 3.49%   |
| Intel Wireless 8260                                                     | 46        | 3.42%   |
| Intel Wi-Fi 6 AX200                                                     | 39        | 2.9%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 33        | 2.45%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 29        | 2.15%   |
| Intel Wireless 3165                                                     | 27        | 2.01%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 27        | 2.01%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 26        | 1.93%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 21        | 1.56%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 21        | 1.56%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 18        | 1.34%   |
| Intel Centrino Advanced-N 6200                                          | 18        | 1.34%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 17        | 1.26%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 17        | 1.26%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 15        | 1.11%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 15        | 1.11%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 15        | 1.11%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 14        | 1.04%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 14        | 1.04%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 14        | 1.04%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 13        | 0.97%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 13        | 0.97%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 13        | 0.97%   |
| Intel WiFi Link 5100                                                    | 13        | 0.97%   |
| Intel Wi-Fi 6 AX201                                                     | 13        | 0.97%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 13        | 0.97%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 13        | 0.97%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 13        | 0.97%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 12        | 0.89%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 12        | 0.89%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 12        | 0.89%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 11        | 0.82%   |
| Intel Centrino Advanced-N 6235                                          | 11        | 0.82%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 10        | 0.74%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 802       | 46.6%   |
| Intel                                  | 600       | 34.86%  |
| Qualcomm Atheros                       | 91        | 5.29%   |
| Broadcom                               | 77        | 4.47%   |
| Marvell Technology Group               | 41        | 2.38%   |
| Nvidia                                 | 28        | 1.63%   |
| Samsung Electronics                    | 25        | 1.45%   |
| Xiaomi                                 | 11        | 0.64%   |
| JMicron Technology                     | 10        | 0.58%   |
| Google                                 | 5         | 0.29%   |
| Silicon Integrated Systems [SiS]       | 4         | 0.23%   |
| Qualcomm                               | 4         | 0.23%   |
| OPPO Electronics                       | 4         | 0.23%   |
| Huawei Technologies                    | 4         | 0.23%   |
| T & A Mobile Phones                    | 2         | 0.12%   |
| Motorola PCS                           | 2         | 0.12%   |
| MediaTek                               | 2         | 0.12%   |
| D-Link System                          | 2         | 0.12%   |
| Aquantia                               | 2         | 0.12%   |
| VIA Technologies                       | 1         | 0.06%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.06%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.06%   |
| National Semiconductor                 | 1         | 0.06%   |
| Chelsio Communications                 | 1         | 0.06%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 664       | 38.2%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 115       | 6.62%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 114       | 6.56%   |
| Intel Ethernet Connection I217-LM                                      | 51        | 2.93%   |
| Intel I211 Gigabit Network Connection                                  | 40        | 2.3%    |
| Intel Ethernet Connection (2) I219-LM                                  | 37        | 2.13%   |
| Intel Ethernet Connection I219-LM                                      | 27        | 1.55%   |
| Nvidia MCP79 Ethernet                                                  | 26        | 1.5%    |
| Intel Ethernet Connection (7) I219-V                                   | 25        | 1.44%   |
| Intel Ethernet Connection (2) I219-V                                   | 24        | 1.38%   |
| Intel 82577LM Gigabit Network Connection                               | 22        | 1.27%   |
| Intel Ethernet Connection (4) I219-LM                                  | 19        | 1.09%   |
| Intel 82574L Gigabit Network Connection                                | 19        | 1.09%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 17        | 0.98%   |
| Intel 82579V Gigabit Network Connection                                | 17        | 0.98%   |
| Intel Ethernet Controller I225-V                                       | 16        | 0.92%   |
| Intel Ethernet Connection I218-LM                                      | 16        | 0.92%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 14        | 0.81%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 14        | 0.81%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 13        | 0.75%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 13        | 0.75%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 13        | 0.75%   |
| Intel Ethernet Connection I217-V                                       | 13        | 0.75%   |
| Intel Ethernet Connection (4) I219-V                                   | 13        | 0.75%   |
| Intel Ethernet Connection (3) I218-LM                                  | 13        | 0.75%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 13        | 0.75%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 12        | 0.69%   |
| Intel 82566MM Gigabit Network Connection                               | 12        | 0.69%   |
| Intel 82567LM Gigabit Network Connection                               | 11        | 0.63%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 9         | 0.52%   |
| Intel Ethernet Connection (6) I219-V                                   | 9         | 0.52%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 8         | 0.46%   |
| Realtek RTL8125 2.5GbE Controller                                      | 8         | 0.46%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 8         | 0.46%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 7         | 0.4%    |
| Intel I210 Gigabit Network Connection                                  | 7         | 0.4%    |
| Intel 82566DM-2 Gigabit Network Connection                             | 7         | 0.4%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 7         | 0.4%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 7         | 0.4%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 6         | 0.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1653      | 56.51%  |
| WiFi     | 1228      | 41.98%  |
| Unknown  | 30        | 1.03%   |
| Modem    | 14        | 0.48%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1321      | 64.1%   |
| WiFi     | 728       | 35.32%  |
| Unknown  | 7         | 0.34%   |
| Modem    | 5         | 0.24%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1009      | 55.59%  |
| 1     | 742       | 40.88%  |
| 3     | 37        | 2.04%   |
| 0     | 21        | 1.16%   |
| 4     | 5         | 0.28%   |
| 9     | 1         | 0.06%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1745      | 95.15%  |
| Yes  | 89        | 4.85%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 419       | 44.48%  |
| Apple                           | 81        | 8.6%    |
| Broadcom                        | 78        | 8.28%   |
| Realtek Semiconductor           | 76        | 8.07%   |
| Qualcomm Atheros Communications | 68        | 7.22%   |
| Cambridge Silicon Radio         | 62        | 6.58%   |
| IMC Networks                    | 32        | 3.4%    |
| Foxconn / Hon Hai               | 27        | 2.87%   |
| Lite-On Technology              | 22        | 2.34%   |
| ASUSTek Computer                | 21        | 2.23%   |
| Dell                            | 14        | 1.49%   |
| Hewlett-Packard                 | 13        | 1.38%   |
| Ralink                          | 8         | 0.85%   |
| TP-Link                         | 4         | 0.42%   |
| Alps Electric                   | 4         | 0.42%   |
| Integrated System Solution      | 3         | 0.32%   |
| MediaTek                        | 2         | 0.21%   |
| Fujitsu                         | 2         | 0.21%   |
| Toshiba                         | 1         | 0.11%   |
| Silicon Wave                    | 1         | 0.11%   |
| Primax Electronics              | 1         | 0.11%   |
| HTC (High Tech Computer)        | 1         | 0.11%   |
| Edimax Technology               | 1         | 0.11%   |
| Askey Computer                  | 1         | 0.11%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 228       | 24.08%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 62        | 6.55%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 41        | 4.33%   |
| Intel AX201 Bluetooth                                       | 39        | 4.12%   |
| Intel AX200 Bluetooth                                       | 36        | 3.8%    |
| Apple Bluetooth Host Controller                             | 32        | 3.38%   |
| Intel Wireless-AC 3168 Bluetooth                            | 27        | 2.85%   |
| Realtek Bluetooth Adapter                                   | 25        | 2.64%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 22        | 2.32%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 20        | 2.11%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 19        | 2.01%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 17        | 1.8%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 16        | 1.69%   |
| Apple Broadcom Built-in Bluetooth                           | 14        | 1.48%   |
| Realtek  Bluetooth 4.2 Adapter                              | 13        | 1.37%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 13        | 1.37%   |
| Intel AX210 Bluetooth                                       | 12        | 1.27%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 11        | 1.16%   |
| Apple Built-in iSight (no firmware loaded)                  | 10        | 1.06%   |
| Realtek Bluetooth 4.0 Adapter                               | 9         | 0.95%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 9         | 0.95%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 9         | 0.95%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 9         | 0.95%   |
| Ralink RT3290 Bluetooth                                     | 8         | 0.84%   |
| Lite-On Atheros AR3012 Bluetooth                            | 8         | 0.84%   |
| Realtek RTL8821A Bluetooth                                  | 7         | 0.74%   |
| IMC Networks Realtek Bluetooth Adapter                      | 7         | 0.74%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 7         | 0.74%   |
| Realtek RTL8723B Bluetooth                                  | 6         | 0.63%   |
| Realtek Bluetooth 4.2 Adapter                               | 6         | 0.63%   |
| Dell DW375 Bluetooth Module                                 | 6         | 0.63%   |
| ASUS USB-BT500                                              | 6         | 0.63%   |
| Qualcomm Atheros Dell Wireless 1703 Bluetooth               | 5         | 0.53%   |
| Qualcomm Atheros AR3011 Bluetooth                           | 5         | 0.53%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 5         | 0.53%   |
| HP Broadcom 2070 Bluetooth Combo                            | 5         | 0.53%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 5         | 0.53%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                 | 5         | 0.53%   |
| Broadcom BCM20702A0 Bluetooth 4.0                           | 5         | 0.53%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]          | 5         | 0.53%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 1401      | 58.64%  |
| AMD                                          | 432       | 18.08%  |
| Nvidia                                       | 371       | 15.53%  |
| C-Media Electronics                          | 47        | 1.97%   |
| Texas Instruments                            | 20        | 0.84%   |
| Creative Labs                                | 11        | 0.46%   |
| GN Netcom                                    | 10        | 0.42%   |
| Generalplus Technology                       | 7         | 0.29%   |
| Creative Technology                          | 6         | 0.25%   |
| SteelSeries ApS                              | 5         | 0.21%   |
| Logitech                                     | 5         | 0.21%   |
| JMTek                                        | 5         | 0.21%   |
| Silicon Integrated Systems [SiS]             | 4         | 0.17%   |
| Realtek Semiconductor                        | 4         | 0.17%   |
| Hewlett-Packard                              | 4         | 0.17%   |
| Yamaha                                       | 3         | 0.13%   |
| Kingston Technology                          | 3         | 0.13%   |
| XMOS                                         | 2         | 0.08%   |
| VIA Technologies                             | 2         | 0.08%   |
| Razer USA                                    | 2         | 0.08%   |
| Micro Star International                     | 2         | 0.08%   |
| Google                                       | 2         | 0.08%   |
| GEMBIRD                                      | 2         | 0.08%   |
| Focusrite-Novation                           | 2         | 0.08%   |
| Cambridge Silicon Radio                      | 2         | 0.08%   |
| BEHRINGER International                      | 2         | 0.08%   |
| ASUSTek Computer                             | 2         | 0.08%   |
| Unknown                                      | 2         | 0.08%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.04%   |
| ZOOM                                         | 1         | 0.04%   |
| Steinberg Soft-und Hardware                  | 1         | 0.04%   |
| RME                                          | 1         | 0.04%   |
| Plantronics                                  | 1         | 0.04%   |
| Phison Electronics                           | 1         | 0.04%   |
| OPPO Electronics                             | 1         | 0.04%   |
| Nektar                                       | 1         | 0.04%   |
| Microsoft                                    | 1         | 0.04%   |
| M-Audio                                      | 1         | 0.04%   |
| Lenovo                                       | 1         | 0.04%   |
| KTMicro                                      | 1         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 184       | 6.52%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 149       | 5.28%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 145       | 5.14%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 105       | 3.72%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 103       | 3.65%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 84        | 2.98%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 79        | 2.8%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 73        | 2.59%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 70        | 2.48%   |
| Intel 8 Series HD Audio Controller                                                                | 66        | 2.34%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 63        | 2.23%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 63        | 2.23%   |
| Intel Cannon Lake PCH cAVS                                                                        | 61        | 2.16%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 59        | 2.09%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 52        | 1.84%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 49        | 1.74%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 49        | 1.74%   |
| AMD FCH Azalia Controller                                                                         | 48        | 1.7%    |
| Intel 200 Series PCH HD Audio                                                                     | 46        | 1.63%   |
| Intel Broadwell-U Audio Controller                                                                | 43        | 1.52%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 40        | 1.42%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 40        | 1.42%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 38        | 1.35%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 37        | 1.31%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 36        | 1.28%   |
| Nvidia MCP79 High Definition Audio                                                                | 28        | 0.99%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 26        | 0.92%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 23        | 0.82%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 23        | 0.82%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 23        | 0.82%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 22        | 0.78%   |
| Nvidia High Definition Audio Controller                                                           | 21        | 0.74%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 21        | 0.74%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 21        | 0.74%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 21        | 0.74%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 19        | 0.67%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 18        | 0.64%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 18        | 0.64%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 18        | 0.64%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 18        | 0.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 411       | 19.13%  |
| SK hynix            | 310       | 14.43%  |
| Kingston            | 289       | 13.45%  |
| Unknown             | 219       | 10.19%  |
| Micron Technology   | 193       | 8.98%   |
| Crucial             | 123       | 5.72%   |
| Corsair             | 81        | 3.77%   |
| G.Skill             | 67        | 3.12%   |
| Unknown             | 63        | 2.93%   |
| Elpida              | 47        | 2.19%   |
| A-DATA Technology   | 42        | 1.95%   |
| Ramaxel Technology  | 37        | 1.72%   |
| Nanya Technology    | 37        | 1.72%   |
| Smart               | 26        | 1.21%   |
| Team                | 23        | 1.07%   |
| Transcend           | 19        | 0.88%   |
| Patriot             | 18        | 0.84%   |
| Apacer              | 11        | 0.51%   |
| Unknown (ABCD)      | 10        | 0.47%   |
| Teikon              | 9         | 0.42%   |
| Goodram             | 8         | 0.37%   |
| Avant               | 8         | 0.37%   |
| PNY                 | 6         | 0.28%   |
| High Bridge         | 6         | 0.28%   |
| AMD                 | 6         | 0.28%   |
| Smart Brazil        | 5         | 0.23%   |
| Atermiter           | 5         | 0.23%   |
| ASint Technology    | 5         | 0.23%   |
| Silicon Power       | 3         | 0.14%   |
| SHARETRONIC         | 3         | 0.14%   |
| Kingmax             | 3         | 0.14%   |
| 48spaces            | 3         | 0.14%   |
| Toshiba             | 2         | 0.09%   |
| Sesame              | 2         | 0.09%   |
| Multilaser          | 2         | 0.09%   |
| Lexar               | 2         | 0.09%   |
| Lenovo              | 2         | 0.09%   |
| GSkill              | 2         | 0.09%   |
| Goldkey             | 2         | 0.09%   |
| GeIL                | 2         | 0.09%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Unknown                                                | 63        | 2.73%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s  | 26        | 1.13%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s             | 24        | 1.04%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s | 21        | 0.91%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s  | 19        | 0.82%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s  | 16        | 0.69%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s | 15        | 0.65%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                   | 14        | 0.61%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s  | 13        | 0.56%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s | 12        | 0.52%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s  | 12        | 0.52%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                   | 11        | 0.48%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s  | 11        | 0.48%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s  | 11        | 0.48%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s             | 10        | 0.43%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3200MT/s     | 9         | 0.39%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s | 9         | 0.39%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 1333MT/s  | 9         | 0.39%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s  | 9         | 0.39%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s               | 8         | 0.35%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s           | 8         | 0.35%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s | 8         | 0.35%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s  | 8         | 0.35%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s  | 8         | 0.35%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s  | 8         | 0.35%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s  | 8         | 0.35%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s    | 8         | 0.35%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3200MT/s   | 8         | 0.35%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s            | 7         | 0.3%    |
| Unknown RAM Module 4GB SODIMM DDR3                     | 7         | 0.3%    |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s              | 7         | 0.3%    |
| Unknown RAM Module 2GB SODIMM DDR2                     | 7         | 0.3%    |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s | 7         | 0.3%    |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s | 7         | 0.3%    |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s            | 7         | 0.3%    |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s    | 7         | 0.3%    |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3200MT/s  | 7         | 0.3%    |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s            | 6         | 0.26%   |
| Unknown RAM Module 2GB DIMM 800MT/s                    | 6         | 0.26%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s | 6         | 0.26%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 835       | 46.6%   |
| DDR4    | 648       | 36.16%  |
| DDR2    | 150       | 8.37%   |
| Unknown | 73        | 4.07%   |
| SDRAM   | 26        | 1.45%   |
| LPDDR3  | 21        | 1.17%   |
| LPDDR4  | 18        | 1%      |
| DDR     | 9         | 0.5%    |
| DDR5    | 6         | 0.33%   |
| DRAM    | 3         | 0.17%   |
| LPDDR5  | 2         | 0.11%   |
| RAM     | 1         | 0.06%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 1001      | 55.8%   |
| DIMM         | 720       | 40.13%  |
| Row Of Chips | 40        | 2.23%   |
| Chip         | 17        | 0.95%   |
| Unknown      | 9         | 0.5%    |
| FB-DIMM      | 4         | 0.22%   |
| RIMM         | 3         | 0.17%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 701       | 34.67%  |
| 8192  | 620       | 30.66%  |
| 2048  | 408       | 20.18%  |
| 16384 | 188       | 9.3%    |
| 1024  | 73        | 3.61%   |
| 32768 | 29        | 1.43%   |
| 512   | 2         | 0.1%    |
| 1491  | 1         | 0.05%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 499       | 25.59%  |
| 1333    | 261       | 13.38%  |
| 2400    | 191       | 9.79%   |
| 3200    | 175       | 8.97%   |
| 2667    | 155       | 7.95%   |
| 2133    | 133       | 6.82%   |
| 667     | 95        | 4.87%   |
| 800     | 75        | 3.85%   |
| 1067    | 70        | 3.59%   |
| 1334    | 61        | 3.13%   |
| Unknown | 47        | 2.41%   |
| 1867    | 35        | 1.79%   |
| 2666    | 27        | 1.38%   |
| 1066    | 24        | 1.23%   |
| 3600    | 15        | 0.77%   |
| 3000    | 11        | 0.56%   |
| 1866    | 11        | 0.56%   |
| 2933    | 9         | 0.46%   |
| 533     | 9         | 0.46%   |
| 400     | 8         | 0.41%   |
| 4800    | 5         | 0.26%   |
| 2048    | 5         | 0.26%   |
| 975     | 4         | 0.21%   |
| 333     | 4         | 0.21%   |
| 6400    | 3         | 0.15%   |
| 4267    | 3         | 0.15%   |
| 3733    | 3         | 0.15%   |
| 4000    | 2         | 0.1%    |
| 1639    | 2         | 0.1%    |
| 4400    | 1         | 0.05%   |
| 4266    | 1         | 0.05%   |
| 3400    | 1         | 0.05%   |
| 3333    | 1         | 0.05%   |
| 2866    | 1         | 0.05%   |
| 2800    | 1         | 0.05%   |
| 1332    | 1         | 0.05%   |
| 1200    | 1         | 0.05%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Brother Industries    | 9         | 37.5%   |
| Hewlett-Packard       | 8         | 33.33%  |
| Lexmark International | 2         | 8.33%   |
| Seiko Epson           | 1         | 4.17%   |
| Samsung Electronics   | 1         | 4.17%   |
| Ricoh                 | 1         | 4.17%   |
| Prolific Technology   | 1         | 4.17%   |
| Kyocera               | 1         | 4.17%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                                                                                                             | Computers | Percent |
|-------------------------------------------------------------------------------------------------------------------|-----------|---------|
| Seiko Epson USB2.0 Printer (Hi-speed)                                                                             | 1         | 4%      |
| Samsung ML-2010P Mono Laser Printer                                                                               | 1         | 4%      |
| Ricoh SP 112                                                                                                      | 1         | 4%      |
| Prolific PL2305 Parallel Port                                                                                     | 1         | 4%      |
| Lexmark International SINDOH A603_A608 Print                                                                      | 1         | 4%      |
| Lexmark International Lexmark MS710 Print                                                                         | 1         | 4%      |
| Kyocera FS-1025MFP                                                                                                | 1         | 4%      |
| HP LaserJet P3005                                                                                                 | 1         | 4%      |
| HP LaserJet 3390                                                                                                  | 1         | 4%      |
| HP LaserJet 2200                                                                                                  | 1         | 4%      |
| HP LaserJet 1200                                                                                                  | 1         | 4%      |
| HP LaserJet 1020                                                                                                  | 1         | 4%      |
| HP HP LaserJet P2035 HP Print                                                                                     | 1         | 4%      |
| HP HP LaserJet MFP E52645 LaserJet 0 LaserJet 0 LaserJet 1 LaserJet 1 LaserJet 2 LaserJet 2 LaserJet 3 LaserJet 3 | 1         | 4%      |
| HP DeskJet 5850c                                                                                                  | 1         | 4%      |
| HP Color LaserJet CP1215                                                                                          | 1         | 4%      |
| Brother MFC-L2685DW                                                                                               | 1         | 4%      |
| Brother MFC-J200                                                                                                  | 1         | 4%      |
| Brother MFC-7360N                                                                                                 | 1         | 4%      |
| Brother HL-L3270CDW series                                                                                        | 1         | 4%      |
| Brother HL-L2310D series                                                                                          | 1         | 4%      |
| Brother HL-L2300D series                                                                                          | 1         | 4%      |
| Brother HL-1430 Laser Printer                                                                                     | 1         | 4%      |
| Brother DCP-J152W                                                                                                 | 1         | 4%      |
| Brother DCP-J100                                                                                                  | 1         | 4%      |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart_bsd/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Canon       | 8         | 88.89%  |
| Seiko Epson | 1         | 11.11%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart_bsd/scanner_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                                                             | 2         | 22.22%  |
| Seiko Epson WF-2860 Series EPSON Scanner USB2.0 Printer EPSON Utility USB2.0 Faxout | 1         | 11.11%  |
| Canon CanoScan N650U/N656U                                                          | 1         | 11.11%  |
| Canon CanoScan N1240U/LiDE 30                                                       | 1         | 11.11%  |
| Canon CanoScan LiDE 700F                                                            | 1         | 11.11%  |
| Canon CanoScan LiDE 220                                                             | 1         | 11.11%  |
| Canon CanoScan LiDE 120                                                             | 1         | 11.11%  |
| Canon CanoScan LiDE 100                                                             | 1         | 11.11%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 195       | 24.68%  |
| Bison Electronics                      | 77        | 9.75%   |
| Microdia                               | 68        | 8.61%   |
| IMC Networks                           | 64        | 8.1%    |
| Realtek Semiconductor                  | 62        | 7.85%   |
| Sunplus Innovation Technology          | 43        | 5.44%   |
| Logitech                               | 27        | 3.42%   |
| Suyin                                  | 26        | 3.29%   |
| Apple                                  | 25        | 3.16%   |
| Syntek                                 | 22        | 2.78%   |
| Quanta                                 | 21        | 2.66%   |
| Lite-On Technology                     | 21        | 2.66%   |
| Cheng Uei Precision Industry (Foxlink) | 20        | 2.53%   |
| Alcor Micro                            | 15        | 1.9%    |
| Z-Star Microelectronics                | 13        | 1.65%   |
| Silicon Motion                         | 13        | 1.65%   |
| Lenovo                                 | 10        | 1.27%   |
| Luxvisions Innotech Limited            | 8         | 1.01%   |
| ALi                                    | 7         | 0.89%   |
| Importek                               | 6         | 0.76%   |
| ARC International                      | 4         | 0.51%   |
| Supreme Electronics                    | 3         | 0.38%   |
| Ricoh                                  | 3         | 0.38%   |
| Intel                                  | 3         | 0.38%   |
| GEMBIRD                                | 3         | 0.38%   |
| Arkmicro Technologies                  | 3         | 0.38%   |
| Primax Electronics                     | 2         | 0.25%   |
| Jiangxi Shinetech Optical              | 2         | 0.25%   |
| Hewlett-Packard                        | 2         | 0.25%   |
| Genesys Logic                          | 2         | 0.25%   |
| Generalplus Technology                 | 2         | 0.25%   |
| DigiTech                               | 2         | 0.25%   |
| Creative Technology                    | 2         | 0.25%   |
| Y Media                                | 1         | 0.13%   |
| ValueHD                                | 1         | 0.13%   |
| USB Camera                             | 1         | 0.13%   |
| Unknown                                | 1         | 0.13%   |
| Trust                                  | 1         | 0.13%   |
| Tripath Technology                     | 1         | 0.13%   |
| SHENZHEN AONI ELECTRONIC               | 1         | 0.13%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                     | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Chicony Integrated Camera                 | 47        | 5.92%   |
| Bison Integrated Camera                   | 25        | 3.15%   |
| Microdia Integrated_Webcam_HD             | 20        | 2.52%   |
| Sunplus Integrated_Webcam_HD              | 15        | 1.89%   |
| Realtek USB 2.0 PC Camera                 | 14        | 1.76%   |
| Realtek Integrated_Webcam_HD              | 14        | 1.76%   |
| Lite-On Integrated Camera                 | 14        | 1.76%   |
| Chicony Lenovo Integrated Camera (0.3MP)  | 14        | 1.76%   |
| Chicony HD WebCam                         | 13        | 1.64%   |
| Bison Lenovo EasyCamera                   | 13        | 1.64%   |
| IMC Networks Integrated Camera            | 12        | 1.51%   |
| Apple FaceTime HD Camera                  | 11        | 1.39%   |
| Syntek Lenovo EasyCamera                  | 10        | 1.26%   |
| Apple FaceTime HD Camera (Built-in)       | 10        | 1.26%   |
| Realtek USB Camera                        | 9         | 1.13%   |
| Microdia Integrated Webcam                | 9         | 1.13%   |
| IMC Networks Realtek PC Camera            | 9         | 1.13%   |
| Microdia USB 2.0 Camera                   | 8         | 1.01%   |
| Logitech Webcam C270                      | 8         | 1.01%   |
| Chicony FJ Camera                         | 8         | 1.01%   |
| Microdia Dell Laptop Integrated Webcam HD | 7         | 0.88%   |
| IMC Networks EasyCamera                   | 7         | 0.88%   |
| Chicony HP HD Webcam [Fixed]              | 7         | 0.88%   |
| Bison ThinkPad Integrated Camera          | 7         | 0.88%   |
| Syntek EasyCamera                         | 6         | 0.76%   |
| Chicony USB2.0 HD UVC WebCam              | 6         | 0.76%   |
| Chicony Realtek DMFT RGB                  | 6         | 0.76%   |
| Chicony Lenovo EasyCamera                 | 6         | 0.76%   |
| Bison SunplusIT Integrated Camera         | 6         | 0.76%   |
| Bison HD Webcam                           | 6         | 0.76%   |
| Suyin Integrated_Webcam_HD                | 5         | 0.63%   |
| Suyin Acer/HP Integrated Webcam [CN0314]  | 5         | 0.63%   |
| Quanta HP TrueVision HD Camera            | 5         | 0.63%   |
| Microdia Laptop_Integrated_Webcam_HD      | 5         | 0.63%   |
| Lenovo Integrated Webcam [R5U877]         | 5         | 0.63%   |
| IMC Networks UVC VGA Webcam               | 5         | 0.63%   |
| IMC Networks USB2.0 HD UVC WebCam         | 5         | 0.63%   |
| Chicony USB2.0 VGA UVC WebCam             | 5         | 0.63%   |
| Chicony Integrated Camera [ThinkPad]      | 5         | 0.63%   |
| Chicony EasyCamera                        | 5         | 0.63%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 72        | 44.72%  |
| AuthenTec                  | 22        | 13.66%  |
| Upek                       | 19        | 11.8%   |
| Synaptics                  | 12        | 7.45%   |
| STMicroelectronics         | 11        | 6.83%   |
| Elan Microelectronics      | 9         | 5.59%   |
| Broadcom                   | 6         | 3.73%   |
| Shenzhen Goodix Technology | 4         | 2.48%   |
| LighTuning Technology      | 4         | 2.48%   |
| FocalTech Systems          | 1         | 0.62%   |
| Fingerprint Cards          | 1         | 0.62%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                             | Computers | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                            | 17        | 10.56%  |
| Validity Sensors VFS 5011 fingerprint sensor                                      | 16        | 9.94%   |
| Validity Sensors VFS495 Fingerprint Reader                                        | 12        | 7.45%   |
| Validity Sensors Synaptics WBDI                                                   | 11        | 6.83%   |
| STMicroelectronics Fingerprint Reader                                             | 11        | 6.83%   |
| Validity Sensors VFS5011 Fingerprint Reader                                       | 9         | 5.59%   |
| Elan Fingerprint Sensor                                                           | 8         | 4.97%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor      | 6         | 3.73%   |
| AuthenTec AES1600                                                                 | 6         | 3.73%   |
| AuthenTec AES2810                                                                 | 5         | 3.11%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                                 | 4         | 2.48%   |
| Validity Sensors VFS491                                                           | 4         | 2.48%   |
| Validity Sensors Fingerprint scanner                                              | 4         | 2.48%   |
| Synaptics WBDI Fingerprint Reader USB 086                                         | 4         | 2.48%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                                 | 4         | 2.48%   |
| AuthenTec AES2501 Fingerprint Sensor                                              | 4         | 2.48%   |
| AuthenTec AES1660                                                                 | 4         | 2.48%   |
| Validity Sensors VFS471 Fingerprint Reader                                        | 3         | 1.86%   |
| Shenzhen Goodix Fingerprint Reader                                                | 3         | 1.86%   |
| Validity Sensors VFS451 Fingerprint Reader                                        | 2         | 1.24%   |
| Validity Sensors VFS101 Fingerprint Reader                                        | 2         | 1.24%   |
| Validity Sensors Swipe Fingerprint Sensor                                         | 2         | 1.24%   |
| Upek TCS5B Fingerprint sensor                                                     | 2         | 1.24%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                                  | 2         | 1.24%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                       | 2         | 1.24%   |
| AuthenTec AES2660                                                                 | 2         | 1.24%   |
| Validity Sensors VFS301 Fingerprint Reader                                        | 1         | 0.62%   |
| Validity Sensors VFS Fingerprint sensor                                           | 1         | 0.62%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint        | 1         | 0.62%   |
| Synaptics WBDI                                                                    | 1         | 0.62%   |
| Synaptics UWP WBDI Device                                                         | 1         | 0.62%   |
| Shenzhen Goodix Fingerprint Reader SGX                                            | 1         | 0.62%   |
| LighTuning Fingerprint Sensor                                                     | 1         | 0.62%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                         | 1         | 0.62%   |
| FocalTech Systems FocalTech Fingerprint Device Realtek USB2.0 Finger Print Bridge | 1         | 0.62%   |
| Fingerprint Cards FPC Fingerprint Reader                                          | 1         | 0.62%   |
| Elan WBF Fingerprint Sensor                                                       | 1         | 0.62%   |
| AuthenTec AES1660 Fingerprint Sensor                                              | 1         | 0.62%   |

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
| 1     | 749       | 40.55%  |
| 0     | 460       | 24.91%  |
| 2     | 426       | 23.06%  |
| 3     | 153       | 8.28%   |
| 4     | 47        | 2.54%   |
| 5     | 10        | 0.54%   |
| 6     | 2         | 0.11%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 1145      | 53.6%   |
| Net/wireless             | 280       | 13.11%  |
| Card reader              | 234       | 10.96%  |
| Bluetooth                | 173       | 8.1%    |
| Fingerprint reader       | 158       | 7.4%    |
| Sound                    | 54        | 2.53%   |
| Firewire controller      | 29        | 1.36%   |
| Network                  | 23        | 1.08%   |
| Storage                  | 16        | 0.75%   |
| Net/ethernet             | 13        | 0.61%   |
| Storage/raid             | 5         | 0.23%   |
| Dvb card                 | 5         | 0.23%   |
| Storage/nvme             | 1         | 0.05%   |

