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

Total: 121

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| GPD           | G1619-04                    | [30ad9b72b5](https://bsd-hardware.info/?probe=30ad9b72b5) | Sep 23, 2023 |
| Compaq        | Presario CQ-17              | [f97feb2db0](https://bsd-hardware.info/?probe=f97feb2db0) | Aug 04, 2023 |
| Dell          | Latitude E6420              | [3151e6d3bb](https://bsd-hardware.info/?probe=3151e6d3bb) | Jul 05, 2023 |
| Dell          | Latitude 5490               | [b638c1b2b1](https://bsd-hardware.info/?probe=b638c1b2b1) | Jun 23, 2023 |
| HP            | 1000                        | [21faecd7a6](https://bsd-hardware.info/?probe=21faecd7a6) | Jun 23, 2023 |
| Lenovo        | B40-30 80F10002BR           | [769c678314](https://bsd-hardware.info/?probe=769c678314) | Jun 10, 2023 |
| Acer          | Nitro AN515-57              | [c39ea00de5](https://bsd-hardware.info/?probe=c39ea00de5) | May 25, 2023 |
| Sony          | VPCEG15FB                   | [8777493861](https://bsd-hardware.info/?probe=8777493861) | May 21, 2023 |
| Unknown       | Apple MacBook Pro (13-in... | [5e25a49c65](https://bsd-hardware.info/?probe=5e25a49c65) | May 20, 2023 |
| Lenovo        | ThinkPad T61 7659AS5        | [7732b2cfa7](https://bsd-hardware.info/?probe=7732b2cfa7) | May 15, 2023 |
| Lenovo        | ThinkPad T61 7659AS5        | [b6071c549a](https://bsd-hardware.info/?probe=b6071c549a) | May 15, 2023 |
| Sony          | SVF14A15CBB                 | [4ada2dca25](https://bsd-hardware.info/?probe=4ada2dca25) | May 14, 2023 |
| Intel         | HuronRiver Platform         | [83494ffd65](https://bsd-hardware.info/?probe=83494ffd65) | May 11, 2023 |
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
| helloSystem 0.8.1    | 14        | 13.08%  |
| helloSystem 0.7.0    | 12        | 11.21%  |
| helloSystem 0.6.0    | 10        | 9.35%   |
| helloSystem 0.4.0    | 10        | 9.35%   |
| helloSystem 0.5.0    | 9         | 8.41%   |
| helloSystem 0.8.0    | 8         | 7.48%   |
| FreeBSD 13.0         | 6         | 5.61%   |
| OpenBSD 7.3          | 4         | 3.74%   |
| FreeBSD 14.0-CURRENT | 3         | 2.8%    |
| FreeBSD 13.0-p3      | 3         | 2.8%    |
| FreeBSD 13.2         | 2         | 1.87%   |
| FreeBSD 13.0-STABLE  | 2         | 1.87%   |
| FreeBSD 12.1         | 2         | 1.87%   |
| OS108 9.99.68        | 1         | 0.93%   |
| OPNsense 23.1.7      | 1         | 0.93%   |
| OPNsense 22.7.4      | 1         | 0.93%   |
| OpenBSD 7.2          | 1         | 0.93%   |
| OpenBSD 7.0          | 1         | 0.93%   |
| OpenBSD 6.9          | 1         | 0.93%   |
| helloSystem 0.8.2    | 1         | 0.93%   |
| helloSystem 0.3.0    | 1         | 0.93%   |
| GhostBSD 23.05.22    | 1         | 0.93%   |
| GhostBSD 22.11.22    | 1         | 0.93%   |
| GhostBSD 22.07.10    | 1         | 0.93%   |
| GhostBSD 20.04.02    | 1         | 0.93%   |
| FreeBSD 13.1-p4      | 1         | 0.93%   |
| FreeBSD 13.0-RC2     | 1         | 0.93%   |
| FreeBSD 13.0-p7      | 1         | 0.93%   |
| FreeBSD 13.0-p4      | 1         | 0.93%   |
| FreeBSD 13.0-CURRENT | 1         | 0.93%   |
| FreeBSD 12.2-p3      | 1         | 0.93%   |
| FreeBSD 12.2         | 1         | 0.93%   |
| FreeBSD 12.1-p7      | 1         | 0.93%   |
| FreeBSD 12.1-p11     | 1         | 0.93%   |
| DragonFly 5.8        | 1         | 0.93%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| helloSystem | 61        | 59.8%   |
| FreeBSD     | 26        | 25.49%  |
| OpenBSD     | 7         | 6.86%   |
| GhostBSD    | 4         | 3.92%   |
| OPNsense    | 2         | 1.96%   |
| OS108       | 1         | 0.98%   |
| DragonFly   | 1         | 0.98%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 97        | 97%     |
| i386  | 2         | 2%      |
| arm64 | 1         | 1%      |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 64        | 62.75%  |
| Console      | 7         | 6.86%   |
| XFCE         | 6         | 5.88%   |
| MATE         | 6         | 5.88%   |
| GNOME        | 6         | 5.88%   |
| KDE5         | 4         | 3.92%   |
| TWM          | 2         | 1.96%   |
| i3           | 2         | 1.96%   |
| fvwm         | 2         | 1.96%   |
| spectrwm     | 1         | 0.98%   |
| Openbox      | 1         | 0.98%   |
| LXQt         | 1         | 0.98%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 93        | 93%     |
| Console | 7         | 7%      |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SLiM    | 66        | 64.71%  |
| Console | 18        | 17.65%  |
| LightDM | 8         | 7.84%   |
| SDDM    | 4         | 3.92%   |
| XDM     | 3         | 2.94%   |
| GDM     | 3         | 2.94%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang            | Notebooks | Percent |
|-----------------|-----------|---------|
| en_US           | 51        | 49.04%  |
| pt_BR           | 15        | 14.42%  |
| Unknown         | 15        | 14.42%  |
| C               | 12        | 11.54%  |
| pt              | 5         | 4.81%   |
| fr_FR           | 4         | 3.85%   |
| en_US.ISO8859-1 | 1         | 0.96%   |
| en_GB           | 1         | 0.96%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 88        | 88%     |
| BIOS | 12        | 12%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Zfs     | 70        | 67.96%  |
| Cd9660  | 14        | 13.59%  |
| Ufs     | 11        | 10.68%  |
| Ffs     | 7         | 6.8%    |
| Hammer2 | 1         | 0.97%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 97        | 97%     |
| MBR     | 2         | 2%      |
| Unknown | 1         | 1%      |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 26        | 26%     |
| Dell                   | 23        | 23%     |
| Acer                   | 11        | 11%     |
| Samsung Electronics    | 9         | 9%      |
| Sony                   | 4         | 4%      |
| Hewlett-Packard        | 3         | 3%      |
| Avell High Performance | 3         | 3%      |
| Apple                  | 3         | 3%      |
| Unknown                | 3         | 3%      |
| Itautec                | 2         | 2%      |
| Gateway                | 2         | 2%      |
| ASUSTek Computer       | 2         | 2%      |
| Semp Toshiba           | 1         | 1%      |
| Positivo               | 1         | 1%      |
| Philco                 | 1         | 1%      |
| Notebook               | 1         | 1%      |
| LG Electronics         | 1         | 1%      |
| Intel                  | 1         | 1%      |
| GPD                    | 1         | 1%      |
| Compaq                 | 1         | 1%      |
| Clevo                  | 1         | 1%      |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Dell Inspiron 3442                          | 5         | 5%      |
| Dell Inspiron 3421                          | 3         | 3%      |
| Unknown                                     | 3         | 3%      |
| Samsung 340XAA/350XAA/550XAA                | 2         | 2%      |
| Samsung 270E5K/270E5Q/271E5K/2570EK         | 2         | 2%      |
| Gateway NE56R                               | 2         | 2%      |
| Dell Latitude 5490                          | 2         | 2%      |
| Acer Aspire 5750                            | 2         | 2%      |
| Sony VPCYB45JB                              | 1         | 1%      |
| Sony VPCEG17FB                              | 1         | 1%      |
| Sony VPCEG15FB                              | 1         | 1%      |
| Sony SVF14A15CBB                            | 1         | 1%      |
| Semp Toshiba STI NA 1401                    | 1         | 1%      |
| Samsung RV411/RV511/E3511/S3511/RV711/E3411 | 1         | 1%      |
| Samsung 530XBB                              | 1         | 1%      |
| Samsung 370E4K                              | 1         | 1%      |
| Samsung 300E5M/300E5L                       | 1         | 1%      |
| Samsung 275E4E/275E5E                       | 1         | 1%      |
| Positivo C14CR01                            | 1         | 1%      |
| Philco 10B                                  | 1         | 1%      |
| Notebook N85_N87HCHNHZ                      | 1         | 1%      |
| LG 14Z980-G.BH51P1                          | 1         | 1%      |
| Lenovo ThinkPad X270 20HM004JBR             | 1         | 1%      |
| Lenovo ThinkPad X250 20CLS2A11K             | 1         | 1%      |
| Lenovo ThinkPad X250 20CLS18S0Z             | 1         | 1%      |
| Lenovo ThinkPad X240 20AMS4V000             | 1         | 1%      |
| Lenovo ThinkPad X230 23257EP                | 1         | 1%      |
| Lenovo ThinkPad X220 4291ON5                | 1         | 1%      |
| Lenovo ThinkPad X201 36801T6                | 1         | 1%      |
| Lenovo ThinkPad T61 7661GY9                 | 1         | 1%      |
| Lenovo ThinkPad T61 7659AS5                 | 1         | 1%      |
| Lenovo ThinkPad T490 20N30029BR             | 1         | 1%      |
| Lenovo ThinkPad T460 20FN002JUS             | 1         | 1%      |
| Lenovo ThinkPad T450s 20BWS05G0T            | 1         | 1%      |
| Lenovo ThinkPad T430u 33522D5               | 1         | 1%      |
| Lenovo ThinkPad T430 2349PMP                | 1         | 1%      |
| Lenovo ThinkPad T430 2349G5P                | 1         | 1%      |
| Lenovo ThinkPad T410 2522CS7                | 1         | 1%      |
| Lenovo ThinkPad E490 20N9001SBR             | 1         | 1%      |
| Lenovo IdeaPad S145-15IWL 81S9              | 1         | 1%      |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Lenovo ThinkPad            | 17        | 17%     |
| Dell Inspiron              | 16        | 16%     |
| Acer Aspire                | 10        | 10%     |
| Lenovo IdeaPad             | 5         | 5%      |
| Dell Latitude              | 4         | 4%      |
| Unknown                    | 3         | 3%      |
| Samsung 340XAA             | 2         | 2%      |
| Samsung 270E5K             | 2         | 2%      |
| Itautec Infoway            | 2         | 2%      |
| Gateway NE56R              | 2         | 2%      |
| Dell Vostro                | 2         | 2%      |
| Avell High Performance A62 | 2         | 2%      |
| Sony VPCYB45JB             | 1         | 1%      |
| Sony VPCEG17FB             | 1         | 1%      |
| Sony VPCEG15FB             | 1         | 1%      |
| Sony SVF14A15CBB           | 1         | 1%      |
| Semp Toshiba STI           | 1         | 1%      |
| Samsung RV411              | 1         | 1%      |
| Samsung 530XBB             | 1         | 1%      |
| Samsung 370E4K             | 1         | 1%      |
| Samsung 300E5M             | 1         | 1%      |
| Samsung 275E4E             | 1         | 1%      |
| Positivo C14CR01           | 1         | 1%      |
| Philco 10B                 | 1         | 1%      |
| Notebook N85               | 1         | 1%      |
| LG 14Z980-G.BH51P1         | 1         | 1%      |
| Lenovo G550                | 1         | 1%      |
| Lenovo G475                | 1         | 1%      |
| Lenovo B40-70              | 1         | 1%      |
| Lenovo B40-30              | 1         | 1%      |
| Intel HuronRiver           | 1         | 1%      |
| HP EliteBook               | 1         | 1%      |
| HP 14                      | 1         | 1%      |
| HP 1000                    | 1         | 1%      |
| GPD G1619-04               | 1         | 1%      |
| Dell Venue                 | 1         | 1%      |
| Compaq Presario            | 1         | 1%      |
| Clevo C41X0                | 1         | 1%      |
| Avell High Performance A60 | 1         | 1%      |
| ASUS VivoBook              | 1         | 1%      |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2013    | 16        | 16%     |
| 2011    | 11        | 11%     |
| 2018    | 10        | 10%     |
| 2020    | 8         | 8%      |
| 2019    | 7         | 7%      |
| 2016    | 7         | 7%      |
| 2014    | 7         | 7%      |
| 2022    | 5         | 5%      |
| 2017    | 5         | 5%      |
| 2015    | 4         | 4%      |
| 2012    | 4         | 4%      |
| 2021    | 3         | 3%      |
| 2010    | 3         | 3%      |
| 2009    | 3         | 3%      |
| 2007    | 3         | 3%      |
| Unknown | 3         | 3%      |
| 2008    | 1         | 1%      |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 100       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 100       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 8.01-16.0  | 44        | 43.56%  |
| 4.01-8.0   | 36        | 35.64%  |
| 16.01-24.0 | 10        | 9.9%    |
| 24.01-32.0 | 4         | 3.96%   |
| 3.01-4.0   | 3         | 2.97%   |
| 32.01-64.0 | 2         | 1.98%   |
| 2.01-3.0   | 2         | 1.98%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 67        | 66.34%  |
| 0.51-1.0   | 27        | 26.73%  |
| 2.01-3.0   | 2         | 1.98%   |
| 1.01-2.0   | 2         | 1.98%   |
| 32.01-64.0 | 1         | 0.99%   |
| 24.01-32.0 | 1         | 0.99%   |
| Unknown    | 1         | 0.99%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 68        | 67.33%  |
| 2      | 25        | 24.75%  |
| 0      | 6         | 5.94%   |
| 3      | 2         | 1.98%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 63        | 63%     |
| Yes       | 37        | 37%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 89        | 89%     |
| No        | 11        | 11%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 97        | 97%     |
| No        | 3         | 3%      |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 73        | 73%     |
| No        | 27        | 27%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Brazil  | 100       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Sao Paulo                 | 10        | 9.43%   |
| Curitiba                  | 6         | 5.66%   |
| SГЈo Paulo              | 4         | 3.77%   |
| Rio de Janeiro            | 4         | 3.77%   |
| Manaus                    | 4         | 3.77%   |
| Campinas                  | 3         | 2.83%   |
| Blumenau                  | 3         | 2.83%   |
| Belo Horizonte            | 3         | 2.83%   |
| SÃ£o Paulo              | 2         | 1.89%   |
| Maraba                    | 2         | 1.89%   |
| JoГЈo Pessoa            | 2         | 1.89%   |
| Ipojuca                   | 2         | 1.89%   |
| Vitória                  | 1         | 0.94%   |
| Visconde do Rio Branco    | 1         | 0.94%   |
| Vila Velha                | 1         | 0.94%   |
| Uberaba                   | 1         | 0.94%   |
| Trindade                  | 1         | 0.94%   |
| Teresopolis               | 1         | 0.94%   |
| Teresina                  | 1         | 0.94%   |
| Tangara                   | 1         | 0.94%   |
| SГЈo JosГ© dos Campos | 1         | 0.94%   |
| Sobral                    | 1         | 0.94%   |
| Sete Lagoas               | 1         | 0.94%   |
| Sao Vicente               | 1         | 0.94%   |
| Sao Jeronimo da Serra     | 1         | 0.94%   |
| Sao Bernardo do Campo     | 1         | 0.94%   |
| Santa Maria               | 1         | 0.94%   |
| Rio das Ostras            | 1         | 0.94%   |
| Presidente Prudente       | 1         | 0.94%   |
| Porto UniГЈo            | 1         | 0.94%   |
| Porto Alegre              | 1         | 0.94%   |
| Piloezinhos               | 1         | 0.94%   |
| Pelotas                   | 1         | 0.94%   |
| Patrocinio                | 1         | 0.94%   |
| Paracuru                  | 1         | 0.94%   |
| Palmas                    | 1         | 0.94%   |
| Osasco                    | 1         | 0.94%   |
| Niterói                  | 1         | 0.94%   |
| Monte Belo                | 1         | 0.94%   |
| Marica                    | 1         | 0.94%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 21        | 23     | 17.21%  |
| Seagate             | 19        | 22     | 15.57%  |
| Kingston            | 14        | 15     | 11.48%  |
| Toshiba             | 12        | 12     | 9.84%   |
| Samsung Electronics | 10        | 11     | 8.2%    |
| A-DATA Technology   | 8         | 8      | 6.56%   |
| Crucial             | 6         | 7      | 4.92%   |
| LITEON              | 4         | 4      | 3.28%   |
| SSSTC               | 3         | 3      | 2.46%   |
| SK hynix            | 3         | 3      | 2.46%   |
| NVMe                | 3         | 3      | 2.46%   |
| SanDisk             | 2         | 2      | 1.64%   |
| KingSpec            | 2         | 3      | 1.64%   |
| Hitachi             | 2         | 2      | 1.64%   |
| China               | 2         | 2      | 1.64%   |
| SMI                 | 1         | 1      | 0.82%   |
| Smart               | 1         | 1      | 0.82%   |
| Silicon Motion      | 1         | 1      | 0.82%   |
| PNY                 | 1         | 1      | 0.82%   |
| Phison              | 1         | 1      | 0.82%   |
| Patriot             | 1         | 4      | 0.82%   |
| Lexar               | 1         | 1      | 0.82%   |
| Hikvision           | 1         | 1      | 0.82%   |
| Gigabyte Technology | 1         | 1      | 0.82%   |
| Biostar             | 1         | 1      | 0.82%   |
| BHT                 | 1         | 1      | 0.82%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Toshiba MQ01ABD100 1TB              | 4         | 3.17%   |
| Kingston SA400S37960G 960GB         | 3         | 2.38%   |
| WDC WDS480G2G0B-00EPW0 480GB        | 2         | 1.59%   |
| WDC WDS240G2G0A-00JH30 240GB        | 2         | 1.59%   |
| WDC WD10SPZX-24Z10 1TB              | 2         | 1.59%   |
| SSSTC CL1-4D256 256GB               | 2         | 1.59%   |
| Seagate ST750LM022 HN-M750MBB 752GB | 2         | 1.59%   |
| Seagate ST500LT012-9WS142 500GB     | 2         | 1.59%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 2         | 1.59%   |
| Seagate ST1000LM048-2E7172 1TB      | 2         | 1.59%   |
| Seagate ST1000LM035-1RK172 1TB      | 2         | 1.59%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 2         | 1.59%   |
| Samsung HM500JJ 500GB               | 2         | 1.59%   |
| Samsung HM321HI 320GB               | 2         | 1.59%   |
| Kingston SA400S37480G 480GB         | 2         | 1.59%   |
| Kingston SA400S37240G 240GB         | 2         | 1.59%   |
| Crucial CT480BX500SSD1 480GB        | 2         | 1.59%   |
| A-DATA SU810NS38 SATA 256 GB        | 2         | 1.59%   |
| WDC WDS120G1G0A-00SS50 120GB        | 1         | 0.79%   |
| WDC WDS100T2G0A-00JH30 1TB          | 1         | 0.79%   |
| WDC WD800BEVS-00RST0 80GB           | 1         | 0.79%   |
| WDC WD6400BEVT-22A0RT0 640GB        | 1         | 0.79%   |
| WDC WD5000LPCX-35VHAT0 500GB        | 1         | 0.79%   |
| WDC WD5000B 500GB                   | 1         | 0.79%   |
| WDC WD20SPZX-22UA7T0 2TB            | 1         | 0.79%   |
| WDC WD1600BPVT-11JJ5T0 160GB        | 1         | 0.79%   |
| WDC WD1600BEVS-60RST0 160GB         | 1         | 0.79%   |
| WDC WD1600BEVS-22VAT0 160GB         | 1         | 0.79%   |
| WDC WD10SPZX-75Z10T1 1TB            | 1         | 0.79%   |
| WDC WD10SPZX-35Z10T0 1TB            | 1         | 0.79%   |
| WDC WD10JPVX-80JC3T0 1TB            | 1         | 0.79%   |
| WDC WD10JPVX-75JC3T0 1TB            | 1         | 0.79%   |
| WDC WD10JPVX-35JC3T0 1TB            | 1         | 0.79%   |
| WDC WD10JPVX-22JC3T0 1TB            | 1         | 0.79%   |
| WDC WD10JPCX-24UE4T0 1TB            | 1         | 0.79%   |
| Toshiba MQ01ABD100V 1TB             | 1         | 0.79%   |
| Toshiba MK6034GSX 64GB              | 1         | 0.79%   |
| Toshiba MK5076GSX 500GB             | 1         | 0.79%   |
| Toshiba MK3261GSYN 320GB            | 1         | 0.79%   |
| Toshiba MK2555GSXF 250GB            | 1         | 0.79%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 19        | 22     | 33.93%  |
| WDC                 | 17        | 17     | 30.36%  |
| Toshiba             | 11        | 11     | 19.64%  |
| Samsung Electronics | 5         | 6      | 8.93%   |
| Hitachi             | 2         | 2      | 3.57%   |
| SMI                 | 1         | 1      | 1.79%   |
| NVMe                | 1         | 1      | 1.79%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 13        | 14     | 26%     |
| WDC                 | 5         | 6      | 10%     |
| Crucial             | 5         | 6      | 10%     |
| Samsung Electronics | 4         | 4      | 8%      |
| LITEON              | 4         | 4      | 8%      |
| SK hynix            | 2         | 2      | 4%      |
| SanDisk             | 2         | 2      | 4%      |
| KingSpec            | 2         | 3      | 4%      |
| China               | 2         | 2      | 4%      |
| A-DATA Technology   | 2         | 2      | 4%      |
| Smart               | 1         | 1      | 2%      |
| PNY                 | 1         | 1      | 2%      |
| Patriot             | 1         | 4      | 2%      |
| NVMe                | 1         | 1      | 2%      |
| Lexar               | 1         | 1      | 2%      |
| Hikvision           | 1         | 1      | 2%      |
| Gigabyte Technology | 1         | 1      | 2%      |
| Biostar             | 1         | 1      | 2%      |
| BHT                 | 1         | 1      | 2%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 48        | 60     | 43.24%  |
| SSD  | 46        | 57     | 41.44%  |
| NVMe | 17        | 17     | 15.32%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 82        | 117    | 82.83%  |
| NVMe | 17        | 17     | 17.17%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB      | Notebooks | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 64        | 82     | 67.37%  |
| 0.51-1.0        | 26        | 30     | 27.37%  |
| 1.01-2.0        | 4         | 4      | 4.21%   |
| More than 100.0 | 1         | 1      | 1.05%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 29        | 27.36%  |
| 101-250    | 28        | 26.42%  |
| 251-500    | 18        | 16.98%  |
| 51-100     | 11        | 10.38%  |
| 501-1000   | 10        | 9.43%   |
| 21-50      | 5         | 4.72%   |
| 1001-2000  | 3         | 2.83%   |
| 2001-3000  | 1         | 0.94%   |
| Unknown    | 1         | 0.94%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 85        | 84.16%  |
| 21-50    | 8         | 7.92%   |
| 101-250  | 3         | 2.97%   |
| 501-1000 | 3         | 2.97%   |
| 51-100   | 1         | 0.99%   |
| Unknown  | 1         | 0.99%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB             | 2         | 2      | 7.41%   |
| Seagate ST500LT012-9WS142 500GB    | 2         | 2      | 7.41%   |
| Samsung Electronics HM321HI 320GB  | 2         | 2      | 7.41%   |
| WDC WD5000B 500GB                  | 1         | 1      | 3.7%    |
| WDC WD1600BEVS-60RST0 160GB        | 1         | 1      | 3.7%    |
| WDC WD10JPVX-75JC3T0 1TB           | 1         | 1      | 3.7%    |
| Toshiba MK6034GSX 64GB             | 1         | 1      | 3.7%    |
| Toshiba MK5076GSX 500GB            | 1         | 1      | 3.7%    |
| Toshiba MK3261GSYN 320GB           | 1         | 1      | 3.7%    |
| Toshiba MK2555GSXF 250GB           | 1         | 1      | 3.7%    |
| Toshiba MK1252GSX 120GB            | 1         | 1      | 3.7%    |
| Toshiba MK1246GSX 120GB            | 1         | 1      | 3.7%    |
| SK hynix HFS128G39TND-N210A 128GB  | 1         | 1      | 3.7%    |
| Seagate ST9500325AS 500GB          | 1         | 1      | 3.7%    |
| Seagate ST9320325ASG 320GB         | 1         | 2      | 3.7%    |
| Seagate ST9320325AS 320GB          | 1         | 1      | 3.7%    |
| Seagate ST9250315AS 250GB          | 1         | 1      | 3.7%    |
| Seagate ST9160314AS 160GB          | 1         | 1      | 3.7%    |
| Seagate ST9120821AS 120GB          | 1         | 1      | 3.7%    |
| Seagate ST1000LM048-2E7172 1TB     | 1         | 1      | 3.7%    |
| Seagate ST1000LM025 HN-M101ABB 1TB | 1         | 1      | 3.7%    |
| LITEON LJH-64V2G-11 M.2 2260 64GB  | 1         | 1      | 3.7%    |
| Hitachi HTS547550A9E384 500GB      | 1         | 1      | 3.7%    |
| Hitachi HTS545050B9A300 500GB      | 1         | 1      | 3.7%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 11     | 37.04%  |
| Toshiba             | 8         | 8      | 29.63%  |
| WDC                 | 3         | 3      | 11.11%  |
| Samsung Electronics | 2         | 2      | 7.41%   |
| Hitachi             | 2         | 2      | 7.41%   |
| SK hynix            | 1         | 1      | 3.7%    |
| LITEON              | 1         | 1      | 3.7%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 11     | 40%     |
| Toshiba             | 8         | 8      | 32%     |
| WDC                 | 3         | 3      | 12%     |
| Samsung Electronics | 2         | 2      | 8%      |
| Hitachi             | 2         | 2      | 8%      |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 21        | 26     | 91.3%   |
| SSD  | 2         | 2      | 8.7%    |

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


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 77        | 101    | 73.33%  |
| Malfunc  | 23        | 28     | 21.9%   |
| Detected | 4         | 4      | 3.81%   |
| Failed   | 1         | 1      | 0.95%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 89        | 78.07%  |
| ADATA Technology               | 6         | 5.26%   |
| AMD                            | 5         | 4.39%   |
| Solid State Storage Technology | 3         | 2.63%   |
| Toshiba                        | 1         | 0.88%   |
| SK hynix                       | 1         | 0.88%   |
| Silicon Motion                 | 1         | 0.88%   |
| Samsung Electronics            | 1         | 0.88%   |
| Realtek Semiconductor          | 1         | 0.88%   |
| Phison Electronics             | 1         | 0.88%   |
| Nvidia                         | 1         | 0.88%   |
| Micron/Crucial Technology      | 1         | 0.88%   |
| MAXIO Technology (Hangzhou)    | 1         | 0.88%   |
| Kingston Technology Company    | 1         | 0.88%   |
| Biwin Storage Technology       | 1         | 0.88%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 15        | 12.71%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 14        | 11.86%  |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                           | 9         | 7.63%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 8         | 6.78%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 8         | 6.78%   |
| ADATA IM2P33F8ABR1 NVMe SSD                                                  | 4         | 3.39%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                               | 3         | 2.54%   |
| Intel Comet Lake SATA AHCI Controller                                        | 3         | 2.54%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                            | 3         | 2.54%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                | 3         | 2.54%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                               | 3         | 2.54%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller               | 3         | 2.54%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                            | 3         | 2.54%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                       | 2         | 1.69%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller     | 2         | 1.69%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]        | 2         | 1.69%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                             | 2         | 1.69%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                | 2         | 1.69%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]              | 2         | 1.69%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]              | 2         | 1.69%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller               | 2         | 1.69%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                         | 2         | 1.69%   |
| Toshiba BG3 NVMe SSD Controller                                              | 1         | 0.85%   |
| SK hynix BC511 NVMe SSD                                                      | 1         | 0.85%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers            | 1         | 0.85%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                | 1         | 0.85%   |
| Realtek RTS5763DL NVMe SSD Controller (DRAM-less)                            | 1         | 0.85%   |
| Phison PS5013 E13 NVMe Controller                                            | 1         | 0.85%   |
| Nvidia MCP79 AHCI Controller                                                 | 1         | 0.85%   |
| Micron/Crucial P1 NVMe PCIe SSD[Frampton]                                    | 1         | 0.85%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                 | 1         | 0.85%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                        | 1         | 0.85%   |
| Intel Tiger Lake SATA AHCI Controller                                        | 1         | 0.85%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                           | 1         | 0.85%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                | 1         | 0.85%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                        | 1         | 0.85%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                            | 1         | 0.85%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                       | 1         | 0.85%   |
| Biwin Storage EX900 NVMe SSD (DRAM-less)                                     | 1         | 0.85%   |
| AMD FCH SATA Controller [IDE mode]                                           | 1         | 0.85%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 87        | 75.65%  |
| NVMe | 18        | 15.65%  |
| IDE  | 7         | 6.09%   |
| RAID | 3         | 2.61%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 91        | 91%     |
| AMD     | 8         | 8%      |
| Unknown | 1         | 1%      |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Intel Core i5-3320M CPU @ 2.60GHz  | 4         | 4%      |
| Intel Core i3-4005U CPU @ 1.70GHz  | 4         | 4%      |
| Intel Core i5-8250U CPU @ 1.60GHz  | 3         | 3%      |
| Intel Core i5-5200U CPU @ 2.20GHz  | 3         | 3%      |
| Intel Core i5-3337U CPU @ 1.80GHz  | 3         | 3%      |
| Intel Core i5-2410M CPU @ 2.30GHz  | 3         | 3%      |
| Intel CPU Version                  | 2         | 2%      |
| Intel Core i7-8565U CPU @ 1.80GHz  | 2         | 2%      |
| Intel Core i7-7500U CPU @ 2.70GHz  | 2         | 2%      |
| Intel Core i7-5600U CPU @ 2.60GHz  | 2         | 2%      |
| Intel Core i7-10750H CPU @ 2.60GHz | 2         | 2%      |
| Intel Core i5-6300U CPU @ 2.40GHz  | 2         | 2%      |
| Intel Core i5-4210U CPU @ 1.70GHz  | 2         | 2%      |
| Intel Core i5-1035G1 CPU @ 1.00GHz | 2         | 2%      |
| Intel Core i5-10210U CPU @ 1.60GHz | 2         | 2%      |
| Intel Core i3-2330M CPU @ 2.20GHz  | 2         | 2%      |
| Intel Celeron CPU N3350 @ 1.10GHz  | 2         | 2%      |
| Intel Pentium M                    | 1         | 1%      |
| Intel Pentium CPU P6200 @ 2.13GHz  | 1         | 1%      |
| Intel Pentium CPU 5405U @ 2.30GHz  | 1         | 1%      |
| Intel Genuine CPU                  | 1         | 1%      |
| Intel Core M-5Y10c CPU @ 0.80GHz   | 1         | 1%      |
| Intel Core i7-9750H CPU @ 2.60GHz  | 1         | 1%      |
| Intel Core i7-8665U CPU @ 1.90GHz  | 1         | 1%      |
| Intel Core i7-8650U CPU @ 1.90GHz  | 1         | 1%      |
| Intel Core i7-8550U CPU @ 1.80GHz  | 1         | 1%      |
| Intel Core i7-7600U CPU @ 2.80GHz  | 1         | 1%      |
| Intel Core i7-6500U CPU @ 2.50GHz  | 1         | 1%      |
| Intel Core i7-5500U CPU @ 2.40GHz  | 1         | 1%      |
| Intel Core i7-3632QM CPU @ 2.20GHz | 1         | 1%      |
| Intel Core i7-2630QM CPU @ 2.00GHz | 1         | 1%      |
| Intel Core i7-10510U CPU @ 1.80GHz | 1         | 1%      |
| Intel Core i5-8350U CPU @ 1.70GHz  | 1         | 1%      |
| Intel Core i5-7300HQ CPU @ 2.50GHz | 1         | 1%      |
| Intel Core i5-7200U CPU @ 2.50GHz  | 1         | 1%      |
| Intel Core i5-6200U CPU @ 2.30GHz  | 1         | 1%      |
| Intel Core i5-5300U CPU @ 2.30GHz  | 1         | 1%      |
| Intel Core i5-4300U CPU @ 1.90GHz  | 1         | 1%      |
| Intel Core i5-4200U CPU @ 1.60GHz  | 1         | 1%      |
| Intel Core i5-3317U CPU @ 1.70GHz  | 1         | 1%      |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 39        | 39%     |
| Intel Core i7    | 18        | 18%     |
| Intel Core i3    | 12        | 12%     |
| Intel Celeron    | 8         | 8%      |
| Other            | 4         | 4%      |
| Intel Core 2 Duo | 4         | 4%      |
| Intel Pentium    | 2         | 2%      |
| Intel Atom       | 2         | 2%      |
| AMD Ryzen 7      | 2         | 2%      |
| AMD E1           | 2         | 2%      |
| Intel Pentium M  | 1         | 1%      |
| Intel Genuine    | 1         | 1%      |
| Intel Core M     | 1         | 1%      |
| AMD Ryzen 5      | 1         | 1%      |
| AMD E            | 1         | 1%      |
| AMD C-60         | 1         | 1%      |
| AMD C-50         | 1         | 1%      |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 69        | 69%     |
| 4       | 17        | 17%     |
| Unknown | 6         | 6%      |
| 6       | 4         | 4%      |
| 8       | 2         | 2%      |
| 16      | 1         | 1%      |
| 1       | 1         | 1%      |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 96        | 96%     |
| 2       | 2         | 2%      |
| Unknown | 2         | 2%      |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 72        | 72%     |
| 1       | 22        | 22%     |
| Unknown | 6         | 6%      |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 20        | 20%     |
| IvyBridge     | 13        | 13%     |
| SandyBridge   | 12        | 12%     |
| Broadwell     | 9         | 9%      |
| Haswell       | 8         | 8%      |
| Westmere      | 5         | 5%      |
| Skylake       | 5         | 5%      |
| Bobcat        | 5         | 5%      |
| Penryn        | 4         | 4%      |
| Core          | 3         | 3%      |
| Unknown       | 3         | 3%      |
| Zen+          | 2         | 2%      |
| IceLake       | 2         | 2%      |
| Goldmont plus | 2         | 2%      |
| Goldmont      | 2         | 2%      |
| CometLake     | 2         | 2%      |
| Bonnell       | 2         | 2%      |
| Silvermont    | 1         | 1%      |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 88        | 74.58%  |
| Nvidia | 19        | 16.1%   |
| AMD    | 11        | 9.32%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                              | 13        | 10.66%  |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 11        | 9.02%   |
| Intel HD Graphics 5500                                                        | 8         | 6.56%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 8         | 6.56%   |
| Intel UHD Graphics 620                                                        | 6         | 4.92%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 5         | 4.1%    |
| Intel Core Processor Integrated Graphics Controller                           | 5         | 4.1%    |
| Intel HD Graphics 620                                                         | 4         | 3.28%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 3         | 2.46%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 3         | 2.46%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 3         | 2.46%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 3         | 2.46%   |
| Nvidia TU117M                                                                 | 2         | 1.64%   |
| Nvidia GP108M [GeForce MX250]                                                 | 2         | 1.64%   |
| Nvidia GM108M [GeForce MX130]                                                 | 2         | 1.64%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 2         | 1.64%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                        | 2         | 1.64%   |
| Intel HD Graphics 500                                                         | 2         | 1.64%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 2         | 1.64%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 2         | 1.64%   |
| AMD Wrestler [Radeon HD 7310]                                                 | 2         | 1.64%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 2         | 1.64%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 1         | 0.82%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                    | 1         | 0.82%   |
| Nvidia GP108M [GeForce MX230]                                                 | 1         | 0.82%   |
| Nvidia GM108M [GeForce MX110]                                                 | 1         | 0.82%   |
| Nvidia GM108M [GeForce 940MX]                                                 | 1         | 0.82%   |
| Nvidia GM108M [GeForce 930M]                                                  | 1         | 0.82%   |
| Nvidia GM107M [GeForce GTX 950M]                                              | 1         | 0.82%   |
| Nvidia GK208M [GeForce GT 740M]                                               | 1         | 0.82%   |
| Nvidia GK208M [GeForce GT 735M]                                               | 1         | 0.82%   |
| Nvidia GK208BM [GeForce 920M]                                                 | 1         | 0.82%   |
| Nvidia GF119M [GeForce 410M]                                                  | 1         | 0.82%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]          | 1         | 0.82%   |
| Nvidia C79 [GeForce 9400M]                                                    | 1         | 0.82%   |
| Intel Whiskey Lake-U GT1 [UHD Graphics 610]                                   | 1         | 0.82%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                          | 1         | 0.82%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 1         | 0.82%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 1         | 0.82%   |
| Intel HD Graphics 630                                                         | 1         | 0.82%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 62        | 62%     |
| Intel + Nvidia | 17        | 17%     |
| 1 x AMD        | 9         | 9%      |
| 2 x Intel      | 7         | 7%      |
| 1 x Nvidia     | 2         | 2%      |
| Intel + AMD    | 2         | 2%      |
| Other          | 1         | 1%      |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 94        | 94%     |
| Proprietary | 3         | 3%      |
| Unknown     | 3         | 3%      |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 93        | 92.08%  |
| 0.01-0.5   | 5         | 4.95%   |
| 3.01-4.0   | 2         | 1.98%   |
| 1.01-2.0   | 1         | 0.99%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 26        | 32.1%   |
| LG Display              | 13        | 16.05%  |
| BOE                     | 9         | 11.11%  |
| Chimei Innolux          | 8         | 9.88%   |
| Samsung Electronics     | 5         | 6.17%   |
| Lenovo                  | 3         | 3.7%    |
| InfoVision              | 3         | 3.7%    |
| Dell                    | 3         | 3.7%    |
| AOC                     | 3         | 3.7%    |
| Goldstar                | 2         | 2.47%   |
| Philips                 | 1         | 1.23%   |
| PANDA                   | 1         | 1.23%   |
| JDI                     | 1         | 1.23%   |
| Hewlett-Packard         | 1         | 1.23%   |
| Chi Mei Optoelectronics | 1         | 1.23%   |
| Apple                   | 1         | 1.23%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD0385 1366x768 310x170mm 13.9-inch           | 4         | 4.94%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 340x190mm 15.3-inch         | 4         | 4.94%   |
| LG Display LCD Monitor LGD0458 1366x768 310x170mm 13.9-inch           | 2         | 2.47%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch          | 2         | 2.47%   |
| BOE LCD Monitor BOE0757 1366x768 340x190mm 15.3-inch                  | 2         | 2.47%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch         | 2         | 2.47%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 340x190mm 15.3-inch         | 2         | 2.47%   |
| AU Optronics LCD Monitor AUO303C 1366x768 310x170mm 13.9-inch         | 2         | 2.47%   |
| AU Optronics LCD Monitor AUO263D 1920x1080 310x170mm 13.9-inch        | 2         | 2.47%   |
| AOC T2242we AOC2242 1920x1080 480x270mm 21.7-inch                     | 2         | 2.47%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 340x190mm 15.3-inch  | 1         | 1.23%   |
| Samsung Electronics LCD Monitor SEC414C 1366x768 310x170mm 13.9-inch  | 1         | 1.23%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 310x170mm 13.9-inch  | 1         | 1.23%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 340x190mm 15.3-inch | 1         | 1.23%   |
| Samsung Electronics LCD Monitor SAM0D4F 1920x1080 890x500mm 40.2-inch | 1         | 1.23%   |
| Philips PHL 193V5 PHLC0CD 1366x768 410x230mm 18.5-inch                | 1         | 1.23%   |
| PANDA LCD Monitor NCP0004 1920x1080 290x170mm 13.2-inch               | 1         | 1.23%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 340x190mm 15.3-inch         | 1         | 1.23%   |
| LG Display LCD Monitor LGD05B1 1920x1080 310x170mm 13.9-inch          | 1         | 1.23%   |
| LG Display LCD Monitor LGD053C 1920x1080 310x170mm 13.9-inch          | 1         | 1.23%   |
| LG Display LCD Monitor LGD03ED 1366x768 280x160mm 12.7-inch           | 1         | 1.23%   |
| LG Display LCD Monitor LGD03B7 1366x768 310x170mm 13.9-inch           | 1         | 1.23%   |
| Lenovo LEN X24A LEN60CF 1920x1080 530x300mm 24.0-inch                 | 1         | 1.23%   |
| Lenovo LCD Monitor LEN4035 1280x800 300x190mm 14.0-inch               | 1         | 1.23%   |
| Lenovo LCD Monitor LEN4031 1280x800 300x190mm 14.0-inch               | 1         | 1.23%   |
| JDI GPD1001H JDI0031 2560x1600 890x500mm 40.2-inch                    | 1         | 1.23%   |
| InfoVision LCD Monitor IVO057D 1920x1080 310x170mm 13.9-inch          | 1         | 1.23%   |
| InfoVision LCD Monitor IVO0579 1366x768 310x170mm 13.9-inch           | 1         | 1.23%   |
| InfoVision LCD Monitor IVO03F4 1024x600 220x130mm 10.1-inch           | 1         | 1.23%   |
| Hewlett-Packard L200hx HWP298F 1600x900 450x250mm 20.3-inch           | 1         | 1.23%   |
| Goldstar LG FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch             | 1         | 1.23%   |
| Goldstar LCD Monitor GSM580D 1920x1080 510x290mm 23.1-inch            | 1         | 1.23%   |
| Dell S2419HGF DELD0E1 1920x1080 530x300mm 24.0-inch                   | 1         | 1.23%   |
| Dell P2419H DELD0D9 1920x1080 530x300mm 24.0-inch                     | 1         | 1.23%   |
| Dell P2418D DELD0C1 2560x1440 530x300mm 24.0-inch                     | 1         | 1.23%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 340x190mm 15.3-inch      | 1         | 1.23%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 340x190mm 15.3-inch       | 1         | 1.23%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 340x190mm 15.3-inch       | 1         | 1.23%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 310x170mm 13.9-inch      | 1         | 1.23%   |
| Chimei Innolux LCD Monitor CMN1496 1366x768 310x170mm 13.9-inch       | 1         | 1.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1366x768 (WXGA)  | 46        | 59.74%  |
| 1920x1080 (FHD)  | 22        | 28.57%  |
| 1280x800 (WXGA)  | 3         | 3.9%    |
| 1600x900 (HD+)   | 2         | 2.6%    |
| 2560x1600        | 1         | 1.3%    |
| 2560x1440 (QHD)  | 1         | 1.3%    |
| 1440x900 (WXGA+) | 1         | 1.3%    |
| 1024x600         | 1         | 1.3%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 13     | 33        | 40.74%  |
| 15     | 25        | 30.86%  |
| 24     | 4         | 4.94%   |
| 14     | 4         | 4.94%   |
| 12     | 4         | 4.94%   |
| 21     | 3         | 3.7%    |
| 18     | 2         | 2.47%   |
| 46     | 1         | 1.23%   |
| 40     | 1         | 1.23%   |
| 23     | 1         | 1.23%   |
| 20     | 1         | 1.23%   |
| 11     | 1         | 1.23%   |
| 10     | 1         | 1.23%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 57        | 70.37%  |
| 201-300     | 11        | 13.58%  |
| 401-500     | 6         | 7.41%   |
| 501-600     | 5         | 6.17%   |
| 801-900     | 1         | 1.23%   |
| 1001-1500   | 1         | 1.23%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 66        | 92.96%  |
| 16/10 | 5         | 7.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 36        | 44.44%  |
| 91-100         | 24        | 29.63%  |
| 201-250        | 8         | 9.88%   |
| 61-70          | 4         | 4.94%   |
| 141-150        | 2         | 2.47%   |
| 501-1000       | 2         | 2.47%   |
| 71-80          | 1         | 1.23%   |
| 51-60          | 1         | 1.23%   |
| 41-50          | 1         | 1.23%   |
| 151-200        | 1         | 1.23%   |
| 101-110        | 1         | 1.23%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 47        | 59.49%  |
| 121-160 | 19        | 24.05%  |
| 51-100  | 9         | 11.39%  |
| 161-240 | 3         | 3.8%    |
| 1-50    | 1         | 1.27%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 74        | 73.27%  |
| 2     | 14        | 13.86%  |
| 0     | 13        | 12.87%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 53        | 32.72%  |
| Qualcomm Atheros         | 44        | 27.16%  |
| Intel                    | 38        | 23.46%  |
| Broadcom                 | 12        | 7.41%   |
| JMicron Technology       | 5         | 3.09%   |
| Samsung Electronics      | 3         | 1.85%   |
| Ralink Technology        | 2         | 1.23%   |
| Xiaomi                   | 1         | 0.62%   |
| TP-Link                  | 1         | 0.62%   |
| Nvidia                   | 1         | 0.62%   |
| MediaTek                 | 1         | 0.62%   |
| Marvell Technology Group | 1         | 0.62%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 24        | 12.31%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 22        | 11.28%  |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 14        | 7.18%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 13        | 6.67%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 6         | 3.08%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 5         | 2.56%   |
| Intel Wireless 8265 / 8275                                        | 5         | 2.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 2.56%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 4         | 2.05%   |
| Intel Wireless 7265                                               | 4         | 2.05%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 4         | 2.05%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 3         | 1.54%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 3         | 1.54%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 1.54%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 3         | 1.54%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.54%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 1.54%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 3         | 1.54%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 1.03%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 1.03%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 2         | 1.03%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 1.03%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller               | 2         | 1.03%   |
| Intel Wireless 8260                                               | 2         | 1.03%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 2         | 1.03%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 2         | 1.03%   |
| Intel Gemini Lake PCH CNVi WiFi                                   | 2         | 1.03%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 1.03%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 1.03%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 1.03%   |
| Intel Centrino Advanced-N 6200                                    | 2         | 1.03%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.03%   |
| Intel 82566MM Gigabit Network Connection                          | 2         | 1.03%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.51%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1         | 0.51%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.51%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 1         | 0.51%   |
| Realtek RTL8191SEvA Wireless LAN Controller                       | 1         | 0.51%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                            | 1         | 0.51%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1         | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Qualcomm Atheros      | 43        | 42.16%  |
| Intel                 | 37        | 36.27%  |
| Realtek Semiconductor | 13        | 12.75%  |
| Broadcom              | 6         | 5.88%   |
| Ralink Technology     | 2         | 1.96%   |
| TP-Link               | 1         | 0.98%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 14        | 13.59%  |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 13        | 12.62%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 6         | 5.83%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 5         | 4.85%   |
| Intel Wireless 8265 / 8275                                     | 5         | 4.85%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 4         | 3.88%   |
| Intel Wireless 7265                                            | 4         | 3.88%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 4         | 3.88%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 3         | 2.91%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 3         | 2.91%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2         | 1.94%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 2         | 1.94%   |
| Intel Wireless 8260                                            | 2         | 1.94%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 2         | 1.94%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 2         | 1.94%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 2         | 1.94%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 2         | 1.94%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 2         | 1.94%   |
| Intel Centrino Advanced-N 6200                                 | 2         | 1.94%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1         | 0.97%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 0.97%   |
| Realtek RTL8191SEvA Wireless LAN Controller                    | 1         | 0.97%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                         | 1         | 0.97%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 0.97%   |
| Realtek 8811CU Wireless LAN 802.11ac USB NIC                   | 1         | 0.97%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 1         | 0.97%   |
| Ralink RT2501/RT2573 Wireless Adapter                          | 1         | 0.97%   |
| Intel Wireless 7260                                            | 1         | 0.97%   |
| Intel Wireless 3165                                            | 1         | 0.97%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 1         | 0.97%   |
| Intel Wi-Fi 6 AX200                                            | 1         | 0.97%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 1         | 0.97%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 1         | 0.97%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 1         | 0.97%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 1         | 0.97%   |
| Intel Centrino Wireless-N 2230                                 | 1         | 0.97%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 1         | 0.97%   |
| Broadcom BRCM4378 Wireless Network Adapter                     | 1         | 0.97%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 1         | 0.97%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 1         | 0.97%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 47        | 51.65%  |
| Intel                    | 19        | 20.88%  |
| Broadcom                 | 7         | 7.69%   |
| Qualcomm Atheros         | 6         | 6.59%   |
| JMicron Technology       | 5         | 5.49%   |
| Samsung Electronics      | 3         | 3.3%    |
| Xiaomi                   | 1         | 1.1%    |
| Nvidia                   | 1         | 1.1%    |
| MediaTek                 | 1         | 1.1%    |
| Marvell Technology Group | 1         | 1.1%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 24        | 26.37%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 22        | 24.18%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 5.49%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 3.3%    |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 3         | 3.3%    |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 3.3%    |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 3.3%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 3         | 3.3%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 2.2%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 2.2%    |
| JMicron JMC260 PCI Express Fast Ethernet Controller               | 2         | 2.2%    |
| Intel Ethernet Connection I219-LM                                 | 2         | 2.2%    |
| Intel 82577LM Gigabit Network Connection                          | 2         | 2.2%    |
| Intel 82566MM Gigabit Network Connection                          | 2         | 2.2%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.1%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 1.1%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 1.1%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 1.1%    |
| Nvidia MCP79 Ethernet                                             | 1         | 1.1%    |
| MediaTek USB Ethernet-RNDIS                                       | 1         | 1.1%    |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 1.1%    |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.1%    |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 1.1%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 1.1%    |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 1         | 1.1%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 1.1%    |
| Broadcom BCM4401-B0 100Base-TX                                    | 1         | 1.1%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 97        | 51.87%  |
| Ethernet | 89        | 47.59%  |
| Unknown  | 1         | 0.53%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 67        | 51.15%  |
| Ethernet | 64        | 48.85%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 84        | 84%     |
| 1     | 16        | 16%     |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 92        | 92%     |
| Yes  | 8         | 8%      |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Qualcomm Atheros Communications | 25        | 34.25%  |
| Intel                           | 25        | 34.25%  |
| Broadcom                        | 6         | 8.22%   |
| Lite-On Technology              | 4         | 5.48%   |
| Foxconn / Hon Hai               | 4         | 5.48%   |
| Apple                           | 4         | 5.48%   |
| Realtek Semiconductor           | 3         | 4.11%   |
| IMC Networks                    | 1         | 1.37%   |
| Dell                            | 1         | 1.37%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 11        | 15.07%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 7         | 9.59%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 6         | 8.22%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 6         | 8.22%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 5         | 6.85%   |
| Qualcomm Atheros Dell Wireless 1703 Bluetooth               | 4         | 5.48%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 3         | 4.11%   |
| Intel AX201 Bluetooth                                       | 3         | 4.11%   |
| Apple Bluetooth Host Controller                             | 3         | 4.11%   |
| Realtek Bluetooth Adapter                                   | 2         | 2.74%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3011 Bluetooth Adapter | 2         | 2.74%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 2         | 2.74%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 2         | 2.74%   |
| Realtek CSR Bluetooth Chip                                  | 1         | 1.37%   |
| Qualcomm Atheros AR3011 Bluetooth                           | 1         | 1.37%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 1         | 1.37%   |
| Lite-On Qualcomm Atheros Bluetooth                          | 1         | 1.37%   |
| Lite-On Atheros Bluetooth                                   | 1         | 1.37%   |
| Lite-On Atheros AR3012 Bluetooth                            | 1         | 1.37%   |
| Intel Wireless-AC 3168 Bluetooth                            | 1         | 1.37%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 1         | 1.37%   |
| Intel AX210 Bluetooth                                       | 1         | 1.37%   |
| Intel AX200 Bluetooth                                       | 1         | 1.37%   |
| IMC Networks Bluetooth Module                               | 1         | 1.37%   |
| Foxconn / Hon Hai Qualcomm Atheros Bluetooth 4.0            | 1         | 1.37%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device             | 1         | 1.37%   |
| Dell Wireless 355 Bluetooth                                 | 1         | 1.37%   |
| Broadcom BCM2046 Bluetooth Device                           | 1         | 1.37%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 1         | 1.37%   |
| Apple Built-in iSight (no firmware loaded)                  | 1         | 1.37%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor            | Notebooks | Percent |
|-------------------|-----------|---------|
| Intel             | 89        | 83.18%  |
| AMD               | 8         | 7.48%   |
| Nvidia            | 6         | 5.61%   |
| Texas Instruments | 1         | 0.93%   |
| M-Audio           | 1         | 0.93%   |
| Logitech          | 1         | 0.93%   |
| Lenovo            | 1         | 0.93%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 16        | 12.31%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 16        | 12.31%  |
| Intel Broadwell-U Audio Controller                                         | 9         | 6.92%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 8         | 6.15%   |
| Intel Haswell-ULT HD Audio Controller                                      | 8         | 6.15%   |
| Intel 8 Series HD Audio Controller                                         | 8         | 6.15%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 8         | 6.15%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 5         | 3.85%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 4         | 3.08%   |
| AMD Wrestler HDMI Audio                                                    | 4         | 3.08%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 2.31%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3         | 2.31%   |
| Intel Comet Lake PCH-LP cAVS                                               | 3         | 2.31%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 3         | 2.31%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 3         | 2.31%   |
| AMD Family 17h/19h HD Audio Controller                                     | 3         | 2.31%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 1.54%   |
| Intel Comet Lake PCH cAVS                                                  | 2         | 1.54%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 1.54%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 2         | 1.54%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 1.54%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 1.54%   |
| AMD FCH Azalia Controller                                                  | 2         | 1.54%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1         | 0.77%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 0.77%   |
| Nvidia MCP79 High Definition Audio                                         | 1         | 0.77%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 0.77%   |
| M-Audio M-Audio Fast Track Pro                                             | 1         | 0.77%   |
| Logitech H390 headset with microphone                                      | 1         | 0.77%   |
| Lenovo Realtek USB Audio                                                   | 1         | 0.77%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1         | 0.77%   |
| Intel CM238 HD Audio Controller                                            | 1         | 0.77%   |
| Intel Cannon Lake PCH cAVS                                                 | 1         | 0.77%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 0.77%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 1         | 0.77%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Smart               | 27        | 24.32%  |
| Samsung Electronics | 13        | 11.71%  |
| Kingston            | 13        | 11.71%  |
| Unknown             | 9         | 8.11%   |
| SK hynix            | 9         | 8.11%   |
| Teikon              | 7         | 6.31%   |
| A-DATA Technology   | 7         | 6.31%   |
| Smart Brazil        | 5         | 4.5%    |
| High Bridge         | 5         | 4.5%    |
| Crucial             | 4         | 3.6%    |
| Micron Technology   | 3         | 2.7%    |
| Multilaser          | 2         | 1.8%    |
| Apacer              | 2         | 1.8%    |
| Unknown (ABCD)      | 1         | 0.9%    |
| Smart Modular       | 1         | 0.9%    |
| PNY                 | 1         | 0.9%    |
| Nanya Technology    | 1         | 0.9%    |
| Kllisre             | 1         | 0.9%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                              | Notebooks | Percent |
|--------------------------------------------------------------------|-----------|---------|
| Smart RAM SH564568FH8NZPHSCR 2GB SODIMM DDR3 1334MT/s              | 4         | 3.39%   |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s              | 4         | 3.39%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s              | 4         | 3.39%   |
| Smart RAM SH564128FJ8NZRNSDG 4GB SODIMM DDR3 1600MT/s              | 3         | 2.54%   |
| Smart RAM SH564128FH8NZQNSCG 4GB SODIMM DDR3 1600MT/s              | 3         | 2.54%   |
| Smart RAM SH564128FH8NZPHSCR 4GB SODIMM DDR3 1333MT/s              | 3         | 2.54%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                         | 2         | 1.69%   |
| Teikon RAM TML251S6EFR8A-PBHC 4GB SODIMM DDR3 1600MT/s             | 2         | 1.69%   |
| Smart RAM SF4641G8CK8IEHLSBG 8GB SODIMM DDR4 2667MT/s              | 2         | 1.69%   |
| Smart Brazil RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2400MT/s       | 2         | 1.69%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s              | 2         | 1.69%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s              | 2         | 1.69%   |
| Multilaser RAM MS3512NSZ-CA3G1 4GB SODIMM DDR3 1600MT/s            | 2         | 1.69%   |
| High Bridge RAM HB3SU002GFM8MMB33. 2GB SODIMM DDR3 1334MT/s        | 2         | 1.69%   |
| Unknown SODIMM 2048MB SODIMM DDR2 667MT/s                          | 1         | 0.85%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                        | 1         | 0.85%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                        | 1         | 0.85%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                        | 1         | 0.85%   |
| Unknown RAM Module 4GB SODIMM DDR3                                 | 1         | 0.85%   |
| Unknown RAM Module 4GB SODIMM DDR2 800MT/s                         | 1         | 0.85%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                        | 1         | 0.85%   |
| Unknown RAM Module 2GB SODIMM DDR3                                 | 1         | 0.85%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s   | 1         | 0.85%   |
| Teikon RAM TMT451S6BFR8A-PBSC 4096MB SODIMM DDR3 1600MT/s          | 1         | 0.85%   |
| Teikon RAM TMT451S6BFR8A-PBHC 4GB SODIMM DDR3 1333MT/s             | 1         | 0.85%   |
| Teikon RAM TMT41GS6BFR8A-PBSC 8GB SODIMM DDR3 1600MT/s             | 1         | 0.85%   |
| Teikon RAM TMT225S6FR8C-H9HC 2GB SODIMM DDR3 1334MT/s              | 1         | 0.85%   |
| Teikon RAM TMA81GS6AFR8N-UHSC 8GB SODIMM DDR4 2400MT/s             | 1         | 0.85%   |
| Smart RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2133MT/s              | 1         | 0.85%   |
| Smart RAM SH564568FH8NWPHSFR 2GB SODIMM DDR3 1333MT/s              | 1         | 0.85%   |
| Smart RAM SH564128FJ8NZRNSDR 4GB SODIMM DDR3 1600MT/s              | 1         | 0.85%   |
| Smart RAM SH564128FH8NZPHSCG 4GB SODIMM DDR3 667MT/s               | 1         | 0.85%   |
| Smart RAM SF564128CJ8NWMNSEG 4GB SODIMM DDR3 1600MT/s              | 1         | 0.85%   |
| Smart RAM SF4641G8CK8IWGKSEG 8GB SODIMM DDR4 2133MT/s              | 1         | 0.85%   |
| Smart RAM SF464128CKHIWDFSEG 4GB SODIMM DDR4 2133MT/s              | 1         | 0.85%   |
| Smart Modular RAM SMS4WEC8C1K0446FCG 8GB SODIMM DDR4 3200MT/s      | 1         | 0.85%   |
| Smart Brazil RAM SMS4WEC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s       | 1         | 0.85%   |
| Smart Brazil RAM SF4641G8CK8IEHLSBG 8GB SODIMM DDR4 2133MT/s       | 1         | 0.85%   |
| Smart Brazil RAM SDQC8G8W16XCWE9N1T 4GB Row Of Chips DDR4 2667MT/s | 1         | 0.85%   |
| Smart Brazil RAM Module 4GB Row Of Chips DDR4 2400MT/s             | 1         | 0.85%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 55        | 62.5%   |
| DDR4   | 24        | 27.27%  |
| DDR2   | 7         | 7.95%   |
| LPDDR4 | 1         | 1.14%   |
| DDR    | 1         | 1.14%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 86        | 97.73%  |
| Row Of Chips | 2         | 2.27%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 48        | 46.6%   |
| 8192  | 22        | 21.36%  |
| 2048  | 22        | 21.36%  |
| 16384 | 9         | 8.74%   |
| 1024  | 2         | 1.94%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 34        | 34%     |
| 1333    | 15        | 15%     |
| 2400    | 11        | 11%     |
| 2667    | 10        | 10%     |
| 1334    | 10        | 10%     |
| 667     | 5         | 5%      |
| 2133    | 4         | 4%      |
| 533     | 3         | 3%      |
| 3200    | 2         | 2%      |
| 800     | 2         | 2%      |
| 1867    | 1         | 1%      |
| 1067    | 1         | 1%      |
| 975     | 1         | 1%      |
| Unknown | 1         | 1%      |

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
| Chicony Electronics           | 19        | 22.62%  |
| Bison Electronics             | 14        | 16.67%  |
| Microdia                      | 10        | 11.9%   |
| Realtek Semiconductor         | 9         | 10.71%  |
| Silicon Motion                | 7         | 8.33%   |
| Suyin                         | 3         | 3.57%   |
| Sunplus Innovation Technology | 3         | 3.57%   |
| IMC Networks                  | 3         | 3.57%   |
| Unknown                       | 2         | 2.38%   |
| Syntek                        | 2         | 2.38%   |
| Luxvisions Innotech Limited   | 2         | 2.38%   |
| Logitech                      | 2         | 2.38%   |
| Lenovo                        | 2         | 2.38%   |
| Alcor Micro                   | 2         | 2.38%   |
| Tripath Technology            | 1         | 1.19%   |
| Quanta                        | 1         | 1.19%   |
| Lite-On Technology            | 1         | 1.19%   |
| Apple                         | 1         | 1.19%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony HD WebCam                             | 5         | 5.88%   |
| Bison Integrated Camera                       | 5         | 5.88%   |
| Silicon Motion Realtek DMFT RGB               | 4         | 4.71%   |
| Microdia Integrated_Webcam_HD                 | 4         | 4.71%   |
| Microdia Dell Laptop Integrated Webcam HD     | 4         | 4.71%   |
| Realtek Dell EasyCamera                       | 3         | 3.53%   |
| Chicony Sony Visual Communication Camera      | 3         | 3.53%   |
| Bison Lenovo EasyCamera                       | 3         | 3.53%   |
| Unknown Realtek PC Camera                     | 2         | 2.35%   |
| Syntek EasyCamera                             | 2         | 2.35%   |
| Sunplus Integrated_Webcam_HD                  | 2         | 2.35%   |
| Realtek Integrated Webcam                     | 2         | 2.35%   |
| Luxvisions Innotech Limited Integrated Camera | 2         | 2.35%   |
| Bison HD Webcam                               | 2         | 2.35%   |
| Alcor Micro Acer Integrated Webcam            | 2         | 2.35%   |
| Tripath USB Camera                            | 1         | 1.18%   |
| Suyin WebCam                                  | 1         | 1.18%   |
| Suyin USB 2.0 UVC 1.3M WebCam                 | 1         | 1.18%   |
| Suyin Integrated_Webcam_HD                    | 1         | 1.18%   |
| Sunplus HD WebCam                             | 1         | 1.18%   |
| Silicon Motion WebCam SCX Series              | 1         | 1.18%   |
| Silicon Motion Realtek USB 2.0 PC Camera      | 1         | 1.18%   |
| Silicon Motion ATIV VGA Camera                | 1         | 1.18%   |
| Realtek LG Camera                             | 1         | 1.18%   |
| Realtek Integrated_Webcam_FHD                 | 1         | 1.18%   |
| Realtek Integrated_Webcam_8M                  | 1         | 1.18%   |
| Realtek Integrated Webcam HD                  | 1         | 1.18%   |
| Realtek Composite Webcam                      | 1         | 1.18%   |
| Quanta HD Webcam                              | 1         | 1.18%   |
| Microdia Laptop_Integrated_Webcam_HD          | 1         | 1.18%   |
| Microdia Integrated Webcam HD                 | 1         | 1.18%   |
| Logitech Webcam C270                          | 1         | 1.18%   |
| Logitech C922 Pro Stream Webcam               | 1         | 1.18%   |
| Lite-On Integrated Camera                     | 1         | 1.18%   |
| Lenovo Integrated Webcam [R5U877]             | 1         | 1.18%   |
| Lenovo Integrated Webcam                      | 1         | 1.18%   |
| IMC Networks Realtek DMFT RGB                 | 1         | 1.18%   |
| IMC Networks EasyCamera                       | 1         | 1.18%   |
| IMC Networks ASUS EasyCamera                  | 1         | 1.18%   |
| Chicony Webcam                                | 1         | 1.18%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 6         | 37.5%   |
| Upek                       | 4         | 25%     |
| Synaptics                  | 2         | 12.5%   |
| Shenzhen Goodix Technology | 2         | 12.5%   |
| Samsung Electronics        | 1         | 6.25%   |
| Broadcom                   | 1         | 6.25%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 4         | 25%     |
| Validity Sensors VFS 5011 fingerprint sensor                                 | 2         | 12.5%   |
| Shenzhen Goodix Fingerprint Reader                                           | 2         | 12.5%   |
| Validity Sensors VFS5011 Fingerprint Reader                                  | 1         | 6.25%   |
| Validity Sensors VFS495 Fingerprint Reader                                   | 1         | 6.25%   |
| Validity Sensors Synaptics WBDI                                              | 1         | 6.25%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                  | 1         | 6.25%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 1         | 6.25%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                             | 1         | 6.25%   |
| Samsung CanvasBio Fingerprint Reader                                         | 1         | 6.25%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 6.25%   |

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
| 1     | 31        | 30.69%  |
| 2     | 29        | 28.71%  |
| 3     | 16        | 15.84%  |
| 0     | 12        | 11.88%  |
| 4     | 8         | 7.92%   |
| 5     | 5         | 4.95%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 79        | 43.89%  |
| Card reader              | 34        | 18.89%  |
| Bluetooth                | 25        | 13.89%  |
| Net/wireless             | 20        | 11.11%  |
| Fingerprint reader       | 15        | 8.33%   |
| Sound                    | 2         | 1.11%   |
| Network                  | 2         | 1.11%   |
| Storage                  | 1         | 0.56%   |
| Net/ethernet             | 1         | 0.56%   |
| Graphics card            | 1         | 0.56%   |

