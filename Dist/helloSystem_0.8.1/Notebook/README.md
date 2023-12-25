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

Total: 241

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
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
| amd64 | 207       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 205       | 99.03%  |
| JWM          | 1         | 0.48%   |
| GNOME        | 1         | 0.48%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 207       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| SLiM | 207       | 99.52%  |
| SDDM | 1         | 0.48%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 100       | 48.08%  |
| fr_FR   | 25        | 12.02%  |
| ru_RU   | 18        | 8.65%   |
| de_DE   | 13        | 6.25%   |
| Unknown | 10        | 4.81%   |
| es_ES   | 9         | 4.33%   |
| pl_PL   | 8         | 3.85%   |
| pt_BR   | 5         | 2.4%    |
| it_IT   | 4         | 1.92%   |
| zh_CN   | 3         | 1.44%   |
| nl_NL   | 3         | 1.44%   |
| fi_FI   | 2         | 0.96%   |
| tr_TR   | 1         | 0.48%   |
| pt_PT   | 1         | 0.48%   |
| pt      | 1         | 0.48%   |
| ko_KR   | 1         | 0.48%   |
| jp_JP   | 1         | 0.48%   |
| fi_DK   | 1         | 0.48%   |
| en      | 1         | 0.48%   |
| C       | 1         | 0.48%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 207       | 100%    |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Zfs    | 104       | 50.24%  |
| Cd9660 | 103       | 49.76%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 207       | 100%    |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 73        | 35.27%  |
| Hewlett-Packard     | 29        | 14.01%  |
| Dell                | 20        | 9.66%   |
| ASUSTek Computer    | 15        | 7.25%   |
| Acer                | 11        | 5.31%   |
| Toshiba             | 9         | 4.35%   |
| Samsung Electronics | 9         | 4.35%   |
| Apple               | 9         | 4.35%   |
| Fujitsu             | 5         | 2.42%   |
| Sony                | 3         | 1.45%   |
| Google              | 3         | 1.45%   |
| Packard Bell        | 2         | 0.97%   |
| Intel               | 2         | 0.97%   |
| TUXEDO              | 1         | 0.48%   |
| Timi                | 1         | 0.48%   |
| Plaisio             | 1         | 0.48%   |
| Panasonic           | 1         | 0.48%   |
| OEGStone            | 1         | 0.48%   |
| NVN-ED01            | 1         | 0.48%   |
| MSI                 | 1         | 0.48%   |
| Medion              | 1         | 0.48%   |
| LG Electronics      | 1         | 0.48%   |
| Irbis               | 1         | 0.48%   |
| IGEL Technology     | 1         | 0.48%   |
| HUAWEI              | 1         | 0.48%   |
| Gateway             | 1         | 0.48%   |
| eMachines           | 1         | 0.48%   |
| Dynabook Europe     | 1         | 0.48%   |
| DNS                 | 1         | 0.48%   |
| Compaq              | 1         | 0.48%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Unknown                               | 4         | 1.93%   |
| HP Laptop 14-bs0xx                    | 2         | 0.97%   |
| Apple MacBookPro9,2                   | 2         | 0.97%   |
| Apple MacBook5,1                      | 2         | 0.97%   |
| TUXEDO Aura 15 Gen1                   | 1         | 0.48%   |
| Toshiba Satellite P300                | 1         | 0.48%   |
| Toshiba Satellite L675D               | 1         | 0.48%   |
| Toshiba Satellite L50-B               | 1         | 0.48%   |
| Toshiba Satellite L40                 | 1         | 0.48%   |
| Toshiba Satellite C845                | 1         | 0.48%   |
| Toshiba Satellite A200                | 1         | 0.48%   |
| Toshiba QOSMIO X775                   | 1         | 0.48%   |
| Toshiba PORTEGE R700                  | 1         | 0.48%   |
| Timi TM1701                           | 1         | 0.48%   |
| Sony VPCEG15FB                        | 1         | 0.48%   |
| Sony VGN-FZ19VN                       | 1         | 0.48%   |
| Sony SVF14A15CBB                      | 1         | 0.48%   |
| Samsung RC530/RC730                   | 1         | 0.48%   |
| Samsung R530/R730/R540                | 1         | 0.48%   |
| Samsung R520/R522/R620                | 1         | 0.48%   |
| Samsung R468/R418                     | 1         | 0.48%   |
| Samsung N150P/N210P/N220P             | 1         | 0.48%   |
| Samsung 370E4K                        | 1         | 0.48%   |
| Samsung 305E4A/305E5A/305E7A          | 1         | 0.48%   |
| Samsung 275E4E/275E5E                 | 1         | 0.48%   |
| Samsung 270E5J/2570EJ                 | 1         | 0.48%   |
| Plaisio Turbo X                       | 1         | 0.48%   |
| Panasonic CF-NX1GDHYS                 | 1         | 0.48%   |
| Packard Bell EasyNote LJ65            | 1         | 0.48%   |
| Packard Bell DOT SE                   | 1         | 0.48%   |
| OEGStone doceo 510                    | 1         | 0.48%   |
| MSI GE63 Raider RGB 8RE               | 1         | 0.48%   |
| Medion E15302                         | 1         | 0.48%   |
| LG E500-L.A2M4A2                      | 1         | 0.48%   |
| Lenovo ZIUS6                          | 1         | 0.48%   |
| Lenovo Z50-70 20354                   | 1         | 0.48%   |
| Lenovo Yoga Slim 7 14ITL05 82A3       | 1         | 0.48%   |
| Lenovo Yoga 2 Pro 20266               | 1         | 0.48%   |
| Lenovo ThinkPad X61s 7667WQS          | 1         | 0.48%   |
| Lenovo ThinkPad X270 W10DG 20K5S0DB05 | 1         | 0.48%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 48        | 23.19%  |
| Lenovo IdeaPad        | 13        | 6.28%   |
| Dell Latitude         | 12        | 5.8%    |
| HP Pavilion           | 9         | 4.35%   |
| HP Laptop             | 7         | 3.38%   |
| Dell Inspiron         | 7         | 3.38%   |
| Acer Aspire           | 7         | 3.38%   |
| Toshiba Satellite     | 6         | 2.9%    |
| HP EliteBook          | 4         | 1.93%   |
| Unknown               | 4         | 1.93%   |
| HP Compaq             | 3         | 1.45%   |
| Fujitsu LIFEBOOK      | 3         | 1.45%   |
| ASUS VivoBook         | 3         | 1.45%   |
| Apple MacBook5        | 3         | 1.45%   |
| Lenovo Yoga           | 2         | 0.97%   |
| Lenovo Legion         | 2         | 0.97%   |
| Apple MacBookPro9     | 2         | 0.97%   |
| TUXEDO Aura           | 1         | 0.48%   |
| Toshiba QOSMIO        | 1         | 0.48%   |
| Toshiba PORTEGE       | 1         | 0.48%   |
| Timi TM1701           | 1         | 0.48%   |
| Sony VPCEG15FB        | 1         | 0.48%   |
| Sony VGN-FZ19VN       | 1         | 0.48%   |
| Sony SVF14A15CBB      | 1         | 0.48%   |
| Samsung RC530         | 1         | 0.48%   |
| Samsung R530          | 1         | 0.48%   |
| Samsung R520          | 1         | 0.48%   |
| Samsung R468          | 1         | 0.48%   |
| Samsung N150P         | 1         | 0.48%   |
| Samsung 370E4K        | 1         | 0.48%   |
| Samsung 305E4A        | 1         | 0.48%   |
| Samsung 275E4E        | 1         | 0.48%   |
| Samsung 270E5J        | 1         | 0.48%   |
| Plaisio Turbo         | 1         | 0.48%   |
| Panasonic CF-NX1GDHYS | 1         | 0.48%   |
| Packard Bell EasyNote | 1         | 0.48%   |
| Packard Bell DOT      | 1         | 0.48%   |
| OEGStone doceo        | 1         | 0.48%   |
| MSI GE63              | 1         | 0.48%   |
| Medion E15302         | 1         | 0.48%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2011 | 21        | 10.14%  |
| 2013 | 17        | 8.21%   |
| 2012 | 17        | 8.21%   |
| 2022 | 16        | 7.73%   |
| 2020 | 15        | 7.25%   |
| 2010 | 15        | 7.25%   |
| 2019 | 13        | 6.28%   |
| 2009 | 13        | 6.28%   |
| 2017 | 12        | 5.8%    |
| 2016 | 12        | 5.8%    |
| 2021 | 10        | 4.83%   |
| 2015 | 10        | 4.83%   |
| 2008 | 10        | 4.83%   |
| 2018 | 8         | 3.86%   |
| 2014 | 8         | 3.86%   |
| 2007 | 5         | 2.42%   |
| 2023 | 3         | 1.45%   |
| 2006 | 2         | 0.97%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 207       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 202       | 97.58%  |
| Yes  | 5         | 2.42%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 73        | 35.27%  |
| 4.01-8.0    | 66        | 31.88%  |
| 16.01-24.0  | 39        | 18.84%  |
| 2.01-3.0    | 16        | 7.73%   |
| 32.01-64.0  | 6         | 2.9%    |
| 3.01-4.0    | 6         | 2.9%    |
| 64.01-256.0 | 1         | 0.48%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 130       | 62.8%   |
| 0.51-1.0 | 57        | 27.54%  |
| 1.01-2.0 | 16        | 7.73%   |
| 2.01-3.0 | 4         | 1.93%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 150       | 71.77%  |
| 2      | 37        | 17.7%   |
| 0      | 17        | 8.13%   |
| 3      | 5         | 2.39%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 134       | 64.73%  |
| Yes       | 73        | 35.27%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 183       | 88.41%  |
| No        | 24        | 11.59%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 200       | 96.62%  |
| No        | 7         | 3.38%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 146       | 70.53%  |
| No        | 61        | 29.47%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country             | Notebooks | Percent |
|---------------------|-----------|---------|
| USA                 | 31        | 14.98%  |
| Russia              | 20        | 9.66%   |
| Germany             | 17        | 8.21%   |
| Poland              | 15        | 7.25%   |
| Brazil              | 14        | 6.76%   |
| UK                  | 9         | 4.35%   |
| Italy               | 8         | 3.86%   |
| Indonesia           | 8         | 3.86%   |
| Spain               | 7         | 3.38%   |
| China               | 6         | 2.9%    |
| Turkey              | 5         | 2.42%   |
| France              | 5         | 2.42%   |
| Canada              | 5         | 2.42%   |
| Romania             | 4         | 1.93%   |
| Netherlands         | 4         | 1.93%   |
| India               | 4         | 1.93%   |
| Australia           | 4         | 1.93%   |
| Mexico              | 3         | 1.45%   |
| Hungary             | 3         | 1.45%   |
| Finland             | 3         | 1.45%   |
| Ukraine             | 2         | 0.97%   |
| Switzerland         | 2         | 0.97%   |
| South Korea         | 2         | 0.97%   |
| Portugal            | 2         | 0.97%   |
| Lithuania           | 2         | 0.97%   |
| Israel              | 2         | 0.97%   |
| Colombia            | 2         | 0.97%   |
| Bulgaria            | 2         | 0.97%   |
| Trinidad and Tobago | 1         | 0.48%   |
| Syria               | 1         | 0.48%   |
| Slovenia            | 1         | 0.48%   |
| Slovakia            | 1         | 0.48%   |
| Philippines         | 1         | 0.48%   |
| Kazakhstan          | 1         | 0.48%   |
| Jamaica             | 1         | 0.48%   |
| Ireland             | 1         | 0.48%   |
| Greece              | 1         | 0.48%   |
| Czechia             | 1         | 0.48%   |
| Cyprus              | 1         | 0.48%   |
| Chile               | 1         | 0.48%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City          | Notebooks | Percent |
|---------------|-----------|---------|
| Sao Paulo     | 4         | 1.9%    |
| Wroclaw       | 3         | 1.43%   |
| St Petersburg | 3         | 1.43%   |
| Moscow        | 3         | 1.43%   |
| Berlin        | 3         | 1.43%   |
| Warsaw        | 2         | 0.95%   |
| Vilnius       | 2         | 0.95%   |
| Valencia      | 2         | 0.95%   |
| Sydney        | 2         | 0.95%   |
| Shenzhen      | 2         | 0.95%   |
| Peterborough  | 2         | 0.95%   |
| Montreal      | 2         | 0.95%   |
| Milan         | 2         | 0.95%   |
| Lisbon        | 2         | 0.95%   |
| Irkutsk       | 2         | 0.95%   |
| Budapest      | 2         | 0.95%   |
| Ankara        | 2         | 0.95%   |
| Zurich        | 1         | 0.48%   |
| Zele          | 1         | 0.48%   |
| Zarautz       | 1         | 0.48%   |
| Yuseong-gu    | 1         | 0.48%   |
| Yogyakarta    | 1         | 0.48%   |
| Yeosu         | 1         | 0.48%   |
| Yekaterinburg | 1         | 0.48%   |
| Woodbridge    | 1         | 0.48%   |
| Whitby        | 1         | 0.48%   |
| West Plains   | 1         | 0.48%   |
| Wausau        | 1         | 0.48%   |
| Vitória      | 1         | 0.48%   |
| Vitebsk       | 1         | 0.48%   |
| Villemomble   | 1         | 0.48%   |
| Villefontaine | 1         | 0.48%   |
| Victoria      | 1         | 0.48%   |
| Ulyanovsk     | 1         | 0.48%   |
| Ufa           | 1         | 0.48%   |
| Twinsburg     | 1         | 0.48%   |
| Tver          | 1         | 0.48%   |
| Trindade      | 1         | 0.48%   |
| Tomasikovo    | 1         | 0.48%   |
| Tolyatti      | 1         | 0.48%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 36        | 39     | 15.52%  |
| Toshiba             | 21        | 23     | 9.05%   |
| Seagate             | 21        | 22     | 9.05%   |
| WDC                 | 20        | 21     | 8.62%   |
| SanDisk             | 17        | 17     | 7.33%   |
| Kingston            | 16        | 16     | 6.9%    |
| Hitachi             | 15        | 15     | 6.47%   |
| Crucial             | 11        | 13     | 4.74%   |
| HGST                | 7         | 10     | 3.02%   |
| A-DATA Technology   | 6         | 6      | 2.59%   |
| SK hynix            | 5         | 5      | 2.16%   |
| Micron Technology   | 5         | 5      | 2.16%   |
| Intel               | 5         | 5      | 2.16%   |
| SPCC                | 3         | 3      | 1.29%   |
| GOODRAM             | 3         | 3      | 1.29%   |
| Fujitsu             | 3         | 3      | 1.29%   |
| China               | 3         | 3      | 1.29%   |
| Transcend           | 2         | 2      | 0.86%   |
| Patriot             | 2         | 2      | 0.86%   |
| OCZ                 | 2         | 2      | 0.86%   |
| Intenso             | 2         | 2      | 0.86%   |
| Gigabyte Technology | 2         | 2      | 0.86%   |
| BHT                 | 2         | 2      | 0.86%   |
| Apple               | 2         | 2      | 0.86%   |
| Verbatim            | 1         | 1      | 0.43%   |
| V-GeN               | 1         | 1      | 0.43%   |
| UMIS                | 1         | 1      | 0.43%   |
| Team                | 1         | 1      | 0.43%   |
| SSSTC               | 1         | 1      | 0.43%   |
| Silicon Motion      | 1         | 1      | 0.43%   |
| SemsoTai            | 1         | 1      | 0.43%   |
| PNY                 | 1         | 1      | 0.43%   |
| Plextor             | 1         | 1      | 0.43%   |
| Phison              | 1         | 1      | 0.43%   |
| Netac               | 1         | 1      | 0.43%   |
| MidasForce          | 1         | 1      | 0.43%   |
| Maxtor              | 1         | 1      | 0.43%   |
| KingSpec            | 1         | 1      | 0.43%   |
| Kingmax             | 1         | 1      | 0.43%   |
| Goldenfir           | 1         | 1      | 0.43%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB            | 4         | 1.7%    |
| Crucial CT480BX500SSD1 480GB         | 4         | 1.7%    |
| Toshiba MQ01ABF050 500GB             | 3         | 1.28%   |
| Kingston SA400S37240G 240GB          | 3         | 1.28%   |
| Toshiba MQ01ABD100 1TB               | 2         | 0.85%   |
| Seagate ST9500325AS 500GB            | 2         | 0.85%   |
| Seagate ST9250410AS 250GB            | 2         | 0.85%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 2         | 0.85%   |
| SanDisk SSD PLUS 120GB               | 2         | 0.85%   |
| Samsung MZVLB256HAHQ-000H1 256GB     | 2         | 0.85%   |
| Samsung HM321HI 320GB                | 2         | 0.85%   |
| Samsung HM160HI 160GB                | 2         | 0.85%   |
| Micron 1100 SATA 256GB               | 2         | 0.85%   |
| Kingston SV300S37A60G 64GB           | 2         | 0.85%   |
| Kingston SV300S37A240G 240GB         | 2         | 0.85%   |
| Hitachi HTS545050B9A300 500GB        | 2         | 0.85%   |
| Hitachi HTS545032B9A300 320GB        | 2         | 0.85%   |
| Hitachi HTS542525K9A300 250GB        | 2         | 0.85%   |
| HGST HTS725050A7E630 500GB           | 2         | 0.85%   |
| HGST HTS545050A7E380 500GB           | 2         | 0.85%   |
| Gigabyte GP-GSTFS31120GNTD 120GB     | 2         | 0.85%   |
| Crucial CT120BX500SSD1 120GB         | 2         | 0.85%   |
| WDC WDS500G2B0B-00YS70 500GB         | 1         | 0.43%   |
| WDC WDS240G2G0A-00JH30 240GB         | 1         | 0.43%   |
| WDC WDS120G1G0A-00SS50 120GB         | 1         | 0.43%   |
| WDC WDS100T2G0A-00JH30 1TB           | 1         | 0.43%   |
| WDC WD5000LPCX-60VHAT0 500GB         | 1         | 0.43%   |
| WDC WD5000LPCX-24VHAT0 500GB         | 1         | 0.43%   |
| WDC WD3200BPVT-80ZEST0 320GB         | 1         | 0.43%   |
| WDC WD3200BPVT-22JJ5T0 320GB         | 1         | 0.43%   |
| WDC WD3200BEVT-60ZCT1 320GB          | 1         | 0.43%   |
| WDC WD30PURZ-85AKKY0 3TB             | 1         | 0.43%   |
| WDC WD2500BEVT-22ZCT0 250GB          | 1         | 0.43%   |
| WDC WD1600BEVT-60ZCT0 160GB          | 1         | 0.43%   |
| WDC WD1600BEVS-22VAT0 160GB          | 1         | 0.43%   |
| WDC WD10SPZX-00Z10T0 1TB             | 1         | 0.43%   |
| WDC WD10JPVX-80JC3T0 1TB             | 1         | 0.43%   |
| WDC WD10JPVX-75JC3T0 1TB             | 1         | 0.43%   |
| WDC WD10JPVX-60JC3T1 1TB             | 1         | 0.43%   |
| WDC PC SN730 SDBPNTY-512G-1101 512GB | 1         | 0.43%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 21        | 22     | 24.42%  |
| Toshiba             | 19        | 21     | 22.09%  |
| Hitachi             | 15        | 15     | 17.44%  |
| WDC                 | 13        | 13     | 15.12%  |
| HGST                | 7         | 10     | 8.14%   |
| Samsung Electronics | 6         | 7      | 6.98%   |
| Fujitsu             | 3         | 3      | 3.49%   |
| Maxtor              | 1         | 1      | 1.16%   |
| Apple               | 1         | 1      | 1.16%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SanDisk             | 17        | 17     | 15.18%  |
| Samsung Electronics | 16        | 17     | 14.29%  |
| Kingston            | 15        | 15     | 13.39%  |
| Crucial             | 10        | 12     | 8.93%   |
| A-DATA Technology   | 5         | 5      | 4.46%   |
| Intel               | 4         | 4      | 3.57%   |
| WDC                 | 3         | 4      | 2.68%   |
| SPCC                | 3         | 3      | 2.68%   |
| Micron Technology   | 3         | 3      | 2.68%   |
| GOODRAM             | 3         | 3      | 2.68%   |
| China               | 3         | 3      | 2.68%   |
| Patriot             | 2         | 2      | 1.79%   |
| OCZ                 | 2         | 2      | 1.79%   |
| Intenso             | 2         | 2      | 1.79%   |
| Gigabyte Technology | 2         | 2      | 1.79%   |
| BHT                 | 2         | 2      | 1.79%   |
| Verbatim            | 1         | 1      | 0.89%   |
| V-GeN               | 1         | 1      | 0.89%   |
| Transcend           | 1         | 1      | 0.89%   |
| Toshiba             | 1         | 1      | 0.89%   |
| Team                | 1         | 1      | 0.89%   |
| SSSTC               | 1         | 1      | 0.89%   |
| SK hynix            | 1         | 1      | 0.89%   |
| SemsoTai            | 1         | 1      | 0.89%   |
| PNY                 | 1         | 1      | 0.89%   |
| Plextor             | 1         | 1      | 0.89%   |
| Netac               | 1         | 1      | 0.89%   |
| MidasForce          | 1         | 1      | 0.89%   |
| KingSpec            | 1         | 1      | 0.89%   |
| Kingmax             | 1         | 1      | 0.89%   |
| Goldenfir           | 1         | 1      | 0.89%   |
| faspeed             | 1         | 1      | 0.89%   |
| Dogfish             | 1         | 1      | 0.89%   |
| Biostar             | 1         | 1      | 0.89%   |
| Apple               | 1         | 1      | 0.89%   |
| Apacer              | 1         | 1      | 0.89%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 103       | 116    | 47.47%  |
| HDD  | 82        | 93     | 37.79%  |
| NVMe | 32        | 35     | 14.75%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 165       | 209    | 83.76%  |
| NVMe | 32        | 35     | 16.24%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 147       | 173    | 83.05%  |
| 0.51-1.0   | 28        | 34     | 15.82%  |
| 2.01-3.0   | 1         | 1      | 0.56%   |
| 1.01-2.0   | 1         | 1      | 0.56%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 97        | 46.41%  |
| 101-250    | 38        | 18.18%  |
| 251-500    | 29        | 13.88%  |
| 51-100     | 29        | 13.88%  |
| 501-1000   | 8         | 3.83%   |
| 21-50      | 7         | 3.35%   |
| Unknown    | 1         | 0.48%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 204       | 98.55%  |
| 21-50   | 1         | 0.48%   |
| 101-250 | 1         | 0.48%   |
| Unknown | 1         | 0.48%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB           | 2         | 2      | 4.35%   |
| Hitachi HTS542525K9A300 250GB       | 2         | 2      | 4.35%   |
| WDC WDS240G2G0A-00JH30 240GB        | 1         | 1      | 2.17%   |
| WDC WD3200BPVT-80ZEST0 320GB        | 1         | 1      | 2.17%   |
| WDC WD30PURZ-85AKKY0 3TB            | 1         | 1      | 2.17%   |
| WDC WD10JPVX-60JC3T1 1TB            | 1         | 1      | 2.17%   |
| Toshiba MQ01ABF050 500GB            | 1         | 1      | 2.17%   |
| Toshiba MQ01ABD100 1TB              | 1         | 1      | 2.17%   |
| Toshiba MQ01ABD032 320GB            | 1         | 1      | 2.17%   |
| Toshiba MK5065GSX 500GB             | 1         | 1      | 2.17%   |
| Toshiba MK5059GSXP 500GB            | 1         | 1      | 2.17%   |
| Toshiba MK1646GSX 160GB             | 1         | 1      | 2.17%   |
| Toshiba MK1229GSG 120GB             | 1         | 1      | 2.17%   |
| SSSTC CVB-8D128-HP 128GB            | 1         | 1      | 2.17%   |
| SK hynix SC210 mSATA 256GB          | 1         | 1      | 2.17%   |
| Seagate ST9250410AS 250GB           | 1         | 1      | 2.17%   |
| Seagate ST9160827AS 160GB           | 1         | 1      | 2.17%   |
| Seagate ST9160314AS 160GB           | 1         | 1      | 2.17%   |
| Seagate ST750LM022 HN-M750MBB 752GB | 1         | 1      | 2.17%   |
| Seagate ST500LM000-SSHD-8GB         | 1         | 1      | 2.17%   |
| Seagate ST500LM000-1EJ162-SSHD-8GB  | 1         | 1      | 2.17%   |
| Seagate ST500LM000-1EJ162 500GB     | 1         | 1      | 2.17%   |
| Seagate ST320LT020-9YG142 320GB     | 1         | 1      | 2.17%   |
| Seagate ST320LT012-9WS14C 320GB     | 1         | 2      | 2.17%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 1         | 1      | 2.17%   |
| Samsung Electronics HM321HI 320GB   | 1         | 1      | 2.17%   |
| Samsung Electronics HM160HI 160GB   | 1         | 1      | 2.17%   |
| OCZ AGILITY3 120GB                  | 1         | 1      | 2.17%   |
| Kingston SV300S37A60G 64GB          | 1         | 1      | 2.17%   |
| Intel SSDSC2BF180A4L 180GB          | 1         | 1      | 2.17%   |
| Hitachi HTS727550A9E364 500GB       | 1         | 1      | 2.17%   |
| Hitachi HTS721060G9SA00 64GB        | 1         | 1      | 2.17%   |
| Hitachi HTS547575A9E384 752GB       | 1         | 1      | 2.17%   |
| Hitachi HTS547550A9E384 500GB       | 1         | 1      | 2.17%   |
| Hitachi HTS545050B9A300 500GB       | 1         | 1      | 2.17%   |
| Hitachi HTS545050A7E380 500GB       | 1         | 1      | 2.17%   |
| Hitachi HTS542512K9SA00 120GB       | 1         | 1      | 2.17%   |
| Hitachi HTS541616J9SA00 160GB       | 1         | 1      | 2.17%   |
| HGST HTS725050A7E630 500GB          | 1         | 1      | 2.17%   |
| HGST HTS545050A7E380 500GB          | 1         | 1      | 2.17%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 12        | 13     | 26.09%  |
| Hitachi             | 10        | 10     | 21.74%  |
| Toshiba             | 7         | 7      | 15.22%  |
| WDC                 | 4         | 4      | 8.7%    |
| HGST                | 4         | 5      | 8.7%    |
| Samsung Electronics | 2         | 2      | 4.35%   |
| Crucial             | 2         | 3      | 4.35%   |
| SSSTC               | 1         | 1      | 2.17%   |
| SK hynix            | 1         | 1      | 2.17%   |
| OCZ                 | 1         | 1      | 2.17%   |
| Kingston            | 1         | 1      | 2.17%   |
| Intel               | 1         | 1      | 2.17%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 12        | 13     | 31.58%  |
| Hitachi             | 10        | 10     | 26.32%  |
| Toshiba             | 7         | 7      | 18.42%  |
| HGST                | 4         | 5      | 10.53%  |
| WDC                 | 3         | 3      | 7.89%   |
| Samsung Electronics | 2         | 2      | 5.26%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 36        | 40     | 81.82%  |
| SSD  | 8         | 9      | 18.18%  |

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
| Works   | 158       | 194    | 77.83%  |
| Malfunc | 44        | 49     | 21.67%  |
| Failed  | 1         | 1      | 0.49%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 165       | 73.33%  |
| AMD                                     | 17        | 7.56%   |
| Samsung Electronics                     | 13        | 5.78%   |
| SanDisk                                 | 7         | 3.11%   |
| Nvidia                                  | 6         | 2.67%   |
| SK hynix                                | 4         | 1.78%   |
| Silicon Motion                          | 3         | 1.33%   |
| Micron Technology                       | 2         | 0.89%   |
| Toshiba                                 | 1         | 0.44%   |
| Silicon Integrated Systems [SiS]        | 1         | 0.44%   |
| Shenzhen Unionmemory Information System | 1         | 0.44%   |
| Phison Electronics                      | 1         | 0.44%   |
| Micron/Crucial Technology               | 1         | 0.44%   |
| MAXIO Technology (Hangzhou)             | 1         | 0.44%   |
| Kingston Technology Company             | 1         | 0.44%   |
| ADATA Technology                        | 1         | 0.44%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 24        | 9.88%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 18        | 7.41%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 18        | 7.41%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 16        | 6.58%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 14        | 5.76%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 13        | 5.35%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 8         | 3.29%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 7         | 2.88%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 7         | 2.88%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 7         | 2.88%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 7         | 2.88%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 6         | 2.47%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 6         | 2.47%   |
| Nvidia MCP79 AHCI Controller                                                     | 5         | 2.06%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 5         | 2.06%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 5         | 2.06%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 4         | 1.65%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 4         | 1.65%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 3         | 1.23%   |
| Intel Comet Lake SATA AHCI Controller                                            | 3         | 1.23%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 3         | 1.23%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 3         | 1.23%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 1.23%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 2         | 0.82%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                            | 2         | 0.82%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                            | 2         | 0.82%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2         | 0.82%   |
| Intel Volume Management Device NVMe RAID Controller                              | 2         | 0.82%   |
| Intel Tiger Lake-LP SATA Controller                                              | 2         | 0.82%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 2         | 0.82%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                 | 2         | 0.82%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 2         | 0.82%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 2         | 0.82%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 2         | 0.82%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 2         | 0.82%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 2         | 0.82%   |
| Toshiba XG6 NVMe SSD Controller                                                  | 1         | 0.41%   |
| SK hynix PC601 NVMe Solid State Drive                                            | 1         | 0.41%   |
| SK hynix BC511 NVMe SSD                                                          | 1         | 0.41%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 0.41%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 173       | 73.93%  |
| NVMe | 32        | 13.68%  |
| IDE  | 20        | 8.55%   |
| RAID | 9         | 3.85%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 185       | 89.37%  |
| AMD    | 22        | 10.63%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Intel Core i5-6300U CPU @ 2.40GHz        | 6         | 2.9%    |
| Intel Core i5-2520M CPU @ 2.50GHz        | 6         | 2.9%    |
| Intel CPU Version                        | 5         | 2.42%   |
| Intel Celeron CPU N3060 @ 1.60GHz        | 5         | 2.42%   |
| Intel Core i7-8550U CPU @ 1.80GHz        | 4         | 1.93%   |
| Intel Core i5-5200U CPU @ 2.20GHz        | 4         | 1.93%   |
| Intel Core 2 Duo CPU P7350 @ 2.00GHz     | 4         | 1.93%   |
| Intel Core i7-5500U CPU @ 2.40GHz        | 3         | 1.45%   |
| Intel Core i7-3520M CPU @ 2.90GHz        | 3         | 1.45%   |
| Intel Core i5-7200U CPU @ 2.50GHz        | 3         | 1.45%   |
| Intel Core i5-4210U CPU @ 1.70GHz        | 3         | 1.45%   |
| Intel Core i5-3337U CPU @ 1.80GHz        | 3         | 1.45%   |
| Intel Core i5-3320M CPU @ 2.60GHz        | 3         | 1.45%   |
| Intel Core i5-3210M CPU @ 2.50GHz        | 3         | 1.45%   |
| Intel Core i5-10210U CPU @ 1.60GHz       | 3         | 1.45%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz     | 3         | 1.45%   |
| Intel Celeron CPU N2840 @ 2.16GHz        | 3         | 1.45%   |
| Intel Pentium CPU P6200 @ 2.13GHz        | 2         | 0.97%   |
| Intel Core i7-8750H CPU @ 2.20GHz        | 2         | 0.97%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz       | 2         | 0.97%   |
| Intel Core i7-4500U CPU @ 1.80GHz        | 2         | 0.97%   |
| Intel Core i7-2670QM CPU @ 2.20GHz       | 2         | 0.97%   |
| Intel Core i5-7300U CPU @ 2.60GHz        | 2         | 0.97%   |
| Intel Core i5-2540M CPU @ 2.60GHz        | 2         | 0.97%   |
| Intel Core i5-2410M CPU @ 2.30GHz        | 2         | 0.97%   |
| Intel Core i5 CPU M 520 @ 2.40GHz        | 2         | 0.97%   |
| Intel Core i5 CPU M 430 @ 2.27GHz        | 2         | 0.97%   |
| Intel Core i3-4030U CPU @ 1.90GHz        | 2         | 0.97%   |
| Intel Core i3-2310M CPU @ 2.10GHz        | 2         | 0.97%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz     | 2         | 0.97%   |
| Intel Core 2 Duo CPU T7100 @ 1.80GHz     | 2         | 0.97%   |
| Intel Core 2 CPU                         | 2         | 0.97%   |
| Intel Celeron N4000 CPU @ 1.10GHz        | 2         | 0.97%   |
| Intel Celeron CPU N3350 @ 1.10GHz        | 2         | 0.97%   |
| Intel Atom CPU N570 @ 1.66GHz            | 2         | 0.97%   |
| Intel Atom CPU N450 @ 1.66GHz            | 2         | 0.97%   |
| AMD Ryzen 7 5800H with Radeon Graphics   | 2         | 0.97%   |
| AMD Ryzen 7 4700U with Radeon Graphics   | 2         | 0.97%   |
| Intel Xeon CPU E3-1535M v5 @ 2.90GHz     | 1         | 0.48%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz | 1         | 0.48%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 59        | 28.5%   |
| Intel Core i7           | 35        | 16.91%  |
| Intel Celeron           | 22        | 10.63%  |
| Intel Core 2 Duo        | 19        | 9.18%   |
| Intel Core i3           | 14        | 6.76%   |
| Other                   | 12        | 5.8%    |
| Intel Atom              | 6         | 2.9%    |
| AMD Ryzen 7             | 6         | 2.9%    |
| Intel Pentium           | 5         | 2.42%   |
| Intel Pentium Dual-Core | 3         | 1.45%   |
| AMD Ryzen 5             | 3         | 1.45%   |
| Intel Pentium Dual      | 2         | 0.97%   |
| Intel Genuine           | 2         | 0.97%   |
| Intel Core 2            | 2         | 0.97%   |
| AMD Athlon              | 2         | 0.97%   |
| Intel Xeon              | 1         | 0.48%   |
| Intel Pentium Silver    | 1         | 0.48%   |
| Intel Pentium Gold      | 1         | 0.48%   |
| Intel Celeron Dual-Core | 1         | 0.48%   |
| Intel Celeron D         | 1         | 0.48%   |
| AMD Ryzen Embedded      | 1         | 0.48%   |
| AMD Ryzen 3             | 1         | 0.48%   |
| AMD Phenom II           | 1         | 0.48%   |
| AMD E2                  | 1         | 0.48%   |
| AMD E1                  | 1         | 0.48%   |
| AMD E                   | 1         | 0.48%   |
| AMD A8                  | 1         | 0.48%   |
| AMD A6                  | 1         | 0.48%   |
| AMD A4                  | 1         | 0.48%   |
| AMD A10                 | 1         | 0.48%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 122       | 58.94%  |
| 4       | 42        | 20.29%  |
| Unknown | 26        | 12.56%  |
| 1       | 5         | 2.42%   |
| 16      | 4         | 1.93%   |
| 8       | 4         | 1.93%   |
| 12      | 2         | 0.97%   |
| 6       | 2         | 0.97%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 200       | 96.62%  |
| 2       | 6         | 2.9%    |
| Unknown | 1         | 0.48%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 121       | 58.45%  |
| 1       | 57        | 27.54%  |
| Unknown | 29        | 14.01%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 28        | 13.53%  |
| SandyBridge   | 22        | 10.63%  |
| IvyBridge     | 22        | 10.63%  |
| Penryn        | 18        | 8.7%    |
| Haswell       | 18        | 8.7%    |
| Core          | 16        | 7.73%   |
| Westmere      | 11        | 5.31%   |
| Skylake       | 10        | 4.83%   |
| Silvermont    | 9         | 4.35%   |
| Broadwell     | 9         | 4.35%   |
| Bonnell       | 7         | 3.38%   |
| TigerLake     | 6         | 2.9%    |
| Zen+          | 4         | 1.93%   |
| Goldmont plus | 4         | 1.93%   |
| Zen 3         | 3         | 1.45%   |
| Zen 2         | 3         | 1.45%   |
| Excavator     | 3         | 1.45%   |
| Bobcat        | 3         | 1.45%   |
| Unknown       | 3         | 1.45%   |
| Goldmont      | 2         | 0.97%   |
| Zen           | 1         | 0.48%   |
| Piledriver    | 1         | 0.48%   |
| Nehalem       | 1         | 0.48%   |
| K10 Llano     | 1         | 0.48%   |
| K10           | 1         | 0.48%   |
| CometLake     | 1         | 0.48%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 167       | 69.29%  |
| Nvidia                           | 39        | 16.18%  |
| AMD                              | 34        | 14.11%  |
| Silicon Integrated Systems [SiS] | 1         | 0.41%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 22        | 8.7%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 21        | 8.3%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 13        | 5.14%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 10        | 3.95%   |
| Intel Core Processor Integrated Graphics Controller                                      | 10        | 3.95%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 9         | 3.56%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 9         | 3.56%   |
| Intel HD Graphics 5500                                                                   | 9         | 3.56%   |
| Intel UHD Graphics 620                                                                   | 8         | 3.16%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 7         | 2.77%   |
| Intel HD Graphics 620                                                                    | 7         | 2.77%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 6         | 2.37%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 6         | 2.37%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 1.98%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 4         | 1.58%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 1.58%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 4         | 1.58%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 1.58%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 1.19%   |
| Nvidia C79 [GeForce 9400M]                                                               | 3         | 1.19%   |
| Intel HD Graphics 630                                                                    | 3         | 1.19%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 1.19%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 1.19%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 3         | 1.19%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 3         | 1.19%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 0.79%   |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 0.79%   |
| Nvidia GF116M [GeForce GT 560M]                                                          | 2         | 0.79%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 0.79%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 2         | 0.79%   |
| Intel HD Graphics 500                                                                    | 2         | 0.79%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 2         | 0.79%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 2         | 0.79%   |
| AMD Lucienne                                                                             | 2         | 0.79%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 2         | 0.79%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 1         | 0.4%    |
| Nvidia TU117M [GeForce MX450]                                                            | 1         | 0.4%    |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 0.4%    |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 1         | 0.4%    |
| Nvidia MCP79 [GeForce 8200M G]                                                           | 1         | 0.4%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 109       | 52.66%  |
| 2 x Intel      | 26        | 12.56%  |
| Intel + Nvidia | 25        | 12.08%  |
| 1 x AMD        | 24        | 11.59%  |
| 1 x Nvidia     | 11        | 5.31%   |
| Intel + AMD    | 7         | 3.38%   |
| AMD + Nvidia   | 2         | 0.97%   |
| 2 x Nvidia     | 1         | 0.48%   |
| 2 x AMD        | 1         | 0.48%   |
| 1 x SiS        | 1         | 0.48%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 188       | 90.82%  |
| Proprietary | 11        | 5.31%   |
| Unknown     | 8         | 3.86%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 188       | 90.82%  |
| 0.01-0.5   | 12        | 5.8%    |
| 0.51-1.0   | 5         | 2.42%   |
| 7.01-8.0   | 1         | 0.48%   |
| 1.01-2.0   | 1         | 0.48%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 25        | 27.17%  |
| Samsung Electronics     | 12        | 13.04%  |
| Chimei Innolux          | 12        | 13.04%  |
| LG Display              | 10        | 10.87%  |
| BOE                     | 10        | 10.87%  |
| Lenovo                  | 4         | 4.35%   |
| InfoVision              | 3         | 3.26%   |
| Chi Mei Optoelectronics | 3         | 3.26%   |
| Apple                   | 3         | 3.26%   |
| Sharp                   | 2         | 2.17%   |
| Goldstar                | 2         | 2.17%   |
| LG Philips              | 1         | 1.09%   |
| Daewoo                  | 1         | 1.09%   |
| CPT                     | 1         | 1.09%   |
| AOC                     | 1         | 1.09%   |
| Acer                    | 1         | 1.09%   |
| Unknown                 | 1         | 1.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch         | 3         | 3.26%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 340x190mm 15.3-inch  | 2         | 2.17%   |
| Lenovo LCD Monitor LEN4022 1400x1050 290x210mm 14.1-inch              | 2         | 2.17%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 310x170mm 13.9-inch        | 2         | 2.17%   |
| Sharp LQ133M1JW01 SHP141B 1920x1080 290x170mm 13.2-inch               | 1         | 1.09%   |
| Sharp LCD Monitor SHP143B 3840x2160 350x190mm 15.7-inch               | 1         | 1.09%   |
| Samsung Electronics SyncMaster SAM058D 1600x900 440x250mm 19.9-inch   | 1         | 1.09%   |
| Samsung Electronics LF27T370F SAM711E 1920x1080 600x340mm 27.2-inch   | 1         | 1.09%   |
| Samsung Electronics LCD Monitor SEC384A 1366x768 340x190mm 15.3-inch  | 1         | 1.09%   |
| Samsung Electronics LCD Monitor SEC3541 1366x768 300x170mm 13.6-inch  | 1         | 1.09%   |
| Samsung Electronics LCD Monitor SEC3052 1024x600 220x130mm 10.1-inch  | 1         | 1.09%   |
| Samsung Electronics LCD Monitor SEC3051 1600x900 390x230mm 17.8-inch  | 1         | 1.09%   |
| Samsung Electronics LCD Monitor SEC3050 1366x768 320x190mm 14.7-inch  | 1         | 1.09%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch  | 1         | 1.09%   |
| Samsung Electronics LCD Monitor SDC424A 3200x1800 290x170mm 13.2-inch | 1         | 1.09%   |
| Samsung Electronics C32HG7x SAM0E13 2560x1440 700x390mm 31.5-inch     | 1         | 1.09%   |
| LG Philips LP154WX4-TLCB LPL3101 1280x800 330x210mm 15.4-inch         | 1         | 1.09%   |
| LG Display LCD Monitor LGD04E8 1920x1080 380x210mm 17.1-inch          | 1         | 1.09%   |
| LG Display LCD Monitor LGD044B 1366x768 340x190mm 15.3-inch           | 1         | 1.09%   |
| LG Display LCD Monitor LGD03DB 1366x768 350x190mm 15.7-inch           | 1         | 1.09%   |
| LG Display LCD Monitor LGD0384 1366x768 340x190mm 15.3-inch           | 1         | 1.09%   |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch           | 1         | 1.09%   |
| LG Display LCD Monitor LGD02E3 1366x768 340x190mm 15.3-inch           | 1         | 1.09%   |
| LG Display LCD Monitor LGD02DC 1366x768 340x190mm 15.3-inch           | 1         | 1.09%   |
| LG Display LCD Monitor LGD02D1 1600x900 380x210mm 17.1-inch           | 1         | 1.09%   |
| LG Display LCD Monitor LGD027A 1600x900 380x210mm 17.1-inch           | 1         | 1.09%   |
| LG Display LCD Monitor LGD024D 1366x768 290x170mm 13.2-inch           | 1         | 1.09%   |
| Lenovo LCD Monitor LEN4057 1280x800 330x210mm 15.4-inch               | 1         | 1.09%   |
| Lenovo LCD Monitor LEN4010 1280x800 260x160mm 12.0-inch               | 1         | 1.09%   |
| InfoVision LCD Monitor IVO0533 1366x768 290x170mm 13.2-inch           | 1         | 1.09%   |
| InfoVision LCD Monitor IVO048E 1366x768 260x140mm 11.6-inch           | 1         | 1.09%   |
| InfoVision LCD Monitor IVO03F4 1024x600 220x130mm 10.1-inch           | 1         | 1.09%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch          | 1         | 1.09%   |
| Goldstar LG FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch             | 1         | 1.09%   |
| Daewoo HDMI DWE2100 1280x1024 470x260mm 21.1-inch                     | 1         | 1.09%   |
| CPT LCD Monitor CPT1BC0 1024x600 220x120mm 9.9-inch                   | 1         | 1.09%   |
| Chimei Innolux LCD Monitor CMN175A 1920x1080 380x210mm 17.1-inch      | 1         | 1.09%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 380x210mm 17.1-inch      | 1         | 1.09%   |
| Chimei Innolux LCD Monitor CMN15F4 1920x1080 340x190mm 15.3-inch      | 1         | 1.09%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 340x190mm 15.3-inch       | 1         | 1.09%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1366x768 (WXGA)  | 38        | 42.22%  |
| 1920x1080 (FHD)  | 30        | 33.33%  |
| 1600x900 (HD+)   | 6         | 6.67%   |
| 1280x800 (WXGA)  | 5         | 5.56%   |
| 1024x600         | 3         | 3.33%   |
| 2560x1600        | 2         | 2.22%   |
| 1400x1050        | 2         | 2.22%   |
| 3840x2160 (4K)   | 1         | 1.11%   |
| 3200x1800 (QHD+) | 1         | 1.11%   |
| 2560x1440 (QHD)  | 1         | 1.11%   |
| 1280x1024 (SXGA) | 1         | 1.11%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 31        | 33.7%   |
| 13      | 27        | 29.35%  |
| 17      | 9         | 9.78%   |
| 12      | 6         | 6.52%   |
| 21      | 4         | 4.35%   |
| 14      | 4         | 4.35%   |
| 11      | 3         | 3.26%   |
| 27      | 2         | 2.17%   |
| 10      | 2         | 2.17%   |
| 31      | 1         | 1.09%   |
| 19      | 1         | 1.09%   |
| 9       | 1         | 1.09%   |
| Unknown | 1         | 1.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 51        | 55.43%  |
| 201-300     | 23        | 25%     |
| 351-400     | 9         | 9.78%   |
| 401-500     | 5         | 5.43%   |
| 501-600     | 2         | 2.17%   |
| 601-700     | 1         | 1.09%   |
| Unknown     | 1         | 1.09%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 79        | 89.77%  |
| 16/10   | 6         | 6.82%   |
| 4/3     | 2         | 2.27%   |
| Unknown | 1         | 1.14%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 91-100         | 28        | 30.43%  |
| 81-90          | 22        | 23.91%  |
| 121-130        | 8         | 8.7%    |
| 71-80          | 6         | 6.52%   |
| 61-70          | 6         | 6.52%   |
| 101-110        | 6         | 6.52%   |
| 51-60          | 3         | 3.26%   |
| 41-50          | 3         | 3.26%   |
| 201-250        | 3         | 3.26%   |
| 301-350        | 2         | 2.17%   |
| 151-200        | 2         | 2.17%   |
| 351-500        | 1         | 1.09%   |
| 131-140        | 1         | 1.09%   |
| Unknown        | 1         | 1.09%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 40        | 43.48%  |
| 101-120       | 37        | 40.22%  |
| 51-100        | 10        | 10.87%  |
| More than 240 | 2         | 2.17%   |
| 161-240       | 2         | 2.17%   |
| Unknown       | 1         | 1.09%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 181       | 87.44%  |
| 0     | 16        | 7.73%   |
| 2     | 10        | 4.83%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 109       | 33.33%  |
| Realtek Semiconductor             | 89        | 27.22%  |
| Qualcomm Atheros                  | 57        | 17.43%  |
| Broadcom                          | 22        | 6.73%   |
| Marvell Technology Group          | 8         | 2.45%   |
| Samsung Electronics               | 6         | 1.83%   |
| Xiaomi                            | 5         | 1.53%   |
| Sierra Wireless                   | 5         | 1.53%   |
| Nvidia                            | 5         | 1.53%   |
| Ralink                            | 3         | 0.92%   |
| MediaTek                          | 3         | 0.92%   |
| Ericsson Business Mobile Networks | 3         | 0.92%   |
| TP-Link                           | 2         | 0.61%   |
| Ralink Technology                 | 2         | 0.61%   |
| JMicron Technology                | 2         | 0.61%   |
| T & A Mobile Phones               | 1         | 0.31%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.31%   |
| Qualcomm                          | 1         | 0.31%   |
| OPPO Electronics                  | 1         | 0.31%   |
| Edimax Technology                 | 1         | 0.31%   |
| ASUSTek Computer                  | 1         | 0.31%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 51        | 12.41%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 25        | 6.08%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 17        | 4.14%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 15        | 3.65%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 14        | 3.41%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 13        | 3.16%   |
| Intel Wireless 8265 / 8275                                              | 10        | 2.43%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 8         | 1.95%   |
| Intel Wireless 8260                                                     | 8         | 1.95%   |
| Intel Wireless 7265                                                     | 7         | 1.7%    |
| Intel Wireless 7260                                                     | 6         | 1.46%   |
| Intel Ethernet Connection I219-LM                                       | 6         | 1.46%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 6         | 1.46%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 5         | 1.22%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 5         | 1.22%   |
| Nvidia MCP79 Ethernet                                                   | 5         | 1.22%   |
| Intel Wireless 3165                                                     | 5         | 1.22%   |
| Intel Wi-Fi 6 AX201                                                     | 5         | 1.22%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 5         | 1.22%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 4         | 0.97%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 4         | 0.97%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 0.97%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 4         | 0.97%   |
| Intel Wi-Fi 6 AX200                                                     | 4         | 0.97%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 4         | 0.97%   |
| Intel Ethernet Connection I217-LM                                       | 4         | 0.97%   |
| Intel Ethernet Connection (4) I219-LM                                   | 4         | 0.97%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 0.97%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 4         | 0.97%   |
| Intel 82567LM Gigabit Network Connection                                | 4         | 0.97%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 0.73%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 3         | 0.73%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 3         | 0.73%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 3         | 0.73%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 0.73%   |
| Intel Ethernet Connection (4) I219-V                                    | 3         | 0.73%   |
| Intel Ethernet Connection (3) I218-LM                                   | 3         | 0.73%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 0.73%   |
| Intel Centrino Wireless-N 2230                                          | 3         | 0.73%   |
| Intel Centrino Advanced-N 6200                                          | 3         | 0.73%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 104       | 49.06%  |
| Qualcomm Atheros      | 50        | 23.58%  |
| Realtek Semiconductor | 26        | 12.26%  |
| Broadcom              | 18        | 8.49%   |
| Sierra Wireless       | 3         | 1.42%   |
| Ralink                | 3         | 1.42%   |
| TP-Link               | 2         | 0.94%   |
| Ralink Technology     | 2         | 0.94%   |
| MediaTek              | 2         | 0.94%   |
| Edimax Technology     | 1         | 0.47%   |
| ASUSTek Computer      | 1         | 0.47%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 15        | 6.98%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 14        | 6.51%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 13        | 6.05%   |
| Intel Wireless 8265 / 8275                                              | 10        | 4.65%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 8         | 3.72%   |
| Intel Wireless 8260                                                     | 8         | 3.72%   |
| Intel Wireless 7265                                                     | 7         | 3.26%   |
| Intel Wireless 7260                                                     | 6         | 2.79%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 6         | 2.79%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 5         | 2.33%   |
| Intel Wireless 3165                                                     | 5         | 2.33%   |
| Intel Wi-Fi 6 AX201                                                     | 5         | 2.33%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 5         | 2.33%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 1.86%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 4         | 1.86%   |
| Intel Wi-Fi 6 AX200                                                     | 4         | 1.86%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 4         | 1.86%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 1.86%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 4         | 1.86%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 1.4%    |
| Realtek RTL8723DE Wireless Network Adapter                              | 3         | 1.4%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 3         | 1.4%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 3         | 1.4%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 1.4%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 1.4%    |
| Intel Centrino Wireless-N 2230                                          | 3         | 1.4%    |
| Intel Centrino Advanced-N 6200                                          | 3         | 1.4%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3         | 1.4%    |
| Broadcom BCM4331 802.11a/b/g/n                                          | 3         | 1.4%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 2         | 0.93%   |
| Sierra Wireless EM7345 4G LTE                                           | 2         | 0.93%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.93%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.93%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 0.93%   |
| Realtek Realtek Bluetooth 4.2 Adapter                                   | 2         | 0.93%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                               | 2         | 0.93%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 2         | 0.93%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 0.93%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 2         | 0.93%   |
| Intel WiFi Link 5100                                                    | 2         | 0.93%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 77        | 40.53%  |
| Intel                            | 60        | 31.58%  |
| Qualcomm Atheros                 | 15        | 7.89%   |
| Marvell Technology Group         | 8         | 4.21%   |
| Broadcom                         | 7         | 3.68%   |
| Samsung Electronics              | 6         | 3.16%   |
| Xiaomi                           | 5         | 2.63%   |
| Nvidia                           | 5         | 2.63%   |
| JMicron Technology               | 2         | 1.05%   |
| T & A Mobile Phones              | 1         | 0.53%   |
| Silicon Integrated Systems [SiS] | 1         | 0.53%   |
| Qualcomm                         | 1         | 0.53%   |
| OPPO Electronics                 | 1         | 0.53%   |
| MediaTek                         | 1         | 0.53%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 51        | 26.84%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 25        | 13.16%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 17        | 8.95%   |
| Intel Ethernet Connection I219-LM                                 | 6         | 3.16%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 5         | 2.63%   |
| Nvidia MCP79 Ethernet                                             | 5         | 2.63%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 4         | 2.11%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 4         | 2.11%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 2.11%   |
| Intel Ethernet Connection (4) I219-LM                             | 4         | 2.11%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 2.11%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 1.58%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 1.58%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 1.58%   |
| Intel 82566MM Gigabit Network Connection                          | 3         | 1.58%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 1.05%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 1.05%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 1.05%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2         | 1.05%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 2         | 1.05%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 2         | 1.05%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 2         | 1.05%   |
| Intel 82573L Gigabit Ethernet Controller                          | 2         | 1.05%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 1.05%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 2         | 1.05%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.53%   |
| T & A Mobile Phones ALCATEL RNDIS Interface                       | 1         | 0.53%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.53%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.53%   |
| Qualcomm FP3                                                      | 1         | 0.53%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.53%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.53%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.53%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 0.53%   |
| OPPO PGCM10 RNDIS Control RNDIS Ethernet Data                     | 1         | 0.53%   |
| MediaTek USB Ethernet-RNDIS                                       | 1         | 0.53%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 0.53%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 0.53%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller             | 1         | 0.53%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller              | 1         | 0.53%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 200       | 51.41%  |
| Ethernet | 183       | 47.04%  |
| Unknown  | 5         | 1.29%   |
| Modem    | 1         | 0.26%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 104       | 56.22%  |
| Ethernet | 81        | 43.78%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 167       | 80.68%  |
| 1     | 36        | 17.39%  |
| 0     | 3         | 1.45%   |
| 3     | 1         | 0.48%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 191       | 91.83%  |
| Yes  | 17        | 8.17%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 65        | 44.52%  |
| Qualcomm Atheros Communications | 17        | 11.64%  |
| Broadcom                        | 17        | 11.64%  |
| Realtek Semiconductor           | 11        | 7.53%   |
| Apple                           | 9         | 6.16%   |
| Foxconn / Hon Hai               | 7         | 4.79%   |
| IMC Networks                    | 4         | 2.74%   |
| ASUSTek Computer                | 4         | 2.74%   |
| Lite-On Technology              | 3         | 2.05%   |
| Hewlett-Packard                 | 3         | 2.05%   |
| Dell                            | 2         | 1.37%   |
| Cambridge Silicon Radio         | 2         | 1.37%   |
| Askey Computer                  | 1         | 0.68%   |
| Alps Electric                   | 1         | 0.68%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                       | 38        | 25.85%  |
| Intel AX201 Bluetooth                                    | 9         | 6.12%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                    | 8         | 5.44%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 6         | 4.08%   |
| Intel Centrino Bluetooth Wireless Transceiver            | 4         | 2.72%   |
| Intel AX200 Bluetooth                                    | 4         | 2.72%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]               | 4         | 2.72%   |
| Apple Bluetooth Host Controller                          | 4         | 2.72%   |
| Realtek Bluetooth Adapter                                | 3         | 2.04%   |
| Intel Wireless-AC 3168 Bluetooth                         | 3         | 2.04%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]            | 3         | 2.04%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]       | 3         | 2.04%   |
| Broadcom BCM2045B (BDC-2.1)                              | 3         | 2.04%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]         | 3         | 2.04%   |
| ASUS BT-270 Bluetooth Adapter                            | 3         | 2.04%   |
| Apple Built-in iSight (no firmware loaded)               | 3         | 2.04%   |
| Realtek RTL8821A Bluetooth                               | 2         | 1.36%   |
| Realtek Bluetooth 4.2 Adapter                            | 2         | 1.36%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                   | 2         | 1.36%   |
| Qualcomm Atheros AR9462 Bluetooth                        | 2         | 1.36%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter             | 2         | 1.36%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device          | 2         | 1.36%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth USB Device | 2         | 1.36%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 2         | 1.36%   |
| Apple Broadcom Built-in Bluetooth                        | 2         | 1.36%   |
| Realtek RTL8723B Bluetooth                               | 1         | 0.68%   |
| Realtek  Bluetooth 4.2 Adapter                           | 1         | 0.68%   |
| Realtek Bluetooth 4.0 Adapter                            | 1         | 0.68%   |
| Realtek Bluetooth 4.0 + High Speed Chip                  | 1         | 0.68%   |
| Qualcomm Atheros Dell Wireless 1901 Bluetooth            | 1         | 0.68%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE      | 1         | 0.68%   |
| Qualcomm Atheros Dell Wireless 1703 Bluetooth            | 1         | 0.68%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)          | 1         | 0.68%   |
| Qualcomm Atheros AR3011 Bluetooth                        | 1         | 0.68%   |
| Lite-On Qualcomm Atheros Bluetooth 4.0 + HS              | 1         | 0.68%   |
| Lite-On Qualcomm Atheros Bluetooth                       | 1         | 0.68%   |
| Lite-On Atheros AR3012 Bluetooth                         | 1         | 0.68%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter         | 1         | 0.68%   |
| IMC Networks Realtek Bluetooth Adapter                   | 1         | 0.68%   |
| IMC Networks Qualcomm Atheros AR3012 Bluetooth 4.0 + HS  | 1         | 0.68%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 178       | 79.82%  |
| AMD                               | 27        | 12.11%  |
| Nvidia                            | 12        | 5.38%   |
| Texas Instruments                 | 1         | 0.45%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.45%   |
| Phison Electronics                | 1         | 0.45%   |
| Generalplus Technology            | 1         | 0.45%   |
| Elitegroup Computer Systems (ECS) | 1         | 0.45%   |
| Conexant Systems                  | 1         | 0.45%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 25        | 9.33%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 24        | 8.96%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 19        | 7.09%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 16        | 5.97%   |
| Intel 8 Series HD Audio Controller                                                                | 13        | 4.85%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 13        | 4.85%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 12        | 4.48%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 12        | 4.48%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 10        | 3.73%   |
| Intel Broadwell-U Audio Controller                                                                | 9         | 3.36%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 8         | 2.99%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 8         | 2.99%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 7         | 2.61%   |
| Nvidia MCP79 High Definition Audio                                                                | 6         | 2.24%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 6         | 2.24%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 6         | 2.24%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5         | 1.87%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 5         | 1.87%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 5         | 1.87%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 4         | 1.49%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 1.49%   |
| Intel Cannon Lake PCH cAVS                                                                        | 4         | 1.49%   |
| AMD FCH Azalia Controller                                                                         | 4         | 1.49%   |
| Intel CM238 HD Audio Controller                                                                   | 3         | 1.12%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 1.12%   |
| AMD High Definition Audio Controller                                                              | 3         | 1.12%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 1.12%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 2         | 0.75%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 0.75%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 0.75%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 0.75%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 0.75%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 2         | 0.75%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 1         | 0.37%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 0.37%   |
| Phison Electronics SoundYouSoundYouSoundYouSoundYouSoundYouSoundYouSoundYouSoun                   | 1         | 0.37%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 1         | 0.37%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.37%   |
| Nvidia GF116 High Definition Audio Controller                                                     | 1         | 0.37%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 1         | 0.37%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 67        | 28.76%  |
| SK hynix            | 44        | 18.88%  |
| Micron Technology   | 22        | 9.44%   |
| Unknown             | 21        | 9.01%   |
| Unknown             | 12        | 5.15%   |
| Kingston            | 11        | 4.72%   |
| Crucial             | 9         | 3.86%   |
| Elpida              | 6         | 2.58%   |
| A-DATA Technology   | 6         | 2.58%   |
| Nanya Technology    | 5         | 2.15%   |
| Ramaxel Technology  | 4         | 1.72%   |
| Unknown (ABCD)      | 3         | 1.29%   |
| Transcend           | 3         | 1.29%   |
| Smart               | 3         | 1.29%   |
| Corsair             | 3         | 1.29%   |
| SHARETRONIC         | 2         | 0.86%   |
| Multilaser          | 2         | 0.86%   |
| Team                | 1         | 0.43%   |
| Swissbit            | 1         | 0.43%   |
| Silicon Power       | 1         | 0.43%   |
| SemsoTai            | 1         | 0.43%   |
| Lenovo              | 1         | 0.43%   |
| GOODRAM             | 1         | 0.43%   |
| G.Skill             | 1         | 0.43%   |
| ASint Technology    | 1         | 0.43%   |
| Apacer              | 1         | 0.43%   |
| 48spaces            | 1         | 0.43%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 12        | 4.94%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 5         | 2.06%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 2.06%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 5         | 2.06%   |
| Unknown RAM Module 1GB SODIMM DDR2                               | 4         | 1.65%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 4         | 1.65%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2400MT/s            | 4         | 1.65%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 3         | 1.23%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 3         | 1.23%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.23%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 3         | 1.23%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s            | 3         | 1.23%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 1.23%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s            | 3         | 1.23%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 3         | 1.23%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 3         | 1.23%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 2         | 0.82%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.82%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.82%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s           | 2         | 0.82%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s           | 2         | 0.82%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 1333MT/s            | 2         | 0.82%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 0.82%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.82%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 2         | 0.82%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 2         | 0.82%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 2         | 0.82%   |
| Samsung RAM M471A5143EB0-CPB 4GB SODIMM DDR4 2133MT/s            | 2         | 0.82%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 0.82%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.82%   |
| Samsung RAM M4 70T5663QZ3-CF7 2GB SODIMM DDR2 2048MT/s           | 2         | 0.82%   |
| Multilaser RAM MS3512NSZ-CA3G1 4GB SODIMM DDR3 1600MT/s          | 2         | 0.82%   |
| Micron RAM Module 4GB SODIMM DDR3 1600MT/s                       | 2         | 0.82%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s          | 2         | 0.82%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 0.41%   |
| Unknown RAM Module 8GB SODIMM DDR3 1333MT/s                      | 1         | 0.41%   |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s                      | 1         | 0.41%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 0.41%   |
| Unknown RAM Module 2GB SODIMM DDR3 667MT/s                       | 1         | 0.41%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 0.41%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 102       | 50.5%   |
| DDR4    | 60        | 29.7%   |
| DDR2    | 24        | 11.88%  |
| Unknown | 7         | 3.47%   |
| LPDDR4  | 4         | 1.98%   |
| SDRAM   | 3         | 1.49%   |
| LPDDR3  | 2         | 0.99%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 188       | 92.61%  |
| Row Of Chips | 5         | 2.46%   |
| Chip         | 4         | 1.97%   |
| Unknown      | 4         | 1.97%   |
| DIMM         | 2         | 0.99%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 77        | 34.53%  |
| 8192  | 63        | 28.25%  |
| 2048  | 53        | 23.77%  |
| 16384 | 15        | 6.73%   |
| 1024  | 13        | 5.83%   |
| 32768 | 2         | 0.9%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 58        | 26.85%  |
| 2400    | 26        | 12.04%  |
| 3200    | 20        | 9.26%   |
| 1333    | 18        | 8.33%   |
| 667     | 18        | 8.33%   |
| 2667    | 16        | 7.41%   |
| 1067    | 14        | 6.48%   |
| 1334    | 10        | 4.63%   |
| 800     | 9         | 4.17%   |
| Unknown | 9         | 4.17%   |
| 2133    | 8         | 3.7%    |
| 1867    | 4         | 1.85%   |
| 2048    | 2         | 0.93%   |
| 1066    | 2         | 0.93%   |
| 3733    | 1         | 0.46%   |
| 533     | 1         | 0.46%   |

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
| Chicony Electronics                    | 42        | 27.27%  |
| Bison Electronics                      | 23        | 14.94%  |
| Microdia                               | 12        | 7.79%   |
| IMC Networks                           | 10        | 6.49%   |
| Realtek Semiconductor                  | 9         | 5.84%   |
| Sunplus Innovation Technology          | 7         | 4.55%   |
| Syntek                                 | 6         | 3.9%    |
| Cheng Uei Precision Industry (Foxlink) | 6         | 3.9%    |
| Quanta                                 | 5         | 3.25%   |
| Suyin                                  | 4         | 2.6%    |
| Silicon Motion                         | 4         | 2.6%    |
| Lite-On Technology                     | 4         | 2.6%    |
| Alcor Micro                            | 4         | 2.6%    |
| Lenovo                                 | 3         | 1.95%   |
| Apple                                  | 3         | 1.95%   |
| ALi                                    | 3         | 1.95%   |
| Z-Star Microelectronics                | 2         | 1.3%    |
| Y Media                                | 1         | 0.65%   |
| Supreme Electronics                    | 1         | 0.65%   |
| Luxvisions Innotech Limited            | 1         | 0.65%   |
| Jiangxi Shinetech Optical              | 1         | 0.65%   |
| Importek                               | 1         | 0.65%   |
| DigiTech                               | 1         | 0.65%   |
| Cubeternet                             | 1         | 0.65%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                   | 14        | 9.09%   |
| Bison Integrated Camera                                     | 9         | 5.84%   |
| Microdia Integrated_Webcam_HD                               | 7         | 4.55%   |
| Chicony Lenovo Integrated Camera (0.3MP)                    | 5         | 3.25%   |
| Realtek Integrated_Webcam_HD                                | 4         | 2.6%    |
| Suyin Acer/HP Integrated Webcam [CN0314]                    | 3         | 1.95%   |
| Chicony FJ Camera                                           | 3         | 1.95%   |
| Cheng Uei Precision Industry (Foxlink) Realtek DMFT RGB     | 3         | 1.95%   |
| Syntek Lenovo EasyCamera                                    | 2         | 1.3%    |
| Syntek Integrated Camera                                    | 2         | 1.3%    |
| Sunplus HP TrueVision HD Camera                             | 2         | 1.3%    |
| Realtek USB Camera                                          | 2         | 1.3%    |
| Lite-On Integrated Camera                                   | 2         | 1.3%    |
| Lenovo Integrated Webcam                                    | 2         | 1.3%    |
| IMC Networks UVC VGA Webcam                                 | 2         | 1.3%    |
| IMC Networks Integrated Webcam                              | 2         | 1.3%    |
| IMC Networks Integrated Camera                              | 2         | 1.3%    |
| IMC Networks EasyCamera                                     | 2         | 1.3%    |
| Chicony USB 2.0 Camera                                      | 2         | 1.3%    |
| Chicony Integrated Camera [ThinkPad]                        | 2         | 1.3%    |
| Chicony HP Wide Vision HD Camera                            | 2         | 1.3%    |
| Cheng Uei Precision Industry (Foxlink) HP Webcam            | 2         | 1.3%    |
| Bison ThinkPad Integrated Camera                            | 2         | 1.3%    |
| Bison SunplusIT Integrated Camera                           | 2         | 1.3%    |
| Bison Lenovo EasyCamera                                     | 2         | 1.3%    |
| Bison HP Webcam-101                                         | 2         | 1.3%    |
| Apple FaceTime HD Camera                                    | 2         | 1.3%    |
| ALi WebCam                                                  | 2         | 1.3%    |
| Alcor Micro USB 2.0 Camera                                  | 2         | 1.3%    |
| Z-Star Webcam                                               | 1         | 0.65%   |
| Z-Star Namuga 1.3M Webcam                                   | 1         | 0.65%   |
| Y Media USB Camera                                          | 1         | 0.65%   |
| Syntek HP Webcam                                            | 1         | 0.65%   |
| Syntek EasyCamera                                           | 1         | 0.65%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 1         | 0.65%   |
| Supreme Integrated Camera                                   | 1         | 0.65%   |
| Sunplus Laptop Integrated WebCam HD                         | 1         | 0.65%   |
| Sunplus Integrated_Webcam_HD                                | 1         | 0.65%   |
| Sunplus Integrated Camera                                   | 1         | 0.65%   |
| Sunplus HP HD Webcam [Fixed]                                | 1         | 0.65%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 11        | 42.31%  |
| Upek                       | 4         | 15.38%  |
| Elan Microelectronics      | 3         | 11.54%  |
| AuthenTec                  | 3         | 11.54%  |
| STMicroelectronics         | 1         | 3.85%   |
| Shenzhen Goodix Technology | 1         | 3.85%   |
| LighTuning Technology      | 1         | 3.85%   |
| FocalTech Systems          | 1         | 3.85%   |
| Fingerprint Cards          | 1         | 3.85%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                             | Notebooks | Percent |
|-----------------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                            | 4         | 15.38%  |
| Validity Sensors VFS 5011 fingerprint sensor                                      | 3         | 11.54%  |
| Validity Sensors Synaptics WBDI                                                   | 3         | 11.54%  |
| Elan Fingerprint Sensor                                                           | 3         | 11.54%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                                 | 1         | 3.85%   |
| Validity Sensors VFS5011 Fingerprint Reader                                       | 1         | 3.85%   |
| Validity Sensors VFS101 Fingerprint Reader                                        | 1         | 3.85%   |
| Validity Sensors Swipe Fingerprint Sensor                                         | 1         | 3.85%   |
| Validity Sensors Fingerprint scanner                                              | 1         | 3.85%   |
| STMicroelectronics Fingerprint Reader                                             | 1         | 3.85%   |
| Shenzhen Goodix Fingerprint Reader SGX                                            | 1         | 3.85%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                       | 1         | 3.85%   |
| FocalTech Systems FocalTech Fingerprint Device Realtek USB2.0 Finger Print Bridge | 1         | 3.85%   |
| Fingerprint Cards FPC Fingerprint Reader                                          | 1         | 3.85%   |
| AuthenTec AES2810                                                                 | 1         | 3.85%   |
| AuthenTec AES2660                                                                 | 1         | 3.85%   |
| AuthenTec AES1660                                                                 | 1         | 3.85%   |

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
| 1     | 99        | 47.6%   |
| 2     | 53        | 25.48%  |
| 0     | 36        | 17.31%  |
| 3     | 18        | 8.65%   |
| 4     | 2         | 0.96%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 137       | 55.02%  |
| Net/wireless             | 35        | 14.06%  |
| Fingerprint reader       | 26        | 10.44%  |
| Card reader              | 26        | 10.44%  |
| Bluetooth                | 16        | 6.43%   |
| Storage                  | 5         | 2.01%   |
| Sound                    | 2         | 0.8%    |
| Network                  | 1         | 0.4%    |
| Net/ethernet             | 1         | 0.4%    |

