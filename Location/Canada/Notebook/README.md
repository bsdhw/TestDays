BSD in Canada - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------------

A project to collect tested hardware configurations for BSD in Canada.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 226

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | [1aec80e256](https://bsd-hardware.info/?probe=1aec80e256) | Dec 18, 2024 |
| Alienware     | m15 R6                      | [477e29857e](https://bsd-hardware.info/?probe=477e29857e) | Dec 03, 2024 |
| Alienware     | m15 R6                      | [b19c3ccd89](https://bsd-hardware.info/?probe=b19c3ccd89) | Dec 02, 2024 |
| Panasonic     | CF-52PFPBSFQ                | [96e9c16dc5](https://bsd-hardware.info/?probe=96e9c16dc5) | Oct 26, 2024 |
| Dell          | Latitude 7490               | [46b2b68262](https://bsd-hardware.info/?probe=46b2b68262) | Oct 24, 2024 |
| ASUSTek       | 1000HE                      | [1a04fd3a79](https://bsd-hardware.info/?probe=1a04fd3a79) | Oct 22, 2024 |
| Matsushita... | CF-51RCVDNLM                | [d911fcdc27](https://bsd-hardware.info/?probe=d911fcdc27) | Oct 21, 2024 |
| Panasonic     | CF-54-1                     | [2c0a3bc2e3](https://bsd-hardware.info/?probe=2c0a3bc2e3) | Oct 18, 2024 |
| Lenovo        | ThinkPad X280 20KF001UUS    | [b63d757906](https://bsd-hardware.info/?probe=b63d757906) | Oct 14, 2024 |
| Lenovo        | ThinkPad T410 2537N24       | [e7b0a90d19](https://bsd-hardware.info/?probe=e7b0a90d19) | Oct 13, 2024 |
| Lenovo        | ThinkPad X260 20F5S2GM00    | [dbdce5230f](https://bsd-hardware.info/?probe=dbdce5230f) | Oct 11, 2024 |
| Panasonic     | CF-53AAGHYDM                | [bbda83e57b](https://bsd-hardware.info/?probe=bbda83e57b) | Oct 10, 2024 |
| Fujitsu       | LIFEBOOK E752               | [01fa981bc4](https://bsd-hardware.info/?probe=01fa981bc4) | Oct 10, 2024 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [37252abbb6](https://bsd-hardware.info/?probe=37252abbb6) | Oct 09, 2024 |
| Lenovo        | ThinkPad T430 2347GZU       | [075e5d2557](https://bsd-hardware.info/?probe=075e5d2557) | Oct 08, 2024 |
| Datto         | Unknown                     | [84a22f341f](https://bsd-hardware.info/?probe=84a22f341f) | Sep 29, 2024 |
| Apple         | MacBookPro8,1               | [a809727aca](https://bsd-hardware.info/?probe=a809727aca) | Sep 17, 2024 |
| Framework     | Laptop                      | [c374e02dcb](https://bsd-hardware.info/?probe=c374e02dcb) | Sep 11, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [bca7dbbacf](https://bsd-hardware.info/?probe=bca7dbbacf) | Aug 30, 2024 |
| Fujitsu       | LIFEBOOK E752               | [1be0ff70bb](https://bsd-hardware.info/?probe=1be0ff70bb) | Aug 21, 2024 |
| Lenovo        | ThinkPad X230 Tablet 343... | [482cba9f2f](https://bsd-hardware.info/?probe=482cba9f2f) | Aug 05, 2024 |
| Dell          | Studio 1535                 | [def6732820](https://bsd-hardware.info/?probe=def6732820) | Aug 03, 2024 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [3d93b160f7](https://bsd-hardware.info/?probe=3d93b160f7) | Jul 25, 2024 |
| Toshiba       | Satellite S50D-A            | [42d990a580](https://bsd-hardware.info/?probe=42d990a580) | Jul 16, 2024 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [3589bb8629](https://bsd-hardware.info/?probe=3589bb8629) | Jun 16, 2024 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | [f5d17502cb](https://bsd-hardware.info/?probe=f5d17502cb) | May 29, 2024 |
| Lenovo        | G560 0679                   | [50faff095e](https://bsd-hardware.info/?probe=50faff095e) | May 27, 2024 |
| Matsushita... | CF-48V4KNDQM                | [9297aa94a7](https://bsd-hardware.info/?probe=9297aa94a7) | May 24, 2024 |
| Matsushita... | CF-51RCVDNLM                | [c20eb22761](https://bsd-hardware.info/?probe=c20eb22761) | May 21, 2024 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [9d43b94e3a](https://bsd-hardware.info/?probe=9d43b94e3a) | May 19, 2024 |
| Gateway       | ID49C                       | [5c123882b9](https://bsd-hardware.info/?probe=5c123882b9) | May 19, 2024 |
| ASUSTek       | 1000HE                      | [65db5ea354](https://bsd-hardware.info/?probe=65db5ea354) | May 11, 2024 |
| Acer          | Aspire R3-131T              | [dec4102ec0](https://bsd-hardware.info/?probe=dec4102ec0) | May 07, 2024 |
| Lenovo        | ThinkPad X240 20AMS3FY00    | [1dc74d60e6](https://bsd-hardware.info/?probe=1dc74d60e6) | May 06, 2024 |
| Panasonic     | CF-54-1                     | [00de332c2c](https://bsd-hardware.info/?probe=00de332c2c) | May 04, 2024 |
| Panasonic     | CF-52PFPBSFQ                | [48423bbece](https://bsd-hardware.info/?probe=48423bbece) | May 03, 2024 |
| Lenovo        | ThinkPad T410 2537N24       | [04370189ed](https://bsd-hardware.info/?probe=04370189ed) | Apr 29, 2024 |
| Lenovo        | ThinkPad T430 2347GZU       | [f49f1b3ac2](https://bsd-hardware.info/?probe=f49f1b3ac2) | Apr 28, 2024 |
| Dell          | Latitude 7490               | [510590d1c7](https://bsd-hardware.info/?probe=510590d1c7) | Apr 24, 2024 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [bf89bc5c69](https://bsd-hardware.info/?probe=bf89bc5c69) | Apr 24, 2024 |
| Lenovo        | ThinkPad X260 20F5S2GM00    | [8a37e6930f](https://bsd-hardware.info/?probe=8a37e6930f) | Apr 23, 2024 |
| Panasonic     | CF-53AAGHYDM                | [3eac3d5a68](https://bsd-hardware.info/?probe=3eac3d5a68) | Apr 23, 2024 |
| Deciso        | NetBoard-A20                | [c64fcd31dd](https://bsd-hardware.info/?probe=c64fcd31dd) | Apr 23, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [4f57a0fe86](https://bsd-hardware.info/?probe=4f57a0fe86) | Apr 22, 2024 |
| Dell          | Latitude 7490               | [e2af0367f5](https://bsd-hardware.info/?probe=e2af0367f5) | Apr 11, 2024 |
| Dell          | XPS 15 7590                 | [1458ea15f4](https://bsd-hardware.info/?probe=1458ea15f4) | Apr 04, 2024 |
| Dell          | Latitude 7220 Rugged Ext... | [d882577127](https://bsd-hardware.info/?probe=d882577127) | Mar 07, 2024 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [fb1f5f8545](https://bsd-hardware.info/?probe=fb1f5f8545) | Feb 16, 2024 |
| Unknown       | Unknown                     | [2af11d5bbf](https://bsd-hardware.info/?probe=2af11d5bbf) | Feb 11, 2024 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [0e644c21cc](https://bsd-hardware.info/?probe=0e644c21cc) | Feb 02, 2024 |
| ASUSTek       | K50IJ                       | [b5cc2ab7ff](https://bsd-hardware.info/?probe=b5cc2ab7ff) | Jan 31, 2024 |
| ASUSTek       | K50IJ                       | [a952b43f14](https://bsd-hardware.info/?probe=a952b43f14) | Jan 31, 2024 |
| Dell          | Latitude 7320 Detachable    | [d29b86c141](https://bsd-hardware.info/?probe=d29b86c141) | Jan 21, 2024 |
| Dell          | Latitude 7320 Detachable    | [b1f9acd523](https://bsd-hardware.info/?probe=b1f9acd523) | Jan 18, 2024 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | [d08f6339ae](https://bsd-hardware.info/?probe=d08f6339ae) | Jan 12, 2024 |
| Lenovo        | ThinkPad P70 20ESS1L600     | [2e3870f2ee](https://bsd-hardware.info/?probe=2e3870f2ee) | Dec 07, 2023 |
| Apple         | MacBookAir4,1               | [4661b8933c](https://bsd-hardware.info/?probe=4661b8933c) | Nov 25, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [9762745c92](https://bsd-hardware.info/?probe=9762745c92) | Nov 23, 2023 |
| Lenovo        | ThinkPad X260 20F5S2GM00    | [b5be73085a](https://bsd-hardware.info/?probe=b5be73085a) | Nov 23, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [0d706d98b4](https://bsd-hardware.info/?probe=0d706d98b4) | Nov 23, 2023 |
| Fujitsu       | LIFEBOOK E752               | [1da7551908](https://bsd-hardware.info/?probe=1da7551908) | Nov 23, 2023 |
| Dell          | Latitude 7490               | [e860d3dbcf](https://bsd-hardware.info/?probe=e860d3dbcf) | Nov 23, 2023 |
| Fujitsu       | LIFEBOOK E752               | [ee95b41634](https://bsd-hardware.info/?probe=ee95b41634) | Nov 10, 2023 |
| Panasonic     | CF-54-1                     | [c530bdbd88](https://bsd-hardware.info/?probe=c530bdbd88) | Nov 10, 2023 |
| Apple         | MacBookPro7,1               | [91d07ef080](https://bsd-hardware.info/?probe=91d07ef080) | Nov 01, 2023 |
| Datto         | Unknown                     | [8b59510085](https://bsd-hardware.info/?probe=8b59510085) | Oct 27, 2023 |
| Panasonic     | CF-52PFPBSFQ                | [4a97ab307a](https://bsd-hardware.info/?probe=4a97ab307a) | Oct 22, 2023 |
| Lenovo        | ThinkPad T430 2347GZU       | [88ae89f787](https://bsd-hardware.info/?probe=88ae89f787) | Oct 22, 2023 |
| Panasonic     | CF-53AAGHYDM                | [6f29731875](https://bsd-hardware.info/?probe=6f29731875) | Oct 22, 2023 |
| ASUSTek       | 1000HE                      | [249959fd2c](https://bsd-hardware.info/?probe=249959fd2c) | Oct 21, 2023 |
| Matsushita... | CF-51RCVDNLM                | [ec5aff8b6b](https://bsd-hardware.info/?probe=ec5aff8b6b) | Oct 21, 2023 |
| Matsushita... | CF-48V4KNDQM                | [625f272fcd](https://bsd-hardware.info/?probe=625f272fcd) | Oct 21, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | [965e71ac80](https://bsd-hardware.info/?probe=965e71ac80) | Oct 21, 2023 |
| Lenovo        | ThinkPad T410 2537N24       | [fd75aab1c6](https://bsd-hardware.info/?probe=fd75aab1c6) | Oct 20, 2023 |
| Lenovo        | ThinkPad T470 20HES0HU00    | [a64fe205a9](https://bsd-hardware.info/?probe=a64fe205a9) | Sep 17, 2023 |
| Shuttle       | DS67U                       | [55c2922a25](https://bsd-hardware.info/?probe=55c2922a25) | Sep 04, 2023 |
| Datto         | Unknown                     | [418eab5eaa](https://bsd-hardware.info/?probe=418eab5eaa) | Aug 23, 2023 |
| Star Labs     | Lite                        | [eabab74d7b](https://bsd-hardware.info/?probe=eabab74d7b) | Aug 18, 2023 |
| ASUSTek       | ROG Strix G513QC_G513QC     | [b90e62e27d](https://bsd-hardware.info/?probe=b90e62e27d) | Aug 04, 2023 |
| Acer          | Aspire 4736Z                | [bccf97f694](https://bsd-hardware.info/?probe=bccf97f694) | Jul 20, 2023 |
| Deciso        | NetBoard-A20                | [0754642fe6](https://bsd-hardware.info/?probe=0754642fe6) | Jun 07, 2023 |
| Lenovo        | ThinkPad T15p Gen 3 21DA... | [8cc6299ba9](https://bsd-hardware.info/?probe=8cc6299ba9) | May 31, 2023 |
| Acer          | Aspire E5-573               | [7bcb7c96be](https://bsd-hardware.info/?probe=7bcb7c96be) | May 23, 2023 |
| Lenovo        | ThinkPad T410 2537N24       | [6cd0f02045](https://bsd-hardware.info/?probe=6cd0f02045) | May 08, 2023 |
| Matsushita... | CF-48V4KNDQM                | [79f10d24d6](https://bsd-hardware.info/?probe=79f10d24d6) | May 07, 2023 |
| ASUSTek       | 1000HE                      | [36214f8bed](https://bsd-hardware.info/?probe=36214f8bed) | May 07, 2023 |
| Matsushita... | CF-51RCVDNLM                | [105a885451](https://bsd-hardware.info/?probe=105a885451) | May 05, 2023 |
| Lenovo        | ThinkPad T420s 41742BU      | [161fe49de4](https://bsd-hardware.info/?probe=161fe49de4) | May 05, 2023 |
| Lenovo        | ThinkPad X230 2325T4T       | [00303b7a59](https://bsd-hardware.info/?probe=00303b7a59) | May 05, 2023 |
| Lenovo        | ThinkPad X220 429043U       | [bb714a4350](https://bsd-hardware.info/?probe=bb714a4350) | May 05, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [28e76d5531](https://bsd-hardware.info/?probe=28e76d5531) | May 04, 2023 |
| Lenovo        | ThinkPad T430 2347GZU       | [8c3f486dbc](https://bsd-hardware.info/?probe=8c3f486dbc) | May 03, 2023 |
| Panasonic     | CF-52PFPBSFQ                | [e2c3df29b5](https://bsd-hardware.info/?probe=e2c3df29b5) | May 03, 2023 |
| Panasonic     | CF-53AAGHYDM                | [c7daf17edb](https://bsd-hardware.info/?probe=c7daf17edb) | May 02, 2023 |
| Lenovo        | ThinkPad X260 20F5S2GM00    | [c4af168c4a](https://bsd-hardware.info/?probe=c4af168c4a) | May 01, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [cf504f51df](https://bsd-hardware.info/?probe=cf504f51df) | May 01, 2023 |
| Fujitsu       | LIFEBOOK E752               | [44ea9fb6ae](https://bsd-hardware.info/?probe=44ea9fb6ae) | Apr 30, 2023 |
| Google        | Terra                       | [ef1619f65f](https://bsd-hardware.info/?probe=ef1619f65f) | Apr 13, 2023 |
| Google        | Terra                       | [bf598bc5bf](https://bsd-hardware.info/?probe=bf598bc5bf) | Apr 13, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X3C... | [0249b4e73f](https://bsd-hardware.info/?probe=0249b4e73f) | Apr 11, 2023 |
| HP            | Pavilion dv6                | [ce2cc6852d](https://bsd-hardware.info/?probe=ce2cc6852d) | Mar 27, 2023 |
| Dell          | Latitude 5420               | [4e22bbc131](https://bsd-hardware.info/?probe=4e22bbc131) | Mar 26, 2023 |
| eMachines     | eM350                       | [bb900ace2d](https://bsd-hardware.info/?probe=bb900ace2d) | Mar 25, 2023 |
| Alienware     | 14                          | [742d648570](https://bsd-hardware.info/?probe=742d648570) | Mar 25, 2023 |
| Acer          | AOD270                      | [73877008e9](https://bsd-hardware.info/?probe=73877008e9) | Mar 25, 2023 |
| Intel         | SandyBridge Platform        | [954a21f7de](https://bsd-hardware.info/?probe=954a21f7de) | Mar 23, 2023 |
| HP            | ProBook 640 G3              | [860471150b](https://bsd-hardware.info/?probe=860471150b) | Mar 18, 2023 |
| Gigabyte      | GB-BSi3A-6100               | [e7ef795b9b](https://bsd-hardware.info/?probe=e7ef795b9b) | Feb 19, 2023 |
| Gigabyte      | GB-BSi3A-6100               | [cd2273037f](https://bsd-hardware.info/?probe=cd2273037f) | Feb 19, 2023 |
| Unknown       | Unknown                     | [4cae5c6bb7](https://bsd-hardware.info/?probe=4cae5c6bb7) | Feb 01, 2023 |
| HP            | 2000                        | [7f29899321](https://bsd-hardware.info/?probe=7f29899321) | Jan 09, 2023 |
| Dell          | XPS 13 9310                 | [e56cfbdedc](https://bsd-hardware.info/?probe=e56cfbdedc) | Jan 08, 2023 |
| Dell          | XPS 13 9310                 | [db483e3d46](https://bsd-hardware.info/?probe=db483e3d46) | Jan 08, 2023 |
| Lenovo        | ThinkPad T400 2764CTO       | [26f8459193](https://bsd-hardware.info/?probe=26f8459193) | Jan 06, 2023 |
| HP            | 2000                        | [5414b7c943](https://bsd-hardware.info/?probe=5414b7c943) | Dec 09, 2022 |
| Acer          | Swift SF114-34              | [2c560bad00](https://bsd-hardware.info/?probe=2c560bad00) | Dec 05, 2022 |
| Panasonic     | CF-54-1                     | [0c5820ea0d](https://bsd-hardware.info/?probe=0c5820ea0d) | Dec 01, 2022 |
| Lenovo        | ThinkPad X230 2325T4T       | [f0cc17c7eb](https://bsd-hardware.info/?probe=f0cc17c7eb) | Nov 21, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [8257d11669](https://bsd-hardware.info/?probe=8257d11669) | Nov 20, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [4044f32351](https://bsd-hardware.info/?probe=4044f32351) | Nov 12, 2022 |
| Lenovo        | ThinkPad X260 20F5S2GM00    | [b8874a6df3](https://bsd-hardware.info/?probe=b8874a6df3) | Nov 10, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [e8aea441aa](https://bsd-hardware.info/?probe=e8aea441aa) | Nov 06, 2022 |
| Lenovo        | ThinkPad X220 429043U       | [e5716f886a](https://bsd-hardware.info/?probe=e5716f886a) | Oct 30, 2022 |
| Lenovo        | ThinkPad T420s 41742BU      | [34f0a2bc03](https://bsd-hardware.info/?probe=34f0a2bc03) | Oct 30, 2022 |
| Lenovo        | ThinkPad T460 20FMS10N00    | [04ce25bd7f](https://bsd-hardware.info/?probe=04ce25bd7f) | Oct 29, 2022 |
| Fujitsu       | LIFEBOOK E752               | [e3c5057898](https://bsd-hardware.info/?probe=e3c5057898) | Oct 29, 2022 |
| Unknown       | Unknown                     | [2df5c5b434](https://bsd-hardware.info/?probe=2df5c5b434) | Oct 28, 2022 |
| Panasonic     | CF-53AAGHYDM                | [f2fafaa9e3](https://bsd-hardware.info/?probe=f2fafaa9e3) | Oct 27, 2022 |
| Matsushita... | CF-48V4KNDQM                | [d96fbc17b5](https://bsd-hardware.info/?probe=d96fbc17b5) | Oct 27, 2022 |
| Panasonic     | CF-52PFPBSFQ                | [088e0245af](https://bsd-hardware.info/?probe=088e0245af) | Oct 27, 2022 |
| Matsushita... | CF-51RCVDNLM                | [6e8067d4d8](https://bsd-hardware.info/?probe=6e8067d4d8) | Oct 26, 2022 |
| Lenovo        | ThinkPad T410 2537N24       | [b7a4ee06a6](https://bsd-hardware.info/?probe=b7a4ee06a6) | Oct 26, 2022 |
| Lenovo        | ThinkPad T430 2347GZU       | [f2236f17ee](https://bsd-hardware.info/?probe=f2236f17ee) | Oct 25, 2022 |
| ASUSTek       | 1000HE                      | [c4bbcf9537](https://bsd-hardware.info/?probe=c4bbcf9537) | Oct 24, 2022 |
| MSI           | GL65 Leopard 10SFSK         | [2ea7c7f9a2](https://bsd-hardware.info/?probe=2ea7c7f9a2) | Oct 10, 2022 |
| MSI           | GL65 Leopard 10SFSK         | [489567748e](https://bsd-hardware.info/?probe=489567748e) | Oct 01, 2022 |
| Intel         | H81U                        | [fa8c32528a](https://bsd-hardware.info/?probe=fa8c32528a) | Sep 28, 2022 |
| Acer          | Swift SF313-52              | [83516dabac](https://bsd-hardware.info/?probe=83516dabac) | Sep 28, 2022 |
| Acer          | Swift SF313-52              | [6339e6b468](https://bsd-hardware.info/?probe=6339e6b468) | Sep 25, 2022 |
| Lenovo        | ThinkPad X250 20CL001GUS    | [2f1f82558e](https://bsd-hardware.info/?probe=2f1f82558e) | Sep 18, 2022 |
| Google        | Peppy                       | [80ffa77224](https://bsd-hardware.info/?probe=80ffa77224) | Sep 15, 2022 |
| Intel         | H81U                        | [b5e2598580](https://bsd-hardware.info/?probe=b5e2598580) | Aug 03, 2022 |
| Intel         | H81U                        | [8f50dbe259](https://bsd-hardware.info/?probe=8f50dbe259) | Aug 01, 2022 |
| Dell          | Latitude E7440              | [03497b7b2a](https://bsd-hardware.info/?probe=03497b7b2a) | Jul 27, 2022 |
| Lenovo        | IdeaPad Y580 20132          | [3df3bd2f62](https://bsd-hardware.info/?probe=3df3bd2f62) | Jul 22, 2022 |
| Dell          | Studio 1747                 | [7ae292b282](https://bsd-hardware.info/?probe=7ae292b282) | May 21, 2022 |
| Dell          | Inspiron 5559               | [a7111b84cb](https://bsd-hardware.info/?probe=a7111b84cb) | May 08, 2022 |
| Fujitsu       | LIFEBOOK E752               | [3e60a82218](https://bsd-hardware.info/?probe=3e60a82218) | May 06, 2022 |
| ASUSTek       | 1000HE                      | [a6393754b4](https://bsd-hardware.info/?probe=a6393754b4) | May 05, 2022 |
| Matsushita... | CF-48V4KNDQM                | [774cab5326](https://bsd-hardware.info/?probe=774cab5326) | May 03, 2022 |
| Matsushita... | CF-51RCVDNLM                | [4b1abdd507](https://bsd-hardware.info/?probe=4b1abdd507) | May 03, 2022 |
| Lenovo        | ThinkPad T410 2537N24       | [2884106c6b](https://bsd-hardware.info/?probe=2884106c6b) | May 03, 2022 |
| Lenovo        | ThinkPad T430 2347GZU       | [00ba6ca9f8](https://bsd-hardware.info/?probe=00ba6ca9f8) | May 03, 2022 |
| Lenovo        | ThinkPad T420s 41742BU      | [6b77fe651f](https://bsd-hardware.info/?probe=6b77fe651f) | May 03, 2022 |
| Lenovo        | ThinkPad X220 429043U       | [f3c30a6190](https://bsd-hardware.info/?probe=f3c30a6190) | May 02, 2022 |
| Panasonic     | CF-53AAGHYDM                | [abd8754907](https://bsd-hardware.info/?probe=abd8754907) | May 01, 2022 |
| Panasonic     | CF-52PFPBSFQ                | [1ce63e2214](https://bsd-hardware.info/?probe=1ce63e2214) | Apr 29, 2022 |
| Toshiba       | Satellite Pro T130          | [62dd51afcf](https://bsd-hardware.info/?probe=62dd51afcf) | Apr 11, 2022 |
| Intel         | H81U                        | [71068a0577](https://bsd-hardware.info/?probe=71068a0577) | Mar 01, 2022 |
| Lenovo        | ThinkPad X250 20CL001GUS    | [4ae2360503](https://bsd-hardware.info/?probe=4ae2360503) | Jan 11, 2022 |
| Toshiba       | TECRA Z40-B                 | [d498fcd3f8](https://bsd-hardware.info/?probe=d498fcd3f8) | Jan 02, 2022 |
| ASUSTek       | U31SD                       | [a07366611d](https://bsd-hardware.info/?probe=a07366611d) | Jan 02, 2022 |
| ASUSTek       | TUF GAMING FX504GD_FX80G... | [259b5cc7b2](https://bsd-hardware.info/?probe=259b5cc7b2) | Dec 28, 2021 |
| Lenovo        | ThinkPad X280 20KF001UUS    | [5b9001009e](https://bsd-hardware.info/?probe=5b9001009e) | Dec 20, 2021 |
| Lenovo        | ThinkPad T420s 41742BU      | [a86326d049](https://bsd-hardware.info/?probe=a86326d049) | Dec 11, 2021 |
| Lenovo        | ThinkPad X220 429043U       | [339779baad](https://bsd-hardware.info/?probe=339779baad) | Nov 26, 2021 |
| Dell          | Studio 1747                 | [b0a51ac0af](https://bsd-hardware.info/?probe=b0a51ac0af) | Nov 11, 2021 |
| Dell          | Studio 1747                 | [7ab6b58d69](https://bsd-hardware.info/?probe=7ab6b58d69) | Nov 11, 2021 |
| Panasonic     | CF-53AAGHYDM                | [721ef0235c](https://bsd-hardware.info/?probe=721ef0235c) | Oct 30, 2021 |
| Matsushita... | CF-48V4KNDQM                | [9e254ab443](https://bsd-hardware.info/?probe=9e254ab443) | Oct 23, 2021 |
| ASUSTek       | 1000HE                      | [1d5e3e5bc3](https://bsd-hardware.info/?probe=1d5e3e5bc3) | Oct 22, 2021 |
| Lenovo        | ThinkPad T430 2347GZU       | [3337c00433](https://bsd-hardware.info/?probe=3337c00433) | Oct 22, 2021 |
| Dell          | Studio 1747                 | [ca939fbe2f](https://bsd-hardware.info/?probe=ca939fbe2f) | Oct 19, 2021 |
| Matsushita... | CF-51RCVDNLM                | [b20953f2f4](https://bsd-hardware.info/?probe=b20953f2f4) | Oct 18, 2021 |
| Panasonic     | CF-52PFPBSFQ                | [bbdfde368b](https://bsd-hardware.info/?probe=bbdfde368b) | Oct 18, 2021 |
| Lenovo        | ThinkPad T410 2537N24       | [1a5bae2227](https://bsd-hardware.info/?probe=1a5bae2227) | Oct 15, 2021 |
| HP            | Notebook                    | [a3c3297cd2](https://bsd-hardware.info/?probe=a3c3297cd2) | Aug 08, 2021 |
| HP            | Notebook                    | [0c316107a4](https://bsd-hardware.info/?probe=0c316107a4) | Aug 08, 2021 |
| Gigabyte      | MMLP3AP-00                  | [168e674b55](https://bsd-hardware.info/?probe=168e674b55) | Jul 03, 2021 |
| Dell          | Inspiron 15-7579            | [4b8b5f7918](https://bsd-hardware.info/?probe=4b8b5f7918) | Jun 19, 2021 |
| LG Electro... | E500-GP01A9                 | [7db1345e97](https://bsd-hardware.info/?probe=7db1345e97) | Jun 17, 2021 |
| LG Electro... | E500-GP01A9                 | [cbade775b6](https://bsd-hardware.info/?probe=cbade775b6) | Jun 17, 2021 |
| LG Electro... | E500-GP01A9                 | [80052d6cdc](https://bsd-hardware.info/?probe=80052d6cdc) | Jun 15, 2021 |
| Dell          | Inspiron 15-3567            | [d239ee4916](https://bsd-hardware.info/?probe=d239ee4916) | Jun 12, 2021 |
| Apple         | PowerBook5,2                | [8cc0aab53c](https://bsd-hardware.info/?probe=8cc0aab53c) | May 31, 2021 |
| Panasonic     | CF-53AAGHYDM                | [ef5e9ec095](https://bsd-hardware.info/?probe=ef5e9ec095) | May 18, 2021 |
| Panasonic     | CF-52PFPBSFQ                | [65f5931910](https://bsd-hardware.info/?probe=65f5931910) | May 18, 2021 |
| Lenovo        | ThinkPad T430 2347GZU       | [1e9f399d73](https://bsd-hardware.info/?probe=1e9f399d73) | May 17, 2021 |
| Lenovo        | ThinkPad T410 2537N24       | [109f3afa21](https://bsd-hardware.info/?probe=109f3afa21) | May 17, 2021 |
| ASUSTek       | 1000HE                      | [f92f43bc54](https://bsd-hardware.info/?probe=f92f43bc54) | May 17, 2021 |
| Matsushita... | CF-51RCVDNLM                | [33bc82e701](https://bsd-hardware.info/?probe=33bc82e701) | May 17, 2021 |
| Matsushita... | CF-48V4KNDQM                | [bf76401b74](https://bsd-hardware.info/?probe=bf76401b74) | May 17, 2021 |
| Dell          | Latitude 3440               | [3c8d21772a](https://bsd-hardware.info/?probe=3c8d21772a) | May 01, 2021 |
| Dell          | Latitude 3440               | [7e85a38390](https://bsd-hardware.info/?probe=7e85a38390) | Apr 04, 2021 |
| ASUSTek       | G75VW                       | [9b84d1e7e6](https://bsd-hardware.info/?probe=9b84d1e7e6) | Mar 24, 2021 |
| ASUSTek       | G75VW                       | [cf4b3e0c6f](https://bsd-hardware.info/?probe=cf4b3e0c6f) | Mar 23, 2021 |
| ASUSTek       | G75VW                       | [4a59793120](https://bsd-hardware.info/?probe=4a59793120) | Mar 23, 2021 |
| Dell          | Inspiron 7370               | [7e2328dda3](https://bsd-hardware.info/?probe=7e2328dda3) | Mar 20, 2021 |
| Apple         | MacBookPro5,5               | [f46146b79e](https://bsd-hardware.info/?probe=f46146b79e) | Mar 11, 2021 |
| Apple         | MacBookPro5,5               | [c1ed4c02b8](https://bsd-hardware.info/?probe=c1ed4c02b8) | Mar 11, 2021 |
| Alienware     | 14                          | [0e0cdf952a](https://bsd-hardware.info/?probe=0e0cdf952a) | Mar 06, 2021 |
| Toshiba       | Satellite U500              | [feae098542](https://bsd-hardware.info/?probe=feae098542) | Feb 20, 2021 |
| Lenovo        | ThinkPad T410 253722U       | [219e9cb1d7](https://bsd-hardware.info/?probe=219e9cb1d7) | Feb 10, 2021 |
| Intel         | H81U                        | [efb1f9d207](https://bsd-hardware.info/?probe=efb1f9d207) | Feb 07, 2021 |
| Alienware     | 14                          | [dd2cc000a7](https://bsd-hardware.info/?probe=dd2cc000a7) | Jan 07, 2021 |
| Alienware     | 14                          | [48f61623f2](https://bsd-hardware.info/?probe=48f61623f2) | Jan 07, 2021 |
| HP            | EliteBook 840 G3            | [11011ecee1](https://bsd-hardware.info/?probe=11011ecee1) | Jan 02, 2021 |
| Lenovo        | ThinkPad T440 20B7S0A800    | [d3474f1ca3](https://bsd-hardware.info/?probe=d3474f1ca3) | Nov 18, 2020 |
| Lenovo        | ThinkPad T490 20N3S8PB00    | [6a0f910601](https://bsd-hardware.info/?probe=6a0f910601) | Nov 10, 2020 |
| Lenovo        | ThinkPad T490 20N3S8PB00    | [6dca4cdd18](https://bsd-hardware.info/?probe=6dca4cdd18) | Nov 10, 2020 |
| Lenovo        | ThinkPad T430 2347GZU       | [f287de215c](https://bsd-hardware.info/?probe=f287de215c) | Oct 20, 2020 |
| Lenovo        | ThinkPad T410 2537N24       | [f846609c80](https://bsd-hardware.info/?probe=f846609c80) | Oct 20, 2020 |
| Panasonic     | CF-52PFPBSFQ                | [feb1da0406](https://bsd-hardware.info/?probe=feb1da0406) | Oct 20, 2020 |
| Matsushita... | CF-51RCVDNLM                | [efece2abf7](https://bsd-hardware.info/?probe=efece2abf7) | Oct 20, 2020 |
| ASUSTek       | 1000HE                      | [621df26e0c](https://bsd-hardware.info/?probe=621df26e0c) | Oct 19, 2020 |
| Lenovo        | ThinkPad T460 20FMS1BC01    | [bf6d6d155b](https://bsd-hardware.info/?probe=bf6d6d155b) | Oct 19, 2020 |
| Lenovo        | ThinkPad E495 20NE0001US    | [a1fc75a9b7](https://bsd-hardware.info/?probe=a1fc75a9b7) | Oct 09, 2020 |
| HP            | Pavilion dv6500             | [316ffb0740](https://bsd-hardware.info/?probe=316ffb0740) | Sep 04, 2020 |
| Acer          | AOD270                      | [41d2974f13](https://bsd-hardware.info/?probe=41d2974f13) | Aug 20, 2020 |
| HP            | Compaq Mini 110c-1100       | [515042ff2d](https://bsd-hardware.info/?probe=515042ff2d) | Aug 20, 2020 |
| Lenovo        | ThinkPad T510 4313CTO       | [7f6095b266](https://bsd-hardware.info/?probe=7f6095b266) | Aug 20, 2020 |
| HP            | EliteBook 840 G3            | [e568f0f32e](https://bsd-hardware.info/?probe=e568f0f32e) | Aug 04, 2020 |
| ASUSTek       | K52JK                       | [d5d32f1334](https://bsd-hardware.info/?probe=d5d32f1334) | Jun 29, 2020 |
| Lenovo        | ThinkPad T420 4180B39       | [05ed5eb1e4](https://bsd-hardware.info/?probe=05ed5eb1e4) | May 25, 2020 |
| Lenovo        | ThinkPad X270 20HNCTO1WW    | [7def094afb](https://bsd-hardware.info/?probe=7def094afb) | May 23, 2020 |
| ASUSTek       | K52JK                       | [6a6b06fc67](https://bsd-hardware.info/?probe=6a6b06fc67) | May 23, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| OpenBSD 7.4          | 16        | 7.88%   |
| OpenBSD 7.2          | 15        | 7.39%   |
| OpenBSD 7.5          | 14        | 6.9%    |
| OpenBSD 7.3          | 14        | 6.9%    |
| OpenBSD 7.6          | 11        | 5.42%   |
| OpenBSD 7.1          | 10        | 4.93%   |
| OpenBSD 7.0          | 9         | 4.43%   |
| OpenBSD 6.9          | 9         | 4.43%   |
| OpenBSD 6.8          | 7         | 3.45%   |
| helloSystem 0.8.1    | 6         | 2.96%   |
| helloSystem 0.4.0    | 4         | 1.97%   |
| helloSystem 0.8.0    | 3         | 1.48%   |
| helloSystem 0.7.0    | 3         | 1.48%   |
| FreeBSD 13.1-p7      | 3         | 1.48%   |
| FreeBSD 13.1-p5      | 3         | 1.48%   |
| FreeBSD 13.0-p5      | 3         | 1.48%   |
| OPNsense 23.7.3      | 2         | 0.99%   |
| helloSystem 0.5.0    | 2         | 0.99%   |
| GhostBSD 23.10.1     | 2         | 0.99%   |
| FreeBSD 14.2         | 2         | 0.99%   |
| FreeBSD 14.1-p2      | 2         | 0.99%   |
| FreeBSD 14.1         | 2         | 0.99%   |
| FreeBSD 14.0-p6      | 2         | 0.99%   |
| FreeBSD 14.0-CURRENT | 2         | 0.99%   |
| FreeBSD 13.1-p2      | 2         | 0.99%   |
| FreeBSD 13.1         | 2         | 0.99%   |
| FreeBSD 13.0         | 2         | 0.99%   |
| FreeBSD 12.2         | 2         | 0.99%   |
| OPNsense 24.7.5      | 1         | 0.49%   |
| OPNsense 24.1.7      | 1         | 0.49%   |
| OPNsense 24.1.6      | 1         | 0.49%   |
| OPNsense 24.1.1      | 1         | 0.49%   |
| OPNsense 23.7.1      | 1         | 0.49%   |
| OPNsense 23.4        | 1         | 0.49%   |
| OPNsense 23.1.3      | 1         | 0.49%   |
| OPNsense 23.1        | 1         | 0.49%   |
| OPNsense 22.7.6      | 1         | 0.49%   |
| OPNsense 22.7.5      | 1         | 0.49%   |
| OPNsense 22.7.4      | 1         | 0.49%   |
| OPNsense 22.7        | 1         | 0.49%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| FreeBSD     | 41        | 36.94%  |
| OpenBSD     | 25        | 22.52%  |
| helloSystem | 20        | 18.02%  |
| OPNsense    | 14        | 12.61%  |
| GhostBSD    | 8         | 7.21%   |
| NetBSD      | 2         | 1.8%    |
| NomadBSD    | 1         | 0.9%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| amd64  | 105       | 95.45%  |
| i386   | 4         | 3.64%   |
| macppc | 1         | 0.91%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 38        | 31.4%   |
| Console      | 23        | 19.01%  |
| XFCE         | 20        | 16.53%  |
| fvwm         | 12        | 9.92%   |
| MATE         | 6         | 4.96%   |
| TWM          | 4         | 3.31%   |
| KDE5         | 4         | 3.31%   |
| GNOME        | 4         | 3.31%   |
| i3           | 3         | 2.48%   |
| Openbox      | 2         | 1.65%   |
| Ratpoison    | 1         | 0.83%   |
| LXQt         | 1         | 0.83%   |
| Lumina       | 1         | 0.83%   |
| Fluxbox      | 1         | 0.83%   |
| Cinnamon     | 1         | 0.83%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 89        | 79.46%  |
| Console | 22        | 19.64%  |
| Wayland | 1         | 0.89%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Console | 59        | 52.68%  |
| SLiM    | 21        | 18.75%  |
| LightDM | 13        | 11.61%  |
| XDM     | 10        | 8.93%   |
| SDDM    | 6         | 5.36%   |
| GDM     | 3         | 2.68%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 52        | 46.02%  |
| en_US   | 25        | 22.12%  |
| C       | 24        | 21.24%  |
| en_CA   | 5         | 4.42%   |
| fr_FR   | 4         | 3.54%   |
| fr_CA   | 1         | 0.88%   |
| en_NL   | 1         | 0.88%   |
| en      | 1         | 0.88%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 82        | 73.21%  |
| BIOS | 30        | 26.79%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Zfs    | 54        | 48.21%  |
| Ufs    | 26        | 23.21%  |
| Ffs    | 25        | 22.32%  |
| Cd9660 | 7         | 6.25%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 92        | 83.64%  |
| MBR     | 16        | 14.55%  |
| Unknown | 2         | 1.82%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 36        | 32.73%  |
| Dell                           | 14        | 12.73%  |
| ASUSTek Computer               | 9         | 8.18%   |
| Hewlett-Packard                | 7         | 6.36%   |
| Acer                           | 6         | 5.45%   |
| Apple                          | 5         | 4.55%   |
| Toshiba                        | 4         | 3.64%   |
| Intel                          | 4         | 3.64%   |
| Panasonic                      | 3         | 2.73%   |
| Unknown                        | 3         | 2.73%   |
| Matsushita Electric Industrial | 2         | 1.82%   |
| Google                         | 2         | 1.82%   |
| Gigabyte Technology            | 2         | 1.82%   |
| Deciso                         | 2         | 1.82%   |
| Alienware                      | 2         | 1.82%   |
| Star Labs                      | 1         | 0.91%   |
| Shuttle                        | 1         | 0.91%   |
| MSI                            | 1         | 0.91%   |
| LG Electronics                 | 1         | 0.91%   |
| Gateway                        | 1         | 0.91%   |
| Fujitsu                        | 1         | 0.91%   |
| Framework                      | 1         | 0.91%   |
| eMachines                      | 1         | 0.91%   |
| Datto                          | 1         | 0.91%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Unknown                                     | 4         | 3.64%   |
| Intel H81U                                  | 3         | 2.73%   |
| Deciso NetBoard-A20                         | 2         | 1.82%   |
| Toshiba TECRA Z40-B                         | 1         | 0.91%   |
| Toshiba Satellite U500                      | 1         | 0.91%   |
| Toshiba Satellite S50D-A                    | 1         | 0.91%   |
| Toshiba Satellite Pro T130                  | 1         | 0.91%   |
| Star Labs Lite                              | 1         | 0.91%   |
| Shuttle DS67U                               | 1         | 0.91%   |
| Panasonic CF-54-1                           | 1         | 0.91%   |
| Panasonic CF-53AAGHYDM                      | 1         | 0.91%   |
| Panasonic CF-52PFPBSFQ                      | 1         | 0.91%   |
| MSI GL65 Leopard 10SFSK                     | 1         | 0.91%   |
| Matsushita Electric Industrial CF-51RCVDNLM | 1         | 0.91%   |
| Matsushita Electric Industrial CF-48V4KNDQM | 1         | 0.91%   |
| LG E500-GP01A9                              | 1         | 0.91%   |
| Lenovo ThinkPad X280 20KF001UUS             | 1         | 0.91%   |
| Lenovo ThinkPad X270 W10DG 20K5S0TT1N       | 1         | 0.91%   |
| Lenovo ThinkPad X270 W10DG 20K5S0PY04       | 1         | 0.91%   |
| Lenovo ThinkPad X270 20HNCTO1WW             | 1         | 0.91%   |
| Lenovo ThinkPad X260 20F5S2GM00             | 1         | 0.91%   |
| Lenovo ThinkPad X250 20CL001GUS             | 1         | 0.91%   |
| Lenovo ThinkPad X240 20AMS3FY00             | 1         | 0.91%   |
| Lenovo ThinkPad X230 Tablet 34372VU         | 1         | 0.91%   |
| Lenovo ThinkPad X230 2325T4T                | 1         | 0.91%   |
| Lenovo ThinkPad X220 429043U                | 1         | 0.91%   |
| Lenovo ThinkPad X1 Carbon 6th 20KGS1TW00    | 1         | 0.91%   |
| Lenovo ThinkPad X1 Carbon 4th 20FCS13H00    | 1         | 0.91%   |
| Lenovo ThinkPad X1 Carbon 2nd 20A8S0ET00    | 1         | 0.91%   |
| Lenovo ThinkPad T510 4313CTO                | 1         | 0.91%   |
| Lenovo ThinkPad T490 20N3S8PB00             | 1         | 0.91%   |
| Lenovo ThinkPad T470 W10DG 20JNS0L300       | 1         | 0.91%   |
| Lenovo ThinkPad T470 20HES0HU00             | 1         | 0.91%   |
| Lenovo ThinkPad T460 20FMS1BC01             | 1         | 0.91%   |
| Lenovo ThinkPad T460 20FMS10N00             | 1         | 0.91%   |
| Lenovo ThinkPad T440 20B7S0A800             | 1         | 0.91%   |
| Lenovo ThinkPad T430 2347GZU                | 1         | 0.91%   |
| Lenovo ThinkPad T420s 41742BU               | 1         | 0.91%   |
| Lenovo ThinkPad T420 4180B39                | 1         | 0.91%   |
| Lenovo ThinkPad T410 2537N24                | 1         | 0.91%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Lenovo ThinkPad                             | 31        | 28.18%  |
| Dell Latitude                               | 6         | 5.45%   |
| Dell Inspiron                               | 4         | 3.64%   |
| Unknown                                     | 4         | 3.64%   |
| Toshiba Satellite                           | 3         | 2.73%   |
| Intel H81U                                  | 3         | 2.73%   |
| Acer Aspire                                 | 3         | 2.73%   |
| Lenovo IdeaPad                              | 2         | 1.82%   |
| HP Pavilion                                 | 2         | 1.82%   |
| Dell XPS                                    | 2         | 1.82%   |
| Dell Studio                                 | 2         | 1.82%   |
| Deciso NetBoard-A20                         | 2         | 1.82%   |
| ASUS VivoBook                               | 2         | 1.82%   |
| Acer Swift                                  | 2         | 1.82%   |
| Toshiba TECRA                               | 1         | 0.91%   |
| Star Labs Lite                              | 1         | 0.91%   |
| Shuttle DS67U                               | 1         | 0.91%   |
| Panasonic CF-54-1                           | 1         | 0.91%   |
| Panasonic CF-53AAGHYDM                      | 1         | 0.91%   |
| Panasonic CF-52PFPBSFQ                      | 1         | 0.91%   |
| MSI GL65                                    | 1         | 0.91%   |
| Matsushita Electric Industrial CF-51RCVDNLM | 1         | 0.91%   |
| Matsushita Electric Industrial CF-48V4KNDQM | 1         | 0.91%   |
| LG E500-GP01A9                              | 1         | 0.91%   |
| Lenovo ThinkBook                            | 1         | 0.91%   |
| Lenovo Legion                               | 1         | 0.91%   |
| Lenovo G560                                 | 1         | 0.91%   |
| Intel SandyBridge                           | 1         | 0.91%   |
| HP ProBook                                  | 1         | 0.91%   |
| HP Notebook                                 | 1         | 0.91%   |
| HP EliteBook                                | 1         | 0.91%   |
| HP Compaq                                   | 1         | 0.91%   |
| HP 2000                                     | 1         | 0.91%   |
| Google Terra                                | 1         | 0.91%   |
| Google Peppy                                | 1         | 0.91%   |
| Gigabyte MMLP3AP-00                         | 1         | 0.91%   |
| Gigabyte GB-BSi3A-6100                      | 1         | 0.91%   |
| Gateway ID49C                               | 1         | 0.91%   |
| Fujitsu LIFEBOOK                            | 1         | 0.91%   |
| Framework Laptop                            | 1         | 0.91%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 10        | 9.09%   |
| 2010    | 10        | 9.09%   |
| 2011    | 9         | 8.18%   |
| 2021    | 8         | 7.27%   |
| 2022    | 7         | 6.36%   |
| 2018    | 7         | 6.36%   |
| 2016    | 7         | 6.36%   |
| 2014    | 7         | 6.36%   |
| 2009    | 7         | 6.36%   |
| 2023    | 6         | 5.45%   |
| 2017    | 6         | 5.45%   |
| 2015    | 6         | 5.45%   |
| 2020    | 5         | 4.55%   |
| 2012    | 5         | 4.55%   |
| 2013    | 4         | 3.64%   |
| 2008    | 2         | 1.82%   |
| 2024    | 1         | 0.91%   |
| 2006    | 1         | 0.91%   |
| 2002    | 1         | 0.91%   |
| Unknown | 1         | 0.91%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 110       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 107       | 97.27%  |
| Yes  | 3         | 2.73%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 8.01-16.0  | 42        | 37.84%  |
| 4.01-8.0   | 22        | 19.82%  |
| 16.01-24.0 | 22        | 19.82%  |
| 32.01-64.0 | 9         | 8.11%   |
| 2.01-3.0   | 7         | 6.31%   |
| 3.01-4.0   | 6         | 5.41%   |
| 24.01-32.0 | 1         | 0.9%    |
| 1.01-2.0   | 1         | 0.9%    |
| 0.51-1.0   | 1         | 0.9%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 67        | 59.82%  |
| 0.51-1.0 | 29        | 25.89%  |
| 1.01-2.0 | 9         | 8.04%   |
| 2.01-3.0 | 2         | 1.79%   |
| 0        | 2         | 1.79%   |
| Unknown  | 2         | 1.79%   |
| 3.01-4.0 | 1         | 0.89%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 84        | 75%     |
| 0      | 16        | 14.29%  |
| 2      | 10        | 8.93%   |
| 58     | 1         | 0.89%   |
| 3      | 1         | 0.89%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 90        | 80.36%  |
| Yes       | 22        | 19.64%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 94        | 85.45%  |
| No        | 16        | 14.55%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 99        | 90%     |
| No        | 11        | 10%     |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 73        | 65.77%  |
| No        | 38        | 34.23%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Canada  | 110       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Montreal          | 27        | 19.42%  |
| Saint-Laurent     | 16        | 11.51%  |
| Vancouver         | 7         | 5.04%   |
| Toronto           | 7         | 5.04%   |
| Calgary           | 7         | 5.04%   |
| Ottawa            | 6         | 4.32%   |
| Victoria          | 5         | 3.6%    |
| QuГ©bec         | 5         | 3.6%    |
| Winnipeg          | 3         | 2.16%   |
| Stratford         | 3         | 2.16%   |
| Kingsburg         | 3         | 2.16%   |
| Sydenham          | 2         | 1.44%   |
| Sainte-Julie      | 2         | 1.44%   |
| Saint-Bruno       | 2         | 1.44%   |
| Québec           | 2         | 1.44%   |
| Peterborough      | 2         | 1.44%   |
| Mississauga       | 2         | 1.44%   |
| Langley           | 2         | 1.44%   |
| Gatineau          | 2         | 1.44%   |
| Whitby            | 1         | 0.72%   |
| Warwick           | 1         | 0.72%   |
| Vaudreuil-Dorion  | 1         | 0.72%   |
| Surrey            | 1         | 0.72%   |
| St. Jean Baptiste | 1         | 0.72%   |
| Sechelt           | 1         | 0.72%   |
| Scarborough       | 1         | 0.72%   |
| Saskatoon         | 1         | 0.72%   |
| Saint-Zotique     | 1         | 0.72%   |
| Prince Albert     | 1         | 0.72%   |
| Powell River      | 1         | 0.72%   |
| Pierrefonds       | 1         | 0.72%   |
| North York        | 1         | 0.72%   |
| North Vancouver   | 1         | 0.72%   |
| Niagara Falls     | 1         | 0.72%   |
| Nepean            | 1         | 0.72%   |
| Mission           | 1         | 0.72%   |
| Maple Ridge       | 1         | 0.72%   |
| Longueuil         | 1         | 0.72%   |
| Lloydminster      | 1         | 0.72%   |
| Laval             | 1         | 0.72%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 20        | 70     | 18.35%  |
| Samsung Electronics | 10        | 20     | 9.17%   |
| Kingston            | 10        | 16     | 9.17%   |
| Toshiba             | 9         | 19     | 8.26%   |
| Seagate             | 9         | 16     | 8.26%   |
| Hitachi             | 7         | 11     | 6.42%   |
| NVMe                | 5         | 8      | 4.59%   |
| Intel               | 5         | 12     | 4.59%   |
| Transcend           | 3         | 3      | 2.75%   |
| SanDisk             | 3         | 5      | 2.75%   |
| Crucial             | 3         | 3      | 2.75%   |
| A-DATA Technology   | 3         | 10     | 2.75%   |
| SK hynix            | 2         | 2      | 1.83%   |
| Micron Technology   | 2         | 2      | 1.83%   |
| Lexar               | 2         | 3      | 1.83%   |
| UMIS                | 1         | 1      | 0.92%   |
| Team                | 1         | 1      | 0.92%   |
| Star Drive          | 1         | 1      | 0.92%   |
| Phison              | 1         | 1      | 0.92%   |
| OCZ                 | 1         | 1      | 0.92%   |
| LITEON              | 1         | 3      | 0.92%   |
| Kston               | 1         | 2      | 0.92%   |
| KIOXIA              | 1         | 1      | 0.92%   |
| KingDian            | 1         | 1      | 0.92%   |
| HPE                 | 1         | 5      | 0.92%   |
| HGST                | 1         | 34     | 0.92%   |
| Hewlett-Packard     | 1         | 1      | 0.92%   |
| Fujitsu             | 1         | 1      | 0.92%   |
| Fanxiang            | 1         | 1      | 0.92%   |
| Apple               | 1         | 1      | 0.92%   |
| Apacer              | 1         | 1      | 0.92%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB          | 3         | 2.65%   |
| WDC WDS500G2B0A-00SM50 500GB         | 2         | 1.77%   |
| Seagate ST9500420AS 500GB            | 2         | 1.77%   |
| NVMe SAMSUNG MZVLW256 256GB          | 2         | 1.77%   |
| Kingston SHFS37A120G 120GB           | 2         | 1.77%   |
| WDC WDS500G2B0A 500GB                | 1         | 0.88%   |
| WDC WDS200T2B0A 2TB                  | 1         | 0.88%   |
| WDC WDBNCE0010PNC 1TB                | 1         | 0.88%   |
| WDC WD7500BPKX-75HPJT0 752GB         | 1         | 0.88%   |
| WDC WD7500BPKX-00HPJT0 752GB         | 1         | 0.88%   |
| WDC WD7500BPKT-75PK4T0 752GB         | 1         | 0.88%   |
| WDC WD7500BPKT-00PK4T0 752GB         | 1         | 0.88%   |
| WDC WD6400BEVT-22A0RT0 640GB         | 1         | 0.88%   |
| WDC WD5000LPLX-00ZNTT0 500GB         | 1         | 0.88%   |
| WDC WD3200LPVX-60V0TT0 320GB         | 1         | 0.88%   |
| WDC WD3200BEVE-00A0HT0 320GB         | 1         | 0.88%   |
| WDC WD2500BEVS-75UST0 250GB          | 1         | 0.88%   |
| WDC WD20SDRW-11VUUS1 2TB             | 1         | 0.88%   |
| WDC WD10JPVX-75JC3T0 1TB             | 1         | 0.88%   |
| WDC WD10JPVT-00A1YT0 1TB             | 1         | 0.88%   |
| WDC WD10JPLX-00MBPT0 1TB             | 1         | 0.88%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB | 1         | 0.88%   |
| WDC PC SN730 SDBQNTY-1T00-1001 1TB   | 1         | 0.88%   |
| WDC PC SN530 SDBPNPZ-256G-1014 256GB | 1         | 0.88%   |
| WDC PC SN530 NVMe 256GB              | 1         | 0.88%   |
| UMIS RPETJ1T24MGE2QDQ 1TB            | 1         | 0.88%   |
| Transcend TSA 240GB                  | 1         | 0.88%   |
| Transcend TS256GMTS952T2 256GB       | 1         | 0.88%   |
| Transcend TS256GMTE710T 256GB        | 1         | 0.88%   |
| Toshiba THNSNJ128GCSU 128GB          | 1         | 0.88%   |
| Toshiba MQ04ABF100 1TB               | 1         | 0.88%   |
| Toshiba MQ01ABF032 320GB             | 1         | 0.88%   |
| Toshiba MK8025GAS 80GB               | 1         | 0.88%   |
| Toshiba MK5061GSYN 500GB             | 1         | 0.88%   |
| Toshiba MK3259GSXP 320GB             | 1         | 0.88%   |
| Toshiba MK1665GSX 160GB              | 1         | 0.88%   |
| Toshiba KXG6AZNV256G 256GB           | 1         | 0.88%   |
| Toshiba HDWQ140 4TB                  | 1         | 0.88%   |
| Team T253X1240G 240GB                | 1         | 0.88%   |
| Star Drive SATA SSD 240GB            | 1         | 0.88%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 13        | 61     | 28.89%  |
| Seagate | 9         | 16     | 20%     |
| Toshiba | 7         | 17     | 15.56%  |
| Hitachi | 7         | 11     | 15.56%  |
| NVMe    | 5         | 8      | 11.11%  |
| Lexar   | 1         | 1      | 2.22%   |
| HPE     | 1         | 5      | 2.22%   |
| HGST    | 1         | 34     | 2.22%   |
| Fujitsu | 1         | 1      | 2.22%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 10        | 15     | 20%     |
| Samsung Electronics | 7         | 17     | 14%     |
| WDC                 | 5         | 5      | 10%     |
| Intel               | 4         | 11     | 8%      |
| SanDisk             | 3         | 5      | 6%      |
| Transcend           | 2         | 2      | 4%      |
| SK hynix            | 2         | 2      | 4%      |
| Crucial             | 2         | 2      | 4%      |
| A-DATA Technology   | 2         | 9      | 4%      |
| Toshiba             | 1         | 1      | 2%      |
| Team                | 1         | 1      | 2%      |
| Star Drive          | 1         | 1      | 2%      |
| OCZ                 | 1         | 1      | 2%      |
| Micron Technology   | 1         | 1      | 2%      |
| LITEON              | 1         | 3      | 2%      |
| Lexar               | 1         | 2      | 2%      |
| Kston               | 1         | 2      | 2%      |
| KingDian            | 1         | 1      | 2%      |
| Hewlett-Packard     | 1         | 1      | 2%      |
| Fanxiang            | 1         | 1      | 2%      |
| Apple               | 1         | 1      | 2%      |
| Apacer              | 1         | 1      | 2%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 46        | 85     | 45.1%   |
| HDD  | 42        | 154    | 41.18%  |
| NVMe | 14        | 17     | 13.73%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 85        | 239    | 85.86%  |
| NVMe | 14        | 17     | 14.14%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 67        | 135    | 76.14%  |
| 0.51-1.0   | 15        | 51     | 17.05%  |
| 1.01-2.0   | 5         | 5      | 5.68%   |
| 3.01-4.0   | 1         | 48     | 1.14%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 34        | 28.81%  |
| 21-50      | 22        | 18.64%  |
| 1-20       | 18        | 15.25%  |
| 251-500    | 17        | 14.41%  |
| 51-100     | 15        | 12.71%  |
| 501-1000   | 9         | 7.63%   |
| 1001-2000  | 2         | 1.69%   |
| Unknown    | 1         | 0.85%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 94        | 83.93%  |
| 21-50   | 10        | 8.93%   |
| 51-100  | 5         | 4.46%   |
| 251-500 | 1         | 0.89%   |
| 101-250 | 1         | 0.89%   |
| Unknown | 1         | 0.89%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                             | Notebooks | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST9500420AS 500GB         | 2         | 3      | 12.5%   |
| WDC WDS200T2B0A 2TB               | 1         | 1      | 6.25%   |
| WDC WD6400BEVT-22A0RT0 640GB      | 1         | 1      | 6.25%   |
| Toshiba MK1665GSX 160GB           | 1         | 1      | 6.25%   |
| SK hynix HFS256G39TND-N210A 256GB | 1         | 1      | 6.25%   |
| Seagate ST9500325AS 500GB         | 1         | 1      | 6.25%   |
| Kingston SV300S37A60G 64GB        | 1         | 2      | 6.25%   |
| Kingston SUV400S37240G 240GB      | 1         | 1      | 6.25%   |
| Kingston SNS4151S316GD 16GB       | 1         | 1      | 6.25%   |
| Kingston SNS4151S316G 16GB        | 1         | 1      | 6.25%   |
| Intel SSDSC2CW120A3 120GB         | 1         | 1      | 6.25%   |
| Hitachi HTS547575A9E384 752GB     | 1         | 1      | 6.25%   |
| Hitachi HTS541612J9SA00 120GB     | 1         | 1      | 6.25%   |
| Apacer 16GB SATA Flash Drive      | 1         | 1      | 6.25%   |
| A-DATA Technology SP550 480GB     | 1         | 8      | 6.25%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Kingston          | 4         | 5      | 25%     |
| Seagate           | 3         | 4      | 18.75%  |
| WDC               | 2         | 2      | 12.5%   |
| Hitachi           | 2         | 2      | 12.5%   |
| Toshiba           | 1         | 1      | 6.25%   |
| SK hynix          | 1         | 1      | 6.25%   |
| Intel             | 1         | 1      | 6.25%   |
| Apacer            | 1         | 1      | 6.25%   |
| A-DATA Technology | 1         | 8      | 6.25%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 4      | 42.86%  |
| Hitachi | 2         | 2      | 28.57%  |
| WDC     | 1         | 1      | 14.29%  |
| Toshiba | 1         | 1      | 14.29%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 9         | 17     | 56.25%  |
| HDD  | 7         | 8      | 43.75%  |

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


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 78        | 220    | 76.47%  |
| Malfunc  | 16        | 25     | 15.69%  |
| Detected | 8         | 11     | 7.84%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 83        | 68.03%  |
| SanDisk                                 | 8         | 6.56%   |
| Samsung Electronics                     | 7         | 5.74%   |
| AMD                                     | 6         | 4.92%   |
| Kingston Technology Company             | 3         | 2.46%   |
| Toshiba                                 | 2         | 1.64%   |
| Realtek Semiconductor                   | 2         | 1.64%   |
| Nvidia                                  | 2         | 1.64%   |
| Transcend                               | 1         | 0.82%   |
| Solid State Storage Technology          | 1         | 0.82%   |
| Shenzhen Unionmemory Information System | 1         | 0.82%   |
| Phison Electronics                      | 1         | 0.82%   |
| Micron/Crucial Technology               | 1         | 0.82%   |
| Micron Technology                       | 1         | 0.82%   |
| MAXIO Technology (Hangzhou)             | 1         | 0.82%   |
| KIOXIA                                  | 1         | 0.82%   |
| Broadcom / LSI                          | 1         | 0.82%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 16        | 12.7%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 8         | 6.35%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                           | 7         | 5.56%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 7         | 5.56%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 7         | 5.56%   |
| AMD FCH SATA Controller [AHCI mode]                                          | 6         | 4.76%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]        | 5         | 3.97%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller               | 5         | 3.97%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                | 4         | 3.17%   |
| Sandisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD      | 3         | 2.38%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD         | 3         | 2.38%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                | 3         | 2.38%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller               | 3         | 2.38%   |
| Toshiba XG6 NVMe SSD Controller                                              | 2         | 1.59%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                | 2         | 1.59%   |
| Kingston Company A2000 NVMe SSD [SM2263EN]                                   | 2         | 1.59%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                           | 2         | 1.59%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                            | 2         | 1.59%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                             | 2         | 1.59%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                | 2         | 1.59%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                               | 2         | 1.59%   |
| Transcend NVMe PCIe SSD 220S/240S/MTE710T                                    | 1         | 0.79%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                               | 1         | 0.79%   |
| Shenzhen Unionmemory Information System AM630 PCIe 4.0 NVMe SSD 1024GB       | 1         | 0.79%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)    | 1         | 0.79%   |
| SanDisk IX SN530 NVMe SSD (DRAM-less)                                        | 1         | 0.79%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                  | 1         | 0.79%   |
| Realtek RTS5765DL NVMe SSD Controller (DRAM-less)                            | 1         | 0.79%   |
| Realtek RTS5763DL NVMe SSD Controller (DRAM-less)                            | 1         | 0.79%   |
| Phison E12 NVMe Controller                                                   | 1         | 0.79%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                     | 1         | 0.79%   |
| Nvidia MCP79 AHCI Controller                                                 | 1         | 0.79%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)         | 1         | 0.79%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                  | 1         | 0.79%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                     | 1         | 0.79%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                   | 1         | 0.79%   |
| Kingston Company NV2 NVMe SSD [SM2267XT] (DRAM-less)                         | 1         | 0.79%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation        | 1         | 0.79%   |
| Intel Tiger Lake-LP SATA Controller                                          | 1         | 0.79%   |
| Intel Tiger Lake SATA AHCI Controller                                        | 1         | 0.79%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 82        | 68.33%  |
| NVMe | 27        | 22.5%   |
| IDE  | 7         | 5.83%   |
| RAID | 3         | 2.5%    |
| SAS  | 1         | 0.83%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 100       | 90.91%  |
| AMD     | 9         | 8.18%   |
| Unknown | 1         | 0.91%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Core i5-6300U CPU @ 2.40GHz                             | 7         | 6.19%   |
| Intel Core i5-2520M CPU @ 2.50GHz                             | 4         | 3.54%   |
| Intel Core i5-3320M CPU @ 2.60GHz                             | 3         | 2.65%   |
| Intel Core i5 CPU M 520 @ 2.40GHz                             | 3         | 2.65%   |
| Intel Celeron CPU 1037U @ 1.80GHz                             | 3         | 2.65%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz                   | 2         | 1.77%   |
| Intel CPU Version                                             | 2         | 1.77%   |
| Intel Core i7-4600U CPU @ 2.10GHz                             | 2         | 1.77%   |
| Intel Core i7-3630QM CPU @ 2.40GHz                            | 2         | 1.77%   |
| Intel Core i5-7200U CPU @ 2.50GHz                             | 2         | 1.77%   |
| Intel Core i5-5300U CPU @ 2.30GHz                             | 2         | 1.77%   |
| Intel Core i5-4210U CPU @ 1.70GHz                             | 2         | 1.77%   |
| Intel Core i3-7100U CPU @ 2.40GHz                             | 2         | 1.77%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz                       | 2         | 1.77%   |
| AMD EPYC 3201 8-Core Processor                                | 2         | 1.77%   |
| Intel Xeon CPU E3-1505M v5 @ 2.80GHz                          | 1         | 0.88%   |
| Intel Xeon CPU E3-1230 V2 @ 3.30GH                            | 1         | 0.88%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz                   | 1         | 0.88%   |
| Intel Pentium CPU P6100 @ 2.00GHz                             | 1         | 0.88%   |
| Intel Pentium CPU N4200 @ 1.10GHz                             | 1         | 0.88%   |
| Intel Pentium CPU N3710 @ 1.60GHz                             | 1         | 0.88%   |
| Intel Pentium 4 Mobile CPU 1.60GHz ("GenuineIntel" 686-class) | 1         | 0.88%   |
| Intel Pentium 4 Mobile CPU 1.60GHz                            | 1         | 0.88%   |
| Intel Genuine CPU T2300 @ 1.66GHz                             | 1         | 0.88%   |
| Intel CPU T2300 @ 1.66GHz ("GenuineIntel" 686-class)          | 1         | 0.88%   |
| Intel Core i7-9750H CPU @ 2.60GHz                             | 1         | 0.88%   |
| Intel Core i7-8750H CPU @ 2.20GHz                             | 1         | 0.88%   |
| Intel Core i7-8650U CPU @ 1.90GHz                             | 1         | 0.88%   |
| Intel Core i7-8550U CPU @ 1.80GHz                             | 1         | 0.88%   |
| Intel Core i7-7600U CPU @ 2.80GHz                             | 1         | 0.88%   |
| Intel Core i7-6600U CPU @ 2.60GHz                             | 1         | 0.88%   |
| Intel Core i7-5500U CPU @ 2.40GHz                             | 1         | 0.88%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz                            | 1         | 0.88%   |
| Intel Core i7-3520M CPU @ 2.90GHz                             | 1         | 0.88%   |
| Intel Core i7-2677M CPU @ 1.80GHz                             | 1         | 0.88%   |
| Intel Core i7-10750H CPU @ 2.60GHz                            | 1         | 0.88%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz                            | 1         | 0.88%   |
| Intel Core i5-8365U CPU @ 1.60GHz                             | 1         | 0.88%   |
| Intel Core i5-8350U CPU @ 1.70GHz                             | 1         | 0.88%   |
| Intel Core i5-8265U CPU @ 1.60GHz                             | 1         | 0.88%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 36        | 32.43%  |
| Intel Core i7           | 16        | 14.41%  |
| Other                   | 13        | 11.71%  |
| Intel Core i3           | 9         | 8.11%   |
| Intel Celeron           | 8         | 7.21%   |
| Intel Core 2 Duo        | 6         | 5.41%   |
| Intel Atom              | 4         | 3.6%    |
| Intel Pentium Dual-Core | 3         | 2.7%    |
| Intel Pentium           | 3         | 2.7%    |
| Intel Xeon              | 2         | 1.8%    |
| AMD Ryzen 7             | 2         | 1.8%    |
| AMD Ryzen 5             | 2         | 1.8%    |
| AMD EPYC                | 2         | 1.8%    |
| Intel Pentium 4         | 1         | 0.9%    |
| Intel Genuine           | 1         | 0.9%    |
| AMD Ryzen 9             | 1         | 0.9%    |
| AMD E1                  | 1         | 0.9%    |
| AMD A10                 | 1         | 0.9%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 65        | 59.09%  |
| 4       | 20        | 18.18%  |
| Unknown | 10        | 9.09%   |
| 6       | 5         | 4.55%   |
| 8       | 4         | 3.64%   |
| 16      | 2         | 1.82%   |
| 1       | 2         | 1.82%   |
| 12      | 1         | 0.91%   |
| 10      | 1         | 0.91%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 107       | 94.69%  |
| Unknown | 4         | 3.54%   |
| 2       | 2         | 1.77%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 75        | 68.18%  |
| 1       | 24        | 21.82%  |
| Unknown | 11        | 10%     |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 14        | 12.5%   |
| Skylake       | 12        | 10.71%  |
| IvyBridge     | 10        | 8.93%   |
| Haswell       | 9         | 8.04%   |
| SandyBridge   | 8         | 7.14%   |
| Penryn        | 8         | 7.14%   |
| Unknown       | 8         | 7.14%   |
| Broadwell     | 7         | 6.25%   |
| Westmere      | 6         | 5.36%   |
| TigerLake     | 6         | 5.36%   |
| Bonnell       | 4         | 3.57%   |
| Zen 3         | 2         | 1.79%   |
| Zen 2         | 2         | 1.79%   |
| Zen           | 2         | 1.79%   |
| Silvermont    | 2         | 1.79%   |
| Core          | 2         | 1.79%   |
| Zen+          | 1         | 0.89%   |
| Piledriver    | 1         | 0.89%   |
| P6            | 1         | 0.89%   |
| NetBurst      | 1         | 0.89%   |
| Nehalem       | 1         | 0.89%   |
| Jaguar        | 1         | 0.89%   |
| IceLake       | 1         | 0.89%   |
| Goldmont plus | 1         | 0.89%   |
| Goldmont      | 1         | 0.89%   |
| CometLake     | 1         | 0.89%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor         | Notebooks | Percent |
|----------------|-----------|---------|
| Intel          | 91        | 76.47%  |
| Nvidia         | 16        | 13.45%  |
| AMD            | 11        | 9.24%   |
| Silicon Motion | 1         | 0.84%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Skylake GT2 [HD Graphics 520]                                                      | 10        | 8.06%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 8         | 6.45%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 8         | 6.45%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 8         | 6.45%   |
| Intel HD Graphics 5500                                                                   | 7         | 5.65%   |
| Intel HD Graphics 620                                                                    | 6         | 4.84%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 5         | 4.03%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 4.03%   |
| Intel UHD Graphics 620                                                                   | 4         | 3.23%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 2.42%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 3         | 2.42%   |
| Nvidia GK107M [GeForce GTX 660M]                                                         | 2         | 1.61%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 2         | 1.61%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 1.61%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 2         | 1.61%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 1.61%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 1.61%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 2         | 1.61%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 1.61%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.61%   |
| Silicon Motion SM712 LynxEM+                                                             | 1         | 0.81%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 0.81%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.81%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 1         | 0.81%   |
| Nvidia GT218M [NVS 3100M]                                                                | 1         | 0.81%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 1         | 0.81%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1         | 0.81%   |
| Nvidia GM107GLM [Quadro M600M]                                                           | 1         | 0.81%   |
| Nvidia GK106M [GeForce GTX 765M]                                                         | 1         | 0.81%   |
| Nvidia GF119M [GeForce GT 520M]                                                          | 1         | 0.81%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 0.81%   |
| Nvidia G86M [GeForce 8400M GS]                                                           | 1         | 0.81%   |
| Nvidia C79 [GeForce 9400M]                                                               | 1         | 0.81%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 1         | 0.81%   |
| Intel Tiger Lake-UP4 GT2 [Iris Xe Graphics]                                              | 1         | 0.81%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 1         | 0.81%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 1         | 0.81%   |
| Intel JasperLake [UHD Graphics]                                                          | 1         | 0.81%   |
| Intel Iris Plus Graphics G7                                                              | 1         | 0.81%   |
| Intel HD Graphics P530                                                                   | 1         | 0.81%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 70        | 63.64%  |
| 2 x Intel          | 11        | 10%     |
| Intel + Nvidia     | 9         | 8.18%   |
| 1 x AMD            | 9         | 8.18%   |
| 1 x Nvidia         | 6         | 5.45%   |
| Other              | 2         | 1.82%   |
| 1 x Silicon Motion | 1         | 0.91%   |
| Intel + AMD        | 1         | 0.91%   |
| AMD + Nvidia       | 1         | 0.91%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 102       | 91.89%  |
| Proprietary | 6         | 5.41%   |
| Unknown     | 3         | 2.7%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 100       | 89.29%  |
| 3.01-4.0   | 3         | 2.68%   |
| 1.01-2.0   | 3         | 2.68%   |
| 0.51-1.0   | 3         | 2.68%   |
| 0.01-0.5   | 3         | 2.68%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 13        | 18.06%  |
| BOE                     | 12        | 16.67%  |
| Chimei Innolux          | 10        | 13.89%  |
| AU Optronics            | 10        | 13.89%  |
| Samsung Electronics     | 9         | 12.5%   |
| Sharp                   | 3         | 4.17%   |
| Lenovo                  | 3         | 4.17%   |
| Chi Mei Optoelectronics | 3         | 4.17%   |
| Apple                   | 3         | 4.17%   |
| Goldstar                | 2         | 2.78%   |
| Toshiba                 | 1         | 1.39%   |
| Panasonic               | 1         | 1.39%   |
| Dell                    | 1         | 1.39%   |
| Acer                    | 1         | 1.39%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1280x800 330x210mm 15.4-inch      | 3         | 4.17%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch               | 2         | 2.78%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch               | 2         | 2.78%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 310x170mm 13.9-inch          | 2         | 2.78%   |
| AU Optronics LCD Monitor AUO226D 1920x1080 280x160mm 12.7-inch            | 2         | 2.78%   |
| Toshiba LCD Monitor LCD0905 1366x768 290x170mm 13.2-inch                  | 1         | 1.39%   |
| Sharp LCD Monitor SHP1526 1920x1280 270x180mm 12.8-inch                   | 1         | 1.39%   |
| Sharp LCD Monitor SHP14C2 1920x1080 260x140mm 11.6-inch                   | 1         | 1.39%   |
| Sharp LCD Monitor SHP14BA 1920x1080 340x190mm 15.3-inch                   | 1         | 1.39%   |
| Samsung Electronics SyncMaster SAM03E4 1680x1050 470x300mm 22.0-inch      | 1         | 1.39%   |
| Samsung Electronics LCD Monitor SEC3345 1280x800 330x210mm 15.4-inch      | 1         | 1.39%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch      | 1         | 1.39%   |
| Samsung Electronics LCD Monitor SEC3050 1366x768 320x190mm 14.7-inch      | 1         | 1.39%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 310x170mm 13.9-inch      | 1         | 1.39%   |
| Samsung Electronics LCD Monitor SDC4147 1366x768 340x190mm 15.3-inch      | 1         | 1.39%   |
| Panasonic LCD Monitor MEI96A2 3840x2160 380x210mm 17.1-inch               | 1         | 1.39%   |
| LG Display LCD Monitor LGD05A2 1920x1080 310x170mm 13.9-inch              | 1         | 1.39%   |
| LG Display LCD Monitor LGD04F0 2560x1440 310x170mm 13.9-inch              | 1         | 1.39%   |
| LG Display LCD Monitor LGD0484 1366x768 340x190mm 15.3-inch               | 1         | 1.39%   |
| LG Display LCD Monitor LGD045E 1366x768 310x170mm 13.9-inch               | 1         | 1.39%   |
| LG Display LCD Monitor LGD0456 1366x768 340x190mm 15.3-inch               | 1         | 1.39%   |
| LG Display LCD Monitor LGD02E2 1600x900 310x170mm 13.9-inch               | 1         | 1.39%   |
| LG Display LCD Monitor LGD021D 1600x900 380x210mm 17.1-inch               | 1         | 1.39%   |
| LG Display LCD Monitor LGD0215 1920x1080 350x190mm 15.7-inch              | 1         | 1.39%   |
| LG Display LCD Monitor LGD01E9 1920x1080 350x190mm 15.7-inch              | 1         | 1.39%   |
| Lenovo LCD Monitor LEN40B1 1600x900 350x190mm 15.7-inch                   | 1         | 1.39%   |
| Lenovo LCD Monitor LEN4035 1280x800 300x190mm 14.0-inch                   | 1         | 1.39%   |
| Lenovo LCD Monitor LEN4031 1280x800 300x190mm 14.0-inch                   | 1         | 1.39%   |
| Goldstar LG HDR WFHD GSM7714 2560x1080 800x340mm 34.2-inch                | 1         | 1.39%   |
| Goldstar L1920P GSM4A7B 1280x1024 380x300mm 19.1-inch                     | 1         | 1.39%   |
| Dell P2723DE DELD144 2560x1440 600x340mm 27.2-inch                        | 1         | 1.39%   |
| Chimei Innolux LCD Monitor CMN15F4 1920x1080 340x190mm 15.3-inch          | 1         | 1.39%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 310x170mm 13.9-inch          | 1         | 1.39%   |
| Chimei Innolux LCD Monitor CMN14B7 1366x768 310x170mm 13.9-inch           | 1         | 1.39%   |
| Chimei Innolux LCD Monitor CMN1492 1366x768 310x170mm 13.9-inch           | 1         | 1.39%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 310x170mm 13.9-inch           | 1         | 1.39%   |
| Chimei Innolux LCD Monitor CMN1367 1920x1080 290x170mm 13.2-inch          | 1         | 1.39%   |
| Chimei Innolux LCD Monitor CMN1239 1920x1080 280x160mm 12.7-inch          | 1         | 1.39%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch           | 1         | 1.39%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 380x210mm 17.1-inch | 1         | 1.39%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 28        | 38.89%  |
| 1366x768 (WXGA)    | 24        | 33.33%  |
| 1600x900 (HD+)     | 5         | 6.94%   |
| 1280x800 (WXGA)    | 5         | 6.94%   |
| 2560x1440 (QHD)    | 2         | 2.78%   |
| 2256x1504          | 2         | 2.78%   |
| 3840x2160 (4K)     | 1         | 1.39%   |
| 2560x1080          | 1         | 1.39%   |
| 1920x1280          | 1         | 1.39%   |
| 1680x1050 (WSXGA+) | 1         | 1.39%   |
| 1280x854           | 1         | 1.39%   |
| 1280x1024 (SXGA)   | 1         | 1.39%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 13     | 26        | 36.11%  |
| 15     | 20        | 27.78%  |
| 12     | 11        | 15.28%  |
| 11     | 4         | 5.56%   |
| 17     | 3         | 4.17%   |
| 14     | 3         | 4.17%   |
| 27     | 2         | 2.78%   |
| 34     | 1         | 1.39%   |
| 22     | 1         | 1.39%   |
| 19     | 1         | 1.39%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 39        | 54.17%  |
| 201-300     | 25        | 34.72%  |
| 351-400     | 4         | 5.56%   |
| 501-600     | 2         | 2.78%   |
| 701-800     | 1         | 1.39%   |
| 401-500     | 1         | 1.39%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 55        | 78.57%  |
| 16/10 | 9         | 12.86%  |
| 3/2   | 4         | 5.71%   |
| 5/4   | 1         | 1.43%   |
| 21/9  | 1         | 1.43%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 24        | 33.33%  |
| 91-100         | 12        | 16.67%  |
| 61-70          | 10        | 13.89%  |
| 101-110        | 9         | 12.5%   |
| 71-80          | 5         | 6.94%   |
| 51-60          | 4         | 5.56%   |
| 121-130        | 3         | 4.17%   |
| 301-350        | 2         | 2.78%   |
| 351-500        | 1         | 1.39%   |
| 201-250        | 1         | 1.39%   |
| 151-200        | 1         | 1.39%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 32        | 44.44%  |
| 101-120       | 19        | 26.39%  |
| 161-240       | 11        | 15.28%  |
| 51-100        | 9         | 12.5%   |
| More than 240 | 1         | 1.39%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 80        | 69.57%  |
| 0     | 32        | 27.83%  |
| 2     | 3         | 2.61%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 75        | 48.39%  |
| Realtek Semiconductor             | 30        | 19.35%  |
| Qualcomm Atheros                  | 22        | 14.19%  |
| Broadcom                          | 10        | 6.45%   |
| Sierra Wireless                   | 3         | 1.94%   |
| MediaTek                          | 3         | 1.94%   |
| Ericsson Business Mobile Networks | 2         | 1.29%   |
| AMD                               | 2         | 1.29%   |
| U-Blox                            | 1         | 0.65%   |
| Ralink Technology                 | 1         | 0.65%   |
| Ralink                            | 1         | 0.65%   |
| Nvidia                            | 1         | 0.65%   |
| NetGear                           | 1         | 0.65%   |
| Marvell Technology Group          | 1         | 0.65%   |
| JMicron Technology                | 1         | 0.65%   |
| Apple                             | 1         | 0.65%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 16        | 7.62%   |
| Intel Ethernet Connection I219-LM                                      | 10        | 4.76%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 9         | 4.29%   |
| Intel Wireless 8260                                                    | 9         | 4.29%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 9         | 4.29%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 8         | 3.81%   |
| Intel Wireless 8265 / 8275                                             | 6         | 2.86%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 5         | 2.38%   |
| Intel Wireless 7260                                                    | 5         | 2.38%   |
| Intel Wireless 7265                                                    | 4         | 1.9%    |
| Intel Wireless 3165                                                    | 4         | 1.9%    |
| Intel Wi-Fi 6 AX201                                                    | 4         | 1.9%    |
| Intel Ethernet Connection I218-LM                                      | 4         | 1.9%    |
| Intel Ethernet Connection (4) I219-LM                                  | 4         | 1.9%    |
| Intel 82577LM Gigabit Network Connection                               | 4         | 1.9%    |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 3         | 1.43%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 3         | 1.43%   |
| Intel Centrino Advanced-N 6200                                         | 3         | 1.43%   |
| Intel 82574L Gigabit Network Connection                                | 3         | 1.43%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                 | 3         | 1.43%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 2         | 0.95%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)         | 2         | 0.95%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 2         | 0.95%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 2         | 0.95%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 2         | 0.95%   |
| Intel Wi-Fi 6 AX200                                                    | 2         | 0.95%   |
| Intel I210 Gigabit Network Connection                                  | 2         | 0.95%   |
| Intel Ethernet Connection (4) I219-V                                   | 2         | 0.95%   |
| Intel Ethernet Connection (3) I218-LM                                  | 2         | 0.95%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 2         | 0.95%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 2         | 0.95%   |
| AMD XGMAC 10GbE Controller                                             | 2         | 0.95%   |
| U-Blox [u-blox 8]                                                      | 1         | 0.48%   |
| Sierra Wireless EM7455                                                 | 1         | 0.48%   |
| Sierra Wireless EM7345 4G LTE                                          | 1         | 0.48%   |
| Sierra Wireless EM7305 Modem                                           | 1         | 0.48%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 1         | 0.48%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 1         | 0.48%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 1         | 0.48%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 1         | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 65        | 63.11%  |
| Qualcomm Atheros      | 14        | 13.59%  |
| Broadcom              | 10        | 9.71%   |
| Realtek Semiconductor | 6         | 5.83%   |
| MediaTek              | 3         | 2.91%   |
| Sierra Wireless       | 2         | 1.94%   |
| Ralink Technology     | 1         | 0.97%   |
| Ralink                | 1         | 0.97%   |
| NetGear               | 1         | 0.97%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8260                                                     | 9         | 8.57%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 8         | 7.62%   |
| Intel Wireless 8265 / 8275                                              | 6         | 5.71%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5         | 4.76%   |
| Intel Wireless 7260                                                     | 5         | 4.76%   |
| Intel Wireless 7265                                                     | 4         | 3.81%   |
| Intel Wireless 3165                                                     | 4         | 3.81%   |
| Intel Wi-Fi 6 AX201                                                     | 4         | 3.81%   |
| Intel Centrino Advanced-N 6200                                          | 3         | 2.86%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 3         | 2.86%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 1.9%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 1.9%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 1.9%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 2         | 1.9%    |
| Intel Wi-Fi 6 AX200                                                     | 2         | 1.9%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 1.9%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2         | 1.9%    |
| Sierra Wireless EM7455                                                  | 1         | 0.95%   |
| Sierra Wireless EM7345 4G LTE                                           | 1         | 0.95%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 0.95%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 0.95%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.95%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 0.95%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 1         | 0.95%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 0.95%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 0.95%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 1         | 0.95%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                               | 1         | 0.95%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 1         | 0.95%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 1         | 0.95%   |
| Qualcomm Atheros AR5212 802.11abg NIC                                   | 1         | 0.95%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.95%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]             | 1         | 0.95%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter                       | 1         | 0.95%   |
| Intel Wireless 3160                                                     | 1         | 0.95%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 1         | 0.95%   |
| Intel Wi-Fi 6 AX201 160MHz                                              | 1         | 0.95%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 1         | 0.95%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 1         | 0.95%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 1         | 0.95%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 48        | 50%     |
| Realtek Semiconductor    | 27        | 28.13%  |
| Qualcomm Atheros         | 12        | 12.5%   |
| Broadcom                 | 3         | 3.13%   |
| AMD                      | 2         | 2.08%   |
| Nvidia                   | 1         | 1.04%   |
| Marvell Technology Group | 1         | 1.04%   |
| JMicron Technology       | 1         | 1.04%   |
| Apple                    | 1         | 1.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 16        | 16%     |
| Intel Ethernet Connection I219-LM                                      | 10        | 10%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 9         | 9%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 9         | 9%      |
| Intel Ethernet Connection I218-LM                                      | 4         | 4%      |
| Intel Ethernet Connection (4) I219-LM                                  | 4         | 4%      |
| Intel 82577LM Gigabit Network Connection                               | 4         | 4%      |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 3         | 3%      |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 3         | 3%      |
| Intel 82574L Gigabit Network Connection                                | 3         | 3%      |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 2         | 2%      |
| Intel I210 Gigabit Network Connection                                  | 2         | 2%      |
| Intel Ethernet Connection (4) I219-V                                   | 2         | 2%      |
| Intel Ethernet Connection (3) I218-LM                                  | 2         | 2%      |
| AMD XGMAC 10GbE Controller                                             | 2         | 2%      |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1         | 1%      |
| Realtek Killer E2600 GbE Controller                                    | 1         | 1%      |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 1%      |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 1         | 1%      |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1         | 1%      |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 1         | 1%      |
| Nvidia MCP79 Ethernet                                                  | 1         | 1%      |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                | 1         | 1%      |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 1         | 1%      |
| Intel I350 Gigabit Fiber Network Connection                            | 1         | 1%      |
| Intel I211 Gigabit Network Connection                                  | 1         | 1%      |
| Intel Ethernet Controller I225-V                                       | 1         | 1%      |
| Intel Ethernet Connection (6) I219-V                                   | 1         | 1%      |
| Intel Ethernet Connection (3) I218-V                                   | 1         | 1%      |
| Intel Ethernet Connection (2) I219-LM                                  | 1         | 1%      |
| Intel Ethernet Connection (16) I219-LM                                 | 1         | 1%      |
| Intel Ethernet Connection (13) I219-V                                  | 1         | 1%      |
| Intel Ethernet Connection (13) I219-LM                                 | 1         | 1%      |
| Intel 82583V Gigabit Network Connection                                | 1         | 1%      |
| Intel 82580 Gigabit Network Connection                                 | 1         | 1%      |
| Intel 82567LM Gigabit Network Connection                               | 1         | 1%      |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 1         | 1%      |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 1         | 1%      |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                        | 1         | 1%      |
| Apple UniNorth 2 GMAC (Sun GEM)                                        | 1         | 1%      |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 99        | 50%     |
| Ethernet | 94        | 47.47%  |
| Unknown  | 3         | 1.52%   |
| Modem    | 2         | 1.01%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 71        | 51.08%  |
| Ethernet | 68        | 48.92%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 85        | 77.27%  |
| 1     | 18        | 16.36%  |
| 3     | 3         | 2.73%   |
| 6     | 2         | 1.82%   |
| 10    | 1         | 0.91%   |
| 4     | 1         | 0.91%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 99        | 86.84%  |
| Yes  | 15        | 13.16%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 40        | 54.05%  |
| IMC Networks                    | 6         | 8.11%   |
| Broadcom                        | 6         | 8.11%   |
| Apple                           | 4         | 5.41%   |
| Foxconn / Hon Hai               | 3         | 4.05%   |
| Cambridge Silicon Radio         | 3         | 4.05%   |
| Realtek Semiconductor           | 2         | 2.7%    |
| Qualcomm Atheros Communications | 2         | 2.7%    |
| Lite-On Technology              | 2         | 2.7%    |
| ASUSTek Computer                | 2         | 2.7%    |
| Alps Electric                   | 2         | 2.7%    |
| Toshiba                         | 1         | 1.35%   |
| Hewlett-Packard                 | 1         | 1.35%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 23        | 31.08%  |
| Intel AX201 Bluetooth                                       | 8         | 10.81%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 3         | 4.05%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 3         | 4.05%   |
| Apple Bluetooth Host Controller                             | 3         | 4.05%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 2         | 2.7%    |
| Intel AX200 Bluetooth                                       | 2         | 2.7%    |
| IMC Networks MediaTek Bluetooth Adapter                     | 2         | 2.7%    |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 2         | 2.7%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 2         | 2.7%    |
| Alps Electric UGTZ4 Bluetooth                               | 2         | 2.7%    |
| Toshiba ASKEY Bluetooth Controller BTU1030                  | 1         | 1.35%   |
| Realtek Bluetooth Adapter                                   | 1         | 1.35%   |
| Realtek Bluetooth 4.0 Adapter                               | 1         | 1.35%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1         | 1.35%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 1         | 1.35%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 1         | 1.35%   |
| Lite-On Broadcom Bluetooth 4.0 USB                          | 1         | 1.35%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 1         | 1.35%   |
| Intel Wireless-AC 3168 Bluetooth                            | 1         | 1.35%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 1         | 1.35%   |
| Intel AX211 Bluetooth                                       | 1         | 1.35%   |
| Intel AX210 Bluetooth                                       | 1         | 1.35%   |
| IMC Networks Realtek Bluetooth Adapter                      | 1         | 1.35%   |
| IMC Networks Bluetooth                                      | 1         | 1.35%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 1         | 1.35%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                | 1         | 1.35%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth USB Device    | 1         | 1.35%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 1         | 1.35%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 1         | 1.35%   |
| ASUS Broadcom Bluetooth 2.1                                 | 1         | 1.35%   |
| ASUS Broadcom BCM20702A0 Bluetooth                          | 1         | 1.35%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 1         | 1.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 95        | 81.9%   |
| AMD                    | 10        | 8.62%   |
| Nvidia                 | 7         | 6.03%   |
| XMOS                   | 1         | 0.86%   |
| Generalplus Technology | 1         | 0.86%   |
| Creative Technology    | 1         | 0.86%   |
| C-Media Electronics    | 1         | 0.86%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 20        | 14.49%  |
| Intel 8 Series HD Audio Controller                                                                | 8         | 5.8%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 8         | 5.8%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 8         | 5.8%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 8         | 5.8%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 7         | 5.07%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 7         | 5.07%   |
| Intel Broadwell-U Audio Controller                                                                | 7         | 5.07%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 6         | 4.35%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 5         | 3.62%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 5         | 3.62%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 5         | 3.62%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 2.17%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 2.17%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 1.45%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 1.45%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.45%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 1.45%   |
| AMD FCH Azalia Controller                                                                         | 2         | 1.45%   |
| XMOS USB Audio                                                                                    | 1         | 0.72%   |
| XMOS iFi (by AMR) HD USB Audio                                                                    | 1         | 0.72%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.72%   |
| Nvidia MCP89 High Definition Audio                                                                | 1         | 0.72%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.72%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.72%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.72%   |
| Nvidia GA107 High Definition Audio Controller                                                     | 1         | 0.72%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 0.72%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 1         | 0.72%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1         | 0.72%   |
| Intel Raptor Lake-P/U/H cAVS                                                                      | 1         | 0.72%   |
| Intel Jasper Lake HD Audio                                                                        | 1         | 0.72%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 0.72%   |
| Intel Comet Lake PCH cAVS                                                                         | 1         | 0.72%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 1         | 0.72%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.72%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 1         | 0.72%   |
| Intel 82801CA/CAM AC'97 Audio Controller                                                          | 1         | 0.72%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1         | 0.72%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 0.72%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 29        | 26.13%  |
| Samsung Electronics | 27        | 24.32%  |
| Micron Technology   | 12        | 10.81%  |
| Unknown             | 11        | 9.91%   |
| Kingston            | 10        | 9.01%   |
| Unknown             | 5         | 4.5%    |
| Crucial             | 4         | 3.6%    |
| Corsair             | 3         | 2.7%    |
| Transcend           | 2         | 1.8%    |
| A-DATA Technology   | 2         | 1.8%    |
| Unknown (ABCD)      | 1         | 0.9%    |
| Ramaxel Technology  | 1         | 0.9%    |
| Nanya Technology    | 1         | 0.9%    |
| G.Skill             | 1         | 0.9%    |
| Elpida              | 1         | 0.9%    |
| 268c                | 1         | 0.9%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 5         | 4.31%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 2.59%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 2.59%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 2         | 1.72%   |
| Unknown RAM Module 1GB SODIMM DDR2                               | 2         | 1.72%   |
| Transcend RAM TS1GLH64V6BL 8GB SODIMM DDR4 2667MT/s              | 2         | 1.72%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.72%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s           | 2         | 1.72%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 2         | 1.72%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 2         | 1.72%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s            | 2         | 1.72%   |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM DDR3 1067MT/s            | 2         | 1.72%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.72%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 1.72%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s            | 2         | 1.72%   |
| Unknown RAM Module 8GB SODIMM DDR4 2400MT/s                      | 1         | 0.86%   |
| Unknown RAM Module 512MB SODIMM SDRAM                            | 1         | 0.86%   |
| Unknown RAM Module 4096MB SODIMM DDR2                            | 1         | 0.86%   |
| Unknown RAM Module 2GB SODIMM DDR3 1067MT/s                      | 1         | 0.86%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 0.86%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                           | 1         | 0.86%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 1         | 0.86%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s | 1         | 0.86%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                     | 1         | 0.86%   |
| SK hynix RAM HYMP112S64CP6-Y5 1GB SODIMM DDR 667MT/s             | 1         | 0.86%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 1         | 0.86%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.86%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.86%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.86%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.86%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 0.86%   |
| SK hynix RAM HMT325S6CFR8C-H9 2GB SODIMM DDR3 1333MT/s           | 1         | 0.86%   |
| SK hynix RAM HMT112S6AFP6C-G7 1GB SODIMM 800MT/s                 | 1         | 0.86%   |
| SK hynix RAM HMCG78MEBSA092N 16GB SODIMM DDR5 4800MT/s           | 1         | 0.86%   |
| SK hynix RAM HMAG68EXNSA051N 8GB SODIMM DDR4 3200MT/s            | 1         | 0.86%   |
| SK hynix RAM HMAA2GS6AJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 0.86%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 0.86%   |
| SK hynix RAM HMA851S6AFR6N-UH 4096MB Row Of Chips DDR4 2400MT/s  | 1         | 0.86%   |
| SK hynix RAM HCNNNBKMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s   | 1         | 0.86%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 1         | 0.86%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 48        | 47.52%  |
| DDR4    | 33        | 32.67%  |
| DDR2    | 7         | 6.93%   |
| LPDDR4  | 4         | 3.96%   |
| LPDDR3  | 4         | 3.96%   |
| SDRAM   | 3         | 2.97%   |
| DDR5    | 1         | 0.99%   |
| Unknown | 1         | 0.99%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 91        | 89.22%  |
| Row Of Chips | 7         | 6.86%   |
| Chip         | 3         | 2.94%   |
| Unknown      | 1         | 0.98%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 34        | 31.78%  |
| 4096  | 34        | 31.78%  |
| 2048  | 19        | 17.76%  |
| 16384 | 12        | 11.21%  |
| 1024  | 4         | 3.74%   |
| 32768 | 3         | 2.8%    |
| 512   | 1         | 0.93%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 27        | 25.47%  |
| 3200    | 13        | 12.26%  |
| 2400    | 11        | 10.38%  |
| 2667    | 9         | 8.49%   |
| 1333    | 9         | 8.49%   |
| 1067    | 8         | 7.55%   |
| 2133    | 7         | 6.6%    |
| 1334    | 6         | 5.66%   |
| Unknown | 6         | 5.66%   |
| 667     | 4         | 3.77%   |
| 4267    | 2         | 1.89%   |
| 800     | 2         | 1.89%   |
| 4800    | 1         | 0.94%   |
| 1867    | 1         | 0.94%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Samsung ML-1610 Mono Laser Printer | 1         | 100%    |

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


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 23        | 31.51%  |
| IMC Networks                  | 8         | 10.96%  |
| Realtek Semiconductor         | 7         | 9.59%   |
| Microdia                      | 7         | 9.59%   |
| Bison Electronics             | 7         | 9.59%   |
| Lite-On Technology            | 4         | 5.48%   |
| Sunplus Innovation Technology | 3         | 4.11%   |
| Syntek                        | 2         | 2.74%   |
| Suyin                         | 2         | 2.74%   |
| Luxvisions Innotech Limited   | 2         | 2.74%   |
| Apple                         | 2         | 2.74%   |
| Silicon Motion                | 1         | 1.37%   |
| Ricoh                         | 1         | 1.37%   |
| Quanta                        | 1         | 1.37%   |
| Lenovo                        | 1         | 1.37%   |
| ALi                           | 1         | 1.37%   |
| Alcor Micro                   | 1         | 1.37%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                   | 7         | 9.59%   |
| Lite-On Integrated Camera                                   | 4         | 5.48%   |
| Bison Integrated Camera                                     | 4         | 5.48%   |
| Microdia Integrated_Webcam_HD                               | 3         | 4.11%   |
| IMC Networks Integrated Camera                              | 3         | 4.11%   |
| Chicony HD Webcam                                           | 3         | 4.11%   |
| Realtek Integrated Webcam HD                                | 2         | 2.74%   |
| Luxvisions Innotech Limited Integrated Camera               | 2         | 2.74%   |
| Chicony Integrated Camera [ThinkPad]                        | 2         | 2.74%   |
| Chicony 2.0M UVC Webcam / CNF7129                           | 2         | 2.74%   |
| Syntek Lenovo EasyCamera                                    | 1         | 1.37%   |
| Syntek Integrated Camera                                    | 1         | 1.37%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                    | 1         | 1.37%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 1.37%   |
| Sunplus Laptop_Integrated_Webcam_FHD                        | 1         | 1.37%   |
| Sunplus ASUS Webcam                                         | 1         | 1.37%   |
| Sunplus 2-USB 2.0 Camera                                    | 1         | 1.37%   |
| Silicon Motion Lenovo EasyCamera                            | 1         | 1.37%   |
| Ricoh Integrated Webcam                                     | 1         | 1.37%   |
| Realtek USB 2.0 PC Camera                                   | 1         | 1.37%   |
| Realtek PC Camera                                           | 1         | 1.37%   |
| Realtek Laptop Camera                                       | 1         | 1.37%   |
| Realtek Integrated Webcam                                   | 1         | 1.37%   |
| Realtek HD Webcam - Realtek                                 | 1         | 1.37%   |
| Quanta Realtek PC Camera                                    | 1         | 1.37%   |
| Microdia Sonix USB 2.0 Camera                               | 1         | 1.37%   |
| Microdia Laptop_Integrated_Webcam_2M                        | 1         | 1.37%   |
| Microdia Integrated Webcam HD                               | 1         | 1.37%   |
| Microdia Integrated Webcam                                  | 1         | 1.37%   |
| Lenovo Integrated Webcam [R5U877]                           | 1         | 1.37%   |
| IMC Networks UVC VGA Webcam                                 | 1         | 1.37%   |
| IMC Networks Realtek PC Camera                              | 1         | 1.37%   |
| IMC Networks Realtek DMFT RGB                               | 1         | 1.37%   |
| IMC Networks Integrated Webcam                              | 1         | 1.37%   |
| IMC Networks EasyCamera                                     | 1         | 1.37%   |
| Chicony WebCam                                              | 1         | 1.37%   |
| Chicony VGA 24fps UVC Webcam                                | 1         | 1.37%   |
| Chicony USB2.0 HD UVC WebCam                                | 1         | 1.37%   |
| Chicony TOSHIBA Web Camera - HD                             | 1         | 1.37%   |
| Chicony TOSHIBA Web Camera - FHD                            | 1         | 1.37%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 12        | 48%     |
| Synaptics                  | 3         | 12%     |
| Upek                       | 2         | 8%      |
| Shenzhen Goodix Technology | 2         | 8%      |
| LighTuning Technology      | 2         | 8%      |
| Elan Microelectronics      | 2         | 8%      |
| AuthenTec                  | 2         | 8%      |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor           | 5         | 20%     |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 2         | 8%      |
| Validity Sensors Synaptics WBDI                        | 2         | 8%      |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 2         | 8%      |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 2         | 8%      |
| Shenzhen Goodix Fingerprint Reader                     | 2         | 8%      |
| LighTuning EgisTec Touch Fingerprint Sensor            | 2         | 8%      |
| Elan Fingerprint Sensor                                | 2         | 8%      |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 4%      |
| Validity Sensors VFS Fingerprint sensor                | 1         | 4%      |
| Validity Sensors Fingerprint scanner                   | 1         | 4%      |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 4%      |
| AuthenTec AES2660                                      | 1         | 4%      |
| AuthenTec AES2501 Fingerprint Sensor                   | 1         | 4%      |

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


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 47        | 41.23%  |
| 2     | 26        | 22.81%  |
| 3     | 19        | 16.67%  |
| 0     | 14        | 12.28%  |
| 4     | 7         | 6.14%   |
| 5     | 1         | 0.88%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 78        | 46.43%  |
| Bluetooth                | 25        | 14.88%  |
| Fingerprint reader       | 18        | 10.71%  |
| Card reader              | 13        | 7.74%   |
| Net/wireless             | 12        | 7.14%   |
| Firewire controller      | 10        | 5.95%   |
| Sound                    | 3         | 1.79%   |
| Graphics card            | 3         | 1.79%   |
| Storage                  | 2         | 1.19%   |
| Net/ethernet             | 2         | 1.19%   |
| Storage/ata              | 1         | 0.6%    |
| Network                  | 1         | 0.6%    |

