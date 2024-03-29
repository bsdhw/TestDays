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

Total: 138

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Lenovo        | V14 G2 ITL 82NM             | [952fa413fe](https://bsd-hardware.info/?probe=952fa413fe) | Feb 01, 2024 |
| Lenovo        | V14 G2 ITL 82NM             | [b66edf2033](https://bsd-hardware.info/?probe=b66edf2033) | Jan 31, 2024 |
| Acer          | Nitro AN515-54              | [94f04895fe](https://bsd-hardware.info/?probe=94f04895fe) | Jan 27, 2024 |
| Acer          | Nitro AN515-54              | [28539d7eb4](https://bsd-hardware.info/?probe=28539d7eb4) | Jan 24, 2024 |
| Lenovo        | ThinkPad X220 42912Z1       | [1abc94b4b1](https://bsd-hardware.info/?probe=1abc94b4b1) | Jan 17, 2024 |
| Acer          | Aspire E5-574               | [8b71e16af3](https://bsd-hardware.info/?probe=8b71e16af3) | Dec 27, 2023 |
| Apple         | MacBookAir5,2               | [2c652aa0a1](https://bsd-hardware.info/?probe=2c652aa0a1) | Dec 16, 2023 |
| Acer          | Aspire E5-574               | [b11a972371](https://bsd-hardware.info/?probe=b11a972371) | Nov 24, 2023 |
| Acer          | Aspire E5-574               | [a4eded7a52](https://bsd-hardware.info/?probe=a4eded7a52) | Nov 22, 2023 |
| Acer          | Aspire ES1-572              | [2aa8175a33](https://bsd-hardware.info/?probe=2aa8175a33) | Nov 17, 2023 |
| Dell          | Inspiron 3442               | [3f63ee5447](https://bsd-hardware.info/?probe=3f63ee5447) | Nov 13, 2023 |
| Dell          | Inspiron N4050              | [9bc3c5e163](https://bsd-hardware.info/?probe=9bc3c5e163) | Nov 05, 2023 |
| Lenovo        | B40-30 80F1                 | [00c5e6adda](https://bsd-hardware.info/?probe=00c5e6adda) | Oct 03, 2023 |
| GPD           | G1619-04                    | [30ad9b72b5](https://bsd-hardware.info/?probe=30ad9b72b5) | Sep 23, 2023 |
| Compaq        | Presario CQ-17              | [f97feb2db0](https://bsd-hardware.info/?probe=f97feb2db0) | Aug 04, 2023 |
| Dell          | Latitude E6420              | [3151e6d3bb](https://bsd-hardware.info/?probe=3151e6d3bb) | Jul 05, 2023 |
| Dell          | Latitude 5490               | [b638c1b2b1](https://bsd-hardware.info/?probe=b638c1b2b1) | Jun 23, 2023 |
| HP            | 1000                        | [21faecd7a6](https://bsd-hardware.info/?probe=21faecd7a6) | Jun 23, 2023 |
| Lenovo        | B40-30 80F1                 | [769c678314](https://bsd-hardware.info/?probe=769c678314) | Jun 10, 2023 |
| Acer          | Nitro AN515-57              | [c39ea00de5](https://bsd-hardware.info/?probe=c39ea00de5) | May 25, 2023 |
| Sony          | VPCEG15FB                   | [8777493861](https://bsd-hardware.info/?probe=8777493861) | May 21, 2023 |
| Unknown       | Apple MacBook Pro (13-in... | [5e25a49c65](https://bsd-hardware.info/?probe=5e25a49c65) | May 20, 2023 |
| Lenovo        | ThinkPad T61 7659AS5        | [7732b2cfa7](https://bsd-hardware.info/?probe=7732b2cfa7) | May 15, 2023 |
| Lenovo        | ThinkPad T61 7659AS5        | [b6071c549a](https://bsd-hardware.info/?probe=b6071c549a) | May 15, 2023 |
| Sony          | SVF14A15CBB                 | [4ada2dca25](https://bsd-hardware.info/?probe=4ada2dca25) | May 14, 2023 |
| Lenovo        | V14 G2 ITL 82NM             | [fa87f4741a](https://bsd-hardware.info/?probe=fa87f4741a) | May 13, 2023 |
| Lenovo        | V14 G2 ITL 82NM             | [bd81294acc](https://bsd-hardware.info/?probe=bd81294acc) | May 13, 2023 |
| Intel         | HuronRiver Platform         | [83494ffd65](https://bsd-hardware.info/?probe=83494ffd65) | May 11, 2023 |
| Lenovo        | V14 G2 ITL 82NM             | [827308827b](https://bsd-hardware.info/?probe=827308827b) | Apr 24, 2023 |
| Dell          | Inspiron 3421               | [ef4870410f](https://bsd-hardware.info/?probe=ef4870410f) | Apr 23, 2023 |
| Lenovo        | V14 G2 ITL 82NM             | [a6141b809a](https://bsd-hardware.info/?probe=a6141b809a) | Apr 21, 2023 |
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
| helloSystem 0.8.1    | 14        | 11.97%  |
| helloSystem 0.7.0    | 12        | 10.26%  |
| helloSystem 0.6.0    | 10        | 8.55%   |
| helloSystem 0.4.0    | 10        | 8.55%   |
| helloSystem 0.5.0    | 9         | 7.69%   |
| helloSystem 0.8.0    | 8         | 6.84%   |
| helloSystem 0.9.0    | 6         | 5.13%   |
| FreeBSD 13.0         | 6         | 5.13%   |
| OpenBSD 7.3          | 5         | 4.27%   |
| FreeBSD 14.0-CURRENT | 3         | 2.56%   |
| FreeBSD 13.0-p3      | 3         | 2.56%   |
| FreeBSD 14.0         | 2         | 1.71%   |
| FreeBSD 13.2         | 2         | 1.71%   |
| FreeBSD 13.0-STABLE  | 2         | 1.71%   |
| FreeBSD 12.1         | 2         | 1.71%   |
| OS108 9.99.68        | 1         | 0.85%   |
| OPNsense 23.1.7      | 1         | 0.85%   |
| OPNsense 22.7.4      | 1         | 0.85%   |
| OpenBSD 7.2          | 1         | 0.85%   |
| OpenBSD 7.0          | 1         | 0.85%   |
| OpenBSD 6.9          | 1         | 0.85%   |
| helloSystem 0.8.2    | 1         | 0.85%   |
| helloSystem 0.3.0    | 1         | 0.85%   |
| GhostBSD 23.05.22    | 1         | 0.85%   |
| GhostBSD 22.11.22    | 1         | 0.85%   |
| GhostBSD 22.07.10    | 1         | 0.85%   |
| GhostBSD 20.04.02    | 1         | 0.85%   |
| FreeBSD 15.0-CURRENT | 1         | 0.85%   |
| FreeBSD 13.1-p4      | 1         | 0.85%   |
| FreeBSD 13.0-RC2     | 1         | 0.85%   |
| FreeBSD 13.0-p7      | 1         | 0.85%   |
| FreeBSD 13.0-p4      | 1         | 0.85%   |
| FreeBSD 13.0-CURRENT | 1         | 0.85%   |
| FreeBSD 12.2-p3      | 1         | 0.85%   |
| FreeBSD 12.2         | 1         | 0.85%   |
| FreeBSD 12.1-p7      | 1         | 0.85%   |
| FreeBSD 12.1-p11     | 1         | 0.85%   |
| DragonFly 5.8        | 1         | 0.85%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| helloSystem | 67        | 60.36%  |
| FreeBSD     | 28        | 25.23%  |
| OpenBSD     | 8         | 7.21%   |
| GhostBSD    | 4         | 3.6%    |
| OPNsense    | 2         | 1.8%    |
| OS108       | 1         | 0.9%    |
| DragonFly   | 1         | 0.9%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 105       | 97.22%  |
| i386  | 2         | 1.85%   |
| arm64 | 1         | 0.93%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 70        | 63.64%  |
| Console      | 7         | 6.36%   |
| XFCE         | 6         | 5.45%   |
| MATE         | 6         | 5.45%   |
| GNOME        | 6         | 5.45%   |
| KDE5         | 4         | 3.64%   |
| TWM          | 3         | 2.73%   |
| i3           | 3         | 2.73%   |
| fvwm         | 2         | 1.82%   |
| spectrwm     | 1         | 0.91%   |
| Openbox      | 1         | 0.91%   |
| LXQt         | 1         | 0.91%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 101       | 92.66%  |
| Console | 8         | 7.34%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SLiM    | 72        | 64.86%  |
| Console | 21        | 18.92%  |
| LightDM | 8         | 7.21%   |
| SDDM    | 4         | 3.6%    |
| XDM     | 3         | 2.7%    |
| GDM     | 3         | 2.7%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang            | Notebooks | Percent |
|-----------------|-----------|---------|
| en_US           | 52        | 46.02%  |
| Unknown         | 21        | 18.58%  |
| pt_BR           | 16        | 14.16%  |
| C               | 13        | 11.5%   |
| pt              | 5         | 4.42%   |
| fr_FR           | 4         | 3.54%   |
| en_US.ISO8859-1 | 1         | 0.88%   |
| en_GB           | 1         | 0.88%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 96        | 88.89%  |
| BIOS | 12        | 11.11%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Zfs     | 75        | 66.37%  |
| Cd9660  | 16        | 14.16%  |
| Ufs     | 13        | 11.5%   |
| Ffs     | 8         | 7.08%   |
| Hammer2 | 1         | 0.88%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 105       | 97.22%  |
| MBR     | 2         | 1.85%   |
| Unknown | 1         | 0.93%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 28        | 25.93%  |
| Dell                   | 25        | 23.15%  |
| Acer                   | 14        | 12.96%  |
| Samsung Electronics    | 9         | 8.33%   |
| Sony                   | 4         | 3.7%    |
| Apple                  | 4         | 3.7%    |
| Hewlett-Packard        | 3         | 2.78%   |
| Avell High Performance | 3         | 2.78%   |
| Unknown                | 3         | 2.78%   |
| Itautec                | 2         | 1.85%   |
| Gateway                | 2         | 1.85%   |
| ASUSTek Computer       | 2         | 1.85%   |
| Semp Toshiba           | 1         | 0.93%   |
| Positivo               | 1         | 0.93%   |
| Philco                 | 1         | 0.93%   |
| Notebook               | 1         | 0.93%   |
| LG Electronics         | 1         | 0.93%   |
| Intel                  | 1         | 0.93%   |
| GPD                    | 1         | 0.93%   |
| Compaq                 | 1         | 0.93%   |
| Clevo                  | 1         | 0.93%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Dell Inspiron 3442                          | 6         | 5.56%   |
| Dell Inspiron 3421                          | 3         | 2.78%   |
| Unknown                                     | 3         | 2.78%   |
| Samsung 340XAA/350XAA/550XAA                | 2         | 1.85%   |
| Samsung 270E5K/270E5Q/271E5K/2570EK         | 2         | 1.85%   |
| Gateway NE56R                               | 2         | 1.85%   |
| Dell Latitude 5490                          | 2         | 1.85%   |
| Acer Aspire 5750                            | 2         | 1.85%   |
| Sony VPCYB45JB                              | 1         | 0.93%   |
| Sony VPCEG17FB                              | 1         | 0.93%   |
| Sony VPCEG15FB                              | 1         | 0.93%   |
| Sony SVF14A15CBB                            | 1         | 0.93%   |
| Semp Toshiba STI NA 1401                    | 1         | 0.93%   |
| Samsung RV411/RV511/E3511/S3511/RV711/E3411 | 1         | 0.93%   |
| Samsung 530XBB                              | 1         | 0.93%   |
| Samsung 370E4K                              | 1         | 0.93%   |
| Samsung 300E5M/300E5L                       | 1         | 0.93%   |
| Samsung 275E4E/275E5E                       | 1         | 0.93%   |
| Positivo C14CR01                            | 1         | 0.93%   |
| Philco 10B                                  | 1         | 0.93%   |
| Notebook N85_N87HCHNHZ                      | 1         | 0.93%   |
| LG 14Z980-G.BH51P1                          | 1         | 0.93%   |
| Lenovo V14 G2 ITL 82NM                      | 1         | 0.93%   |
| Lenovo ThinkPad X270 20HM004JBR             | 1         | 0.93%   |
| Lenovo ThinkPad X250 20CLS2A11K             | 1         | 0.93%   |
| Lenovo ThinkPad X250 20CLS18S0Z             | 1         | 0.93%   |
| Lenovo ThinkPad X240 20AMS4V000             | 1         | 0.93%   |
| Lenovo ThinkPad X230 23257EP                | 1         | 0.93%   |
| Lenovo ThinkPad X220 4291ON5                | 1         | 0.93%   |
| Lenovo ThinkPad X220 42912Z1                | 1         | 0.93%   |
| Lenovo ThinkPad X201 36801T6                | 1         | 0.93%   |
| Lenovo ThinkPad T61 7661GY9                 | 1         | 0.93%   |
| Lenovo ThinkPad T61 7659AS5                 | 1         | 0.93%   |
| Lenovo ThinkPad T490 20N30029BR             | 1         | 0.93%   |
| Lenovo ThinkPad T460 20FN002JUS             | 1         | 0.93%   |
| Lenovo ThinkPad T450s 20BWS05G0T            | 1         | 0.93%   |
| Lenovo ThinkPad T430u 33522D5               | 1         | 0.93%   |
| Lenovo ThinkPad T430 2349PMP                | 1         | 0.93%   |
| Lenovo ThinkPad T430 2349G5P                | 1         | 0.93%   |
| Lenovo ThinkPad T410 2522CS7                | 1         | 0.93%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Lenovo ThinkPad            | 18        | 16.67%  |
| Dell Inspiron              | 18        | 16.67%  |
| Acer Aspire                | 12        | 11.11%  |
| Lenovo IdeaPad             | 5         | 4.63%   |
| Dell Latitude              | 4         | 3.7%    |
| Unknown                    | 3         | 2.78%   |
| Samsung 340XAA             | 2         | 1.85%   |
| Samsung 270E5K             | 2         | 1.85%   |
| Itautec Infoway            | 2         | 1.85%   |
| Gateway NE56R              | 2         | 1.85%   |
| Dell Vostro                | 2         | 1.85%   |
| Avell High Performance A62 | 2         | 1.85%   |
| Acer Nitro                 | 2         | 1.85%   |
| Sony VPCYB45JB             | 1         | 0.93%   |
| Sony VPCEG17FB             | 1         | 0.93%   |
| Sony VPCEG15FB             | 1         | 0.93%   |
| Sony SVF14A15CBB           | 1         | 0.93%   |
| Semp Toshiba STI           | 1         | 0.93%   |
| Samsung RV411              | 1         | 0.93%   |
| Samsung 530XBB             | 1         | 0.93%   |
| Samsung 370E4K             | 1         | 0.93%   |
| Samsung 300E5M             | 1         | 0.93%   |
| Samsung 275E4E             | 1         | 0.93%   |
| Positivo C14CR01           | 1         | 0.93%   |
| Philco 10B                 | 1         | 0.93%   |
| Notebook N85               | 1         | 0.93%   |
| LG 14Z980-G.BH51P1         | 1         | 0.93%   |
| Lenovo V14                 | 1         | 0.93%   |
| Lenovo G550                | 1         | 0.93%   |
| Lenovo G475                | 1         | 0.93%   |
| Lenovo B40-70              | 1         | 0.93%   |
| Lenovo B40-30              | 1         | 0.93%   |
| Intel HuronRiver           | 1         | 0.93%   |
| HP EliteBook               | 1         | 0.93%   |
| HP 14                      | 1         | 0.93%   |
| HP 1000                    | 1         | 0.93%   |
| GPD G1619-04               | 1         | 0.93%   |
| Dell Venue                 | 1         | 0.93%   |
| Compaq Presario            | 1         | 0.93%   |
| Clevo C41X0                | 1         | 0.93%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2013    | 16        | 14.81%  |
| 2011    | 12        | 11.11%  |
| 2018    | 10        | 9.26%   |
| 2020    | 9         | 8.33%   |
| 2016    | 8         | 7.41%   |
| 2014    | 8         | 7.41%   |
| 2019    | 7         | 6.48%   |
| 2022    | 5         | 4.63%   |
| 2017    | 5         | 4.63%   |
| 2015    | 5         | 4.63%   |
| 2012    | 5         | 4.63%   |
| 2021    | 4         | 3.7%    |
| 2010    | 3         | 2.78%   |
| 2009    | 3         | 2.78%   |
| 2007    | 3         | 2.78%   |
| Unknown | 3         | 2.78%   |
| 2023    | 1         | 0.93%   |
| 2008    | 1         | 0.93%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 108       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 108       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 8.01-16.0  | 49        | 44.55%  |
| 4.01-8.0   | 38        | 34.55%  |
| 16.01-24.0 | 12        | 10.91%  |
| 24.01-32.0 | 4         | 3.64%   |
| 3.01-4.0   | 3         | 2.73%   |
| 32.01-64.0 | 2         | 1.82%   |
| 2.01-3.0   | 2         | 1.82%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 74        | 67.27%  |
| 0.51-1.0   | 29        | 26.36%  |
| 2.01-3.0   | 2         | 1.82%   |
| 1.01-2.0   | 2         | 1.82%   |
| 32.01-64.0 | 1         | 0.91%   |
| 24.01-32.0 | 1         | 0.91%   |
| Unknown    | 1         | 0.91%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 76        | 68.47%  |
| 2      | 26        | 23.42%  |
| 0      | 7         | 6.31%   |
| 3      | 2         | 1.8%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 68        | 62.96%  |
| Yes       | 40        | 37.04%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 96        | 88.89%  |
| No        | 12        | 11.11%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 105       | 97.22%  |
| No        | 3         | 2.78%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 79        | 73.15%  |
| No        | 29        | 26.85%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Brazil  | 108       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Sao Paulo                 | 12        | 10.53%  |
| Curitiba                  | 6         | 5.26%   |
| Rio de Janeiro            | 5         | 4.39%   |
| SГЈo Paulo              | 4         | 3.51%   |
| Manaus                    | 4         | 3.51%   |
| Blumenau                  | 4         | 3.51%   |
| Campinas                  | 3         | 2.63%   |
| Belo Horizonte            | 3         | 2.63%   |
| SÃ£o Paulo              | 2         | 1.75%   |
| Maraba                    | 2         | 1.75%   |
| Maceió                   | 2         | 1.75%   |
| JoГЈo Pessoa            | 2         | 1.75%   |
| Ipojuca                   | 2         | 1.75%   |
| Fortaleza                 | 2         | 1.75%   |
| Vitória                  | 1         | 0.88%   |
| Visconde do Rio Branco    | 1         | 0.88%   |
| Vila Velha                | 1         | 0.88%   |
| Uberaba                   | 1         | 0.88%   |
| Trindade                  | 1         | 0.88%   |
| Teresopolis               | 1         | 0.88%   |
| Teresina                  | 1         | 0.88%   |
| Tangara                   | 1         | 0.88%   |
| SГЈo JosГ© dos Campos | 1         | 0.88%   |
| Sobral                    | 1         | 0.88%   |
| Sete Lagoas               | 1         | 0.88%   |
| Sao Vicente               | 1         | 0.88%   |
| Sao Jeronimo da Serra     | 1         | 0.88%   |
| Sao Bernardo do Campo     | 1         | 0.88%   |
| Santa Maria               | 1         | 0.88%   |
| Rio das Ostras            | 1         | 0.88%   |
| Presidente Prudente       | 1         | 0.88%   |
| Porto UniГЈo            | 1         | 0.88%   |
| Porto Alegre              | 1         | 0.88%   |
| Piloezinhos               | 1         | 0.88%   |
| Pelotas                   | 1         | 0.88%   |
| Patrocinio                | 1         | 0.88%   |
| Paracuru                  | 1         | 0.88%   |
| Palmas                    | 1         | 0.88%   |
| Osasco                    | 1         | 0.88%   |
| Niterói                  | 1         | 0.88%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 21        | 23     | 15.67%  |
| Seagate             | 20        | 23     | 14.93%  |
| Kingston            | 17        | 18     | 12.69%  |
| Toshiba             | 12        | 12     | 8.96%   |
| Samsung Electronics | 10        | 11     | 7.46%   |
| A-DATA Technology   | 9         | 9      | 6.72%   |
| Crucial             | 7         | 11     | 5.22%   |
| SanDisk             | 5         | 5      | 3.73%   |
| NVMe                | 4         | 5      | 2.99%   |
| LITEON              | 4         | 4      | 2.99%   |
| SSSTC               | 3         | 3      | 2.24%   |
| SK hynix            | 3         | 3      | 2.24%   |
| Patriot             | 2         | 5      | 1.49%   |
| KingSpec            | 2         | 3      | 1.49%   |
| Hitachi             | 2         | 2      | 1.49%   |
| China               | 2         | 2      | 1.49%   |
| SMI                 | 1         | 1      | 0.75%   |
| Smart               | 1         | 1      | 0.75%   |
| Silicon Motion      | 1         | 1      | 0.75%   |
| PNY                 | 1         | 1      | 0.75%   |
| Phison              | 1         | 1      | 0.75%   |
| Lexar               | 1         | 1      | 0.75%   |
| Hikvision           | 1         | 1      | 0.75%   |
| Gigabyte Technology | 1         | 1      | 0.75%   |
| Biostar             | 1         | 1      | 0.75%   |
| BHT                 | 1         | 1      | 0.75%   |
| Apple               | 1         | 1      | 0.75%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Toshiba MQ01ABD100 1TB              | 4         | 2.9%    |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 3         | 2.17%   |
| Kingston SA400S37960G 960GB         | 3         | 2.17%   |
| Kingston SA400S37240G 240GB         | 3         | 2.17%   |
| WDC WDS480G2G0B-00EPW0 480GB        | 2         | 1.45%   |
| WDC WDS240G2G0A-00JH30 240GB        | 2         | 1.45%   |
| WDC WD10SPZX-24Z10 1TB              | 2         | 1.45%   |
| SSSTC CL1-4D256 256GB               | 2         | 1.45%   |
| Seagate ST750LM022 HN-M750MBB 752GB | 2         | 1.45%   |
| Seagate ST500LT012-9WS142 500GB     | 2         | 1.45%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 2         | 1.45%   |
| Seagate ST1000LM048-2E7172 1TB      | 2         | 1.45%   |
| Seagate ST1000LM035-1RK172 1TB      | 2         | 1.45%   |
| SanDisk SSD U100 32GB               | 2         | 1.45%   |
| Samsung HM500JJ 500GB               | 2         | 1.45%   |
| Samsung HM321HI 320GB               | 2         | 1.45%   |
| Patriot Burst 120GB                 | 2         | 1.45%   |
| Kingston SA400S37480G 480GB         | 2         | 1.45%   |
| Crucial CT480BX500SSD1 480GB        | 2         | 1.45%   |
| A-DATA SU810NS38 SATA 256 GB        | 2         | 1.45%   |
| WDC WDS120G1G0A-00SS50 120GB        | 1         | 0.72%   |
| WDC WDS100T2G0A-00JH30 1TB          | 1         | 0.72%   |
| WDC WD800BEVS-00RST0 80GB           | 1         | 0.72%   |
| WDC WD6400BEVT-22A0RT0 640GB        | 1         | 0.72%   |
| WDC WD5000LPCX-35VHAT0 500GB        | 1         | 0.72%   |
| WDC WD5000B 500GB                   | 1         | 0.72%   |
| WDC WD20SPZX-22UA7T0 2TB            | 1         | 0.72%   |
| WDC WD1600BPVT-11JJ5T0 160GB        | 1         | 0.72%   |
| WDC WD1600BEVS-60RST0 160GB         | 1         | 0.72%   |
| WDC WD1600BEVS-22VAT0 160GB         | 1         | 0.72%   |
| WDC WD10SPZX-75Z10T1 1TB            | 1         | 0.72%   |
| WDC WD10SPZX-35Z10T0 1TB            | 1         | 0.72%   |
| WDC WD10JPVX-80JC3T0 1TB            | 1         | 0.72%   |
| WDC WD10JPVX-75JC3T0 1TB            | 1         | 0.72%   |
| WDC WD10JPVX-35JC3T0 1TB            | 1         | 0.72%   |
| WDC WD10JPVX-22JC3T0 1TB            | 1         | 0.72%   |
| WDC WD10JPCX-24UE4T0 1TB            | 1         | 0.72%   |
| Toshiba MQ01ABD100V 1TB             | 1         | 0.72%   |
| Toshiba MK6034GSX 64GB              | 1         | 0.72%   |
| Toshiba MK5076GSX 500GB             | 1         | 0.72%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 20        | 23     | 34.48%  |
| WDC                 | 17        | 17     | 29.31%  |
| Toshiba             | 11        | 11     | 18.97%  |
| Samsung Electronics | 5         | 6      | 8.62%   |
| NVMe                | 2         | 3      | 3.45%   |
| Hitachi             | 2         | 2      | 3.45%   |
| SMI                 | 1         | 1      | 1.72%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 16        | 17     | 27.12%  |
| Crucial             | 6         | 10     | 10.17%  |
| WDC                 | 5         | 6      | 8.47%   |
| SanDisk             | 5         | 5      | 8.47%   |
| Samsung Electronics | 4         | 4      | 6.78%   |
| LITEON              | 4         | 4      | 6.78%   |
| SK hynix            | 2         | 2      | 3.39%   |
| Patriot             | 2         | 5      | 3.39%   |
| KingSpec            | 2         | 3      | 3.39%   |
| China               | 2         | 2      | 3.39%   |
| A-DATA Technology   | 2         | 2      | 3.39%   |
| Smart               | 1         | 1      | 1.69%   |
| PNY                 | 1         | 1      | 1.69%   |
| NVMe                | 1         | 1      | 1.69%   |
| Lexar               | 1         | 1      | 1.69%   |
| Hikvision           | 1         | 1      | 1.69%   |
| Gigabyte Technology | 1         | 1      | 1.69%   |
| Biostar             | 1         | 1      | 1.69%   |
| BHT                 | 1         | 1      | 1.69%   |
| Apple               | 1         | 1      | 1.69%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 54        | 69     | 44.26%  |
| HDD  | 50        | 63     | 40.98%  |
| NVMe | 18        | 18     | 14.75%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 90        | 132    | 83.33%  |
| NVMe | 18        | 18     | 16.67%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB      | Notebooks | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 70        | 95     | 67.96%  |
| 0.51-1.0        | 28        | 32     | 27.18%  |
| 1.01-2.0        | 4         | 4      | 3.88%   |
| More than 100.0 | 1         | 1      | 0.97%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 35        | 29.66%  |
| 1-20       | 30        | 25.42%  |
| 251-500    | 19        | 16.1%   |
| 51-100     | 12        | 10.17%  |
| 501-1000   | 11        | 9.32%   |
| 21-50      | 6         | 5.08%   |
| 1001-2000  | 3         | 2.54%   |
| 2001-3000  | 1         | 0.85%   |
| Unknown    | 1         | 0.85%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 92        | 83.64%  |
| 21-50    | 8         | 7.27%   |
| 101-250  | 3         | 2.73%   |
| 501-1000 | 3         | 2.73%   |
| 51-100   | 2         | 1.82%   |
| 251-500  | 1         | 0.91%   |
| Unknown  | 1         | 0.91%   |

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
| Works    | 86        | 115    | 74.78%  |
| Malfunc  | 23        | 28     | 20%     |
| Detected | 5         | 6      | 4.35%   |
| Failed   | 1         | 1      | 0.87%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 97        | 78.23%  |
| ADATA Technology               | 7         | 5.65%   |
| AMD                            | 5         | 4.03%   |
| Solid State Storage Technology | 4         | 3.23%   |
| Toshiba                        | 1         | 0.81%   |
| SK hynix                       | 1         | 0.81%   |
| Silicon Motion                 | 1         | 0.81%   |
| Samsung Electronics            | 1         | 0.81%   |
| Realtek Semiconductor          | 1         | 0.81%   |
| Phison Electronics             | 1         | 0.81%   |
| Nvidia                         | 1         | 0.81%   |
| Micron/Crucial Technology      | 1         | 0.81%   |
| MAXIO Technology (Hangzhou)    | 1         | 0.81%   |
| Kingston Technology Company    | 1         | 0.81%   |
| Biwin Storage Technology       | 1         | 0.81%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 17        | 13.28%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 15        | 11.72%  |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 10        | 7.81%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                           | 9         | 7.03%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 9         | 7.03%   |
| ADATA IM2P33F8 series NVMe SSD (DRAM-less)                                   | 5         | 3.91%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                               | 4         | 3.13%   |
| Intel Comet Lake SATA AHCI Controller                                        | 3         | 2.34%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                            | 3         | 2.34%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                | 3         | 2.34%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                               | 3         | 2.34%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller               | 3         | 2.34%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                            | 3         | 2.34%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                       | 2         | 1.56%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller     | 2         | 1.56%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                            | 2         | 1.56%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]        | 2         | 1.56%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                             | 2         | 1.56%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                | 2         | 1.56%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]              | 2         | 1.56%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]              | 2         | 1.56%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller               | 2         | 1.56%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                         | 2         | 1.56%   |
| Toshiba BG3 x2 NVMe SSD Controller (DRAM-less)                               | 1         | 0.78%   |
| SK hynix BC511 NVMe SSD                                                      | 1         | 0.78%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers            | 1         | 0.78%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                | 1         | 0.78%   |
| Realtek RTS5763DL NVMe SSD Controller (DRAM-less)                            | 1         | 0.78%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                          | 1         | 0.78%   |
| Nvidia MCP79 AHCI Controller                                                 | 1         | 0.78%   |
| Micron/Crucial P1 NVMe PCIe SSD[Frampton]                                    | 1         | 0.78%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                     | 1         | 0.78%   |
| Kingston Company A1000/U-SNS8154P3 x2 NVMe SSD                               | 1         | 0.78%   |
| Intel Tiger Lake-LP SATA Controller                                          | 1         | 0.78%   |
| Intel Tiger Lake SATA AHCI Controller                                        | 1         | 0.78%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                           | 1         | 0.78%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                | 1         | 0.78%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                        | 1         | 0.78%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                       | 1         | 0.78%   |
| Biwin Storage EX900 NVMe SSD (DRAM-less)                                     | 1         | 0.78%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 95        | 76%     |
| NVMe | 20        | 16%     |
| IDE  | 7         | 5.6%    |
| RAID | 3         | 2.4%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 99        | 91.67%  |
| AMD     | 8         | 7.41%   |
| Unknown | 1         | 0.93%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Intel Core i3-4005U CPU @ 1.70GHz  | 5         | 4.63%   |
| Intel Core i5-3320M CPU @ 2.60GHz  | 4         | 3.7%    |
| Intel Core i5-8250U CPU @ 1.60GHz  | 3         | 2.78%   |
| Intel Core i5-5200U CPU @ 2.20GHz  | 3         | 2.78%   |
| Intel Core i5-3337U CPU @ 1.80GHz  | 3         | 2.78%   |
| Intel Core i5-2410M CPU @ 2.30GHz  | 3         | 2.78%   |
| Intel CPU Version                  | 2         | 1.85%   |
| Intel Core i7-8565U CPU @ 1.80GHz  | 2         | 1.85%   |
| Intel Core i7-7500U CPU @ 2.70GHz  | 2         | 1.85%   |
| Intel Core i7-5600U CPU @ 2.60GHz  | 2         | 1.85%   |
| Intel Core i7-10750H CPU @ 2.60GHz | 2         | 1.85%   |
| Intel Core i5-6300U CPU @ 2.40GHz  | 2         | 1.85%   |
| Intel Core i5-4210U CPU @ 1.70GHz  | 2         | 1.85%   |
| Intel Core i5-2520M CPU @ 2.50GHz  | 2         | 1.85%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz | 2         | 1.85%   |
| Intel Core i5-10210U CPU @ 1.60GHz | 2         | 1.85%   |
| Intel Core i3-6100U CPU @ 2.30GHz  | 2         | 1.85%   |
| Intel Core i3-2330M CPU @ 2.20GHz  | 2         | 1.85%   |
| Intel Celeron CPU N3350 @ 1.10GHz  | 2         | 1.85%   |
| Intel Pentium M                    | 1         | 0.93%   |
| Intel Pentium CPU P6200 @ 2.13GHz  | 1         | 0.93%   |
| Intel Pentium CPU 5405U @ 2.30GHz  | 1         | 0.93%   |
| Intel Genuine CPU                  | 1         | 0.93%   |
| Intel Core M-5Y10c CPU @ 0.80GHz   | 1         | 0.93%   |
| Intel Core i7-9750H CPU @ 2.60GHz  | 1         | 0.93%   |
| Intel Core i7-8665U CPU @ 1.90GHz  | 1         | 0.93%   |
| Intel Core i7-8650U CPU @ 1.90GHz  | 1         | 0.93%   |
| Intel Core i7-8550U CPU @ 1.80GHz  | 1         | 0.93%   |
| Intel Core i7-7600U CPU @ 2.80GHz  | 1         | 0.93%   |
| Intel Core i7-6500U CPU @ 2.50GHz  | 1         | 0.93%   |
| Intel Core i7-5500U CPU @ 2.40GHz  | 1         | 0.93%   |
| Intel Core i7-3632QM CPU @ 2.20GHz | 1         | 0.93%   |
| Intel Core i7-2630QM CPU @ 2.00GHz | 1         | 0.93%   |
| Intel Core i7-10510U CPU @ 1.80GHz | 1         | 0.93%   |
| Intel Core i5-9300H CPU @ 2.40GHz  | 1         | 0.93%   |
| Intel Core i5-8350U CPU @ 1.70GHz  | 1         | 0.93%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz | 1         | 0.93%   |
| Intel Core i5-7200U CPU @ 2.50GHz  | 1         | 0.93%   |
| Intel Core i5-6200U CPU @ 2.30GHz  | 1         | 0.93%   |
| Intel Core i5-5300U CPU @ 2.30GHz  | 1         | 0.93%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 42        | 38.89%  |
| Intel Core i7    | 18        | 16.67%  |
| Intel Core i3    | 16        | 14.81%  |
| Intel Celeron    | 8         | 7.41%   |
| Other            | 5         | 4.63%   |
| Intel Core 2 Duo | 4         | 3.7%    |
| Intel Pentium    | 2         | 1.85%   |
| Intel Atom       | 2         | 1.85%   |
| AMD Ryzen 7      | 2         | 1.85%   |
| AMD E1           | 2         | 1.85%   |
| Intel Pentium M  | 1         | 0.93%   |
| Intel Genuine    | 1         | 0.93%   |
| Intel Core M     | 1         | 0.93%   |
| AMD Ryzen 5      | 1         | 0.93%   |
| AMD E            | 1         | 0.93%   |
| AMD C-60         | 1         | 0.93%   |
| AMD C-50         | 1         | 0.93%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 75        | 69.44%  |
| 4       | 19        | 17.59%  |
| Unknown | 6         | 5.56%   |
| 6       | 4         | 3.7%    |
| 8       | 2         | 1.85%   |
| 16      | 1         | 0.93%   |
| 1       | 1         | 0.93%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 104       | 96.3%   |
| 2       | 2         | 1.85%   |
| Unknown | 2         | 1.85%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 80        | 74.07%  |
| 1       | 22        | 20.37%  |
| Unknown | 6         | 5.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 21        | 19.44%  |
| SandyBridge   | 14        | 12.96%  |
| IvyBridge     | 14        | 12.96%  |
| Haswell       | 9         | 8.33%   |
| Broadwell     | 9         | 8.33%   |
| Skylake       | 7         | 6.48%   |
| Westmere      | 5         | 4.63%   |
| Bobcat        | 5         | 4.63%   |
| Penryn        | 4         | 3.7%    |
| Core          | 3         | 2.78%   |
| Unknown       | 3         | 2.78%   |
| Zen+          | 2         | 1.85%   |
| IceLake       | 2         | 1.85%   |
| Goldmont plus | 2         | 1.85%   |
| Goldmont      | 2         | 1.85%   |
| CometLake     | 2         | 1.85%   |
| Bonnell       | 2         | 1.85%   |
| TigerLake     | 1         | 0.93%   |
| Silvermont    | 1         | 0.93%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 96        | 75.59%  |
| Nvidia | 20        | 15.75%  |
| AMD    | 11        | 8.66%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                              | 14        | 10.69%  |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 13        | 9.92%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 9         | 6.87%   |
| Intel HD Graphics 5500                                                        | 8         | 6.11%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 7         | 5.34%   |
| Intel UHD Graphics 620                                                        | 6         | 4.58%   |
| Intel Core Processor Integrated Graphics Controller                           | 5         | 3.82%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 4         | 3.05%   |
| Intel HD Graphics 620                                                         | 4         | 3.05%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 3         | 2.29%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 3         | 2.29%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 3         | 2.29%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 3         | 2.29%   |
| Nvidia GP108M [GeForce MX250]                                                 | 2         | 1.53%   |
| Nvidia GM108M [GeForce MX130]                                                 | 2         | 1.53%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                  | 2         | 1.53%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                        | 2         | 1.53%   |
| Intel HD Graphics 500                                                         | 2         | 1.53%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 2         | 1.53%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 2         | 1.53%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 2         | 1.53%   |
| AMD Wrestler [Radeon HD 7310]                                                 | 2         | 1.53%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 2         | 1.53%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                    | 1         | 0.76%   |
| Nvidia GP108M [GeForce MX230]                                                 | 1         | 0.76%   |
| Nvidia GM108M [GeForce MX110]                                                 | 1         | 0.76%   |
| Nvidia GM108M [GeForce 940MX]                                                 | 1         | 0.76%   |
| Nvidia GM108M [GeForce 930M]                                                  | 1         | 0.76%   |
| Nvidia GM107M [GeForce GTX 950M]                                              | 1         | 0.76%   |
| Nvidia GK208M [GeForce GT 740M]                                               | 1         | 0.76%   |
| Nvidia GK208M [GeForce GT 735M]                                               | 1         | 0.76%   |
| Nvidia GK208BM [GeForce 920M]                                                 | 1         | 0.76%   |
| Nvidia GF119M [GeForce 410M]                                                  | 1         | 0.76%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]          | 1         | 0.76%   |
| Nvidia C79 [GeForce 9400M]                                                    | 1         | 0.76%   |
| Intel Whiskey Lake-U GT1 [UHD Graphics 610]                                   | 1         | 0.76%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 1         | 0.76%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                          | 1         | 0.76%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                    | 1         | 0.76%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller | 1         | 0.76%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 69        | 63.89%  |
| Intel + Nvidia | 18        | 16.67%  |
| 1 x AMD        | 9         | 8.33%   |
| 2 x Intel      | 7         | 6.48%   |
| 1 x Nvidia     | 2         | 1.85%   |
| Intel + AMD    | 2         | 1.85%   |
| Other          | 1         | 0.93%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 102       | 94.44%  |
| Proprietary | 3         | 2.78%   |
| Unknown     | 3         | 2.78%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 101       | 92.66%  |
| 0.01-0.5   | 5         | 4.59%   |
| 3.01-4.0   | 2         | 1.83%   |
| 1.01-2.0   | 1         | 0.92%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 28        | 31.46%  |
| LG Display              | 15        | 16.85%  |
| Chimei Innolux          | 10        | 11.24%  |
| BOE                     | 10        | 11.24%  |
| Samsung Electronics     | 5         | 5.62%   |
| Lenovo                  | 3         | 3.37%   |
| InfoVision              | 3         | 3.37%   |
| Dell                    | 3         | 3.37%   |
| AOC                     | 3         | 3.37%   |
| Goldstar                | 2         | 2.25%   |
| Apple                   | 2         | 2.25%   |
| Philips                 | 1         | 1.12%   |
| PANDA                   | 1         | 1.12%   |
| JDI                     | 1         | 1.12%   |
| Hewlett-Packard         | 1         | 1.12%   |
| Chi Mei Optoelectronics | 1         | 1.12%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD0385 1366x768 310x170mm 13.9-inch           | 4         | 4.49%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 340x190mm 15.3-inch         | 4         | 4.49%   |
| LG Display LCD Monitor LGD0458 1366x768 310x170mm 13.9-inch           | 2         | 2.25%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch          | 2         | 2.25%   |
| BOE LCD Monitor BOE0757 1366x768 340x190mm 15.3-inch                  | 2         | 2.25%   |
| BOE LCD Monitor BOE05EF 1366x768 310x170mm 13.9-inch                  | 2         | 2.25%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch         | 2         | 2.25%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 340x190mm 15.3-inch         | 2         | 2.25%   |
| AU Optronics LCD Monitor AUO303C 1366x768 310x170mm 13.9-inch         | 2         | 2.25%   |
| AU Optronics LCD Monitor AUO263D 1920x1080 310x170mm 13.9-inch        | 2         | 2.25%   |
| AU Optronics LCD Monitor AUO183C 1366x768 310x170mm 13.9-inch         | 2         | 2.25%   |
| AOC T2242we AOC2242 1920x1080 480x270mm 21.7-inch                     | 2         | 2.25%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 340x190mm 15.3-inch  | 1         | 1.12%   |
| Samsung Electronics LCD Monitor SEC414C 1366x768 310x170mm 13.9-inch  | 1         | 1.12%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 340x190mm 15.3-inch  | 1         | 1.12%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 340x190mm 15.3-inch | 1         | 1.12%   |
| Samsung Electronics LCD Monitor SAM0D4F 1920x1080 890x500mm 40.2-inch | 1         | 1.12%   |
| Philips PHL 193V5 PHLC0CD 1366x768 410x230mm 18.5-inch                | 1         | 1.12%   |
| PANDA LCD Monitor NCP0004 1920x1080 290x170mm 13.2-inch               | 1         | 1.12%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 340x190mm 15.3-inch         | 1         | 1.12%   |
| LG Display LCD Monitor LGD05B1 1920x1080 310x170mm 13.9-inch          | 1         | 1.12%   |
| LG Display LCD Monitor LGD053C 1920x1080 310x170mm 13.9-inch          | 1         | 1.12%   |
| LG Display LCD Monitor LGD0505 1366x768 340x190mm 15.3-inch           | 1         | 1.12%   |
| LG Display LCD Monitor LGD03ED 1366x768 280x160mm 12.7-inch           | 1         | 1.12%   |
| LG Display LCD Monitor LGD03B7 1366x768 310x170mm 13.9-inch           | 1         | 1.12%   |
| LG Display LCD Monitor LGD02D3 1366x768 280x160mm 12.7-inch           | 1         | 1.12%   |
| Lenovo LEN X24A LEN60CF 1920x1080 530x300mm 24.0-inch                 | 1         | 1.12%   |
| Lenovo LCD Monitor LEN4035 1280x800 300x190mm 14.0-inch               | 1         | 1.12%   |
| Lenovo LCD Monitor LEN4031 1280x800 300x190mm 14.0-inch               | 1         | 1.12%   |
| JDI GPD1001H JDI0031 2560x1600 890x500mm 40.2-inch                    | 1         | 1.12%   |
| InfoVision LCD Monitor IVO057D 1920x1080 310x170mm 13.9-inch          | 1         | 1.12%   |
| InfoVision LCD Monitor IVO0579 1366x768 310x170mm 13.9-inch           | 1         | 1.12%   |
| InfoVision LCD Monitor IVO03F4 1024x600 220x130mm 10.1-inch           | 1         | 1.12%   |
| Hewlett-Packard L200hx HWP298F 1600x900 450x250mm 20.3-inch           | 1         | 1.12%   |
| Goldstar LG FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch             | 1         | 1.12%   |
| Goldstar LCD Monitor GSM580D 1920x1080 510x290mm 23.1-inch            | 1         | 1.12%   |
| Dell S2419HGF DELD0E1 1920x1080 530x300mm 24.0-inch                   | 1         | 1.12%   |
| Dell P2419H DELD0D9 1920x1080 530x300mm 24.0-inch                     | 1         | 1.12%   |
| Dell P2418D DELD0C1 2560x1440 530x300mm 24.0-inch                     | 1         | 1.12%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 340x190mm 15.3-inch      | 1         | 1.12%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1366x768 (WXGA)  | 51        | 60%     |
| 1920x1080 (FHD)  | 24        | 28.24%  |
| 1280x800 (WXGA)  | 3         | 3.53%   |
| 1600x900 (HD+)   | 2         | 2.35%   |
| 1440x900 (WXGA+) | 2         | 2.35%   |
| 2560x1600        | 1         | 1.18%   |
| 2560x1440 (QHD)  | 1         | 1.18%   |
| 1024x600         | 1         | 1.18%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 13     | 37        | 41.57%  |
| 15     | 28        | 31.46%  |
| 12     | 5         | 5.62%   |
| 24     | 4         | 4.49%   |
| 14     | 4         | 4.49%   |
| 21     | 3         | 3.37%   |
| 18     | 2         | 2.25%   |
| 46     | 1         | 1.12%   |
| 40     | 1         | 1.12%   |
| 23     | 1         | 1.12%   |
| 20     | 1         | 1.12%   |
| 11     | 1         | 1.12%   |
| 10     | 1         | 1.12%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 63        | 70.79%  |
| 201-300     | 13        | 14.61%  |
| 401-500     | 6         | 6.74%   |
| 501-600     | 5         | 5.62%   |
| 801-900     | 1         | 1.12%   |
| 1001-1500   | 1         | 1.12%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 73        | 92.41%  |
| 16/10 | 6         | 7.59%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 40        | 44.94%  |
| 91-100         | 27        | 30.34%  |
| 201-250        | 8         | 8.99%   |
| 61-70          | 5         | 5.62%   |
| 141-150        | 2         | 2.25%   |
| 501-1000       | 2         | 2.25%   |
| 71-80          | 1         | 1.12%   |
| 51-60          | 1         | 1.12%   |
| 41-50          | 1         | 1.12%   |
| 151-200        | 1         | 1.12%   |
| 101-110        | 1         | 1.12%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 51        | 58.62%  |
| 121-160 | 23        | 26.44%  |
| 51-100  | 9         | 10.34%  |
| 161-240 | 3         | 3.45%   |
| 1-50    | 1         | 1.15%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 82        | 74.55%  |
| 2     | 14        | 12.73%  |
| 0     | 14        | 12.73%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 59        | 33.33%  |
| Qualcomm Atheros         | 48        | 27.12%  |
| Intel                    | 41        | 23.16%  |
| Broadcom                 | 13        | 7.34%   |
| JMicron Technology       | 5         | 2.82%   |
| Samsung Electronics      | 4         | 2.26%   |
| Ralink Technology        | 2         | 1.13%   |
| Xiaomi                   | 1         | 0.56%   |
| TP-Link                  | 1         | 0.56%   |
| Nvidia                   | 1         | 0.56%   |
| MediaTek                 | 1         | 0.56%   |
| Marvell Technology Group | 1         | 0.56%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 26        | 12.32%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 26        | 12.32%  |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 16        | 7.58%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 13        | 6.16%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 6         | 2.84%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 6         | 2.84%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 6         | 2.84%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                             | 5         | 2.37%   |
| Intel Wireless 8265 / 8275                                             | 5         | 2.37%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 5         | 2.37%   |
| Intel Wireless 7265                                                    | 4         | 1.9%    |
| Samsung Galaxy series, misc. (tethering mode)                          | 3         | 1.42%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 3         | 1.42%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)         | 3         | 1.42%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 3         | 1.42%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 3         | 1.42%   |
| Intel Ethernet Connection (4) I219-LM                                  | 3         | 1.42%   |
| Intel Ethernet Connection (3) I218-LM                                  | 3         | 1.42%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 3         | 1.42%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 2         | 0.95%   |
| Realtek RTL8188EE Wireless Network Adapter                             | 2         | 0.95%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 2         | 0.95%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                    | 2         | 0.95%   |
| Intel Wireless 8260                                                    | 2         | 0.95%   |
| Intel Wi-Fi 6 AX200                                                    | 2         | 0.95%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                  | 2         | 0.95%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                        | 2         | 0.95%   |
| Intel Gemini Lake PCH CNVi WiFi                                        | 2         | 0.95%   |
| Intel Ethernet Connection I219-LM                                      | 2         | 0.95%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 2         | 0.95%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 2         | 0.95%   |
| Intel Centrino Advanced-N 6200                                         | 2         | 0.95%   |
| Intel 82577LM Gigabit Network Connection                               | 2         | 0.95%   |
| Intel 82566MM Gigabit Network Connection                               | 2         | 0.95%   |
| Broadcom BCM43224 802.11a/b/g/n                                        | 2         | 0.95%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 0.47%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]             | 1         | 0.47%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 1         | 0.47%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 1         | 0.47%   |
| Realtek RTL8191SEvA Wireless LAN Controller                            | 1         | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Qualcomm Atheros      | 47        | 42.73%  |
| Intel                 | 40        | 36.36%  |
| Realtek Semiconductor | 13        | 11.82%  |
| Broadcom              | 7         | 6.36%   |
| Ralink Technology     | 2         | 1.82%   |
| TP-Link               | 1         | 0.91%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 16        | 14.41%  |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 13        | 11.71%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 6         | 5.41%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 6         | 5.41%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 5         | 4.5%    |
| Intel Wireless 8265 / 8275                                     | 5         | 4.5%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 5         | 4.5%    |
| Intel Wireless 7265                                            | 4         | 3.6%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 3         | 2.7%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 3         | 2.7%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2         | 1.8%    |
| Realtek RTL8188EE Wireless Network Adapter                     | 2         | 1.8%    |
| Intel Wireless 8260                                            | 2         | 1.8%    |
| Intel Wi-Fi 6 AX200                                            | 2         | 1.8%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 2         | 1.8%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 2         | 1.8%    |
| Intel Gemini Lake PCH CNVi WiFi                                | 2         | 1.8%    |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 2         | 1.8%    |
| Intel Comet Lake PCH CNVi WiFi                                 | 2         | 1.8%    |
| Intel Centrino Advanced-N 6200                                 | 2         | 1.8%    |
| Broadcom BCM43224 802.11a/b/g/n                                | 2         | 1.8%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1         | 0.9%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 0.9%    |
| Realtek RTL8191SEvA Wireless LAN Controller                    | 1         | 0.9%    |
| Realtek RTL8188SU 802.11n WLAN Adapter                         | 1         | 0.9%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 0.9%    |
| Realtek 8811CU Wireless LAN 802.11ac USB NIC                   | 1         | 0.9%    |
| Ralink RT2870/RT3070 Wireless Adapter                          | 1         | 0.9%    |
| Ralink RT2501/RT2573 Wireless Adapter                          | 1         | 0.9%    |
| Intel Wireless 7260                                            | 1         | 0.9%    |
| Intel Wireless 3165                                            | 1         | 0.9%    |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 1         | 0.9%    |
| Intel Wi-Fi 6 AX201                                            | 1         | 0.9%    |
| Intel Tiger Lake PCH CNVi WiFi                                 | 1         | 0.9%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 1         | 0.9%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 1         | 0.9%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 1         | 0.9%    |
| Intel Centrino Wireless-N 2230                                 | 1         | 0.9%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 1         | 0.9%    |
| Broadcom BCM4378 802.11ax Dual Band Wireless Network Adapter   | 1         | 0.9%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 53        | 53.54%  |
| Intel                    | 20        | 20.2%   |
| Broadcom                 | 7         | 7.07%   |
| Qualcomm Atheros         | 6         | 6.06%   |
| JMicron Technology       | 5         | 5.05%   |
| Samsung Electronics      | 4         | 4.04%   |
| Xiaomi                   | 1         | 1.01%   |
| Nvidia                   | 1         | 1.01%   |
| MediaTek                 | 1         | 1.01%   |
| Marvell Technology Group | 1         | 1.01%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 26        | 26.26%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 26        | 26.26%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 6         | 6.06%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 3         | 3.03%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 3         | 3.03%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 3         | 3.03%   |
| Intel Ethernet Connection (4) I219-LM                                  | 3         | 3.03%   |
| Intel Ethernet Connection (3) I218-LM                                  | 3         | 3.03%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 3         | 3.03%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 2         | 2.02%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                    | 2         | 2.02%   |
| Intel Ethernet Connection I219-LM                                      | 2         | 2.02%   |
| Intel 82577LM Gigabit Network Connection                               | 2         | 2.02%   |
| Intel 82566MM Gigabit Network Connection                               | 2         | 2.02%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 1.01%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 1         | 1.01%   |
| Realtek Killer E2600 GbE Controller                                    | 1         | 1.01%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 1         | 1.01%   |
| Nvidia MCP79 Ethernet                                                  | 1         | 1.01%   |
| MediaTek USB Ethernet-RNDIS                                            | 1         | 1.01%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 1         | 1.01%   |
| Intel Ethernet Connection I218-LM                                      | 1         | 1.01%   |
| Intel Ethernet Connection (6) I219-LM                                  | 1         | 1.01%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 1         | 1.01%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                    | 1         | 1.01%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 1         | 1.01%   |
| Broadcom BCM4401-B0 100Base-TX                                         | 1         | 1.01%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 105       | 51.98%  |
| Ethernet | 96        | 47.52%  |
| Unknown  | 1         | 0.5%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 75        | 53.19%  |
| Ethernet | 66        | 46.81%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 91        | 84.26%  |
| 1     | 17        | 15.74%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 100       | 92.59%  |
| Yes  | 8         | 7.41%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Qualcomm Atheros Communications | 27        | 34.18%  |
| Intel                           | 27        | 34.18%  |
| Broadcom                        | 6         | 7.59%   |
| Lite-On Technology              | 5         | 6.33%   |
| Apple                           | 5         | 6.33%   |
| Foxconn / Hon Hai               | 4         | 5.06%   |
| Realtek Semiconductor           | 3         | 3.8%    |
| IMC Networks                    | 1         | 1.27%   |
| Dell                            | 1         | 1.27%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 11        | 13.92%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 8         | 10.13%  |
| Qualcomm Atheros AR9462 Bluetooth                           | 6         | 7.59%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 6         | 7.59%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 5         | 6.33%   |
| Qualcomm Atheros Dell Wireless 1703 Bluetooth               | 4         | 5.06%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 3         | 3.8%    |
| Qualcomm Atheros AR3011 Bluetooth                           | 3         | 3.8%    |
| Intel AX201 Bluetooth                                       | 3         | 3.8%    |
| Apple Bluetooth Host Controller                             | 3         | 3.8%    |
| Realtek Bluetooth Adapter                                   | 2         | 2.53%   |
| Lite-On Qualcomm Atheros Bluetooth                          | 2         | 2.53%   |
| Intel AX200 Bluetooth                                       | 2         | 2.53%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3011 Bluetooth Adapter | 2         | 2.53%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 2         | 2.53%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 2         | 2.53%   |
| Realtek CSR Bluetooth Chip                                  | 1         | 1.27%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 1         | 1.27%   |
| Lite-On Atheros Bluetooth                                   | 1         | 1.27%   |
| Lite-On Atheros AR3012 Bluetooth                            | 1         | 1.27%   |
| Intel Wireless-AC 3168 Bluetooth                            | 1         | 1.27%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 1         | 1.27%   |
| Intel AX210 Bluetooth                                       | 1         | 1.27%   |
| IMC Networks Bluetooth Module                               | 1         | 1.27%   |
| Foxconn / Hon Hai Qualcomm Atheros Bluetooth 4.0            | 1         | 1.27%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device             | 1         | 1.27%   |
| Dell Wireless 355 Bluetooth                                 | 1         | 1.27%   |
| Broadcom BCM2046 Bluetooth Device                           | 1         | 1.27%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 1         | 1.27%   |
| Apple Built-in iSight (no firmware loaded)                  | 1         | 1.27%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 1         | 1.27%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor            | Notebooks | Percent |
|-------------------|-----------|---------|
| Intel             | 97        | 82.91%  |
| AMD               | 8         | 6.84%   |
| Nvidia            | 7         | 5.98%   |
| Texas Instruments | 1         | 0.85%   |
| Plantronics       | 1         | 0.85%   |
| M-Audio           | 1         | 0.85%   |
| Logitech          | 1         | 0.85%   |
| Lenovo            | 1         | 0.85%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 18        | 12.77%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 17        | 12.06%  |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 10        | 7.09%   |
| Intel Haswell-ULT HD Audio Controller                                      | 9         | 6.38%   |
| Intel Broadwell-U Audio Controller                                         | 9         | 6.38%   |
| Intel 8 Series HD Audio Controller                                         | 9         | 6.38%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 8         | 5.67%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 5         | 3.55%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 4         | 2.84%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 4         | 2.84%   |
| AMD Wrestler HDMI Audio                                                    | 4         | 2.84%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3         | 2.13%   |
| Intel Comet Lake PCH-LP cAVS                                               | 3         | 2.13%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 3         | 2.13%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 3         | 2.13%   |
| AMD Family 17h/19h HD Audio Controller                                     | 3         | 2.13%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 1.42%   |
| Intel Comet Lake PCH cAVS                                                  | 2         | 1.42%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 1.42%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 2         | 1.42%   |
| Intel Cannon Lake PCH cAVS                                                 | 2         | 1.42%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 1.42%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 1.42%   |
| AMD FCH Azalia Controller                                                  | 2         | 1.42%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1         | 0.71%   |
| Plantronics Plantronics Blackwire 3210 Series                              | 1         | 0.71%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 0.71%   |
| Nvidia MCP79 High Definition Audio                                         | 1         | 0.71%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 0.71%   |
| M-Audio M-Audio Fast Track Pro                                             | 1         | 0.71%   |
| Logitech H390 headset with microphone                                      | 1         | 0.71%   |
| Lenovo Realtek USB Audio                                                   | 1         | 0.71%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 1         | 0.71%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1         | 0.71%   |
| Intel CM238 HD Audio Controller                                            | 1         | 0.71%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 0.71%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 1         | 0.71%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Smart               | 31        | 25.41%  |
| Samsung Electronics | 14        | 11.48%  |
| Kingston            | 14        | 11.48%  |
| SK hynix            | 11        | 9.02%   |
| Unknown             | 9         | 7.38%   |
| Teikon              | 8         | 6.56%   |
| A-DATA Technology   | 8         | 6.56%   |
| Smart Brazil        | 5         | 4.1%    |
| High Bridge         | 5         | 4.1%    |
| Crucial             | 4         | 3.28%   |
| Micron Technology   | 3         | 2.46%   |
| Multilaser          | 2         | 1.64%   |
| Apacer              | 2         | 1.64%   |
| Unknown (ABCD)      | 1         | 0.82%   |
| Smart Modular       | 1         | 0.82%   |
| PNY                 | 1         | 0.82%   |
| Nanya Technology    | 1         | 0.82%   |
| Lenovo              | 1         | 0.82%   |
| Kllisre             | 1         | 0.82%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 6         | 4.58%   |
| Smart RAM SH564568FH8NZPHSCR 2GB SODIMM DDR3 1334MT/s            | 4         | 3.05%   |
| Smart RAM SH564128FJ8NZRNSDG 4GB SODIMM DDR3 1600MT/s            | 4         | 3.05%   |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s            | 4         | 3.05%   |
| Smart RAM SH564128FH8NZQNSCG 4GB SODIMM DDR3 1600MT/s            | 3         | 2.29%   |
| Smart RAM SH564128FH8NZPHSCR 4GB SODIMM DDR3 1333MT/s            | 3         | 2.29%   |
| Smart RAM SF4641G8CK8IEHLSBG 8GB SODIMM DDR4 2667MT/s            | 3         | 2.29%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 2         | 1.53%   |
| Teikon RAM TML251S6EFR8A-PBHC 4GB SODIMM DDR3 1600MT/s           | 2         | 1.53%   |
| Smart RAM SH564128FH8NZPHSCG 4GB SODIMM DDR3 1333MT/s            | 2         | 1.53%   |
| Smart RAM SF564128CJ8NWMNSEG 4GB SODIMM DDR3 1600MT/s            | 2         | 1.53%   |
| Smart Brazil RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2400MT/s     | 2         | 1.53%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.53%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 2         | 1.53%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s            | 2         | 1.53%   |
| Multilaser RAM MS3512NSZ-CA3G1 4GB SODIMM DDR3 1600MT/s          | 2         | 1.53%   |
| High Bridge RAM HB3SU002GFM8MMB33. 2GB SODIMM DDR3 1334MT/s      | 2         | 1.53%   |
| Unknown SODIMM 2048MB SODIMM DDR2 667MT/s                        | 1         | 0.76%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 0.76%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                      | 1         | 0.76%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 1         | 0.76%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 0.76%   |
| Unknown RAM Module 4GB SODIMM DDR2 800MT/s                       | 1         | 0.76%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 1         | 0.76%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 0.76%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 0.76%   |
| Teikon RAM TMT451S6BFR8A-PBSC 4096MB SODIMM DDR3 1600MT/s        | 1         | 0.76%   |
| Teikon RAM TMT451S6BFR8A-PBHC 4GB SODIMM DDR3 1333MT/s           | 1         | 0.76%   |
| Teikon RAM TMT425S6CFR6A-PBNJ 2GB SODIMM DDR3 1600MT/s           | 1         | 0.76%   |
| Teikon RAM TMT41GS6BFR8A-PBSC 8GB SODIMM DDR3 1600MT/s           | 1         | 0.76%   |
| Teikon RAM TMT225S6FR8C-H9HC 2GB SODIMM DDR3 1334MT/s            | 1         | 0.76%   |
| Teikon RAM TMA81GS6AFR8N-UHSC 8GB SODIMM DDR4 2400MT/s           | 1         | 0.76%   |
| Smart RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2133MT/s            | 1         | 0.76%   |
| Smart RAM SH564568FH8NWPHSFR 2GB SODIMM DDR3 1333MT/s            | 1         | 0.76%   |
| Smart RAM SH564128FJ8NZRNSDR 4GB SODIMM DDR3 1600MT/s            | 1         | 0.76%   |
| Smart RAM SF4641G8CK8IWGKSEG 8GB SODIMM DDR4 2133MT/s            | 1         | 0.76%   |
| Smart RAM SF464128CKHIWDFSEG 4GB SODIMM DDR4 2133MT/s            | 1         | 0.76%   |
| Smart Modular RAM SMS4WEC8C1K0446FCG 8GB SODIMM DDR4 3200MT/s    | 1         | 0.76%   |
| Smart Brazil RAM SMS4WEC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s     | 1         | 0.76%   |
| Smart Brazil RAM SF4641G8CK8IEHLSBG 8GB SODIMM DDR4 2133MT/s     | 1         | 0.76%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 61        | 63.54%  |
| DDR4   | 26        | 27.08%  |
| DDR2   | 7         | 7.29%   |
| LPDDR4 | 1         | 1.04%   |
| DDR    | 1         | 1.04%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 94        | 96.91%  |
| Row Of Chips | 3         | 3.09%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 52        | 46.43%  |
| 8192  | 25        | 22.32%  |
| 2048  | 24        | 21.43%  |
| 16384 | 9         | 8.04%   |
| 1024  | 2         | 1.79%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 40        | 36.7%   |
| 1333    | 17        | 15.6%   |
| 2667    | 11        | 10.09%  |
| 2400    | 11        | 10.09%  |
| 1334    | 10        | 9.17%   |
| 2133    | 4         | 3.67%   |
| 667     | 4         | 3.67%   |
| 3200    | 3         | 2.75%   |
| 533     | 3         | 2.75%   |
| 800     | 2         | 1.83%   |
| 1867    | 1         | 0.92%   |
| 1067    | 1         | 0.92%   |
| 975     | 1         | 0.92%   |
| Unknown | 1         | 0.92%   |

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
| Chicony Electronics           | 22        | 24.44%  |
| Bison Electronics             | 14        | 15.56%  |
| Microdia                      | 11        | 12.22%  |
| Realtek Semiconductor         | 10        | 11.11%  |
| Silicon Motion                | 7         | 7.78%   |
| Suyin                         | 3         | 3.33%   |
| Sunplus Innovation Technology | 3         | 3.33%   |
| IMC Networks                  | 3         | 3.33%   |
| Unknown                       | 2         | 2.22%   |
| Syntek                        | 2         | 2.22%   |
| Luxvisions Innotech Limited   | 2         | 2.22%   |
| Logitech                      | 2         | 2.22%   |
| Lenovo                        | 2         | 2.22%   |
| Apple                         | 2         | 2.22%   |
| Alcor Micro                   | 2         | 2.22%   |
| Tripath Technology            | 1         | 1.11%   |
| Quanta                        | 1         | 1.11%   |
| Lite-On Technology            | 1         | 1.11%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony HD WebCam                             | 6         | 6.59%   |
| Bison Integrated Camera                       | 5         | 5.49%   |
| Silicon Motion Realtek DMFT RGB               | 4         | 4.4%    |
| Microdia Integrated_Webcam_HD                 | 4         | 4.4%    |
| Microdia Dell Laptop Integrated Webcam HD     | 4         | 4.4%    |
| Realtek Dell EasyCamera                       | 3         | 3.3%    |
| Chicony Sony Visual Communication Camera      | 3         | 3.3%    |
| Bison Lenovo EasyCamera                       | 3         | 3.3%    |
| Unknown Realtek PC Camera                     | 2         | 2.2%    |
| Syntek EasyCamera                             | 2         | 2.2%    |
| Sunplus Integrated_Webcam_HD                  | 2         | 2.2%    |
| Realtek Integrated Webcam                     | 2         | 2.2%    |
| Luxvisions Innotech Limited Integrated Camera | 2         | 2.2%    |
| Chicony Lenovo Integrated Camera (0.3MP)      | 2         | 2.2%    |
| Chicony Integrated Camera                     | 2         | 2.2%    |
| Bison HD Webcam                               | 2         | 2.2%    |
| Alcor Micro Acer Integrated Webcam            | 2         | 2.2%    |
| Tripath USB Camera                            | 1         | 1.1%    |
| Suyin WebCam                                  | 1         | 1.1%    |
| Suyin USB 2.0 UVC 1.3M WebCam                 | 1         | 1.1%    |
| Suyin Integrated_Webcam_HD                    | 1         | 1.1%    |
| Sunplus HD WebCam                             | 1         | 1.1%    |
| Silicon Motion WebCam SCX Series              | 1         | 1.1%    |
| Silicon Motion Realtek USB 2.0 PC Camera      | 1         | 1.1%    |
| Silicon Motion ATIV VGA Camera                | 1         | 1.1%    |
| Realtek LG Camera                             | 1         | 1.1%    |
| Realtek Integrated_Webcam_FHD                 | 1         | 1.1%    |
| Realtek Integrated_Webcam_8M                  | 1         | 1.1%    |
| Realtek Integrated Webcam HD                  | 1         | 1.1%    |
| Realtek Composite Webcam                      | 1         | 1.1%    |
| Realtek Acer 640 x 480 laptop camera          | 1         | 1.1%    |
| Quanta HD Webcam                              | 1         | 1.1%    |
| Microdia Laptop_Integrated_Webcam_HD          | 1         | 1.1%    |
| Microdia Laptop_Integrated_Webcam_1.3M        | 1         | 1.1%    |
| Microdia Integrated Webcam HD                 | 1         | 1.1%    |
| Logitech Webcam C270                          | 1         | 1.1%    |
| Logitech C922 Pro Stream Webcam               | 1         | 1.1%    |
| Lite-On Integrated Camera                     | 1         | 1.1%    |
| Lenovo Integrated Webcam [R5U877]             | 1         | 1.1%    |
| Lenovo Integrated Webcam                      | 1         | 1.1%    |

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
| 2     | 34        | 31.19%  |
| 1     | 34        | 31.19%  |
| 3     | 16        | 14.68%  |
| 0     | 12        | 11.01%  |
| 4     | 8         | 7.34%   |
| 5     | 5         | 4.59%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 87        | 45.55%  |
| Card reader              | 37        | 19.37%  |
| Bluetooth                | 25        | 13.09%  |
| Net/wireless             | 20        | 10.47%  |
| Fingerprint reader       | 15        | 7.85%   |
| Sound                    | 2         | 1.05%   |
| Network                  | 2         | 1.05%   |
| Storage                  | 1         | 0.52%   |
| Net/ethernet             | 1         | 0.52%   |
| Graphics card            | 1         | 0.52%   |

