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

Total: 147

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Lenovo        | B40-30 80F1                 | [98be66c2e6](https://bsd-hardware.info/?probe=98be66c2e6) | May 03, 2024 |
| Lenovo        | ThinkPad E490 20N9S48S00    | [f70fb4bd81](https://bsd-hardware.info/?probe=f70fb4bd81) | May 01, 2024 |
| Acer          | Aspire 5551                 | [ee15a7d2b5](https://bsd-hardware.info/?probe=ee15a7d2b5) | Apr 29, 2024 |
| Lenovo        | ThinkPad E490 20N9S48S00    | [a755c9e288](https://bsd-hardware.info/?probe=a755c9e288) | Apr 13, 2024 |
| Dell          | Inspiron 15 3511            | [7ac9f4bd85](https://bsd-hardware.info/?probe=7ac9f4bd85) | Mar 14, 2024 |
| Lenovo        | IdeaPad 3 15ITL6 82MD       | [e97bd00aad](https://bsd-hardware.info/?probe=e97bd00aad) | Mar 13, 2024 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [fd60868096](https://bsd-hardware.info/?probe=fd60868096) | Mar 10, 2024 |
| Itautec       | Infoway                     | [35399f6e75](https://bsd-hardware.info/?probe=35399f6e75) | Feb 28, 2024 |
| Lenovo        | B40-30 80F1                 | [9e435212e2](https://bsd-hardware.info/?probe=9e435212e2) | Feb 27, 2024 |
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
| helloSystem 0.8.1    | 15        | 12.1%   |
| helloSystem 0.7.0    | 12        | 9.68%   |
| helloSystem 0.6.0    | 10        | 8.06%   |
| helloSystem 0.4.0    | 10        | 8.06%   |
| helloSystem 0.5.0    | 9         | 7.26%   |
| helloSystem 0.8.0    | 8         | 6.45%   |
| helloSystem 0.9.0    | 7         | 5.65%   |
| FreeBSD 13.0         | 6         | 4.84%   |
| OpenBSD 7.3          | 5         | 4.03%   |
| FreeBSD 14.0-CURRENT | 3         | 2.42%   |
| FreeBSD 13.0-p3      | 3         | 2.42%   |
| FreeBSD 15.0-CURRENT | 2         | 1.61%   |
| FreeBSD 14.0-p5      | 2         | 1.61%   |
| FreeBSD 14.0         | 2         | 1.61%   |
| FreeBSD 13.2         | 2         | 1.61%   |
| FreeBSD 13.0-STABLE  | 2         | 1.61%   |
| FreeBSD 12.1         | 2         | 1.61%   |
| OS108 9.99.68        | 1         | 0.81%   |
| OPNsense 23.1.7      | 1         | 0.81%   |
| OPNsense 22.7.4      | 1         | 0.81%   |
| OpenBSD 7.2          | 1         | 0.81%   |
| OpenBSD 7.0          | 1         | 0.81%   |
| OpenBSD 6.9          | 1         | 0.81%   |
| helloSystem 0.8.2    | 1         | 0.81%   |
| helloSystem 0.3.0    | 1         | 0.81%   |
| GhostBSD 23.05.22    | 1         | 0.81%   |
| GhostBSD 22.11.22    | 1         | 0.81%   |
| GhostBSD 22.07.10    | 1         | 0.81%   |
| GhostBSD 20.04.02    | 1         | 0.81%   |
| FreeBSD 14.0-p6      | 1         | 0.81%   |
| FreeBSD 13.2-p7      | 1         | 0.81%   |
| FreeBSD 13.1-p4      | 1         | 0.81%   |
| FreeBSD 13.0-RC2     | 1         | 0.81%   |
| FreeBSD 13.0-p7      | 1         | 0.81%   |
| FreeBSD 13.0-p4      | 1         | 0.81%   |
| FreeBSD 13.0-CURRENT | 1         | 0.81%   |
| FreeBSD 12.2-p3      | 1         | 0.81%   |
| FreeBSD 12.2         | 1         | 0.81%   |
| FreeBSD 12.1-p7      | 1         | 0.81%   |
| FreeBSD 12.1-p11     | 1         | 0.81%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| helloSystem | 69        | 58.97%  |
| FreeBSD     | 32        | 27.35%  |
| OpenBSD     | 8         | 6.84%   |
| GhostBSD    | 4         | 3.42%   |
| OPNsense    | 2         | 1.71%   |
| OS108       | 1         | 0.85%   |
| DragonFly   | 1         | 0.85%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 111       | 97.37%  |
| i386  | 2         | 1.75%   |
| arm64 | 1         | 0.88%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 72        | 60.5%   |
| Console      | 8         | 6.72%   |
| GNOME        | 7         | 5.88%   |
| XFCE         | 6         | 5.04%   |
| MATE         | 6         | 5.04%   |
| KDE5         | 4         | 3.36%   |
| TWM          | 3         | 2.52%   |
| i3           | 3         | 2.52%   |
| spectrwm     | 2         | 1.68%   |
| Openbox      | 2         | 1.68%   |
| fvwm         | 2         | 1.68%   |
| LXQt         | 1         | 0.84%   |
| KDE          | 1         | 0.84%   |
| Hyprland     | 1         | 0.84%   |
| EXWM         | 1         | 0.84%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 106       | 91.38%  |
| Console | 9         | 7.76%   |
| Wayland | 1         | 0.86%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SLiM    | 74        | 62.71%  |
| Console | 23        | 19.49%  |
| LightDM | 8         | 6.78%   |
| SDDM    | 6         | 5.08%   |
| GDM     | 4         | 3.39%   |
| XDM     | 3         | 2.54%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang            | Notebooks | Percent |
|-----------------|-----------|---------|
| en_US           | 52        | 43.33%  |
| Unknown         | 22        | 18.33%  |
| pt_BR           | 18        | 15%     |
| C               | 17        | 14.17%  |
| pt              | 5         | 4.17%   |
| fr_FR           | 4         | 3.33%   |
| en_US.ISO8859-1 | 1         | 0.83%   |
| en_GB           | 1         | 0.83%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 101       | 88.6%   |
| BIOS | 13        | 11.4%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Zfs     | 80        | 67.23%  |
| Cd9660  | 17        | 14.29%  |
| Ufs     | 13        | 10.92%  |
| Ffs     | 8         | 6.72%   |
| Hammer2 | 1         | 0.84%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 111       | 97.37%  |
| MBR     | 2         | 1.75%   |
| Unknown | 1         | 0.88%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 30        | 26.32%  |
| Dell                   | 26        | 22.81%  |
| Acer                   | 15        | 13.16%  |
| Samsung Electronics    | 10        | 8.77%   |
| Sony                   | 4         | 3.51%   |
| Apple                  | 4         | 3.51%   |
| Itautec                | 3         | 2.63%   |
| Hewlett-Packard        | 3         | 2.63%   |
| Avell High Performance | 3         | 2.63%   |
| Unknown                | 3         | 2.63%   |
| Gateway                | 2         | 1.75%   |
| ASUSTek Computer       | 2         | 1.75%   |
| Semp Toshiba           | 1         | 0.88%   |
| Positivo               | 1         | 0.88%   |
| Philco                 | 1         | 0.88%   |
| Notebook               | 1         | 0.88%   |
| LG Electronics         | 1         | 0.88%   |
| Intel                  | 1         | 0.88%   |
| GPD                    | 1         | 0.88%   |
| Compaq                 | 1         | 0.88%   |
| Clevo                  | 1         | 0.88%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                                  | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Dell Inspiron 3442                                    | 6         | 5.26%   |
| Dell Inspiron 3421                                    | 3         | 2.63%   |
| Unknown                                               | 3         | 2.63%   |
| Samsung 340XAA/350XAA/550XAA                          | 2         | 1.75%   |
| Samsung 270E5K/270E5Q/271E5K/2570EK                   | 2         | 1.75%   |
| Gateway NE56R                                         | 2         | 1.75%   |
| Dell Latitude 5490                                    | 2         | 1.75%   |
| Acer Aspire 5750                                      | 2         | 1.75%   |
| Sony VPCYB45JB                                        | 1         | 0.88%   |
| Sony VPCEG17FB                                        | 1         | 0.88%   |
| Sony VPCEG15FB                                        | 1         | 0.88%   |
| Sony SVF14A15CBB                                      | 1         | 0.88%   |
| Semp Toshiba STI NA 1401                              | 1         | 0.88%   |
| Samsung RV411/RV511/E3511/S3511/RV711/E3411           | 1         | 0.88%   |
| Samsung 530XBB                                        | 1         | 0.88%   |
| Samsung 370E4K                                        | 1         | 0.88%   |
| Samsung 300E5M/300E5L                                 | 1         | 0.88%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV/2470EV/2470EE | 1         | 0.88%   |
| Samsung 275E4E/275E5E                                 | 1         | 0.88%   |
| Positivo C14CR01                                      | 1         | 0.88%   |
| Philco 10B                                            | 1         | 0.88%   |
| Notebook N85_N87HCHNHZ                                | 1         | 0.88%   |
| LG 14Z980-G.BH51P1                                    | 1         | 0.88%   |
| Lenovo V14 G2 ITL 82NM                                | 1         | 0.88%   |
| Lenovo ThinkPad X270 20HM004JBR                       | 1         | 0.88%   |
| Lenovo ThinkPad X250 20CLS2A11K                       | 1         | 0.88%   |
| Lenovo ThinkPad X250 20CLS18S0Z                       | 1         | 0.88%   |
| Lenovo ThinkPad X240 20AMS4V000                       | 1         | 0.88%   |
| Lenovo ThinkPad X230 23257EP                          | 1         | 0.88%   |
| Lenovo ThinkPad X220 4291ON5                          | 1         | 0.88%   |
| Lenovo ThinkPad X220 42912Z1                          | 1         | 0.88%   |
| Lenovo ThinkPad X201 36801T6                          | 1         | 0.88%   |
| Lenovo ThinkPad T61 7661GY9                           | 1         | 0.88%   |
| Lenovo ThinkPad T61 7659AS5                           | 1         | 0.88%   |
| Lenovo ThinkPad T490 20N30029BR                       | 1         | 0.88%   |
| Lenovo ThinkPad T460 20FN002JUS                       | 1         | 0.88%   |
| Lenovo ThinkPad T450s 20BWS05G0T                      | 1         | 0.88%   |
| Lenovo ThinkPad T430u 33522D5                         | 1         | 0.88%   |
| Lenovo ThinkPad T430 2349PMP                          | 1         | 0.88%   |
| Lenovo ThinkPad T430 2349G5P                          | 1         | 0.88%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Lenovo ThinkPad            | 19        | 16.67%  |
| Dell Inspiron              | 19        | 16.67%  |
| Acer Aspire                | 13        | 11.4%   |
| Lenovo IdeaPad             | 6         | 5.26%   |
| Dell Latitude              | 4         | 3.51%   |
| Itautec Infoway            | 3         | 2.63%   |
| Unknown                    | 3         | 2.63%   |
| Samsung 340XAA             | 2         | 1.75%   |
| Samsung 270E5K             | 2         | 1.75%   |
| Gateway NE56R              | 2         | 1.75%   |
| Dell Vostro                | 2         | 1.75%   |
| Avell High Performance A62 | 2         | 1.75%   |
| Acer Nitro                 | 2         | 1.75%   |
| Sony VPCYB45JB             | 1         | 0.88%   |
| Sony VPCEG17FB             | 1         | 0.88%   |
| Sony VPCEG15FB             | 1         | 0.88%   |
| Sony SVF14A15CBB           | 1         | 0.88%   |
| Semp Toshiba STI           | 1         | 0.88%   |
| Samsung RV411              | 1         | 0.88%   |
| Samsung 530XBB             | 1         | 0.88%   |
| Samsung 370E4K             | 1         | 0.88%   |
| Samsung 300E5M             | 1         | 0.88%   |
| Samsung 300E5EV            | 1         | 0.88%   |
| Samsung 275E4E             | 1         | 0.88%   |
| Positivo C14CR01           | 1         | 0.88%   |
| Philco 10B                 | 1         | 0.88%   |
| Notebook N85               | 1         | 0.88%   |
| LG 14Z980-G.BH51P1         | 1         | 0.88%   |
| Lenovo V14                 | 1         | 0.88%   |
| Lenovo G550                | 1         | 0.88%   |
| Lenovo G475                | 1         | 0.88%   |
| Lenovo B40-70              | 1         | 0.88%   |
| Lenovo B40-30              | 1         | 0.88%   |
| Intel HuronRiver           | 1         | 0.88%   |
| HP EliteBook               | 1         | 0.88%   |
| HP 14                      | 1         | 0.88%   |
| HP 1000                    | 1         | 0.88%   |
| GPD G1619-04               | 1         | 0.88%   |
| Dell Venue                 | 1         | 0.88%   |
| Compaq Presario            | 1         | 0.88%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2013    | 16        | 14.04%  |
| 2011    | 14        | 12.28%  |
| 2018    | 11        | 9.65%   |
| 2020    | 9         | 7.89%   |
| 2014    | 9         | 7.89%   |
| 2016    | 8         | 7.02%   |
| 2019    | 7         | 6.14%   |
| 2022    | 6         | 5.26%   |
| 2017    | 5         | 4.39%   |
| 2015    | 5         | 4.39%   |
| 2012    | 5         | 4.39%   |
| 2021    | 4         | 3.51%   |
| 2010    | 3         | 2.63%   |
| 2009    | 3         | 2.63%   |
| 2007    | 3         | 2.63%   |
| Unknown | 3         | 2.63%   |
| 2023    | 2         | 1.75%   |
| 2008    | 1         | 0.88%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 114       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 114       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 8.01-16.0  | 51        | 43.97%  |
| 4.01-8.0   | 40        | 34.48%  |
| 16.01-24.0 | 14        | 12.07%  |
| 24.01-32.0 | 4         | 3.45%   |
| 3.01-4.0   | 3         | 2.59%   |
| 32.01-64.0 | 2         | 1.72%   |
| 2.01-3.0   | 2         | 1.72%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 76        | 65.52%  |
| 0.51-1.0   | 33        | 28.45%  |
| 2.01-3.0   | 2         | 1.72%   |
| 1.01-2.0   | 2         | 1.72%   |
| 32.01-64.0 | 1         | 0.86%   |
| 24.01-32.0 | 1         | 0.86%   |
| Unknown    | 1         | 0.86%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 80        | 68.38%  |
| 2      | 26        | 22.22%  |
| 0      | 9         | 7.69%   |
| 3      | 2         | 1.71%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 71        | 62.28%  |
| Yes       | 43        | 37.72%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 100       | 87.72%  |
| No        | 14        | 12.28%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 111       | 97.37%  |
| No        | 3         | 2.63%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 83        | 72.81%  |
| No        | 31        | 27.19%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Brazil  | 114       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Sao Paulo                 | 12        | 10%     |
| Rio de Janeiro            | 6         | 5%      |
| Curitiba                  | 6         | 5%      |
| SГЈo Paulo              | 4         | 3.33%   |
| Manaus                    | 4         | 3.33%   |
| Maceió                   | 4         | 3.33%   |
| Blumenau                  | 4         | 3.33%   |
| Belo Horizonte            | 4         | 3.33%   |
| Campinas                  | 3         | 2.5%    |
| SÃ£o Paulo              | 2         | 1.67%   |
| Maraba                    | 2         | 1.67%   |
| JoГЈo Pessoa            | 2         | 1.67%   |
| Ipojuca                   | 2         | 1.67%   |
| Fortaleza                 | 2         | 1.67%   |
| Vitória                  | 1         | 0.83%   |
| Visconde do Rio Branco    | 1         | 0.83%   |
| Vila Velha                | 1         | 0.83%   |
| Uberaba                   | 1         | 0.83%   |
| Trindade                  | 1         | 0.83%   |
| Teresopolis               | 1         | 0.83%   |
| Teresina                  | 1         | 0.83%   |
| Tangara                   | 1         | 0.83%   |
| SГЈo JosГ© dos Campos | 1         | 0.83%   |
| Sobral                    | 1         | 0.83%   |
| Sete Lagoas               | 1         | 0.83%   |
| Sao Vicente               | 1         | 0.83%   |
| Sao Jeronimo da Serra     | 1         | 0.83%   |
| Sao Bernardo do Campo     | 1         | 0.83%   |
| Santa Maria               | 1         | 0.83%   |
| Rio das Ostras            | 1         | 0.83%   |
| Presidente Prudente       | 1         | 0.83%   |
| Porto UniГЈo            | 1         | 0.83%   |
| Porto Alegre              | 1         | 0.83%   |
| Piloezinhos               | 1         | 0.83%   |
| Pelotas                   | 1         | 0.83%   |
| Patrocinio                | 1         | 0.83%   |
| Paracuru                  | 1         | 0.83%   |
| Palmas                    | 1         | 0.83%   |
| Osasco                    | 1         | 0.83%   |
| Niterói                  | 1         | 0.83%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 22        | 24     | 15.83%  |
| Seagate             | 21        | 24     | 15.11%  |
| Kingston            | 17        | 20     | 12.23%  |
| Toshiba             | 14        | 14     | 10.07%  |
| Samsung Electronics | 10        | 11     | 7.19%   |
| A-DATA Technology   | 9         | 9      | 6.47%   |
| Crucial             | 7         | 11     | 5.04%   |
| SanDisk             | 5         | 5      | 3.6%    |
| NVMe                | 4         | 5      | 2.88%   |
| LITEON              | 4         | 4      | 2.88%   |
| SSSTC               | 3         | 3      | 2.16%   |
| SK hynix            | 3         | 3      | 2.16%   |
| Patriot             | 2         | 5      | 1.44%   |
| KingSpec            | 2         | 3      | 1.44%   |
| Hitachi             | 2         | 2      | 1.44%   |
| Gigabyte Technology | 2         | 2      | 1.44%   |
| China               | 2         | 2      | 1.44%   |
| SMI                 | 1         | 1      | 0.72%   |
| Smart               | 1         | 1      | 0.72%   |
| Silicon Motion      | 1         | 1      | 0.72%   |
| PNY                 | 1         | 1      | 0.72%   |
| Phison              | 1         | 1      | 0.72%   |
| Lexar               | 1         | 1      | 0.72%   |
| Hikvision           | 1         | 1      | 0.72%   |
| Biostar             | 1         | 1      | 0.72%   |
| BHT                 | 1         | 1      | 0.72%   |
| Apple               | 1         | 1      | 0.72%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Toshiba MQ01ABD100 1TB              | 4         | 2.8%    |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 3         | 2.1%    |
| Kingston SA400S37960G 960GB         | 3         | 2.1%    |
| Kingston SA400S37240G 240GB         | 3         | 2.1%    |
| WDC WDS480G2G0B-00EPW0 480GB        | 2         | 1.4%    |
| WDC WDS240G2G0A-00JH30 240GB        | 2         | 1.4%    |
| WDC WD10SPZX-24Z10 1TB              | 2         | 1.4%    |
| SSSTC CL1-4D256 256GB               | 2         | 1.4%    |
| Seagate ST9500325AS 500GB           | 2         | 1.4%    |
| Seagate ST750LM022 HN-M750MBB 752GB | 2         | 1.4%    |
| Seagate ST500LT012-9WS142 500GB     | 2         | 1.4%    |
| Seagate ST500LM012 HN-M500MBB 500GB | 2         | 1.4%    |
| Seagate ST1000LM048-2E7172 1TB      | 2         | 1.4%    |
| Seagate ST1000LM035-1RK172 1TB      | 2         | 1.4%    |
| SanDisk SSD U100 32GB               | 2         | 1.4%    |
| Samsung HM500JJ 500GB               | 2         | 1.4%    |
| Samsung HM321HI 320GB               | 2         | 1.4%    |
| Patriot Burst 120GB                 | 2         | 1.4%    |
| Kingston SA400S37480G 480GB         | 2         | 1.4%    |
| Gigabyte GP-GSTFS31120GNTD 120GB    | 2         | 1.4%    |
| Crucial CT480BX500SSD1 480GB        | 2         | 1.4%    |
| A-DATA SU810NS38 SATA 256 GB        | 2         | 1.4%    |
| WDC WDS120G1G0A-00SS50 120GB        | 1         | 0.7%    |
| WDC WDS100T2G0A-00JH30 1TB          | 1         | 0.7%    |
| WDC WD800BEVS-00RST0 80GB           | 1         | 0.7%    |
| WDC WD6400BEVT-22A0RT0 640GB        | 1         | 0.7%    |
| WDC WD5000LPCX-35VHAT0 500GB        | 1         | 0.7%    |
| WDC WD5000B 500GB                   | 1         | 0.7%    |
| WDC WD20SPZX-22UA7T0 2TB            | 1         | 0.7%    |
| WDC WD1600BPVT-11JJ5T0 160GB        | 1         | 0.7%    |
| WDC WD1600BEVS-60RST0 160GB         | 1         | 0.7%    |
| WDC WD1600BEVS-22VAT0 160GB         | 1         | 0.7%    |
| WDC WD10SPZX-75Z10T2 1TB            | 1         | 0.7%    |
| WDC WD10SPZX-75Z10T1 1TB            | 1         | 0.7%    |
| WDC WD10SPZX-35Z10T0 1TB            | 1         | 0.7%    |
| WDC WD10JPVX-80JC3T0 1TB            | 1         | 0.7%    |
| WDC WD10JPVX-75JC3T0 1TB            | 1         | 0.7%    |
| WDC WD10JPVX-35JC3T0 1TB            | 1         | 0.7%    |
| WDC WD10JPVX-22JC3T0 1TB            | 1         | 0.7%    |
| WDC WD10JPCX-24UE4T0 1TB            | 1         | 0.7%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 21        | 24     | 33.87%  |
| WDC                 | 18        | 18     | 29.03%  |
| Toshiba             | 13        | 13     | 20.97%  |
| Samsung Electronics | 5         | 6      | 8.06%   |
| NVMe                | 2         | 3      | 3.23%   |
| Hitachi             | 2         | 2      | 3.23%   |
| SMI                 | 1         | 1      | 1.61%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 16        | 19     | 26.67%  |
| Crucial             | 6         | 10     | 10%     |
| WDC                 | 5         | 6      | 8.33%   |
| SanDisk             | 5         | 5      | 8.33%   |
| Samsung Electronics | 4         | 4      | 6.67%   |
| LITEON              | 4         | 4      | 6.67%   |
| SK hynix            | 2         | 2      | 3.33%   |
| Patriot             | 2         | 5      | 3.33%   |
| KingSpec            | 2         | 3      | 3.33%   |
| Gigabyte Technology | 2         | 2      | 3.33%   |
| China               | 2         | 2      | 3.33%   |
| A-DATA Technology   | 2         | 2      | 3.33%   |
| Smart               | 1         | 1      | 1.67%   |
| PNY                 | 1         | 1      | 1.67%   |
| NVMe                | 1         | 1      | 1.67%   |
| Lexar               | 1         | 1      | 1.67%   |
| Hikvision           | 1         | 1      | 1.67%   |
| Biostar             | 1         | 1      | 1.67%   |
| BHT                 | 1         | 1      | 1.67%   |
| Apple               | 1         | 1      | 1.67%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 55        | 72     | 43.31%  |
| HDD  | 54        | 67     | 42.52%  |
| NVMe | 18        | 18     | 14.17%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 94        | 139    | 83.93%  |
| NVMe | 18        | 18     | 16.07%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB      | Notebooks | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 73        | 100    | 67.59%  |
| 0.51-1.0        | 30        | 34     | 27.78%  |
| 1.01-2.0        | 4         | 4      | 3.7%    |
| More than 100.0 | 1         | 1      | 0.93%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 39        | 31.2%   |
| 1-20       | 30        | 24%     |
| 251-500    | 20        | 16%     |
| 51-100     | 13        | 10.4%   |
| 501-1000   | 12        | 9.6%    |
| 21-50      | 6         | 4.8%    |
| 1001-2000  | 3         | 2.4%    |
| 2001-3000  | 1         | 0.8%    |
| Unknown    | 1         | 0.8%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 97        | 83.62%  |
| 21-50    | 8         | 6.9%    |
| 101-250  | 4         | 3.45%   |
| 501-1000 | 3         | 2.59%   |
| 51-100   | 2         | 1.72%   |
| 251-500  | 1         | 0.86%   |
| Unknown  | 1         | 0.86%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB             | 2         | 2      | 6.67%   |
| Seagate ST9500325AS 500GB          | 2         | 2      | 6.67%   |
| Seagate ST500LT012-9WS142 500GB    | 2         | 2      | 6.67%   |
| Samsung Electronics HM321HI 320GB  | 2         | 2      | 6.67%   |
| WDC WD5000B 500GB                  | 1         | 1      | 3.33%   |
| WDC WD1600BEVS-60RST0 160GB        | 1         | 1      | 3.33%   |
| WDC WD10JPVX-75JC3T0 1TB           | 1         | 1      | 3.33%   |
| Toshiba MK6465GSX 640GB            | 1         | 1      | 3.33%   |
| Toshiba MK6034GSX 64GB             | 1         | 1      | 3.33%   |
| Toshiba MK5076GSX 500GB            | 1         | 1      | 3.33%   |
| Toshiba MK3261GSYN 320GB           | 1         | 1      | 3.33%   |
| Toshiba MK2555GSXF 250GB           | 1         | 1      | 3.33%   |
| Toshiba MK1646GSX 160GB            | 1         | 1      | 3.33%   |
| Toshiba MK1252GSX 120GB            | 1         | 1      | 3.33%   |
| Toshiba MK1246GSX 120GB            | 1         | 1      | 3.33%   |
| SK hynix HFS128G39TND-N210A 128GB  | 1         | 1      | 3.33%   |
| Seagate ST9320325ASG 320GB         | 1         | 2      | 3.33%   |
| Seagate ST9320325AS 320GB          | 1         | 1      | 3.33%   |
| Seagate ST9250315AS 250GB          | 1         | 1      | 3.33%   |
| Seagate ST9160314AS 160GB          | 1         | 1      | 3.33%   |
| Seagate ST9120821AS 120GB          | 1         | 1      | 3.33%   |
| Seagate ST1000LM048-2E7172 1TB     | 1         | 1      | 3.33%   |
| Seagate ST1000LM025 HN-M101ABB 1TB | 1         | 1      | 3.33%   |
| LITEON LJH-64V2G-11 M.2 2260 64GB  | 1         | 1      | 3.33%   |
| Hitachi HTS547550A9E384 500GB      | 1         | 1      | 3.33%   |
| Hitachi HTS545050B9A300 500GB      | 1         | 1      | 3.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 12     | 36.67%  |
| Toshiba             | 10        | 10     | 33.33%  |
| WDC                 | 3         | 3      | 10%     |
| Samsung Electronics | 2         | 2      | 6.67%   |
| Hitachi             | 2         | 2      | 6.67%   |
| SK hynix            | 1         | 1      | 3.33%   |
| LITEON              | 1         | 1      | 3.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 12     | 39.29%  |
| Toshiba             | 10        | 10     | 35.71%  |
| WDC                 | 3         | 3      | 10.71%  |
| Samsung Electronics | 2         | 2      | 7.14%   |
| Hitachi             | 2         | 2      | 7.14%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 24        | 29     | 92.31%  |
| SSD  | 2         | 2      | 7.69%   |

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
| Works    | 87        | 119    | 73.11%  |
| Malfunc  | 26        | 31     | 21.85%  |
| Detected | 5         | 6      | 4.2%    |
| Failed   | 1         | 1      | 0.84%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 102       | 76.69%  |
| ADATA Technology               | 8         | 6.02%   |
| AMD                            | 6         | 4.51%   |
| Solid State Storage Technology | 4         | 3.01%   |
| Kingston Technology Company    | 3         | 2.26%   |
| Toshiba                        | 1         | 0.75%   |
| SK hynix                       | 1         | 0.75%   |
| Silicon Motion                 | 1         | 0.75%   |
| Samsung Electronics            | 1         | 0.75%   |
| Realtek Semiconductor          | 1         | 0.75%   |
| Phison Electronics             | 1         | 0.75%   |
| Nvidia                         | 1         | 0.75%   |
| Micron/Crucial Technology      | 1         | 0.75%   |
| MAXIO Technology (Hangzhou)    | 1         | 0.75%   |
| Biwin Storage Technology       | 1         | 0.75%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 17        | 12.23%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 16        | 11.51%  |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 10        | 7.19%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                           | 9         | 6.47%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 9         | 6.47%   |
| ADATA IM2P33F8 series NVMe SSD (DRAM-less)                                   | 5         | 3.6%    |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                               | 4         | 2.88%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                            | 4         | 2.88%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller               | 4         | 2.88%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                            | 4         | 2.88%   |
| Intel Tiger Lake-LP SATA Controller                                          | 3         | 2.16%   |
| Intel Comet Lake SATA AHCI Controller                                        | 3         | 2.16%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                | 3         | 2.16%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                               | 3         | 2.16%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                | 2         | 1.44%   |
| Intel Volume Management Device NVMe RAID Controller                          | 2         | 1.44%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                       | 2         | 1.44%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller     | 2         | 1.44%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                            | 2         | 1.44%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]        | 2         | 1.44%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                             | 2         | 1.44%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                | 2         | 1.44%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]              | 2         | 1.44%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]              | 2         | 1.44%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller               | 2         | 1.44%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                         | 2         | 1.44%   |
| Toshiba BG3 x2 NVMe SSD Controller (DRAM-less)                               | 1         | 0.72%   |
| SK hynix BC511 NVMe SSD                                                      | 1         | 0.72%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers            | 1         | 0.72%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                | 1         | 0.72%   |
| Realtek RTS5763DL NVMe SSD Controller (DRAM-less)                            | 1         | 0.72%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                          | 1         | 0.72%   |
| Nvidia MCP79 AHCI Controller                                                 | 1         | 0.72%   |
| Micron/Crucial P1 NVMe PCIe SSD[Frampton]                                    | 1         | 0.72%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                     | 1         | 0.72%   |
| Kingston Company A1000/U-SNS8154P3 x2 NVMe SSD                               | 1         | 0.72%   |
| Intel Tiger Lake SATA AHCI Controller                                        | 1         | 0.72%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                           | 1         | 0.72%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                | 1         | 0.72%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                        | 1         | 0.72%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 101       | 74.26%  |
| NVMe | 23        | 16.91%  |
| IDE  | 7         | 5.15%   |
| RAID | 5         | 3.68%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 104       | 91.23%  |
| AMD     | 9         | 7.89%   |
| Unknown | 1         | 0.88%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i3-4005U CPU @ 1.70GHz       | 5         | 4.39%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 4         | 3.51%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 3         | 2.63%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 3         | 2.63%   |
| Intel Core i5-3337U CPU @ 1.80GHz       | 3         | 2.63%   |
| Intel Core i5-2410M CPU @ 2.30GHz       | 3         | 2.63%   |
| Intel Genuine CPU                       | 2         | 1.75%   |
| Intel CPU Version                       | 2         | 1.75%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 2         | 1.75%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 2         | 1.75%   |
| Intel Core i7-5600U CPU @ 2.60GHz       | 2         | 1.75%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 2         | 1.75%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 2         | 1.75%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 2         | 1.75%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 2         | 1.75%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz      | 2         | 1.75%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 2         | 1.75%   |
| Intel Core i3-6100U CPU @ 2.30GHz       | 2         | 1.75%   |
| Intel Core i3-2330M CPU @ 2.20GHz       | 2         | 1.75%   |
| Intel Celeron CPU N3350 @ 1.10GHz       | 2         | 1.75%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 2         | 1.75%   |
| Intel Pentium M                         | 1         | 0.88%   |
| Intel Pentium CPU P6200 @ 2.13GHz       | 1         | 0.88%   |
| Intel Pentium CPU 5405U @ 2.30GHz       | 1         | 0.88%   |
| Intel Core M-5Y10c CPU @ 0.80GHz        | 1         | 0.88%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 1         | 0.88%   |
| Intel Core i7-8665U CPU @ 1.90GHz       | 1         | 0.88%   |
| Intel Core i7-8650U CPU @ 1.90GHz       | 1         | 0.88%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 1         | 0.88%   |
| Intel Core i7-7600U CPU @ 2.80GHz       | 1         | 0.88%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 1         | 0.88%   |
| Intel Core i7-5500U CPU @ 2.40GHz       | 1         | 0.88%   |
| Intel Core i7-3632QM CPU @ 2.20GHz      | 1         | 0.88%   |
| Intel Core i7-2630QM CPU @ 2.00GHz      | 1         | 0.88%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 1         | 0.88%   |
| Intel Core i5-9300H CPU @ 2.40GHz       | 1         | 0.88%   |
| Intel Core i5-8350U CPU @ 1.70GHz       | 1         | 0.88%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 1         | 0.88%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz      | 1         | 0.88%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 1         | 0.88%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 43        | 37.72%  |
| Intel Core i7    | 18        | 15.79%  |
| Intel Core i3    | 16        | 14.04%  |
| Intel Celeron    | 9         | 7.89%   |
| Other            | 7         | 6.14%   |
| Intel Core 2 Duo | 4         | 3.51%   |
| Intel Pentium    | 2         | 1.75%   |
| Intel Genuine    | 2         | 1.75%   |
| Intel Atom       | 2         | 1.75%   |
| AMD Ryzen 7      | 2         | 1.75%   |
| AMD E1           | 2         | 1.75%   |
| Intel Pentium M  | 1         | 0.88%   |
| Intel Core M     | 1         | 0.88%   |
| AMD Ryzen 5      | 1         | 0.88%   |
| AMD E            | 1         | 0.88%   |
| AMD C-60         | 1         | 0.88%   |
| AMD C-50         | 1         | 0.88%   |
| AMD Athlon II    | 1         | 0.88%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 79        | 69.3%   |
| 4       | 21        | 18.42%  |
| Unknown | 6         | 5.26%   |
| 6       | 4         | 3.51%   |
| 8       | 2         | 1.75%   |
| 16      | 1         | 0.88%   |
| 1       | 1         | 0.88%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 110       | 96.49%  |
| 2       | 2         | 1.75%   |
| Unknown | 2         | 1.75%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 84        | 73.68%  |
| 1       | 24        | 21.05%  |
| Unknown | 6         | 5.26%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 22        | 19.3%   |
| IvyBridge     | 15        | 13.16%  |
| SandyBridge   | 14        | 12.28%  |
| Haswell       | 9         | 7.89%   |
| Broadwell     | 9         | 7.89%   |
| Skylake       | 7         | 6.14%   |
| Westmere      | 6         | 5.26%   |
| Bobcat        | 5         | 4.39%   |
| Penryn        | 4         | 3.51%   |
| TigerLake     | 3         | 2.63%   |
| Core          | 3         | 2.63%   |
| Unknown       | 3         | 2.63%   |
| Zen+          | 2         | 1.75%   |
| IceLake       | 2         | 1.75%   |
| Goldmont plus | 2         | 1.75%   |
| Goldmont      | 2         | 1.75%   |
| CometLake     | 2         | 1.75%   |
| Bonnell       | 2         | 1.75%   |
| Silvermont    | 1         | 0.88%   |
| K10           | 1         | 0.88%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 101       | 75.94%  |
| Nvidia | 20        | 15.04%  |
| AMD    | 12        | 9.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                          | 15        | 10.95%  |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 13        | 9.49%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 9         | 6.57%   |
| Intel HD Graphics 5500                                                    | 8         | 5.84%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 7         | 5.11%   |
| Intel UHD Graphics 620                                                    | 6         | 4.38%   |
| Intel Core Processor Integrated Graphics Controller                       | 6         | 4.38%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 4         | 2.92%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 4         | 2.92%   |
| Intel HD Graphics 620                                                     | 4         | 2.92%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)       | 3         | 2.19%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)         | 3         | 2.19%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 3         | 2.19%   |
| Nvidia GP108M [GeForce MX250]                                             | 2         | 1.46%   |
| Nvidia GM108M [GeForce MX130]                                             | 2         | 1.46%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 2         | 1.46%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 2         | 1.46%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 2         | 1.46%   |
| Intel HD Graphics 500                                                     | 2         | 1.46%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 2         | 1.46%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 2         | 1.46%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 2         | 1.46%   |
| AMD Wrestler [Radeon HD 7310]                                             | 2         | 1.46%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 2         | 1.46%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 1         | 0.73%   |
| Nvidia GP108M [GeForce MX230]                                             | 1         | 0.73%   |
| Nvidia GM108M [GeForce MX110]                                             | 1         | 0.73%   |
| Nvidia GM108M [GeForce 940MX]                                             | 1         | 0.73%   |
| Nvidia GM108M [GeForce 930M]                                              | 1         | 0.73%   |
| Nvidia GM107M [GeForce GTX 950M]                                          | 1         | 0.73%   |
| Nvidia GK208M [GeForce GT 740M]                                           | 1         | 0.73%   |
| Nvidia GK208M [GeForce GT 735M]                                           | 1         | 0.73%   |
| Nvidia GK208BM [GeForce 920M]                                             | 1         | 0.73%   |
| Nvidia GF119M [GeForce 410M]                                              | 1         | 0.73%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]      | 1         | 0.73%   |
| Nvidia C79 [GeForce 9400M]                                                | 1         | 0.73%   |
| Intel Whiskey Lake-U GT1 [UHD Graphics 610]                               | 1         | 0.73%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 1         | 0.73%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                 | 1         | 0.73%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                | 1         | 0.73%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 74        | 64.91%  |
| Intel + Nvidia | 18        | 15.79%  |
| 1 x AMD        | 10        | 8.77%   |
| 2 x Intel      | 7         | 6.14%   |
| 1 x Nvidia     | 2         | 1.75%   |
| Intel + AMD    | 2         | 1.75%   |
| Other          | 1         | 0.88%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 108       | 94.74%  |
| Proprietary | 3         | 2.63%   |
| Unknown     | 3         | 2.63%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 107       | 93.04%  |
| 0.01-0.5   | 5         | 4.35%   |
| 3.01-4.0   | 2         | 1.74%   |
| 1.01-2.0   | 1         | 0.87%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 29        | 30.85%  |
| LG Display              | 15        | 15.96%  |
| BOE                     | 12        | 12.77%  |
| Chimei Innolux          | 11        | 11.7%   |
| Samsung Electronics     | 5         | 5.32%   |
| InfoVision              | 4         | 4.26%   |
| Lenovo                  | 3         | 3.19%   |
| Dell                    | 3         | 3.19%   |
| AOC                     | 3         | 3.19%   |
| Goldstar                | 2         | 2.13%   |
| Apple                   | 2         | 2.13%   |
| Philips                 | 1         | 1.06%   |
| PANDA                   | 1         | 1.06%   |
| JDI                     | 1         | 1.06%   |
| Hewlett-Packard         | 1         | 1.06%   |
| Chi Mei Optoelectronics | 1         | 1.06%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD0385 1366x768 310x170mm 13.9-inch           | 4         | 4.26%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 340x190mm 15.3-inch         | 4         | 4.26%   |
| LG Display LCD Monitor LGD0458 1366x768 310x170mm 13.9-inch           | 2         | 2.13%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch          | 2         | 2.13%   |
| BOE LCD Monitor BOE0757 1366x768 340x190mm 15.3-inch                  | 2         | 2.13%   |
| BOE LCD Monitor BOE05EF 1366x768 310x170mm 13.9-inch                  | 2         | 2.13%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch         | 2         | 2.13%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 340x190mm 15.3-inch         | 2         | 2.13%   |
| AU Optronics LCD Monitor AUO303C 1366x768 310x170mm 13.9-inch         | 2         | 2.13%   |
| AU Optronics LCD Monitor AUO263D 1920x1080 310x170mm 13.9-inch        | 2         | 2.13%   |
| AU Optronics LCD Monitor AUO183C 1366x768 310x170mm 13.9-inch         | 2         | 2.13%   |
| AOC T2242we AOC2242 1920x1080 480x270mm 21.7-inch                     | 2         | 2.13%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 340x190mm 15.3-inch  | 1         | 1.06%   |
| Samsung Electronics LCD Monitor SEC414C 1366x768 310x170mm 13.9-inch  | 1         | 1.06%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 340x190mm 15.3-inch  | 1         | 1.06%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 340x190mm 15.3-inch | 1         | 1.06%   |
| Samsung Electronics LCD Monitor SAM0D4F 1920x1080 890x500mm 40.2-inch | 1         | 1.06%   |
| Philips PHL 193V5 PHLC0CD 1366x768 410x230mm 18.5-inch                | 1         | 1.06%   |
| PANDA LCD Monitor NCP0004 1920x1080 290x170mm 13.2-inch               | 1         | 1.06%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 340x190mm 15.3-inch         | 1         | 1.06%   |
| LG Display LCD Monitor LGD05B1 1920x1080 310x170mm 13.9-inch          | 1         | 1.06%   |
| LG Display LCD Monitor LGD053C 1920x1080 310x170mm 13.9-inch          | 1         | 1.06%   |
| LG Display LCD Monitor LGD0505 1366x768 340x190mm 15.3-inch           | 1         | 1.06%   |
| LG Display LCD Monitor LGD03ED 1366x768 280x160mm 12.7-inch           | 1         | 1.06%   |
| LG Display LCD Monitor LGD03B7 1366x768 310x170mm 13.9-inch           | 1         | 1.06%   |
| LG Display LCD Monitor LGD02D3 1366x768 280x160mm 12.7-inch           | 1         | 1.06%   |
| Lenovo LEN X24A LEN60CF 1920x1080 530x300mm 24.0-inch                 | 1         | 1.06%   |
| Lenovo LCD Monitor LEN4035 1280x800 300x190mm 14.0-inch               | 1         | 1.06%   |
| Lenovo LCD Monitor LEN4031 1280x800 300x190mm 14.0-inch               | 1         | 1.06%   |
| JDI GPD1001H JDI0031 2560x1600 890x500mm 40.2-inch                    | 1         | 1.06%   |
| InfoVision LCD Monitor IVO057D 1920x1080 310x170mm 13.9-inch          | 1         | 1.06%   |
| InfoVision LCD Monitor IVO057A 1366x768 310x170mm 13.9-inch           | 1         | 1.06%   |
| InfoVision LCD Monitor IVO0579 1366x768 310x170mm 13.9-inch           | 1         | 1.06%   |
| InfoVision LCD Monitor IVO03F4 1024x600 220x130mm 10.1-inch           | 1         | 1.06%   |
| Hewlett-Packard L200hx HWP298F 1600x900 450x250mm 20.3-inch           | 1         | 1.06%   |
| Goldstar LG FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch             | 1         | 1.06%   |
| Goldstar LCD Monitor GSM580D 1920x1080 510x290mm 23.1-inch            | 1         | 1.06%   |
| Dell S2419HGF DELD0E1 1920x1080 530x300mm 24.0-inch                   | 1         | 1.06%   |
| Dell P2419H DELD0D9 1920x1080 530x300mm 24.0-inch                     | 1         | 1.06%   |
| Dell P2418D DELD0C1 2560x1440 530x300mm 24.0-inch                     | 1         | 1.06%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1366x768 (WXGA)  | 54        | 60%     |
| 1920x1080 (FHD)  | 26        | 28.89%  |
| 1280x800 (WXGA)  | 3         | 3.33%   |
| 1600x900 (HD+)   | 2         | 2.22%   |
| 1440x900 (WXGA+) | 2         | 2.22%   |
| 2560x1600        | 1         | 1.11%   |
| 2560x1440 (QHD)  | 1         | 1.11%   |
| 1024x600         | 1         | 1.11%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 13     | 40        | 42.55%  |
| 15     | 30        | 31.91%  |
| 12     | 5         | 5.32%   |
| 24     | 4         | 4.26%   |
| 14     | 4         | 4.26%   |
| 21     | 3         | 3.19%   |
| 18     | 2         | 2.13%   |
| 46     | 1         | 1.06%   |
| 40     | 1         | 1.06%   |
| 23     | 1         | 1.06%   |
| 20     | 1         | 1.06%   |
| 11     | 1         | 1.06%   |
| 10     | 1         | 1.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 68        | 72.34%  |
| 201-300     | 13        | 13.83%  |
| 401-500     | 6         | 6.38%   |
| 501-600     | 5         | 5.32%   |
| 801-900     | 1         | 1.06%   |
| 1001-1500   | 1         | 1.06%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 78        | 92.86%  |
| 16/10 | 6         | 7.14%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 43        | 45.74%  |
| 91-100         | 29        | 30.85%  |
| 201-250        | 8         | 8.51%   |
| 61-70          | 5         | 5.32%   |
| 141-150        | 2         | 2.13%   |
| 501-1000       | 2         | 2.13%   |
| 71-80          | 1         | 1.06%   |
| 51-60          | 1         | 1.06%   |
| 41-50          | 1         | 1.06%   |
| 151-200        | 1         | 1.06%   |
| 101-110        | 1         | 1.06%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 54        | 58.7%   |
| 121-160 | 25        | 27.17%  |
| 51-100  | 9         | 9.78%   |
| 161-240 | 3         | 3.26%   |
| 1-50    | 1         | 1.09%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 87        | 74.36%  |
| 0     | 16        | 13.68%  |
| 2     | 14        | 11.97%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 61        | 32.8%   |
| Qualcomm Atheros         | 49        | 26.34%  |
| Intel                    | 44        | 23.66%  |
| Broadcom                 | 14        | 7.53%   |
| JMicron Technology       | 6         | 3.23%   |
| Samsung Electronics      | 5         | 2.69%   |
| Ralink Technology        | 2         | 1.08%   |
| Xiaomi                   | 1         | 0.54%   |
| TP-Link                  | 1         | 0.54%   |
| Nvidia                   | 1         | 0.54%   |
| MediaTek                 | 1         | 0.54%   |
| Marvell Technology Group | 1         | 0.54%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 27        | 12.22%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 26        | 11.76%  |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 16        | 7.24%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 14        | 6.33%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                             | 6         | 2.71%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 6         | 2.71%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 6         | 2.71%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 6         | 2.71%   |
| Intel Wireless 8265 / 8275                                             | 5         | 2.26%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 5         | 2.26%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 4         | 1.81%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 4         | 1.81%   |
| Intel Wireless 7265                                                    | 4         | 1.81%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 3         | 1.36%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)         | 3         | 1.36%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 3         | 1.36%   |
| Intel Wi-Fi 6 AX201                                                    | 3         | 1.36%   |
| Intel Ethernet Connection (4) I219-LM                                  | 3         | 1.36%   |
| Intel Ethernet Connection (3) I218-LM                                  | 3         | 1.36%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 3         | 1.36%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 2         | 0.9%    |
| Realtek RTL8188EE Wireless Network Adapter                             | 2         | 0.9%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 2         | 0.9%    |
| JMicron JMC260 PCI Express Fast Ethernet Controller                    | 2         | 0.9%    |
| Intel Wireless 8260                                                    | 2         | 0.9%    |
| Intel Wi-Fi 6 AX200                                                    | 2         | 0.9%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                  | 2         | 0.9%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                        | 2         | 0.9%    |
| Intel Gemini Lake PCH CNVi WiFi                                        | 2         | 0.9%    |
| Intel Ethernet Connection I219-LM                                      | 2         | 0.9%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 2         | 0.9%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 2         | 0.9%    |
| Intel Comet Lake PCH CNVi WiFi                                         | 2         | 0.9%    |
| Intel Centrino Advanced-N 6200                                         | 2         | 0.9%    |
| Intel 82577LM Gigabit Network Connection                               | 2         | 0.9%    |
| Intel 82566MM Gigabit Network Connection                               | 2         | 0.9%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 2         | 0.9%    |
| Broadcom BCM43225 802.11b/g/n                                          | 2         | 0.9%    |
| Broadcom BCM43224 802.11a/b/g/n                                        | 2         | 0.9%    |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 0.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Qualcomm Atheros      | 48        | 41.38%  |
| Intel                 | 43        | 37.07%  |
| Realtek Semiconductor | 14        | 12.07%  |
| Broadcom              | 8         | 6.9%    |
| Ralink Technology     | 2         | 1.72%   |
| TP-Link               | 1         | 0.86%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 16        | 13.68%  |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 14        | 11.97%  |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 6         | 5.13%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 6         | 5.13%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 6         | 5.13%   |
| Intel Wireless 8265 / 8275                                     | 5         | 4.27%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 5         | 4.27%   |
| Intel Wireless 7265                                            | 4         | 3.42%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 3         | 2.56%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 3         | 2.56%   |
| Intel Wi-Fi 6 AX201                                            | 3         | 2.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2         | 1.71%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 2         | 1.71%   |
| Intel Wireless 8260                                            | 2         | 1.71%   |
| Intel Wi-Fi 6 AX200                                            | 2         | 1.71%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 2         | 1.71%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 2         | 1.71%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 2         | 1.71%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2         | 1.71%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 2         | 1.71%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 2         | 1.71%   |
| Intel Centrino Advanced-N 6200                                 | 2         | 1.71%   |
| Broadcom BCM43225 802.11b/g/n                                  | 2         | 1.71%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 2         | 1.71%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1         | 0.85%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 0.85%   |
| Realtek RTL8191SEvA Wireless LAN Controller                    | 1         | 0.85%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                         | 1         | 0.85%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 0.85%   |
| Realtek 8811CU Wireless LAN 802.11ac USB NIC                   | 1         | 0.85%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 1         | 0.85%   |
| Ralink RT2501/RT2573 Wireless Adapter                          | 1         | 0.85%   |
| Intel Wireless 7260                                            | 1         | 0.85%   |
| Intel Wireless 3165                                            | 1         | 0.85%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 1         | 0.85%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 1         | 0.85%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 1         | 0.85%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 1         | 0.85%   |
| Intel Centrino Wireless-N 2230                                 | 1         | 0.85%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 1         | 0.85%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 54        | 52.43%  |
| Intel                    | 20        | 19.42%  |
| Broadcom                 | 8         | 7.77%   |
| Qualcomm Atheros         | 6         | 5.83%   |
| JMicron Technology       | 6         | 5.83%   |
| Samsung Electronics      | 5         | 4.85%   |
| Xiaomi                   | 1         | 0.97%   |
| Nvidia                   | 1         | 0.97%   |
| MediaTek                 | 1         | 0.97%   |
| Marvell Technology Group | 1         | 0.97%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 27        | 26.21%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 26        | 25.24%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 6         | 5.83%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 4         | 3.88%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 4         | 3.88%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 3         | 2.91%   |
| Intel Ethernet Connection (4) I219-LM                                  | 3         | 2.91%   |
| Intel Ethernet Connection (3) I218-LM                                  | 3         | 2.91%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 3         | 2.91%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 2         | 1.94%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                    | 2         | 1.94%   |
| Intel Ethernet Connection I219-LM                                      | 2         | 1.94%   |
| Intel 82577LM Gigabit Network Connection                               | 2         | 1.94%   |
| Intel 82566MM Gigabit Network Connection                               | 2         | 1.94%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 2         | 1.94%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 0.97%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 1         | 0.97%   |
| Realtek Killer E2600 GbE Controller                                    | 1         | 0.97%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 1         | 0.97%   |
| Nvidia MCP79 Ethernet                                                  | 1         | 0.97%   |
| MediaTek USB Ethernet-RNDIS                                            | 1         | 0.97%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 1         | 0.97%   |
| Intel Ethernet Connection I218-LM                                      | 1         | 0.97%   |
| Intel Ethernet Connection (6) I219-LM                                  | 1         | 0.97%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 1         | 0.97%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                    | 1         | 0.97%   |
| Broadcom BCM4401-B0 100Base-TX                                         | 1         | 0.97%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 111       | 52.36%  |
| Ethernet | 100       | 47.17%  |
| Unknown  | 1         | 0.47%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 79        | 54.11%  |
| Ethernet | 67        | 45.89%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 94        | 82.46%  |
| 1     | 20        | 17.54%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 106       | 92.98%  |
| Yes  | 8         | 7.02%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 30        | 36.14%  |
| Qualcomm Atheros Communications | 28        | 33.73%  |
| Broadcom                        | 6         | 7.23%   |
| Lite-On Technology              | 5         | 6.02%   |
| Apple                           | 5         | 6.02%   |
| Foxconn / Hon Hai               | 4         | 4.82%   |
| Realtek Semiconductor           | 3         | 3.61%   |
| IMC Networks                    | 1         | 1.2%    |
| Dell                            | 1         | 1.2%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 11        | 13.25%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 10        | 12.05%  |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 7         | 8.43%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 6         | 7.23%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 5         | 6.02%   |
| Qualcomm Atheros Dell Wireless 1703 Bluetooth               | 4         | 4.82%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 3         | 3.61%   |
| Qualcomm Atheros AR3011 Bluetooth                           | 3         | 3.61%   |
| Intel AX201 Bluetooth                                       | 3         | 3.61%   |
| Apple Bluetooth Host Controller                             | 3         | 3.61%   |
| Realtek Bluetooth Adapter                                   | 2         | 2.41%   |
| Lite-On Qualcomm Atheros Bluetooth                          | 2         | 2.41%   |
| Intel Wireless-AC 3168 Bluetooth                            | 2         | 2.41%   |
| Intel AX200 Bluetooth                                       | 2         | 2.41%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3011 Bluetooth Adapter | 2         | 2.41%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 2         | 2.41%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 2         | 2.41%   |
| Realtek CSR Bluetooth Chip                                  | 1         | 1.2%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 1         | 1.2%    |
| Lite-On Atheros Bluetooth                                   | 1         | 1.2%    |
| Lite-On Atheros AR3012 Bluetooth                            | 1         | 1.2%    |
| Intel Centrino Bluetooth Wireless Transceiver               | 1         | 1.2%    |
| Intel AX210 Bluetooth                                       | 1         | 1.2%    |
| IMC Networks Bluetooth Module                               | 1         | 1.2%    |
| Foxconn / Hon Hai Qualcomm Atheros Bluetooth 4.0            | 1         | 1.2%    |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device             | 1         | 1.2%    |
| Dell Wireless 355 Bluetooth                                 | 1         | 1.2%    |
| Broadcom BCM2046 Bluetooth Device                           | 1         | 1.2%    |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 1         | 1.2%    |
| Apple Built-in iSight (no firmware loaded)                  | 1         | 1.2%    |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 1         | 1.2%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor            | Notebooks | Percent |
|-------------------|-----------|---------|
| Intel             | 102       | 82.93%  |
| AMD               | 9         | 7.32%   |
| Nvidia            | 7         | 5.69%   |
| Texas Instruments | 1         | 0.81%   |
| Plantronics       | 1         | 0.81%   |
| M-Audio           | 1         | 0.81%   |
| Logitech          | 1         | 0.81%   |
| Lenovo            | 1         | 0.81%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 18        | 12.16%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 18        | 12.16%  |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 10        | 6.76%   |
| Intel Haswell-ULT HD Audio Controller                                      | 9         | 6.08%   |
| Intel Broadwell-U Audio Controller                                         | 9         | 6.08%   |
| Intel 8 Series HD Audio Controller                                         | 9         | 6.08%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 8         | 5.41%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 6         | 4.05%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 5         | 3.38%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 4         | 2.7%    |
| AMD Wrestler HDMI Audio                                                    | 4         | 2.7%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 4         | 2.7%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 3         | 2.03%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3         | 2.03%   |
| Intel Comet Lake PCH-LP cAVS                                               | 3         | 2.03%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 3         | 2.03%   |
| AMD Family 17h/19h HD Audio Controller                                     | 3         | 2.03%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 1.35%   |
| Intel Comet Lake PCH cAVS                                                  | 2         | 1.35%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 1.35%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 2         | 1.35%   |
| Intel Cannon Lake PCH cAVS                                                 | 2         | 1.35%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 1.35%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 2         | 1.35%   |
| AMD FCH Azalia Controller                                                  | 2         | 1.35%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1         | 0.68%   |
| Plantronics Plantronics Blackwire 3210 Series                              | 1         | 0.68%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 0.68%   |
| Nvidia MCP79 High Definition Audio                                         | 1         | 0.68%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 0.68%   |
| M-Audio M-Audio Fast Track Pro                                             | 1         | 0.68%   |
| Logitech H390 headset with microphone                                      | 1         | 0.68%   |
| Lenovo Realtek USB Audio                                                   | 1         | 0.68%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1         | 0.68%   |
| Intel CM238 HD Audio Controller                                            | 1         | 0.68%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 1         | 0.68%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                               | 1         | 0.68%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 1         | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Smart               | 33        | 25.38%  |
| Samsung Electronics | 15        | 11.54%  |
| Kingston            | 15        | 11.54%  |
| SK hynix            | 11        | 8.46%   |
| A-DATA Technology   | 10        | 7.69%   |
| Unknown             | 9         | 6.92%   |
| Teikon              | 8         | 6.15%   |
| High Bridge         | 6         | 4.62%   |
| Smart Brazil        | 5         | 3.85%   |
| Crucial             | 4         | 3.08%   |
| Micron Technology   | 3         | 2.31%   |
| Multilaser          | 2         | 1.54%   |
| Apacer              | 2         | 1.54%   |
| Unknown (ABCD)      | 1         | 0.77%   |
| Smart Modular       | 1         | 0.77%   |
| PNY                 | 1         | 0.77%   |
| Nanya Technology    | 1         | 0.77%   |
| Lenovo              | 1         | 0.77%   |
| Kllisre             | 1         | 0.77%   |
| Unknown             | 1         | 0.77%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 6         | 4.32%   |
| Smart RAM SH564568FH8NZPHSCR 2GB SODIMM DDR3 1334MT/s            | 4         | 2.88%   |
| Smart RAM SH564128FJ8NZRNSDG 4GB SODIMM DDR3 1600MT/s            | 4         | 2.88%   |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s            | 4         | 2.88%   |
| Smart RAM SF4641G8CK8IEHLSBG 8GB SODIMM DDR4 2667MT/s            | 4         | 2.88%   |
| Smart RAM SH564128FH8NZQNSCG 4GB SODIMM DDR3 1600MT/s            | 3         | 2.16%   |
| Smart RAM SH564128FH8NZPHSCR 4GB SODIMM DDR3 1333MT/s            | 3         | 2.16%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 2         | 1.44%   |
| Teikon RAM TML251S6EFR8A-PBHC 4GB SODIMM DDR3 1600MT/s           | 2         | 1.44%   |
| Smart RAM SH564128FH8NZPHSCG 4GB SODIMM DDR3 1333MT/s            | 2         | 1.44%   |
| Smart RAM SF564128CJ8NWMNSEG 4GB SODIMM DDR3 1600MT/s            | 2         | 1.44%   |
| Smart Brazil RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2400MT/s     | 2         | 1.44%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.44%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 2         | 1.44%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s            | 2         | 1.44%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 2         | 1.44%   |
| Multilaser RAM MS3512NSZ-CA3G1 4GB SODIMM DDR3 1600MT/s          | 2         | 1.44%   |
| Kingston RAM Module 8GB SODIMM DDR3 1600MT/s                     | 2         | 1.44%   |
| High Bridge RAM HB3SU002GFM8MMB33. 2GB SODIMM DDR3 1334MT/s      | 2         | 1.44%   |
| High Bridge RAM HB3SU002GFM8DMA33. 2GB SODIMM DDR3 1334MT/s      | 2         | 1.44%   |
| A-DATA RAM AL1P32NC8W1-B1AS 8GB SODIMM DDR4 3200MT/s             | 2         | 1.44%   |
| Unknown SODIMM 2048MB SODIMM DDR2 667MT/s                        | 1         | 0.72%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 0.72%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                      | 1         | 0.72%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 1         | 0.72%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 0.72%   |
| Unknown RAM Module 4GB SODIMM DDR2 800MT/s                       | 1         | 0.72%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 1         | 0.72%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 0.72%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 0.72%   |
| Teikon RAM TMT451S6BFR8A-PBSC 4096MB SODIMM DDR3 1600MT/s        | 1         | 0.72%   |
| Teikon RAM TMT451S6BFR8A-PBHC 4GB SODIMM DDR3 1333MT/s           | 1         | 0.72%   |
| Teikon RAM TMT425S6CFR6A-PBNJ 2GB SODIMM DDR3 1600MT/s           | 1         | 0.72%   |
| Teikon RAM TMT41GS6BFR8A-PBSC 8GB SODIMM DDR3 1600MT/s           | 1         | 0.72%   |
| Teikon RAM TMT225S6FR8C-H9HC 2GB SODIMM DDR3 1334MT/s            | 1         | 0.72%   |
| Teikon RAM TMA81GS6AFR8N-UHSC 8GB SODIMM DDR4 2400MT/s           | 1         | 0.72%   |
| Smart RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2133MT/s            | 1         | 0.72%   |
| Smart RAM SH564568FH8NZPHSCG 2GB SODIMM DDR3 1066MT/s            | 1         | 0.72%   |
| Smart RAM SH564568FH8NWPHSFR 2GB SODIMM DDR3 1333MT/s            | 1         | 0.72%   |
| Smart RAM SH564128FJ8NZRNSDR 4GB SODIMM DDR3 1600MT/s            | 1         | 0.72%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 64        | 62.75%  |
| DDR4   | 29        | 28.43%  |
| DDR2   | 7         | 6.86%   |
| LPDDR4 | 1         | 0.98%   |
| DDR    | 1         | 0.98%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 99        | 96.12%  |
| Row Of Chips | 4         | 3.88%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 52        | 44.07%  |
| 8192  | 29        | 24.58%  |
| 2048  | 26        | 22.03%  |
| 16384 | 9         | 7.63%   |
| 1024  | 2         | 1.69%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 41        | 35.34%  |
| 1333    | 16        | 13.79%  |
| 2667    | 12        | 10.34%  |
| 1334    | 12        | 10.34%  |
| 2400    | 11        | 9.48%   |
| 3200    | 6         | 5.17%   |
| 2133    | 4         | 3.45%   |
| 667     | 4         | 3.45%   |
| 533     | 3         | 2.59%   |
| 800     | 2         | 1.72%   |
| 1867    | 1         | 0.86%   |
| 1067    | 1         | 0.86%   |
| 1066    | 1         | 0.86%   |
| 975     | 1         | 0.86%   |
| Unknown | 1         | 0.86%   |

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
| Chicony Electronics           | 22        | 23.16%  |
| Bison Electronics             | 15        | 15.79%  |
| Microdia                      | 12        | 12.63%  |
| Realtek Semiconductor         | 10        | 10.53%  |
| Silicon Motion                | 8         | 8.42%   |
| IMC Networks                  | 4         | 4.21%   |
| Suyin                         | 3         | 3.16%   |
| Sunplus Innovation Technology | 3         | 3.16%   |
| Unknown                       | 2         | 2.11%   |
| Syntek                        | 2         | 2.11%   |
| Luxvisions Innotech Limited   | 2         | 2.11%   |
| Logitech                      | 2         | 2.11%   |
| Lenovo                        | 2         | 2.11%   |
| Apple                         | 2         | 2.11%   |
| Alcor Micro                   | 2         | 2.11%   |
| Tripath Technology            | 1         | 1.05%   |
| Quanta                        | 1         | 1.05%   |
| Lite-On Technology            | 1         | 1.05%   |
| ALi                           | 1         | 1.05%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Chicony HD WebCam                             | 6         | 6.25%   |
| Bison Integrated Camera                       | 6         | 6.25%   |
| Microdia Integrated_Webcam_HD                 | 5         | 5.21%   |
| Silicon Motion Realtek DMFT RGB               | 4         | 4.17%   |
| Microdia Dell Laptop Integrated Webcam HD     | 4         | 4.17%   |
| Realtek Dell EasyCamera                       | 3         | 3.13%   |
| Chicony Sony Visual Communication Camera      | 3         | 3.13%   |
| Bison Lenovo EasyCamera                       | 3         | 3.13%   |
| Unknown Realtek PC Camera                     | 2         | 2.08%   |
| Syntek EasyCamera                             | 2         | 2.08%   |
| Sunplus Integrated_Webcam_HD                  | 2         | 2.08%   |
| Silicon Motion Realtek USB 2.0 PC Camera      | 2         | 2.08%   |
| Realtek Integrated Webcam                     | 2         | 2.08%   |
| Luxvisions Innotech Limited Integrated Camera | 2         | 2.08%   |
| IMC Networks EasyCamera                       | 2         | 2.08%   |
| Chicony Lenovo Integrated Camera (0.3MP)      | 2         | 2.08%   |
| Chicony Integrated Camera                     | 2         | 2.08%   |
| Bison HD Webcam                               | 2         | 2.08%   |
| Alcor Micro Acer Integrated Webcam            | 2         | 2.08%   |
| Tripath USB Camera                            | 1         | 1.04%   |
| Suyin WebCam                                  | 1         | 1.04%   |
| Suyin USB 2.0 UVC 1.3M WebCam                 | 1         | 1.04%   |
| Suyin Integrated_Webcam_HD                    | 1         | 1.04%   |
| Sunplus HD WebCam                             | 1         | 1.04%   |
| Silicon Motion WebCam SCX Series              | 1         | 1.04%   |
| Silicon Motion ATIV VGA Camera                | 1         | 1.04%   |
| Realtek LG Camera                             | 1         | 1.04%   |
| Realtek Integrated_Webcam_FHD                 | 1         | 1.04%   |
| Realtek Integrated_Webcam_8M                  | 1         | 1.04%   |
| Realtek Integrated Webcam HD                  | 1         | 1.04%   |
| Realtek Composite Webcam                      | 1         | 1.04%   |
| Realtek Acer 640 x 480 laptop camera          | 1         | 1.04%   |
| Quanta HD Webcam                              | 1         | 1.04%   |
| Microdia Laptop_Integrated_Webcam_HD          | 1         | 1.04%   |
| Microdia Laptop_Integrated_Webcam_1.3M        | 1         | 1.04%   |
| Microdia Integrated Webcam HD                 | 1         | 1.04%   |
| Logitech Webcam C270                          | 1         | 1.04%   |
| Logitech C922 Pro Stream Webcam               | 1         | 1.04%   |
| Lite-On Integrated Camera                     | 1         | 1.04%   |
| Lenovo Integrated Webcam [R5U877]             | 1         | 1.04%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 6         | 35.29%  |
| Upek                       | 4         | 23.53%  |
| Synaptics                  | 3         | 17.65%  |
| Shenzhen Goodix Technology | 2         | 11.76%  |
| Samsung Electronics        | 1         | 5.88%   |
| Broadcom                   | 1         | 5.88%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 4         | 23.53%  |
| Validity Sensors VFS 5011 fingerprint sensor                                 | 2         | 11.76%  |
| Synaptics Metallica MOH Touch Fingerprint Reader                             | 2         | 11.76%  |
| Shenzhen Goodix Fingerprint Reader                                           | 2         | 11.76%  |
| Validity Sensors VFS5011 Fingerprint Reader                                  | 1         | 5.88%   |
| Validity Sensors VFS495 Fingerprint Reader                                   | 1         | 5.88%   |
| Validity Sensors Synaptics WBDI                                              | 1         | 5.88%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                  | 1         | 5.88%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 1         | 5.88%   |
| Samsung CanvasBio Fingerprint Reader                                         | 1         | 5.88%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 5.88%   |

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
| 2     | 36        | 31.3%   |
| 1     | 35        | 30.43%  |
| 3     | 17        | 14.78%  |
| 0     | 13        | 11.3%   |
| 4     | 9         | 7.83%   |
| 5     | 5         | 4.35%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 92        | 45.77%  |
| Card reader              | 37        | 18.41%  |
| Bluetooth                | 29        | 14.43%  |
| Net/wireless             | 20        | 9.95%   |
| Fingerprint reader       | 16        | 7.96%   |
| Sound                    | 2         | 1%      |
| Network                  | 2         | 1%      |
| Storage                  | 1         | 0.5%    |
| Net/ethernet             | 1         | 0.5%    |
| Graphics card            | 1         | 0.5%    |

