BSD in Brazil - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------------

A project to collect tested hardware configurations for BSD in Brazil.

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

Total: 108

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Dell          | Inspiron 3421               | [ef4870410f](https://bsd-hardware.info/?probe=ef4870410f) | Apr 23, 2023 |
| Apple         | MacBook3,1                  | [74986a169a](https://bsd-hardware.info/?probe=74986a169a) | Apr 15, 2023 |
| Samsung       | 370E4K                      | [c363d008bf](https://bsd-hardware.info/?probe=c363d008bf) | Apr 13, 2023 |
| Lenovo        | ThinkPad X230 23257EP       | [e94085cd2d](https://bsd-hardware.info/?probe=e94085cd2d) | Apr 12, 2023 |
| Lenovo        | ThinkPad T430 2349G5P       | [9ea67d3893](https://bsd-hardware.info/?probe=9ea67d3893) | Mar 27, 2023 |
| Dell          | Inspiron 3442               | [cbb9f6bfbb](https://bsd-hardware.info/?probe=cbb9f6bfbb) | Mar 17, 2023 |
| Lenovo        | ThinkPad X201 36801T6       | [decaf0c347](https://bsd-hardware.info/?probe=decaf0c347) | Mar 17, 2023 |
| Dell          | Inspiron 5557               | [ff199c6d21](https://bsd-hardware.info/?probe=ff199c6d21) | Mar 16, 2023 |
| Samsung       | 275E4E/275E5E               | [dd4f7ef594](https://bsd-hardware.info/?probe=dd4f7ef594) | Mar 15, 2023 |
| Dell          | Inspiron 15 3515            | [b480a98b22](https://bsd-hardware.info/?probe=b480a98b22) | Feb 26, 2023 |
| Samsung       | 270E5K/270E5Q/271E5K/257... | [45549e4faf](https://bsd-hardware.info/?probe=45549e4faf) | Feb 25, 2023 |
| Acer          | Aspire E1-421               | [db00abb833](https://bsd-hardware.info/?probe=db00abb833) | Feb 19, 2023 |
| Lenovo        | ThinkPad T430u 33522D5      | [d5bbbb8cbe](https://bsd-hardware.info/?probe=d5bbbb8cbe) | Feb 17, 2023 |
| Acer          | Aspire 4739Z                | [1e97a0b938](https://bsd-hardware.info/?probe=1e97a0b938) | Feb 09, 2023 |
| Lenovo        | IdeaPad 3 15IML05 82BS      | [3345f50844](https://bsd-hardware.info/?probe=3345f50844) | Feb 06, 2023 |
| Lenovo        | B40-70 80F30005BR           | [17333d88cf](https://bsd-hardware.info/?probe=17333d88cf) | Jan 17, 2023 |
| Lenovo        | ThinkPad T460 20FN002JUS    | [3a9623cfb4](https://bsd-hardware.info/?probe=3a9623cfb4) | Dec 16, 2022 |
| Lenovo        | ThinkPad T460 20FN002JUS    | [0314add226](https://bsd-hardware.info/?probe=0314add226) | Dec 16, 2022 |
| Dell          | Inspiron 3442               | [529cbab9aa](https://bsd-hardware.info/?probe=529cbab9aa) | Dec 01, 2022 |
| Apple         | MacBookPro8,1               | [3dd9e3557c](https://bsd-hardware.info/?probe=3dd9e3557c) | Nov 30, 2022 |
| Dell          | Vostro 3501                 | [61f8a35700](https://bsd-hardware.info/?probe=61f8a35700) | Nov 25, 2022 |
| Dell          | Inspiron 3421               | [5c37012f33](https://bsd-hardware.info/?probe=5c37012f33) | Nov 10, 2022 |
| Acer          | Aspire F5-573               | [9c092c9cd7](https://bsd-hardware.info/?probe=9c092c9cd7) | Oct 05, 2022 |
| Lenovo        | G475 20080                  | [fb07463a9a](https://bsd-hardware.info/?probe=fb07463a9a) | Sep 24, 2022 |
| Lenovo        | G475 20080                  | [c4b1acb6d1](https://bsd-hardware.info/?probe=c4b1acb6d1) | Sep 24, 2022 |
| Lenovo        | ThinkPad T61 7661GY9        | [7ab5339eee](https://bsd-hardware.info/?probe=7ab5339eee) | Jul 30, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [e2a5a65135](https://bsd-hardware.info/?probe=e2a5a65135) | Jul 23, 2022 |
| Dell          | Inspiron MP061              | [56a7002cc5](https://bsd-hardware.info/?probe=56a7002cc5) | Jul 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [b09ba0c799](https://bsd-hardware.info/?probe=b09ba0c799) | Jul 12, 2022 |
| Acer          | Aspire E5-571G              | [56fae2295e](https://bsd-hardware.info/?probe=56fae2295e) | Jul 08, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [ba96a05e5c](https://bsd-hardware.info/?probe=ba96a05e5c) | Jul 08, 2022 |
| Lenovo        | ThinkPad T410 2522CS7       | [a1561dacb2](https://bsd-hardware.info/?probe=a1561dacb2) | Jun 26, 2022 |
| Lenovo        | IdeaPad 3 15IGL05 82BU      | [6a6450f264](https://bsd-hardware.info/?probe=6a6450f264) | May 30, 2022 |
| Acer          | Aspire 5742                 | [b0ea5e7a5e](https://bsd-hardware.info/?probe=b0ea5e7a5e) | May 19, 2022 |
| Dell          | Inspiron 5437               | [830ea686ab](https://bsd-hardware.info/?probe=830ea686ab) | Apr 24, 2022 |
| Gateway       | NE56R                       | [87d177b9da](https://bsd-hardware.info/?probe=87d177b9da) | Mar 20, 2022 |
| Acer          | Aspire E1-421               | [cc83218496](https://bsd-hardware.info/?probe=cc83218496) | Mar 10, 2022 |
| Itautec       | Infoway w7535               | [b55f9d1bfb](https://bsd-hardware.info/?probe=b55f9d1bfb) | Mar 09, 2022 |
| Apple         | MacBookPro8,1               | [aa484c30a8](https://bsd-hardware.info/?probe=aa484c30a8) | Feb 12, 2022 |
| Gateway       | NE56R                       | [a5aa8aa49a](https://bsd-hardware.info/?probe=a5aa8aa49a) | Jan 18, 2022 |
| Acer          | Aspire ES1-533              | [a9d2458de5](https://bsd-hardware.info/?probe=a9d2458de5) | Jan 13, 2022 |
| Sony          | VPCYB45JB                   | [cd18905620](https://bsd-hardware.info/?probe=cd18905620) | Jan 09, 2022 |
| Lenovo        | G550 2958                   | [21407195e3](https://bsd-hardware.info/?probe=21407195e3) | Jan 07, 2022 |
| Samsung       | 530XBB                      | [fe0adb59d8](https://bsd-hardware.info/?probe=fe0adb59d8) | Dec 20, 2021 |
| Philco        | 10B                         | [a27148f35d](https://bsd-hardware.info/?probe=a27148f35d) | Dec 06, 2021 |
| Positivo      | C14CR01                     | [a33c158f9f](https://bsd-hardware.info/?probe=a33c158f9f) | Dec 05, 2021 |
| Samsung       | 530XBB                      | [8387645312](https://bsd-hardware.info/?probe=8387645312) | Dec 03, 2021 |
| Samsung       | 530XBB                      | [41d5f95889](https://bsd-hardware.info/?probe=41d5f95889) | Dec 03, 2021 |
| Samsung       | 530XBB                      | [e1983c2353](https://bsd-hardware.info/?probe=e1983c2353) | Dec 03, 2021 |
| Samsung       | 530XBB                      | [b344605891](https://bsd-hardware.info/?probe=b344605891) | Dec 02, 2021 |
| Dell          | Inspiron 5566               | [7c6b2f2013](https://bsd-hardware.info/?probe=7c6b2f2013) | Nov 14, 2021 |
| Toshiba       | STI NA 1401                 | [bbbf661ee8](https://bsd-hardware.info/?probe=bbbf661ee8) | Nov 14, 2021 |
| HP            | 14                          | [e0c8e95e52](https://bsd-hardware.info/?probe=e0c8e95e52) | Nov 07, 2021 |
| HP            | EliteBook 840 G3            | [03be88ded4](https://bsd-hardware.info/?probe=03be88ded4) | Nov 02, 2021 |
| Dell          | Inspiron 7460               | [3dbc09a4df](https://bsd-hardware.info/?probe=3dbc09a4df) | Oct 13, 2021 |
| Lenovo        | ThinkPad X250 20CLS2A11K    | [e47f4113bf](https://bsd-hardware.info/?probe=e47f4113bf) | Oct 08, 2021 |
| Itautec       | Infoway w7530               | [a376201681](https://bsd-hardware.info/?probe=a376201681) | Oct 05, 2021 |
| Dell          | Latitude 5490               | [f0f4370a9c](https://bsd-hardware.info/?probe=f0f4370a9c) | Sep 27, 2021 |
| Itautec       | Infoway w7530               | [d91ec24ce0](https://bsd-hardware.info/?probe=d91ec24ce0) | Aug 29, 2021 |
| Itautec       | Infoway w7530               | [fe69db32c8](https://bsd-hardware.info/?probe=fe69db32c8) | Aug 27, 2021 |
| Acer          | Aspire 5750                 | [2bc72bf29e](https://bsd-hardware.info/?probe=2bc72bf29e) | Aug 23, 2021 |
| Avell High... | A60 MUV                     | [85f5c972a5](https://bsd-hardware.info/?probe=85f5c972a5) | Aug 21, 2021 |
| Samsung       | 300E5M/300E5L               | [ae874102c3](https://bsd-hardware.info/?probe=ae874102c3) | Aug 04, 2021 |
| Dell          | Inspiron 3442               | [6283cb4190](https://bsd-hardware.info/?probe=6283cb4190) | Aug 01, 2021 |
| Avell High... | A62 LIV                     | [5983302b1d](https://bsd-hardware.info/?probe=5983302b1d) | Jul 21, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | [daa7e68a1f](https://bsd-hardware.info/?probe=daa7e68a1f) | Jul 21, 2021 |
| Acer          | Aspire A515-54G             | [08cafd05b1](https://bsd-hardware.info/?probe=08cafd05b1) | Jul 06, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | [128c08e60f](https://bsd-hardware.info/?probe=128c08e60f) | Jul 04, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [ceb18e38a3](https://bsd-hardware.info/?probe=ceb18e38a3) | Jun 28, 2021 |
| Acer          | Aspire 5750                 | [d59f20f88a](https://bsd-hardware.info/?probe=d59f20f88a) | Jun 22, 2021 |
| Acer          | Aspire 5750                 | [cc6dc71d37](https://bsd-hardware.info/?probe=cc6dc71d37) | Jun 21, 2021 |
| Gateway       | NE56R                       | [cc65e24aea](https://bsd-hardware.info/?probe=cc65e24aea) | Jun 20, 2021 |
| Gateway       | NE56R                       | [932f5d03f3](https://bsd-hardware.info/?probe=932f5d03f3) | Jun 13, 2021 |
| Dell          | Vostro 5490                 | [cf3508718c](https://bsd-hardware.info/?probe=cf3508718c) | Jun 11, 2021 |
| Lenovo        | ThinkPad X220 4291ON5       | [66743a51cc](https://bsd-hardware.info/?probe=66743a51cc) | Jun 04, 2021 |
| Acer          | Aspire A515-51G             | [53a69aa8c1](https://bsd-hardware.info/?probe=53a69aa8c1) | Jun 04, 2021 |
| Lenovo        | ThinkPad X270 20HM004JBR    | [88c27e65d7](https://bsd-hardware.info/?probe=88c27e65d7) | May 23, 2021 |
| Dell          | Inspiron 3442               | [0d1d75a914](https://bsd-hardware.info/?probe=0d1d75a914) | May 23, 2021 |
| Dell          | Inspiron 3442               | [076dc91b26](https://bsd-hardware.info/?probe=076dc91b26) | May 13, 2021 |
| Lenovo        | ThinkPad E490 20N9001SBR    | [852a900303](https://bsd-hardware.info/?probe=852a900303) | Apr 22, 2021 |
| Gateway       | NE56R                       | [bbbc827581](https://bsd-hardware.info/?probe=bbbc827581) | Apr 16, 2021 |
| Gateway       | NE56R                       | [af262c2350](https://bsd-hardware.info/?probe=af262c2350) | Apr 11, 2021 |
| Avell High... | A62                         | [df77dd6562](https://bsd-hardware.info/?probe=df77dd6562) | Mar 22, 2021 |
| Notebook      | N85_N87HCHNHZ               | [e84b5b6e5f](https://bsd-hardware.info/?probe=e84b5b6e5f) | Mar 22, 2021 |
| Lenovo        | ThinkPad X220 4291ON5       | [8d81204137](https://bsd-hardware.info/?probe=8d81204137) | Mar 22, 2021 |
| Dell          | Inspiron 7520               | [599d3e84d7](https://bsd-hardware.info/?probe=599d3e84d7) | Mar 16, 2021 |
| Dell          | Inspiron 3442               | [f156951052](https://bsd-hardware.info/?probe=f156951052) | Mar 14, 2021 |
| Dell          | Inspiron 3543               | [525eeec663](https://bsd-hardware.info/?probe=525eeec663) | Mar 12, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [5211d36066](https://bsd-hardware.info/?probe=5211d36066) | Feb 25, 2021 |
| Unknown       | Unknown                     | [d11ec93413](https://bsd-hardware.info/?probe=d11ec93413) | Feb 23, 2021 |
| Samsung       | RV411/RV511/E3511/S3511/... | [467a915fc7](https://bsd-hardware.info/?probe=467a915fc7) | Feb 23, 2021 |
| LG Electro... | 14Z980-G.BH51P1             | [d8ee6bc4e3](https://bsd-hardware.info/?probe=d8ee6bc4e3) | Feb 22, 2021 |
| Lenovo        | ThinkPad X240 20AMS4V000    | [cbfa45fe44](https://bsd-hardware.info/?probe=cbfa45fe44) | Feb 22, 2021 |
| ASUSTek       | K46CA                       | [f286c1e784](https://bsd-hardware.info/?probe=f286c1e784) | Feb 21, 2021 |
| Dell          | Venue 11 Pro 7140           | [1a49b7921a](https://bsd-hardware.info/?probe=1a49b7921a) | Feb 17, 2021 |
| Lenovo        | ThinkPad T430 2349PMP       | [23de6449ad](https://bsd-hardware.info/?probe=23de6449ad) | Feb 17, 2021 |
| Dell          | Inspiron 3421               | [c5f6880081](https://bsd-hardware.info/?probe=c5f6880081) | Feb 15, 2021 |
| Dell          | Inspiron 3442               | [411797b4dc](https://bsd-hardware.info/?probe=411797b4dc) | Feb 13, 2021 |
| Clevo         | C41X0                       | [81c48d156a](https://bsd-hardware.info/?probe=81c48d156a) | Feb 12, 2021 |
| Apple         | MacBook6,1                  | [3a9335691f](https://bsd-hardware.info/?probe=3a9335691f) | Feb 11, 2021 |
| Samsung       | 300E5M/300E5L               | [a667296c17](https://bsd-hardware.info/?probe=a667296c17) | Feb 03, 2021 |
| Lenovo        | ThinkPad T450s 20BWS05G0... | [bc2855974c](https://bsd-hardware.info/?probe=bc2855974c) | Dec 06, 2020 |
| Unknown       | Unknown                     | [6953b9a9e4](https://bsd-hardware.info/?probe=6953b9a9e4) | Nov 22, 2020 |
| Dell          | Latitude 3490               | [b28cc12aeb](https://bsd-hardware.info/?probe=b28cc12aeb) | Sep 20, 2020 |
| Lenovo        | ThinkPad T490 20N30029BR    | [41dbfb6fdc](https://bsd-hardware.info/?probe=41dbfb6fdc) | Aug 06, 2020 |
| Samsung       | 270E5K/270E5Q/271E5K/257... | [1b84bffd9b](https://bsd-hardware.info/?probe=1b84bffd9b) | Jul 24, 2020 |
| Sony          | VPCEG17FB                   | [7d48bd3606](https://bsd-hardware.info/?probe=7d48bd3606) | Jul 13, 2020 |
| Lenovo        | ThinkPad X250 20CLS18S0Z    | [f668ce4e5b](https://bsd-hardware.info/?probe=f668ce4e5b) | Jul 05, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart_bsd/os_name.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| helloSystem 0.7.0    | 12        | 12.63%  |
| helloSystem 0.8.1    | 10        | 10.53%  |
| helloSystem 0.6.0    | 10        | 10.53%  |
| helloSystem 0.4.0    | 10        | 10.53%  |
| helloSystem 0.5.0    | 9         | 9.47%   |
| helloSystem 0.8.0    | 8         | 8.42%   |
| FreeBSD 13.0         | 6         | 6.32%   |
| FreeBSD 14.0-CURRENT | 3         | 3.16%   |
| FreeBSD 13.0-p3      | 3         | 3.16%   |
| FreeBSD 13.0-STABLE  | 2         | 2.11%   |
| FreeBSD 12.1         | 2         | 2.11%   |
| OS108 9.99.68        | 1         | 1.05%   |
| OPNsense 22.7.4      | 1         | 1.05%   |
| OpenBSD 7.3          | 1         | 1.05%   |
| OpenBSD 7.2          | 1         | 1.05%   |
| OpenBSD 7.0          | 1         | 1.05%   |
| OpenBSD 6.9          | 1         | 1.05%   |
| helloSystem 0.3.0    | 1         | 1.05%   |
| GhostBSD 22.11.22    | 1         | 1.05%   |
| GhostBSD 22.07.10    | 1         | 1.05%   |
| GhostBSD 20.04.02    | 1         | 1.05%   |
| FreeBSD 13.1-p4      | 1         | 1.05%   |
| FreeBSD 13.0-RC2     | 1         | 1.05%   |
| FreeBSD 13.0-p7      | 1         | 1.05%   |
| FreeBSD 13.0-p4      | 1         | 1.05%   |
| FreeBSD 13.0-CURRENT | 1         | 1.05%   |
| FreeBSD 12.2-p3      | 1         | 1.05%   |
| FreeBSD 12.2         | 1         | 1.05%   |
| FreeBSD 12.1-p7      | 1         | 1.05%   |
| FreeBSD 12.1-p11     | 1         | 1.05%   |
| DragonFly 5.8        | 1         | 1.05%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| helloSystem | 56        | 62.22%  |
| FreeBSD     | 24        | 26.67%  |
| OpenBSD     | 4         | 4.44%   |
| GhostBSD    | 3         | 3.33%   |
| OS108       | 1         | 1.11%   |
| OPNsense    | 1         | 1.11%   |
| DragonFly   | 1         | 1.11%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 87        | 98.86%  |
| i386  | 1         | 1.14%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 57        | 63.33%  |
| XFCE         | 6         | 6.67%   |
| Console      | 6         | 6.67%   |
| MATE         | 5         | 5.56%   |
| KDE5         | 4         | 4.44%   |
| GNOME        | 4         | 4.44%   |
| i3           | 2         | 2.22%   |
| fvwm         | 2         | 2.22%   |
| TWM          | 1         | 1.11%   |
| spectrwm     | 1         | 1.11%   |
| Openbox      | 1         | 1.11%   |
| LXQt         | 1         | 1.11%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 83        | 94.32%  |
| Console | 5         | 5.68%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SLiM    | 61        | 67.78%  |
| Console | 13        | 14.44%  |
| LightDM | 7         | 7.78%   |
| SDDM    | 4         | 4.44%   |
| XDM     | 3         | 3.33%   |
| GDM     | 2         | 2.22%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang            | Notebooks | Percent |
|-----------------|-----------|---------|
| en_US           | 49        | 53.26%  |
| Unknown         | 12        | 13.04%  |
| pt_BR           | 11        | 11.96%  |
| C               | 11        | 11.96%  |
| pt              | 5         | 5.43%   |
| fr_FR           | 2         | 2.17%   |
| en_US.ISO8859-1 | 1         | 1.09%   |
| en_GB           | 1         | 1.09%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 77        | 87.5%   |
| BIOS | 11        | 12.5%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Zfs     | 63        | 69.23%  |
| Cd9660  | 13        | 14.29%  |
| Ufs     | 10        | 10.99%  |
| Ffs     | 4         | 4.4%    |
| Hammer2 | 1         | 1.1%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 86        | 97.73%  |
| MBR     | 1         | 1.14%   |
| Unknown | 1         | 1.14%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 24        | 27.27%  |
| Dell                   | 21        | 23.86%  |
| Acer                   | 10        | 11.36%  |
| Samsung Electronics    | 9         | 10.23%  |
| Avell High Performance | 3         | 3.41%   |
| Apple                  | 3         | 3.41%   |
| Sony                   | 2         | 2.27%   |
| Itautec                | 2         | 2.27%   |
| Hewlett-Packard        | 2         | 2.27%   |
| Gateway                | 2         | 2.27%   |
| ASUSTek Computer       | 2         | 2.27%   |
| Unknown                | 2         | 2.27%   |
| Semp Toshiba           | 1         | 1.14%   |
| Positivo               | 1         | 1.14%   |
| Philco                 | 1         | 1.14%   |
| Notebook               | 1         | 1.14%   |
| LG Electronics         | 1         | 1.14%   |
| Clevo                  | 1         | 1.14%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Dell Inspiron 3442                          | 5         | 5.68%   |
| Dell Inspiron 3421                          | 3         | 3.41%   |
| Samsung 340XAA/350XAA/550XAA                | 2         | 2.27%   |
| Samsung 270E5K/270E5Q/271E5K/2570EK         | 2         | 2.27%   |
| Gateway NE56R                               | 2         | 2.27%   |
| Acer Aspire 5750                            | 2         | 2.27%   |
| Unknown                                     | 2         | 2.27%   |
| Sony VPCYB45JB                              | 1         | 1.14%   |
| Sony VPCEG17FB                              | 1         | 1.14%   |
| Semp Toshiba STI NA 1401                    | 1         | 1.14%   |
| Samsung RV411/RV511/E3511/S3511/RV711/E3411 | 1         | 1.14%   |
| Samsung 530XBB                              | 1         | 1.14%   |
| Samsung 370E4K                              | 1         | 1.14%   |
| Samsung 300E5M/300E5L                       | 1         | 1.14%   |
| Samsung 275E4E/275E5E                       | 1         | 1.14%   |
| Positivo C14CR01                            | 1         | 1.14%   |
| Philco 10B                                  | 1         | 1.14%   |
| Notebook N85_N87HCHNHZ                      | 1         | 1.14%   |
| LG 14Z980-G.BH51P1                          | 1         | 1.14%   |
| Lenovo ThinkPad X270 20HM004JBR             | 1         | 1.14%   |
| Lenovo ThinkPad X250 20CLS2A11K             | 1         | 1.14%   |
| Lenovo ThinkPad X250 20CLS18S0Z             | 1         | 1.14%   |
| Lenovo ThinkPad X240 20AMS4V000             | 1         | 1.14%   |
| Lenovo ThinkPad X230 23257EP                | 1         | 1.14%   |
| Lenovo ThinkPad X220 4291ON5                | 1         | 1.14%   |
| Lenovo ThinkPad X201 36801T6                | 1         | 1.14%   |
| Lenovo ThinkPad T61 7661GY9                 | 1         | 1.14%   |
| Lenovo ThinkPad T490 20N30029BR             | 1         | 1.14%   |
| Lenovo ThinkPad T460 20FN002JUS             | 1         | 1.14%   |
| Lenovo ThinkPad T450s 20BWS05G0T            | 1         | 1.14%   |
| Lenovo ThinkPad T430u 33522D5               | 1         | 1.14%   |
| Lenovo ThinkPad T430 2349PMP                | 1         | 1.14%   |
| Lenovo ThinkPad T430 2349G5P                | 1         | 1.14%   |
| Lenovo ThinkPad T410 2522CS7                | 1         | 1.14%   |
| Lenovo ThinkPad E490 20N9001SBR             | 1         | 1.14%   |
| Lenovo IdeaPad S145-15IWL 81S9              | 1         | 1.14%   |
| Lenovo IdeaPad S145-15IWL 81MV              | 1         | 1.14%   |
| Lenovo IdeaPad S145-15API 81V7              | 1         | 1.14%   |
| Lenovo IdeaPad 3 15IML05 82BS               | 1         | 1.14%   |
| Lenovo IdeaPad 3 15IGL05 82BU               | 1         | 1.14%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Lenovo ThinkPad            | 16        | 18.18%  |
| Dell Inspiron              | 16        | 18.18%  |
| Acer Aspire                | 10        | 11.36%  |
| Lenovo IdeaPad             | 5         | 5.68%   |
| Samsung 340XAA             | 2         | 2.27%   |
| Samsung 270E5K             | 2         | 2.27%   |
| Itautec Infoway            | 2         | 2.27%   |
| Gateway NE56R              | 2         | 2.27%   |
| Dell Vostro                | 2         | 2.27%   |
| Dell Latitude              | 2         | 2.27%   |
| Avell High Performance A62 | 2         | 2.27%   |
| Unknown                    | 2         | 2.27%   |
| Sony VPCYB45JB             | 1         | 1.14%   |
| Sony VPCEG17FB             | 1         | 1.14%   |
| Semp Toshiba STI           | 1         | 1.14%   |
| Samsung RV411              | 1         | 1.14%   |
| Samsung 530XBB             | 1         | 1.14%   |
| Samsung 370E4K             | 1         | 1.14%   |
| Samsung 300E5M             | 1         | 1.14%   |
| Samsung 275E4E             | 1         | 1.14%   |
| Positivo C14CR01           | 1         | 1.14%   |
| Philco 10B                 | 1         | 1.14%   |
| Notebook N85               | 1         | 1.14%   |
| LG 14Z980-G.BH51P1         | 1         | 1.14%   |
| Lenovo G550                | 1         | 1.14%   |
| Lenovo G475                | 1         | 1.14%   |
| Lenovo B40-70              | 1         | 1.14%   |
| HP EliteBook               | 1         | 1.14%   |
| HP 14                      | 1         | 1.14%   |
| Dell Venue                 | 1         | 1.14%   |
| Clevo C41X0                | 1         | 1.14%   |
| Avell High Performance A60 | 1         | 1.14%   |
| ASUS VivoBook              | 1         | 1.14%   |
| ASUS K46CA                 | 1         | 1.14%   |
| Apple MacBookPro8          | 1         | 1.14%   |
| Apple MacBook6             | 1         | 1.14%   |
| Apple MacBook3             | 1         | 1.14%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2013    | 15        | 17.05%  |
| 2020    | 8         | 9.09%   |
| 2018    | 8         | 9.09%   |
| 2011    | 8         | 9.09%   |
| 2019    | 7         | 7.95%   |
| 2016    | 7         | 7.95%   |
| 2014    | 6         | 6.82%   |
| 2017    | 4         | 4.55%   |
| 2015    | 4         | 4.55%   |
| 2012    | 4         | 4.55%   |
| 2022    | 3         | 3.41%   |
| 2021    | 3         | 3.41%   |
| 2010    | 3         | 3.41%   |
| 2009    | 3         | 3.41%   |
| 2007    | 2         | 2.27%   |
| Unknown | 2         | 2.27%   |
| 2008    | 1         | 1.14%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 88        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 88        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 8.01-16.0  | 41        | 46.07%  |
| 4.01-8.0   | 31        | 34.83%  |
| 16.01-24.0 | 9         | 10.11%  |
| 32.01-64.0 | 2         | 2.25%   |
| 3.01-4.0   | 2         | 2.25%   |
| 24.01-32.0 | 2         | 2.25%   |
| 2.01-3.0   | 2         | 2.25%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 58        | 65.17%  |
| 0.51-1.0   | 25        | 28.09%  |
| 2.01-3.0   | 2         | 2.25%   |
| 32.01-64.0 | 1         | 1.12%   |
| 24.01-32.0 | 1         | 1.12%   |
| 1.01-2.0   | 1         | 1.12%   |
| Unknown    | 1         | 1.12%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 59        | 66.29%  |
| 2      | 23        | 25.84%  |
| 0      | 6         | 6.74%   |
| 3      | 1         | 1.12%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 54        | 61.36%  |
| Yes       | 34        | 38.64%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 80        | 90.91%  |
| No        | 8         | 9.09%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 85        | 96.59%  |
| No        | 3         | 3.41%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 66        | 75%     |
| No        | 22        | 25%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Brazil  | 88        | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Sao Paulo                 | 7         | 7.45%   |
| Curitiba                  | 6         | 6.38%   |
| SГЈo Paulo              | 4         | 4.26%   |
| Rio de Janeiro            | 4         | 4.26%   |
| Manaus                    | 4         | 4.26%   |
| Campinas                  | 3         | 3.19%   |
| Belo Horizonte            | 3         | 3.19%   |
| SÃ£o Paulo              | 2         | 2.13%   |
| Maraba                    | 2         | 2.13%   |
| JoГЈo Pessoa            | 2         | 2.13%   |
| Ipojuca                   | 2         | 2.13%   |
| Vitória                  | 1         | 1.06%   |
| Visconde do Rio Branco    | 1         | 1.06%   |
| Uberaba                   | 1         | 1.06%   |
| Trindade                  | 1         | 1.06%   |
| Teresopolis               | 1         | 1.06%   |
| Teresina                  | 1         | 1.06%   |
| Tangara                   | 1         | 1.06%   |
| SГЈo JosГ© dos Campos | 1         | 1.06%   |
| Sobral                    | 1         | 1.06%   |
| Sao Vicente               | 1         | 1.06%   |
| Sao Jeronimo da Serra     | 1         | 1.06%   |
| Sao Bernardo do Campo     | 1         | 1.06%   |
| Santa Maria               | 1         | 1.06%   |
| Rio das Ostras            | 1         | 1.06%   |
| Presidente Prudente       | 1         | 1.06%   |
| Porto UniГЈo            | 1         | 1.06%   |
| Porto Alegre              | 1         | 1.06%   |
| Piloezinhos               | 1         | 1.06%   |
| Pelotas                   | 1         | 1.06%   |
| Paracuru                  | 1         | 1.06%   |
| Osasco                    | 1         | 1.06%   |
| Niterói                  | 1         | 1.06%   |
| Monte Belo                | 1         | 1.06%   |
| Marica                    | 1         | 1.06%   |
| Marcolandia               | 1         | 1.06%   |
| Maracanau                 | 1         | 1.06%   |
| Mage                      | 1         | 1.06%   |
| Maceió                   | 1         | 1.06%   |
| Londrina                  | 1         | 1.06%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 21        | 23     | 19.63%  |
| Seagate             | 16        | 19     | 14.95%  |
| Kingston            | 13        | 14     | 12.15%  |
| Toshiba             | 11        | 11     | 10.28%  |
| Samsung Electronics | 9         | 9      | 8.41%   |
| Crucial             | 6         | 7      | 5.61%   |
| A-DATA Technology   | 6         | 6      | 5.61%   |
| LITEON              | 4         | 4      | 3.74%   |
| SSSTC               | 3         | 3      | 2.8%    |
| SK hynix            | 3         | 3      | 2.8%    |
| SanDisk             | 2         | 2      | 1.87%   |
| Hitachi             | 2         | 2      | 1.87%   |
| China               | 2         | 2      | 1.87%   |
| Smart               | 1         | 1      | 0.93%   |
| Silicon Motion      | 1         | 1      | 0.93%   |
| PNY                 | 1         | 1      | 0.93%   |
| Phison              | 1         | 1      | 0.93%   |
| Patriot             | 1         | 4      | 0.93%   |
| NVMe                | 1         | 1      | 0.93%   |
| KingSpec            | 1         | 1      | 0.93%   |
| Hikvision           | 1         | 1      | 0.93%   |
| Gigabyte Technology | 1         | 1      | 0.93%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Toshiba MQ01ABD100 1TB              | 4         | 3.64%   |
| WDC WDS480G2G0B-00EPW0 480GB        | 2         | 1.82%   |
| WDC WDS240G2G0A-00JH30 240GB        | 2         | 1.82%   |
| WDC WD10SPZX-24Z10 1TB              | 2         | 1.82%   |
| SSSTC CL1-4D256 256GB               | 2         | 1.82%   |
| Seagate ST750LM022 HN-M750MBB 752GB | 2         | 1.82%   |
| Seagate ST1000LM048-2E7172 1TB      | 2         | 1.82%   |
| Seagate ST1000LM035-1RK172 1TB      | 2         | 1.82%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 2         | 1.82%   |
| Kingston SA400S37960G 960GB         | 2         | 1.82%   |
| Kingston SA400S37480G 480GB         | 2         | 1.82%   |
| Kingston SA400S37240G 240GB         | 2         | 1.82%   |
| Crucial CT480BX500SSD1 480GB        | 2         | 1.82%   |
| WDC WDS120G1G0A-00SS50 120GB        | 1         | 0.91%   |
| WDC WDS100T2G0A-00JH30 1TB          | 1         | 0.91%   |
| WDC WD800BEVS-00RST0 80GB           | 1         | 0.91%   |
| WDC WD6400BEVT-22A0RT0 640GB        | 1         | 0.91%   |
| WDC WD5000LPCX-35VHAT0 500GB        | 1         | 0.91%   |
| WDC WD5000B 500GB                   | 1         | 0.91%   |
| WDC WD20SPZX-22UA7T0 2TB            | 1         | 0.91%   |
| WDC WD1600BPVT-11JJ5T0 160GB        | 1         | 0.91%   |
| WDC WD1600BEVS-60RST0 160GB         | 1         | 0.91%   |
| WDC WD1600BEVS-22VAT0 160GB         | 1         | 0.91%   |
| WDC WD10SPZX-75Z10T1 1TB            | 1         | 0.91%   |
| WDC WD10SPZX-35Z10T0 1TB            | 1         | 0.91%   |
| WDC WD10JPVX-80JC3T0 1TB            | 1         | 0.91%   |
| WDC WD10JPVX-75JC3T0 1TB            | 1         | 0.91%   |
| WDC WD10JPVX-35JC3T0 1TB            | 1         | 0.91%   |
| WDC WD10JPVX-22JC3T0 1TB            | 1         | 0.91%   |
| WDC WD10JPCX-24UE4T0 1TB            | 1         | 0.91%   |
| Toshiba MQ01ABD100V 1TB             | 1         | 0.91%   |
| Toshiba MK6034GSX 64GB              | 1         | 0.91%   |
| Toshiba MK5076GSX 500GB             | 1         | 0.91%   |
| Toshiba MK3261GSYN 320GB            | 1         | 0.91%   |
| Toshiba MK2555GSXF 250GB            | 1         | 0.91%   |
| Toshiba MK1252GSX 120GB             | 1         | 0.91%   |
| Toshiba KBG30ZMV256G 256GB          | 1         | 0.91%   |
| SSSTC CL1-4D128 128GB               | 1         | 0.91%   |
| Smart SSD XceedValue2 mSATA 32GB    | 1         | 0.91%   |
| SK hynix HFS128G39TND-N210A 128GB   | 1         | 0.91%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 17        | 17     | 34.69%  |
| Seagate             | 16        | 19     | 32.65%  |
| Toshiba             | 10        | 10     | 20.41%  |
| Samsung Electronics | 4         | 4      | 8.16%   |
| Hitachi             | 2         | 2      | 4.08%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 12        | 13     | 27.91%  |
| WDC                 | 5         | 6      | 11.63%  |
| Crucial             | 5         | 6      | 11.63%  |
| Samsung Electronics | 4         | 4      | 9.3%    |
| LITEON              | 4         | 4      | 9.3%    |
| SK hynix            | 2         | 2      | 4.65%   |
| SanDisk             | 2         | 2      | 4.65%   |
| China               | 2         | 2      | 4.65%   |
| Smart               | 1         | 1      | 2.33%   |
| PNY                 | 1         | 1      | 2.33%   |
| Patriot             | 1         | 4      | 2.33%   |
| KingSpec            | 1         | 1      | 2.33%   |
| Hikvision           | 1         | 1      | 2.33%   |
| Gigabyte Technology | 1         | 1      | 2.33%   |
| A-DATA Technology   | 1         | 1      | 2.33%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 43        | 52     | 43.88%  |
| SSD  | 39        | 49     | 39.8%   |
| NVMe | 16        | 16     | 16.33%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 70        | 101    | 81.4%   |
| NVMe | 16        | 16     | 18.6%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 54        | 69     | 65.85%  |
| 0.51-1.0   | 25        | 29     | 30.49%  |
| 1.01-2.0   | 3         | 3      | 3.66%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 27        | 28.72%  |
| 101-250    | 26        | 27.66%  |
| 251-500    | 17        | 18.09%  |
| 501-1000   | 10        | 10.64%  |
| 51-100     | 6         | 6.38%   |
| 21-50      | 3         | 3.19%   |
| 1001-2000  | 3         | 3.19%   |
| 2001-3000  | 1         | 1.06%   |
| Unknown    | 1         | 1.06%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 73        | 82.02%  |
| 21-50    | 8         | 8.99%   |
| 101-250  | 3         | 3.37%   |
| 501-1000 | 3         | 3.37%   |
| 51-100   | 1         | 1.12%   |
| Unknown  | 1         | 1.12%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB             | 2         | 2      | 8.7%    |
| WDC WD5000B 500GB                  | 1         | 1      | 4.35%   |
| WDC WD1600BEVS-60RST0 160GB        | 1         | 1      | 4.35%   |
| WDC WD10JPVX-75JC3T0 1TB           | 1         | 1      | 4.35%   |
| Toshiba MK6034GSX 64GB             | 1         | 1      | 4.35%   |
| Toshiba MK5076GSX 500GB            | 1         | 1      | 4.35%   |
| Toshiba MK3261GSYN 320GB           | 1         | 1      | 4.35%   |
| Toshiba MK2555GSXF 250GB           | 1         | 1      | 4.35%   |
| Toshiba MK1252GSX 120GB            | 1         | 1      | 4.35%   |
| SK hynix HFS128G39TND-N210A 128GB  | 1         | 1      | 4.35%   |
| Seagate ST9500325AS 500GB          | 1         | 1      | 4.35%   |
| Seagate ST9320325ASG 320GB         | 1         | 2      | 4.35%   |
| Seagate ST9320325AS 320GB          | 1         | 1      | 4.35%   |
| Seagate ST9250315AS 250GB          | 1         | 1      | 4.35%   |
| Seagate ST9120821AS 118GB          | 1         | 1      | 4.35%   |
| Seagate ST500LT012-9WS142 500GB    | 1         | 1      | 4.35%   |
| Seagate ST1000LM048-2E7172 1TB     | 1         | 1      | 4.35%   |
| Seagate ST1000LM025 HN-M101ABB 1TB | 1         | 1      | 4.35%   |
| Samsung Electronics HM321HI 320GB  | 1         | 1      | 4.35%   |
| LITEON LJH-64V2G-11 M.2 2260 64GB  | 1         | 1      | 4.35%   |
| Hitachi HTS547550A9E384 500GB      | 1         | 1      | 4.35%   |
| Hitachi HTS545050B9A300 500GB      | 1         | 1      | 4.35%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 9      | 34.78%  |
| Toshiba             | 7         | 7      | 30.43%  |
| WDC                 | 3         | 3      | 13.04%  |
| Hitachi             | 2         | 2      | 8.7%    |
| SK hynix            | 1         | 1      | 4.35%   |
| Samsung Electronics | 1         | 1      | 4.35%   |
| LITEON              | 1         | 1      | 4.35%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 9      | 38.1%   |
| Toshiba             | 7         | 7      | 33.33%  |
| WDC                 | 3         | 3      | 14.29%  |
| Hitachi             | 2         | 2      | 9.52%   |
| Samsung Electronics | 1         | 1      | 4.76%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 18        | 22     | 90%     |
| SSD  | 2         | 2      | 10%     |

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
| Works    | 70        | 92     | 76.92%  |
| Malfunc  | 20        | 24     | 21.98%  |
| Detected | 1         | 1      | 1.1%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 79        | 78.22%  |
| AMD                            | 5         | 4.95%   |
| ADATA Technology               | 5         | 4.95%   |
| Solid State Storage Technology | 3         | 2.97%   |
| Toshiba                        | 1         | 0.99%   |
| SK hynix                       | 1         | 0.99%   |
| Silicon Motion                 | 1         | 0.99%   |
| Samsung Electronics            | 1         | 0.99%   |
| Realtek Semiconductor          | 1         | 0.99%   |
| Phison Electronics             | 1         | 0.99%   |
| Nvidia                         | 1         | 0.99%   |
| Micron/Crucial Technology      | 1         | 0.99%   |
| Kingston Technology Company    | 1         | 0.99%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 14        | 13.33%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 12        | 11.43%  |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                           | 9         | 8.57%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 8         | 7.62%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 6         | 5.71%   |
| Solid State Storage CL1                                                      | 3         | 2.86%   |
| Intel Comet Lake SATA AHCI Controller                                        | 3         | 2.86%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                            | 3         | 2.86%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller               | 3         | 2.86%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                            | 3         | 2.86%   |
| ADATA IM2P33F8ABR1 NVMe SSD                                                  | 3         | 2.86%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                       | 2         | 1.9%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]        | 2         | 1.9%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                | 2         | 1.9%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                             | 2         | 1.9%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                | 2         | 1.9%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                               | 2         | 1.9%    |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]              | 2         | 1.9%    |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]              | 2         | 1.9%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller               | 2         | 1.9%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                         | 2         | 1.9%    |
| Toshiba BG3 NVMe SSD Controller                                              | 1         | 0.95%   |
| SK hynix BC511                                                               | 1         | 0.95%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                              | 1         | 0.95%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                | 1         | 0.95%   |
| Realtek NVMe Controller                                                      | 1         | 0.95%   |
| Phison PS5013 E13 NVMe Controller                                            | 1         | 0.95%   |
| Nvidia MCP79 AHCI Controller                                                 | 1         | 0.95%   |
| Micron/Crucial P1 NVMe PCIe SSD                                              | 1         | 0.95%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                        | 1         | 0.95%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                           | 1         | 0.95%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                | 1         | 0.95%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                        | 1         | 0.95%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller     | 1         | 0.95%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                            | 1         | 0.95%   |
| AMD FCH SATA Controller [IDE mode]                                           | 1         | 0.95%   |
| AMD FCH SATA Controller [AHCI mode]                                          | 1         | 0.95%   |
| ADATA Technology unknown                                                     | 1         | 0.95%   |
| Unknown                                                                      | 1         | 0.95%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 78        | 75.73%  |
| NVMe | 16        | 15.53%  |
| IDE  | 7         | 6.8%    |
| RAID | 2         | 1.94%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 81        | 92.05%  |
| AMD    | 7         | 7.95%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Intel Core i5-3320M CPU @ 2.60GHz  | 4         | 4.55%   |
| Intel Core i3-4005U CPU @ 1.70GHz  | 4         | 4.55%   |
| Intel Core i5-8250U CPU @ 1.60GHz  | 3         | 3.41%   |
| Intel Core i5-5200U CPU @ 2.20GHz  | 3         | 3.41%   |
| Intel CPU Version                  | 2         | 2.27%   |
| Intel Core i7-8565U CPU @ 1.80GHz  | 2         | 2.27%   |
| Intel Core i7-7500U CPU @ 2.70GHz  | 2         | 2.27%   |
| Intel Core i7-5600U CPU @ 2.60GHz  | 2         | 2.27%   |
| Intel Core i7-10750H CPU @ 2.60GHz | 2         | 2.27%   |
| Intel Core i5-6300U CPU @ 2.40GHz  | 2         | 2.27%   |
| Intel Core i5-4210U CPU @ 1.70GHz  | 2         | 2.27%   |
| Intel Core i5-3337U CPU @ 1.80GHz  | 2         | 2.27%   |
| Intel Core i5-2410M CPU @ 2.30GHz  | 2         | 2.27%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz | 2         | 2.27%   |
| Intel Core i5-10210U CPU @ 1.60GHz | 2         | 2.27%   |
| Intel Core i3-2330M CPU @ 2.20GHz  | 2         | 2.27%   |
| Intel Pentium M                    | 1         | 1.14%   |
| Intel Pentium CPU P6200 @ 2.13GHz  | 1         | 1.14%   |
| Intel Pentium CPU 5405U @ 2.30GHz  | 1         | 1.14%   |
| Intel Genuine CPU                  | 1         | 1.14%   |
| Intel Core M-5Y10c CPU @ 0.80GHz   | 1         | 1.14%   |
| Intel Core i7-9750H CPU @ 2.60GHz  | 1         | 1.14%   |
| Intel Core i7-8665U CPU @ 1.90GHz  | 1         | 1.14%   |
| Intel Core i7-8650U CPU @ 1.90GHz  | 1         | 1.14%   |
| Intel Core i7-8550U CPU @ 1.80GHz  | 1         | 1.14%   |
| Intel Core i7-7600U CPU @ 2.80GHz  | 1         | 1.14%   |
| Intel Core i7-6500U CPU @ 2.50GHz  | 1         | 1.14%   |
| Intel Core i7-5500U CPU @ 2.40GHz  | 1         | 1.14%   |
| Intel Core i7-3632QM CPU @ 2.20GHz | 1         | 1.14%   |
| Intel Core i7-10510U CPU @ 1.80GHz | 1         | 1.14%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz | 1         | 1.14%   |
| Intel Core i5-7200U CPU @ 2.50GHz  | 1         | 1.14%   |
| Intel Core i5-6200U CPU @ 2.30GHz  | 1         | 1.14%   |
| Intel Core i5-5300U CPU @ 2.30GHz  | 1         | 1.14%   |
| Intel Core i5-4300U CPU @ 1.90GHz  | 1         | 1.14%   |
| Intel Core i5-4200U CPU @ 1.60GHz  | 1         | 1.14%   |
| Intel Core i5-3317U CPU @ 1.70GHz  | 1         | 1.14%   |
| Intel Core i5-3230M CPU @ 2.60GHz  | 1         | 1.14%   |
| Intel Core i5-2520M CPU @ 2.50GHz  | 1         | 1.14%   |
| Intel Core i5-2415M CPU @ 2.30GHz  | 1         | 1.14%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 35        | 39.77%  |
| Intel Core i7    | 17        | 19.32%  |
| Intel Core i3    | 11        | 12.5%   |
| Intel Celeron    | 6         | 6.82%   |
| Intel Core 2 Duo | 3         | 3.41%   |
| Other            | 2         | 2.27%   |
| Intel Pentium    | 2         | 2.27%   |
| Intel Atom       | 2         | 2.27%   |
| AMD E1           | 2         | 2.27%   |
| Intel Pentium M  | 1         | 1.14%   |
| Intel Genuine    | 1         | 1.14%   |
| Intel Core M     | 1         | 1.14%   |
| AMD Ryzen 7      | 1         | 1.14%   |
| AMD Ryzen 5      | 1         | 1.14%   |
| AMD E            | 1         | 1.14%   |
| AMD C-60         | 1         | 1.14%   |
| AMD C-50         | 1         | 1.14%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 63        | 71.59%  |
| 4       | 15        | 17.05%  |
| Unknown | 4         | 4.55%   |
| 6       | 3         | 3.41%   |
| 8       | 2         | 2.27%   |
| 1       | 1         | 1.14%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 86        | 97.73%  |
| 2      | 2         | 2.27%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 65        | 73.86%  |
| 1       | 19        | 21.59%  |
| Unknown | 4         | 4.55%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 19        | 21.59%  |
| IvyBridge     | 11        | 12.5%   |
| SandyBridge   | 9         | 10.23%  |
| Broadwell     | 9         | 10.23%  |
| Haswell       | 8         | 9.09%   |
| Westmere      | 5         | 5.68%   |
| Skylake       | 5         | 5.68%   |
| Bobcat        | 5         | 5.68%   |
| Penryn        | 4         | 4.55%   |
| Zen+          | 2         | 2.27%   |
| IceLake       | 2         | 2.27%   |
| Goldmont plus | 2         | 2.27%   |
| Core          | 2         | 2.27%   |
| CometLake     | 2         | 2.27%   |
| Bonnell       | 2         | 2.27%   |
| Goldmont      | 1         | 1.14%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 78        | 74.29%  |
| Nvidia | 17        | 16.19%  |
| AMD    | 10        | 9.52%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                              | 11        | 10.19%  |
| Intel HD Graphics 5500                                                        | 8         | 7.41%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 8         | 7.41%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 8         | 7.41%   |
| Intel UHD Graphics 620                                                        | 5         | 4.63%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 5         | 4.63%   |
| Intel Core Processor Integrated Graphics Controller                           | 5         | 4.63%   |
| Intel HD Graphics 620                                                         | 4         | 3.7%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 3         | 2.78%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 3         | 2.78%   |
| Nvidia TU117M                                                                 | 2         | 1.85%   |
| Nvidia GP108M [GeForce MX250]                                                 | 2         | 1.85%   |
| Nvidia GM108M [GeForce MX130]                                                 | 2         | 1.85%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 2         | 1.85%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 2         | 1.85%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 2         | 1.85%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                        | 2         | 1.85%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 2         | 1.85%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 2         | 1.85%   |
| AMD Wrestler [Radeon HD 7310]                                                 | 2         | 1.85%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 2         | 1.85%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                    | 1         | 0.93%   |
| Nvidia GP108M [GeForce MX230]                                                 | 1         | 0.93%   |
| Nvidia GM108M [GeForce MX110]                                                 | 1         | 0.93%   |
| Nvidia GM108M [GeForce 940MX]                                                 | 1         | 0.93%   |
| Nvidia GM108M [GeForce 930M]                                                  | 1         | 0.93%   |
| Nvidia GM107M [GeForce GTX 950M]                                              | 1         | 0.93%   |
| Nvidia GK208M [GeForce GT 740M]                                               | 1         | 0.93%   |
| Nvidia GK208BM [GeForce 920M]                                                 | 1         | 0.93%   |
| Nvidia GF119M [GeForce 410M]                                                  | 1         | 0.93%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]          | 1         | 0.93%   |
| Nvidia C79 [GeForce 9400M]                                                    | 1         | 0.93%   |
| Intel Whiskey Lake-U GT1 [UHD Graphics 610]                                   | 1         | 0.93%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 1         | 0.93%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 1         | 0.93%   |
| Intel HD Graphics 630                                                         | 1         | 0.93%   |
| Intel HD Graphics 610                                                         | 1         | 0.93%   |
| Intel HD Graphics 5300                                                        | 1         | 0.93%   |
| Intel HD Graphics 500                                                         | 1         | 0.93%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 1         | 0.93%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 55        | 62.5%   |
| Intel + Nvidia | 15        | 17.05%  |
| 1 x AMD        | 8         | 9.09%   |
| 2 x Intel      | 6         | 6.82%   |
| 1 x Nvidia     | 2         | 2.27%   |
| Intel + AMD    | 2         | 2.27%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 83        | 94.32%  |
| Proprietary | 3         | 3.41%   |
| Unknown     | 2         | 2.27%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 81        | 91.01%  |
| 0.01-0.5   | 5         | 5.62%   |
| 3.01-4.0   | 2         | 2.25%   |
| 1.01-2.0   | 1         | 1.12%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| AU Optronics        | 20        | 28.99%  |
| LG Display          | 12        | 17.39%  |
| BOE                 | 9         | 13.04%  |
| Chimei Innolux      | 7         | 10.14%  |
| Samsung Electronics | 5         | 7.25%   |
| Lenovo              | 3         | 4.35%   |
| InfoVision          | 3         | 4.35%   |
| Dell                | 3         | 4.35%   |
| AOC                 | 2         | 2.9%    |
| Philips             | 1         | 1.45%   |
| PANDA               | 1         | 1.45%   |
| Hewlett-Packard     | 1         | 1.45%   |
| Goldstar            | 1         | 1.45%   |
| Apple               | 1         | 1.45%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO26EC 1366x768 340x190mm 15.3-inch         | 4         | 5.8%    |
| LG Display LCD Monitor LGD0385 1366x768 310x170mm 13.9-inch           | 3         | 4.35%   |
| LG Display LCD Monitor LGD0458 1366x768 310x170mm 13.9-inch           | 2         | 2.9%    |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch          | 2         | 2.9%    |
| BOE LCD Monitor BOE0757 1366x768 340x190mm 15.3-inch                  | 2         | 2.9%    |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch         | 2         | 2.9%    |
| AU Optronics LCD Monitor AUO40EC 1366x768 340x190mm 15.3-inch         | 2         | 2.9%    |
| AU Optronics LCD Monitor AUO303C 1366x768 310x170mm 13.9-inch         | 2         | 2.9%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 340x190mm 15.3-inch  | 1         | 1.45%   |
| Samsung Electronics LCD Monitor SEC414C 1366x768 310x170mm 13.9-inch  | 1         | 1.45%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 310x170mm 13.9-inch  | 1         | 1.45%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 340x190mm 15.3-inch | 1         | 1.45%   |
| Samsung Electronics LCD Monitor SAM0D4F 1920x1080 890x500mm 40.2-inch | 1         | 1.45%   |
| Philips PHL 193V5 PHLC0CD 1366x768 410x230mm 18.5-inch                | 1         | 1.45%   |
| PANDA LCD Monitor NCP0004 1920x1080 290x170mm 13.2-inch               | 1         | 1.45%   |
| LG Display LCD Monitor LGD05B1 1920x1080 310x170mm 13.9-inch          | 1         | 1.45%   |
| LG Display LCD Monitor LGD053C 1920x1080 310x170mm 13.9-inch          | 1         | 1.45%   |
| LG Display LCD Monitor LGD03ED 1366x768 280x160mm 12.7-inch           | 1         | 1.45%   |
| LG Display LCD Monitor LGD03B7 1366x768 310x170mm 13.9-inch           | 1         | 1.45%   |
| LG Display LCD Monitor LGD0230 1366x768 340x190mm 15.3-inch           | 1         | 1.45%   |
| Lenovo LEN X24A LEN60CF 1920x1080 530x300mm 24.0-inch                 | 1         | 1.45%   |
| Lenovo LCD Monitor LEN4035 1280x800 300x190mm 14.0-inch               | 1         | 1.45%   |
| Lenovo LCD Monitor LEN4031 1280x800 300x190mm 14.0-inch               | 1         | 1.45%   |
| InfoVision LCD Monitor IVO057D 1920x1080 310x170mm 13.9-inch          | 1         | 1.45%   |
| InfoVision LCD Monitor IVO0579 1366x768 310x170mm 13.9-inch           | 1         | 1.45%   |
| InfoVision LCD Monitor IVO03F4 1024x600 220x130mm 10.1-inch           | 1         | 1.45%   |
| Hewlett-Packard L200hx HWP298F 1600x900 450x250mm 20.3-inch           | 1         | 1.45%   |
| Goldstar LCD Monitor GSM580D 1920x1080 510x290mm 23.1-inch            | 1         | 1.45%   |
| Dell S2419HGF DELD0E1 1920x1080 530x300mm 24.0-inch                   | 1         | 1.45%   |
| Dell P2419H DELD0D9 1920x1080 530x300mm 24.0-inch                     | 1         | 1.45%   |
| Dell P2418D DELD0C1 2560x1440 530x300mm 24.0-inch                     | 1         | 1.45%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 340x190mm 15.3-inch      | 1         | 1.45%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 340x190mm 15.3-inch       | 1         | 1.45%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 340x190mm 15.3-inch       | 1         | 1.45%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 310x170mm 13.9-inch      | 1         | 1.45%   |
| Chimei Innolux LCD Monitor CMN1496 1366x768 310x170mm 13.9-inch       | 1         | 1.45%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 310x170mm 13.9-inch       | 1         | 1.45%   |
| Chimei Innolux LCD Monitor CMN1119 1366x768 260x140mm 11.6-inch       | 1         | 1.45%   |
| BOE LCD Monitor BOE08CD 1366x768 340x190mm 15.3-inch                  | 1         | 1.45%   |
| BOE LCD Monitor BOE0747 1920x1080 340x190mm 15.3-inch                 | 1         | 1.45%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution      | Notebooks | Percent |
|-----------------|-----------|---------|
| 1366x768 (WXGA) | 41        | 62.12%  |
| 1920x1080 (FHD) | 19        | 28.79%  |
| 1280x800 (WXGA) | 3         | 4.55%   |
| 2560x1440 (QHD) | 1         | 1.52%   |
| 1600x900 (HD+)  | 1         | 1.52%   |
| 1024x600        | 1         | 1.52%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 13     | 27        | 39.13%  |
| 15     | 24        | 34.78%  |
| 24     | 4         | 5.8%    |
| 12     | 4         | 5.8%    |
| 18     | 2         | 2.9%    |
| 14     | 2         | 2.9%    |
| 46     | 1         | 1.45%   |
| 23     | 1         | 1.45%   |
| 21     | 1         | 1.45%   |
| 20     | 1         | 1.45%   |
| 11     | 1         | 1.45%   |
| 10     | 1         | 1.45%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 49        | 71.01%  |
| 201-300     | 10        | 14.49%  |
| 501-600     | 5         | 7.25%   |
| 401-500     | 4         | 5.8%    |
| 1001-1500   | 1         | 1.45%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 57        | 93.44%  |
| 16/10 | 4         | 6.56%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 28        | 40.58%  |
| 91-100         | 23        | 33.33%  |
| 201-250        | 6         | 8.7%    |
| 61-70          | 4         | 5.8%    |
| 141-150        | 2         | 2.9%    |
| 71-80          | 1         | 1.45%   |
| 51-60          | 1         | 1.45%   |
| 41-50          | 1         | 1.45%   |
| 151-200        | 1         | 1.45%   |
| 101-110        | 1         | 1.45%   |
| 501-1000       | 1         | 1.45%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 40        | 59.7%   |
| 121-160 | 15        | 22.39%  |
| 51-100  | 8         | 11.94%  |
| 161-240 | 3         | 4.48%   |
| 1-50    | 1         | 1.49%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 66        | 74.16%  |
| 2     | 12        | 13.48%  |
| 0     | 11        | 12.36%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 48        | 33.1%   |
| Qualcomm Atheros         | 40        | 27.59%  |
| Intel                    | 32        | 22.07%  |
| Broadcom                 | 11        | 7.59%   |
| JMicron Technology       | 5         | 3.45%   |
| Samsung Electronics      | 3         | 2.07%   |
| Xiaomi                   | 1         | 0.69%   |
| TP-Link                  | 1         | 0.69%   |
| Ralink Technology        | 1         | 0.69%   |
| Nvidia                   | 1         | 0.69%   |
| MediaTek                 | 1         | 0.69%   |
| Marvell Technology Group | 1         | 0.69%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 22        | 12.79%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 20        | 11.63%  |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 13        | 7.56%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 12        | 6.98%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 6         | 3.49%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 4         | 2.33%   |
| Intel Wireless 8265 / 8275                                        | 4         | 2.33%   |
| Intel Wireless 7265                                               | 4         | 2.33%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 4         | 2.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 2.33%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 3         | 1.74%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 3         | 1.74%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 3         | 1.74%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 1.74%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 3         | 1.74%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 1.16%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 1.16%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 2         | 1.16%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 2         | 1.16%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 1.16%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 1.16%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller               | 2         | 1.16%   |
| Intel Wireless 8260                                               | 2         | 1.16%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 2         | 1.16%   |
| Intel Gemini Lake PCH CNVi WiFi                                   | 2         | 1.16%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 1.16%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.16%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 1.16%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 1.16%   |
| Intel Centrino Advanced-N 6200                                    | 2         | 1.16%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.16%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.58%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1         | 0.58%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.58%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 0.58%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                            | 1         | 0.58%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 0.58%   |
| Realtek 8811CU Wireless LAN 802.11ac USB NIC                      | 1         | 0.58%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 1         | 0.58%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.58%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Qualcomm Atheros      | 39        | 43.82%  |
| Intel                 | 32        | 35.96%  |
| Realtek Semiconductor | 11        | 12.36%  |
| Broadcom              | 5         | 5.62%   |
| TP-Link               | 1         | 1.12%   |
| Ralink Technology     | 1         | 1.12%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 13        | 14.44%  |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 12        | 13.33%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 6         | 6.67%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 4         | 4.44%   |
| Intel Wireless 8265 / 8275                                     | 4         | 4.44%   |
| Intel Wireless 7265                                            | 4         | 4.44%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 4         | 4.44%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 3         | 3.33%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 3         | 3.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2         | 2.22%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 2         | 2.22%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 2.22%   |
| Intel Wireless 8260                                            | 2         | 2.22%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 2         | 2.22%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 2         | 2.22%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 2         | 2.22%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 2         | 2.22%   |
| Intel Centrino Advanced-N 6200                                 | 2         | 2.22%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1         | 1.11%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 1.11%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                         | 1         | 1.11%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 1.11%   |
| Realtek 8811CU Wireless LAN 802.11ac USB NIC                   | 1         | 1.11%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 1         | 1.11%   |
| Intel Wireless 7260                                            | 1         | 1.11%   |
| Intel Wi-Fi 6 AX200                                            | 1         | 1.11%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 1         | 1.11%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 1         | 1.11%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 1         | 1.11%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 1         | 1.11%   |
| Intel Centrino Wireless-N 2230                                 | 1         | 1.11%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 1         | 1.11%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 1         | 1.11%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 1         | 1.11%   |
| Broadcom BCM43225 802.11b/g/n                                  | 1         | 1.11%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 1         | 1.11%   |
| Broadcom BCM4321 802.11a/b/g/n                                 | 1         | 1.11%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 42        | 51.85%  |
| Intel                    | 16        | 19.75%  |
| Broadcom                 | 7         | 8.64%   |
| Qualcomm Atheros         | 5         | 6.17%   |
| JMicron Technology       | 5         | 6.17%   |
| Samsung Electronics      | 3         | 3.7%    |
| Xiaomi                   | 1         | 1.23%   |
| Nvidia                   | 1         | 1.23%   |
| Marvell Technology Group | 1         | 1.23%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 22        | 27.16%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 20        | 24.69%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 4.94%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 3         | 3.7%    |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 3.7%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 3         | 3.7%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 2.47%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 2.47%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 2.47%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller               | 2         | 2.47%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 2.47%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 2.47%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 2.47%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.23%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 1.23%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 1.23%   |
| Nvidia MCP79 Ethernet                                             | 1         | 1.23%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 1.23%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.23%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 1.23%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 1.23%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 1.23%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 1         | 1.23%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.23%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 1         | 1.23%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 85        | 51.2%   |
| Ethernet | 80        | 48.19%  |
| Modem    | 1         | 0.6%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 60        | 50%     |
| Ethernet | 60        | 50%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 74        | 84.09%  |
| 1     | 14        | 15.91%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 82        | 93.18%  |
| Yes  | 6         | 6.82%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Qualcomm Atheros Communications | 23        | 34.85%  |
| Intel                           | 21        | 31.82%  |
| Broadcom                        | 6         | 9.09%   |
| Lite-On Technology              | 4         | 6.06%   |
| Apple                           | 4         | 6.06%   |
| Realtek Semiconductor           | 3         | 4.55%   |
| Foxconn / Hon Hai               | 3         | 4.55%   |
| IMC Networks                    | 1         | 1.52%   |
| Dell                            | 1         | 1.52%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 9         | 13.64%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 7         | 10.61%  |
| Qualcomm Atheros AR9462 Bluetooth                           | 6         | 9.09%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 5         | 7.58%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 5         | 7.58%   |
| Qualcomm Atheros Dell Wireless 1703 Bluetooth               | 4         | 6.06%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 3         | 4.55%   |
| Apple Bluetooth Host Controller                             | 3         | 4.55%   |
| Realtek Bluetooth Adapter                                   | 2         | 3.03%   |
| Intel AX201 Bluetooth                                       | 2         | 3.03%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 2         | 3.03%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 2         | 3.03%   |
| Realtek CSR Bluetooth Chip                                  | 1         | 1.52%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 1         | 1.52%   |
| Lite-On Qualcomm Atheros Bluetooth                          | 1         | 1.52%   |
| Lite-On Atheros Bluetooth                                   | 1         | 1.52%   |
| Lite-On Atheros AR3012 Bluetooth                            | 1         | 1.52%   |
| Intel Wireless-AC 3168 Bluetooth                            | 1         | 1.52%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 1         | 1.52%   |
| Intel AX200 Bluetooth                                       | 1         | 1.52%   |
| IMC Networks Bluetooth Module                               | 1         | 1.52%   |
| Foxconn / Hon Hai Qualcomm Atheros Bluetooth 4.0            | 1         | 1.52%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3011 Bluetooth Adapter | 1         | 1.52%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device             | 1         | 1.52%   |
| Dell Wireless 355 Bluetooth                                 | 1         | 1.52%   |
| Broadcom BCM2046 Bluetooth Device                           | 1         | 1.52%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 1         | 1.52%   |
| Apple Built-in iSight (no firmware loaded)                  | 1         | 1.52%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Intel    | 80        | 84.21%  |
| AMD      | 7         | 7.37%   |
| Nvidia   | 5         | 5.26%   |
| M-Audio  | 1         | 1.05%   |
| Logitech | 1         | 1.05%   |
| Lenovo   | 1         | 1.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 15        | 12.82%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 14        | 11.97%  |
| Intel Broadwell-U Audio Controller                                         | 9         | 7.69%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 8         | 6.84%   |
| Intel Haswell-ULT HD Audio Controller                                      | 8         | 6.84%   |
| Intel 8 Series HD Audio Controller                                         | 8         | 6.84%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 6         | 5.13%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 5         | 4.27%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 4         | 3.42%   |
| AMD Wrestler HDMI Audio                                                    | 4         | 3.42%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3         | 2.56%   |
| Intel Comet Lake PCH-LP cAVS                                               | 3         | 2.56%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 3         | 2.56%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 1.71%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 1.71%   |
| Intel Comet Lake PCH cAVS                                                  | 2         | 1.71%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 1.71%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 1.71%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2         | 1.71%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 1.71%   |
| AMD FCH Azalia Controller                                                  | 2         | 1.71%   |
| AMD Family 17h/19h HD Audio Controller                                     | 2         | 1.71%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 0.85%   |
| Nvidia MCP79 High Definition Audio                                         | 1         | 0.85%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 0.85%   |
| M-Audio M-Audio Fast Track Pro                                             | 1         | 0.85%   |
| Logitech H390 headset with microphone                                      | 1         | 0.85%   |
| Lenovo Realtek USB Audio                                                   | 1         | 0.85%   |
| Intel CM238 HD Audio Controller                                            | 1         | 0.85%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 1         | 0.85%   |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 0.85%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Smart               | 25        | 25%     |
| Samsung Electronics | 13        | 13%     |
| Kingston            | 11        | 11%     |
| SK hynix            | 9         | 9%      |
| Teikon              | 7         | 7%      |
| A-DATA Technology   | 7         | 7%      |
| Unknown             | 6         | 6%      |
| Smart Brazil        | 5         | 5%      |
| High Bridge         | 4         | 4%      |
| Micron Technology   | 3         | 3%      |
| Crucial             | 3         | 3%      |
| Apacer              | 2         | 2%      |
| Unknown (ABCD)      | 1         | 1%      |
| PNY                 | 1         | 1%      |
| Nanya Technology    | 1         | 1%      |
| Multilaser          | 1         | 1%      |
| Kllisre             | 1         | 1%      |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                              | Notebooks | Percent |
|--------------------------------------------------------------------|-----------|---------|
| Smart RAM SH564568FH8NZPHSCR 2GB SODIMM DDR3 1334MT/s              | 4         | 3.77%   |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s              | 4         | 3.77%   |
| Smart RAM SH564128FJ8NZRNSDG 4GB SODIMM DDR3 1600MT/s              | 3         | 2.83%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s              | 3         | 2.83%   |
| Smart RAM SH564128FH8NZPHSCR 4GB SODIMM DDR3 1333MT/s              | 3         | 2.83%   |
| Teikon RAM TML251S6EFR8A-PBHC 4GB SODIMM DDR3 1600MT/s             | 2         | 1.89%   |
| Smart RAM SH564128FH8NZQNSCG 4GB SODIMM DDR3 1600MT/s              | 2         | 1.89%   |
| Smart RAM SF4641G8CK8IEHLSBG 8GB SODIMM DDR4 2667MT/s              | 2         | 1.89%   |
| Smart Brazil RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2400MT/s       | 2         | 1.89%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s              | 2         | 1.89%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s              | 2         | 1.89%   |
| High Bridge RAM HB3SU002GFM8MMB33. 2GB SODIMM DDR3 1334MT/s        | 2         | 1.89%   |
| Unknown SODIMM 2048MB SODIMM DDR2 667MT/s                          | 1         | 0.94%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                        | 1         | 0.94%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                        | 1         | 0.94%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                        | 1         | 0.94%   |
| Unknown RAM Module 4GB SODIMM DDR2 800MT/s                         | 1         | 0.94%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                         | 1         | 0.94%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2133MT/s   | 1         | 0.94%   |
| Teikon RAM TMT451S6BFR8A-PBSC 4096MB SODIMM DDR3 1600MT/s          | 1         | 0.94%   |
| Teikon RAM TMT451S6BFR8A-PBHC 4GB SODIMM DDR3 1333MT/s             | 1         | 0.94%   |
| Teikon RAM TMT41GS6BFR8A-PBSC 8GB SODIMM DDR3 1600MT/s             | 1         | 0.94%   |
| Teikon RAM TMT225S6FR8C-H9HC 2GB SODIMM DDR3 1334MT/s              | 1         | 0.94%   |
| Teikon RAM TMA81GS6AFR8N-UHSC 8GB SODIMM DDR4 2400MT/s             | 1         | 0.94%   |
| Smart RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2133MT/s              | 1         | 0.94%   |
| Smart RAM SH564568FH8NWPHSFR 2GB SODIMM DDR3 1333MT/s              | 1         | 0.94%   |
| Smart RAM SH564128FJ8NZRNSDR 4GB SODIMM DDR3 1600MT/s              | 1         | 0.94%   |
| Smart RAM SH564128FH8NZPHSCG 4GB SODIMM DDR3 667MT/s               | 1         | 0.94%   |
| Smart RAM SF564128CJ8NWMNSEG 4GB SODIMM DDR3 1600MT/s              | 1         | 0.94%   |
| Smart RAM SF4641G8CK8IWGKSEG 8GB SODIMM DDR4 2133MT/s              | 1         | 0.94%   |
| Smart RAM SF464128CKHIWDFSEG 4GB SODIMM DDR4 2133MT/s              | 1         | 0.94%   |
| Smart Brazil RAM SMS4WEC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s       | 1         | 0.94%   |
| Smart Brazil RAM SF4641G8CK8IEHLSBG 8GB SODIMM DDR4 2133MT/s       | 1         | 0.94%   |
| Smart Brazil RAM SDQC8G8W16XCWE9N1T 4GB Row Of Chips DDR4 2667MT/s | 1         | 0.94%   |
| Smart Brazil RAM Module 4GB Row Of Chips DDR4 2400MT/s             | 1         | 0.94%   |
| SK hynix RAM HYMP512S64CP8-C4 1GB SODIMM DDR 533MT/s               | 1         | 0.94%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s              | 1         | 0.94%   |
| SK hynix RAM HMT451S6MFR8A-PB 4GB SODIMM DDR3 800MT/s              | 1         | 0.94%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s             | 1         | 0.94%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s             | 1         | 0.94%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 49        | 61.25%  |
| DDR4   | 23        | 28.75%  |
| DDR2   | 6         | 7.5%    |
| LPDDR4 | 1         | 1.25%   |
| DDR    | 1         | 1.25%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 78        | 97.5%   |
| Row Of Chips | 2         | 2.5%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 43        | 46.74%  |
| 8192  | 20        | 21.74%  |
| 2048  | 19        | 20.65%  |
| 16384 | 8         | 8.7%    |
| 1024  | 2         | 2.17%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 31        | 34.07%  |
| 1333  | 12        | 13.19%  |
| 2667  | 10        | 10.99%  |
| 2400  | 10        | 10.99%  |
| 1334  | 10        | 10.99%  |
| 2133  | 5         | 5.49%   |
| 667   | 4         | 4.4%    |
| 533   | 3         | 3.3%    |
| 800   | 2         | 2.2%    |
| 3200  | 1         | 1.1%    |
| 1867  | 1         | 1.1%    |
| 1067  | 1         | 1.1%    |
| 975   | 1         | 1.1%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart_bsd/printer_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| ELGIN  | 2         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart_bsd/printer_model.svg)


| Model        | Notebooks | Percent |
|--------------|-----------|---------|
| ELGIN L42PRO | 2         | 100%    |

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
| Chicony Electronics           | 17        | 21.79%  |
| Bison Electronics             | 12        | 15.38%  |
| Microdia                      | 10        | 12.82%  |
| Realtek Semiconductor         | 8         | 10.26%  |
| Silicon Motion                | 7         | 8.97%   |
| Suyin                         | 3         | 3.85%   |
| Sunplus Innovation Technology | 3         | 3.85%   |
| IMC Networks                  | 3         | 3.85%   |
| Unknown                       | 2         | 2.56%   |
| Syntek                        | 2         | 2.56%   |
| Luxvisions Innotech Limited   | 2         | 2.56%   |
| Logitech                      | 2         | 2.56%   |
| Lenovo                        | 2         | 2.56%   |
| Alcor Micro                   | 2         | 2.56%   |
| Quanta                        | 1         | 1.28%   |
| Lite-On Technology            | 1         | 1.28%   |
| Apple                         | 1         | 1.28%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony HD WebCam                             | 5         | 6.33%   |
| Bison Integrated Camera                       | 5         | 6.33%   |
| Silicon Motion Realtek DMFT RGB               | 4         | 5.06%   |
| Microdia Integrated_Webcam_HD                 | 4         | 5.06%   |
| Microdia Dell Laptop Integrated Webcam HD     | 4         | 5.06%   |
| Realtek Dell EasyCamera                       | 3         | 3.8%    |
| Unknown Realtek PC Camera                     | 2         | 2.53%   |
| Syntek EasyCamera                             | 2         | 2.53%   |
| Sunplus Integrated_Webcam_HD                  | 2         | 2.53%   |
| Realtek Integrated Webcam                     | 2         | 2.53%   |
| Luxvisions Innotech Limited Integrated Camera | 2         | 2.53%   |
| Chicony Sony Visual Communication Camera      | 2         | 2.53%   |
| Bison Lenovo EasyCamera                       | 2         | 2.53%   |
| Bison HD Webcam                               | 2         | 2.53%   |
| Alcor Micro Acer Integrated Webcam            | 2         | 2.53%   |
| Suyin WebCam                                  | 1         | 1.27%   |
| Suyin USB 2.0 UVC 1.3M WebCam                 | 1         | 1.27%   |
| Suyin Integrated_Webcam_HD                    | 1         | 1.27%   |
| Sunplus HD WebCam                             | 1         | 1.27%   |
| Silicon Motion WebCam SCX Series              | 1         | 1.27%   |
| Silicon Motion Realtek USB 2.0 PC Camera      | 1         | 1.27%   |
| Silicon Motion ATIV VGA Camera                | 1         | 1.27%   |
| Realtek LG Camera                             | 1         | 1.27%   |
| Realtek Integrated_Webcam_FHD                 | 1         | 1.27%   |
| Realtek Integrated_Webcam_8M                  | 1         | 1.27%   |
| Realtek Composite Webcam                      | 1         | 1.27%   |
| Quanta HD Webcam                              | 1         | 1.27%   |
| Microdia Laptop_Integrated_Webcam_HD          | 1         | 1.27%   |
| Microdia Integrated Webcam HD                 | 1         | 1.27%   |
| Logitech Webcam C270                          | 1         | 1.27%   |
| Logitech C922 Pro Stream Webcam               | 1         | 1.27%   |
| Lite-On Integrated Camera                     | 1         | 1.27%   |
| Lenovo Integrated Webcam [R5U877]             | 1         | 1.27%   |
| Lenovo Integrated Webcam                      | 1         | 1.27%   |
| IMC Networks Realtek DMFT RGB                 | 1         | 1.27%   |
| IMC Networks EasyCamera                       | 1         | 1.27%   |
| IMC Networks ASUS EasyCamera                  | 1         | 1.27%   |
| Chicony Webcam                                | 1         | 1.27%   |
| Chicony thinkpad t430s camera                 | 1         | 1.27%   |
| Chicony Sonix ST50220 USB Video Camera        | 1         | 1.27%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 6         | 40%     |
| Upek                       | 4         | 26.67%  |
| Synaptics                  | 2         | 13.33%  |
| Shenzhen Goodix Technology | 2         | 13.33%  |
| Samsung Electronics        | 1         | 6.67%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor      | 4         | 26.67%  |
| Validity Sensors VFS 5011 fingerprint sensor                | 2         | 13.33%  |
| Shenzhen Goodix Fingerprint Reader                          | 2         | 13.33%  |
| Validity Sensors VFS5011 Fingerprint Reader                 | 1         | 6.67%   |
| Validity Sensors VFS495 Fingerprint Reader                  | 1         | 6.67%   |
| Validity Sensors Synaptics WBDI                             | 1         | 6.67%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor | 1         | 6.67%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader           | 1         | 6.67%   |
| Synaptics Metallica MOH Touch Fingerprint Reader            | 1         | 6.67%   |
| Samsung CanvasBio Fingerprint Reader                        | 1         | 6.67%   |

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
| 1     | 26        | 29.21%  |
| 2     | 25        | 28.09%  |
| 3     | 16        | 17.98%  |
| 0     | 11        | 12.36%  |
| 4     | 6         | 6.74%   |
| 5     | 5         | 5.62%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 72        | 44.72%  |
| Card reader              | 33        | 20.5%   |
| Bluetooth                | 21        | 13.04%  |
| Net/wireless             | 19        | 11.8%   |
| Fingerprint reader       | 14        | 8.7%    |
| Sound                    | 2         | 1.24%   |

