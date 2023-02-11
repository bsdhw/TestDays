helloSystem 0.4.0 - Tested Hardware & Statistics
------------------------------------------------

A project to collect tested hardware configurations for helloSystem 0.4.0.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/helloSystem_0.4.0/Desktop/README.md) and [notebooks](/Dist/helloSystem_0.4.0/Notebook/README.md).

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

Total: 244

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Acidanther... | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [9b6f9eac6f](https://bsd-hardware.info/?probe=9b6f9eac6f) | Apr 01, 2022 |
| Apple         | MacBookPro4,1               | Notebook    | [d852363467](https://bsd-hardware.info/?probe=d852363467) | Feb 08, 2022 |
| Apple         | MacBookPro4,1               | Notebook    | [f05ce66a9a](https://bsd-hardware.info/?probe=f05ce66a9a) | Feb 08, 2022 |
| HP            | 81B4 01                     | Desktop     | [5b28c9bb75](https://bsd-hardware.info/?probe=5b28c9bb75) | Sep 20, 2021 |
| Dell          | 0MGK50 A02                  | Desktop     | [2468e9d0ba](https://bsd-hardware.info/?probe=2468e9d0ba) | Aug 17, 2021 |
| Samsung       | 3570R/370R/470R/450R/510... | Notebook    | [31d42f4469](https://bsd-hardware.info/?probe=31d42f4469) | Jul 05, 2021 |
| MSI           | G41M-P25                    | Desktop     | [5cc75b4df0](https://bsd-hardware.info/?probe=5cc75b4df0) | Jun 25, 2021 |
| ASUSTek       | Z97-A-USB31                 | Desktop     | [7fe10badbb](https://bsd-hardware.info/?probe=7fe10badbb) | Jun 11, 2021 |
| Pegatron      | T12Ah                       | Notebook    | [50d37406df](https://bsd-hardware.info/?probe=50d37406df) | Jun 06, 2021 |
| HP            | Pavilion dv4                | Notebook    | [27f912e4e4](https://bsd-hardware.info/?probe=27f912e4e4) | May 28, 2021 |
| Lenovo        | Board                       | Desktop     | [1d6f23a5de](https://bsd-hardware.info/?probe=1d6f23a5de) | May 24, 2021 |
| Dell          | Inspiron 3442               | Notebook    | [0d1d75a914](https://bsd-hardware.info/?probe=0d1d75a914) | May 23, 2021 |
| Dell          | Latitude E6410              | Notebook    | [211fe874fd](https://bsd-hardware.info/?probe=211fe874fd) | May 22, 2021 |
| Apple         | Mac-F221BEC8                | Desktop     | [869f003493](https://bsd-hardware.info/?probe=869f003493) | May 17, 2021 |
| Dell          | Inspiron 3442               | Notebook    | [076dc91b26](https://bsd-hardware.info/?probe=076dc91b26) | May 13, 2021 |
| HP            | 240 G5 Notebook PC          | Notebook    | [f9c67b360f](https://bsd-hardware.info/?probe=f9c67b360f) | May 08, 2021 |
| Dell          | Latitude E5570              | Notebook    | [c8477da717](https://bsd-hardware.info/?probe=c8477da717) | May 07, 2021 |
| MSI           | B450M-A PRO MAX             | Desktop     | [6317bd7dbd](https://bsd-hardware.info/?probe=6317bd7dbd) | May 05, 2021 |
| Apple         | MacBookPro11,3              | Notebook    | [1c9feef8e7](https://bsd-hardware.info/?probe=1c9feef8e7) | May 03, 2021 |
| Dell          | Inspiron 7373               | Convertible | [dc37c53e48](https://bsd-hardware.info/?probe=dc37c53e48) | May 02, 2021 |
| Notebook      | W65KJ1_KK1                  | Notebook    | [d4d0b819bc](https://bsd-hardware.info/?probe=d4d0b819bc) | Apr 24, 2021 |
| ASUSTek       | ROG STRIX B360-F GAMING     | Desktop     | [6e874538cb](https://bsd-hardware.info/?probe=6e874538cb) | Apr 20, 2021 |
| HP            | 18E7                        | Desktop     | [e6354de524](https://bsd-hardware.info/?probe=e6354de524) | Apr 20, 2021 |
| Gateway       | NE56R                       | Notebook    | [bbbc827581](https://bsd-hardware.info/?probe=bbbc827581) | Apr 16, 2021 |
| Dell          | Latitude E7240              | Notebook    | [1dbd9a5cee](https://bsd-hardware.info/?probe=1dbd9a5cee) | Apr 13, 2021 |
| Lenovo        | ThinkPad T400 7417TPU       | Notebook    | [981517a51a](https://bsd-hardware.info/?probe=981517a51a) | Apr 13, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [5d3d014284](https://bsd-hardware.info/?probe=5d3d014284) | Apr 12, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [ffcc46ea0b](https://bsd-hardware.info/?probe=ffcc46ea0b) | Apr 12, 2021 |
| Gateway       | NE56R                       | Notebook    | [af262c2350](https://bsd-hardware.info/?probe=af262c2350) | Apr 11, 2021 |
| ASUSTek       | TP500LNG                    | Notebook    | [6501322932](https://bsd-hardware.info/?probe=6501322932) | Apr 06, 2021 |
| Panasonic     | CF-NX1GDHYS                 | Notebook    | [6bbadba65d](https://bsd-hardware.info/?probe=6bbadba65d) | Apr 04, 2021 |
| ASUSTek       | X540UP                      | Notebook    | [a9c4506364](https://bsd-hardware.info/?probe=a9c4506364) | Mar 28, 2021 |
| Dell          | 0NW6H5 A00                  | Desktop     | [1499695aae](https://bsd-hardware.info/?probe=1499695aae) | Mar 25, 2021 |
| ASUSTek       | G75VW                       | Notebook    | [cf4b3e0c6f](https://bsd-hardware.info/?probe=cf4b3e0c6f) | Mar 23, 2021 |
| ASUSTek       | G75VW                       | Notebook    | [4a59793120](https://bsd-hardware.info/?probe=4a59793120) | Mar 23, 2021 |
| ASRock        | H71M-DGS                    | Desktop     | [d05d6281d3](https://bsd-hardware.info/?probe=d05d6281d3) | Mar 21, 2021 |
| HP            | 1825                        | Desktop     | [15e822a4dc](https://bsd-hardware.info/?probe=15e822a4dc) | Mar 20, 2021 |
| Dell          | Inspiron 7370               | Notebook    | [7e2328dda3](https://bsd-hardware.info/?probe=7e2328dda3) | Mar 20, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [f9c3fc3b84](https://bsd-hardware.info/?probe=f9c3fc3b84) | Mar 19, 2021 |
| Pegatron      | IPM41-D3                    | Desktop     | [fdfc8e2b9b](https://bsd-hardware.info/?probe=fdfc8e2b9b) | Mar 17, 2021 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [9f780aff14](https://bsd-hardware.info/?probe=9f780aff14) | Mar 16, 2021 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [83aacceb4c](https://bsd-hardware.info/?probe=83aacceb4c) | Mar 16, 2021 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [adb0e59aa1](https://bsd-hardware.info/?probe=adb0e59aa1) | Mar 15, 2021 |
| Dell          | Inspiron 3442               | Notebook    | [f156951052](https://bsd-hardware.info/?probe=f156951052) | Mar 14, 2021 |
| Supermicro    | X10SRA                      | Server      | [4da7433e8b](https://bsd-hardware.info/?probe=4da7433e8b) | Mar 14, 2021 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [416039a620](https://bsd-hardware.info/?probe=416039a620) | Mar 13, 2021 |
| Lenovo        | ThinkPad T61 766416U        | Notebook    | [cf75f7c9cb](https://bsd-hardware.info/?probe=cf75f7c9cb) | Mar 13, 2021 |
| Lenovo        | ThinkPad T61 766416U        | Notebook    | [b90180457c](https://bsd-hardware.info/?probe=b90180457c) | Mar 13, 2021 |
| ASUSTek       | BM6AD_BM1AD_BP1AD           | Desktop     | [60dedd3dcc](https://bsd-hardware.info/?probe=60dedd3dcc) | Mar 13, 2021 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [436706f322](https://bsd-hardware.info/?probe=436706f322) | Mar 12, 2021 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [002e54c256](https://bsd-hardware.info/?probe=002e54c256) | Mar 12, 2021 |
| Dell          | 0HN7XN A01                  | Desktop     | [3339a68c44](https://bsd-hardware.info/?probe=3339a68c44) | Mar 12, 2021 |
| Apple         | MacBookPro5,5               | Notebook    | [f46146b79e](https://bsd-hardware.info/?probe=f46146b79e) | Mar 11, 2021 |
| Apple         | MacBookPro5,5               | Notebook    | [c1ed4c02b8](https://bsd-hardware.info/?probe=c1ed4c02b8) | Mar 11, 2021 |
| ASUSTek       | M4A78                       | Desktop     | [00dc46f0a1](https://bsd-hardware.info/?probe=00dc46f0a1) | Mar 10, 2021 |
| Lenovo        | ThinkPad T530 2392ASU       | Notebook    | [39f3a4f234](https://bsd-hardware.info/?probe=39f3a4f234) | Mar 09, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [66a223add9](https://bsd-hardware.info/?probe=66a223add9) | Mar 08, 2021 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [b79872a08e](https://bsd-hardware.info/?probe=b79872a08e) | Mar 07, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [5e5632d9b6](https://bsd-hardware.info/?probe=5e5632d9b6) | Mar 07, 2021 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [a03927cc2e](https://bsd-hardware.info/?probe=a03927cc2e) | Mar 06, 2021 |
| Lenovo        | 3000 N200 0769AP2           | Notebook    | [6b81593de9](https://bsd-hardware.info/?probe=6b81593de9) | Mar 06, 2021 |
| Medion        | H61H2-LM3                   | Desktop     | [01df19257a](https://bsd-hardware.info/?probe=01df19257a) | Mar 05, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [b03cb1f957](https://bsd-hardware.info/?probe=b03cb1f957) | Mar 05, 2021 |
| Gigabyte      | Z77M-D3H                    | Desktop     | [2f1e8f315f](https://bsd-hardware.info/?probe=2f1e8f315f) | Mar 05, 2021 |
| Dell          | 03CDJK A01                  | All in one  | [fc655524ab](https://bsd-hardware.info/?probe=fc655524ab) | Mar 04, 2021 |
| VeryPC        | S400                        | Desktop     | [77b744169b](https://bsd-hardware.info/?probe=77b744169b) | Mar 04, 2021 |
| ASRock        | 970A-G                      | Desktop     | [3e474f93cf](https://bsd-hardware.info/?probe=3e474f93cf) | Mar 04, 2021 |
| Gigabyte      | Z87-D3HP-CF                 | Desktop     | [4c2d7f9b3b](https://bsd-hardware.info/?probe=4c2d7f9b3b) | Mar 03, 2021 |
| ASUSTek       | X55CR                       | Notebook    | [e887ee2ff5](https://bsd-hardware.info/?probe=e887ee2ff5) | Mar 03, 2021 |
| ASUSTek       | X55CR                       | Notebook    | [e1e4548d22](https://bsd-hardware.info/?probe=e1e4548d22) | Mar 03, 2021 |
| HP            | 339A                        | Desktop     | [6b1072ee33](https://bsd-hardware.info/?probe=6b1072ee33) | Mar 01, 2021 |
| HP            | 18E7                        | Desktop     | [091b80c404](https://bsd-hardware.info/?probe=091b80c404) | Mar 01, 2021 |
| Intel         | NUC8BEB J72693-306          | Mini pc     | [0951c73dba](https://bsd-hardware.info/?probe=0951c73dba) | Mar 01, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [950cf51db1](https://bsd-hardware.info/?probe=950cf51db1) | Feb 28, 2021 |
| ASUSTek       | G1S                         | Notebook    | [593c12aa06](https://bsd-hardware.info/?probe=593c12aa06) | Feb 28, 2021 |
| ASRock        | AB350 Pro4                  | Desktop     | [8e0afc66b5](https://bsd-hardware.info/?probe=8e0afc66b5) | Feb 26, 2021 |
| ASRock        | H61M-VG3                    | Desktop     | [68d5d3c6cd](https://bsd-hardware.info/?probe=68d5d3c6cd) | Feb 26, 2021 |
| ASUSTek       | X555LAB                     | Notebook    | [b0364fffaf](https://bsd-hardware.info/?probe=b0364fffaf) | Feb 25, 2021 |
| Intel         | NUC7JYB J67969-401          | Mini pc     | [8e78a839a5](https://bsd-hardware.info/?probe=8e78a839a5) | Feb 25, 2021 |
| ASUSTek       | X555LAB                     | Notebook    | [45d57c2be0](https://bsd-hardware.info/?probe=45d57c2be0) | Feb 24, 2021 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [13c1f72630](https://bsd-hardware.info/?probe=13c1f72630) | Feb 24, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [7f35ef7fa9](https://bsd-hardware.info/?probe=7f35ef7fa9) | Feb 23, 2021 |
| Lenovo        | Z50-70 20354                | Notebook    | [d3d9dc620f](https://bsd-hardware.info/?probe=d3d9dc620f) | Feb 23, 2021 |
| Intel         | H61                         | Desktop     | [a8ae96a0ab](https://bsd-hardware.info/?probe=a8ae96a0ab) | Feb 23, 2021 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [7def696a61](https://bsd-hardware.info/?probe=7def696a61) | Feb 22, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [8390039d0b](https://bsd-hardware.info/?probe=8390039d0b) | Feb 22, 2021 |
| ASUSTek       | PRIME Z390M-PLUS            | Desktop     | [58c6bf426e](https://bsd-hardware.info/?probe=58c6bf426e) | Feb 22, 2021 |
| Lenovo        | ThinkPad X240 20AMS4V000    | Notebook    | [cbfa45fe44](https://bsd-hardware.info/?probe=cbfa45fe44) | Feb 22, 2021 |
| MSI           | A78M-E35                    | Desktop     | [0a1462e4a7](https://bsd-hardware.info/?probe=0a1462e4a7) | Feb 22, 2021 |
| Dell          | 0M863N A01                  | Desktop     | [8dd5cd14a9](https://bsd-hardware.info/?probe=8dd5cd14a9) | Feb 22, 2021 |
| ASUSTek       | K46CA                       | Notebook    | [f286c1e784](https://bsd-hardware.info/?probe=f286c1e784) | Feb 21, 2021 |
| Gigabyte      | Z77M-D3H                    | Desktop     | [d0b9e29aed](https://bsd-hardware.info/?probe=d0b9e29aed) | Feb 21, 2021 |
| ASUSTek       | GRYPHON Z97 ARMOR EDITIO... | Desktop     | [405b36b911](https://bsd-hardware.info/?probe=405b36b911) | Feb 21, 2021 |
| ASUSTek       | X751LN                      | Notebook    | [a88cfd7fdd](https://bsd-hardware.info/?probe=a88cfd7fdd) | Feb 21, 2021 |
| Lenovo        | ThinkPad T440p 20AWS0U50... | Notebook    | [5d86c90af1](https://bsd-hardware.info/?probe=5d86c90af1) | Feb 21, 2021 |
| Dell          | 0YK962 A03                  | Server      | [e98f23cd45](https://bsd-hardware.info/?probe=e98f23cd45) | Feb 21, 2021 |
| Toshiba       | Satellite U500              | Notebook    | [feae098542](https://bsd-hardware.info/?probe=feae098542) | Feb 20, 2021 |
| Packard Be... | EasyNote TS11HR             | Notebook    | [1adcd64182](https://bsd-hardware.info/?probe=1adcd64182) | Feb 20, 2021 |
| ASUSTek       | X556UA                      | Notebook    | [6bbf9d6e29](https://bsd-hardware.info/?probe=6bbf9d6e29) | Feb 20, 2021 |
| ASUSTek       | PRIME H310M-A               | Desktop     | [cda0bac40d](https://bsd-hardware.info/?probe=cda0bac40d) | Feb 20, 2021 |
| Gigabyte      | GA-870-UD3P                 | Desktop     | [e228db2983](https://bsd-hardware.info/?probe=e228db2983) | Feb 20, 2021 |
| Dell          | 0M863N A01                  | Desktop     | [94f2627d79](https://bsd-hardware.info/?probe=94f2627d79) | Feb 20, 2021 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [d60f06a51d](https://bsd-hardware.info/?probe=d60f06a51d) | Feb 20, 2021 |
| Intel         | NUC7i7DNB J83500-202        | Mini pc     | [3802b33f17](https://bsd-hardware.info/?probe=3802b33f17) | Feb 20, 2021 |
| ASRock        | 970 Extreme3                | Desktop     | [daa7afc688](https://bsd-hardware.info/?probe=daa7afc688) | Feb 19, 2021 |
| Apple         | MacBook5,1                  | Notebook    | [1a374f79df](https://bsd-hardware.info/?probe=1a374f79df) | Feb 19, 2021 |
| ASRock        | Z170 Pro4/D3                | Desktop     | [7df0653726](https://bsd-hardware.info/?probe=7df0653726) | Feb 19, 2021 |
| Acer          | Aspire ES1-533              | Notebook    | [045cf81f15](https://bsd-hardware.info/?probe=045cf81f15) | Feb 18, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [71cfece3a7](https://bsd-hardware.info/?probe=71cfece3a7) | Feb 18, 2021 |
| Acidanther... | Mac-42FD25EABCABB274 iMa... | All in one  | [1917cd73e1](https://bsd-hardware.info/?probe=1917cd73e1) | Feb 18, 2021 |
| ASRock        | B365M Pro4                  | Desktop     | [1c438d977e](https://bsd-hardware.info/?probe=1c438d977e) | Feb 18, 2021 |
| HARDKERNEL    | ODROID-H2                   | Desktop     | [6fe9279f1f](https://bsd-hardware.info/?probe=6fe9279f1f) | Feb 18, 2021 |
| Fujitsu       | D3517-A1 S26361-D3517-A1    | Desktop     | [8891e427e1](https://bsd-hardware.info/?probe=8891e427e1) | Feb 17, 2021 |
| Dell          | Inspiron 3521               | Notebook    | [10490aef33](https://bsd-hardware.info/?probe=10490aef33) | Feb 17, 2021 |
| Dell          | Latitude E6330              | Notebook    | [abe1869a95](https://bsd-hardware.info/?probe=abe1869a95) | Feb 17, 2021 |
| Fujitsu       | LIFEBOOK E744               | Notebook    | [fc2f449a8a](https://bsd-hardware.info/?probe=fc2f449a8a) | Feb 17, 2021 |
| Dell          | Latitude 7390               | Notebook    | [3fe6eff89a](https://bsd-hardware.info/?probe=3fe6eff89a) | Feb 17, 2021 |
| Lenovo        | NO DPK                      | Desktop     | [1ec71f814b](https://bsd-hardware.info/?probe=1ec71f814b) | Feb 17, 2021 |
| Dell          | Venue 11 Pro 7140           | Notebook    | [1a49b7921a](https://bsd-hardware.info/?probe=1a49b7921a) | Feb 17, 2021 |
| Lenovo        | ThinkServer TS140           | Desktop     | [29fb200d1a](https://bsd-hardware.info/?probe=29fb200d1a) | Feb 17, 2021 |
| Lenovo        | ThinkPad T430 2349PMP       | Notebook    | [23de6449ad](https://bsd-hardware.info/?probe=23de6449ad) | Feb 17, 2021 |
| Dell          | Latitude E4300              | Notebook    | [d5051ef185](https://bsd-hardware.info/?probe=d5051ef185) | Feb 16, 2021 |
| Pegatron      | IPM41-D3                    | Desktop     | [ffc1292c18](https://bsd-hardware.info/?probe=ffc1292c18) | Feb 16, 2021 |
| Lenovo        | Board                       | Desktop     | [966a037b6d](https://bsd-hardware.info/?probe=966a037b6d) | Feb 16, 2021 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [c112c8a9fe](https://bsd-hardware.info/?probe=c112c8a9fe) | Feb 16, 2021 |
| MSI           | G41M-P25                    | Desktop     | [3e037419d7](https://bsd-hardware.info/?probe=3e037419d7) | Feb 16, 2021 |
| Lenovo        | U310                        | Notebook    | [ccec69b736](https://bsd-hardware.info/?probe=ccec69b736) | Feb 16, 2021 |
| Gigabyte      | B360N WIFI-CF               | Desktop     | [0a48ee3b16](https://bsd-hardware.info/?probe=0a48ee3b16) | Feb 16, 2021 |
| Google        | Guado                       | Desktop     | [f6473eeb71](https://bsd-hardware.info/?probe=f6473eeb71) | Feb 16, 2021 |
| Lenovo        | U310                        | Notebook    | [83805a17c5](https://bsd-hardware.info/?probe=83805a17c5) | Feb 16, 2021 |
| Lenovo        | U310                        | Notebook    | [111385095d](https://bsd-hardware.info/?probe=111385095d) | Feb 16, 2021 |
| Apple         | MacBookAir4,2               | Notebook    | [7d8419c918](https://bsd-hardware.info/?probe=7d8419c918) | Feb 16, 2021 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [19f307ff6d](https://bsd-hardware.info/?probe=19f307ff6d) | Feb 16, 2021 |
| Lenovo        | ThinkPad T430 23427YU       | Notebook    | [79d1896352](https://bsd-hardware.info/?probe=79d1896352) | Feb 16, 2021 |
| HP            | EliteBook 8440p             | Notebook    | [7968c7d2dd](https://bsd-hardware.info/?probe=7968c7d2dd) | Feb 16, 2021 |
| ASUSTek       | P5E-VM SE                   | Desktop     | [89fbf4a403](https://bsd-hardware.info/?probe=89fbf4a403) | Feb 16, 2021 |
| Dell          | Inspiron 3421               | Notebook    | [c5f6880081](https://bsd-hardware.info/?probe=c5f6880081) | Feb 15, 2021 |
| ASUSTek       | X75VC                       | Notebook    | [4a0982db2b](https://bsd-hardware.info/?probe=4a0982db2b) | Feb 15, 2021 |
| Dell          | 0HY9JP A00                  | Desktop     | [ddabefae47](https://bsd-hardware.info/?probe=ddabefae47) | Feb 15, 2021 |
| HP            | 304Bh                       | Desktop     | [ebd3736a78](https://bsd-hardware.info/?probe=ebd3736a78) | Feb 15, 2021 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | Notebook    | [5a393bc680](https://bsd-hardware.info/?probe=5a393bc680) | Feb 15, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [9181a2479b](https://bsd-hardware.info/?probe=9181a2479b) | Feb 15, 2021 |
| HP            | 2B3C                        | Desktop     | [6c628d33ab](https://bsd-hardware.info/?probe=6c628d33ab) | Feb 15, 2021 |
| Medion        | P6812                       | Notebook    | [c2c592bca8](https://bsd-hardware.info/?probe=c2c592bca8) | Feb 15, 2021 |
| Medion        | P6812                       | Notebook    | [afa43a6aab](https://bsd-hardware.info/?probe=afa43a6aab) | Feb 15, 2021 |
| Apple         | MacBookPro6,2               | Notebook    | [4d83633f97](https://bsd-hardware.info/?probe=4d83633f97) | Feb 15, 2021 |
| HP            | 81B4 01                     | Desktop     | [1bf2cb9506](https://bsd-hardware.info/?probe=1bf2cb9506) | Feb 15, 2021 |
| ASRock        | A300M-STX                   | Desktop     | [9d7266ffc2](https://bsd-hardware.info/?probe=9d7266ffc2) | Feb 15, 2021 |
| ASUSTek       | ROG STRIX TRX40-E GAMING    | Desktop     | [02f241b7d7](https://bsd-hardware.info/?probe=02f241b7d7) | Feb 14, 2021 |
| Gigabyte      | Z68X-UD3H-B3                | Desktop     | [290991af1f](https://bsd-hardware.info/?probe=290991af1f) | Feb 14, 2021 |
| Gigabyte      | Z97M-D3H                    | Desktop     | [a335917871](https://bsd-hardware.info/?probe=a335917871) | Feb 14, 2021 |
| ASUSTek       | PRIME Z390M-PLUS            | Desktop     | [c996e74ebc](https://bsd-hardware.info/?probe=c996e74ebc) | Feb 14, 2021 |
| ASUSTek       | ROG STRIX B360-F GAMING     | Desktop     | [94167310ae](https://bsd-hardware.info/?probe=94167310ae) | Feb 14, 2021 |
| Lenovo        | ThinkPad T400 2768WGC       | Notebook    | [f8ce633ed7](https://bsd-hardware.info/?probe=f8ce633ed7) | Feb 14, 2021 |
| HP            | ProBook 470 G4              | Notebook    | [f808e6bb4a](https://bsd-hardware.info/?probe=f808e6bb4a) | Feb 13, 2021 |
| ASUSTek       | GRYPHON Z97 ARMOR EDITIO... | Desktop     | [694204751b](https://bsd-hardware.info/?probe=694204751b) | Feb 13, 2021 |
| Dell          | 0PC5F7 A01                  | Desktop     | [f1e8c08e31](https://bsd-hardware.info/?probe=f1e8c08e31) | Feb 13, 2021 |
| ASUSTek       | Z170-K                      | Desktop     | [aa525de283](https://bsd-hardware.info/?probe=aa525de283) | Feb 13, 2021 |
| Lenovo        | ThinkPad T580 20LAS2TG00    | Notebook    | [d5a1c088b3](https://bsd-hardware.info/?probe=d5a1c088b3) | Feb 13, 2021 |
| Gigabyte      | Z68X-UD3H-B3                | Desktop     | [a2040528cc](https://bsd-hardware.info/?probe=a2040528cc) | Feb 13, 2021 |
| eMachines     | eME732ZG                    | Notebook    | [c51678397d](https://bsd-hardware.info/?probe=c51678397d) | Feb 13, 2021 |
| Lenovo        | ThinkPad X200 7459ZLW       | Notebook    | [9fbba84be0](https://bsd-hardware.info/?probe=9fbba84be0) | Feb 13, 2021 |
| Lenovo        | ThinkPad T430 2349GCG       | Notebook    | [6da4116499](https://bsd-hardware.info/?probe=6da4116499) | Feb 13, 2021 |
| Lenovo        | ThinkPad T430 2349GCG       | Notebook    | [d212f58dd2](https://bsd-hardware.info/?probe=d212f58dd2) | Feb 13, 2021 |
| Dell          | 06NWYK A00                  | Desktop     | [32acfb4467](https://bsd-hardware.info/?probe=32acfb4467) | Feb 13, 2021 |
| ASUSTek       | H61M-E                      | Desktop     | [98b498ddb0](https://bsd-hardware.info/?probe=98b498ddb0) | Feb 13, 2021 |
| ASUSTek       | P8H61-M LE                  | Desktop     | [b861820636](https://bsd-hardware.info/?probe=b861820636) | Feb 13, 2021 |
| Dell          | Inspiron 3442               | Notebook    | [411797b4dc](https://bsd-hardware.info/?probe=411797b4dc) | Feb 13, 2021 |
| Dell          | 0KWVT8 A03                  | Desktop     | [289b3114ec](https://bsd-hardware.info/?probe=289b3114ec) | Feb 13, 2021 |
| Samsung       | 910S3K/9310SK/910S3P/911... | Notebook    | [bdf7452299](https://bsd-hardware.info/?probe=bdf7452299) | Feb 13, 2021 |
| Dell          | 06NWYK A00                  | Desktop     | [2ff05af403](https://bsd-hardware.info/?probe=2ff05af403) | Feb 13, 2021 |
| ASUSTek       | P8H61-M LE                  | Desktop     | [3a3d7d0701](https://bsd-hardware.info/?probe=3a3d7d0701) | Feb 12, 2021 |
| Dell          | Latitude E6420              | Notebook    | [6bf1f5fe84](https://bsd-hardware.info/?probe=6bf1f5fe84) | Feb 12, 2021 |
| Google        | Panther                     | Desktop     | [1d1512889f](https://bsd-hardware.info/?probe=1d1512889f) | Feb 12, 2021 |
| HP            | 339A                        | Desktop     | [18b86b645a](https://bsd-hardware.info/?probe=18b86b645a) | Feb 12, 2021 |
| Gigabyte      | Z87-D3HP-CF                 | Desktop     | [64551b8203](https://bsd-hardware.info/?probe=64551b8203) | Feb 12, 2021 |
| HP            | 2B17                        | Desktop     | [572bf634a8](https://bsd-hardware.info/?probe=572bf634a8) | Feb 12, 2021 |
| Clevo         | C41X0                       | Notebook    | [81c48d156a](https://bsd-hardware.info/?probe=81c48d156a) | Feb 12, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [37e4e7c85c](https://bsd-hardware.info/?probe=37e4e7c85c) | Feb 12, 2021 |
| HP            | 8055                        | Desktop     | [8ecc5bbb55](https://bsd-hardware.info/?probe=8ecc5bbb55) | Feb 12, 2021 |
| Lenovo        | ThinkPad T460s 20F90037L... | Notebook    | [8325c794b3](https://bsd-hardware.info/?probe=8325c794b3) | Feb 12, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [ac6b550ff4](https://bsd-hardware.info/?probe=ac6b550ff4) | Feb 12, 2021 |
| Apple         | MacBook5,2                  | Notebook    | [f1bc2178a9](https://bsd-hardware.info/?probe=f1bc2178a9) | Feb 12, 2021 |
| Lenovo        | ThinkPad T440s 20ARS10P0... | Notebook    | [bfee99bebd](https://bsd-hardware.info/?probe=bfee99bebd) | Feb 12, 2021 |
| Lenovo        | MAHOBAY                     | Desktop     | [bacae1ddbb](https://bsd-hardware.info/?probe=bacae1ddbb) | Feb 12, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [2b0f35d7a9](https://bsd-hardware.info/?probe=2b0f35d7a9) | Feb 12, 2021 |
| Lenovo        | G500 20236                  | Notebook    | [9b149fcd68](https://bsd-hardware.info/?probe=9b149fcd68) | Feb 12, 2021 |
| Dell          | Inspiron 3521               | Notebook    | [3a73ecd855](https://bsd-hardware.info/?probe=3a73ecd855) | Feb 12, 2021 |
| Dell          | Inspiron 3521               | Notebook    | [afd71fdf87](https://bsd-hardware.info/?probe=afd71fdf87) | Feb 12, 2021 |
| Dell          | Latitude 7380               | Notebook    | [1aa2a3a541](https://bsd-hardware.info/?probe=1aa2a3a541) | Feb 12, 2021 |
| Dell          | Latitude 7380               | Notebook    | [4814701c0e](https://bsd-hardware.info/?probe=4814701c0e) | Feb 12, 2021 |
| Dell          | XPS 15 9560                 | Notebook    | [687008da4f](https://bsd-hardware.info/?probe=687008da4f) | Feb 11, 2021 |
| ASUSTek       | S551LN                      | Notebook    | [42792115e3](https://bsd-hardware.info/?probe=42792115e3) | Feb 11, 2021 |
| ASUSTek       | P8H77-V                     | Desktop     | [aaaffba650](https://bsd-hardware.info/?probe=aaaffba650) | Feb 11, 2021 |
| Apple         | MacBook6,1                  | Notebook    | [3a9335691f](https://bsd-hardware.info/?probe=3a9335691f) | Feb 11, 2021 |
| ASUSTek       | PRIME H310I-PLUS R2.0       | Desktop     | [5965bc8a1d](https://bsd-hardware.info/?probe=5965bc8a1d) | Feb 11, 2021 |
| MSI           | PRESTIGE X570 CREATION      | Desktop     | [261aa9d7ab](https://bsd-hardware.info/?probe=261aa9d7ab) | Feb 11, 2021 |
| Intel         | DG41RQ AAE54511-203         | Desktop     | [e0f72bc85e](https://bsd-hardware.info/?probe=e0f72bc85e) | Feb 11, 2021 |
| Intel         | DG41RQ AAE54511-203         | Desktop     | [3030d78460](https://bsd-hardware.info/?probe=3030d78460) | Feb 11, 2021 |
| ASUSTek       | K50IJ                       | Notebook    | [8cd0aedd3a](https://bsd-hardware.info/?probe=8cd0aedd3a) | Feb 11, 2021 |
| ASRock        | AB350 Gaming-ITX/ac         | Desktop     | [3a6a5a66f7](https://bsd-hardware.info/?probe=3a6a5a66f7) | Feb 11, 2021 |
| A-DATA Tec... | XENIA159GENI72060           | Notebook    | [b2bf9a977b](https://bsd-hardware.info/?probe=b2bf9a977b) | Feb 11, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [a49ff2b77a](https://bsd-hardware.info/?probe=a49ff2b77a) | Feb 11, 2021 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [f19ced0784](https://bsd-hardware.info/?probe=f19ced0784) | Feb 11, 2021 |
| Dell          | Latitude 3410               | Notebook    | [465dd01c0d](https://bsd-hardware.info/?probe=465dd01c0d) | Feb 11, 2021 |
| Samsung       | 300V3Z/300V4Z/300V5Z        | Notebook    | [270ca253a3](https://bsd-hardware.info/?probe=270ca253a3) | Feb 11, 2021 |
| Dell          | Inspiron 3521               | Notebook    | [b3569ebb39](https://bsd-hardware.info/?probe=b3569ebb39) | Feb 11, 2021 |
| Medion        | H81H3-EM2 H81EM2W08.308     | Desktop     | [9958f514c9](https://bsd-hardware.info/?probe=9958f514c9) | Feb 10, 2021 |
| Lenovo        | ThinkPad L470 20J5S09500    | Notebook    | [b17963cd30](https://bsd-hardware.info/?probe=b17963cd30) | Feb 10, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [b507d43de5](https://bsd-hardware.info/?probe=b507d43de5) | Feb 10, 2021 |
| Lenovo        | ThinkPad T410 253722U       | Notebook    | [219e9cb1d7](https://bsd-hardware.info/?probe=219e9cb1d7) | Feb 10, 2021 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [cba616392a](https://bsd-hardware.info/?probe=cba616392a) | Feb 10, 2021 |
| ASUSTek       | K50IJ                       | Notebook    | [52a30e2478](https://bsd-hardware.info/?probe=52a30e2478) | Feb 10, 2021 |
| ASRock        | H270M Pro4                  | Desktop     | [37af53e334](https://bsd-hardware.info/?probe=37af53e334) | Feb 10, 2021 |
| Acer          | Aspire X1700                | Desktop     | [06dc1753ef](https://bsd-hardware.info/?probe=06dc1753ef) | Feb 10, 2021 |
| Acer          | Aspire X1700                | Desktop     | [6886acf351](https://bsd-hardware.info/?probe=6886acf351) | Feb 10, 2021 |
| Toshiba       | TECRA M11                   | Notebook    | [468d16d496](https://bsd-hardware.info/?probe=468d16d496) | Feb 10, 2021 |
| ASUSTek       | P8Z77-V PRO/THUNDERBOLT     | Desktop     | [6fdcef7c9e](https://bsd-hardware.info/?probe=6fdcef7c9e) | Feb 10, 2021 |
| MSI           | Z87-G41 PC Mate             | Desktop     | [23fc631dec](https://bsd-hardware.info/?probe=23fc631dec) | Feb 10, 2021 |
| Gigabyte      | Z97P-D3                     | Desktop     | [a3bd8f5772](https://bsd-hardware.info/?probe=a3bd8f5772) | Feb 10, 2021 |
| Lenovo        | ThinkPad L512 25975XU       | Notebook    | [b4d22f4179](https://bsd-hardware.info/?probe=b4d22f4179) | Feb 10, 2021 |
| Apple         | Mac-F42C88C8 Proto1         | Desktop     | [9517fd0273](https://bsd-hardware.info/?probe=9517fd0273) | Feb 10, 2021 |
| Dell          | 0PC5F7 A01                  | Desktop     | [f045556287](https://bsd-hardware.info/?probe=f045556287) | Feb 09, 2021 |
| Lenovo        | ThinkPad X260 20F5S1H800    | Notebook    | [ca369843a9](https://bsd-hardware.info/?probe=ca369843a9) | Feb 09, 2021 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [a77e980850](https://bsd-hardware.info/?probe=a77e980850) | Feb 09, 2021 |
| ASUSTek       | X550LC                      | Notebook    | [b3cf6f9142](https://bsd-hardware.info/?probe=b3cf6f9142) | Feb 09, 2021 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [7e5ce355e7](https://bsd-hardware.info/?probe=7e5ce355e7) | Feb 08, 2021 |
| Dell          | Latitude 5280               | Notebook    | [73fca8b178](https://bsd-hardware.info/?probe=73fca8b178) | Feb 08, 2021 |
| ASUSTek       | X510UQ                      | Notebook    | [9da77349b9](https://bsd-hardware.info/?probe=9da77349b9) | Feb 07, 2021 |
| ASUSTek       | X502CA                      | Notebook    | [5e15d06a9b](https://bsd-hardware.info/?probe=5e15d06a9b) | Feb 06, 2021 |
| ASUSTek       | X502CA                      | Notebook    | [1a2df26f19](https://bsd-hardware.info/?probe=1a2df26f19) | Feb 06, 2021 |
| Fujitsu       | LIFEBOOK E753               | Notebook    | [37245aca21](https://bsd-hardware.info/?probe=37245aca21) | Feb 03, 2021 |
| Lenovo        | ThinkPad T470s 20HGS1VD0... | Notebook    | [faa7becf82](https://bsd-hardware.info/?probe=faa7becf82) | Feb 01, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [b3eb492602](https://bsd-hardware.info/?probe=b3eb492602) | Jan 31, 2021 |
| Dell          | Latitude E6440              | Notebook    | [ed46852cfa](https://bsd-hardware.info/?probe=ed46852cfa) | Jan 26, 2021 |
| Pegatron      | T12Ah                       | Notebook    | [e9c5982872](https://bsd-hardware.info/?probe=e9c5982872) | Jan 23, 2021 |
| Dell          | 0Y7WYT A00                  | Desktop     | [4af9b92154](https://bsd-hardware.info/?probe=4af9b92154) | Jan 19, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3444A... | Notebook    | [b659b95d1a](https://bsd-hardware.info/?probe=b659b95d1a) | Jan 18, 2021 |
| HP            | ProBook 470 G4              | Notebook    | [e39a46cadf](https://bsd-hardware.info/?probe=e39a46cadf) | Jan 17, 2021 |
| MSI           | Boston                      | Desktop     | [aa9d7bae21](https://bsd-hardware.info/?probe=aa9d7bae21) | Jan 17, 2021 |
| MSI           | Boston                      | Desktop     | [f21954fa35](https://bsd-hardware.info/?probe=f21954fa35) | Jan 17, 2021 |
| Gigabyte      | TRX40 DESIGNARE             | Desktop     | [f506b21449](https://bsd-hardware.info/?probe=f506b21449) | Jan 17, 2021 |
| Lenovo        | ThinkPad T480s 20L8S6G21... | Notebook    | [a8508f91de](https://bsd-hardware.info/?probe=a8508f91de) | Jan 14, 2021 |
| HP            | ProBook 470 G4              | Notebook    | [c4eecdac67](https://bsd-hardware.info/?probe=c4eecdac67) | Jan 14, 2021 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 190       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| helloDesktop | 189       | 99.47%  |
| KDE5         | 1         | 0.53%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 190       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| SLiM | 189       | 99.47%  |
| SDDM | 1         | 0.53%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 185       | 97.37%  |
| fr_FR | 2         | 1.05%   |
| es_ES | 2         | 1.05%   |
| de_DE | 1         | 0.53%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 170       | 89.47%  |
| BIOS | 20        | 10.53%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| Zfs  | 190       | 100%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 190       | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 38        | 20%     |
| Lenovo              | 35        | 18.42%  |
| Dell                | 30        | 15.79%  |
| Hewlett-Packard     | 17        | 8.95%   |
| Gigabyte Technology | 13        | 6.84%   |
| Apple               | 11        | 5.79%   |
| ASRock              | 10        | 5.26%   |
| MSI                 | 5         | 2.63%   |
| Intel               | 5         | 2.63%   |
| Samsung Electronics | 3         | 1.58%   |
| Fujitsu             | 3         | 1.58%   |
| Toshiba             | 2         | 1.05%   |
| Pegatron            | 2         | 1.05%   |
| Medion              | 2         | 1.05%   |
| Google              | 2         | 1.05%   |
| Acidanthera         | 2         | 1.05%   |
| Acer                | 2         | 1.05%   |
| VeryPC              | 1         | 0.53%   |
| Supermicro          | 1         | 0.53%   |
| Panasonic           | 1         | 0.53%   |
| Packard Bell        | 1         | 0.53%   |
| Notebook            | 1         | 0.53%   |
| HARDKERNEL          | 1         | 0.53%   |
| Gateway             | 1         | 0.53%   |
| Clevo               | 1         | 0.53%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Dell Inspiron 3521                       | 2         | 1.05%   |
| Dell Inspiron 3442                       | 2         | 1.05%   |
| ASUS All Series                          | 2         | 1.05%   |
| VeryPC S400-K7-N-O                       | 1         | 0.53%   |
| Toshiba TECRA M11                        | 1         | 0.53%   |
| Toshiba Satellite U500                   | 1         | 0.53%   |
| Supermicro X10SRA                        | 1         | 0.53%   |
| Samsung 910S3K/9310SK/910S3P/911S3K      | 1         | 0.53%   |
| Samsung 3570R/370R/470R/450R/510R/4450RV | 1         | 0.53%   |
| Samsung 300V3Z/300V4Z/300V5Z             | 1         | 0.53%   |
| Pegatron T12Ah                           | 1         | 0.53%   |
| Pegatron IPM41-D3                        | 1         | 0.53%   |
| Panasonic CF-NX1GDHYS                    | 1         | 0.53%   |
| Packard Bell EasyNote TS11HR             | 1         | 0.53%   |
| Notebook W65KJ1_KK1                      | 1         | 0.53%   |
| MSI NR074AA-ABZ CQ5125IT                 | 1         | 0.53%   |
| MSI MS-7C52                              | 1         | 0.53%   |
| MSI MS-7850                              | 1         | 0.53%   |
| MSI MS-7721                              | 1         | 0.53%   |
| MSI MS-7592                              | 1         | 0.53%   |
| Medion P6812                             | 1         | 0.53%   |
| Medion H81H3-EM2                         | 1         | 0.53%   |
| Lenovo Z50-70 20354                      | 1         | 0.53%   |
| Lenovo U310                              | 1         | 0.53%   |
| Lenovo ThinkStation S30 43511K5          | 1         | 0.53%   |
| Lenovo ThinkPad X260 20F5S1H800          | 1         | 0.53%   |
| Lenovo ThinkPad X240 20AMS4V000          | 1         | 0.53%   |
| Lenovo ThinkPad X200 7459ZLW             | 1         | 0.53%   |
| Lenovo ThinkPad X1 Carbon 5th 20HQS02100 | 1         | 0.53%   |
| Lenovo ThinkPad X1 Carbon 4th 20FCS2K000 | 1         | 0.53%   |
| Lenovo ThinkPad X1 Carbon 3444AZU        | 1         | 0.53%   |
| Lenovo ThinkPad T61 766416U              | 1         | 0.53%   |
| Lenovo ThinkPad T580 20LAS2TG00          | 1         | 0.53%   |
| Lenovo ThinkPad T530 2392ASU             | 1         | 0.53%   |
| Lenovo ThinkPad T480s 20L8S6G21E         | 1         | 0.53%   |
| Lenovo ThinkPad T470s 20HGS1VD00         | 1         | 0.53%   |
| Lenovo ThinkPad T460s 20F90037LM         | 1         | 0.53%   |
| Lenovo ThinkPad T440s 20ARS10P05         | 1         | 0.53%   |
| Lenovo ThinkPad T440p 20AWS0U500         | 1         | 0.53%   |
| Lenovo ThinkPad T430 2349PMP             | 1         | 0.53%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 23        | 12.11%  |
| Dell Latitude         | 11        | 5.79%   |
| Dell OptiPlex         | 7         | 3.68%   |
| Dell Inspiron         | 7         | 3.68%   |
| Lenovo ThinkCentre    | 5         | 2.63%   |
| ASUS PRIME            | 5         | 2.63%   |
| HP Compaq             | 3         | 1.58%   |
| ASUS ROG              | 3         | 1.58%   |
| HP ProDesk            | 2         | 1.05%   |
| HP Pavilion           | 2         | 1.05%   |
| HP EliteDesk          | 2         | 1.05%   |
| HP EliteBook          | 2         | 1.05%   |
| Fujitsu LIFEBOOK      | 2         | 1.05%   |
| Dell XPS              | 2         | 1.05%   |
| ASUS VivoBook         | 2         | 1.05%   |
| ASUS P8Z77-V          | 2         | 1.05%   |
| ASUS M5A78L-M         | 2         | 1.05%   |
| ASUS All              | 2         | 1.05%   |
| ASRock AB350          | 2         | 1.05%   |
| Acer Aspire           | 2         | 1.05%   |
| VeryPC S400-K7-N-O    | 1         | 0.53%   |
| Toshiba TECRA         | 1         | 0.53%   |
| Toshiba Satellite     | 1         | 0.53%   |
| Supermicro X10SRA     | 1         | 0.53%   |
| Samsung 910S3K        | 1         | 0.53%   |
| Samsung 3570R         | 1         | 0.53%   |
| Samsung 300V3Z        | 1         | 0.53%   |
| Pegatron T12Ah        | 1         | 0.53%   |
| Pegatron IPM41-D3     | 1         | 0.53%   |
| Panasonic CF-NX1GDHYS | 1         | 0.53%   |
| Packard Bell EasyNote | 1         | 0.53%   |
| Notebook W65KJ1       | 1         | 0.53%   |
| MSI NR074AA-ABZ       | 1         | 0.53%   |
| MSI MS-7C52           | 1         | 0.53%   |
| MSI MS-7850           | 1         | 0.53%   |
| MSI MS-7721           | 1         | 0.53%   |
| MSI MS-7592           | 1         | 0.53%   |
| Medion P6812          | 1         | 0.53%   |
| Medion H81H3-EM2      | 1         | 0.53%   |
| Lenovo Z50-70         | 1         | 0.53%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2013 | 26        | 13.68%  |
| 2018 | 24        | 12.63%  |
| 2020 | 18        | 9.47%   |
| 2014 | 18        | 9.47%   |
| 2019 | 17        | 8.95%   |
| 2016 | 16        | 8.42%   |
| 2009 | 14        | 7.37%   |
| 2017 | 12        | 6.32%   |
| 2012 | 12        | 6.32%   |
| 2010 | 8         | 4.21%   |
| 2015 | 7         | 3.68%   |
| 2011 | 7         | 3.68%   |
| 2008 | 6         | 3.16%   |
| 2021 | 2         | 1.05%   |
| 2007 | 2         | 1.05%   |
| 2006 | 1         | 0.53%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 92        | 48.42%  |
| Desktop     | 90        | 47.37%  |
| Mini pc     | 4         | 2.11%   |
| Server      | 2         | 1.05%   |
| Convertible | 1         | 0.53%   |
| All in one  | 1         | 0.53%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 188       | 98.95%  |
| Yes  | 2         | 1.05%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 63        | 33.16%  |
| 4.01-8.0    | 55        | 28.95%  |
| 16.01-24.0  | 52        | 27.37%  |
| 32.01-64.0  | 13        | 6.84%   |
| 24.01-32.0  | 4         | 2.11%   |
| 64.01-256.0 | 3         | 1.58%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Computers | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 102       | 53.4%   |
| 0.51-1.0 | 69        | 36.13%  |
| 1.01-2.0 | 13        | 6.81%   |
| 2.01-3.0 | 6         | 3.14%   |
| 3.01-4.0 | 1         | 0.52%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 115       | 60.53%  |
| 2      | 33        | 17.37%  |
| 3      | 19        | 10%     |
| 4      | 12        | 6.32%   |
| 0      | 5         | 2.63%   |
| 5      | 3         | 1.58%   |
| 6      | 2         | 1.05%   |
| 7      | 1         | 0.53%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 109       | 57.37%  |
| Yes       | 81        | 42.63%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 181       | 95.26%  |
| No        | 9         | 4.74%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 121       | 63.68%  |
| No        | 69        | 36.32%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 95        | 50%     |
| No        | 95        | 50%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| Germany      | 34        | 17.89%  |
| USA          | 27        | 14.21%  |
| Brazil       | 15        | 7.89%   |
| Italy        | 12        | 6.32%   |
| France       | 11        | 5.79%   |
| UK           | 10        | 5.26%   |
| Spain        | 9         | 4.74%   |
| Russia       | 6         | 3.16%   |
| Australia    | 6         | 3.16%   |
| China        | 5         | 2.63%   |
| Canada       | 5         | 2.63%   |
| Hungary      | 4         | 2.11%   |
| Ukraine      | 3         | 1.58%   |
| Poland       | 3         | 1.58%   |
| Mexico       | 3         | 1.58%   |
| India        | 3         | 1.58%   |
| UAE          | 2         | 1.05%   |
| Taiwan       | 2         | 1.05%   |
| Sweden       | 2         | 1.05%   |
| South Africa | 2         | 1.05%   |
| Portugal     | 2         | 1.05%   |
| Netherlands  | 2         | 1.05%   |
| Macao        | 2         | 1.05%   |
| Japan        | 2         | 1.05%   |
| Greece       | 2         | 1.05%   |
| Croatia      | 2         | 1.05%   |
| Switzerland  | 1         | 0.53%   |
| South Korea  | 1         | 0.53%   |
| Philippines  | 1         | 0.53%   |
| Peru         | 1         | 0.53%   |
| Lithuania    | 1         | 0.53%   |
| Ireland      | 1         | 0.53%   |
| Indonesia    | 1         | 0.53%   |
| Finland      | 1         | 0.53%   |
| Estonia      | 1         | 0.53%   |
| Egypt        | 1         | 0.53%   |
| Colombia     | 1         | 0.53%   |
| Chile        | 1         | 0.53%   |
| Bulgaria     | 1         | 0.53%   |
| Belgium      | 1         | 0.53%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                      | Computers | Percent |
|---------------------------|-----------|---------|
| SГЈo Paulo              | 3         | 1.57%   |
| Rudersberg                | 3         | 1.57%   |
| Paris                     | 3         | 1.57%   |
| Franconville              | 3         | 1.57%   |
| Taoyuan District          | 2         | 1.05%   |
| Stourbridge               | 2         | 1.05%   |
| Seattle                   | 2         | 1.05%   |
| Reigate                   | 2         | 1.05%   |
| Oklahoma City             | 2         | 1.05%   |
| New York                  | 2         | 1.05%   |
| Marlborough               | 2         | 1.05%   |
| Macao                     | 2         | 1.05%   |
| Halle                     | 2         | 1.05%   |
| Guangzhou                 | 2         | 1.05%   |
| Curitiba                  | 2         | 1.05%   |
| Canberra                  | 2         | 1.05%   |
| Budapest                  | 2         | 1.05%   |
| Brighton                  | 2         | 1.05%   |
| Berlin                    | 2         | 1.05%   |
| ЕљwiД™tochЕ‚owice | 1         | 0.52%   |
| Zaragoza                  | 1         | 0.52%   |
| Zajaczki Pierwsze         | 1         | 0.52%   |
| Wesley Chapel             | 1         | 0.52%   |
| Ware                      | 1         | 0.52%   |
| Vilnius                   | 1         | 0.52%   |
| Victoria                  | 1         | 0.52%   |
| Vereeniging               | 1         | 0.52%   |
| Velika Gorica             | 1         | 0.52%   |
| Valencia                  | 1         | 0.52%   |
| Utrecht                   | 1         | 0.52%   |
| Ufa                       | 1         | 0.52%   |
| Uberaba                   | 1         | 0.52%   |
| Turin                     | 1         | 0.52%   |
| Trieste                   | 1         | 0.52%   |
| Toronto                   | 1         | 0.52%   |
| Tomah                     | 1         | 0.52%   |
| Tilburg                   | 1         | 0.52%   |
| Tieling                   | 1         | 0.52%   |
| The Bronx                 | 1         | 0.52%   |
| Terrassa                  | 1         | 0.52%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 47        | 58     | 16.79%  |
| Samsung Electronics | 46        | 66     | 16.43%  |
| Seagate             | 39        | 49     | 13.93%  |
| Kingston            | 23        | 24     | 8.21%   |
| Crucial             | 19        | 24     | 6.79%   |
| SanDisk             | 18        | 19     | 6.43%   |
| Toshiba             | 17        | 17     | 6.07%   |
| Hitachi             | 11        | 14     | 3.93%   |
| Intel               | 7         | 7      | 2.5%    |
| Micron Technology   | 6         | 6      | 2.14%   |
| SPCC                | 5         | 5      | 1.79%   |
| PNY                 | 3         | 3      | 1.07%   |
| HGST                | 3         | 3      | 1.07%   |
| Transcend           | 2         | 2      | 0.71%   |
| SK hynix            | 2         | 2      | 0.71%   |
| Patriot             | 2         | 2      | 0.71%   |
| OCZ                 | 2         | 3      | 0.71%   |
| LITEON              | 2         | 2      | 0.71%   |
| Intenso             | 2         | 3      | 0.71%   |
| GOODRAM             | 2         | 2      | 0.71%   |
| Gigabyte Technology | 2         | 3      | 0.71%   |
| Corsair             | 2         | 2      | 0.71%   |
| A-DATA Technology   | 2         | 2      | 0.71%   |
| Silicon Motion      | 1         | 1      | 0.36%   |
| Pioneer             | 1         | 1      | 0.36%   |
| Phison              | 1         | 3      | 0.36%   |
| Maxtor              | 1         | 1      | 0.36%   |
| LITEONIT            | 1         | 1      | 0.36%   |
| Lexar               | 1         | 1      | 0.36%   |
| Leven               | 1         | 2      | 0.36%   |
| KingDian            | 1         | 1      | 0.36%   |
| Hoodisk             | 1         | 1      | 0.36%   |
| Hikvision           | 1         | 1      | 0.36%   |
| Fujitsu             | 1         | 1      | 0.36%   |
| Enmotus             | 1         | 1      | 0.36%   |
| EMTEC               | 1         | 1      | 0.36%   |
| Colorful            | 1         | 1      | 0.36%   |
| China               | 1         | 1      | 0.36%   |
| Apple               | 1         | 1      | 0.36%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB           | 6         | 1.88%   |
| Kingston SA400S37240G 240GB         | 5         | 1.57%   |
| Crucial CT500MX500SSD1 500GB        | 5         | 1.57%   |
| Samsung SSD 850 EVO 250GB           | 4         | 1.25%   |
| Samsung HD103SI 1TB                 | 4         | 1.25%   |
| Micron 1100 SATA 256GB              | 4         | 1.25%   |
| Kingston SV300S37A120G 120GB        | 4         | 1.25%   |
| WDC WDS240G2G0A-00JH30 240GB        | 3         | 0.94%   |
| Toshiba MQ01ABD100 1TB              | 3         | 0.94%   |
| Toshiba DT01ACA100 1TB              | 3         | 0.94%   |
| Seagate ST500DM002-1BD142 500GB     | 3         | 0.94%   |
| SanDisk pSSD 16GB                   | 3         | 0.94%   |
| Samsung SSD 860 EVO 250GB           | 3         | 0.94%   |
| Samsung SSD 840 EVO 1TB             | 3         | 0.94%   |
| WDC WDS100T2B0A-00SM50 1TB          | 2         | 0.63%   |
| WDC WD20EARX-00PASB0 2TB            | 2         | 0.63%   |
| WDC WD1600BEVS-08VAT2 160GB         | 2         | 0.63%   |
| WDC WD10EZEX-00RKKA0 1TB            | 2         | 0.63%   |
| Toshiba Q300 240GB                  | 2         | 0.63%   |
| SPCC Solid State Disk 512GB         | 2         | 0.63%   |
| Seagate ST750LM022 HN-M750MBB 752GB | 2         | 0.63%   |
| Seagate ST500LX025-1U717D 500GB     | 2         | 0.63%   |
| Seagate ST500LM021-1KJ152 500GB     | 2         | 0.63%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 2         | 0.63%   |
| Seagate ST1000DM010-2EP102 1TB      | 2         | 0.63%   |
| Seagate ST1000DM003-1ER162 1TB      | 2         | 0.63%   |
| SanDisk SDSSDA240G 240GB            | 2         | 0.63%   |
| Samsung SSD 960 EVO 500GB           | 2         | 0.63%   |
| Samsung SSD 960 EVO 250GB           | 2         | 0.63%   |
| Samsung SSD 840 EVO 250GB           | 2         | 0.63%   |
| Samsung SSD 840 EVO 120GB           | 2         | 0.63%   |
| Samsung MZVLW256HEHP-000L7 256GB    | 2         | 0.63%   |
| Samsung HD322HJ 320GB               | 2         | 0.63%   |
| PNY CS900 240GB SSD                 | 2         | 0.63%   |
| Kingston SUV500M8240G 240GB         | 2         | 0.63%   |
| Kingston SA400S37480G 480GB         | 2         | 0.63%   |
| Kingston SA2000M8250G 250GB         | 2         | 0.63%   |
| Crucial M4-CT128M4SSD2 128GB        | 2         | 0.63%   |
| Crucial CT500MX500SSD4 500GB        | 2         | 0.63%   |
| Crucial CT250MX500SSD1 250GB        | 2         | 0.63%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 39        | 49     | 33.91%  |
| WDC                 | 38        | 44     | 33.04%  |
| Toshiba             | 11        | 11     | 9.57%   |
| Samsung Electronics | 11        | 16     | 9.57%   |
| Hitachi             | 11        | 14     | 9.57%   |
| HGST                | 3         | 3      | 2.61%   |
| Maxtor              | 1         | 1      | 0.87%   |
| Fujitsu             | 1         | 1      | 0.87%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 30        | 37     | 20.98%  |
| Kingston            | 20        | 21     | 13.99%  |
| SanDisk             | 18        | 19     | 12.59%  |
| Crucial             | 18        | 23     | 12.59%  |
| WDC                 | 11        | 11     | 7.69%   |
| Micron Technology   | 6         | 6      | 4.2%    |
| Toshiba             | 4         | 4      | 2.8%    |
| SPCC                | 4         | 4      | 2.8%    |
| Intel               | 4         | 4      | 2.8%    |
| PNY                 | 3         | 3      | 2.1%    |
| Transcend           | 2         | 2      | 1.4%    |
| Patriot             | 2         | 2      | 1.4%    |
| OCZ                 | 2         | 3      | 1.4%    |
| LITEON              | 2         | 2      | 1.4%    |
| Intenso             | 2         | 3      | 1.4%    |
| GOODRAM             | 2         | 2      | 1.4%    |
| A-DATA Technology   | 2         | 2      | 1.4%    |
| SK hynix            | 1         | 1      | 0.7%    |
| Pioneer             | 1         | 1      | 0.7%    |
| LITEONIT            | 1         | 1      | 0.7%    |
| Lexar               | 1         | 1      | 0.7%    |
| Leven               | 1         | 2      | 0.7%    |
| KingDian            | 1         | 1      | 0.7%    |
| Hoodisk             | 1         | 1      | 0.7%    |
| Hikvision           | 1         | 1      | 0.7%    |
| EMTEC               | 1         | 1      | 0.7%    |
| China               | 1         | 1      | 0.7%    |
| Apple               | 1         | 1      | 0.7%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 115       | 160    | 48.32%  |
| HDD  | 93        | 139    | 39.08%  |
| NVMe | 30        | 38     | 12.61%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 174       | 299    | 85.29%  |
| NVMe | 30        | 38     | 14.71%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 151       | 215    | 70.89%  |
| 0.51-1.0   | 46        | 64     | 21.6%   |
| 1.01-2.0   | 11        | 14     | 5.16%   |
| 3.01-4.0   | 2         | 2      | 0.94%   |
| 4.01-10.0  | 2         | 2      | 0.94%   |
| 2.01-3.0   | 1         | 2      | 0.47%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 1-20       | 142       | 74.35%  |
| 101-250    | 29        | 15.18%  |
| 251-500    | 13        | 6.81%   |
| 501-1000   | 4         | 2.09%   |
| 51-100     | 2         | 1.05%   |
| 21-50      | 1         | 0.52%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Computers | Percent |
|---------|-----------|---------|
| 1-20    | 190       | 100%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB                       | 2         | 2      | 3.45%   |
| Seagate ST500DM002-1BD142 500GB              | 2         | 3      | 3.45%   |
| WDC WDS240G2G0A-00JH30 240GB                 | 1         | 1      | 1.72%   |
| WDC WDS200T2B0A 2TB                          | 1         | 1      | 1.72%   |
| WDC WD5000AVCS-632DY1 500GB                  | 1         | 1      | 1.72%   |
| WDC WD5000AAKS-00E4A0 500GB                  | 1         | 1      | 1.72%   |
| WDC WD3200BPVT-55ZEST0 320GB                 | 1         | 1      | 1.72%   |
| WDC WD3200BEVT-60ZCT1 320GB                  | 1         | 1      | 1.72%   |
| WDC WD3200BEKT-60V5T1 320GB                  | 1         | 1      | 1.72%   |
| WDC WD2500AAKX-083CA1 250GB                  | 1         | 1      | 1.72%   |
| WDC WD20EVDS-63T3B0 2TB                      | 1         | 1      | 1.72%   |
| WDC WD20EARX-00PASB0 2TB                     | 1         | 1      | 1.72%   |
| WDC WD2002FYPS-01U1B1 2TB                    | 1         | 1      | 1.72%   |
| WDC WD1600BEVS-60RST0 160GB                  | 1         | 1      | 1.72%   |
| WDC WD10JPVX-75JC3T0 1TB                     | 1         | 1      | 1.72%   |
| WDC WD10JMVW-11AJGS0 1TB                     | 1         | 1      | 1.72%   |
| WDC WD10EZEX-00RKKA0 1TB                     | 1         | 1      | 1.72%   |
| WDC WD10EAVS-00D7B0 1TB                      | 1         | 1      | 1.72%   |
| Toshiba MQ02ABF050H-SSHD-8GB                 | 1         | 1      | 1.72%   |
| Toshiba MK2555GSXF 250GB                     | 1         | 1      | 1.72%   |
| Seagate ST9500420AS 500GB                    | 1         | 1      | 1.72%   |
| Seagate ST9320325AS 320GB                    | 1         | 1      | 1.72%   |
| Seagate ST9160314AS 160GB                    | 1         | 1      | 1.72%   |
| Seagate ST750LM022 HN-M750MBB 752GB          | 1         | 1      | 1.72%   |
| Seagate ST320LT012-9WS14C 320GB              | 1         | 1      | 1.72%   |
| Seagate ST320LM001 HN-M320MBB 320GB          | 1         | 1      | 1.72%   |
| Seagate ST3160215AS 160GB                    | 1         | 1      | 1.72%   |
| Seagate ST31500341AS 1.5TB                   | 1         | 1      | 1.72%   |
| Seagate ST1000LM025 HN-M101ABB 1TB           | 1         | 1      | 1.72%   |
| Seagate ST1000DX001-1CM162 1TB               | 1         | 1      | 1.72%   |
| Seagate ST1000DM003-9YN162 1TB               | 1         | 1      | 1.72%   |
| SanDisk SSD PLUS 480GB                       | 1         | 1      | 1.72%   |
| SanDisk SD5SG2128G1052E 128GB                | 1         | 1      | 1.72%   |
| Samsung Electronics SP2514N 250GB            | 1         | 1      | 1.72%   |
| Samsung Electronics MZHPV512HDGL-00000 512GB | 1         | 1      | 1.72%   |
| Samsung Electronics HM321HI 320GB            | 1         | 1      | 1.72%   |
| Samsung Electronics HM320JI 320GB            | 1         | 1      | 1.72%   |
| Samsung Electronics HD753LJ 752GB            | 1         | 1      | 1.72%   |
| Samsung Electronics HD252HJ 250GB            | 1         | 1      | 1.72%   |
| Samsung Electronics HD103UJ 1TB              | 1         | 1      | 1.72%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 16        | 16     | 29.09%  |
| Seagate             | 12        | 14     | 21.82%  |
| Samsung Electronics | 6         | 8      | 10.91%  |
| Hitachi             | 5         | 5      | 9.09%   |
| Toshiba             | 4         | 4      | 7.27%   |
| Intel               | 4         | 4      | 7.27%   |
| SanDisk             | 2         | 2      | 3.64%   |
| HGST                | 2         | 2      | 3.64%   |
| Micron Technology   | 1         | 1      | 1.82%   |
| LITEON              | 1         | 1      | 1.82%   |
| Kingston            | 1         | 1      | 1.82%   |
| Crucial             | 1         | 2      | 1.82%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 14        | 14     | 33.33%  |
| Seagate             | 12        | 14     | 28.57%  |
| Samsung Electronics | 5         | 7      | 11.9%   |
| Hitachi             | 5         | 5      | 11.9%   |
| Toshiba             | 4         | 4      | 9.52%   |
| HGST                | 2         | 2      | 4.76%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 37        | 46     | 74%     |
| SSD  | 12        | 13     | 24%     |
| NVMe | 1         | 1      | 2%      |

Failed Drives
-------------

Failed drive models

Zero info for selected period =(

Failed Drive Vendor
-------------------

Failed drive vendors

Zero info for selected period =(

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 159       | 275    | 75.36%  |
| Malfunc  | 50        | 60     | 23.7%   |
| Detected | 2         | 2      | 0.95%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 154       | 68.14%  |
| AMD                         | 27        | 11.95%  |
| Samsung Electronics         | 12        | 5.31%   |
| Phison Electronics          | 5         | 2.21%   |
| ASMedia Technology          | 5         | 2.21%   |
| Nvidia                      | 4         | 1.77%   |
| SanDisk                     | 3         | 1.33%   |
| Kingston Technology Company | 3         | 1.33%   |
| Toshiba                     | 2         | 0.88%   |
| Silicon Motion              | 2         | 0.88%   |
| Marvell Technology Group    | 2         | 0.88%   |
| JMicron Technology          | 2         | 0.88%   |
| SK hynix                    | 1         | 0.44%   |
| Micron/Crucial Technology   | 1         | 0.44%   |
| Enmotus                     | 1         | 0.44%   |
| Broadcom / LSI              | 1         | 0.44%   |
| Broadcom                    | 1         | 0.44%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 19        | 7.22%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 18        | 6.84%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 16        | 6.08%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 16        | 6.08%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 9         | 3.42%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 9         | 3.42%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 8         | 3.04%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 7         | 2.66%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 7         | 2.66%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 7         | 2.66%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 7         | 2.66%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 5         | 1.9%    |
| ASMedia ASM1062 Serial ATA Controller                                          | 5         | 1.9%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 5         | 1.9%    |
| AMD 400 Series Chipset SATA Controller                                         | 5         | 1.9%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 4         | 1.52%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 4         | 1.52%   |
| Intel SATA Controller [RAID mode]                                              | 4         | 1.52%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 4         | 1.52%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 4         | 1.52%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 4         | 1.52%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 4         | 1.52%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 4         | 1.52%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 4         | 1.52%   |
| Nvidia MCP79 AHCI Controller                                                   | 3         | 1.14%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 3         | 1.14%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 3         | 1.14%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 3         | 1.14%   |
| AMD 300 Series Chipset SATA Controller                                         | 3         | 1.14%   |
| Unknown                                                                        | 3         | 1.14%   |
| Phison PS5013 E13 NVMe Controller                                              | 2         | 0.76%   |
| Phison E16 PCIe4 NVMe Controller                                               | 2         | 0.76%   |
| Phison E12 NVMe Controller                                                     | 2         | 0.76%   |
| Marvell Group 88SE9172 SATA 6Gb/s Controller                                   | 2         | 0.76%   |
| Kingston Company A2000 NVMe SSD                                                | 2         | 0.76%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                               | 2         | 0.76%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 2         | 0.76%   |
| Intel Comet Lake PCH-LP SATA RAID Premium Controller                           | 2         | 0.76%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 0.76%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 2         | 0.76%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 158       | 69%     |
| NVMe | 29        | 12.66%  |
| IDE  | 27        | 11.79%  |
| RAID | 12        | 5.24%   |
| SAS  | 2         | 0.87%   |
| SCSI | 1         | 0.44%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 162       | 85.26%  |
| AMD    | 28        | 14.74%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz           | 4         | 2.11%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 4         | 2.11%   |
| Intel Core 2 Duo                            | 4         | 2.11%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 3         | 1.58%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 3         | 1.58%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 3         | 1.58%   |
| Intel Core i5-3317U CPU @ 1.70GHz           | 3         | 1.58%   |
| Intel Core i3-6100T CPU @ 3.20GHz           | 3         | 1.58%   |
| Intel Core i3-3227U CPU @ 1.90GHz           | 3         | 1.58%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 3         | 1.58%   |
| Intel CPU Version                           | 2         | 1.05%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 2         | 1.05%   |
| Intel Core i7-7600U CPU @ 2.80GHz           | 2         | 1.05%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 2         | 1.05%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz          | 2         | 1.05%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 2         | 1.05%   |
| Intel Core i7-3520M CPU @ 2.90GHz           | 2         | 1.05%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 2         | 1.05%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 2         | 1.05%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 2         | 1.05%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 2         | 1.05%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 2         | 1.05%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 2         | 1.05%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 2         | 1.05%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 2         | 1.05%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz        | 2         | 1.05%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 2         | 1.05%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 2         | 1.05%   |
| Intel Xeon CPU X5690 @ 3.47GHz              | 1         | 0.53%   |
| Intel Xeon CPU X                            | 1         | 0.53%   |
| Intel Xeon CPU E5-2620 0 @ 2.00GHz          | 1         | 0.53%   |
| Intel Xeon CPU E5-1620 v4 @ 3.50GHz         | 1         | 0.53%   |
| Intel Xeon CPU E5-1620 @ 3.60GHz            | 1         | 0.53%   |
| Intel Xeon CPU E31245 @ 3.30GH              | 1         | 0.53%   |
| Intel Xeon CPU E3-1265L v3 @ 2.50GHz        | 1         | 0.53%   |
| Intel Xeon CPU E3-1245 v3 @ 3.40GHz         | 1         | 0.53%   |
| Intel Pentium Silver J5005 CPU @ 1.50GHz    | 1         | 0.53%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 1         | 0.53%   |
| Intel Pentium Dual-Core CPU E6700 @ 3.20GHz | 1         | 0.53%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 1         | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 51        | 26.84%  |
| Intel Core i7           | 40        | 21.05%  |
| Intel Core i3           | 21        | 11.05%  |
| Intel Core 2 Duo        | 18        | 9.47%   |
| AMD Ryzen 5             | 9         | 4.74%   |
| Intel Xeon              | 8         | 4.21%   |
| Intel Pentium           | 8         | 4.21%   |
| Intel Celeron           | 7         | 3.68%   |
| AMD FX                  | 5         | 2.63%   |
| Other                   | 3         | 1.58%   |
| Intel Pentium Dual-Core | 3         | 1.58%   |
| AMD Ryzen 7             | 3         | 1.58%   |
| AMD Ryzen 3             | 3         | 1.58%   |
| AMD A8                  | 3         | 1.58%   |
| AMD Ryzen Threadripper  | 2         | 1.05%   |
| AMD Phenom II X4        | 2         | 1.05%   |
| Intel Pentium Silver    | 1         | 0.53%   |
| Intel Genuine           | 1         | 0.53%   |
| Intel Core M            | 1         | 0.53%   |
| Intel Core 2 Quad       | 1         | 0.53%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 89        | 46.84%  |
| 4       | 59        | 31.05%  |
| Unknown | 15        | 7.89%   |
| 6       | 9         | 4.74%   |
| 8       | 7         | 3.68%   |
| 12      | 6         | 3.16%   |
| 16      | 3         | 1.58%   |
| 64      | 1         | 0.53%   |
| 48      | 1         | 0.53%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 184       | 96.84%  |
| 2      | 5         | 2.63%   |
| 8      | 1         | 0.53%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 106       | 55.79%  |
| 1       | 69        | 36.32%  |
| Unknown | 15        | 7.89%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Haswell       | 31        | 16.32%  |
| KabyLake      | 28        | 14.74%  |
| IvyBridge     | 26        | 13.68%  |
| SandyBridge   | 20        | 10.53%  |
| Penryn        | 20        | 10.53%  |
| Skylake       | 15        | 7.89%   |
| Westmere      | 9         | 4.74%   |
| Zen 2         | 7         | 3.68%   |
| Piledriver    | 7         | 3.68%   |
| Zen+          | 6         | 3.16%   |
| Core          | 5         | 2.63%   |
| Broadwell     | 5         | 2.63%   |
| Zen           | 4         | 2.11%   |
| K10           | 2         | 1.05%   |
| Goldmont plus | 2         | 1.05%   |
| K8 Hammer     | 1         | 0.53%   |
| Goldmont      | 1         | 0.53%   |
| Bulldozer     | 1         | 0.53%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 117       | 53.92%  |
| Nvidia | 64        | 29.49%  |
| AMD    | 36        | 16.59%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                            | 15        | 6.88%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 15        | 6.88%   |
| Intel HD Graphics 620                                                       | 10        | 4.59%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 10        | 4.59%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 8         | 3.67%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 8         | 3.67%   |
| Intel Core Processor Integrated Graphics Controller                         | 7         | 3.21%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 6         | 2.75%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 6         | 2.75%   |
| Intel UHD Graphics 620                                                      | 4         | 1.83%   |
| Intel HD Graphics 630                                                       | 4         | 1.83%   |
| Intel HD Graphics 530                                                       | 4         | 1.83%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 4         | 1.83%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 4         | 1.83%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 3         | 1.38%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 3         | 1.38%   |
| Nvidia GK208B [GeForce GT 730]                                              | 3         | 1.38%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 3         | 1.38%   |
| Intel HD Graphics 5500                                                      | 3         | 1.38%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 3         | 1.38%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 3         | 1.38%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 2         | 0.92%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 2         | 0.92%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 2         | 0.92%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 2         | 0.92%   |
| Nvidia GM108M [GeForce 840M]                                                | 2         | 0.92%   |
| Nvidia GK208B [GeForce GT 720]                                              | 2         | 0.92%   |
| Nvidia GK107 [GeForce GTX 650]                                              | 2         | 0.92%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 2         | 0.92%   |
| Nvidia GF119 [GeForce GT 610]                                               | 2         | 0.92%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]        | 2         | 0.92%   |
| Nvidia G92 [GeForce 9800 GT]                                                | 2         | 0.92%   |
| Nvidia G84M [GeForce 8600M GT]                                              | 2         | 0.92%   |
| Nvidia C79 [GeForce 9400M]                                                  | 2         | 0.92%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 2         | 0.92%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 2         | 0.92%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 2         | 0.92%   |
| AMD Renoir                                                                  | 2         | 0.92%   |
| AMD Oland XT [Radeon HD 8670 / R5 340X OEM / R7 250/350/350X OEM]           | 2         | 0.92%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 2         | 0.92%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 83        | 43.46%  |
| 1 x Nvidia     | 43        | 22.51%  |
| 1 x AMD        | 29        | 15.18%  |
| Intel + Nvidia | 18        | 9.42%   |
| 2 x Intel      | 10        | 5.24%   |
| Intel + AMD    | 5         | 2.62%   |
| AMD + Nvidia   | 2         | 1.05%   |
| 2 x Nvidia     | 1         | 0.52%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 147       | 77.37%  |
| Proprietary | 33        | 17.37%  |
| Unknown     | 10        | 5.26%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 139       | 72.77%  |
| 1.01-2.0   | 20        | 10.47%  |
| 3.01-4.0   | 11        | 5.76%   |
| 0.51-1.0   | 10        | 5.24%   |
| 7.01-8.0   | 5         | 2.62%   |
| 5.01-6.0   | 4         | 2.09%   |
| 2.01-3.0   | 1         | 0.52%   |
| 0.01-0.5   | 1         | 0.52%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 20        | 13.42%  |
| LG Display              | 18        | 12.08%  |
| Goldstar                | 13        | 8.72%   |
| Samsung Electronics     | 12        | 8.05%   |
| Dell                    | 10        | 6.71%   |
| Lenovo                  | 9         | 6.04%   |
| Chimei Innolux          | 9         | 6.04%   |
| Hewlett-Packard         | 7         | 4.7%    |
| Acer                    | 7         | 4.7%    |
| BOE                     | 6         | 4.03%   |
| BenQ                    | 5         | 3.36%   |
| Ancor Communications    | 4         | 2.68%   |
| ViewSonic               | 3         | 2.01%   |
| Philips                 | 3         | 2.01%   |
| Eizo                    | 3         | 2.01%   |
| Chi Mei Optoelectronics | 3         | 2.01%   |
| Apple                   | 3         | 2.01%   |
| Packard Bell            | 2         | 1.34%   |
| Vestel Elektronik       | 1         | 0.67%   |
| Toshiba                 | 1         | 0.67%   |
| Sony                    | 1         | 0.67%   |
| Sharp                   | 1         | 0.67%   |
| PRI                     | 1         | 0.67%   |
| PANDA                   | 1         | 0.67%   |
| KJT                     | 1         | 0.67%   |
| InfoVision              | 1         | 0.67%   |
| Iiyama                  | 1         | 0.67%   |
| HannStar                | 1         | 0.67%   |
| ASUSTek Computer        | 1         | 0.67%   |
| AOC                     | 1         | 0.67%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD03AB 1366x768 340x190mm 15.3-inch           | 2         | 1.33%   |
| Lenovo LCD Monitor LEN4031 1280x800 300x190mm 14.0-inch               | 2         | 1.33%   |
| Goldstar E2441 GSM581F 1920x1080 530x300mm 24.0-inch                  | 2         | 1.33%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 340x190mm 15.3-inch       | 2         | 1.33%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 310x170mm 13.9-inch      | 2         | 1.33%   |
| BenQ GW2765 BNQ78D6 2560x1440 600x340mm 27.2-inch                     | 2         | 1.33%   |
| ViewSonic VX2433wm VSC3822 1920x1080 520x290mm 23.4-inch              | 1         | 0.67%   |
| ViewSonic VA2026w VSC5020 1680x1050 430x270mm 20.0-inch               | 1         | 0.67%   |
| ViewSonic LCD Monitor VSC941C 1280x1024 340x270mm 17.1-inch           | 1         | 0.67%   |
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 710x400mm 32.1-inch    | 1         | 0.67%   |
| Toshiba TV TSB0218 3840x2160                                          | 1         | 0.67%   |
| Sony TV SNY9C01 1360x768                                              | 1         | 0.67%   |
| Sharp LCD Monitor SHP1453 1920x1080 350x190mm 15.7-inch               | 1         | 0.67%   |
| Samsung Electronics SyncMaster SAM0600 1600x900 440x250mm 19.9-inch   | 1         | 0.67%   |
| Samsung Electronics SyncMaster SAM05C5 1920x1080                      | 1         | 0.67%   |
| Samsung Electronics SyncMaster SAM036C 1920x1200 550x340mm 25.5-inch  | 1         | 0.67%   |
| Samsung Electronics SyncMaster SAM0364 1360x768 340x190mm 15.3-inch   | 1         | 0.67%   |
| Samsung Electronics SyncMaster SAM0304 1680x1050 490x320mm 23.0-inch  | 1         | 0.67%   |
| Samsung Electronics SMBX2231 SAM076D 1920x1080 480x270mm 21.7-inch    | 1         | 0.67%   |
| Samsung Electronics S24E390 SAM0C1A 1920x1080 520x290mm 23.4-inch     | 1         | 0.67%   |
| Samsung Electronics LCD Monitor SEC5442 1440x900 300x190mm 14.0-inch  | 1         | 0.67%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 340x190mm 15.3-inch  | 1         | 0.67%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 310x170mm 13.9-inch  | 1         | 0.67%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 340x190mm 15.3-inch | 1         | 0.67%   |
| Samsung Electronics LCD Monitor SAM03A2 1440x900 410x260mm 19.1-inch  | 1         | 0.67%   |
| PRI LED-MONITOR PRI0828 3840x2160 1150x650mm 52.0-inch                | 1         | 0.67%   |
| Philips PHL 328E1 PHLC204 3840x2160 700x390mm 31.5-inch               | 1         | 0.67%   |
| Philips PHL 278E9Q PHLC17F 1920x1080 600x340mm 27.2-inch              | 1         | 0.67%   |
| Philips LCD Monitor PHLC0B1 1920x1080 480x270mm 21.7-inch             | 1         | 0.67%   |
| PANDA LM156LF1L03 NCP001C 1920x1080 340x190mm 15.3-inch               | 1         | 0.67%   |
| Packard Bell Viseo223DX PKB0385 1920x1080 480x270mm 21.7-inch         | 1         | 0.67%   |
| Packard Bell Viseo 200Ws PKB00C2 1600x900 440x250mm 19.9-inch         | 1         | 0.67%   |
| LG Display LCD Monitor LGDCF01 1366x768 340x190mm 15.3-inch           | 1         | 0.67%   |
| LG Display LCD Monitor LGD11F9 1280x800 290x180mm 13.4-inch           | 1         | 0.67%   |
| LG Display LCD Monitor LGD059B 1920x1080 290x170mm 13.2-inch          | 1         | 0.67%   |
| LG Display LCD Monitor LGD0573 1920x1080 340x190mm 15.3-inch          | 1         | 0.67%   |
| LG Display LCD Monitor LGD055F 2560x1440 310x170mm 13.9-inch          | 1         | 0.67%   |
| LG Display LCD Monitor LGD04A3 1366x768 280x160mm 12.7-inch           | 1         | 0.67%   |
| LG Display LCD Monitor LGD0458 1366x768 310x170mm 13.9-inch           | 1         | 0.67%   |
| LG Display LCD Monitor LGD03DC 1366x768 280x160mm 12.7-inch           | 1         | 0.67%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 56        | 38.36%  |
| 1366x768 (WXGA)    | 32        | 21.92%  |
| 1600x900 (HD+)     | 11        | 7.53%   |
| 1280x800 (WXGA)    | 8         | 5.48%   |
| 3840x2160 (4K)     | 7         | 4.79%   |
| 2560x1440 (QHD)    | 6         | 4.11%   |
| 1920x1200 (WUXGA)  | 6         | 4.11%   |
| 1680x1050 (WSXGA+) | 4         | 2.74%   |
| 1440x900 (WXGA+)   | 4         | 2.74%   |
| 1280x1024 (SXGA)   | 4         | 2.74%   |
| 3440x1440          | 2         | 1.37%   |
| 2560x1080          | 2         | 1.37%   |
| 1360x768           | 2         | 1.37%   |
| 2048x1152          | 1         | 0.68%   |
| 1920x540           | 1         | 0.68%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 33        | 22.15%  |
| 13      | 29        | 19.46%  |
| 27      | 15        | 10.07%  |
| 24      | 14        | 9.4%    |
| 21      | 13        | 8.72%   |
| 23      | 10        | 6.71%   |
| 19      | 6         | 4.03%   |
| 12      | 5         | 3.36%   |
| 34      | 4         | 2.68%   |
| 17      | 4         | 2.68%   |
| 14      | 4         | 2.68%   |
| Unknown | 3         | 2.01%   |
| 42      | 2         | 1.34%   |
| 22      | 2         | 1.34%   |
| 52      | 1         | 0.67%   |
| 31      | 1         | 0.67%   |
| 25      | 1         | 0.67%   |
| 20      | 1         | 0.67%   |
| 18      | 1         | 0.67%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 53        | 35.81%  |
| 501-600     | 35        | 23.65%  |
| 401-500     | 23        | 15.54%  |
| 201-300     | 20        | 13.51%  |
| 701-800     | 4         | 2.7%    |
| 351-400     | 4         | 2.7%    |
| 601-700     | 3         | 2.03%   |
| Unknown     | 3         | 2.03%   |
| 901-1000    | 2         | 1.35%   |
| 1001-1500   | 1         | 0.68%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 113       | 79.02%  |
| 16/10 | 20        | 13.99%  |
| 5/4   | 4         | 2.8%    |
| 21/9  | 4         | 2.8%    |
| 3/2   | 2         | 1.4%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 32        | 21.77%  |
| 81-90          | 26        | 17.69%  |
| 91-100         | 23        | 15.65%  |
| 301-350        | 15        | 10.2%   |
| 101-110        | 10        | 6.8%    |
| 71-80          | 7         | 4.76%   |
| 151-200        | 7         | 4.76%   |
| 251-300        | 6         | 4.08%   |
| 61-70          | 5         | 3.4%    |
| 351-500        | 5         | 3.4%    |
| 141-150        | 3         | 2.04%   |
| Unknown        | 3         | 2.04%   |
| 121-130        | 2         | 1.36%   |
| 501-1000       | 2         | 1.36%   |
| More than 1000 | 1         | 0.68%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 51-100  | 54        | 36.49%  |
| 101-120 | 53        | 35.81%  |
| 121-160 | 31        | 20.95%  |
| 161-240 | 7         | 4.73%   |
| Unknown | 3         | 2.03%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 139       | 73.16%  |
| 0     | 42        | 22.11%  |
| 2     | 9         | 4.74%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 111       | 43.53%  |
| Realtek Semiconductor             | 79        | 30.98%  |
| Qualcomm Atheros                  | 28        | 10.98%  |
| Broadcom                          | 20        | 7.84%   |
| Nvidia                            | 4         | 1.57%   |
| Ralink Technology                 | 2         | 0.78%   |
| Ralink                            | 2         | 0.78%   |
| Sierra Wireless                   | 1         | 0.39%   |
| MediaTek                          | 1         | 0.39%   |
| Marvell Technology Group          | 1         | 0.39%   |
| JMicron Technology                | 1         | 0.39%   |
| Hewlett-Packard                   | 1         | 0.39%   |
| Ericsson Business Mobile Networks | 1         | 0.39%   |
| Edimax Technology                 | 1         | 0.39%   |
| D-Link System                     | 1         | 0.39%   |
| Bluegiga Technologies             | 1         | 0.39%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 62        | 19.44%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 18        | 5.64%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 14        | 4.39%   |
| Intel Wireless 8265 / 8275                                        | 12        | 3.76%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 10        | 3.13%   |
| Intel Wireless 7260                                               | 9         | 2.82%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 9         | 2.82%   |
| Intel Ethernet Connection I217-LM                                 | 8         | 2.51%   |
| Intel I211 Gigabit Network Connection                             | 6         | 1.88%   |
| Intel Wireless 7265                                               | 5         | 1.57%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 1.57%   |
| Intel Ethernet Connection (4) I219-LM                             | 5         | 1.57%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 4         | 1.25%   |
| Intel Wireless 8260                                               | 4         | 1.25%   |
| Intel Wi-Fi 6 AX200                                               | 4         | 1.25%   |
| Intel Ethernet Connection I217-V                                  | 4         | 1.25%   |
| Intel Ethernet Connection (2) I219-LM                             | 4         | 1.25%   |
| Intel Centrino Advanced-N 6200                                    | 4         | 1.25%   |
| Intel 82577LM Gigabit Network Connection                          | 4         | 1.25%   |
| Broadcom BCM43224 802.11a/b/g/n                                   | 4         | 1.25%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 3         | 0.94%   |
| Nvidia MCP79 Ethernet                                             | 3         | 0.94%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection           | 3         | 0.94%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 0.94%   |
| Intel Ethernet Connection (7) I219-V                              | 3         | 0.94%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 0.94%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 0.94%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3         | 0.94%   |
| Intel 82567LM Gigabit Network Connection                          | 3         | 0.94%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 3         | 0.94%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 0.63%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 0.63%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 0.63%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 0.63%   |
| Intel Wireless-AC 9260                                            | 2         | 0.63%   |
| Intel Wireless 3165                                               | 2         | 0.63%   |
| Intel WiFi Link 5100                                              | 2         | 0.63%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 2         | 0.63%   |
| Intel I210 Gigabit Network Connection                             | 2         | 0.63%   |
| Intel Ethernet Connection (2) I218-V                              | 2         | 0.63%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 74        | 57.81%  |
| Qualcomm Atheros      | 24        | 18.75%  |
| Broadcom              | 15        | 11.72%  |
| Realtek Semiconductor | 9         | 7.03%   |
| Ralink Technology     | 2         | 1.56%   |
| Ralink                | 2         | 1.56%   |
| Sierra Wireless       | 1         | 0.78%   |
| Edimax Technology     | 1         | 0.78%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 14        | 10.94%  |
| Intel Wireless 8265 / 8275                                                            | 12        | 9.38%   |
| Intel Wireless 7260                                                                   | 9         | 7.03%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 9         | 7.03%   |
| Intel Wireless 7265                                                                   | 5         | 3.91%   |
| Intel Wireless 8260                                                                   | 4         | 3.13%   |
| Intel Wi-Fi 6 AX200                                                                   | 4         | 3.13%   |
| Intel Centrino Advanced-N 6200                                                        | 4         | 3.13%   |
| Broadcom BCM43224 802.11a/b/g/n                                                       | 4         | 3.13%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 3         | 2.34%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                               | 3         | 2.34%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 3         | 2.34%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                | 3         | 2.34%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 2         | 1.56%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 2         | 1.56%   |
| Intel Wireless-AC 9260                                                                | 2         | 1.56%   |
| Intel Wireless 3165                                                                   | 2         | 1.56%   |
| Intel WiFi Link 5100                                                                  | 2         | 1.56%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                         | 2         | 1.56%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 2         | 1.56%   |
| Intel Centrino Wireless-N 2230                                                        | 2         | 1.56%   |
| Intel Centrino Advanced-N 6235                                                        | 2         | 1.56%   |
| Broadcom BCM4331 802.11a/b/g/n                                                        | 2         | 1.56%   |
| Sierra Wireless EM7455                                                                | 1         | 0.78%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 1         | 0.78%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                               | 1         | 0.78%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                              | 1         | 0.78%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                | 1         | 0.78%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                           | 1         | 0.78%   |
| Realtek RTL8188EE Wireless Network Adapter                                            | 1         | 0.78%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                               | 1         | 0.78%   |
| Ralink RT5370 Wireless Adapter                                                        | 1         | 0.78%   |
| Ralink MT7601U Wireless Adapter                                                       | 1         | 0.78%   |
| Ralink RT5360 Wireless 802.11n 1T/1R                                                  | 1         | 0.78%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                                  | 1         | 0.78%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 1         | 0.78%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 1         | 0.78%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                        | 1         | 0.78%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 1         | 0.78%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 0.78%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 83        | 44.86%  |
| Realtek Semiconductor    | 76        | 41.08%  |
| Qualcomm Atheros         | 9         | 4.86%   |
| Broadcom                 | 9         | 4.86%   |
| Nvidia                   | 4         | 2.16%   |
| MediaTek                 | 1         | 0.54%   |
| Marvell Technology Group | 1         | 0.54%   |
| JMicron Technology       | 1         | 0.54%   |
| D-Link System            | 1         | 0.54%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 62        | 32.98%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 18        | 9.57%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 10        | 5.32%   |
| Intel Ethernet Connection I217-LM                                             | 8         | 4.26%   |
| Intel I211 Gigabit Network Connection                                         | 6         | 3.19%   |
| Intel Ethernet Connection I219-LM                                             | 5         | 2.66%   |
| Intel Ethernet Connection (4) I219-LM                                         | 5         | 2.66%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                      | 4         | 2.13%   |
| Intel Ethernet Connection I217-V                                              | 4         | 2.13%   |
| Intel Ethernet Connection (2) I219-LM                                         | 4         | 2.13%   |
| Intel 82577LM Gigabit Network Connection                                      | 4         | 2.13%   |
| Nvidia MCP79 Ethernet                                                         | 3         | 1.6%    |
| Intel Ethernet Connection I218-LM                                             | 3         | 1.6%    |
| Intel Ethernet Connection (7) I219-V                                          | 3         | 1.6%    |
| Intel Ethernet Connection (4) I219-V                                          | 3         | 1.6%    |
| Intel Ethernet Connection (2) I219-V                                          | 3         | 1.6%    |
| Intel 82567LM Gigabit Network Connection                                      | 3         | 1.6%    |
| Realtek RTL8125 2.5GbE Controller                                             | 2         | 1.06%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 2         | 1.06%   |
| Intel I210 Gigabit Network Connection                                         | 2         | 1.06%   |
| Intel Ethernet Connection (2) I218-V                                          | 2         | 1.06%   |
| Intel 82578DM Gigabit Network Connection                                      | 2         | 1.06%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                               | 2         | 1.06%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 1         | 0.53%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 1         | 0.53%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                        | 1         | 0.53%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                 | 1         | 0.53%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                | 1         | 0.53%   |
| Nvidia MCP73 Ethernet                                                         | 1         | 0.53%   |
| MediaTek USB Ethernet-RNDIS                                                   | 1         | 0.53%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                       | 1         | 0.53%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                           | 1         | 0.53%   |
| Intel Ethernet Connection (6) I219-V                                          | 1         | 0.53%   |
| Intel Ethernet Connection (5) I219-LM                                         | 1         | 0.53%   |
| Intel Ethernet Connection (10) I219-LM                                        | 1         | 0.53%   |
| Intel 82579V Gigabit Network Connection                                       | 1         | 0.53%   |
| Intel 82574L Gigabit Network Connection                                       | 1         | 0.53%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 1         | 0.53%   |
| Intel 82567LM-3 Gigabit Network Connection                                    | 1         | 0.53%   |
| Intel 82567LF Gigabit Network Connection                                      | 1         | 0.53%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 182       | 59.09%  |
| WiFi     | 123       | 39.94%  |
| Modem    | 3         | 0.97%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 181       | 63.73%  |
| WiFi     | 101       | 35.56%  |
| Modem    | 2         | 0.7%    |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 110       | 57.89%  |
| 1     | 74        | 38.95%  |
| 3     | 6         | 3.16%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 189       | 99.47%  |
| Yes  | 1         | 0.53%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 44        | 44.44%  |
| Apple                           | 10        | 10.1%   |
| Cambridge Silicon Radio         | 9         | 9.09%   |
| Broadcom                        | 9         | 9.09%   |
| Qualcomm Atheros Communications | 7         | 7.07%   |
| Realtek Semiconductor           | 5         | 5.05%   |
| IMC Networks                    | 5         | 5.05%   |
| ASUSTek Computer                | 4         | 4.04%   |
| Lite-On Technology              | 2         | 2.02%   |
| Integrated System Solution      | 1         | 1.01%   |
| Hewlett-Packard                 | 1         | 1.01%   |
| Dell                            | 1         | 1.01%   |
| Alps Electric                   | 1         | 1.01%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                      | 27        | 27%     |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)     | 9         | 9%      |
| Apple Bluetooth Host Controller                         | 5         | 5%      |
| Intel Centrino Bluetooth Wireless Transceiver           | 4         | 4%      |
| Intel AX200 Bluetooth                                   | 4         | 4%      |
| Intel Wireless-AC 3168 Bluetooth                        | 3         | 3%      |
| Apple Built-in Bluetooth 2.0+EDR HCI                    | 3         | 3%      |
| Qualcomm Atheros Dell Wireless 1703 Bluetooth           | 2         | 2%      |
| Qualcomm Atheros AR9462 Bluetooth                       | 2         | 2%      |
| Intel Wireless-AC 9260 Bluetooth Adapter                | 2         | 2%      |
| Intel AX201 Bluetooth                                   | 2         | 2%      |
| Broadcom BCM20702A0 Bluetooth 4.0                       | 2         | 2%      |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]              | 2         | 2%      |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]      | 2         | 2%      |
| ASUS ASUS USB-BT500                                     | 2         | 2%      |
| Realtek RTL8723B Bluetooth                              | 1         | 1%      |
| Realtek  Bluetooth Adapter                              | 1         | 1%      |
| Realtek  Bluetooth 4.2 Adapter                          | 1         | 1%      |
| Realtek  Bluetooth 4.0 Adapter                          | 1         | 1%      |
| Realtek Bluetooth Radio                                 | 1         | 1%      |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                 | 1         | 1%      |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                  | 1         | 1%      |
| Qualcomm Atheros AR3012 Bluetooth 4.0                   | 1         | 1%      |
| Lite-On Qualcomm Atheros Bluetooth 4.0 + HS             | 1         | 1%      |
| Lite-On Atheros Bluetooth                               | 1         | 1%      |
| Intel Centrino Advanced-N 6230 Bluetooth adapter        | 1         | 1%      |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)          | 1         | 1%      |
| Integrated System Solution Bluetooth Device             | 1         | 1%      |
| IMC Networks Qualcomm Atheros Bluetooth 4.1             | 1         | 1%      |
| IMC Networks Qualcomm Atheros AR9462 Bluetooth 4.0 + HS | 1         | 1%      |
| IMC Networks Qualcomm Atheros AR3012 Bluetooth 4.0 + HS | 1         | 1%      |
| IMC Networks Bluetooth Module                           | 1         | 1%      |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter       | 1         | 1%      |
| HP Broadcom 2070 Bluetooth Combo                        | 1         | 1%      |
| Dell DW375 Bluetooth Module                             | 1         | 1%      |
| Broadcom Broadcom 4371 Bluetooth 4.1 Adapter            | 1         | 1%      |
| Broadcom BCM43142 Bluetooth 4.0                         | 1         | 1%      |
| Broadcom BCM2045B (BDC-2.1)                             | 1         | 1%      |
| ASUS BT-253 Bluetooth Adapter                           | 1         | 1%      |
| ASUS BT-183 Bluetooth 2.0+EDR adapter                   | 1         | 1%      |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Intel                | 157       | 60.38%  |
| Nvidia               | 45        | 17.31%  |
| AMD                  | 42        | 16.15%  |
| C-Media Electronics  | 7         | 2.69%   |
| Creative Labs        | 2         | 0.77%   |
| Texas Instruments    | 1         | 0.38%   |
| SteelSeries ApS      | 1         | 0.38%   |
| Griffin Technology   | 1         | 0.38%   |
| GN Netcom            | 1         | 0.38%   |
| Giga-Byte Technology | 1         | 0.38%   |
| Elgato Systems       | 1         | 0.38%   |
| Bose                 | 1         | 0.38%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 26        | 8.55%   |
| Intel Sunrise Point-LP HD Audio                                            | 20        | 6.58%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 17        | 5.59%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 16        | 5.26%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 12        | 3.95%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 11        | 3.62%   |
| Intel Haswell-ULT HD Audio Controller                                      | 10        | 3.29%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 10        | 3.29%   |
| Intel 8 Series HD Audio Controller                                         | 10        | 3.29%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 8         | 2.63%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 7         | 2.3%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 7         | 2.3%    |
| AMD Family 17h/19h HD Audio Controller                                     | 7         | 2.3%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 6         | 1.97%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 6         | 1.97%   |
| Nvidia GK107 HDMI Audio Controller                                         | 5         | 1.64%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5         | 1.64%   |
| AMD Starship/Matisse HD Audio Controller                                   | 5         | 1.64%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 5         | 1.64%   |
| Nvidia GP107GL High Definition Audio Controller                            | 4         | 1.32%   |
| Intel Cannon Lake PCH cAVS                                                 | 4         | 1.32%   |
| Intel Broadwell-U Audio Controller                                         | 4         | 1.32%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 4         | 1.32%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 4         | 1.32%   |
| Intel 200 Series PCH HD Audio                                              | 4         | 1.32%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4         | 1.32%   |
| AMD Navi 10 HDMI Audio                                                     | 4         | 1.32%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 4         | 1.32%   |
| Nvidia MCP79 High Definition Audio                                         | 3         | 0.99%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 3         | 0.99%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 3         | 0.99%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 3         | 0.99%   |
| AMD FCH Azalia Controller                                                  | 3         | 0.99%   |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 0.66%   |
| Nvidia GP108 High Definition Audio Controller                              | 2         | 0.66%   |
| Nvidia GP106 High Definition Audio Controller                              | 2         | 0.66%   |
| Nvidia GP104 High Definition Audio Controller                              | 2         | 0.66%   |
| Nvidia GM206 High Definition Audio Controller                              | 2         | 0.66%   |
| Nvidia GK106 HDMI Audio Controller                                         | 2         | 0.66%   |
| Nvidia GF119 HDMI Audio Controller                                         | 2         | 0.66%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 45        | 19.15%  |
| SK hynix            | 36        | 15.32%  |
| Kingston            | 32        | 13.62%  |
| Micron Technology   | 23        | 9.79%   |
| Unknown             | 22        | 9.36%   |
| Crucial             | 21        | 8.94%   |
| Corsair             | 14        | 5.96%   |
| G.Skill             | 10        | 4.26%   |
| Elpida              | 7         | 2.98%   |
| A-DATA Technology   | 4         | 1.7%    |
| Smart               | 3         | 1.28%   |
| Ramaxel Technology  | 3         | 1.28%   |
| Transcend           | 2         | 0.85%   |
| Nanya Technology    | 2         | 0.85%   |
| V-GeN               | 1         | 0.43%   |
| Unknown (ABCD)      | 1         | 0.43%   |
| Unknown (08B5)      | 1         | 0.43%   |
| Team                | 1         | 0.43%   |
| Silicon Power       | 1         | 0.43%   |
| SHARETRONIC         | 1         | 0.43%   |
| Ramos Technology    | 1         | 0.43%   |
| PNY                 | 1         | 0.43%   |
| KomputerBay         | 1         | 0.43%   |
| Avant               | 1         | 0.43%   |
| Unknown             | 1         | 0.43%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s            | 4         | 1.57%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s              | 3         | 1.18%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s   | 3         | 1.18%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s    | 3         | 1.18%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                  | 2         | 0.79%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s   | 2         | 0.79%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s   | 2         | 0.79%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s   | 2         | 0.79%   |
| SK hynix RAM HMT325U6CFR8C-H9 2GB DIMM DDR3 1333MT/s     | 2         | 0.79%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s   | 2         | 0.79%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2133MT/s   | 2         | 0.79%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s    | 2         | 0.79%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s | 2         | 0.79%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s    | 2         | 0.79%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s    | 2         | 0.79%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s    | 2         | 0.79%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s    | 2         | 0.79%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 1333MT/s      | 2         | 0.79%   |
| Micron RAM Module 4096MB SODIMM DDR3 1600MT/s            | 2         | 0.79%   |
| Micron RAM 8KTF51264HZ-1G6N1 4GB SODIMM DDR3 1600MT/s    | 2         | 0.79%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s     | 2         | 0.79%   |
| Kingston RAM Module 2048MB DIMM DDR2 800MT/s             | 2         | 0.79%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3200MT/s     | 2         | 0.79%   |
| Kingston RAM KHX1600C10D3/8G 4GB DIMM DDR3 1600MT/s      | 2         | 0.79%   |
| Kingston RAM 99U5584-010.A00LF 4096MB DIMM DDR3 1866MT/s | 2         | 0.79%   |
| Kingston RAM 99U5471-025.A00LF 4GB DIMM DDR3 1333MT/s    | 2         | 0.79%   |
| Elpida RAM Module 4096MB SODIMM DDR3 1600MT/s            | 2         | 0.79%   |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1600MT/s    | 2         | 0.79%   |
| Corsair RAM Module 4096MB SODIMM DDR3 1067MT/s           | 2         | 0.79%   |
| Corsair RAM CMZ8GX3M2A1600C9 4GB DIMM 1600MT/s           | 2         | 0.79%   |
| V-GeN RAM D4R8GS24A8R 8192MB SODIMM DDR4 2133MT/s        | 1         | 0.39%   |
| Unknown SODIMM 2048MB SODIMM DDR2 667MT/s                | 1         | 0.39%   |
| Unknown SODIMM 2048MB SODIMM DDR2 533MT/s                | 1         | 0.39%   |
| Unknown RAM Module 8192MB DIMM 1600MT/s                  | 1         | 0.39%   |
| Unknown RAM Module 4096MB SODIMM DDR4 2133MT/s           | 1         | 0.39%   |
| Unknown RAM Module 4096MB SODIMM DDR3 667MT/s            | 1         | 0.39%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1067MT/s           | 1         | 0.39%   |
| Unknown RAM Module 4096MB SODIMM DDR2                    | 1         | 0.39%   |
| Unknown RAM Module 4096MB SODIMM 1066MT/s                | 1         | 0.39%   |
| Unknown RAM Module 4096MB DIMM DDR3 1067MT/s             | 1         | 0.39%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 105       | 55.26%  |
| DDR4    | 57        | 30%     |
| DDR2    | 19        | 10%     |
| Unknown | 4         | 2.11%   |
| LPDDR3  | 3         | 1.58%   |
| SDRAM   | 1         | 0.53%   |
| LPDDR4  | 1         | 0.53%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 103       | 53.93%  |
| DIMM         | 80        | 41.88%  |
| Row Of Chips | 3         | 1.57%   |
| Chip         | 3         | 1.57%   |
| FB-DIMM      | 1         | 0.52%   |
| Unknown      | 1         | 0.52%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 91        | 42.72%  |
| 8192  | 63        | 29.58%  |
| 2048  | 40        | 18.78%  |
| 16384 | 17        | 7.98%   |
| 1024  | 2         | 0.94%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 63        | 29.86%  |
| 2400    | 32        | 15.17%  |
| 1333    | 32        | 15.17%  |
| 3200    | 12        | 5.69%   |
| 2133    | 12        | 5.69%   |
| 800     | 9         | 4.27%   |
| 667     | 9         | 4.27%   |
| 1067    | 8         | 3.79%   |
| 2667    | 7         | 3.32%   |
| 1334    | 7         | 3.32%   |
| 1867    | 6         | 2.84%   |
| 2666    | 3         | 1.42%   |
| 1066    | 3         | 1.42%   |
| 1866    | 2         | 0.95%   |
| Unknown | 2         | 0.95%   |
| 3600    | 1         | 0.47%   |
| 3000    | 1         | 0.47%   |
| 2933    | 1         | 0.47%   |
| 533     | 1         | 0.47%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Ricoh              | 1         | 25%     |
| Kyocera            | 1         | 25%     |
| Hewlett-Packard    | 1         | 25%     |
| Brother Industries | 1         | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model              | Computers | Percent |
|--------------------|-----------|---------|
| Ricoh SP 112       | 1         | 25%     |
| Kyocera FS-1025MFP | 1         | 25%     |
| HP LaserJet P3005  | 1         | 25%     |
| Brother MFC-J200   | 1         | 25%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart_bsd/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Canon       | 2         | 66.67%  |
| Seiko Epson | 1         | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart_bsd/scanner_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                                                             | 2         | 66.67%  |
| Seiko Epson WF-2860 Series EPSON Scanner USB2.0 Printer EPSON Utility USB2.0 Faxout | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart_bsd/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 23        | 25.84%  |
| Realtek Semiconductor                  | 9         | 10.11%  |
| Microdia                               | 9         | 10.11%  |
| IMC Networks                           | 7         | 7.87%   |
| Acer                                   | 7         | 7.87%   |
| Suyin                                  | 5         | 5.62%   |
| Sunplus Innovation Technology          | 5         | 5.62%   |
| Silicon Motion                         | 3         | 3.37%   |
| Lite-On Technology                     | 3         | 3.37%   |
| Z-Star Microelectronics                | 2         | 2.25%   |
| Logitech                               | 2         | 2.25%   |
| ARC International                      | 2         | 2.25%   |
| Apple                                  | 2         | 2.25%   |
| Syntek                                 | 1         | 1.12%   |
| Ricoh                                  | 1         | 1.12%   |
| Luxvisions Innotech Limited            | 1         | 1.12%   |
| Linux Foundation                       | 1         | 1.12%   |
| Lenovo                                 | 1         | 1.12%   |
| KYE Systems (Mouse Systems)            | 1         | 1.12%   |
| Generalplus Technology                 | 1         | 1.12%   |
| Creative Technology                    | 1         | 1.12%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 1.12%   |
| Alcor Micro                            | 1         | 1.12%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 6         | 6.67%   |
| Sunplus Integrated_Webcam_HD                         | 3         | 3.33%   |
| Realtek Realtek USB2.0 PC Camera                     | 3         | 3.33%   |
| Microdia Integrated_Webcam_HD                        | 3         | 3.33%   |
| Lite-On Integrated Camera                            | 3         | 3.33%   |
| Suyin Integrated_Webcam_HD                           | 2         | 2.22%   |
| Realtek USB Camera                                   | 2         | 2.22%   |
| Realtek Integrated_Webcam_HD                         | 2         | 2.22%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 2         | 2.22%   |
| Chicony UVC 1.00 device HD UVC WebCam                | 2         | 2.22%   |
| Chicony USB2.0 VGA UVC WebCam                        | 2         | 2.22%   |
| Chicony USB2.0 HD UVC WebCam                         | 2         | 2.22%   |
| Chicony FJ Camera                                    | 2         | 2.22%   |
| ARC International Camera                             | 2         | 2.22%   |
| Acer Integrated Camera                               | 2         | 2.22%   |
| Z-Star Venus USB2.0 Camera                           | 1         | 1.11%   |
| Z-Star Vega USB 2.0 Camera                           | 1         | 1.11%   |
| Syntek Lenovo EasyCamera                             | 1         | 1.11%   |
| Suyin HP webcam [dv6-1190en]                         | 1         | 1.11%   |
| Suyin Acer Crystal Eye webcam                        | 1         | 1.11%   |
| Suyin 1.3M HD WebCam                                 | 1         | 1.11%   |
| Sunplus Laptop_Integrated_Webcam_FHD                 | 1         | 1.11%   |
| Sunplus Aukey-PC-LM1E Camera                         | 1         | 1.11%   |
| Silicon Motion WebCam SCB-1100N                      | 1         | 1.11%   |
| Silicon Motion Realtek USB2.0 PC Camera              | 1         | 1.11%   |
| Silicon Motion ATIV Real HD Camera                   | 1         | 1.11%   |
| Ricoh HD Webcam                                      | 1         | 1.11%   |
| Realtek Integrated_Webcam_FHD                        | 1         | 1.11%   |
| Realtek Integrated_Webcam_8M                         | 1         | 1.11%   |
| Realtek Acer 640 x 480 laptop camera                 | 1         | 1.11%   |
| Microdia Webcam Vitade AF                            | 1         | 1.11%   |
| Microdia Laptop_Integrated_Webcam_HD                 | 1         | 1.11%   |
| Microdia Integrated Webcam                           | 1         | 1.11%   |
| Microdia Dell Laptop Integrated Webcam HD            | 1         | 1.11%   |
| Microdia Dell Integrated HD Webcam                   | 1         | 1.11%   |
| Microdia ASUS USB2.0 Webcam                          | 1         | 1.11%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 1         | 1.11%   |
| Logitech Webcam C310                                 | 1         | 1.11%   |
| Logitech C922 Pro Stream Webcam                      | 1         | 1.11%   |
| Linux Foundation HD Camera                           | 1         | 1.11%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 6         | 40%     |
| AuthenTec             | 4         | 26.67%  |
| Upek                  | 1         | 6.67%   |
| Synaptics             | 1         | 6.67%   |
| STMicroelectronics    | 1         | 6.67%   |
| Elan Microelectronics | 1         | 6.67%   |
| Broadcom              | 1         | 6.67%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS7500 Touch Fingerprint Sensor                            | 2         | 13.33%  |
| Validity Sensors VFS495 Fingerprint Reader                                   | 1         | 6.67%   |
| Validity Sensors VFS451 Fingerprint Reader                                   | 1         | 6.67%   |
| Validity Sensors VFS 5011 fingerprint sensor                                 | 1         | 6.67%   |
| Validity Sensors Synaptics WBDI                                              | 1         | 6.67%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 1         | 6.67%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                             | 1         | 6.67%   |
| STMicroelectronics Fingerprint Reader                                        | 1         | 6.67%   |
| Elan ELAN WBF Fingerprint Sensor                                             | 1         | 6.67%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 6.67%   |
| AuthenTec AuthenTec Inc. AES2660                                             | 1         | 6.67%   |
| AuthenTec AuthenTec Inc. AES1660                                             | 1         | 6.67%   |
| AuthenTec AES2810                                                            | 1         | 6.67%   |
| AuthenTec AES2501 Fingerprint Sensor                                         | 1         | 6.67%   |

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
| 1     | 76        | 40%     |
| 2     | 44        | 23.16%  |
| 0     | 43        | 22.63%  |
| 3     | 18        | 9.47%   |
| 4     | 6         | 3.16%   |
| 5     | 2         | 1.05%   |
| 6     | 1         | 0.53%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 134       | 52.96%  |
| Card reader              | 43        | 17%     |
| Bluetooth                | 23        | 9.09%   |
| Net/wireless             | 20        | 7.91%   |
| Fingerprint reader       | 15        | 5.93%   |
| Sound                    | 8         | 3.16%   |
| Firewire controller      | 3         | 1.19%   |
| Storage/raid             | 2         | 0.79%   |
| Network                  | 2         | 0.79%   |
| Net/ethernet             | 2         | 0.79%   |
| Storage                  | 1         | 0.4%    |

