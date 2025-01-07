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

Total: 173

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Lenovo        | IdeaPad S145-15API 81V7     | [4bd0423b13](https://bsd-hardware.info/?probe=4bd0423b13) | Jan 05, 2025 |
| Dell          | Inspiron 3421               | [0cae3b71cd](https://bsd-hardware.info/?probe=0cae3b71cd) | Dec 31, 2024 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | [81977dc6c5](https://bsd-hardware.info/?probe=81977dc6c5) | Dec 28, 2024 |
| Unknown       | Unknown                     | [e02dd09c46](https://bsd-hardware.info/?probe=e02dd09c46) | Dec 12, 2024 |
| Timi          | TM1703                      | [6af452297e](https://bsd-hardware.info/?probe=6af452297e) | Dec 07, 2024 |
| Lenovo        | Legion Slim 5 16IRH8 83D... | [208feb98b3](https://bsd-hardware.info/?probe=208feb98b3) | Nov 26, 2024 |
| Lenovo        | Legion Slim 5 16IRH8 83D... | [1f1948481c](https://bsd-hardware.info/?probe=1f1948481c) | Nov 26, 2024 |
| Unknown       | Unknown                     | [c5db5961d4](https://bsd-hardware.info/?probe=c5db5961d4) | Nov 20, 2024 |
| Lenovo        | Legion Slim 5 16IRH8 83D... | [ab3ba2edf5](https://bsd-hardware.info/?probe=ab3ba2edf5) | Nov 18, 2024 |
| Lenovo        | Legion Slim 5 16IRH8 83D... | [2a9c5b1e5c](https://bsd-hardware.info/?probe=2a9c5b1e5c) | Nov 18, 2024 |
| Apple         | MacBook7,1                  | [056bc64a0c](https://bsd-hardware.info/?probe=056bc64a0c) | Nov 03, 2024 |
| Unknown       | Unknown                     | [57c6faa7cc](https://bsd-hardware.info/?probe=57c6faa7cc) | Nov 01, 2024 |
| Positivo      | H14BT58                     | [b54614c603](https://bsd-hardware.info/?probe=b54614c603) | Oct 31, 2024 |
| Unknown       | Unknown                     | [46a5a36c7d](https://bsd-hardware.info/?probe=46a5a36c7d) | Oct 29, 2024 |
| Dell          | Latitude 5490               | [aa1887b2e7](https://bsd-hardware.info/?probe=aa1887b2e7) | Oct 28, 2024 |
| Lenovo        | ThinkPad E490 20N9S48S00    | [6df8b611a2](https://bsd-hardware.info/?probe=6df8b611a2) | Oct 14, 2024 |
| Acer          | Aspire A515-45              | [3e03a4540a](https://bsd-hardware.info/?probe=3e03a4540a) | Oct 02, 2024 |
| Samsung       | 530U3C/530U4C/532U3C        | [f78f3487b8](https://bsd-hardware.info/?probe=f78f3487b8) | Aug 27, 2024 |
| Acer          | Aspire 5551                 | [861d3a83cc](https://bsd-hardware.info/?probe=861d3a83cc) | Aug 27, 2024 |
| Samsung       | 530U3C/530U4C/532U3C        | [d5e4a58748](https://bsd-hardware.info/?probe=d5e4a58748) | Aug 27, 2024 |
| Acer          | Aspire 5551                 | [07da5932a6](https://bsd-hardware.info/?probe=07da5932a6) | Aug 27, 2024 |
| Intelbras     | S41ILx                      | [85e9cf50b4](https://bsd-hardware.info/?probe=85e9cf50b4) | Aug 16, 2024 |
| Dell          | Inspiron 15-3567            | [7a5e3b5861](https://bsd-hardware.info/?probe=7a5e3b5861) | Jul 07, 2024 |
| Lenovo        | ThinkPad X230 2325SCM       | [8406cad5be](https://bsd-hardware.info/?probe=8406cad5be) | Jul 06, 2024 |
| Unknown       | Unknown                     | [d424bffcf6](https://bsd-hardware.info/?probe=d424bffcf6) | Jul 04, 2024 |
| Dell          | Inspiron 3501               | [058d42521c](https://bsd-hardware.info/?probe=058d42521c) | Jun 29, 2024 |
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
| helloSystem 0.8.1    | 18        | 12.59%  |
| helloSystem 0.7.0    | 12        | 8.39%   |
| helloSystem 0.9.0    | 10        | 6.99%   |
| helloSystem 0.6.0    | 10        | 6.99%   |
| helloSystem 0.4.0    | 10        | 6.99%   |
| helloSystem 0.5.0    | 9         | 6.29%   |
| helloSystem 0.8.0    | 8         | 5.59%   |
| FreeBSD 13.0         | 6         | 4.2%    |
| OpenBSD 7.3          | 5         | 3.5%    |
| FreeBSD 14.1         | 3         | 2.1%    |
| FreeBSD 14.0-CURRENT | 3         | 2.1%    |
| FreeBSD 14.0         | 3         | 2.1%    |
| FreeBSD 13.0-p3      | 3         | 2.1%    |
| FreeBSD 15.0-CURRENT | 2         | 1.4%    |
| FreeBSD 14.1-p5      | 2         | 1.4%    |
| FreeBSD 14.0-p5      | 2         | 1.4%    |
| FreeBSD 13.2         | 2         | 1.4%    |
| FreeBSD 13.0-STABLE  | 2         | 1.4%    |
| FreeBSD 12.1         | 2         | 1.4%    |
| OS108 9.99.68        | 1         | 0.7%    |
| OPNsense 24.7.9      | 1         | 0.7%    |
| OPNsense 24.7.7      | 1         | 0.7%    |
| OPNsense 24.1.9      | 1         | 0.7%    |
| OPNsense 23.1.7      | 1         | 0.7%    |
| OPNsense 22.7.4      | 1         | 0.7%    |
| OpenBSD 7.5          | 1         | 0.7%    |
| OpenBSD 7.2          | 1         | 0.7%    |
| OpenBSD 7.0          | 1         | 0.7%    |
| OpenBSD 6.9          | 1         | 0.7%    |
| NetBSD 10.0          | 1         | 0.7%    |
| helloSystem 0.8.2    | 1         | 0.7%    |
| helloSystem 0.3.0    | 1         | 0.7%    |
| GhostBSD 23.05.22    | 1         | 0.7%    |
| GhostBSD 22.11.22    | 1         | 0.7%    |
| GhostBSD 22.07.10    | 1         | 0.7%    |
| GhostBSD 20.04.02    | 1         | 0.7%    |
| FreeBSD 14.2         | 1         | 0.7%    |
| FreeBSD 14.1-p6      | 1         | 0.7%    |
| FreeBSD 14.0-p6      | 1         | 0.7%    |
| FreeBSD 13.2-p7      | 1         | 0.7%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| helloSystem | 74        | 55.64%  |
| FreeBSD     | 38        | 28.57%  |
| OpenBSD     | 9         | 6.77%   |
| OPNsense    | 5         | 3.76%   |
| GhostBSD    | 4         | 3.01%   |
| OS108       | 1         | 0.75%   |
| NetBSD      | 1         | 0.75%   |
| DragonFly   | 1         | 0.75%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 126       | 97.67%  |
| i386  | 2         | 1.55%   |
| arm64 | 1         | 0.78%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 78        | 56.93%  |
| Console      | 12        | 8.76%   |
| GNOME        | 8         | 5.84%   |
| XFCE         | 7         | 5.11%   |
| MATE         | 7         | 5.11%   |
| KDE5         | 7         | 5.11%   |
| TWM          | 5         | 3.65%   |
| i3           | 3         | 2.19%   |
| spectrwm     | 2         | 1.46%   |
| Openbox      | 2         | 1.46%   |
| fvwm         | 2         | 1.46%   |
| LXQt         | 1         | 0.73%   |
| KDE          | 1         | 0.73%   |
| Hyprland     | 1         | 0.73%   |
| EXWM         | 1         | 0.73%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 117       | 89.31%  |
| Console | 13        | 9.92%   |
| Wayland | 1         | 0.76%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SLiM    | 79        | 58.96%  |
| Console | 30        | 22.39%  |
| LightDM | 10        | 7.46%   |
| SDDM    | 8         | 5.97%   |
| GDM     | 4         | 2.99%   |
| XDM     | 3         | 2.24%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang            | Notebooks | Percent |
|-----------------|-----------|---------|
| en_US           | 54        | 39.71%  |
| Unknown         | 28        | 20.59%  |
| C               | 23        | 16.91%  |
| pt_BR           | 20        | 14.71%  |
| pt              | 5         | 3.68%   |
| fr_FR           | 4         | 2.94%   |
| en_US.ISO8859-1 | 1         | 0.74%   |
| en_GB           | 1         | 0.74%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 115       | 88.46%  |
| BIOS | 15        | 11.54%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Zfs     | 86        | 63.24%  |
| Ufs     | 20        | 14.71%  |
| Cd9660  | 19        | 13.97%  |
| Ffs     | 10        | 7.35%   |
| Hammer2 | 1         | 0.74%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 125       | 96.9%   |
| MBR     | 3         | 2.33%   |
| Unknown | 1         | 0.78%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 34        | 26.36%  |
| Dell                   | 28        | 21.71%  |
| Acer                   | 16        | 12.4%   |
| Samsung Electronics    | 11        | 8.53%   |
| Unknown                | 6         | 4.65%   |
| Apple                  | 5         | 3.88%   |
| Sony                   | 4         | 3.1%    |
| Itautec                | 3         | 2.33%   |
| Hewlett-Packard        | 3         | 2.33%   |
| Avell High Performance | 3         | 2.33%   |
| Positivo               | 2         | 1.55%   |
| Gateway                | 2         | 1.55%   |
| ASUSTek Computer       | 2         | 1.55%   |
| Timi                   | 1         | 0.78%   |
| Semp Toshiba           | 1         | 0.78%   |
| Philco                 | 1         | 0.78%   |
| Notebook               | 1         | 0.78%   |
| LG Electronics         | 1         | 0.78%   |
| Intelbras              | 1         | 0.78%   |
| Intel                  | 1         | 0.78%   |
| GPD                    | 1         | 0.78%   |
| Compaq                 | 1         | 0.78%   |
| Clevo                  | 1         | 0.78%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                                  | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Dell Inspiron 3442                                    | 6         | 4.65%   |
| Unknown                                               | 6         | 4.65%   |
| Dell Inspiron 3421                                    | 3         | 2.33%   |
| Samsung 340XAA/350XAA/550XAA                          | 2         | 1.55%   |
| Samsung 270E5K/270E5Q/271E5K/2570EK                   | 2         | 1.55%   |
| Lenovo IdeaPad S145-15API 81V7                        | 2         | 1.55%   |
| Gateway NE56R                                         | 2         | 1.55%   |
| Dell Latitude 5490                                    | 2         | 1.55%   |
| Acer Aspire 5750                                      | 2         | 1.55%   |
| Timi TM1703                                           | 1         | 0.78%   |
| Sony VPCYB45JB                                        | 1         | 0.78%   |
| Sony VPCEG17FB                                        | 1         | 0.78%   |
| Sony VPCEG15FB                                        | 1         | 0.78%   |
| Sony SVF14A15CBB                                      | 1         | 0.78%   |
| Semp Toshiba STI NA 1401                              | 1         | 0.78%   |
| Samsung RV411/RV511/E3511/S3511/RV711/E3411           | 1         | 0.78%   |
| Samsung 530XBB                                        | 1         | 0.78%   |
| Samsung 530U3C/530U4C/532U3C                          | 1         | 0.78%   |
| Samsung 370E4K                                        | 1         | 0.78%   |
| Samsung 300E5M/300E5L                                 | 1         | 0.78%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV/2470EV/2470EE | 1         | 0.78%   |
| Samsung 275E4E/275E5E                                 | 1         | 0.78%   |
| Positivo H14BT58                                      | 1         | 0.78%   |
| Positivo C14CR01                                      | 1         | 0.78%   |
| Philco 10B                                            | 1         | 0.78%   |
| Notebook N85_N87HCHNHZ                                | 1         | 0.78%   |
| LG 14Z980-G.BH51P1                                    | 1         | 0.78%   |
| Lenovo V14 G2 ITL 82NM                                | 1         | 0.78%   |
| Lenovo ThinkPad X270 20HM004JBR                       | 1         | 0.78%   |
| Lenovo ThinkPad X250 20CLS2A11K                       | 1         | 0.78%   |
| Lenovo ThinkPad X250 20CLS18S0Z                       | 1         | 0.78%   |
| Lenovo ThinkPad X240 20AMS4V000                       | 1         | 0.78%   |
| Lenovo ThinkPad X230 2325SCM                          | 1         | 0.78%   |
| Lenovo ThinkPad X230 23257EP                          | 1         | 0.78%   |
| Lenovo ThinkPad X220 4291ON5                          | 1         | 0.78%   |
| Lenovo ThinkPad X220 42912Z1                          | 1         | 0.78%   |
| Lenovo ThinkPad X201 36801T6                          | 1         | 0.78%   |
| Lenovo ThinkPad T61 7661GY9                           | 1         | 0.78%   |
| Lenovo ThinkPad T61 7659AS5                           | 1         | 0.78%   |
| Lenovo ThinkPad T490 20N30029BR                       | 1         | 0.78%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Dell Inspiron              | 21        | 16.28%  |
| Lenovo ThinkPad            | 20        | 15.5%   |
| Acer Aspire                | 14        | 10.85%  |
| Lenovo IdeaPad             | 8         | 6.2%    |
| Unknown                    | 6         | 4.65%   |
| Dell Latitude              | 4         | 3.1%    |
| Itautec Infoway            | 3         | 2.33%   |
| Samsung 340XAA             | 2         | 1.55%   |
| Samsung 270E5K             | 2         | 1.55%   |
| Gateway NE56R              | 2         | 1.55%   |
| Dell Vostro                | 2         | 1.55%   |
| Avell High Performance A62 | 2         | 1.55%   |
| Acer Nitro                 | 2         | 1.55%   |
| Timi TM1703                | 1         | 0.78%   |
| Sony VPCYB45JB             | 1         | 0.78%   |
| Sony VPCEG17FB             | 1         | 0.78%   |
| Sony VPCEG15FB             | 1         | 0.78%   |
| Sony SVF14A15CBB           | 1         | 0.78%   |
| Semp Toshiba STI           | 1         | 0.78%   |
| Samsung RV411              | 1         | 0.78%   |
| Samsung 530XBB             | 1         | 0.78%   |
| Samsung 530U3C             | 1         | 0.78%   |
| Samsung 370E4K             | 1         | 0.78%   |
| Samsung 300E5M             | 1         | 0.78%   |
| Samsung 300E5EV            | 1         | 0.78%   |
| Samsung 275E4E             | 1         | 0.78%   |
| Positivo H14BT58           | 1         | 0.78%   |
| Positivo C14CR01           | 1         | 0.78%   |
| Philco 10B                 | 1         | 0.78%   |
| Notebook N85               | 1         | 0.78%   |
| LG 14Z980-G.BH51P1         | 1         | 0.78%   |
| Lenovo V14                 | 1         | 0.78%   |
| Lenovo Legion              | 1         | 0.78%   |
| Lenovo G550                | 1         | 0.78%   |
| Lenovo G475                | 1         | 0.78%   |
| Lenovo B40-70              | 1         | 0.78%   |
| Lenovo B40-30              | 1         | 0.78%   |
| Intelbras S41ILx           | 1         | 0.78%   |
| Intel HuronRiver           | 1         | 0.78%   |
| HP EliteBook               | 1         | 0.78%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2013    | 17        | 13.18%  |
| 2011    | 14        | 10.85%  |
| 2018    | 12        | 9.3%    |
| 2019    | 10        | 7.75%   |
| 2020    | 9         | 6.98%   |
| 2014    | 9         | 6.98%   |
| 2016    | 8         | 6.2%    |
| 2022    | 7         | 5.43%   |
| 2012    | 7         | 5.43%   |
| 2021    | 6         | 4.65%   |
| 2015    | 6         | 4.65%   |
| 2023    | 5         | 3.88%   |
| 2017    | 5         | 3.88%   |
| 2009    | 4         | 3.1%    |
| 2010    | 3         | 2.33%   |
| 2007    | 3         | 2.33%   |
| Unknown | 3         | 2.33%   |
| 2008    | 1         | 0.78%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 129       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 129       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 8.01-16.0  | 58        | 43.61%  |
| 4.01-8.0   | 46        | 34.59%  |
| 16.01-24.0 | 16        | 12.03%  |
| 3.01-4.0   | 4         | 3.01%   |
| 24.01-32.0 | 4         | 3.01%   |
| 2.01-3.0   | 3         | 2.26%   |
| 32.01-64.0 | 2         | 1.5%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 83        | 63.36%  |
| 0.51-1.0   | 38        | 29.01%  |
| 2.01-3.0   | 3         | 2.29%   |
| 1.01-2.0   | 3         | 2.29%   |
| Unknown    | 2         | 1.53%   |
| 32.01-64.0 | 1         | 0.76%   |
| 24.01-32.0 | 1         | 0.76%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 88        | 65.67%  |
| 2      | 28        | 20.9%   |
| 0      | 15        | 11.19%  |
| 3      | 2         | 1.49%   |
| 4      | 1         | 0.75%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 84        | 65.12%  |
| Yes       | 45        | 34.88%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 113       | 87.6%   |
| No        | 16        | 12.4%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 122       | 94.57%  |
| No        | 7         | 5.43%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 93        | 72.09%  |
| No        | 36        | 27.91%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Brazil  | 129       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Sao Paulo                 | 16        | 11.68%  |
| Rio de Janeiro            | 8         | 5.84%   |
| Curitiba                  | 7         | 5.11%   |
| Belo Horizonte            | 5         | 3.65%   |
| SГЈo Paulo              | 4         | 2.92%   |
| Manaus                    | 4         | 2.92%   |
| Maceió                   | 4         | 2.92%   |
| Campinas                  | 4         | 2.92%   |
| Blumenau                  | 4         | 2.92%   |
| Fortaleza                 | 3         | 2.19%   |
| Visconde do Rio Branco    | 2         | 1.46%   |
| SÃ£o Paulo              | 2         | 1.46%   |
| Maraba                    | 2         | 1.46%   |
| JoГЈo Pessoa            | 2         | 1.46%   |
| Ipojuca                   | 2         | 1.46%   |
| Vitória                  | 1         | 0.73%   |
| Vila Velha                | 1         | 0.73%   |
| Uberaba                   | 1         | 0.73%   |
| Trindade                  | 1         | 0.73%   |
| Três Lagoas              | 1         | 0.73%   |
| Teresopolis               | 1         | 0.73%   |
| Teresina                  | 1         | 0.73%   |
| Tangara                   | 1         | 0.73%   |
| SГЈo JosГ© dos Campos | 1         | 0.73%   |
| Sobral                    | 1         | 0.73%   |
| Sete Lagoas               | 1         | 0.73%   |
| Sao Vicente               | 1         | 0.73%   |
| Sao Jeronimo da Serra     | 1         | 0.73%   |
| Sao Goncalo               | 1         | 0.73%   |
| Sao Bernardo do Campo     | 1         | 0.73%   |
| Santa Maria               | 1         | 0.73%   |
| Rio das Ostras            | 1         | 0.73%   |
| Presidente Prudente       | 1         | 0.73%   |
| Porto UniГЈo            | 1         | 0.73%   |
| Porto Alegre              | 1         | 0.73%   |
| Poços de Caldas          | 1         | 0.73%   |
| Piloezinhos               | 1         | 0.73%   |
| Petrópolis               | 1         | 0.73%   |
| Pelotas                   | 1         | 0.73%   |
| Patrocinio                | 1         | 0.73%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor                             | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| WDC                                | 24        | 27     | 15.69%  |
| Seagate                            | 23        | 27     | 15.03%  |
| Kingston                           | 19        | 22     | 12.42%  |
| Toshiba                            | 14        | 15     | 9.15%   |
| Samsung Electronics                | 11        | 12     | 7.19%   |
| A-DATA Technology                  | 9         | 10     | 5.88%   |
| SanDisk                            | 7         | 7      | 4.58%   |
| Crucial                            | 7         | 11     | 4.58%   |
| NVMe                               | 4         | 5      | 2.61%   |
| LITEON                             | 4         | 4      | 2.61%   |
| SSSTC                              | 3         | 3      | 1.96%   |
| SK hynix                           | 3         | 3      | 1.96%   |
| Product:              USB DISK 2.0 | 2         | 2      | 1.31%   |
| Patriot                            | 2         | 5      | 1.31%   |
| KingSpec                           | 2         | 3      | 1.31%   |
| Hitachi                            | 2         | 2      | 1.31%   |
| Gigabyte Technology                | 2         | 3      | 1.31%   |
| China                              | 2         | 2      | 1.31%   |
| SMI                                | 1         | 1      | 0.65%   |
| Smart                              | 1         | 1      | 0.65%   |
| Silicon Motion                     | 1         | 1      | 0.65%   |
| Qunion                             | 1         | 1      | 0.65%   |
| PNY                                | 1         | 1      | 0.65%   |
| Phison                             | 1         | 1      | 0.65%   |
| LITEONIT                           | 1         | 1      | 0.65%   |
| Lexar                              | 1         | 1      | 0.65%   |
| Hikvision                          | 1         | 1      | 0.65%   |
| Generic                            | 1         | 1      | 0.65%   |
| Biostar                            | 1         | 1      | 0.65%   |
| BHT                                | 1         | 1      | 0.65%   |
| Apple                              | 1         | 1      | 0.65%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Toshiba MQ01ABD100 1TB                               | 4         | 2.55%   |
| WDC WDS240G2G0A-00JH30 240GB                         | 3         | 1.91%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                   | 3         | 1.91%   |
| Kingston SA400S37960G 960GB                          | 3         | 1.91%   |
| Kingston SA400S37240G 240GB                          | 3         | 1.91%   |
| WDC WDS480G2G0B-00EPW0 480GB                         | 2         | 1.27%   |
| WDC WD10SPZX-24Z10 1TB                               | 2         | 1.27%   |
| SSSTC CL1-4D256 256GB                                | 2         | 1.27%   |
| Seagate ST9500325AS 500GB                            | 2         | 1.27%   |
| Seagate ST750LM022 HN-M750MBB 752GB                  | 2         | 1.27%   |
| Seagate ST500LT012-9WS142 500GB                      | 2         | 1.27%   |
| Seagate ST500LM012 HN-M500MBB 500GB                  | 2         | 1.27%   |
| Seagate ST1000LM048-2E7172 1TB                       | 2         | 1.27%   |
| Seagate ST1000LM035-1RK172 1TB                       | 2         | 1.27%   |
| SanDisk SSD U100 32GB                                | 2         | 1.27%   |
| Samsung HM500JJ 500GB                                | 2         | 1.27%   |
| Samsung HM321HI 320GB                                | 2         | 1.27%   |
| Product:              USB DISK 2.0 USB DISK 2.0 16GB | 2         | 1.27%   |
| Patriot Burst 120GB                                  | 2         | 1.27%   |
| Kingston SA400S37480G 480GB                          | 2         | 1.27%   |
| Gigabyte GP-GSTFS31120GNTD 120GB                     | 2         | 1.27%   |
| Crucial CT480BX500SSD1 480GB                         | 2         | 1.27%   |
| A-DATA SU810NS38 SATA 256 GB                         | 2         | 1.27%   |
| WDC WDS120G1G0A-00SS50 120GB                         | 1         | 0.64%   |
| WDC WDS100T2G0A-00JH30 1TB                           | 1         | 0.64%   |
| WDC WD800BEVS-00RST0 80GB                            | 1         | 0.64%   |
| WDC WD6400BEVT-22A0RT0 640GB                         | 1         | 0.64%   |
| WDC WD5000LPCX-35VHAT0 500GB                         | 1         | 0.64%   |
| WDC WD5000LPCX-24VHAT0 500GB                         | 1         | 0.64%   |
| WDC WD5000B 500GB                                    | 1         | 0.64%   |
| WDC WD20SPZX-22UA7T0 2TB                             | 1         | 0.64%   |
| WDC WD1600BPVT-11JJ5T0 160GB                         | 1         | 0.64%   |
| WDC WD1600BEVS-60RST0 160GB                          | 1         | 0.64%   |
| WDC WD1600BEVS-22VAT0 160GB                          | 1         | 0.64%   |
| WDC WD10SPZX-75Z10T2 1TB                             | 1         | 0.64%   |
| WDC WD10SPZX-75Z10T1 1TB                             | 1         | 0.64%   |
| WDC WD10SPZX-35Z10T0 1TB                             | 1         | 0.64%   |
| WDC WD10JPVX-80JC3T0 1TB                             | 1         | 0.64%   |
| WDC WD10JPVX-75JC3T0 1TB                             | 1         | 0.64%   |
| WDC WD10JPVX-35JC3T0 1TB                             | 1         | 0.64%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor                             | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate                            | 23        | 27     | 33.82%  |
| WDC                                | 19        | 19     | 27.94%  |
| Toshiba                            | 13        | 14     | 19.12%  |
| Samsung Electronics                | 5         | 6      | 7.35%   |
| Product:              USB DISK 2.0 | 2         | 2      | 2.94%   |
| NVMe                               | 2         | 3      | 2.94%   |
| Hitachi                            | 2         | 2      | 2.94%   |
| SMI                                | 1         | 1      | 1.47%   |
| Generic                            | 1         | 1      | 1.47%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 18        | 21     | 26.87%  |
| SanDisk             | 7         | 7      | 10.45%  |
| WDC                 | 6         | 8      | 8.96%   |
| Crucial             | 6         | 10     | 8.96%   |
| Samsung Electronics | 4         | 4      | 5.97%   |
| LITEON              | 4         | 4      | 5.97%   |
| SK hynix            | 2         | 2      | 2.99%   |
| Patriot             | 2         | 5      | 2.99%   |
| KingSpec            | 2         | 3      | 2.99%   |
| Gigabyte Technology | 2         | 3      | 2.99%   |
| China               | 2         | 2      | 2.99%   |
| A-DATA Technology   | 2         | 3      | 2.99%   |
| Smart               | 1         | 1      | 1.49%   |
| Qunion              | 1         | 1      | 1.49%   |
| PNY                 | 1         | 1      | 1.49%   |
| NVMe                | 1         | 1      | 1.49%   |
| LITEONIT            | 1         | 1      | 1.49%   |
| Lexar               | 1         | 1      | 1.49%   |
| Hikvision           | 1         | 1      | 1.49%   |
| Biostar             | 1         | 1      | 1.49%   |
| BHT                 | 1         | 1      | 1.49%   |
| Apple               | 1         | 1      | 1.49%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 60        | 82     | 43.8%   |
| HDD  | 58        | 75     | 42.34%  |
| NVMe | 19        | 19     | 13.87%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 102       | 157    | 84.3%   |
| NVMe | 19        | 19     | 15.7%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 82        | 118    | 70.69%  |
| 0.51-1.0   | 30        | 35     | 25.86%  |
| 1.01-2.0   | 4         | 4      | 3.45%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 45        | 31.25%  |
| 1-20       | 32        | 22.22%  |
| 251-500    | 23        | 15.97%  |
| 51-100     | 19        | 13.19%  |
| 501-1000   | 12        | 8.33%   |
| 21-50      | 8         | 5.56%   |
| 1001-2000  | 3         | 2.08%   |
| 2001-3000  | 1         | 0.69%   |
| Unknown    | 1         | 0.69%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 110       | 83.33%  |
| 21-50    | 10        | 7.58%   |
| 101-250  | 4         | 3.03%   |
| 501-1000 | 3         | 2.27%   |
| 51-100   | 3         | 2.27%   |
| 251-500  | 1         | 0.76%   |
| Unknown  | 1         | 0.76%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB              | 2         | 2      | 6.25%   |
| Seagate ST9500325AS 500GB           | 2         | 2      | 6.25%   |
| Seagate ST500LT012-9WS142 500GB     | 2         | 2      | 6.25%   |
| Samsung Electronics HM321HI 320GB   | 2         | 2      | 6.25%   |
| WDC WD5000B 500GB                   | 1         | 1      | 3.13%   |
| WDC WD1600BEVS-60RST0 160GB         | 1         | 1      | 3.13%   |
| WDC WD10JPVX-75JC3T0 1TB            | 1         | 1      | 3.13%   |
| Toshiba MK6465GSX 640GB             | 1         | 2      | 3.13%   |
| Toshiba MK6034GSX 64GB              | 1         | 1      | 3.13%   |
| Toshiba MK5076GSX 500GB             | 1         | 1      | 3.13%   |
| Toshiba MK3261GSYN 320GB            | 1         | 1      | 3.13%   |
| Toshiba MK2555GSXF 250GB            | 1         | 1      | 3.13%   |
| Toshiba MK1646GSX 160GB             | 1         | 1      | 3.13%   |
| Toshiba MK1252GSX 120GB             | 1         | 1      | 3.13%   |
| Toshiba MK1246GSX 120GB             | 1         | 1      | 3.13%   |
| SK hynix HFS128G39TND-N210A 128GB   | 1         | 1      | 3.13%   |
| Seagate ST9320325ASG 320GB          | 1         | 2      | 3.13%   |
| Seagate ST9320325AS 320GB           | 1         | 1      | 3.13%   |
| Seagate ST9250315AS 250GB           | 1         | 1      | 3.13%   |
| Seagate ST9160314AS 160GB           | 1         | 1      | 3.13%   |
| Seagate ST9120821AS 120GB           | 1         | 1      | 3.13%   |
| Seagate ST320LM001 HN-M320MBB 320GB | 1         | 1      | 3.13%   |
| Seagate ST1000LM048-2E7172 1TB      | 1         | 1      | 3.13%   |
| Seagate ST1000LM025 HN-M101ABB 1TB  | 1         | 1      | 3.13%   |
| LITEON LJH-64V2G-11 M.2 2260 64GB   | 1         | 1      | 3.13%   |
| Kingston HyperX Fury 3D 240GB       | 1         | 1      | 3.13%   |
| Hitachi HTS547550A9E384 500GB       | 1         | 1      | 3.13%   |
| Hitachi HTS545050B9A300 500GB       | 1         | 1      | 3.13%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 12        | 13     | 37.5%   |
| Toshiba             | 10        | 11     | 31.25%  |
| WDC                 | 3         | 3      | 9.38%   |
| Samsung Electronics | 2         | 2      | 6.25%   |
| Hitachi             | 2         | 2      | 6.25%   |
| SK hynix            | 1         | 1      | 3.13%   |
| LITEON              | 1         | 1      | 3.13%   |
| Kingston            | 1         | 1      | 3.13%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 12        | 13     | 41.38%  |
| Toshiba             | 10        | 11     | 34.48%  |
| WDC                 | 3         | 3      | 10.34%  |
| Samsung Electronics | 2         | 2      | 6.9%    |
| Hitachi             | 2         | 2      | 6.9%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 25        | 31     | 89.29%  |
| SSD  | 3         | 3      | 10.71%  |

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
| Works    | 94        | 132    | 72.31%  |
| Malfunc  | 28        | 34     | 21.54%  |
| Detected | 7         | 9      | 5.38%   |
| Failed   | 1         | 1      | 0.77%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 113       | 74.83%  |
| ADATA Technology               | 9         | 5.96%   |
| AMD                            | 7         | 4.64%   |
| Solid State Storage Technology | 4         | 2.65%   |
| Samsung Electronics            | 4         | 2.65%   |
| Kingston Technology Company    | 3         | 1.99%   |
| Nvidia                         | 2         | 1.32%   |
| Toshiba                        | 1         | 0.66%   |
| SK hynix                       | 1         | 0.66%   |
| Silicon Motion                 | 1         | 0.66%   |
| Realtek Semiconductor          | 1         | 0.66%   |
| Phison Electronics             | 1         | 0.66%   |
| Micron/Crucial Technology      | 1         | 0.66%   |
| MAXIO Technology (Hangzhou)    | 1         | 0.66%   |
| KIOXIA                         | 1         | 0.66%   |
| Biwin Storage Technology       | 1         | 0.66%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 19        | 12.03%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 19        | 12.03%  |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 10        | 6.33%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 10        | 6.33%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                           | 9         | 5.7%    |
| ADATA IM2P33F8 series NVMe SSD (DRAM-less)                                   | 6         | 3.8%    |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                               | 4         | 2.53%   |
| Intel Tiger Lake-LP SATA Controller                                          | 4         | 2.53%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                            | 4         | 2.53%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                               | 4         | 2.53%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller               | 4         | 2.53%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                            | 4         | 2.53%   |
| Intel Volume Management Device NVMe RAID Controller                          | 3         | 1.9%    |
| Intel Comet Lake SATA AHCI Controller                                        | 3         | 1.9%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]        | 3         | 1.9%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                | 3         | 1.9%    |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                | 2         | 1.27%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                       | 2         | 1.27%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller     | 2         | 1.27%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                            | 2         | 1.27%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                       | 2         | 1.27%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                             | 2         | 1.27%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                | 2         | 1.27%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]              | 2         | 1.27%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]              | 2         | 1.27%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller               | 2         | 1.27%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                         | 2         | 1.27%   |
| AMD FCH SATA Controller [AHCI mode]                                          | 2         | 1.27%   |
| Toshiba BG3 x2 NVMe SSD Controller (DRAM-less)                               | 1         | 0.63%   |
| SK hynix BC511 NVMe SSD                                                      | 1         | 0.63%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers            | 1         | 0.63%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                | 1         | 0.63%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                | 1         | 0.63%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                               | 1         | 0.63%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                  | 1         | 0.63%   |
| Realtek RTS5763DL NVMe SSD Controller (DRAM-less)                            | 1         | 0.63%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                          | 1         | 0.63%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                     | 1         | 0.63%   |
| Nvidia MCP79 AHCI Controller                                                 | 1         | 0.63%   |
| Micron/Crucial P1 NVMe PCIe SSD[Frampton]                                    | 1         | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 113       | 72.9%   |
| NVMe | 28        | 18.06%  |
| RAID | 7         | 4.52%   |
| IDE  | 7         | 4.52%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 117       | 90.7%   |
| AMD     | 11        | 8.53%   |
| Unknown | 1         | 0.78%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i5-3320M CPU @ 2.60GHz       | 5         | 3.88%   |
| Intel Core i3-4005U CPU @ 1.70GHz       | 5         | 3.88%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 4         | 3.1%    |
| Intel CPU Version                       | 3         | 2.33%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 3         | 2.33%   |
| Intel Core i5-3337U CPU @ 1.80GHz       | 3         | 2.33%   |
| Intel Core i5-2410M CPU @ 2.30GHz       | 3         | 2.33%   |
| Intel Core i3-6006U CPU @ 2.00GHz       | 3         | 2.33%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 3         | 2.33%   |
| Intel Genuine CPU                       | 2         | 1.55%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 2         | 1.55%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 2         | 1.55%   |
| Intel Core i7-5600U CPU @ 2.60GHz       | 2         | 1.55%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 2         | 1.55%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 2         | 1.55%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 2         | 1.55%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 2         | 1.55%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz      | 2         | 1.55%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 2         | 1.55%   |
| Intel Core i3-6100U CPU @ 2.30GHz       | 2         | 1.55%   |
| Intel Core i3-3217U CPU @ 1.80GHz       | 2         | 1.55%   |
| Intel Core i3-2330M CPU @ 2.20GHz       | 2         | 1.55%   |
| Intel Core i3-2310M CPU @ 2.10GHz       | 2         | 1.55%   |
| Intel Celeron CPU N3350 @ 1.10GHz       | 2         | 1.55%   |
| Intel Pentium M                         | 1         | 0.78%   |
| Intel Pentium CPU P6200 @ 2.13GHz       | 1         | 0.78%   |
| Intel Pentium CPU N3540 @ 2.16GHz       | 1         | 0.78%   |
| Intel Pentium CPU G630 @ 2.70GHz        | 1         | 0.78%   |
| Intel Pentium CPU 5405U @ 2.30GHz       | 1         | 0.78%   |
| Intel Core M-5Y10c CPU @ 0.80GHz        | 1         | 0.78%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 1         | 0.78%   |
| Intel Core i7-8665U CPU @ 1.90GHz       | 1         | 0.78%   |
| Intel Core i7-8650U CPU @ 1.90GHz       | 1         | 0.78%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 1         | 0.78%   |
| Intel Core i7-7600U CPU @ 2.80GHz       | 1         | 0.78%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 1         | 0.78%   |
| Intel Core i7-5500U CPU @ 2.40GHz       | 1         | 0.78%   |
| Intel Core i7-3632QM CPU @ 2.20GHz      | 1         | 0.78%   |
| Intel Core i7-2630QM CPU @ 2.00GHz      | 1         | 0.78%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 1         | 0.78%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 45        | 34.88%  |
| Intel Core i3    | 20        | 15.5%   |
| Intel Core i7    | 18        | 13.95%  |
| Other            | 10        | 7.75%   |
| Intel Celeron    | 10        | 7.75%   |
| Intel Core 2 Duo | 5         | 3.88%   |
| Intel Pentium    | 4         | 3.1%    |
| AMD Ryzen 7      | 3         | 2.33%   |
| Intel Genuine    | 2         | 1.55%   |
| Intel Atom       | 2         | 1.55%   |
| AMD E1           | 2         | 1.55%   |
| Intel Pentium M  | 1         | 0.78%   |
| Intel Core M     | 1         | 0.78%   |
| AMD Ryzen 5      | 1         | 0.78%   |
| AMD Ryzen 3      | 1         | 0.78%   |
| AMD E            | 1         | 0.78%   |
| AMD C-60         | 1         | 0.78%   |
| AMD C-50         | 1         | 0.78%   |
| AMD Athlon II    | 1         | 0.78%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 87        | 67.44%  |
| 4       | 25        | 19.38%  |
| Unknown | 7         | 5.43%   |
| 6       | 4         | 3.1%    |
| 8       | 3         | 2.33%   |
| 16      | 1         | 0.78%   |
| 12      | 1         | 0.78%   |
| 1       | 1         | 0.78%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 124       | 96.12%  |
| 2       | 3         | 2.33%   |
| Unknown | 2         | 1.55%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 92        | 71.32%  |
| 1       | 30        | 23.26%  |
| Unknown | 7         | 5.43%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 23        | 17.83%  |
| IvyBridge     | 17        | 13.18%  |
| SandyBridge   | 16        | 12.4%   |
| Haswell       | 10        | 7.75%   |
| Skylake       | 9         | 6.98%   |
| Broadwell     | 9         | 6.98%   |
| Westmere      | 6         | 4.65%   |
| Penryn        | 6         | 4.65%   |
| Bobcat        | 5         | 3.88%   |
| Unknown       | 5         | 3.88%   |
| TigerLake     | 4         | 3.1%    |
| Zen+          | 3         | 2.33%   |
| Core          | 3         | 2.33%   |
| Silvermont    | 2         | 1.55%   |
| IceLake       | 2         | 1.55%   |
| Goldmont plus | 2         | 1.55%   |
| Goldmont      | 2         | 1.55%   |
| CometLake     | 2         | 1.55%   |
| Bonnell       | 2         | 1.55%   |
| K10           | 1         | 0.78%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 112       | 75.17%  |
| Nvidia | 23        | 15.44%  |
| AMD    | 14        | 9.4%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                          | 17        | 11.11%  |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 15        | 9.8%    |
| Intel Haswell-ULT Integrated Graphics Controller                          | 10        | 6.54%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 8         | 5.23%   |
| Intel HD Graphics 5500                                                    | 8         | 5.23%   |
| Intel UHD Graphics 620                                                    | 7         | 4.58%   |
| Intel Core Processor Integrated Graphics Controller                       | 6         | 3.92%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 4         | 2.61%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 4         | 2.61%   |
| Intel HD Graphics 620                                                     | 4         | 2.61%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 3         | 1.96%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)       | 3         | 1.96%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)         | 3         | 1.96%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 3         | 1.96%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 3         | 1.96%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 3         | 1.96%   |
| Nvidia GP108M [GeForce MX250]                                             | 2         | 1.31%   |
| Nvidia GM108M [GeForce MX130]                                             | 2         | 1.31%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 2         | 1.31%   |
| Intel HD Graphics 500                                                     | 2         | 1.31%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 2         | 1.31%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 2         | 1.31%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 2         | 1.31%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 2         | 1.31%   |
| AMD Wrestler [Radeon HD 7310]                                             | 2         | 1.31%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 1         | 0.65%   |
| Nvidia MCP89 [GeForce 320M]                                               | 1         | 0.65%   |
| Nvidia GP108M [GeForce MX230]                                             | 1         | 0.65%   |
| Nvidia GP108M [GeForce MX150]                                             | 1         | 0.65%   |
| Nvidia GM108M [GeForce MX110]                                             | 1         | 0.65%   |
| Nvidia GM108M [GeForce 940MX]                                             | 1         | 0.65%   |
| Nvidia GM108M [GeForce 930M]                                              | 1         | 0.65%   |
| Nvidia GM107M [GeForce GTX 950M]                                          | 1         | 0.65%   |
| Nvidia GK208M [GeForce GT 740M]                                           | 1         | 0.65%   |
| Nvidia GK208M [GeForce GT 735M]                                           | 1         | 0.65%   |
| Nvidia GK208BM [GeForce 920M]                                             | 1         | 0.65%   |
| Nvidia GF119M [GeForce 410M]                                              | 1         | 0.65%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]      | 1         | 0.65%   |
| Nvidia GA107BM / GN20-P0-R-K2 [GeForce RTX 3050 6GB Laptop GPU]           | 1         | 0.65%   |
| Nvidia C79 [GeForce 9400M]                                                | 1         | 0.65%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 83        | 64.34%  |
| Intel + Nvidia | 19        | 14.73%  |
| 1 x AMD        | 12        | 9.3%    |
| 2 x Intel      | 8         | 6.2%    |
| 1 x Nvidia     | 4         | 3.1%    |
| Intel + AMD    | 2         | 1.55%   |
| Other          | 1         | 0.78%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 120       | 92.31%  |
| Proprietary | 6         | 4.62%   |
| Unknown     | 4         | 3.08%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 120       | 92.31%  |
| 0.01-0.5   | 6         | 4.62%   |
| 3.01-4.0   | 2         | 1.54%   |
| 5.01-6.0   | 1         | 0.77%   |
| 1.01-2.0   | 1         | 0.77%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 33        | 31.13%  |
| BOE                     | 18        | 16.98%  |
| LG Display              | 15        | 14.15%  |
| Chimei Innolux          | 11        | 10.38%  |
| Samsung Electronics     | 5         | 4.72%   |
| InfoVision              | 4         | 3.77%   |
| Lenovo                  | 3         | 2.83%   |
| Goldstar                | 3         | 2.83%   |
| Dell                    | 3         | 2.83%   |
| AOC                     | 3         | 2.83%   |
| Apple                   | 2         | 1.89%   |
| Philips                 | 1         | 0.94%   |
| PANDA                   | 1         | 0.94%   |
| MTD                     | 1         | 0.94%   |
| JDI                     | 1         | 0.94%   |
| Hewlett-Packard         | 1         | 0.94%   |
| Chi Mei Optoelectronics | 1         | 0.94%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD0385 1366x768 310x170mm 13.9-inch           | 4         | 3.77%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 340x190mm 15.3-inch         | 4         | 3.77%   |
| AU Optronics LCD Monitor AUO303C 1366x768 310x170mm 13.9-inch         | 3         | 2.83%   |
| LG Display LCD Monitor LGD0458 1366x768 310x170mm 13.9-inch           | 2         | 1.89%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch          | 2         | 1.89%   |
| BOE LCD Monitor BOE08CD 1366x768 340x190mm 15.3-inch                  | 2         | 1.89%   |
| BOE LCD Monitor BOE0757 1366x768 340x190mm 15.3-inch                  | 2         | 1.89%   |
| BOE LCD Monitor BOE05EF 1366x768 310x170mm 13.9-inch                  | 2         | 1.89%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch         | 2         | 1.89%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 340x190mm 15.3-inch         | 2         | 1.89%   |
| AU Optronics LCD Monitor AUO263D 1920x1080 310x170mm 13.9-inch        | 2         | 1.89%   |
| AU Optronics LCD Monitor AUO183C 1366x768 310x170mm 13.9-inch         | 2         | 1.89%   |
| AOC T2242we AOC2242 1920x1080 480x270mm 21.7-inch                     | 2         | 1.89%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 330x210mm 15.4-inch  | 1         | 0.94%   |
| Samsung Electronics LCD Monitor SEC414C 1366x768 310x170mm 13.9-inch  | 1         | 0.94%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 340x190mm 15.3-inch  | 1         | 0.94%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 340x190mm 15.3-inch | 1         | 0.94%   |
| Samsung Electronics LCD Monitor SAM0D4F 1920x1080 890x500mm 40.2-inch | 1         | 0.94%   |
| Philips PHL 193V5 PHLC0CD 1366x768 410x230mm 18.5-inch                | 1         | 0.94%   |
| PANDA LCD Monitor NCP0004 1920x1080 290x170mm 13.2-inch               | 1         | 0.94%   |
| MTD LCD Monitor MTD0001 1280x800 300x190mm 14.0-inch                  | 1         | 0.94%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 340x190mm 15.3-inch         | 1         | 0.94%   |
| LG Display LCD Monitor LGD05B1 1920x1080 310x170mm 13.9-inch          | 1         | 0.94%   |
| LG Display LCD Monitor LGD053C 1920x1080 310x170mm 13.9-inch          | 1         | 0.94%   |
| LG Display LCD Monitor LGD0505 1366x768 340x190mm 15.3-inch           | 1         | 0.94%   |
| LG Display LCD Monitor LGD03ED 1366x768 280x160mm 12.7-inch           | 1         | 0.94%   |
| LG Display LCD Monitor LGD03B7 1366x768 310x170mm 13.9-inch           | 1         | 0.94%   |
| LG Display LCD Monitor LGD02D3 1366x768 280x160mm 12.7-inch           | 1         | 0.94%   |
| Lenovo LEN X24A LEN60CF 1920x1080 530x300mm 24.0-inch                 | 1         | 0.94%   |
| Lenovo LCD Monitor LEN4035 1280x800 300x190mm 14.0-inch               | 1         | 0.94%   |
| Lenovo LCD Monitor LEN4031 1280x800 300x190mm 14.0-inch               | 1         | 0.94%   |
| JDI GPD1001H JDI0031 2560x1600 890x500mm 40.2-inch                    | 1         | 0.94%   |
| InfoVision LCD Monitor IVO057D 1920x1080 310x170mm 13.9-inch          | 1         | 0.94%   |
| InfoVision LCD Monitor IVO057A 1366x768 310x170mm 13.9-inch           | 1         | 0.94%   |
| InfoVision LCD Monitor IVO0579 1366x768 310x170mm 13.9-inch           | 1         | 0.94%   |
| InfoVision LCD Monitor IVO03F4 1024x600 220x130mm 10.1-inch           | 1         | 0.94%   |
| Hewlett-Packard L200hx HWP298F 1600x900 450x250mm 20.3-inch           | 1         | 0.94%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 580x240mm 24.7-inch           | 1         | 0.94%   |
| Goldstar LG FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch             | 1         | 0.94%   |
| Goldstar LCD Monitor GSM580D 1920x1080 510x290mm 23.1-inch            | 1         | 0.94%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1366x768 (WXGA)  | 61        | 59.8%   |
| 1920x1080 (FHD)  | 28        | 27.45%  |
| 1280x800 (WXGA)  | 4         | 3.92%   |
| 2560x1600        | 2         | 1.96%   |
| 1600x900 (HD+)   | 2         | 1.96%   |
| 1440x900 (WXGA+) | 2         | 1.96%   |
| 2560x1440 (QHD)  | 1         | 0.98%   |
| 2560x1080        | 1         | 0.98%   |
| 1024x600         | 1         | 0.98%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 13     | 44        | 41.51%  |
| 15     | 35        | 33.02%  |
| 12     | 6         | 5.66%   |
| 14     | 5         | 4.72%   |
| 24     | 4         | 3.77%   |
| 21     | 3         | 2.83%   |
| 18     | 2         | 1.89%   |
| 46     | 1         | 0.94%   |
| 40     | 1         | 0.94%   |
| 34     | 1         | 0.94%   |
| 23     | 1         | 0.94%   |
| 20     | 1         | 0.94%   |
| 11     | 1         | 0.94%   |
| 10     | 1         | 0.94%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 76        | 71.7%   |
| 201-300     | 16        | 15.09%  |
| 401-500     | 6         | 5.66%   |
| 501-600     | 5         | 4.72%   |
| 801-900     | 1         | 0.94%   |
| 701-800     | 1         | 0.94%   |
| 1001-1500   | 1         | 0.94%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 87        | 90.63%  |
| 16/10 | 8         | 8.33%   |
| 21/9  | 1         | 1.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 47        | 44.34%  |
| 91-100         | 32        | 30.19%  |
| 201-250        | 8         | 7.55%   |
| 61-70          | 6         | 5.66%   |
| 71-80          | 2         | 1.89%   |
| 141-150        | 2         | 1.89%   |
| 101-110        | 2         | 1.89%   |
| 501-1000       | 2         | 1.89%   |
| 51-60          | 1         | 0.94%   |
| 351-500        | 1         | 0.94%   |
| 41-50          | 1         | 0.94%   |
| 151-200        | 1         | 0.94%   |
| 111-120        | 1         | 0.94%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 61        | 58.65%  |
| 121-160 | 27        | 25.96%  |
| 51-100  | 10        | 9.62%   |
| 161-240 | 5         | 4.81%   |
| 1-50    | 1         | 0.96%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 96        | 72.73%  |
| 0     | 21        | 15.91%  |
| 2     | 15        | 11.36%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 69        | 32.86%  |
| Intel                    | 53        | 25.24%  |
| Qualcomm Atheros         | 51        | 24.29%  |
| Broadcom                 | 15        | 7.14%   |
| Samsung Electronics      | 6         | 2.86%   |
| JMicron Technology       | 6         | 2.86%   |
| Ralink Technology        | 3         | 1.43%   |
| Nvidia                   | 2         | 0.95%   |
| MediaTek                 | 2         | 0.95%   |
| Xiaomi                   | 1         | 0.48%   |
| TP-Link                  | 1         | 0.48%   |
| Marvell Technology Group | 1         | 0.48%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 33        | 13.31%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 28        | 11.29%  |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 17        | 6.85%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 14        | 5.65%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 7         | 2.82%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 7         | 2.82%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                             | 6         | 2.42%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 6         | 2.42%   |
| Intel Wireless 8265 / 8275                                             | 6         | 2.42%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 6         | 2.42%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 4         | 1.61%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 4         | 1.61%   |
| Intel Wireless 7265                                                    | 4         | 1.61%   |
| Intel Wi-Fi 6 AX201                                                    | 4         | 1.61%   |
| Realtek RTL8188EE Wireless Network Adapter                             | 3         | 1.21%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 3         | 1.21%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)         | 3         | 1.21%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 3         | 1.21%   |
| Intel Ethernet Connection (4) I219-LM                                  | 3         | 1.21%   |
| Intel Ethernet Connection (3) I218-LM                                  | 3         | 1.21%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 3         | 1.21%   |
| Broadcom BCM43224 802.11a/b/g/n                                        | 3         | 1.21%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 2         | 0.81%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 2         | 0.81%   |
| Ralink RT2870/RT3070 Wireless Adapter                                  | 2         | 0.81%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 2         | 0.81%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                    | 2         | 0.81%   |
| Intel Wireless 8260                                                    | 2         | 0.81%   |
| Intel Wi-Fi 6 AX200                                                    | 2         | 0.81%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                  | 2         | 0.81%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                        | 2         | 0.81%   |
| Intel Gemini Lake PCH CNVi WiFi                                        | 2         | 0.81%   |
| Intel Ethernet Connection I219-LM                                      | 2         | 0.81%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 2         | 0.81%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                        | 2         | 0.81%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 2         | 0.81%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 2         | 0.81%   |
| Intel Centrino Advanced-N 6200                                         | 2         | 0.81%   |
| Intel 82577LM Gigabit Network Connection                               | 2         | 0.81%   |
| Intel 82566MM Gigabit Network Connection                               | 2         | 0.81%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Qualcomm Atheros      | 50        | 39.06%  |
| Intel                 | 49        | 38.28%  |
| Realtek Semiconductor | 15        | 11.72%  |
| Broadcom              | 9         | 7.03%   |
| Ralink Technology     | 3         | 2.34%   |
| TP-Link               | 1         | 0.78%   |
| MediaTek              | 1         | 0.78%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 17        | 13.18%  |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 14        | 10.85%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 7         | 5.43%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 6         | 4.65%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 6         | 4.65%   |
| Intel Wireless 8265 / 8275                                     | 6         | 4.65%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 6         | 4.65%   |
| Intel Wireless 7265                                            | 4         | 3.1%    |
| Intel Wi-Fi 6 AX201                                            | 4         | 3.1%    |
| Realtek RTL8188EE Wireless Network Adapter                     | 3         | 2.33%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 3         | 2.33%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 3         | 2.33%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 3         | 2.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2         | 1.55%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 2         | 1.55%   |
| Intel Wireless 8260                                            | 2         | 1.55%   |
| Intel Wi-Fi 6 AX200                                            | 2         | 1.55%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 2         | 1.55%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 2         | 1.55%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 2         | 1.55%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2         | 1.55%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 2         | 1.55%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 2         | 1.55%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 2         | 1.55%   |
| Intel Centrino Advanced-N 6200                                 | 2         | 1.55%   |
| Broadcom BCM43225 802.11b/g/n                                  | 2         | 1.55%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1         | 0.78%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 0.78%   |
| Realtek RTL8191SEvA Wireless LAN Controller                    | 1         | 0.78%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                         | 1         | 0.78%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 0.78%   |
| Realtek 8811CU Wireless LAN 802.11ac USB NIC                   | 1         | 0.78%   |
| Ralink RT2501/RT2573 Wireless Adapter                          | 1         | 0.78%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 1         | 0.78%   |
| Intel Wireless 7260                                            | 1         | 0.78%   |
| Intel Wireless 3165                                            | 1         | 0.78%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 1         | 0.78%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 1         | 0.78%   |
| Intel Raptor Lake PCH CNVi WiFi                                | 1         | 0.78%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 1         | 0.78%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 62        | 52.99%  |
| Intel                    | 24        | 20.51%  |
| Broadcom                 | 8         | 6.84%   |
| Samsung Electronics      | 6         | 5.13%   |
| Qualcomm Atheros         | 6         | 5.13%   |
| JMicron Technology       | 6         | 5.13%   |
| Nvidia                   | 2         | 1.71%   |
| Xiaomi                   | 1         | 0.85%   |
| MediaTek                 | 1         | 0.85%   |
| Marvell Technology Group | 1         | 0.85%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 33        | 27.97%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 28        | 23.73%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 7         | 5.93%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 4         | 3.39%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 4         | 3.39%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 3         | 2.54%   |
| Intel Ethernet Connection (4) I219-LM                                  | 3         | 2.54%   |
| Intel Ethernet Connection (3) I218-LM                                  | 3         | 2.54%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 3         | 2.54%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 2         | 1.69%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 2         | 1.69%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                    | 2         | 1.69%   |
| Intel Ethernet Connection I219-LM                                      | 2         | 1.69%   |
| Intel 82577LM Gigabit Network Connection                               | 2         | 1.69%   |
| Intel 82566MM Gigabit Network Connection                               | 2         | 1.69%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 2         | 1.69%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 0.85%   |
| Realtek Killer E2600 GbE Controller                                    | 1         | 0.85%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 1         | 0.85%   |
| Nvidia MCP89 Ethernet                                                  | 1         | 0.85%   |
| Nvidia MCP79 Ethernet                                                  | 1         | 0.85%   |
| MediaTek USB Ethernet-RNDIS                                            | 1         | 0.85%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 1         | 0.85%   |
| Intel I211 Gigabit Network Connection                                  | 1         | 0.85%   |
| Intel Ethernet Controller I225-V                                       | 1         | 0.85%   |
| Intel Ethernet Connection I218-LM                                      | 1         | 0.85%   |
| Intel Ethernet Connection (6) I219-LM                                  | 1         | 0.85%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                   | 1         | 0.85%   |
| Intel 82574L Gigabit Network Connection                                | 1         | 0.85%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 1         | 0.85%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                    | 1         | 0.85%   |
| Broadcom BCM4401-B0 100Base-TX                                         | 1         | 0.85%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 122       | 51.48%  |
| Ethernet | 113       | 47.68%  |
| Unknown  | 2         | 0.84%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 86        | 53.09%  |
| Ethernet | 75        | 46.3%   |
| Unknown  | 1         | 0.62%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 103       | 79.84%  |
| 1     | 23        | 17.83%  |
| 6     | 2         | 1.55%   |
| 8     | 1         | 0.78%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 116       | 89.92%  |
| Yes  | 13        | 10.08%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 35        | 37.23%  |
| Qualcomm Atheros Communications | 30        | 31.91%  |
| Broadcom                        | 7         | 7.45%   |
| Lite-On Technology              | 6         | 6.38%   |
| Apple                           | 6         | 6.38%   |
| Foxconn / Hon Hai               | 4         | 4.26%   |
| Realtek Semiconductor           | 3         | 3.19%   |
| IMC Networks                    | 1         | 1.06%   |
| Dell                            | 1         | 1.06%   |
| Cambridge Silicon Radio         | 1         | 1.06%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 13        | 13.83%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 11        | 11.7%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 7         | 7.45%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 6         | 6.38%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 6         | 6.38%   |
| Qualcomm Atheros Dell Wireless 1703 Bluetooth               | 4         | 4.26%   |
| Apple Bluetooth Host Controller                             | 4         | 4.26%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 3         | 3.19%   |
| Qualcomm Atheros AR3011 Bluetooth                           | 3         | 3.19%   |
| Intel AX201 Bluetooth                                       | 3         | 3.19%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 3         | 3.19%   |
| Realtek Bluetooth Adapter                                   | 2         | 2.13%   |
| Lite-On Qualcomm Atheros Bluetooth                          | 2         | 2.13%   |
| Intel Wireless-AC 3168 Bluetooth                            | 2         | 2.13%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 2         | 2.13%   |
| Intel AX200 Bluetooth                                       | 2         | 2.13%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3011 Bluetooth Adapter | 2         | 2.13%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 2         | 2.13%   |
| Realtek CSR Bluetooth Chip                                  | 1         | 1.06%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1         | 1.06%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 1         | 1.06%   |
| Lite-On MediaTek Bluetooth MT7921                           | 1         | 1.06%   |
| Lite-On Atheros Bluetooth                                   | 1         | 1.06%   |
| Lite-On Atheros AR3012 Bluetooth                            | 1         | 1.06%   |
| Intel AX211 Bluetooth                                       | 1         | 1.06%   |
| Intel AX210 Bluetooth                                       | 1         | 1.06%   |
| IMC Networks Bluetooth Module                               | 1         | 1.06%   |
| Foxconn / Hon Hai Qualcomm Atheros Bluetooth 4.0            | 1         | 1.06%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device             | 1         | 1.06%   |
| Dell Wireless 355 Bluetooth                                 | 1         | 1.06%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 1         | 1.06%   |
| Broadcom BCM2046 Bluetooth Device                           | 1         | 1.06%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 1         | 1.06%   |
| Apple Built-in iSight (no firmware loaded)                  | 1         | 1.06%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 1         | 1.06%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor            | Notebooks | Percent |
|-------------------|-----------|---------|
| Intel             | 112       | 81.75%  |
| AMD               | 11        | 8.03%   |
| Nvidia            | 9         | 6.57%   |
| Texas Instruments | 1         | 0.73%   |
| Plantronics       | 1         | 0.73%   |
| M-Audio           | 1         | 0.73%   |
| Logitech          | 1         | 0.73%   |
| Lenovo            | 1         | 0.73%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 21        | 12.73%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 20        | 12.12%  |
| Intel Haswell-ULT HD Audio Controller                                      | 10        | 6.06%   |
| Intel 8 Series HD Audio Controller                                         | 10        | 6.06%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 10        | 6.06%   |
| Intel Broadwell-U Audio Controller                                         | 9         | 5.45%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 8         | 4.85%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 6         | 3.64%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 5         | 3.03%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 5         | 3.03%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 4         | 2.42%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 4         | 2.42%   |
| AMD Wrestler HDMI Audio                                                    | 4         | 2.42%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 4         | 2.42%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3         | 1.82%   |
| Intel Comet Lake PCH-LP cAVS                                               | 3         | 1.82%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3         | 1.82%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 3         | 1.82%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3         | 1.82%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 1.21%   |
| Intel Comet Lake PCH cAVS                                                  | 2         | 1.21%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 1.21%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 2         | 1.21%   |
| Intel Cannon Lake PCH cAVS                                                 | 2         | 1.21%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2         | 1.21%   |
| AMD FCH Azalia Controller                                                  | 2         | 1.21%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1         | 0.61%   |
| Plantronics Plantronics Blackwire 3210 Series                              | 1         | 0.61%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 0.61%   |
| Nvidia MCP89 High Definition Audio                                         | 1         | 0.61%   |
| Nvidia MCP79 High Definition Audio                                         | 1         | 0.61%   |
| Nvidia GF119 HDMI Audio Controller                                         | 1         | 0.61%   |
| Nvidia GA107 High Definition Audio Controller                              | 1         | 0.61%   |
| M-Audio M-Audio Fast Track Pro                                             | 1         | 0.61%   |
| Logitech H390 headset with microphone                                      | 1         | 0.61%   |
| Lenovo Realtek USB Audio                                                   | 1         | 0.61%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 1         | 0.61%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 1         | 0.61%   |
| Intel CM238 HD Audio Controller                                            | 1         | 0.61%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                               | 1         | 0.61%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Smart               | 35        | 23.81%  |
| Samsung Electronics | 19        | 12.93%  |
| Kingston            | 18        | 12.24%  |
| Unknown             | 12        | 8.16%   |
| SK hynix            | 12        | 8.16%   |
| A-DATA Technology   | 10        | 6.8%    |
| Teikon              | 9         | 6.12%   |
| Smart Brazil        | 6         | 4.08%   |
| High Bridge         | 6         | 4.08%   |
| Crucial             | 4         | 2.72%   |
| Micron Technology   | 3         | 2.04%   |
| Multilaser          | 2         | 1.36%   |
| Apacer              | 2         | 1.36%   |
| Unknown (ABCD)      | 1         | 0.68%   |
| Smart Modular       | 1         | 0.68%   |
| PUSKILL             | 1         | 0.68%   |
| PNY                 | 1         | 0.68%   |
| Nanya Technology    | 1         | 0.68%   |
| Lenovo              | 1         | 0.68%   |
| Kllisre             | 1         | 0.68%   |
| Elpida              | 1         | 0.68%   |
| Unknown             | 1         | 0.68%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 6         | 3.8%    |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s            | 5         | 3.16%   |
| Smart RAM SH564568FH8NZPHSCR 2GB SODIMM DDR3 1334MT/s            | 4         | 2.53%   |
| Smart RAM SH564128FJ8NZRNSDG 4GB SODIMM DDR3 1600MT/s            | 4         | 2.53%   |
| Smart RAM SF4641G8CK8IEHLSBG 8GB SODIMM DDR4 2667MT/s            | 4         | 2.53%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 3         | 1.9%    |
| Smart RAM SH564128FH8NZQNSCG 4GB SODIMM DDR3 1600MT/s            | 3         | 1.9%    |
| Smart RAM SH564128FH8NZPHSCR 4GB SODIMM DDR3 1333MT/s            | 3         | 1.9%    |
| Smart Brazil RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2400MT/s     | 3         | 1.9%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s            | 3         | 1.9%    |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 2         | 1.27%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                      | 2         | 1.27%   |
| Teikon RAM TML251S6EFR8A-PBHC 4GB SODIMM DDR3 1600MT/s           | 2         | 1.27%   |
| Smart RAM SH564128FH8NZPHSCG 4GB SODIMM DDR3 1333MT/s            | 2         | 1.27%   |
| Smart RAM SF564128CJ8NWMNSEG 4GB SODIMM DDR3 1600MT/s            | 2         | 1.27%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.27%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 2         | 1.27%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 2         | 1.27%   |
| Multilaser RAM MS3512NSZ-CA3G1 4GB SODIMM DDR3 1600MT/s          | 2         | 1.27%   |
| Kingston RAM Module 8GB SODIMM DDR3 1600MT/s                     | 2         | 1.27%   |
| Kingston RAM KHX1600C9S3L/8G 8GB SODIMM DDR3 1600MT/s            | 2         | 1.27%   |
| High Bridge RAM HB3SU002GFM8MMB33. 2GB SODIMM DDR3 1334MT/s      | 2         | 1.27%   |
| High Bridge RAM HB3SU002GFM8DMA33. 2GB SODIMM DDR3 1334MT/s      | 2         | 1.27%   |
| A-DATA RAM AL1P32NC8W1-B1AS 8GB SODIMM DDR4 3200MT/s             | 2         | 1.27%   |
| Unknown SODIMM 2048MB SODIMM DDR2 667MT/s                        | 1         | 0.63%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 1         | 0.63%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 0.63%   |
| Unknown RAM Module 4GB SODIMM DDR2 800MT/s                       | 1         | 0.63%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 1         | 0.63%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 0.63%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s | 1         | 0.63%   |
| Teikon RAM TMT451S6BFR8A-PBSC 4096MB SODIMM DDR3 1600MT/s        | 1         | 0.63%   |
| Teikon RAM TMT451S6BFR8A-PBHC 4GB SODIMM DDR3 1333MT/s           | 1         | 0.63%   |
| Teikon RAM TMT425S6CFR6A-PBNJ 2GB SODIMM DDR3 1600MT/s           | 1         | 0.63%   |
| Teikon RAM TMT41GS6BFR8A-PBSC 8GB SODIMM DDR3 1600MT/s           | 1         | 0.63%   |
| Teikon RAM TMT225S6FR8C-H9HC 2GB SODIMM DDR3 1334MT/s            | 1         | 0.63%   |
| Teikon RAM TMA851S6AFR6N-UHHC 4GB SODIMM DDR4 2400MT/s           | 1         | 0.63%   |
| Teikon RAM TMA81GS6AFR8N-UHSC 8GB SODIMM DDR4 2400MT/s           | 1         | 0.63%   |
| Smart RAM SMS4WEC3C0K0446SCG 4GB SODIMM DDR4 3200MT/s            | 1         | 0.63%   |
| Smart RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2133MT/s            | 1         | 0.63%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 70        | 60.34%  |
| DDR4   | 35        | 30.17%  |
| DDR2   | 8         | 6.9%    |
| LPDDR4 | 1         | 0.86%   |
| DDR5   | 1         | 0.86%   |
| DDR    | 1         | 0.86%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 113       | 96.58%  |
| Row Of Chips | 4         | 3.42%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 60        | 44.12%  |
| 8192  | 34        | 25%     |
| 2048  | 30        | 22.06%  |
| 16384 | 10        | 7.35%   |
| 1024  | 2         | 1.47%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 45        | 34.09%  |
| 2400    | 16        | 12.12%  |
| 1333    | 16        | 12.12%  |
| 2667    | 14        | 10.61%  |
| 1334    | 12        | 9.09%   |
| 3200    | 7         | 5.3%    |
| 667     | 5         | 3.79%   |
| 2133    | 4         | 3.03%   |
| 533     | 3         | 2.27%   |
| 1067    | 2         | 1.52%   |
| 800     | 2         | 1.52%   |
| Unknown | 2         | 1.52%   |
| 5600    | 1         | 0.76%   |
| 1867    | 1         | 0.76%   |
| 1066    | 1         | 0.76%   |
| 975     | 1         | 0.76%   |

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
| Chicony Electronics           | 25        | 24.04%  |
| Bison Electronics             | 16        | 15.38%  |
| Microdia                      | 13        | 12.5%   |
| Realtek Semiconductor         | 10        | 9.62%   |
| Silicon Motion                | 9         | 8.65%   |
| Sunplus Innovation Technology | 4         | 3.85%   |
| IMC Networks                  | 4         | 3.85%   |
| Syntek                        | 3         | 2.88%   |
| Suyin                         | 3         | 2.88%   |
| Luxvisions Innotech Limited   | 3         | 2.88%   |
| Unknown                       | 2         | 1.92%   |
| Logitech                      | 2         | 1.92%   |
| Lenovo                        | 2         | 1.92%   |
| Apple                         | 2         | 1.92%   |
| Alcor Micro                   | 2         | 1.92%   |
| Tripath Technology            | 1         | 0.96%   |
| Quanta                        | 1         | 0.96%   |
| Lite-On Technology            | 1         | 0.96%   |
| ALi                           | 1         | 0.96%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                 | 6         | 5.71%   |
| Chicony HD WebCam                             | 6         | 5.71%   |
| Bison Integrated Camera                       | 6         | 5.71%   |
| Silicon Motion Realtek DMFT RGB               | 4         | 3.81%   |
| Microdia Dell Laptop Integrated Webcam HD     | 4         | 3.81%   |
| Syntek EasyCamera                             | 3         | 2.86%   |
| Sunplus Integrated_Webcam_HD                  | 3         | 2.86%   |
| Silicon Motion Realtek USB 2.0 PC Camera      | 3         | 2.86%   |
| Realtek Dell EasyCamera                       | 3         | 2.86%   |
| Luxvisions Innotech Limited Integrated Camera | 3         | 2.86%   |
| Chicony Sony Visual Communication Camera      | 3         | 2.86%   |
| Chicony Integrated Camera                     | 3         | 2.86%   |
| Bison Lenovo EasyCamera                       | 3         | 2.86%   |
| Unknown Realtek PC Camera                     | 2         | 1.9%    |
| Realtek Integrated Webcam                     | 2         | 1.9%    |
| IMC Networks EasyCamera                       | 2         | 1.9%    |
| Chicony Lenovo Integrated Camera (0.3MP)      | 2         | 1.9%    |
| Bison HD Webcam                               | 2         | 1.9%    |
| Alcor Micro Acer Integrated Webcam            | 2         | 1.9%    |
| Tripath USB Camera                            | 1         | 0.95%   |
| Suyin WebCam                                  | 1         | 0.95%   |
| Suyin USB 2.0 UVC 1.3M WebCam                 | 1         | 0.95%   |
| Suyin Integrated_Webcam_HD                    | 1         | 0.95%   |
| Sunplus HD WebCam                             | 1         | 0.95%   |
| Silicon Motion WebCam SCX Series              | 1         | 0.95%   |
| Silicon Motion ATIV VGA Camera                | 1         | 0.95%   |
| Realtek LG Camera                             | 1         | 0.95%   |
| Realtek Integrated_Webcam_FHD                 | 1         | 0.95%   |
| Realtek Integrated_Webcam_8M                  | 1         | 0.95%   |
| Realtek Integrated Webcam HD                  | 1         | 0.95%   |
| Realtek Composite Webcam                      | 1         | 0.95%   |
| Realtek Acer 640 x 480 laptop camera          | 1         | 0.95%   |
| Quanta HD Webcam                              | 1         | 0.95%   |
| Microdia Laptop_Integrated_Webcam_HD          | 1         | 0.95%   |
| Microdia Laptop_Integrated_Webcam_1.3M        | 1         | 0.95%   |
| Microdia Integrated Webcam HD                 | 1         | 0.95%   |
| Logitech Webcam C270                          | 1         | 0.95%   |
| Logitech C922 Pro Stream Webcam               | 1         | 0.95%   |
| Lite-On Integrated Camera                     | 1         | 0.95%   |
| Lenovo Integrated Webcam [R5U877]             | 1         | 0.95%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 6         | 33.33%  |
| Upek                       | 4         | 22.22%  |
| Synaptics                  | 3         | 16.67%  |
| Shenzhen Goodix Technology | 2         | 11.11%  |
| Samsung Electronics        | 1         | 5.56%   |
| Elan Microelectronics      | 1         | 5.56%   |
| Broadcom                   | 1         | 5.56%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 4         | 22.22%  |
| Validity Sensors VFS 5011 fingerprint sensor                                 | 2         | 11.11%  |
| Synaptics Metallica MOH Touch Fingerprint Reader                             | 2         | 11.11%  |
| Shenzhen Goodix Fingerprint Reader                                           | 2         | 11.11%  |
| Validity Sensors VFS5011 Fingerprint Reader                                  | 1         | 5.56%   |
| Validity Sensors VFS495 Fingerprint Reader                                   | 1         | 5.56%   |
| Validity Sensors Synaptics WBDI                                              | 1         | 5.56%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                  | 1         | 5.56%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 1         | 5.56%   |
| Samsung CanvasBio Fingerprint Reader                                         | 1         | 5.56%   |
| Elan Fingerprint Sensor                                                      | 1         | 5.56%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 5.56%   |

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
| 2     | 42        | 32.06%  |
| 1     | 42        | 32.06%  |
| 3     | 17        | 12.98%  |
| 0     | 16        | 12.21%  |
| 4     | 9         | 6.87%   |
| 5     | 5         | 3.82%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 102       | 46.58%  |
| Card reader              | 38        | 17.35%  |
| Bluetooth                | 32        | 14.61%  |
| Net/wireless             | 23        | 10.5%   |
| Fingerprint reader       | 17        | 7.76%   |
| Sound                    | 2         | 0.91%   |
| Network                  | 2         | 0.91%   |
| Storage                  | 1         | 0.46%   |
| Net/ethernet             | 1         | 0.46%   |
| Graphics card            | 1         | 0.46%   |

