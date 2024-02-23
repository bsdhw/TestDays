helloSystem 0.8.1 - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------------

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

Total: 261

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T480 20L6SDA400    | [4934e88205](https://bsd-hardware.info/?probe=4934e88205) | Feb 07, 2024 |
| ASUSTek       | K52F                        | [bc31c4707c](https://bsd-hardware.info/?probe=bc31c4707c) | Feb 04, 2024 |
| Panasonic     | CF-52PGNBX2M                | [401aeae642](https://bsd-hardware.info/?probe=401aeae642) | Feb 03, 2024 |
| ASUSTek       | K52F                        | [9022031518](https://bsd-hardware.info/?probe=9022031518) | Feb 03, 2024 |
| Lenovo        | ThinkPad T460 20FMS1VA1D    | [03d11c45e9](https://bsd-hardware.info/?probe=03d11c45e9) | Jan 28, 2024 |
| Dell          | Precision M4700             | [05a9a26c16](https://bsd-hardware.info/?probe=05a9a26c16) | Jan 24, 2024 |
| Acer          | Nitro AN515-54              | [28539d7eb4](https://bsd-hardware.info/?probe=28539d7eb4) | Jan 24, 2024 |
| Acer          | TravelMate B115-M           | [d7a78aa2cf](https://bsd-hardware.info/?probe=d7a78aa2cf) | Jan 22, 2024 |
| Apple         | MacBookAir4,1               | [f51a396e5e](https://bsd-hardware.info/?probe=f51a396e5e) | Jan 21, 2024 |
| Dell          | Latitude 7480               | [d9b4d836e7](https://bsd-hardware.info/?probe=d9b4d836e7) | Jan 17, 2024 |
| HP            | Mini 210-1000               | [f25c646418](https://bsd-hardware.info/?probe=f25c646418) | Jan 16, 2024 |
| HP            | Mini 210-1000               | [fb086c3baa](https://bsd-hardware.info/?probe=fb086c3baa) | Jan 15, 2024 |
| Apple         | MacBookAir4,1               | [b9653bc7d3](https://bsd-hardware.info/?probe=b9653bc7d3) | Jan 14, 2024 |
| Dell          | Inspiron 14-3452            | [47ac3f7eaa](https://bsd-hardware.info/?probe=47ac3f7eaa) | Jan 09, 2024 |
| HP            | Compaq 6510b (GM108UC#AB... | [7ed7da2383](https://bsd-hardware.info/?probe=7ed7da2383) | Jan 08, 2024 |
| ASUSTek       | X551MA                      | [91eda59c82](https://bsd-hardware.info/?probe=91eda59c82) | Jan 06, 2024 |
| Lenovo        | ThinkPad X250 20CMS01M00    | [1f52525bb9](https://bsd-hardware.info/?probe=1f52525bb9) | Jan 04, 2024 |
| Samsung       | R510/P510                   | [920e7e2d14](https://bsd-hardware.info/?probe=920e7e2d14) | Dec 31, 2023 |
| Dell          | Vostro V130                 | [44e78243c2](https://bsd-hardware.info/?probe=44e78243c2) | Dec 30, 2023 |
| Lenovo        | ThinkPad X131e 33672T9      | [93f964da45](https://bsd-hardware.info/?probe=93f964da45) | Dec 25, 2023 |
| eMachines     | eM350                       | [00d1d0c359](https://bsd-hardware.info/?probe=00d1d0c359) | Dec 23, 2023 |
| Lenovo        | ThinkPad X220 4291H77       | [2fe3ff7e06](https://bsd-hardware.info/?probe=2fe3ff7e06) | Dec 18, 2023 |
| Acer          | V5-131                      | [76e88ee5df](https://bsd-hardware.info/?probe=76e88ee5df) | Dec 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [7a1ab6fd47](https://bsd-hardware.info/?probe=7a1ab6fd47) | Dec 06, 2023 |
| Intel         | H81U                        | [b74cca91df](https://bsd-hardware.info/?probe=b74cca91df) | Dec 01, 2023 |
| Samsung       | N150P/N210P/N220P           | [b394563830](https://bsd-hardware.info/?probe=b394563830) | Nov 30, 2023 |
| Lenovo        | Yoga 2 Pro 20266            | [1096dc8160](https://bsd-hardware.info/?probe=1096dc8160) | Nov 27, 2023 |
| Lenovo        | Yoga 2 Pro 20266            | [1bfc57a019](https://bsd-hardware.info/?probe=1bfc57a019) | Nov 27, 2023 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [a44d6afa76](https://bsd-hardware.info/?probe=a44d6afa76) | Nov 24, 2023 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [b67644f2b3](https://bsd-hardware.info/?probe=b67644f2b3) | Nov 24, 2023 |
| Acer          | Aspire E5-574               | [a4eded7a52](https://bsd-hardware.info/?probe=a4eded7a52) | Nov 22, 2023 |
| HP            | Laptop 14-fq0xxx            | [4c5aa5c3ea](https://bsd-hardware.info/?probe=4c5aa5c3ea) | Nov 22, 2023 |
| Lenovo        | ThinkPad X230 2320A5U       | [48f8b6a93a](https://bsd-hardware.info/?probe=48f8b6a93a) | Nov 16, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | [b85df96058](https://bsd-hardware.info/?probe=b85df96058) | Nov 11, 2023 |
| Lenovo        | ThinkPad E14 20RA0016RT     | [83b87dac52](https://bsd-hardware.info/?probe=83b87dac52) | Nov 10, 2023 |
| Gateway       | NV79                        | [2a7dd49956](https://bsd-hardware.info/?probe=2a7dd49956) | Nov 09, 2023 |
| Lenovo        | Z50-70 20354                | [641e875b3b](https://bsd-hardware.info/?probe=641e875b3b) | Nov 04, 2023 |
| TUXEDO        | Aura 15 Gen1                | [7a6b4537f3](https://bsd-hardware.info/?probe=7a6b4537f3) | Oct 29, 2023 |
| Lenovo        | Z50-70 20354                | [f3d9534b2d](https://bsd-hardware.info/?probe=f3d9534b2d) | Oct 28, 2023 |
| Lenovo        | ThinkPad T520 42405FG       | [e6aca7e0c8](https://bsd-hardware.info/?probe=e6aca7e0c8) | Oct 28, 2023 |
| Toshiba       | Unknown                     | [de44a16738](https://bsd-hardware.info/?probe=de44a16738) | Oct 24, 2023 |
| Acer          | Aspire 5336                 | [ebfed0efbc](https://bsd-hardware.info/?probe=ebfed0efbc) | Oct 18, 2023 |
| Apple         | MacBook5,2                  | [5f364ec930](https://bsd-hardware.info/?probe=5f364ec930) | Oct 17, 2023 |
| Dell          | Latitude 3440               | [3e6826570c](https://bsd-hardware.info/?probe=3e6826570c) | Oct 16, 2023 |
| Lenovo        | ThinkPad T480 20L5000UUS    | [20fe904881](https://bsd-hardware.info/?probe=20fe904881) | Oct 15, 2023 |
| Acer          | Aspire ES1-571              | [f3036a27e5](https://bsd-hardware.info/?probe=f3036a27e5) | Oct 13, 2023 |
| Apple         | MacBook5,1                  | [518658e176](https://bsd-hardware.info/?probe=518658e176) | Oct 11, 2023 |
| Apple         | MacBookPro9,2               | [c88d8880ea](https://bsd-hardware.info/?probe=c88d8880ea) | Oct 11, 2023 |
| Lenovo        | IdeaPad 3 17ITL6 82H9       | [5be3eb1296](https://bsd-hardware.info/?probe=5be3eb1296) | Oct 08, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [c646a3b663](https://bsd-hardware.info/?probe=c646a3b663) | Oct 07, 2023 |
| ASUSTek       | K73E                        | [ce5fcbdc3e](https://bsd-hardware.info/?probe=ce5fcbdc3e) | Oct 04, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [5cd50ed5b5](https://bsd-hardware.info/?probe=5cd50ed5b5) | Sep 24, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | [8a3d3b3d0d](https://bsd-hardware.info/?probe=8a3d3b3d0d) | Sep 21, 2023 |
| Lenovo        | ThinkPad Edge E531 68852... | [cc3bef6a45](https://bsd-hardware.info/?probe=cc3bef6a45) | Sep 15, 2023 |
| OEGStone      | doceo 510                   | [9f3b47e30f](https://bsd-hardware.info/?probe=9f3b47e30f) | Sep 13, 2023 |
| HP            | OMEN by Laptop              | [f0fc4f47b8](https://bsd-hardware.info/?probe=f0fc4f47b8) | Sep 10, 2023 |
| Lenovo        | ThinkPad SL 2746N8G         | [07eda65608](https://bsd-hardware.info/?probe=07eda65608) | Sep 09, 2023 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | [1d5aff2e2a](https://bsd-hardware.info/?probe=1d5aff2e2a) | Sep 08, 2023 |
| HP            | Pavilion g7                 | [4870da3b0e](https://bsd-hardware.info/?probe=4870da3b0e) | Sep 07, 2023 |
| Lenovo        | ThinkPad X240 20AMA1Y3UK    | [8277297743](https://bsd-hardware.info/?probe=8277297743) | Sep 05, 2023 |
| HP            | G62                         | [b4777b6ba5](https://bsd-hardware.info/?probe=b4777b6ba5) | Sep 04, 2023 |
| Toshiba       | QOSMIO X775                 | [d92a05ab1d](https://bsd-hardware.info/?probe=d92a05ab1d) | Sep 04, 2023 |
| Samsung       | 270E5J/2570EJ               | [3feb685296](https://bsd-hardware.info/?probe=3feb685296) | Sep 03, 2023 |
| Fujitsu       | LIFEBOOK S935               | [a6cfe011fe](https://bsd-hardware.info/?probe=a6cfe011fe) | Sep 02, 2023 |
| HP            | 2000                        | [6d9c442ae6](https://bsd-hardware.info/?probe=6d9c442ae6) | Aug 31, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [a308c3a87b](https://bsd-hardware.info/?probe=a308c3a87b) | Aug 31, 2023 |
| HP            | Pavilion dv3500             | [0c3f84b285](https://bsd-hardware.info/?probe=0c3f84b285) | Aug 29, 2023 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | [e74ef1d37c](https://bsd-hardware.info/?probe=e74ef1d37c) | Aug 29, 2023 |
| NVN-ED01      | Unknown                     | [dba43e889a](https://bsd-hardware.info/?probe=dba43e889a) | Aug 25, 2023 |
| Lenovo        | ThinkPad P50 20EN0009MS     | [4b3fcfa17e](https://bsd-hardware.info/?probe=4b3fcfa17e) | Aug 25, 2023 |
| ASUSTek       | S500CA                      | [019366a664](https://bsd-hardware.info/?probe=019366a664) | Aug 25, 2023 |
| Lenovo        | ThinkPad T450 20BUS0370P    | [5fefc051e1](https://bsd-hardware.info/?probe=5fefc051e1) | Aug 20, 2023 |
| ASUSTek       | X553MA                      | [7334765d8a](https://bsd-hardware.info/?probe=7334765d8a) | Aug 16, 2023 |
| ASUSTek       | GL753VD                     | [8ccbffdd73](https://bsd-hardware.info/?probe=8ccbffdd73) | Aug 15, 2023 |
| Lenovo        | ThinkPad X200 7458WNZ       | [3ac1d60240](https://bsd-hardware.info/?probe=3ac1d60240) | Aug 12, 2023 |
| Lenovo        | ThinkPad T60 1951CZ1        | [46766bc381](https://bsd-hardware.info/?probe=46766bc381) | Aug 11, 2023 |
| Acer          | Aspire V3-371               | [21c262aadb](https://bsd-hardware.info/?probe=21c262aadb) | Aug 09, 2023 |
| Acer          | Aspire V3-371               | [68bceee682](https://bsd-hardware.info/?probe=68bceee682) | Aug 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [9c01814bdc](https://bsd-hardware.info/?probe=9c01814bdc) | Aug 07, 2023 |
| Compaq        | Presario CQ-17              | [f97feb2db0](https://bsd-hardware.info/?probe=f97feb2db0) | Aug 04, 2023 |
| HP            | EliteBook 840 G5            | [6496fe0cfe](https://bsd-hardware.info/?probe=6496fe0cfe) | Aug 03, 2023 |
| Lenovo        | IdeaPad S210 Touch 20257    | [1e372622c1](https://bsd-hardware.info/?probe=1e372622c1) | Jul 31, 2023 |
| Lenovo        | ThinkPad X270 20HNA04GCD    | [6547f4a73b](https://bsd-hardware.info/?probe=6547f4a73b) | Jul 31, 2023 |
| Lenovo        | ThinkPad X230 23202DG       | [f8ade878ce](https://bsd-hardware.info/?probe=f8ade878ce) | Jul 30, 2023 |
| HP            | Notebook                    | [360790274a](https://bsd-hardware.info/?probe=360790274a) | Jul 29, 2023 |
| Apple         | MacBookPro9,2               | [53e133857b](https://bsd-hardware.info/?probe=53e133857b) | Jul 29, 2023 |
| HP            | Pavilion g6                 | [bdd2349f1c](https://bsd-hardware.info/?probe=bdd2349f1c) | Jul 28, 2023 |
| Dell          | Latitude 5480               | [e1521ed9d2](https://bsd-hardware.info/?probe=e1521ed9d2) | Jul 26, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [60dac781b2](https://bsd-hardware.info/?probe=60dac781b2) | Jul 24, 2023 |
| Acer          | Aspire 4736Z                | [bccf97f694](https://bsd-hardware.info/?probe=bccf97f694) | Jul 20, 2023 |
| ASUSTek       | 1015PX                      | [dc06c76cf9](https://bsd-hardware.info/?probe=dc06c76cf9) | Jul 19, 2023 |
| Lenovo        | Legion 5 15IMH05 82AU       | [5fcffa5bd6](https://bsd-hardware.info/?probe=5fcffa5bd6) | Jul 19, 2023 |
| ASUSTek       | K42Jr                       | [256168572a](https://bsd-hardware.info/?probe=256168572a) | Jul 18, 2023 |
| Samsung       | RC530/RC730                 | [b76e5e8a87](https://bsd-hardware.info/?probe=b76e5e8a87) | Jul 17, 2023 |
| Lenovo        | ThinkPad R14 Gen 4 21E5A... | [e0fc7135e5](https://bsd-hardware.info/?probe=e0fc7135e5) | Jul 15, 2023 |
| ASUSTek       | X541UVK                     | [17f58b70e4](https://bsd-hardware.info/?probe=17f58b70e4) | Jul 10, 2023 |
| HP            | Compaq Presario CQ61        | [d070292855](https://bsd-hardware.info/?probe=d070292855) | Jul 03, 2023 |
| Lenovo        | ThinkPad T60 20076PU        | [cb47bfef12](https://bsd-hardware.info/?probe=cb47bfef12) | Jun 30, 2023 |
| HP            | EliteBook 840 G3            | [17834256ca](https://bsd-hardware.info/?probe=17834256ca) | Jun 28, 2023 |
| Dell          | Latitude E4310              | [9cdd4909fe](https://bsd-hardware.info/?probe=9cdd4909fe) | Jun 24, 2023 |
| HP            | Laptop 15-ra0xx             | [8c31502b68](https://bsd-hardware.info/?probe=8c31502b68) | Jun 24, 2023 |
| HP            | EliteBook 750 G1            | [aba91c70d1](https://bsd-hardware.info/?probe=aba91c70d1) | Jun 24, 2023 |
| Dell          | Latitude 5490               | [b638c1b2b1](https://bsd-hardware.info/?probe=b638c1b2b1) | Jun 23, 2023 |
| Acer          | Aspire 5749                 | [75ad2ddb6f](https://bsd-hardware.info/?probe=75ad2ddb6f) | Jun 22, 2023 |
| Acer          | Aspire 5749                 | [1e91633580](https://bsd-hardware.info/?probe=1e91633580) | Jun 20, 2023 |
| HP            | Pavilion 15                 | [9ba6acdb4b](https://bsd-hardware.info/?probe=9ba6acdb4b) | Jun 18, 2023 |
| HP            | Stream Laptop 14-ds0xxx     | [81bbc73e72](https://bsd-hardware.info/?probe=81bbc73e72) | Jun 18, 2023 |
| HUAWEI        | BOHB-WAX9                   | [d8079e6155](https://bsd-hardware.info/?probe=d8079e6155) | Jun 16, 2023 |
| MSI           | GE63 Raider RGB 8RE         | [ecdb80adc0](https://bsd-hardware.info/?probe=ecdb80adc0) | Jun 14, 2023 |
| HP            | Compaq 6830s                | [1a06917a0f](https://bsd-hardware.info/?probe=1a06917a0f) | Jun 14, 2023 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [76809610f9](https://bsd-hardware.info/?probe=76809610f9) | Jun 13, 2023 |
| Lenovo        | ThinkPad T440p 20AWS1CH0... | [b532f1ce9c](https://bsd-hardware.info/?probe=b532f1ce9c) | Jun 13, 2023 |
| Samsung       | R530/R730/R540              | [b007264caa](https://bsd-hardware.info/?probe=b007264caa) | Jun 11, 2023 |
| Lenovo        | S10-3                       | [f874a66e78](https://bsd-hardware.info/?probe=f874a66e78) | Jun 05, 2023 |
| Lenovo        | S10-3                       | [b76483ab8b](https://bsd-hardware.info/?probe=b76483ab8b) | Jun 05, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [e1a7d29d74](https://bsd-hardware.info/?probe=e1a7d29d74) | Jun 04, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [d0d9de7cf3](https://bsd-hardware.info/?probe=d0d9de7cf3) | Jun 04, 2023 |
| Panasonic     | CF-NX1GDHYS                 | [fb1f293997](https://bsd-hardware.info/?probe=fb1f293997) | Jun 02, 2023 |
| HP            | Pavilion Notebook           | [1bb0436fe5](https://bsd-hardware.info/?probe=1bb0436fe5) | May 30, 2023 |
| Apple         | MacBookPro10,2              | [c274e2c9db](https://bsd-hardware.info/?probe=c274e2c9db) | May 29, 2023 |
| Fujitsu       | Unknown                     | [3b5c9ab914](https://bsd-hardware.info/?probe=3b5c9ab914) | May 27, 2023 |
| Timi          | TM1701                      | [1dd768a721](https://bsd-hardware.info/?probe=1dd768a721) | May 25, 2023 |
| ASUSTek       | K42Jc                       | [3da2928a08](https://bsd-hardware.info/?probe=3da2928a08) | May 23, 2023 |
| Google        | Sentry                      | [107124dd66](https://bsd-hardware.info/?probe=107124dd66) | May 22, 2023 |
| Sony          | VPCEG15FB                   | [8777493861](https://bsd-hardware.info/?probe=8777493861) | May 21, 2023 |
| HP            | Pavilion Notebook           | [41ce3c5d11](https://bsd-hardware.info/?probe=41ce3c5d11) | May 21, 2023 |
| Packard Be... | EasyNote LJ65               | [36d3e7aaf7](https://bsd-hardware.info/?probe=36d3e7aaf7) | May 19, 2023 |
| Sony          | SVF14A15CBB                 | [4ada2dca25](https://bsd-hardware.info/?probe=4ada2dca25) | May 14, 2023 |
| Lenovo        | B570e HuronRiver Platfor... | [256915976d](https://bsd-hardware.info/?probe=256915976d) | May 12, 2023 |
| TUXEDO        | Aura 15 Gen1                | [3d889e8b9b](https://bsd-hardware.info/?probe=3d889e8b9b) | May 11, 2023 |
| Apple         | MacBook5,1                  | [da07885adb](https://bsd-hardware.info/?probe=da07885adb) | May 09, 2023 |
| HP            | Laptop 14-bs0xx             | [98ea66d6e8](https://bsd-hardware.info/?probe=98ea66d6e8) | May 07, 2023 |
| Lenovo        | Flex 2-15 20405             | [3773da7851](https://bsd-hardware.info/?probe=3773da7851) | May 03, 2023 |
| HP            | Compaq Presario CQ50        | [f296048a29](https://bsd-hardware.info/?probe=f296048a29) | May 03, 2023 |
| Apple         | MacBook5,1                  | [a5a1ca2ee6](https://bsd-hardware.info/?probe=a5a1ca2ee6) | May 02, 2023 |
| Apple         | MacBook5,1                  | [52174cc0ba](https://bsd-hardware.info/?probe=52174cc0ba) | Apr 27, 2023 |
| Apple         | MacBook5,1                  | [4c7f33d6a9](https://bsd-hardware.info/?probe=4c7f33d6a9) | Apr 25, 2023 |
| Lenovo        | ThinkPad X270 20HMS06Q1D    | [2df7c991f0](https://bsd-hardware.info/?probe=2df7c991f0) | Apr 23, 2023 |
| Lenovo        | G500 20236                  | [e7387bfd6e](https://bsd-hardware.info/?probe=e7387bfd6e) | Apr 23, 2023 |
| Dell          | Inspiron 3421               | [ef4870410f](https://bsd-hardware.info/?probe=ef4870410f) | Apr 23, 2023 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | [93b498fb0c](https://bsd-hardware.info/?probe=93b498fb0c) | Apr 21, 2023 |
| Packard Be... | DOT SE                      | [f456e964db](https://bsd-hardware.info/?probe=f456e964db) | Apr 19, 2023 |
| Dell          | Latitude 7410               | [d5c047907d](https://bsd-hardware.info/?probe=d5c047907d) | Apr 19, 2023 |
| Acer          | V5-131                      | [4c2332c3b8](https://bsd-hardware.info/?probe=4c2332c3b8) | Apr 19, 2023 |
| Medion        | E15302                      | [f47f32e1cc](https://bsd-hardware.info/?probe=f47f32e1cc) | Apr 17, 2023 |
| Toshiba       | PORTEGE R700                | [8b196955ac](https://bsd-hardware.info/?probe=8b196955ac) | Apr 15, 2023 |
| Apple         | MacBook3,1                  | [74986a169a](https://bsd-hardware.info/?probe=74986a169a) | Apr 15, 2023 |
| Google        | Terra                       | [ef1619f65f](https://bsd-hardware.info/?probe=ef1619f65f) | Apr 13, 2023 |
| Google        | Terra                       | [bf598bc5bf](https://bsd-hardware.info/?probe=bf598bc5bf) | Apr 13, 2023 |
| Samsung       | 370E4K                      | [c363d008bf](https://bsd-hardware.info/?probe=c363d008bf) | Apr 13, 2023 |
| Lenovo        | ThinkPad L540 20AUA34DJP    | [c7e40ee8ea](https://bsd-hardware.info/?probe=c7e40ee8ea) | Apr 12, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X3C... | [0249b4e73f](https://bsd-hardware.info/?probe=0249b4e73f) | Apr 11, 2023 |
| Lenovo        | ThinkPad L540 20AUA34DJP    | [52aac5fc6f](https://bsd-hardware.info/?probe=52aac5fc6f) | Apr 11, 2023 |
| Lenovo        | ThinkPad X1 Carbon 34487... | [cec90ddd1b](https://bsd-hardware.info/?probe=cec90ddd1b) | Apr 08, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [f3ac765863](https://bsd-hardware.info/?probe=f3ac765863) | Apr 08, 2023 |
| Dell          | XPS 13 9343                 | [8354aed46e](https://bsd-hardware.info/?probe=8354aed46e) | Apr 07, 2023 |
| Fujitsu       | CELSIUS H920                | [0551eecbcc](https://bsd-hardware.info/?probe=0551eecbcc) | Apr 06, 2023 |
| Acer          | Aspire 5250                 | [385751dbc3](https://bsd-hardware.info/?probe=385751dbc3) | Apr 06, 2023 |
| Google        | Wolf                        | [2546416afd](https://bsd-hardware.info/?probe=2546416afd) | Apr 05, 2023 |
| HP            | Laptop 15-bw0xx             | [93ea83eef5](https://bsd-hardware.info/?probe=93ea83eef5) | Apr 03, 2023 |
| Lenovo        | G570 20079                  | [76cc1653c3](https://bsd-hardware.info/?probe=76cc1653c3) | Apr 03, 2023 |
| Lenovo        | ThinkBook 14-IML 20RV       | [48b0a1024e](https://bsd-hardware.info/?probe=48b0a1024e) | Apr 02, 2023 |
| ASUSTek       | X58C                        | [dad28a9d36](https://bsd-hardware.info/?probe=dad28a9d36) | Apr 01, 2023 |
| Fujitsu       | CELSIUS H920                | [e6300dc691](https://bsd-hardware.info/?probe=e6300dc691) | Mar 31, 2023 |
| DNS           | W9x0LU                      | [6539659387](https://bsd-hardware.info/?probe=6539659387) | Mar 31, 2023 |
| Lenovo        | ThinkPad X220 4290DK6       | [96c83a2846](https://bsd-hardware.info/?probe=96c83a2846) | Mar 31, 2023 |
| Intel         | Intel                       | [75e9733afd](https://bsd-hardware.info/?probe=75e9733afd) | Mar 30, 2023 |
| Toshiba       | Satellite L675D             | [0bf578daec](https://bsd-hardware.info/?probe=0bf578daec) | Mar 30, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [ff14982ad9](https://bsd-hardware.info/?probe=ff14982ad9) | Mar 29, 2023 |
| Dell          | Latitude 5590               | [7e87d436df](https://bsd-hardware.info/?probe=7e87d436df) | Mar 29, 2023 |
| Lenovo        | ThinkPad T540p 20BFS10W0... | [30c5fc2625](https://bsd-hardware.info/?probe=30c5fc2625) | Mar 29, 2023 |
| Irbis         | NB78                        | [471efbc788](https://bsd-hardware.info/?probe=471efbc788) | Mar 29, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [f4e450fed1](https://bsd-hardware.info/?probe=f4e450fed1) | Mar 29, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [dddf27cde4](https://bsd-hardware.info/?probe=dddf27cde4) | Mar 28, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [c2ba6aca7d](https://bsd-hardware.info/?probe=c2ba6aca7d) | Mar 28, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [fb4eec9c34](https://bsd-hardware.info/?probe=fb4eec9c34) | Mar 27, 2023 |
| HP            | Pavilion dv6                | [ce2cc6852d](https://bsd-hardware.info/?probe=ce2cc6852d) | Mar 27, 2023 |
| Dell          | Inspiron 7437               | [2c4de59558](https://bsd-hardware.info/?probe=2c4de59558) | Mar 27, 2023 |
| Lenovo        | IdeaPad S210 20256          | [2e22ee87c3](https://bsd-hardware.info/?probe=2e22ee87c3) | Mar 27, 2023 |
| Lenovo        | ThinkPad T430 2349G5P       | [9ea67d3893](https://bsd-hardware.info/?probe=9ea67d3893) | Mar 27, 2023 |
| Dell          | Latitude 5420               | [4e22bbc131](https://bsd-hardware.info/?probe=4e22bbc131) | Mar 26, 2023 |
| LG Electro... | E500-L.A2M4A2               | [8dab794233](https://bsd-hardware.info/?probe=8dab794233) | Mar 26, 2023 |
| Samsung       | R468/R418                   | [f620a5c6ec](https://bsd-hardware.info/?probe=f620a5c6ec) | Mar 25, 2023 |
| Lenovo        | ThinkPad X220 4291AN9       | [1646bb53ab](https://bsd-hardware.info/?probe=1646bb53ab) | Mar 25, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [7df625b1df](https://bsd-hardware.info/?probe=7df625b1df) | Mar 25, 2023 |
| Lenovo        | ThinkPad X230 Tablet 343... | [8e798ca6ef](https://bsd-hardware.info/?probe=8e798ca6ef) | Mar 25, 2023 |
| Lenovo        | ThinkPad W541 20EF000NUS    | [34b156c20c](https://bsd-hardware.info/?probe=34b156c20c) | Mar 24, 2023 |
| Dell          | Latitude 5500               | [8db518ef3d](https://bsd-hardware.info/?probe=8db518ef3d) | Mar 24, 2023 |
| Lenovo        | ThinkPad T61 7658CTO        | [f00e571f76](https://bsd-hardware.info/?probe=f00e571f76) | Mar 23, 2023 |
| Lenovo        | ThinkPad T430s 2356CV6      | [d9efc1e30b](https://bsd-hardware.info/?probe=d9efc1e30b) | Mar 22, 2023 |
| ASUSTek       | X71Vn                       | [6e96ea55ee](https://bsd-hardware.info/?probe=6e96ea55ee) | Mar 22, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [136a6641be](https://bsd-hardware.info/?probe=136a6641be) | Mar 21, 2023 |
| Lenovo        | ThinkPad X230 232578G       | [edf47cb2d4](https://bsd-hardware.info/?probe=edf47cb2d4) | Mar 21, 2023 |
| Lenovo        | ThinkPad T61 7659CA1        | [bba228ddc9](https://bsd-hardware.info/?probe=bba228ddc9) | Mar 20, 2023 |
| Lenovo        | G500 20236                  | [55dc82af1c](https://bsd-hardware.info/?probe=55dc82af1c) | Mar 20, 2023 |
| ASUSTek       | 1015PX                      | [d6c1199165](https://bsd-hardware.info/?probe=d6c1199165) | Mar 20, 2023 |
| Apple         | MacBookPro5,1               | [9e300b5797](https://bsd-hardware.info/?probe=9e300b5797) | Mar 19, 2023 |
| Toshiba       | Satellite P300              | [81b7ca608e](https://bsd-hardware.info/?probe=81b7ca608e) | Mar 19, 2023 |
| Lenovo        | ThinkPad T520 4242PN3       | [3ea33f0cad](https://bsd-hardware.info/?probe=3ea33f0cad) | Mar 19, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [e35600705f](https://bsd-hardware.info/?probe=e35600705f) | Mar 19, 2023 |
| Samsung       | R520/R522/R620              | [096d52b83d](https://bsd-hardware.info/?probe=096d52b83d) | Mar 18, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [be9a45f529](https://bsd-hardware.info/?probe=be9a45f529) | Mar 18, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [a365a5b411](https://bsd-hardware.info/?probe=a365a5b411) | Mar 18, 2023 |
| Apple         | MacBook4,1                  | [6f2790802d](https://bsd-hardware.info/?probe=6f2790802d) | Mar 18, 2023 |
| Fujitsu       | LIFEBOOK AH530              | [50a5ed6b41](https://bsd-hardware.info/?probe=50a5ed6b41) | Mar 18, 2023 |
| IGEL Techn... | M350C                       | [a04efafd2e](https://bsd-hardware.info/?probe=a04efafd2e) | Mar 18, 2023 |
| HP            | Pavilion dv5                | [113fe74799](https://bsd-hardware.info/?probe=113fe74799) | Mar 18, 2023 |
| HP            | EliteBook 850 G2            | [653dbe54a4](https://bsd-hardware.info/?probe=653dbe54a4) | Mar 18, 2023 |
| Lenovo        | ThinkPad T440p              | [575123c3ac](https://bsd-hardware.info/?probe=575123c3ac) | Mar 17, 2023 |
| Dell          | Inspiron 3442               | [cbb9f6bfbb](https://bsd-hardware.info/?probe=cbb9f6bfbb) | Mar 17, 2023 |
| Dell          | Latitude E5570              | [8b9aa95420](https://bsd-hardware.info/?probe=8b9aa95420) | Mar 17, 2023 |
| Toshiba       | Satellite L40               | [2297dcb7e7](https://bsd-hardware.info/?probe=2297dcb7e7) | Mar 17, 2023 |
| Dell          | Latitude E5570              | [937a7c9385](https://bsd-hardware.info/?probe=937a7c9385) | Mar 17, 2023 |
| Lenovo        | ThinkPad X201 36801T6       | [decaf0c347](https://bsd-hardware.info/?probe=decaf0c347) | Mar 17, 2023 |
| Lenovo        | ThinkPad X61s 7667WQS       | [f1351003d1](https://bsd-hardware.info/?probe=f1351003d1) | Mar 17, 2023 |
| Dell          | Inspiron 5557               | [ff199c6d21](https://bsd-hardware.info/?probe=ff199c6d21) | Mar 16, 2023 |
| HP            | Unknown                     | [0b79535c7f](https://bsd-hardware.info/?probe=0b79535c7f) | Mar 16, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | [564b1ccce1](https://bsd-hardware.info/?probe=564b1ccce1) | Mar 15, 2023 |
| Acer          | Aspire E5-571G              | [ca34dac813](https://bsd-hardware.info/?probe=ca34dac813) | Mar 15, 2023 |
| Samsung       | 275E4E/275E5E               | [dd4f7ef594](https://bsd-hardware.info/?probe=dd4f7ef594) | Mar 15, 2023 |
| HP            | Pavilion TS Sleekbook 14    | [d57e5b1b88](https://bsd-hardware.info/?probe=d57e5b1b88) | Mar 15, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [89a5ee25f9](https://bsd-hardware.info/?probe=89a5ee25f9) | Mar 14, 2023 |
| Acer          | TravelMate P249-G2-M        | [090f37a821](https://bsd-hardware.info/?probe=090f37a821) | Mar 14, 2023 |
| Dell          | Latitude D630               | [da1fa73418](https://bsd-hardware.info/?probe=da1fa73418) | Mar 14, 2023 |
| HP            | Laptop 14-bs0xx             | [cd76713b75](https://bsd-hardware.info/?probe=cd76713b75) | Mar 14, 2023 |
| Dynabook E... | Satellite Pro E10-G-101     | [c58a37ef03](https://bsd-hardware.info/?probe=c58a37ef03) | Mar 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3448A... | [eaaf0fc8c7](https://bsd-hardware.info/?probe=eaaf0fc8c7) | Mar 14, 2023 |
| Toshiba       | Satellite L50-B             | [7052b38ba8](https://bsd-hardware.info/?probe=7052b38ba8) | Mar 14, 2023 |
| Lenovo        | ThinkPad L450 20DSS1S402    | [b4893ae18f](https://bsd-hardware.info/?probe=b4893ae18f) | Mar 14, 2023 |
| Toshiba       | Satellite A200              | [c49985d00b](https://bsd-hardware.info/?probe=c49985d00b) | Mar 13, 2023 |
| Lenovo        | ThinkPad P51 20HH001RMX     | [d9d7368322](https://bsd-hardware.info/?probe=d9d7368322) | Mar 13, 2023 |
| Samsung       | R468/R418                   | [af44a29d38](https://bsd-hardware.info/?probe=af44a29d38) | Mar 13, 2023 |
| Dell          | Inspiron 7520               | [8b259d99ec](https://bsd-hardware.info/?probe=8b259d99ec) | Mar 13, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | [5ce3dfe4a2](https://bsd-hardware.info/?probe=5ce3dfe4a2) | Mar 13, 2023 |
| Lenovo        | ThinkPad X200 74591P0       | [882cc7fc62](https://bsd-hardware.info/?probe=882cc7fc62) | Mar 13, 2023 |
| ASUSTek       | G74Sx                       | [6b7cf8fcac](https://bsd-hardware.info/?probe=6b7cf8fcac) | Mar 13, 2023 |
| Toshiba       | Satellite C845              | [0b680543b7](https://bsd-hardware.info/?probe=0b680543b7) | Mar 13, 2023 |
| Sony          | VGN-FZ19VN                  | [73809d943a](https://bsd-hardware.info/?probe=73809d943a) | Mar 13, 2023 |
| Fujitsu       | LIFEBOOK E736               | [1040a34321](https://bsd-hardware.info/?probe=1040a34321) | Mar 12, 2023 |
| HP            | Laptop 14-bs1xx             | [99446c8dd0](https://bsd-hardware.info/?probe=99446c8dd0) | Mar 12, 2023 |
| Lenovo        | ThinkPad X200 2024AY7       | [bb432faf36](https://bsd-hardware.info/?probe=bb432faf36) | Mar 12, 2023 |
| Lenovo        | ZIUS6                       | [d387825f01](https://bsd-hardware.info/?probe=d387825f01) | Mar 12, 2023 |
| Dell          | Latitude E6330              | [5c60cd3d04](https://bsd-hardware.info/?probe=5c60cd3d04) | Mar 12, 2023 |
| Lenovo        | ThinkPad T440p              | [6d372db804](https://bsd-hardware.info/?probe=6d372db804) | Mar 12, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | [5bcd236c4a](https://bsd-hardware.info/?probe=5bcd236c4a) | Mar 12, 2023 |
| Acer          | Nitro AN515-54              | [6e97a003ec](https://bsd-hardware.info/?probe=6e97a003ec) | Mar 12, 2023 |
| Acer          | Swift SF314-42              | [aa89c48cb7](https://bsd-hardware.info/?probe=aa89c48cb7) | Mar 12, 2023 |
| HP            | Laptop 15-bs1xx             | [1df045ffd0](https://bsd-hardware.info/?probe=1df045ffd0) | Mar 11, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2BR0... | [56fa0d4656](https://bsd-hardware.info/?probe=56fa0d4656) | Mar 11, 2023 |
| Dell          | Latitude E5450              | [4bb2040221](https://bsd-hardware.info/?probe=4bb2040221) | Mar 11, 2023 |
| Lenovo        | ThinkPad L590 20Q7U04602    | [64a11e18da](https://bsd-hardware.info/?probe=64a11e18da) | Mar 11, 2023 |
| ASUSTek       | 1201N                       | [5dc595eb79](https://bsd-hardware.info/?probe=5dc595eb79) | Mar 05, 2023 |
| ASUSTek       | 1201N                       | [daa787f637](https://bsd-hardware.info/?probe=daa787f637) | Mar 05, 2023 |
| HP            | EliteBook 2730p             | [3c404c9d20](https://bsd-hardware.info/?probe=3c404c9d20) | Mar 05, 2023 |
| Dell          | Inspiron 15 3515            | [b480a98b22](https://bsd-hardware.info/?probe=b480a98b22) | Feb 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [95c66df5a4](https://bsd-hardware.info/?probe=95c66df5a4) | Feb 24, 2023 |
| Plaisio       | Turbo X                     | [e0a8a02bb9](https://bsd-hardware.info/?probe=e0a8a02bb9) | Feb 23, 2023 |
| Lenovo        | ThinkPad T520 4243F39       | [d8ba5b3157](https://bsd-hardware.info/?probe=d8ba5b3157) | Feb 19, 2023 |
| Lenovo        | ThinkPad T520 4243F39       | [820596f359](https://bsd-hardware.info/?probe=820596f359) | Feb 18, 2023 |
| Lenovo        | ThinkPad T430u 33522D5      | [d5bbbb8cbe](https://bsd-hardware.info/?probe=d5bbbb8cbe) | Feb 17, 2023 |
| Lenovo        | ThinkPad T520 4243F39       | [9137c7933c](https://bsd-hardware.info/?probe=9137c7933c) | Feb 13, 2023 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 222       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 220       | 99.1%   |
| JWM          | 1         | 0.45%   |
| GNOME        | 1         | 0.45%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 222       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| SLiM | 222       | 99.55%  |
| SDDM | 1         | 0.45%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 105       | 47.09%  |
| fr_FR   | 26        | 11.66%  |
| ru_RU   | 19        | 8.52%   |
| de_DE   | 16        | 7.17%   |
| Unknown | 11        | 4.93%   |
| es_ES   | 9         | 4.04%   |
| pl_PL   | 8         | 3.59%   |
| it_IT   | 7         | 3.14%   |
| pt_BR   | 5         | 2.24%   |
| nl_NL   | 4         | 1.79%   |
| zh_CN   | 3         | 1.35%   |
| fi_FI   | 2         | 0.9%    |
| tr_TR   | 1         | 0.45%   |
| pt_PT   | 1         | 0.45%   |
| pt      | 1         | 0.45%   |
| ko_KR   | 1         | 0.45%   |
| jp_JP   | 1         | 0.45%   |
| fi_DK   | 1         | 0.45%   |
| en      | 1         | 0.45%   |
| C       | 1         | 0.45%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 222       | 100%    |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Cd9660 | 112       | 50.45%  |
| Zfs    | 110       | 49.55%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 222       | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 77        | 34.68%  |
| Hewlett-Packard     | 31        | 13.96%  |
| Dell                | 24        | 10.81%  |
| ASUSTek Computer    | 16        | 7.21%   |
| Acer                | 12        | 5.41%   |
| Samsung Electronics | 10        | 4.5%    |
| Apple               | 10        | 4.5%    |
| Toshiba             | 9         | 4.05%   |
| Fujitsu             | 5         | 2.25%   |
| Sony                | 3         | 1.35%   |
| Google              | 3         | 1.35%   |
| Panasonic           | 2         | 0.9%    |
| Packard Bell        | 2         | 0.9%    |
| Intel               | 2         | 0.9%    |
| TUXEDO              | 1         | 0.45%   |
| Timi                | 1         | 0.45%   |
| Plaisio             | 1         | 0.45%   |
| OEGStone            | 1         | 0.45%   |
| NVN-ED01            | 1         | 0.45%   |
| MSI                 | 1         | 0.45%   |
| Medion              | 1         | 0.45%   |
| LG Electronics      | 1         | 0.45%   |
| Irbis               | 1         | 0.45%   |
| IGEL Technology     | 1         | 0.45%   |
| HUAWEI              | 1         | 0.45%   |
| Gateway             | 1         | 0.45%   |
| eMachines           | 1         | 0.45%   |
| Dynabook Europe     | 1         | 0.45%   |
| DNS                 | 1         | 0.45%   |
| Compaq              | 1         | 0.45%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                            | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Unknown                         | 4         | 1.8%    |
| HP Laptop 14-bs0xx              | 2         | 0.9%    |
| Apple MacBookPro9,2             | 2         | 0.9%    |
| Apple MacBook5,1                | 2         | 0.9%    |
| TUXEDO Aura 15 Gen1             | 1         | 0.45%   |
| Toshiba Satellite P300          | 1         | 0.45%   |
| Toshiba Satellite L675D         | 1         | 0.45%   |
| Toshiba Satellite L50-B         | 1         | 0.45%   |
| Toshiba Satellite L40           | 1         | 0.45%   |
| Toshiba Satellite C845          | 1         | 0.45%   |
| Toshiba Satellite A200          | 1         | 0.45%   |
| Toshiba QOSMIO X775             | 1         | 0.45%   |
| Toshiba PORTEGE R700            | 1         | 0.45%   |
| Timi TM1701                     | 1         | 0.45%   |
| Sony VPCEG15FB                  | 1         | 0.45%   |
| Sony VGN-FZ19VN                 | 1         | 0.45%   |
| Sony SVF14A15CBB                | 1         | 0.45%   |
| Samsung RC530/RC730             | 1         | 0.45%   |
| Samsung R530/R730/R540          | 1         | 0.45%   |
| Samsung R520/R522/R620          | 1         | 0.45%   |
| Samsung R510/P510               | 1         | 0.45%   |
| Samsung R468/R418               | 1         | 0.45%   |
| Samsung N150P/N210P/N220P       | 1         | 0.45%   |
| Samsung 370E4K                  | 1         | 0.45%   |
| Samsung 305E4A/305E5A/305E7A    | 1         | 0.45%   |
| Samsung 275E4E/275E5E           | 1         | 0.45%   |
| Samsung 270E5J/2570EJ           | 1         | 0.45%   |
| Plaisio Turbo X                 | 1         | 0.45%   |
| Panasonic CF-NX1GDHYS           | 1         | 0.45%   |
| Panasonic CF-52PGNBX2M          | 1         | 0.45%   |
| Packard Bell EasyNote LJ65      | 1         | 0.45%   |
| Packard Bell DOT SE             | 1         | 0.45%   |
| OEGStone doceo 510              | 1         | 0.45%   |
| MSI GE63 Raider RGB 8RE         | 1         | 0.45%   |
| Medion E15302                   | 1         | 0.45%   |
| LG E500-L.A2M4A2                | 1         | 0.45%   |
| Lenovo ZIUS6                    | 1         | 0.45%   |
| Lenovo Z50-70 20354             | 1         | 0.45%   |
| Lenovo Yoga Slim 7 14ITL05 82A3 | 1         | 0.45%   |
| Lenovo Yoga 2 Pro 20266         | 1         | 0.45%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 52        | 23.42%  |
| Lenovo IdeaPad         | 13        | 5.86%   |
| Dell Latitude          | 13        | 5.86%   |
| HP Pavilion            | 9         | 4.05%   |
| Dell Inspiron          | 8         | 3.6%    |
| HP Laptop              | 7         | 3.15%   |
| Acer Aspire            | 7         | 3.15%   |
| Toshiba Satellite      | 6         | 2.7%    |
| HP EliteBook           | 4         | 1.8%    |
| HP Compaq              | 4         | 1.8%    |
| Unknown                | 4         | 1.8%    |
| Fujitsu LIFEBOOK       | 3         | 1.35%   |
| ASUS VivoBook          | 3         | 1.35%   |
| Apple MacBook5         | 3         | 1.35%   |
| Lenovo Yoga            | 2         | 0.9%    |
| Lenovo Legion          | 2         | 0.9%    |
| Apple MacBookPro9      | 2         | 0.9%    |
| Acer TravelMate        | 2         | 0.9%    |
| TUXEDO Aura            | 1         | 0.45%   |
| Toshiba QOSMIO         | 1         | 0.45%   |
| Toshiba PORTEGE        | 1         | 0.45%   |
| Timi TM1701            | 1         | 0.45%   |
| Sony VPCEG15FB         | 1         | 0.45%   |
| Sony VGN-FZ19VN        | 1         | 0.45%   |
| Sony SVF14A15CBB       | 1         | 0.45%   |
| Samsung RC530          | 1         | 0.45%   |
| Samsung R530           | 1         | 0.45%   |
| Samsung R520           | 1         | 0.45%   |
| Samsung R510           | 1         | 0.45%   |
| Samsung R468           | 1         | 0.45%   |
| Samsung N150P          | 1         | 0.45%   |
| Samsung 370E4K         | 1         | 0.45%   |
| Samsung 305E4A         | 1         | 0.45%   |
| Samsung 275E4E         | 1         | 0.45%   |
| Samsung 270E5J         | 1         | 0.45%   |
| Plaisio Turbo          | 1         | 0.45%   |
| Panasonic CF-NX1GDHYS  | 1         | 0.45%   |
| Panasonic CF-52PGNBX2M | 1         | 0.45%   |
| Packard Bell EasyNote  | 1         | 0.45%   |
| Packard Bell DOT       | 1         | 0.45%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2011 | 24        | 10.81%  |
| 2013 | 19        | 8.56%   |
| 2012 | 17        | 7.66%   |
| 2022 | 16        | 7.21%   |
| 2020 | 16        | 7.21%   |
| 2010 | 16        | 7.21%   |
| 2019 | 14        | 6.31%   |
| 2016 | 13        | 5.86%   |
| 2009 | 13        | 5.86%   |
| 2017 | 12        | 5.41%   |
| 2015 | 11        | 4.95%   |
| 2008 | 11        | 4.95%   |
| 2021 | 10        | 4.5%    |
| 2018 | 10        | 4.5%    |
| 2014 | 9         | 4.05%   |
| 2007 | 6         | 2.7%    |
| 2023 | 3         | 1.35%   |
| 2006 | 2         | 0.9%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 222       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 217       | 97.75%  |
| Yes  | 5         | 2.25%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 78        | 35.14%  |
| 4.01-8.0    | 70        | 31.53%  |
| 16.01-24.0  | 39        | 17.57%  |
| 2.01-3.0    | 18        | 8.11%   |
| 32.01-64.0  | 8         | 3.6%    |
| 3.01-4.0    | 8         | 3.6%    |
| 64.01-256.0 | 1         | 0.45%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 143       | 64.41%  |
| 0.51-1.0 | 57        | 25.68%  |
| 1.01-2.0 | 18        | 8.11%   |
| 2.01-3.0 | 4         | 1.8%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 161       | 71.88%  |
| 2      | 39        | 17.41%  |
| 0      | 19        | 8.48%   |
| 3      | 5         | 2.23%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 144       | 64.86%  |
| Yes       | 78        | 35.14%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 196       | 88.29%  |
| No        | 26        | 11.71%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 214       | 96.4%   |
| No        | 8         | 3.6%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 156       | 70.27%  |
| No        | 66        | 29.73%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country             | Notebooks | Percent |
|---------------------|-----------|---------|
| USA                 | 33        | 14.86%  |
| Russia              | 20        | 9.01%   |
| Germany             | 20        | 9.01%   |
| Poland              | 15        | 6.76%   |
| Brazil              | 14        | 6.31%   |
| Italy               | 11        | 4.95%   |
| UK                  | 10        | 4.5%    |
| Spain               | 8         | 3.6%    |
| Indonesia           | 8         | 3.6%    |
| France              | 6         | 2.7%    |
| China               | 6         | 2.7%    |
| Turkey              | 5         | 2.25%   |
| Netherlands         | 5         | 2.25%   |
| India               | 5         | 2.25%   |
| Canada              | 5         | 2.25%   |
| Romania             | 4         | 1.8%    |
| Australia           | 4         | 1.8%    |
| Mexico              | 3         | 1.35%   |
| Hungary             | 3         | 1.35%   |
| Finland             | 3         | 1.35%   |
| Ukraine             | 2         | 0.9%    |
| Switzerland         | 2         | 0.9%    |
| South Korea         | 2         | 0.9%    |
| Portugal            | 2         | 0.9%    |
| Lithuania           | 2         | 0.9%    |
| Israel              | 2         | 0.9%    |
| Colombia            | 2         | 0.9%    |
| Bulgaria            | 2         | 0.9%    |
| Trinidad and Tobago | 1         | 0.45%   |
| Syria               | 1         | 0.45%   |
| Sweden              | 1         | 0.45%   |
| Slovenia            | 1         | 0.45%   |
| Slovakia            | 1         | 0.45%   |
| Philippines         | 1         | 0.45%   |
| Kazakhstan          | 1         | 0.45%   |
| Jamaica             | 1         | 0.45%   |
| Ireland             | 1         | 0.45%   |
| Greece              | 1         | 0.45%   |
| Estonia             | 1         | 0.45%   |
| Czechia             | 1         | 0.45%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City          | Notebooks | Percent |
|---------------|-----------|---------|
| Berlin        | 5         | 2.22%   |
| Sao Paulo     | 4         | 1.78%   |
| Wroclaw       | 3         | 1.33%   |
| St Petersburg | 3         | 1.33%   |
| Moscow        | 3         | 1.33%   |
| Warsaw        | 2         | 0.89%   |
| Vilnius       | 2         | 0.89%   |
| Valencia      | 2         | 0.89%   |
| Sydney        | 2         | 0.89%   |
| Shenzhen      | 2         | 0.89%   |
| Peterborough  | 2         | 0.89%   |
| Montreal      | 2         | 0.89%   |
| Milan         | 2         | 0.89%   |
| Lisbon        | 2         | 0.89%   |
| Irkutsk       | 2         | 0.89%   |
| Budapest      | 2         | 0.89%   |
| Ankara        | 2         | 0.89%   |
| Zurich        | 1         | 0.44%   |
| Zele          | 1         | 0.44%   |
| Zarautz       | 1         | 0.44%   |
| Yuseong-gu    | 1         | 0.44%   |
| Yogyakarta    | 1         | 0.44%   |
| Yeosu         | 1         | 0.44%   |
| Yekaterinburg | 1         | 0.44%   |
| Woodbridge    | 1         | 0.44%   |
| Whitby        | 1         | 0.44%   |
| West Plains   | 1         | 0.44%   |
| Wausau        | 1         | 0.44%   |
| Vitória      | 1         | 0.44%   |
| Vitebsk       | 1         | 0.44%   |
| Villemomble   | 1         | 0.44%   |
| Villefontaine | 1         | 0.44%   |
| Victoria      | 1         | 0.44%   |
| Valga         | 1         | 0.44%   |
| Ulyanovsk     | 1         | 0.44%   |
| Ufa           | 1         | 0.44%   |
| Twinsburg     | 1         | 0.44%   |
| Tver          | 1         | 0.44%   |
| Trindade      | 1         | 0.44%   |
| Tomasikovo    | 1         | 0.44%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 38        | 41     | 15.32%  |
| WDC                 | 23        | 24     | 9.27%   |
| Toshiba             | 23        | 25     | 9.27%   |
| Seagate             | 21        | 22     | 8.47%   |
| SanDisk             | 17        | 17     | 6.85%   |
| Kingston            | 16        | 16     | 6.45%   |
| Hitachi             | 15        | 15     | 6.05%   |
| Crucial             | 12        | 14     | 4.84%   |
| HGST                | 7         | 10     | 2.82%   |
| A-DATA Technology   | 7         | 7      | 2.82%   |
| Intel               | 6         | 6      | 2.42%   |
| SK hynix            | 5         | 5      | 2.02%   |
| Micron Technology   | 5         | 5      | 2.02%   |
| Transcend           | 3         | 3      | 1.21%   |
| SPCC                | 3         | 3      | 1.21%   |
| GOODRAM             | 3         | 3      | 1.21%   |
| Fujitsu             | 3         | 3      | 1.21%   |
| China               | 3         | 3      | 1.21%   |
| Apple               | 3         | 3      | 1.21%   |
| Patriot             | 2         | 2      | 0.81%   |
| OCZ                 | 2         | 2      | 0.81%   |
| Intenso             | 2         | 2      | 0.81%   |
| Gigabyte Technology | 2         | 2      | 0.81%   |
| Dogfish             | 2         | 2      | 0.81%   |
| BHT                 | 2         | 2      | 0.81%   |
| Verbatim            | 1         | 1      | 0.4%    |
| Vaseky              | 1         | 1      | 0.4%    |
| V-GeN               | 1         | 1      | 0.4%    |
| UMIS                | 1         | 1      | 0.4%    |
| Team                | 1         | 1      | 0.4%    |
| SSSTC               | 1         | 1      | 0.4%    |
| Silicon Motion      | 1         | 1      | 0.4%    |
| SemsoTai            | 1         | 1      | 0.4%    |
| PNY                 | 1         | 1      | 0.4%    |
| Plextor             | 1         | 1      | 0.4%    |
| Phison              | 1         | 1      | 0.4%    |
| Netac               | 1         | 1      | 0.4%    |
| MidasForce          | 1         | 1      | 0.4%    |
| Maxtor              | 1         | 1      | 0.4%    |
| LITEON              | 1         | 1      | 0.4%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB          | 4         | 1.59%   |
| Crucial CT480BX500SSD1 480GB       | 4         | 1.59%   |
| Toshiba MQ01ABF050 500GB           | 3         | 1.2%    |
| Kingston SA400S37240G 240GB        | 3         | 1.2%    |
| WDC WD2500BEVT-22ZCT0 250GB        | 2         | 0.8%    |
| Toshiba MQ01ABD100 1TB             | 2         | 0.8%    |
| Seagate ST9500325AS 500GB          | 2         | 0.8%    |
| Seagate ST9250410AS 250GB          | 2         | 0.8%    |
| Seagate ST1000LM024 HN-M101MBB 1TB | 2         | 0.8%    |
| SanDisk SSD PLUS 120GB             | 2         | 0.8%    |
| Samsung MZVLB256HAHQ-000H1 256GB   | 2         | 0.8%    |
| Samsung HM321HI 320GB              | 2         | 0.8%    |
| Samsung HM160HI 160GB              | 2         | 0.8%    |
| Micron 1100 SATA 256GB             | 2         | 0.8%    |
| Kingston SV300S37A60G 64GB         | 2         | 0.8%    |
| Kingston SV300S37A240G 240GB       | 2         | 0.8%    |
| Hitachi HTS545050B9A300 500GB      | 2         | 0.8%    |
| Hitachi HTS545032B9A300 320GB      | 2         | 0.8%    |
| Hitachi HTS542525K9A300 250GB      | 2         | 0.8%    |
| HGST HTS725050A7E630 500GB         | 2         | 0.8%    |
| HGST HTS545050A7E380 500GB         | 2         | 0.8%    |
| Gigabyte GP-GSTFS31120GNTD 120GB   | 2         | 0.8%    |
| Crucial CT120BX500SSD1 120GB       | 2         | 0.8%    |
| WDC WDS500G2B0B-00YS70 500GB       | 1         | 0.4%    |
| WDC WDS240G2G0A-00JH30 240GB       | 1         | 0.4%    |
| WDC WDS120G2G0A-00JH30 120GB       | 1         | 0.4%    |
| WDC WDS120G1G0A-00SS50 120GB       | 1         | 0.4%    |
| WDC WDS100T2G0A-00JH30 1TB         | 1         | 0.4%    |
| WDC WD5000LPVX-22V0TT0 500GB       | 1         | 0.4%    |
| WDC WD5000LPCX-60VHAT0 500GB       | 1         | 0.4%    |
| WDC WD5000LPCX-24VHAT0 500GB       | 1         | 0.4%    |
| WDC WD3200BPVT-80ZEST0 320GB       | 1         | 0.4%    |
| WDC WD3200BPVT-22JJ5T0 320GB       | 1         | 0.4%    |
| WDC WD3200BEVT-60ZCT1 320GB        | 1         | 0.4%    |
| WDC WD30PURZ-85AKKY0 3TB           | 1         | 0.4%    |
| WDC WD1600BEVT-60ZCT0 160GB        | 1         | 0.4%    |
| WDC WD1600BEVS-22VAT0 160GB        | 1         | 0.4%    |
| WDC WD10SPZX-00Z10T0 1TB           | 1         | 0.4%    |
| WDC WD10JPVX-80JC3T0 1TB           | 1         | 0.4%    |
| WDC WD10JPVX-75JC3T0 1TB           | 1         | 0.4%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 21        | 23     | 23.33%  |
| Seagate             | 21        | 22     | 23.33%  |
| WDC                 | 15        | 15     | 16.67%  |
| Hitachi             | 15        | 15     | 16.67%  |
| HGST                | 7         | 10     | 7.78%   |
| Samsung Electronics | 6         | 7      | 6.67%   |
| Fujitsu             | 3         | 3      | 3.33%   |
| Maxtor              | 1         | 1      | 1.11%   |
| Apple               | 1         | 1      | 1.11%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 17        | 17     | 13.93%  |
| Samsung Electronics | 17        | 18     | 13.93%  |
| Kingston            | 15        | 15     | 12.3%   |
| Crucial             | 11        | 13     | 9.02%   |
| Intel               | 5         | 5      | 4.1%    |
| A-DATA Technology   | 5         | 5      | 4.1%    |
| WDC                 | 4         | 5      | 3.28%   |
| SPCC                | 3         | 3      | 2.46%   |
| Micron Technology   | 3         | 3      | 2.46%   |
| GOODRAM             | 3         | 3      | 2.46%   |
| China               | 3         | 3      | 2.46%   |
| Transcend           | 2         | 2      | 1.64%   |
| Patriot             | 2         | 2      | 1.64%   |
| OCZ                 | 2         | 2      | 1.64%   |
| Intenso             | 2         | 2      | 1.64%   |
| Gigabyte Technology | 2         | 2      | 1.64%   |
| Dogfish             | 2         | 2      | 1.64%   |
| BHT                 | 2         | 2      | 1.64%   |
| Apple               | 2         | 2      | 1.64%   |
| Verbatim            | 1         | 1      | 0.82%   |
| Vaseky              | 1         | 1      | 0.82%   |
| V-GeN               | 1         | 1      | 0.82%   |
| Toshiba             | 1         | 1      | 0.82%   |
| Team                | 1         | 1      | 0.82%   |
| SSSTC               | 1         | 1      | 0.82%   |
| SK hynix            | 1         | 1      | 0.82%   |
| SemsoTai            | 1         | 1      | 0.82%   |
| PNY                 | 1         | 1      | 0.82%   |
| Plextor             | 1         | 1      | 0.82%   |
| Netac               | 1         | 1      | 0.82%   |
| MidasForce          | 1         | 1      | 0.82%   |
| LITEON              | 1         | 1      | 0.82%   |
| KingSpec            | 1         | 1      | 0.82%   |
| Kingmax             | 1         | 1      | 0.82%   |
| Hewlett-Packard     | 1         | 1      | 0.82%   |
| Goldenfir           | 1         | 1      | 0.82%   |
| faspeed             | 1         | 1      | 0.82%   |
| Biostar             | 1         | 1      | 0.82%   |
| Apacer              | 1         | 1      | 0.82%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 111       | 126    | 48.05%  |
| HDD  | 86        | 97     | 37.23%  |
| NVMe | 34        | 37     | 14.72%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 177       | 223    | 83.89%  |
| NVMe | 34        | 37     | 16.11%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 159       | 187    | 84.13%  |
| 0.51-1.0   | 28        | 34     | 14.81%  |
| 2.01-3.0   | 1         | 1      | 0.53%   |
| 1.01-2.0   | 1         | 1      | 0.53%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 105       | 46.88%  |
| 101-250    | 40        | 17.86%  |
| 51-100     | 32        | 14.29%  |
| 251-500    | 30        | 13.39%  |
| 21-50      | 8         | 3.57%   |
| 501-1000   | 8         | 3.57%   |
| Unknown    | 1         | 0.45%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 219       | 98.65%  |
| 21-50   | 1         | 0.45%   |
| 101-250 | 1         | 0.45%   |
| Unknown | 1         | 0.45%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB           | 2         | 2      | 3.92%   |
| Hitachi HTS542525K9A300 250GB       | 2         | 2      | 3.92%   |
| WDC WDS240G2G0A-00JH30 240GB        | 1         | 1      | 1.96%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 1         | 1      | 1.96%   |
| WDC WD3200BPVT-80ZEST0 320GB        | 1         | 1      | 1.96%   |
| WDC WD30PURZ-85AKKY0 3TB            | 1         | 1      | 1.96%   |
| WDC WD2500BEVT-22ZCT0 250GB         | 1         | 1      | 1.96%   |
| WDC WD10JPVX-60JC3T1 1TB            | 1         | 1      | 1.96%   |
| Toshiba MQ01ABF050 500GB            | 1         | 1      | 1.96%   |
| Toshiba MQ01ABD100 1TB              | 1         | 1      | 1.96%   |
| Toshiba MQ01ABD050 500GB            | 1         | 1      | 1.96%   |
| Toshiba MQ01ABD032 320GB            | 1         | 1      | 1.96%   |
| Toshiba MK5065GSX 500GB             | 1         | 1      | 1.96%   |
| Toshiba MK5059GSXP 500GB            | 1         | 1      | 1.96%   |
| Toshiba MK3261GSY 320GB             | 1         | 1      | 1.96%   |
| Toshiba MK1646GSX 160GB             | 1         | 1      | 1.96%   |
| Toshiba MK1229GSG 120GB             | 1         | 1      | 1.96%   |
| SSSTC CVB-8D128-HP 128GB            | 1         | 1      | 1.96%   |
| SK hynix SC210 mSATA 256GB          | 1         | 1      | 1.96%   |
| Seagate ST9250410AS 250GB           | 1         | 1      | 1.96%   |
| Seagate ST9160827AS 160GB           | 1         | 1      | 1.96%   |
| Seagate ST9160314AS 160GB           | 1         | 1      | 1.96%   |
| Seagate ST750LM022 HN-M750MBB 752GB | 1         | 1      | 1.96%   |
| Seagate ST500LM000-SSHD-8GB         | 1         | 1      | 1.96%   |
| Seagate ST500LM000-1EJ162-SSHD-8GB  | 1         | 1      | 1.96%   |
| Seagate ST500LM000-1EJ162 500GB     | 1         | 1      | 1.96%   |
| Seagate ST320LT020-9YG142 320GB     | 1         | 1      | 1.96%   |
| Seagate ST320LT012-9WS14C 320GB     | 1         | 2      | 1.96%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 1         | 1      | 1.96%   |
| Samsung Electronics HM321HI 320GB   | 1         | 1      | 1.96%   |
| Samsung Electronics HM160HI 160GB   | 1         | 1      | 1.96%   |
| OCZ AGILITY3 120GB                  | 1         | 1      | 1.96%   |
| Kingston SV300S37A60G 64GB          | 1         | 1      | 1.96%   |
| Intel SSDSC2BF180A4L 180GB          | 1         | 1      | 1.96%   |
| Hitachi HTS727550A9E364 500GB       | 1         | 1      | 1.96%   |
| Hitachi HTS721060G9SA00 64GB        | 1         | 1      | 1.96%   |
| Hitachi HTS547575A9E384 752GB       | 1         | 1      | 1.96%   |
| Hitachi HTS547550A9E384 500GB       | 1         | 1      | 1.96%   |
| Hitachi HTS545050B9A300 500GB       | 1         | 1      | 1.96%   |
| Hitachi HTS545050A7E380 500GB       | 1         | 1      | 1.96%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 12        | 13     | 23.53%  |
| Hitachi             | 10        | 10     | 19.61%  |
| Toshiba             | 9         | 9      | 17.65%  |
| WDC                 | 6         | 6      | 11.76%  |
| HGST                | 4         | 5      | 7.84%   |
| Samsung Electronics | 2         | 2      | 3.92%   |
| Crucial             | 2         | 3      | 3.92%   |
| SSSTC               | 1         | 1      | 1.96%   |
| SK hynix            | 1         | 1      | 1.96%   |
| OCZ                 | 1         | 1      | 1.96%   |
| Kingston            | 1         | 1      | 1.96%   |
| Intel               | 1         | 1      | 1.96%   |
| Apple               | 1         | 1      | 1.96%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 12        | 13     | 28.57%  |
| Hitachi             | 10        | 10     | 23.81%  |
| Toshiba             | 9         | 9      | 21.43%  |
| WDC                 | 5         | 5      | 11.9%   |
| HGST                | 4         | 5      | 9.52%   |
| Samsung Electronics | 2         | 2      | 4.76%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 40        | 44     | 81.63%  |
| SSD  | 9         | 10     | 18.37%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart_bsd/drive_failed.svg)


| Model                             | Notebooks | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Samsung Electronics HM500JJ 500GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart_bsd/drive_status.svg)


| Status  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Works   | 167       | 205    | 76.96%  |
| Malfunc | 49        | 54     | 22.58%  |
| Failed  | 1         | 1      | 0.46%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 178       | 74.48%  |
| AMD                                     | 17        | 7.11%   |
| Samsung Electronics                     | 14        | 5.86%   |
| SanDisk                                 | 7         | 2.93%   |
| Nvidia                                  | 6         | 2.51%   |
| SK hynix                                | 4         | 1.67%   |
| Silicon Motion                          | 3         | 1.26%   |
| Micron Technology                       | 2         | 0.84%   |
| Toshiba                                 | 1         | 0.42%   |
| Silicon Integrated Systems [SiS]        | 1         | 0.42%   |
| Shenzhen Unionmemory Information System | 1         | 0.42%   |
| Phison Electronics                      | 1         | 0.42%   |
| Micron/Crucial Technology               | 1         | 0.42%   |
| MAXIO Technology (Hangzhou)             | 1         | 0.42%   |
| Kingston Technology Company             | 1         | 0.42%   |
| ADATA Technology                        | 1         | 0.42%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 26        | 10.08%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 20        | 7.75%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 19        | 7.36%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 17        | 6.59%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 14        | 5.43%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 13        | 5.04%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 10        | 3.88%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 8         | 3.1%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 8         | 3.1%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 8         | 3.1%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 7         | 2.71%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 7         | 2.71%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 7         | 2.71%   |
| Nvidia MCP79 AHCI Controller                                                     | 5         | 1.94%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 5         | 1.94%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 5         | 1.94%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 4         | 1.55%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 4         | 1.55%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 4         | 1.55%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 4         | 1.55%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 3         | 1.16%   |
| Intel Comet Lake SATA AHCI Controller                                            | 3         | 1.16%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 3         | 1.16%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 2         | 0.78%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                            | 2         | 0.78%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                            | 2         | 0.78%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2         | 0.78%   |
| Intel Volume Management Device NVMe RAID Controller                              | 2         | 0.78%   |
| Intel Tiger Lake-LP SATA Controller                                              | 2         | 0.78%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 2         | 0.78%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                 | 2         | 0.78%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 2         | 0.78%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 2         | 0.78%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 2         | 0.78%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 2         | 0.78%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 2         | 0.78%   |
| Toshiba XG6 NVMe SSD Controller                                                  | 1         | 0.39%   |
| SK hynix PC601 NVMe Solid State Drive                                            | 1         | 0.39%   |
| SK hynix BC511 NVMe SSD                                                          | 1         | 0.39%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 0.39%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 186       | 74.7%   |
| NVMe | 33        | 13.25%  |
| IDE  | 21        | 8.43%   |
| RAID | 9         | 3.61%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 200       | 90.09%  |
| AMD    | 22        | 9.91%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel Core i5-6300U CPU @ 2.40GHz      | 7         | 3.15%   |
| Intel CPU Version                      | 6         | 2.7%    |
| Intel Core i5-2520M CPU @ 2.50GHz      | 6         | 2.7%    |
| Intel Core i7-8550U CPU @ 1.80GHz      | 5         | 2.25%   |
| Intel Celeron CPU N3060 @ 1.60GHz      | 5         | 2.25%   |
| Intel Core i5-5200U CPU @ 2.20GHz      | 4         | 1.8%    |
| Intel Core 2 Duo CPU P7350 @ 2.00GHz   | 4         | 1.8%    |
| Intel Core i7-5500U CPU @ 2.40GHz      | 3         | 1.35%   |
| Intel Core i7-3520M CPU @ 2.90GHz      | 3         | 1.35%   |
| Intel Core i5-7300U CPU @ 2.60GHz      | 3         | 1.35%   |
| Intel Core i5-7200U CPU @ 2.50GHz      | 3         | 1.35%   |
| Intel Core i5-4210U CPU @ 1.70GHz      | 3         | 1.35%   |
| Intel Core i5-3337U CPU @ 1.80GHz      | 3         | 1.35%   |
| Intel Core i5-3320M CPU @ 2.60GHz      | 3         | 1.35%   |
| Intel Core i5-3210M CPU @ 2.50GHz      | 3         | 1.35%   |
| Intel Core i5-10210U CPU @ 1.60GHz     | 3         | 1.35%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz   | 3         | 1.35%   |
| Intel Celeron CPU N2840 @ 2.16GHz      | 3         | 1.35%   |
| Intel Atom CPU N450 @ 1.66GHz          | 3         | 1.35%   |
| Intel Pentium CPU P6200 @ 2.13GHz      | 2         | 0.9%    |
| Intel Core i7-8750H CPU @ 2.20GHz      | 2         | 0.9%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz     | 2         | 0.9%    |
| Intel Core i7-4500U CPU @ 1.80GHz      | 2         | 0.9%    |
| Intel Core i7-3720QM CPU @ 2.60GHz     | 2         | 0.9%    |
| Intel Core i7-2670QM CPU @ 2.20GHz     | 2         | 0.9%    |
| Intel Core i5-2540M CPU @ 2.60GHz      | 2         | 0.9%    |
| Intel Core i5-2410M CPU @ 2.30GHz      | 2         | 0.9%    |
| Intel Core i5 CPU M 520 @ 2.40GHz      | 2         | 0.9%    |
| Intel Core i5 CPU M 430 @ 2.27GHz      | 2         | 0.9%    |
| Intel Core i3-4030U CPU @ 1.90GHz      | 2         | 0.9%    |
| Intel Core i3-2310M CPU @ 2.10GHz      | 2         | 0.9%    |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz   | 2         | 0.9%    |
| Intel Core 2 Duo CPU T7100 @ 1.80GHz   | 2         | 0.9%    |
| Intel Core 2 CPU                       | 2         | 0.9%    |
| Intel Celeron N4000 CPU @ 1.10GHz      | 2         | 0.9%    |
| Intel Celeron CPU N3350 @ 1.10GHz      | 2         | 0.9%    |
| Intel Atom CPU N570 @ 1.66GHz          | 2         | 0.9%    |
| AMD Ryzen 7 5800H with Radeon Graphics | 2         | 0.9%    |
| AMD Ryzen 7 4700U with Radeon Graphics | 2         | 0.9%    |
| Intel Xeon CPU E3-1535M v5 @ 2.90GHz   | 1         | 0.45%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 63        | 28.38%  |
| Intel Core i7           | 37        | 16.67%  |
| Intel Celeron           | 25        | 11.26%  |
| Intel Core 2 Duo        | 20        | 9.01%   |
| Intel Core i3           | 16        | 7.21%   |
| Other                   | 13        | 5.86%   |
| Intel Atom              | 7         | 3.15%   |
| Intel Pentium           | 6         | 2.7%    |
| AMD Ryzen 7             | 6         | 2.7%    |
| Intel Pentium Dual-Core | 3         | 1.35%   |
| AMD Ryzen 5             | 3         | 1.35%   |
| Intel Pentium Dual      | 2         | 0.9%    |
| Intel Genuine           | 2         | 0.9%    |
| Intel Core 2            | 2         | 0.9%    |
| AMD Athlon              | 2         | 0.9%    |
| Intel Xeon              | 1         | 0.45%   |
| Intel Pentium Silver    | 1         | 0.45%   |
| Intel Pentium Gold      | 1         | 0.45%   |
| Intel Celeron Dual-Core | 1         | 0.45%   |
| Intel Celeron D         | 1         | 0.45%   |
| AMD Ryzen Embedded      | 1         | 0.45%   |
| AMD Ryzen 3             | 1         | 0.45%   |
| AMD Phenom II           | 1         | 0.45%   |
| AMD E2                  | 1         | 0.45%   |
| AMD E1                  | 1         | 0.45%   |
| AMD E                   | 1         | 0.45%   |
| AMD A8                  | 1         | 0.45%   |
| AMD A6                  | 1         | 0.45%   |
| AMD A4                  | 1         | 0.45%   |
| AMD A10                 | 1         | 0.45%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 132       | 59.46%  |
| 4       | 45        | 20.27%  |
| Unknown | 27        | 12.16%  |
| 1       | 6         | 2.7%    |
| 16      | 4         | 1.8%    |
| 8       | 4         | 1.8%    |
| 12      | 2         | 0.9%    |
| 6       | 2         | 0.9%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 215       | 96.85%  |
| 2       | 6         | 2.7%    |
| Unknown | 1         | 0.45%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 130       | 58.56%  |
| 1       | 62        | 27.93%  |
| Unknown | 30        | 13.51%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 30        | 13.51%  |
| IvyBridge     | 24        | 10.81%  |
| SandyBridge   | 23        | 10.36%  |
| Penryn        | 19        | 8.56%   |
| Haswell       | 18        | 8.11%   |
| Core          | 17        | 7.66%   |
| Westmere      | 14        | 6.31%   |
| Skylake       | 11        | 4.95%   |
| Silvermont    | 11        | 4.95%   |
| Broadwell     | 10        | 4.5%    |
| Bonnell       | 8         | 3.6%    |
| TigerLake     | 6         | 2.7%    |
| Zen+          | 4         | 1.8%    |
| Goldmont plus | 4         | 1.8%    |
| Zen 3         | 3         | 1.35%   |
| Zen 2         | 3         | 1.35%   |
| Excavator     | 3         | 1.35%   |
| Bobcat        | 3         | 1.35%   |
| Unknown       | 3         | 1.35%   |
| Goldmont      | 2         | 0.9%    |
| Zen           | 1         | 0.45%   |
| Piledriver    | 1         | 0.45%   |
| Nehalem       | 1         | 0.45%   |
| K10 Llano     | 1         | 0.45%   |
| K10           | 1         | 0.45%   |
| CometLake     | 1         | 0.45%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 182       | 70.82%  |
| Nvidia                           | 40        | 15.56%  |
| AMD                              | 34        | 13.23%  |
| Silicon Integrated Systems [SiS] | 1         | 0.39%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 24        | 8.89%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 22        | 8.15%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 13        | 4.81%   |
| Intel Core Processor Integrated Graphics Controller                                      | 13        | 4.81%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 11        | 4.07%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 10        | 3.7%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 10        | 3.7%    |
| Intel HD Graphics 5500                                                                   | 10        | 3.7%    |
| Intel UHD Graphics 620                                                                   | 9         | 3.33%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 8         | 2.96%   |
| Intel HD Graphics 620                                                                    | 8         | 2.96%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 7         | 2.59%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 7         | 2.59%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 1.85%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 4         | 1.48%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 1.48%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 4         | 1.48%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 1.48%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 1.48%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 1.11%   |
| Nvidia C79 [GeForce 9400M]                                                               | 3         | 1.11%   |
| Intel HD Graphics 630                                                                    | 3         | 1.11%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 1.11%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 3         | 1.11%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 3         | 1.11%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 0.74%   |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 0.74%   |
| Nvidia GF116M [GeForce GT 560M]                                                          | 2         | 0.74%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 0.74%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 2         | 0.74%   |
| Intel HD Graphics 500                                                                    | 2         | 0.74%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 2         | 0.74%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 2         | 0.74%   |
| AMD Lucienne                                                                             | 2         | 0.74%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 2         | 0.74%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 1         | 0.37%   |
| Nvidia TU117M [GeForce MX450]                                                            | 1         | 0.37%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 0.37%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 0.37%   |
| Nvidia MCP79 [GeForce 8200M G]                                                           | 1         | 0.37%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 120       | 54.05%  |
| 2 x Intel      | 29        | 13.06%  |
| Intel + Nvidia | 26        | 11.71%  |
| 1 x AMD        | 24        | 10.81%  |
| 1 x Nvidia     | 11        | 4.95%   |
| Intel + AMD    | 7         | 3.15%   |
| AMD + Nvidia   | 2         | 0.9%    |
| 2 x Nvidia     | 1         | 0.45%   |
| 2 x AMD        | 1         | 0.45%   |
| 1 x SiS        | 1         | 0.45%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 202       | 90.99%  |
| Proprietary | 12        | 5.41%   |
| Unknown     | 8         | 3.6%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 203       | 91.44%  |
| 0.01-0.5   | 12        | 5.41%   |
| 0.51-1.0   | 5         | 2.25%   |
| 7.01-8.0   | 1         | 0.45%   |
| 1.01-2.0   | 1         | 0.45%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 27        | 25.71%  |
| LG Display              | 14        | 13.33%  |
| Chimei Innolux          | 14        | 13.33%  |
| Samsung Electronics     | 13        | 12.38%  |
| BOE                     | 12        | 11.43%  |
| Lenovo                  | 4         | 3.81%   |
| Apple                   | 4         | 3.81%   |
| InfoVision              | 3         | 2.86%   |
| Chi Mei Optoelectronics | 3         | 2.86%   |
| Sharp                   | 2         | 1.9%    |
| Goldstar                | 2         | 1.9%    |
| Quanta Display          | 1         | 0.95%   |
| LG Philips              | 1         | 0.95%   |
| Daewoo                  | 1         | 0.95%   |
| CPT                     | 1         | 0.95%   |
| AOC                     | 1         | 0.95%   |
| Acer                    | 1         | 0.95%   |
| Unknown                 | 1         | 0.95%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC3245 1280x800 330x210mm 15.4-inch  | 3         | 2.86%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch         | 3         | 2.86%   |
| Lenovo LCD Monitor LEN4022 1400x1050 290x210mm 14.1-inch              | 2         | 1.9%    |
| AU Optronics LCD Monitor AUO403D 1920x1080 310x170mm 13.9-inch        | 2         | 1.9%    |
| Sharp LQ133M1JW01 SHP141B 1920x1080 290x170mm 13.2-inch               | 1         | 0.95%   |
| Sharp LCD Monitor SHP143B 3840x2160 350x190mm 15.7-inch               | 1         | 0.95%   |
| Samsung Electronics SyncMaster SAM058D 1600x900 440x250mm 19.9-inch   | 1         | 0.95%   |
| Samsung Electronics LF27T370F SAM711E 1920x1080 600x340mm 27.2-inch   | 1         | 0.95%   |
| Samsung Electronics LCD Monitor SEC384A 1366x768 340x190mm 15.3-inch  | 1         | 0.95%   |
| Samsung Electronics LCD Monitor SEC3541 1366x768 300x170mm 13.6-inch  | 1         | 0.95%   |
| Samsung Electronics LCD Monitor SEC3052 1024x600 220x130mm 10.1-inch  | 1         | 0.95%   |
| Samsung Electronics LCD Monitor SEC3051 1600x900 390x230mm 17.8-inch  | 1         | 0.95%   |
| Samsung Electronics LCD Monitor SEC3050 1366x768 320x190mm 14.7-inch  | 1         | 0.95%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch  | 1         | 0.95%   |
| Samsung Electronics LCD Monitor SDC424A 3200x1800 290x170mm 13.2-inch | 1         | 0.95%   |
| Samsung Electronics C32HG7x SAM0E13 2560x1440 700x390mm 31.5-inch     | 1         | 0.95%   |
| Quanta Display LCD Monitor QDS0053 1280x800 300x190mm 14.0-inch       | 1         | 0.95%   |
| LG Philips LP154WX4-TLCB LPL3101 1280x800 330x210mm 15.4-inch         | 1         | 0.95%   |
| LG Display LCD Monitor LGD04E8 1920x1080 380x210mm 17.1-inch          | 1         | 0.95%   |
| LG Display LCD Monitor LGD044B 1366x768 340x190mm 15.3-inch           | 1         | 0.95%   |
| LG Display LCD Monitor LGD03ED 1366x768 280x160mm 12.7-inch           | 1         | 0.95%   |
| LG Display LCD Monitor LGD03DB 1366x768 350x190mm 15.7-inch           | 1         | 0.95%   |
| LG Display LCD Monitor LGD0384 1366x768 340x190mm 15.3-inch           | 1         | 0.95%   |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch           | 1         | 0.95%   |
| LG Display LCD Monitor LGD032C 1920x1080 340x190mm 15.3-inch          | 1         | 0.95%   |
| LG Display LCD Monitor LGD02EC 1366x768 290x160mm 13.0-inch           | 1         | 0.95%   |
| LG Display LCD Monitor LGD02E3 1366x768 340x190mm 15.3-inch           | 1         | 0.95%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch           | 1         | 0.95%   |
| LG Display LCD Monitor LGD02D1 1600x900 380x210mm 17.1-inch           | 1         | 0.95%   |
| LG Display LCD Monitor LGD027A 1600x900 380x210mm 17.1-inch           | 1         | 0.95%   |
| LG Display LCD Monitor LGD0250 1366x768 350x190mm 15.7-inch           | 1         | 0.95%   |
| LG Display LCD Monitor LGD024D 1366x768 290x170mm 13.2-inch           | 1         | 0.95%   |
| Lenovo LCD Monitor LEN4057 1280x800 330x210mm 15.4-inch               | 1         | 0.95%   |
| Lenovo LCD Monitor LEN4010 1280x800 260x160mm 12.0-inch               | 1         | 0.95%   |
| InfoVision LCD Monitor IVO0533 1366x768 290x170mm 13.2-inch           | 1         | 0.95%   |
| InfoVision LCD Monitor IVO048E 1366x768 260x140mm 11.6-inch           | 1         | 0.95%   |
| InfoVision LCD Monitor IVO03F4 1024x600 220x130mm 10.1-inch           | 1         | 0.95%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch          | 1         | 0.95%   |
| Goldstar LG FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch             | 1         | 0.95%   |
| Daewoo HDMI DWE2100 1280x1024 470x260mm 21.1-inch                     | 1         | 0.95%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1366x768 (WXGA)  | 45        | 43.69%  |
| 1920x1080 (FHD)  | 34        | 33.01%  |
| 1600x900 (HD+)   | 6         | 5.83%   |
| 1280x800 (WXGA)  | 6         | 5.83%   |
| 1024x600         | 4         | 3.88%   |
| 2560x1600        | 2         | 1.94%   |
| 1400x1050        | 2         | 1.94%   |
| 3840x2160 (4K)   | 1         | 0.97%   |
| 3200x1800 (QHD+) | 1         | 0.97%   |
| 2560x1440 (QHD)  | 1         | 0.97%   |
| 1280x1024 (SXGA) | 1         | 0.97%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 34        | 32.38%  |
| 13      | 32        | 30.48%  |
| 17      | 9         | 8.57%   |
| 12      | 7         | 6.67%   |
| 14      | 5         | 4.76%   |
| 11      | 5         | 4.76%   |
| 21      | 4         | 3.81%   |
| 10      | 3         | 2.86%   |
| 27      | 2         | 1.9%    |
| 31      | 1         | 0.95%   |
| 19      | 1         | 0.95%   |
| 9       | 1         | 0.95%   |
| Unknown | 1         | 0.95%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 58        | 55.24%  |
| 201-300     | 29        | 27.62%  |
| 351-400     | 9         | 8.57%   |
| 401-500     | 5         | 4.76%   |
| 501-600     | 2         | 1.9%    |
| 601-700     | 1         | 0.95%   |
| Unknown     | 1         | 0.95%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 88        | 87.13%  |
| 16/10   | 10        | 9.9%    |
| 4/3     | 2         | 1.98%   |
| Unknown | 1         | 0.99%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 27        | 25.71%  |
| 91-100         | 27        | 25.71%  |
| 101-110        | 10        | 9.52%   |
| 121-130        | 8         | 7.62%   |
| 71-80          | 7         | 6.67%   |
| 61-70          | 7         | 6.67%   |
| 51-60          | 5         | 4.76%   |
| 41-50          | 4         | 3.81%   |
| 201-250        | 3         | 2.86%   |
| 301-350        | 2         | 1.9%    |
| 151-200        | 2         | 1.9%    |
| 351-500        | 1         | 0.95%   |
| 131-140        | 1         | 0.95%   |
| Unknown        | 1         | 0.95%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 48        | 45.71%  |
| 101-120       | 38        | 36.19%  |
| 51-100        | 14        | 13.33%  |
| More than 240 | 2         | 1.9%    |
| 161-240       | 2         | 1.9%    |
| Unknown       | 1         | 0.95%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 195       | 87.84%  |
| 0     | 17        | 7.66%   |
| 2     | 10        | 4.5%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 116       | 32.86%  |
| Realtek Semiconductor             | 95        | 26.91%  |
| Qualcomm Atheros                  | 61        | 17.28%  |
| Broadcom                          | 28        | 7.93%   |
| Marvell Technology Group          | 9         | 2.55%   |
| Samsung Electronics               | 6         | 1.7%    |
| Xiaomi                            | 5         | 1.42%   |
| Sierra Wireless                   | 5         | 1.42%   |
| Nvidia                            | 5         | 1.42%   |
| Ralink                            | 3         | 0.85%   |
| MediaTek                          | 3         | 0.85%   |
| JMicron Technology                | 3         | 0.85%   |
| Ericsson Business Mobile Networks | 3         | 0.85%   |
| TP-Link                           | 2         | 0.57%   |
| Ralink Technology                 | 2         | 0.57%   |
| T & A Mobile Phones               | 1         | 0.28%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.28%   |
| Qualcomm                          | 1         | 0.28%   |
| OPPO Electronics                  | 1         | 0.28%   |
| Edimax Technology                 | 1         | 0.28%   |
| BUFFALO                           | 1         | 0.28%   |
| ASUSTek Computer                  | 1         | 0.28%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 54        | 12.27%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 26        | 5.91%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 18        | 4.09%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 17        | 3.86%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 14        | 3.18%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 13        | 2.95%   |
| Intel Wireless 8265 / 8275                                              | 11        | 2.5%    |
| Intel Wireless 8260                                                     | 9         | 2.05%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 8         | 1.82%   |
| Intel Wireless 7265                                                     | 8         | 1.82%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 8         | 1.82%   |
| Intel Ethernet Connection I219-LM                                       | 7         | 1.59%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 6         | 1.36%   |
| Intel Wireless 7260                                                     | 6         | 1.36%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 5         | 1.14%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 5         | 1.14%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 5         | 1.14%   |
| Nvidia MCP79 Ethernet                                                   | 5         | 1.14%   |
| Intel Wireless 3165                                                     | 5         | 1.14%   |
| Intel Wi-Fi 6 AX201                                                     | 5         | 1.14%   |
| Intel Ethernet Connection (4) I219-LM                                   | 5         | 1.14%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 5         | 1.14%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 4         | 0.91%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 4         | 0.91%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 4         | 0.91%   |
| Intel Wi-Fi 6 AX200                                                     | 4         | 0.91%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 4         | 0.91%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 4         | 0.91%   |
| Intel Ethernet Connection I217-LM                                       | 4         | 0.91%   |
| Intel Ethernet Connection (4) I219-V                                    | 4         | 0.91%   |
| Intel Ethernet Connection (3) I218-LM                                   | 4         | 0.91%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 0.91%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 4         | 0.91%   |
| Intel 82577LM Gigabit Network Connection                                | 4         | 0.91%   |
| Intel 82567LM Gigabit Network Connection                                | 4         | 0.91%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 0.68%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 3         | 0.68%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                  | 3         | 0.68%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 3         | 0.68%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 0.68%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 108       | 47.37%  |
| Qualcomm Atheros      | 54        | 23.68%  |
| Realtek Semiconductor | 28        | 12.28%  |
| Broadcom              | 23        | 10.09%  |
| Sierra Wireless       | 3         | 1.32%   |
| Ralink                | 3         | 1.32%   |
| TP-Link               | 2         | 0.88%   |
| Ralink Technology     | 2         | 0.88%   |
| MediaTek              | 2         | 0.88%   |
| Edimax Technology     | 1         | 0.44%   |
| BUFFALO               | 1         | 0.44%   |
| ASUSTek Computer      | 1         | 0.44%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 17        | 7.36%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 14        | 6.06%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 13        | 5.63%   |
| Intel Wireless 8265 / 8275                                              | 11        | 4.76%   |
| Intel Wireless 8260                                                     | 9         | 3.9%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 8         | 3.46%   |
| Intel Wireless 7265                                                     | 8         | 3.46%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 8         | 3.46%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 6         | 2.6%    |
| Intel Wireless 7260                                                     | 6         | 2.6%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 5         | 2.16%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 5         | 2.16%   |
| Intel Wireless 3165                                                     | 5         | 2.16%   |
| Intel Wi-Fi 6 AX201                                                     | 5         | 2.16%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 5         | 2.16%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 4         | 1.73%   |
| Intel Wi-Fi 6 AX200                                                     | 4         | 1.73%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 4         | 1.73%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 4         | 1.73%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 1.73%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 4         | 1.73%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 1.3%    |
| Realtek RTL8723DE Wireless Network Adapter                              | 3         | 1.3%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 3         | 1.3%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 1.3%    |
| Intel Centrino Wireless-N 2230                                          | 3         | 1.3%    |
| Intel Centrino Advanced-N 6200                                          | 3         | 1.3%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3         | 1.3%    |
| Broadcom BCM4331 802.11a/b/g/n                                          | 3         | 1.3%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 2         | 0.87%   |
| Sierra Wireless EM7345 4G LTE                                           | 2         | 0.87%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.87%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.87%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 0.87%   |
| Realtek Realtek Bluetooth 4.2 Adapter                                   | 2         | 0.87%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                               | 2         | 0.87%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 2         | 0.87%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 0.87%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 2         | 0.87%   |
| Intel WiFi Link 5100                                                    | 2         | 0.87%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 81        | 39.9%   |
| Intel                            | 66        | 32.51%  |
| Qualcomm Atheros                 | 15        | 7.39%   |
| Marvell Technology Group         | 9         | 4.43%   |
| Broadcom                         | 8         | 3.94%   |
| Samsung Electronics              | 6         | 2.96%   |
| Xiaomi                           | 5         | 2.46%   |
| Nvidia                           | 5         | 2.46%   |
| JMicron Technology               | 3         | 1.48%   |
| T & A Mobile Phones              | 1         | 0.49%   |
| Silicon Integrated Systems [SiS] | 1         | 0.49%   |
| Qualcomm                         | 1         | 0.49%   |
| OPPO Electronics                 | 1         | 0.49%   |
| MediaTek                         | 1         | 0.49%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 54        | 26.6%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 26        | 12.81%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 18        | 8.87%   |
| Intel Ethernet Connection I219-LM                                      | 7         | 3.45%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 5         | 2.46%   |
| Nvidia MCP79 Ethernet                                                  | 5         | 2.46%   |
| Intel Ethernet Connection (4) I219-LM                                  | 5         | 2.46%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 4         | 1.97%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 4         | 1.97%   |
| Intel Ethernet Connection I217-LM                                      | 4         | 1.97%   |
| Intel Ethernet Connection (4) I219-V                                   | 4         | 1.97%   |
| Intel Ethernet Connection (3) I218-LM                                  | 4         | 1.97%   |
| Intel 82577LM Gigabit Network Connection                               | 4         | 1.97%   |
| Intel 82567LM Gigabit Network Connection                               | 4         | 1.97%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 3         | 1.48%   |
| Intel 82566MM Gigabit Network Connection                               | 3         | 1.48%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 2         | 0.99%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 2         | 0.99%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 2         | 0.99%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 2         | 0.99%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 2         | 0.99%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 2         | 0.99%   |
| Intel 82573L Gigabit Ethernet Controller                               | 2         | 0.99%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 2         | 0.99%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 2         | 0.99%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 1         | 0.49%   |
| T & A Mobile Phones ALCATEL RNDIS Interface                            | 1         | 0.49%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter          | 1         | 0.49%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1         | 0.49%   |
| Qualcomm FP3                                                           | 1         | 0.49%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 0.49%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1         | 0.49%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                             | 1         | 0.49%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 1         | 0.49%   |
| OPPO PGCM10 RNDIS Control RNDIS Ethernet Data                          | 1         | 0.49%   |
| MediaTek USB Ethernet-RNDIS                                            | 1         | 0.49%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                | 1         | 0.49%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                | 1         | 0.49%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 1         | 0.49%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller                  | 1         | 0.49%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 214       | 51.44%  |
| Ethernet | 196       | 47.12%  |
| Unknown  | 5         | 1.2%    |
| Modem    | 1         | 0.24%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 112       | 56.28%  |
| Ethernet | 87        | 43.72%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 179       | 80.63%  |
| 1     | 39        | 17.57%  |
| 0     | 3         | 1.35%   |
| 3     | 1         | 0.45%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 206       | 92.38%  |
| Yes  | 17        | 7.62%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 68        | 43.59%  |
| Broadcom                        | 19        | 12.18%  |
| Qualcomm Atheros Communications | 18        | 11.54%  |
| Realtek Semiconductor           | 12        | 7.69%   |
| Apple                           | 10        | 6.41%   |
| Foxconn / Hon Hai               | 8         | 5.13%   |
| IMC Networks                    | 4         | 2.56%   |
| Hewlett-Packard                 | 4         | 2.56%   |
| ASUSTek Computer                | 4         | 2.56%   |
| Lite-On Technology              | 3         | 1.92%   |
| Dell                            | 2         | 1.28%   |
| Cambridge Silicon Radio         | 2         | 1.28%   |
| Askey Computer                  | 1         | 0.64%   |
| Alps Electric                   | 1         | 0.64%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                       | 41        | 26.11%  |
| Intel AX201 Bluetooth                                    | 9         | 5.73%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                    | 8         | 5.1%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 6         | 3.82%   |
| Intel Centrino Bluetooth Wireless Transceiver            | 4         | 2.55%   |
| Intel AX200 Bluetooth                                    | 4         | 2.55%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]            | 4         | 2.55%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]               | 4         | 2.55%   |
| Apple Bluetooth Host Controller                          | 4         | 2.55%   |
| Realtek Bluetooth Adapter                                | 3         | 1.91%   |
| Intel Wireless-AC 3168 Bluetooth                         | 3         | 1.91%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]       | 3         | 1.91%   |
| Broadcom BCM2045B (BDC-2.1)                              | 3         | 1.91%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]         | 3         | 1.91%   |
| ASUS BT-270 Bluetooth Adapter                            | 3         | 1.91%   |
| Apple Built-in iSight (no firmware loaded)               | 3         | 1.91%   |
| Realtek RTL8821A Bluetooth                               | 2         | 1.27%   |
| Realtek Bluetooth 4.2 Adapter                            | 2         | 1.27%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                   | 2         | 1.27%   |
| Qualcomm Atheros AR9462 Bluetooth                        | 2         | 1.27%   |
| Qualcomm Atheros AR3011 Bluetooth                        | 2         | 1.27%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter             | 2         | 1.27%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device          | 2         | 1.27%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth USB Device | 2         | 1.27%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 2         | 1.27%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                     | 2         | 1.27%   |
| Apple Broadcom Built-in Bluetooth                        | 2         | 1.27%   |
| Realtek RTL8723B Bluetooth                               | 1         | 0.64%   |
| Realtek  Bluetooth 4.2 Adapter                           | 1         | 0.64%   |
| Realtek Dell Wireless 1801 Bluetooth 4.0 LE              | 1         | 0.64%   |
| Realtek Bluetooth 4.0 Adapter                            | 1         | 0.64%   |
| Realtek Bluetooth 4.0 + High Speed Chip                  | 1         | 0.64%   |
| Qualcomm Atheros Dell Wireless 1901 Bluetooth            | 1         | 0.64%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE      | 1         | 0.64%   |
| Qualcomm Atheros Dell Wireless 1703 Bluetooth            | 1         | 0.64%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)          | 1         | 0.64%   |
| Lite-On Qualcomm Atheros Bluetooth 4.0 + HS              | 1         | 0.64%   |
| Lite-On Qualcomm Atheros Bluetooth                       | 1         | 0.64%   |
| Lite-On Atheros AR3012 Bluetooth                         | 1         | 0.64%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter         | 1         | 0.64%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 193       | 80.42%  |
| AMD                               | 27        | 11.25%  |
| Nvidia                            | 12        | 5%      |
| Texas Instruments                 | 1         | 0.42%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.42%   |
| Realtek Semiconductor             | 1         | 0.42%   |
| Phison Electronics                | 1         | 0.42%   |
| Generalplus Technology            | 1         | 0.42%   |
| Elitegroup Computer Systems (ECS) | 1         | 0.42%   |
| Conexant Systems                  | 1         | 0.42%   |
| Apogee Electronics                | 1         | 0.42%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 27        | 9.44%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 27        | 9.44%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 20        | 6.99%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 17        | 5.94%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 15        | 5.24%   |
| Intel 8 Series HD Audio Controller                                                                | 13        | 4.55%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 13        | 4.55%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 12        | 4.2%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 11        | 3.85%   |
| Intel Broadwell-U Audio Controller                                                                | 10        | 3.5%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 9         | 3.15%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 9         | 3.15%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 7         | 2.45%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 7         | 2.45%   |
| Nvidia MCP79 High Definition Audio                                                                | 6         | 2.1%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 6         | 2.1%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5         | 1.75%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 5         | 1.75%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 5         | 1.75%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 4         | 1.4%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 1.4%    |
| Intel Cannon Lake PCH cAVS                                                                        | 4         | 1.4%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 1.4%    |
| AMD FCH Azalia Controller                                                                         | 4         | 1.4%    |
| Intel CM238 HD Audio Controller                                                                   | 3         | 1.05%   |
| AMD High Definition Audio Controller                                                              | 3         | 1.05%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 1.05%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 2         | 0.7%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 0.7%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 0.7%    |
| AMD Wrestler HDMI Audio                                                                           | 2         | 0.7%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 0.7%    |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 2         | 0.7%    |
| Texas Instruments PCM2902 Audio Codec                                                             | 1         | 0.35%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 0.35%   |
| Realtek Semiconductor USB Audio                                                                   | 1         | 0.35%   |
| Phison Electronics SoundYouSoundYouSoundYouSoundYouSoundYouSoundYouSoundYouSoun                   | 1         | 0.35%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.35%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.35%   |
| Nvidia GF116 High Definition Audio Controller                                                     | 1         | 0.35%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 72        | 29.03%  |
| SK hynix            | 45        | 18.15%  |
| Unknown             | 23        | 9.27%   |
| Micron Technology   | 22        | 8.87%   |
| Kingston            | 13        | 5.24%   |
| Unknown             | 12        | 4.84%   |
| Crucial             | 10        | 4.03%   |
| Elpida              | 7         | 2.82%   |
| A-DATA Technology   | 6         | 2.42%   |
| Nanya Technology    | 5         | 2.02%   |
| Ramaxel Technology  | 4         | 1.61%   |
| Corsair             | 4         | 1.61%   |
| Unknown (ABCD)      | 3         | 1.21%   |
| Transcend           | 3         | 1.21%   |
| Smart               | 3         | 1.21%   |
| SHARETRONIC         | 2         | 0.81%   |
| Multilaser          | 2         | 0.81%   |
| ASint Technology    | 2         | 0.81%   |
| Team                | 1         | 0.4%    |
| Swissbit            | 1         | 0.4%    |
| Silicon Power       | 1         | 0.4%    |
| SemsoTai            | 1         | 0.4%    |
| Qimonda             | 1         | 0.4%    |
| Lenovo              | 1         | 0.4%    |
| GOODRAM             | 1         | 0.4%    |
| G.Skill             | 1         | 0.4%    |
| Apacer              | 1         | 0.4%    |
| 48spaces            | 1         | 0.4%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 12        | 4.56%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 6         | 2.28%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 1.9%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 5         | 1.9%    |
| Unknown RAM Module 1GB SODIMM DDR2                               | 4         | 1.52%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 4         | 1.52%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s            | 4         | 1.52%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s            | 4         | 1.52%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 3         | 1.14%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 3         | 1.14%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 3         | 1.14%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.14%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 3         | 1.14%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.14%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s            | 3         | 1.14%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 1.14%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 1.14%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 3         | 1.14%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s          | 3         | 1.14%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 3         | 1.14%   |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s                      | 2         | 0.76%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.76%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s           | 2         | 0.76%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s           | 2         | 0.76%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 1333MT/s            | 2         | 0.76%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 0.76%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 2         | 0.76%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.76%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 2         | 0.76%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 2         | 0.76%   |
| Samsung RAM M471A5143EB0-CPB 4GB SODIMM DDR4 2133MT/s            | 2         | 0.76%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 0.76%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.76%   |
| Samsung RAM M4 70T5663QZ3-CF7 2GB SODIMM DDR2 2048MT/s           | 2         | 0.76%   |
| Multilaser RAM MS3512NSZ-CA3G1 4GB SODIMM DDR3 1600MT/s          | 2         | 0.76%   |
| Micron RAM Module 4GB SODIMM DDR3 1600MT/s                       | 2         | 0.76%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 0.38%   |
| Unknown RAM Module 8GB SODIMM DDR3 1333MT/s                      | 1         | 0.38%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 0.38%   |
| Unknown RAM Module 2GB SODIMM DDR3 667MT/s                       | 1         | 0.38%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 112       | 51.61%  |
| DDR4    | 62        | 28.57%  |
| DDR2    | 27        | 12.44%  |
| Unknown | 7         | 3.23%   |
| LPDDR4  | 4         | 1.84%   |
| SDRAM   | 3         | 1.38%   |
| LPDDR3  | 2         | 0.92%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 203       | 93.12%  |
| Row Of Chips | 5         | 2.29%   |
| Chip         | 4         | 1.83%   |
| Unknown      | 4         | 1.83%   |
| DIMM         | 2         | 0.92%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 82        | 34.02%  |
| 8192  | 67        | 27.8%   |
| 2048  | 58        | 24.07%  |
| 16384 | 16        | 6.64%   |
| 1024  | 16        | 6.64%   |
| 32768 | 2         | 0.83%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 64        | 27.71%  |
| 2400    | 27        | 11.69%  |
| 667     | 21        | 9.09%   |
| 3200    | 20        | 8.66%   |
| 1333    | 20        | 8.66%   |
| 2667    | 17        | 7.36%   |
| 1067    | 16        | 6.93%   |
| 1334    | 10        | 4.33%   |
| 800     | 9         | 3.9%    |
| Unknown | 9         | 3.9%    |
| 2133    | 8         | 3.46%   |
| 1867    | 4         | 1.73%   |
| 2048    | 2         | 0.87%   |
| 1066    | 2         | 0.87%   |
| 3733    | 1         | 0.43%   |
| 533     | 1         | 0.43%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| HP LaserJet 1020 | 1         | 100%    |

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


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 42        | 25.61%  |
| Bison Electronics                      | 24        | 14.63%  |
| Microdia                               | 13        | 7.93%   |
| IMC Networks                           | 11        | 6.71%   |
| Sunplus Innovation Technology          | 9         | 5.49%   |
| Realtek Semiconductor                  | 9         | 5.49%   |
| Syntek                                 | 6         | 3.66%   |
| Lite-On Technology                     | 6         | 3.66%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 3.66%   |
| Silicon Motion                         | 5         | 3.05%   |
| Quanta                                 | 5         | 3.05%   |
| Suyin                                  | 4         | 2.44%   |
| Apple                                  | 4         | 2.44%   |
| Alcor Micro                            | 4         | 2.44%   |
| Z-Star Microelectronics                | 3         | 1.83%   |
| Lenovo                                 | 3         | 1.83%   |
| ALi                                    | 3         | 1.83%   |
| Y Media                                | 1         | 0.61%   |
| Supreme Electronics                    | 1         | 0.61%   |
| Luxvisions Innotech Limited            | 1         | 0.61%   |
| Jiangxi Shinetech Optical              | 1         | 0.61%   |
| Importek                               | 1         | 0.61%   |
| DigiTech                               | 1         | 0.61%   |
| Cubeternet                             | 1         | 0.61%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                   | 14        | 8.54%   |
| Bison Integrated Camera                                     | 9         | 5.49%   |
| Microdia Integrated_Webcam_HD                               | 8         | 4.88%   |
| Chicony Lenovo Integrated Camera (0.3MP)                    | 5         | 3.05%   |
| Realtek Integrated_Webcam_HD                                | 4         | 2.44%   |
| Lite-On Integrated Camera                                   | 4         | 2.44%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                    | 3         | 1.83%   |
| IMC Networks Integrated Webcam                              | 3         | 1.83%   |
| Chicony FJ Camera                                           | 3         | 1.83%   |
| Cheng Uei Precision Industry (Foxlink) Realtek DMFT RGB     | 3         | 1.83%   |
| Syntek Lenovo EasyCamera                                    | 2         | 1.22%   |
| Syntek Integrated Camera                                    | 2         | 1.22%   |
| Sunplus Integrated_Webcam_HD                                | 2         | 1.22%   |
| Sunplus HP TrueVision HD Camera                             | 2         | 1.22%   |
| Realtek USB Camera                                          | 2         | 1.22%   |
| Lenovo Integrated Webcam                                    | 2         | 1.22%   |
| IMC Networks UVC VGA Webcam                                 | 2         | 1.22%   |
| IMC Networks Integrated Camera                              | 2         | 1.22%   |
| IMC Networks EasyCamera                                     | 2         | 1.22%   |
| Chicony USB 2.0 Camera                                      | 2         | 1.22%   |
| Chicony Integrated Camera [ThinkPad]                        | 2         | 1.22%   |
| Chicony HP Wide Vision HD Camera                            | 2         | 1.22%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam            | 2         | 1.22%   |
| Bison ThinkPad Integrated Camera                            | 2         | 1.22%   |
| Bison SunplusIT Integrated Camera                           | 2         | 1.22%   |
| Bison Lenovo Integrated Webcam                              | 2         | 1.22%   |
| Bison Lenovo EasyCamera                                     | 2         | 1.22%   |
| Bison HP Webcam-101                                         | 2         | 1.22%   |
| Apple FaceTime HD Camera                                    | 2         | 1.22%   |
| ALi WebCam                                                  | 2         | 1.22%   |
| Alcor Micro USB 2.0 Camera                                  | 2         | 1.22%   |
| Z-Star Webcam                                               | 1         | 0.61%   |
| Z-Star Vega USB 2.0 Camera                                  | 1         | 0.61%   |
| Z-Star Namuga 1.3M Webcam                                   | 1         | 0.61%   |
| Y Media USB Camera                                          | 1         | 0.61%   |
| Syntek HP Webcam                                            | 1         | 0.61%   |
| Syntek EasyCamera                                           | 1         | 0.61%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 0.61%   |
| Supreme Integrated Camera                                   | 1         | 0.61%   |
| Sunplus Laptop Integrated WebCam HD                         | 1         | 0.61%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 13        | 44.83%  |
| Upek                       | 4         | 13.79%  |
| AuthenTec                  | 4         | 13.79%  |
| Elan Microelectronics      | 3         | 10.34%  |
| STMicroelectronics         | 1         | 3.45%   |
| Shenzhen Goodix Technology | 1         | 3.45%   |
| LighTuning Technology      | 1         | 3.45%   |
| FocalTech Systems          | 1         | 3.45%   |
| Fingerprint Cards          | 1         | 3.45%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                             | Notebooks | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor                                      | 5         | 17.24%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                            | 4         | 13.79%  |
| Validity Sensors Synaptics WBDI                                                   | 3         | 10.34%  |
| Elan Fingerprint Sensor                                                           | 3         | 10.34%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                                 | 1         | 3.45%   |
| Validity Sensors VFS5011 Fingerprint Reader                                       | 1         | 3.45%   |
| Validity Sensors VFS101 Fingerprint Reader                                        | 1         | 3.45%   |
| Validity Sensors Swipe Fingerprint Sensor                                         | 1         | 3.45%   |
| Validity Sensors Fingerprint scanner                                              | 1         | 3.45%   |
| STMicroelectronics Fingerprint Reader                                             | 1         | 3.45%   |
| Shenzhen Goodix Fingerprint Reader SGX                                            | 1         | 3.45%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                       | 1         | 3.45%   |
| FocalTech Systems FocalTech Fingerprint Device Realtek USB2.0 Finger Print Bridge | 1         | 3.45%   |
| Fingerprint Cards FPC Fingerprint Reader                                          | 1         | 3.45%   |
| AuthenTec AES2810                                                                 | 1         | 3.45%   |
| AuthenTec AES2660                                                                 | 1         | 3.45%   |
| AuthenTec AES2501 Fingerprint Sensor                                              | 1         | 3.45%   |
| AuthenTec AES1660                                                                 | 1         | 3.45%   |

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
| 1     | 104       | 46.64%  |
| 2     | 59        | 26.46%  |
| 0     | 38        | 17.04%  |
| 3     | 19        | 8.52%   |
| 4     | 3         | 1.35%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 147       | 54.44%  |
| Net/wireless             | 39        | 14.44%  |
| Fingerprint reader       | 29        | 10.74%  |
| Card reader              | 28        | 10.37%  |
| Bluetooth                | 18        | 6.67%   |
| Storage                  | 5         | 1.85%   |
| Sound                    | 2         | 0.74%   |
| Network                  | 1         | 0.37%   |
| Net/ethernet             | 1         | 0.37%   |

