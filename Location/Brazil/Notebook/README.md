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

Total: 200

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T460 20FMA00F00    | [69e4dd0799](https://bsd-hardware.info/?probe=69e4dd0799) | Dec 27, 2025 |
| Apple         | MacBook7,1                  | [0ef8b03b05](https://bsd-hardware.info/?probe=0ef8b03b05) | Nov 29, 2025 |
| Unknown       | Unknown                     | [f4459c125f](https://bsd-hardware.info/?probe=f4459c125f) | Oct 31, 2025 |
| Samsung       | N150P                       | [e7870f807d](https://bsd-hardware.info/?probe=e7870f807d) | Oct 21, 2025 |
| Acer          | Aspire A515-45              | [39fdb3cdce](https://bsd-hardware.info/?probe=39fdb3cdce) | Sep 25, 2025 |
| Compaq        | 420                         | [cfd9456ae1](https://bsd-hardware.info/?probe=cfd9456ae1) | Sep 22, 2025 |
| Compaq        | 420                         | [3f0f0af3f2](https://bsd-hardware.info/?probe=3f0f0af3f2) | Sep 20, 2025 |
| Acer          | Aspire E5-574               | [83363756fe](https://bsd-hardware.info/?probe=83363756fe) | Aug 31, 2025 |
| Lenovo        | Unknown                     | [9862e1a37f](https://bsd-hardware.info/?probe=9862e1a37f) | Aug 20, 2025 |
| Lenovo        | Unknown                     | [10b7d0fc70](https://bsd-hardware.info/?probe=10b7d0fc70) | Aug 05, 2025 |
| Dell          | Inspiron 3442               | [aa97e5091d](https://bsd-hardware.info/?probe=aa97e5091d) | Aug 04, 2025 |
| Unknown       | Unknown                     | [56803f24c8](https://bsd-hardware.info/?probe=56803f24c8) | Jul 25, 2025 |
| Unknown       | Unknown                     | [f1d9181e89](https://bsd-hardware.info/?probe=f1d9181e89) | Jul 14, 2025 |
| Lenovo        | ThinkPad X270 20HM004JBR    | [e4715f2336](https://bsd-hardware.info/?probe=e4715f2336) | Jul 06, 2025 |
| Lenovo        | ThinkPad T450 20BUS26K07    | [8c23f251b4](https://bsd-hardware.info/?probe=8c23f251b4) | May 09, 2025 |
| LG Electro... | Z360-G.BG71P1               | [ee691a990c](https://bsd-hardware.info/?probe=ee691a990c) | May 08, 2025 |
| Multilaser    | UB22X                       | [fdc94fecc9](https://bsd-hardware.info/?probe=fdc94fecc9) | May 05, 2025 |
| Positivo      | S14BW01                     | [4eb5ebcf6d](https://bsd-hardware.info/?probe=4eb5ebcf6d) | Apr 22, 2025 |
| Positivo      | N4350                       | [6f75dfb6c3](https://bsd-hardware.info/?probe=6f75dfb6c3) | Apr 13, 2025 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [601968f0ee](https://bsd-hardware.info/?probe=601968f0ee) | Apr 05, 2025 |
| Lenovo        | ThinkPad X270 20HM004JBR    | [2fdca1b5da](https://bsd-hardware.info/?probe=2fdca1b5da) | Apr 01, 2025 |
| Lenovo        | ThinkPad T460 20FN002JUS    | [6cd500ca14](https://bsd-hardware.info/?probe=6cd500ca14) | Mar 28, 2025 |
| Samsung       | 550XDA                      | [6dcf2809ad](https://bsd-hardware.info/?probe=6dcf2809ad) | Mar 24, 2025 |
| Samsung       | 550XDA                      | [eb376da91f](https://bsd-hardware.info/?probe=eb376da91f) | Mar 24, 2025 |
| Lenovo        | ThinkPad T460 20FN002JUS    | [3141e284a2](https://bsd-hardware.info/?probe=3141e284a2) | Feb 22, 2025 |
| Unknown       | Unknown                     | [f2043db6fc](https://bsd-hardware.info/?probe=f2043db6fc) | Feb 09, 2025 |
| Lenovo        | ThinkPad T460 20FN002JUS    | [53362c6f2b](https://bsd-hardware.info/?probe=53362c6f2b) | Feb 08, 2025 |
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
| helloSystem 0.8.1    | 24        | 14.55%  |
| helloSystem 0.7.0    | 12        | 7.27%   |
| helloSystem 0.9.0    | 11        | 6.67%   |
| helloSystem 0.6.0    | 10        | 6.06%   |
| helloSystem 0.4.0    | 10        | 6.06%   |
| helloSystem 0.5.0    | 9         | 5.45%   |
| helloSystem 0.8.0    | 8         | 4.85%   |
| FreeBSD 13.0         | 6         | 3.64%   |
| OpenBSD 7.3          | 5         | 3.03%   |
| FreeBSD 15.0-CURRENT | 3         | 1.82%   |
| FreeBSD 14.1         | 3         | 1.82%   |
| FreeBSD 14.0-CURRENT | 3         | 1.82%   |
| FreeBSD 14.0         | 3         | 1.82%   |
| FreeBSD 13.0-p3      | 3         | 1.82%   |
| FreeBSD 14.3         | 2         | 1.21%   |
| FreeBSD 14.2         | 2         | 1.21%   |
| FreeBSD 14.1-p5      | 2         | 1.21%   |
| FreeBSD 14.0-p5      | 2         | 1.21%   |
| FreeBSD 13.2         | 2         | 1.21%   |
| FreeBSD 13.0-STABLE  | 2         | 1.21%   |
| FreeBSD 12.1         | 2         | 1.21%   |
| OS108 9.99.68        | 1         | 0.61%   |
| OPNsense 25.7.6      | 1         | 0.61%   |
| OPNsense 25.7.3      | 1         | 0.61%   |
| OPNsense 25.7        | 1         | 0.61%   |
| OPNsense 24.7.9      | 1         | 0.61%   |
| OPNsense 24.7.7      | 1         | 0.61%   |
| OPNsense 24.7.12     | 1         | 0.61%   |
| OPNsense 24.1.9      | 1         | 0.61%   |
| OPNsense 23.1.7      | 1         | 0.61%   |
| OPNsense 22.7.4      | 1         | 0.61%   |
| OpenBSD 7.6          | 1         | 0.61%   |
| OpenBSD 7.5          | 1         | 0.61%   |
| OpenBSD 7.2          | 1         | 0.61%   |
| OpenBSD 7.0          | 1         | 0.61%   |
| OpenBSD 6.9          | 1         | 0.61%   |
| NetBSD 10.0          | 1         | 0.61%   |
| helloSystem 0.8.2    | 1         | 0.61%   |
| helloSystem 0.3.0    | 1         | 0.61%   |
| GhostBSD 23.05.22    | 1         | 0.61%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart_bsd/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| helloSystem | 81        | 54.36%  |
| FreeBSD     | 43        | 28.86%  |
| OpenBSD     | 10        | 6.71%   |
| OPNsense    | 7         | 4.7%    |
| GhostBSD    | 4         | 2.68%   |
| OS108       | 1         | 0.67%   |
| NetBSD      | 1         | 0.67%   |
| DragonFly   | 1         | 0.67%   |
| ClonOS      | 1         | 0.67%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 141       | 97.92%  |
| i386  | 2         | 1.39%   |
| arm64 | 1         | 0.69%   |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 86        | 55.84%  |
| Console      | 15        | 9.74%   |
| GNOME        | 9         | 5.84%   |
| XFCE         | 8         | 5.19%   |
| TWM          | 7         | 4.55%   |
| MATE         | 7         | 4.55%   |
| KDE5         | 7         | 4.55%   |
| i3           | 4         | 2.6%    |
| spectrwm     | 2         | 1.3%    |
| Openbox      | 2         | 1.3%    |
| fvwm         | 2         | 1.3%    |
| LXQt         | 1         | 0.65%   |
| Lumina       | 1         | 0.65%   |
| KDE          | 1         | 0.65%   |
| Hyprland     | 1         | 0.65%   |
| EXWM         | 1         | 0.65%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 129       | 87.76%  |
| Console | 16        | 10.88%  |
| Wayland | 2         | 1.36%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SLiM    | 86        | 57.33%  |
| Console | 37        | 24.67%  |
| LightDM | 10        | 6.67%   |
| SDDM    | 9         | 6%      |
| GDM     | 4         | 2.67%   |
| XDM     | 3         | 2%      |
| Ly      | 1         | 0.67%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang            | Notebooks | Percent |
|-----------------|-----------|---------|
| en_US           | 56        | 36.84%  |
| Unknown         | 35        | 23.03%  |
| C               | 26        | 17.11%  |
| pt_BR           | 23        | 15.13%  |
| pt              | 5         | 3.29%   |
| fr_FR           | 5         | 3.29%   |
| en_US.ISO8859-1 | 1         | 0.66%   |
| en_GB           | 1         | 0.66%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 129       | 88.97%  |
| BIOS | 16        | 11.03%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Zfs     | 96        | 63.16%  |
| Cd9660  | 23        | 15.13%  |
| Ufs     | 21        | 13.82%  |
| Ffs     | 11        | 7.24%   |
| Hammer2 | 1         | 0.66%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 140       | 97.22%  |
| MBR     | 3         | 2.08%   |
| Unknown | 1         | 0.69%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 37        | 25.69%  |
| Dell                   | 29        | 20.14%  |
| Acer                   | 17        | 11.81%  |
| Samsung Electronics    | 13        | 9.03%   |
| Unknown                | 7         | 4.86%   |
| Apple                  | 6         | 4.17%   |
| Sony                   | 4         | 2.78%   |
| Positivo               | 4         | 2.78%   |
| Itautec                | 3         | 2.08%   |
| Hewlett-Packard        | 3         | 2.08%   |
| Avell High Performance | 3         | 2.08%   |
| ASUSTek Computer       | 3         | 2.08%   |
| LG Electronics         | 2         | 1.39%   |
| Gateway                | 2         | 1.39%   |
| Compaq                 | 2         | 1.39%   |
| Timi                   | 1         | 0.69%   |
| Semp Toshiba           | 1         | 0.69%   |
| Philco                 | 1         | 0.69%   |
| Notebook               | 1         | 0.69%   |
| Multilaser             | 1         | 0.69%   |
| Intelbras              | 1         | 0.69%   |
| Intel                  | 1         | 0.69%   |
| GPD                    | 1         | 0.69%   |
| Clevo                  | 1         | 0.69%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                                  | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Unknown                                               | 8         | 5.56%   |
| Dell Inspiron 3442                                    | 7         | 4.86%   |
| Dell Inspiron 3421                                    | 3         | 2.08%   |
| Samsung 340XAA/350XAA/550XAA                          | 2         | 1.39%   |
| Samsung 270E5K/270E5Q/271E5K/2570EK                   | 2         | 1.39%   |
| Lenovo IdeaPad S145-15API 81V7                        | 2         | 1.39%   |
| Gateway NE56R                                         | 2         | 1.39%   |
| Dell Latitude 5490                                    | 2         | 1.39%   |
| Apple MacBook7,1                                      | 2         | 1.39%   |
| Acer Aspire E5-574                                    | 2         | 1.39%   |
| Acer Aspire 5750                                      | 2         | 1.39%   |
| Timi TM1703                                           | 1         | 0.69%   |
| Sony VPCYB45JB                                        | 1         | 0.69%   |
| Sony VPCEG17FB                                        | 1         | 0.69%   |
| Sony VPCEG15FB                                        | 1         | 0.69%   |
| Sony SVF14A15CBB                                      | 1         | 0.69%   |
| Semp Toshiba STI NA 1401                              | 1         | 0.69%   |
| Samsung RV411/RV511/E3511/S3511/RV711/E3411           | 1         | 0.69%   |
| Samsung N150P                                         | 1         | 0.69%   |
| Samsung 550XDA                                        | 1         | 0.69%   |
| Samsung 530XBB                                        | 1         | 0.69%   |
| Samsung 530U3C/530U4C/532U3C                          | 1         | 0.69%   |
| Samsung 370E4K                                        | 1         | 0.69%   |
| Samsung 300E5M/300E5L                                 | 1         | 0.69%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV/2470EV/2470EE | 1         | 0.69%   |
| Samsung 275E4E/275E5E                                 | 1         | 0.69%   |
| Positivo S14BW01                                      | 1         | 0.69%   |
| Positivo N4350                                        | 1         | 0.69%   |
| Positivo H14BT58                                      | 1         | 0.69%   |
| Positivo C14CR01                                      | 1         | 0.69%   |
| Philco 10B                                            | 1         | 0.69%   |
| Notebook N85_N87HCHNHZ                                | 1         | 0.69%   |
| Multilaser UB22X                                      | 1         | 0.69%   |
| LG Z360-G.BG71P1                                      | 1         | 0.69%   |
| LG 14Z980-G.BH51P1                                    | 1         | 0.69%   |
| Lenovo V14 G2 ITL 82NM                                | 1         | 0.69%   |
| Lenovo ThinkPad X270 20HM004JBR                       | 1         | 0.69%   |
| Lenovo ThinkPad X250 20CLS2A11K                       | 1         | 0.69%   |
| Lenovo ThinkPad X250 20CLS18S0Z                       | 1         | 0.69%   |
| Lenovo ThinkPad X240 20AMS4V000                       | 1         | 0.69%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Lenovo ThinkPad            | 22        | 15.28%  |
| Dell Inspiron              | 22        | 15.28%  |
| Acer Aspire                | 15        | 10.42%  |
| Lenovo IdeaPad             | 8         | 5.56%   |
| Unknown                    | 8         | 5.56%   |
| Dell Latitude              | 4         | 2.78%   |
| Itautec Infoway            | 3         | 2.08%   |
| Samsung 340XAA             | 2         | 1.39%   |
| Samsung 270E5K             | 2         | 1.39%   |
| Gateway NE56R              | 2         | 1.39%   |
| Dell Vostro                | 2         | 1.39%   |
| Avell High Performance A62 | 2         | 1.39%   |
| Apple MacBook7             | 2         | 1.39%   |
| Acer Nitro                 | 2         | 1.39%   |
| Timi TM1703                | 1         | 0.69%   |
| Sony VPCYB45JB             | 1         | 0.69%   |
| Sony VPCEG17FB             | 1         | 0.69%   |
| Sony VPCEG15FB             | 1         | 0.69%   |
| Sony SVF14A15CBB           | 1         | 0.69%   |
| Semp Toshiba STI           | 1         | 0.69%   |
| Samsung RV411              | 1         | 0.69%   |
| Samsung N150P              | 1         | 0.69%   |
| Samsung 550XDA             | 1         | 0.69%   |
| Samsung 530XBB             | 1         | 0.69%   |
| Samsung 530U3C             | 1         | 0.69%   |
| Samsung 370E4K             | 1         | 0.69%   |
| Samsung 300E5M             | 1         | 0.69%   |
| Samsung 300E5EV            | 1         | 0.69%   |
| Samsung 275E4E             | 1         | 0.69%   |
| Positivo S14BW01           | 1         | 0.69%   |
| Positivo N4350             | 1         | 0.69%   |
| Positivo H14BT58           | 1         | 0.69%   |
| Positivo C14CR01           | 1         | 0.69%   |
| Philco 10B                 | 1         | 0.69%   |
| Notebook N85               | 1         | 0.69%   |
| Multilaser UB22X           | 1         | 0.69%   |
| LG Z360-G.BG71P1           | 1         | 0.69%   |
| LG 14Z980-G.BH51P1         | 1         | 0.69%   |
| Lenovo V14                 | 1         | 0.69%   |
| Lenovo Legion              | 1         | 0.69%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2013    | 18        | 12.5%   |
| 2011    | 15        | 10.42%  |
| 2018    | 14        | 9.72%   |
| 2019    | 12        | 8.33%   |
| 2014    | 10        | 6.94%   |
| 2021    | 9         | 6.25%   |
| 2016    | 9         | 6.25%   |
| 2022    | 8         | 5.56%   |
| 2020    | 8         | 5.56%   |
| 2015    | 8         | 5.56%   |
| 2012    | 7         | 4.86%   |
| 2023    | 5         | 3.47%   |
| 2017    | 5         | 3.47%   |
| 2009    | 4         | 2.78%   |
| 2010    | 3         | 2.08%   |
| 2007    | 3         | 2.08%   |
| Unknown | 3         | 2.08%   |
| 2024    | 2         | 1.39%   |
| 2008    | 1         | 0.69%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 144       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 144       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 67        | 44.37%  |
| 4.01-8.0    | 49        | 32.45%  |
| 16.01-24.0  | 19        | 12.58%  |
| 2.01-3.0    | 5         | 3.31%   |
| 3.01-4.0    | 4         | 2.65%   |
| 24.01-32.0  | 4         | 2.65%   |
| 32.01-64.0  | 2         | 1.32%   |
| 64.01-256.0 | 1         | 0.66%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 93        | 62.84%  |
| 0.51-1.0   | 44        | 29.73%  |
| 2.01-3.0   | 4         | 2.7%    |
| 1.01-2.0   | 3         | 2.03%   |
| Unknown    | 2         | 1.35%   |
| 32.01-64.0 | 1         | 0.68%   |
| 24.01-32.0 | 1         | 0.68%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 101       | 66.89%  |
| 2      | 28        | 18.54%  |
| 0      | 19        | 12.58%  |
| 3      | 2         | 1.32%   |
| 4      | 1         | 0.66%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 97        | 67.36%  |
| Yes       | 47        | 32.64%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 126       | 87.5%   |
| No        | 18        | 12.5%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 136       | 94.44%  |
| No        | 8         | 5.56%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 106       | 73.61%  |
| No        | 38        | 26.39%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Brazil  | 144       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Sao Paulo                 | 18        | 11.61%  |
| Rio de Janeiro            | 10        | 6.45%   |
| Curitiba                  | 8         | 5.16%   |
| Belo Horizonte            | 6         | 3.87%   |
| Manaus                    | 5         | 3.23%   |
| SГЈo Paulo              | 4         | 2.58%   |
| Maceió                   | 4         | 2.58%   |
| Campinas                  | 4         | 2.58%   |
| Blumenau                  | 4         | 2.58%   |
| Fortaleza                 | 3         | 1.94%   |
| Visconde do Rio Branco    | 2         | 1.29%   |
| SÃ£o Paulo              | 2         | 1.29%   |
| Niterói                  | 2         | 1.29%   |
| Maraba                    | 2         | 1.29%   |
| JoГЈo Pessoa            | 2         | 1.29%   |
| Joao Pessoa               | 2         | 1.29%   |
| Ipojuca                   | 2         | 1.29%   |
| Vitória                  | 1         | 0.65%   |
| Vila Velha                | 1         | 0.65%   |
| Uberaba                   | 1         | 0.65%   |
| Trindade                  | 1         | 0.65%   |
| Três Lagoas              | 1         | 0.65%   |
| Teresopolis               | 1         | 0.65%   |
| Teresina                  | 1         | 0.65%   |
| Tangara                   | 1         | 0.65%   |
| SГЈo JosГ© dos Campos | 1         | 0.65%   |
| Sobral                    | 1         | 0.65%   |
| Sete Lagoas               | 1         | 0.65%   |
| Sao Vicente               | 1         | 0.65%   |
| Sao Jose                  | 1         | 0.65%   |
| Sao Jeronimo da Serra     | 1         | 0.65%   |
| Sao Goncalo               | 1         | 0.65%   |
| Sao Bernardo do Campo     | 1         | 0.65%   |
| Santa Maria               | 1         | 0.65%   |
| Rio das Ostras            | 1         | 0.65%   |
| Ribeirao Preto            | 1         | 0.65%   |
| Presidente Prudente       | 1         | 0.65%   |
| Porto UniГЈo            | 1         | 0.65%   |
| Porto Esperidiao          | 1         | 0.65%   |
| Porto Alegre              | 1         | 0.65%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor                             | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| WDC                                | 26        | 29     | 15.57%  |
| Seagate                            | 24        | 29     | 14.37%  |
| Kingston                           | 20        | 23     | 11.98%  |
| Toshiba                            | 14        | 15     | 8.38%   |
| Samsung Electronics                | 13        | 16     | 7.78%   |
| A-DATA Technology                  | 11        | 12     | 6.59%   |
| SanDisk                            | 7         | 7      | 4.19%   |
| Crucial                            | 7         | 11     | 4.19%   |
| SK hynix                           | 4         | 4      | 2.4%    |
| NVMe                               | 4         | 5      | 2.4%    |
| LITEON                             | 4         | 4      | 2.4%    |
| China                              | 4         | 4      | 2.4%    |
| SSSTC                              | 3         | 3      | 1.8%    |
| Hitachi                            | 3         | 3      | 1.8%    |
| Product:              USB DISK 2.0 | 2         | 2      | 1.2%    |
| Patriot                            | 2         | 5      | 1.2%    |
| KingSpec                           | 2         | 3      | 1.2%    |
| Gigabyte Technology                | 2         | 3      | 1.2%    |
| Wodposit                           | 1         | 1      | 0.6%    |
| SMI                                | 1         | 1      | 0.6%    |
| Smart                              | 1         | 1      | 0.6%    |
| Silicon Motion                     | 1         | 1      | 0.6%    |
| Qunion                             | 1         | 1      | 0.6%    |
| PNY                                | 1         | 1      | 0.6%    |
| Phison                             | 1         | 1      | 0.6%    |
| MACROVIP                           | 1         | 1      | 0.6%    |
| LITEONIT                           | 1         | 1      | 0.6%    |
| Lexar                              | 1         | 1      | 0.6%    |
| Hikvision                          | 1         | 1      | 0.6%    |
| Generic                            | 1         | 1      | 0.6%    |
| Biostar                            | 1         | 1      | 0.6%    |
| BHT                                | 1         | 1      | 0.6%    |
| Apple                              | 1         | 1      | 0.6%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Toshiba MQ01ABD100 1TB                              | 4         | 2.34%   |
| Kingston SA400S37960G 960GB                         | 4         | 2.34%   |
| WDC WDS240G2G0A-00JH30 240GB                        | 3         | 1.75%   |
| WDC WD10SPZX-24Z10 1TB                              | 3         | 1.75%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 3         | 1.75%   |
| Samsung HM321HI 320GB                               | 3         | 1.75%   |
| Kingston SA400S37240G 240GB                         | 3         | 1.75%   |
| WDC WDS480G2G0B-00EPW0 480GB                        | 2         | 1.17%   |
| WDC WD10JPVX-75JC3T0 1TB                            | 2         | 1.17%   |
| SSSTC CL1-4D256 256GB                               | 2         | 1.17%   |
| Seagate ST9500325AS 500GB                           | 2         | 1.17%   |
| Seagate ST750LM022 HN-M750MBB 752GB                 | 2         | 1.17%   |
| Seagate ST500LT012-9WS142 500GB                     | 2         | 1.17%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 2         | 1.17%   |
| Seagate ST1000LM048-2E7172 1TB                      | 2         | 1.17%   |
| Seagate ST1000LM035-1RK172 1TB                      | 2         | 1.17%   |
| SanDisk SSD U100 32GB                               | 2         | 1.17%   |
| Samsung HM500JJ 500GB                               | 2         | 1.17%   |
| Product:              USB DISK 2.0 USB DISK 2.0 8GB | 2         | 1.17%   |
| Patriot Burst 120GB                                 | 2         | 1.17%   |
| Kingston SA400S37480G 480GB                         | 2         | 1.17%   |
| Gigabyte GP-GSTFS31120GNTD 120GB                    | 2         | 1.17%   |
| Crucial CT480BX500SSD1 480GB                        | 2         | 1.17%   |
| A-DATA SU810NS38 SATA 256 GB                        | 2         | 1.17%   |
| Wodposit SSD 64GB                                   | 1         | 0.58%   |
| WDC WDS120G1G0A-00SS50 120GB                        | 1         | 0.58%   |
| WDC WDS100T2G0A-00JH30 1TB                          | 1         | 0.58%   |
| WDC WD800BEVS-00RST0 80GB                           | 1         | 0.58%   |
| WDC WD6400BEVT-22A0RT0 640GB                        | 1         | 0.58%   |
| WDC WD5000LPCX-35VHAT0 500GB                        | 1         | 0.58%   |
| WDC WD5000LPCX-24VHAT0 500GB                        | 1         | 0.58%   |
| WDC WD5000B 500GB                                   | 1         | 0.58%   |
| WDC WD20SPZX-22UA7T0 2TB                            | 1         | 0.58%   |
| WDC WD1600BPVT-11JJ5T0 160GB                        | 1         | 0.58%   |
| WDC WD1600BEVS-60RST0 160GB                         | 1         | 0.58%   |
| WDC WD1600BEVS-22VAT0 160GB                         | 1         | 0.58%   |
| WDC WD10SPZX-75Z10T2 1TB                            | 1         | 0.58%   |
| WDC WD10SPZX-75Z10T1 1TB                            | 1         | 0.58%   |
| WDC WD10SPZX-35Z10T0 1TB                            | 1         | 0.58%   |
| WDC WD10JPVX-80JC3T0 1TB                            | 1         | 0.58%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor                             | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate                            | 24        | 29     | 32.88%  |
| WDC                                | 21        | 21     | 28.77%  |
| Toshiba                            | 13        | 14     | 17.81%  |
| Samsung Electronics                | 6         | 7      | 8.22%   |
| Hitachi                            | 3         | 3      | 4.11%   |
| Product:              USB DISK 2.0 | 2         | 2      | 2.74%   |
| NVMe                               | 2         | 3      | 2.74%   |
| SMI                                | 1         | 1      | 1.37%   |
| Generic                            | 1         | 1      | 1.37%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 19        | 22     | 25%     |
| SanDisk             | 7         | 7      | 9.21%   |
| WDC                 | 6         | 8      | 7.89%   |
| Crucial             | 6         | 10     | 7.89%   |
| Samsung Electronics | 5         | 7      | 6.58%   |
| LITEON              | 4         | 4      | 5.26%   |
| China               | 4         | 4      | 5.26%   |
| A-DATA Technology   | 4         | 5      | 5.26%   |
| SK hynix            | 3         | 3      | 3.95%   |
| Patriot             | 2         | 5      | 2.63%   |
| KingSpec            | 2         | 3      | 2.63%   |
| Gigabyte Technology | 2         | 3      | 2.63%   |
| Wodposit            | 1         | 1      | 1.32%   |
| Smart               | 1         | 1      | 1.32%   |
| Qunion              | 1         | 1      | 1.32%   |
| PNY                 | 1         | 1      | 1.32%   |
| NVMe                | 1         | 1      | 1.32%   |
| MACROVIP            | 1         | 1      | 1.32%   |
| LITEONIT            | 1         | 1      | 1.32%   |
| Lexar               | 1         | 1      | 1.32%   |
| Hikvision           | 1         | 1      | 1.32%   |
| Biostar             | 1         | 1      | 1.32%   |
| BHT                 | 1         | 1      | 1.32%   |
| Apple               | 1         | 1      | 1.32%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 68        | 93     | 45.33%  |
| HDD  | 63        | 81     | 42%     |
| NVMe | 19        | 19     | 12.67%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 114       | 174    | 85.71%  |
| NVMe | 19        | 19     | 14.29%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 91        | 130    | 70.54%  |
| 0.51-1.0   | 33        | 39     | 25.58%  |
| 1.01-2.0   | 4         | 4      | 3.1%    |
| 3.01-4.0   | 1         | 1      | 0.78%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 52        | 32.3%   |
| 1-20           | 36        | 22.36%  |
| 251-500        | 26        | 16.15%  |
| 51-100         | 19        | 11.8%   |
| 501-1000       | 12        | 7.45%   |
| 21-50          | 9         | 5.59%   |
| 1001-2000      | 4         | 2.48%   |
| More than 3000 | 1         | 0.62%   |
| 2001-3000      | 1         | 0.62%   |
| Unknown        | 1         | 0.62%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 126       | 84.56%  |
| 21-50    | 11        | 7.38%   |
| 101-250  | 4         | 2.68%   |
| 501-1000 | 3         | 2.01%   |
| 51-100   | 3         | 2.01%   |
| 251-500  | 1         | 0.67%   |
| Unknown  | 1         | 0.67%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB              | 2         | 2      | 5.71%   |
| Seagate ST9500325AS 500GB           | 2         | 2      | 5.71%   |
| Seagate ST500LT012-9WS142 500GB     | 2         | 2      | 5.71%   |
| Samsung Electronics HM321HI 320GB   | 2         | 2      | 5.71%   |
| WDC WD5000B 500GB                   | 1         | 1      | 2.86%   |
| WDC WD1600BEVS-60RST0 160GB         | 1         | 1      | 2.86%   |
| WDC WD10JPVX-75JC3T0 1TB            | 1         | 1      | 2.86%   |
| Toshiba MK6465GSX 640GB             | 1         | 2      | 2.86%   |
| Toshiba MK6034GSX 64GB              | 1         | 1      | 2.86%   |
| Toshiba MK5076GSX 500GB             | 1         | 1      | 2.86%   |
| Toshiba MK3261GSYN 320GB            | 1         | 1      | 2.86%   |
| Toshiba MK2555GSXF 250GB            | 1         | 1      | 2.86%   |
| Toshiba MK1646GSX 160GB             | 1         | 1      | 2.86%   |
| Toshiba MK1252GSX 120GB             | 1         | 1      | 2.86%   |
| Toshiba MK1246GSX 120GB             | 1         | 1      | 2.86%   |
| SK hynix SC210 mSATA 256GB          | 1         | 1      | 2.86%   |
| SK hynix HFS128G39TND-N210A 128GB   | 1         | 1      | 2.86%   |
| Seagate ST9320325ASG 320GB          | 1         | 2      | 2.86%   |
| Seagate ST9320325AS 320GB           | 1         | 1      | 2.86%   |
| Seagate ST9250315AS 250GB           | 1         | 1      | 2.86%   |
| Seagate ST9160314AS 160GB           | 1         | 1      | 2.86%   |
| Seagate ST9120821AS 120GB           | 1         | 1      | 2.86%   |
| Seagate ST320LM001 HN-M320MBB 320GB | 1         | 1      | 2.86%   |
| Seagate ST1000LM048-2E7172 1TB      | 1         | 1      | 2.86%   |
| Seagate ST1000LM025 HN-M101ABB 1TB  | 1         | 1      | 2.86%   |
| Seagate ST1000LM014-1EJ164 1TB      | 1         | 1      | 2.86%   |
| LITEON LJH-64V2G-11 M.2 2260 64GB   | 1         | 1      | 2.86%   |
| Kingston HyperX Fury 3D 240GB       | 1         | 1      | 2.86%   |
| Hitachi HTS547550A9E384 500GB       | 1         | 1      | 2.86%   |
| Hitachi HTS545050B9A300 500GB       | 1         | 1      | 2.86%   |
| Hitachi HTS545025B9SA02 250GB       | 1         | 1      | 2.86%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 13        | 14     | 37.14%  |
| Toshiba             | 10        | 11     | 28.57%  |
| WDC                 | 3         | 3      | 8.57%   |
| Hitachi             | 3         | 3      | 8.57%   |
| SK hynix            | 2         | 2      | 5.71%   |
| Samsung Electronics | 2         | 2      | 5.71%   |
| LITEON              | 1         | 1      | 2.86%   |
| Kingston            | 1         | 1      | 2.86%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 13        | 14     | 41.94%  |
| Toshiba             | 10        | 11     | 32.26%  |
| WDC                 | 3         | 3      | 9.68%   |
| Hitachi             | 3         | 3      | 9.68%   |
| Samsung Electronics | 2         | 2      | 6.45%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 27        | 33     | 87.1%   |
| SSD  | 4         | 4      | 12.9%   |

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
| Works    | 104       | 146    | 72.73%  |
| Malfunc  | 31        | 37     | 21.68%  |
| Detected | 7         | 9      | 4.9%    |
| Failed   | 1         | 1      | 0.7%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 126       | 74.12%  |
| ADATA Technology               | 10        | 5.88%   |
| AMD                            | 7         | 4.12%   |
| Samsung Electronics            | 6         | 3.53%   |
| Solid State Storage Technology | 5         | 2.94%   |
| Kingston Technology Company    | 4         | 2.35%   |
| Nvidia                         | 3         | 1.76%   |
| Toshiba                        | 1         | 0.59%   |
| SK hynix                       | 1         | 0.59%   |
| Silicon Motion                 | 1         | 0.59%   |
| Realtek Semiconductor          | 1         | 0.59%   |
| Phison Electronics             | 1         | 0.59%   |
| Micron/Crucial Technology      | 1         | 0.59%   |
| MAXIO Technology (Hangzhou)    | 1         | 0.59%   |
| KIOXIA                         | 1         | 0.59%   |
| Biwin Storage Technology       | 1         | 0.59%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 21        | 11.86%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 20        | 11.3%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 12        | 6.78%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 10        | 5.65%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 10        | 5.65%   |
| Intel Tiger Lake-LP SATA Controller                                              | 6         | 3.39%   |
| ADATA IM2P33F8 series NVMe SSD (DRAM-less)                                       | 6         | 3.39%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                   | 4         | 2.26%   |
| Intel Volume Management Device NVMe RAID Controller                              | 4         | 2.26%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 4         | 2.26%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 4         | 2.26%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 4         | 2.26%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 4         | 2.26%   |
| Intel Comet Lake SATA AHCI Controller                                            | 3         | 1.69%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 3         | 1.69%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 3         | 1.69%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 3         | 1.69%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 2         | 1.13%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 2         | 1.13%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                         | 2         | 1.13%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                    | 2         | 1.13%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 2         | 1.13%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 2         | 1.13%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 2         | 1.13%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 2         | 1.13%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 2         | 1.13%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 2         | 1.13%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 2         | 1.13%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                  | 2         | 1.13%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                  | 2         | 1.13%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 2         | 1.13%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 2         | 1.13%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 2         | 1.13%   |
| Toshiba BG3 x2 NVMe SSD Controller (DRAM-less)                                   | 1         | 0.56%   |
| Solid State Storage CL4-8D512 NVMe SSD M.2 (DRAM-less)                           | 1         | 0.56%   |
| SK hynix BC511 NVMe SSD                                                          | 1         | 0.56%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 1         | 0.56%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 1         | 0.56%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 0.56%   |
| Realtek RTS5763DL NVMe SSD Controller (DRAM-less)                                | 1         | 0.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 126       | 72.83%  |
| NVMe | 32        | 18.5%   |
| RAID | 8         | 4.62%   |
| IDE  | 7         | 4.05%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 132       | 91.67%  |
| AMD     | 11        | 7.64%   |
| Unknown | 1         | 0.69%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i5-3320M CPU @ 2.60GHz       | 5         | 3.47%   |
| Intel Core i3-4005U CPU @ 1.70GHz       | 5         | 3.47%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 4         | 2.78%   |
| Intel CPU Version                       | 3         | 2.08%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 3         | 2.08%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 3         | 2.08%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 3         | 2.08%   |
| Intel Core i5-3337U CPU @ 1.80GHz       | 3         | 2.08%   |
| Intel Core i5-2410M CPU @ 2.30GHz       | 3         | 2.08%   |
| Intel Core i3-6006U CPU @ 2.00GHz       | 3         | 2.08%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 3         | 2.08%   |
| Intel Genuine CPU                       | 2         | 1.39%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 2         | 1.39%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 2         | 1.39%   |
| Intel Core i7-5600U CPU @ 2.60GHz       | 2         | 1.39%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 2         | 1.39%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 2         | 1.39%   |
| Intel Core i5-5300U CPU @ 2.30GHz       | 2         | 1.39%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 2         | 1.39%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz      | 2         | 1.39%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 2         | 1.39%   |
| Intel Core i3-6100U CPU @ 2.30GHz       | 2         | 1.39%   |
| Intel Core i3-3217U CPU @ 1.80GHz       | 2         | 1.39%   |
| Intel Core i3-2330M CPU @ 2.20GHz       | 2         | 1.39%   |
| Intel Core i3-2310M CPU @ 2.10GHz       | 2         | 1.39%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz    | 2         | 1.39%   |
| Intel Celeron N4020 CPU @ 1.10GHz       | 2         | 1.39%   |
| Intel Celeron CPU N3350 @ 1.10GHz       | 2         | 1.39%   |
| Intel Pentium M                         | 1         | 0.69%   |
| Intel Pentium CPU P6200 @ 2.13GHz       | 1         | 0.69%   |
| Intel Pentium CPU N3700 @ 1.60GHz       | 1         | 0.69%   |
| Intel Pentium CPU N3540 @ 2.16GHz       | 1         | 0.69%   |
| Intel Pentium CPU G630 @ 2.70GHz        | 1         | 0.69%   |
| Intel Pentium CPU 5405U @ 2.30GHz       | 1         | 0.69%   |
| Intel Core M-5Y10c CPU @ 0.80GHz        | 1         | 0.69%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 1         | 0.69%   |
| Intel Core i7-8665U CPU @ 1.90GHz       | 1         | 0.69%   |
| Intel Core i7-8650U CPU @ 1.90GHz       | 1         | 0.69%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 1         | 0.69%   |
| Intel Core i7-7600U CPU @ 2.80GHz       | 1         | 0.69%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 49        | 34.03%  |
| Intel Core i3    | 21        | 14.58%  |
| Intel Core i7    | 19        | 13.19%  |
| Other            | 13        | 9.03%   |
| Intel Celeron    | 13        | 9.03%   |
| Intel Core 2 Duo | 6         | 4.17%   |
| Intel Pentium    | 5         | 3.47%   |
| Intel Atom       | 3         | 2.08%   |
| AMD Ryzen 7      | 3         | 2.08%   |
| Intel Genuine    | 2         | 1.39%   |
| AMD E1           | 2         | 1.39%   |
| Intel Pentium M  | 1         | 0.69%   |
| Intel Core M     | 1         | 0.69%   |
| AMD Ryzen 5      | 1         | 0.69%   |
| AMD Ryzen 3      | 1         | 0.69%   |
| AMD E            | 1         | 0.69%   |
| AMD C-60         | 1         | 0.69%   |
| AMD C-50         | 1         | 0.69%   |
| AMD Athlon II    | 1         | 0.69%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 96        | 66.67%  |
| 4       | 27        | 18.75%  |
| Unknown | 9         | 6.25%   |
| 8       | 4         | 2.78%   |
| 6       | 4         | 2.78%   |
| 20      | 1         | 0.69%   |
| 16      | 1         | 0.69%   |
| 12      | 1         | 0.69%   |
| 1       | 1         | 0.69%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 137       | 95.14%  |
| 2       | 4         | 2.78%   |
| Unknown | 3         | 2.08%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 100       | 69.44%  |
| 1       | 35        | 24.31%  |
| Unknown | 9         | 6.25%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 23        | 15.97%  |
| IvyBridge     | 18        | 12.5%   |
| SandyBridge   | 16        | 11.11%  |
| Haswell       | 12        | 8.33%   |
| Skylake       | 11        | 7.64%   |
| Broadwell     | 10        | 6.94%   |
| Penryn        | 7         | 4.86%   |
| Unknown       | 7         | 4.86%   |
| Westmere      | 6         | 4.17%   |
| TigerLake     | 6         | 4.17%   |
| Bobcat        | 5         | 3.47%   |
| Silvermont    | 4         | 2.78%   |
| Zen+          | 3         | 2.08%   |
| Goldmont plus | 3         | 2.08%   |
| Core          | 3         | 2.08%   |
| Bonnell       | 3         | 2.08%   |
| IceLake       | 2         | 1.39%   |
| Goldmont      | 2         | 1.39%   |
| CometLake     | 2         | 1.39%   |
| K10           | 1         | 0.69%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 126       | 75.45%  |
| Nvidia | 27        | 16.17%  |
| AMD    | 14        | 8.38%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 18        | 10.53%  |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 15        | 8.77%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 12        | 7.02%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                                    | 10        | 5.85%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                                 | 9         | 5.26%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                                 | 7         | 4.09%   |
| Intel Core Processor Integrated Graphics Controller                                      | 6         | 3.51%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 2.34%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 4         | 2.34%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 4         | 2.34%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                                  | 4         | 2.34%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 3         | 1.75%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 3         | 1.75%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 1.75%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 1.75%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 1.75%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 1.75%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 2         | 1.17%   |
| Nvidia GP108M [GeForce MX250]                                                            | 2         | 1.17%   |
| Nvidia GM108M [GeForce MX130]                                                            | 2         | 1.17%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 1.17%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 2         | 1.17%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 1.17%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 1.17%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 1.17%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 1.17%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 1.17%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 2         | 1.17%   |
| Intel Apollo Lake GT1 [HD Graphics 500]                                                  | 2         | 1.17%   |
| AMD Wrestler [Radeon HD 7310]                                                            | 2         | 1.17%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.58%   |
| Nvidia GP108M [GeForce MX230]                                                            | 1         | 0.58%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 0.58%   |
| Nvidia GM108M [GeForce MX110]                                                            | 1         | 0.58%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 0.58%   |
| Nvidia GM108M [GeForce 930M]                                                             | 1         | 0.58%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 1         | 0.58%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 0.58%   |
| Nvidia GK208M [GeForce GT 735M]                                                          | 1         | 0.58%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 1         | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 93        | 64.58%  |
| Intel + Nvidia | 22        | 15.28%  |
| 1 x AMD        | 12        | 8.33%   |
| 2 x Intel      | 9         | 6.25%   |
| 1 x Nvidia     | 5         | 3.47%   |
| Intel + AMD    | 2         | 1.39%   |
| Other          | 1         | 0.69%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 135       | 93.1%   |
| Proprietary | 6         | 4.14%   |
| Unknown     | 4         | 2.76%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 135       | 93.1%   |
| 0.01-0.5   | 6         | 4.14%   |
| 3.01-4.0   | 2         | 1.38%   |
| 5.01-6.0   | 1         | 0.69%   |
| 1.01-2.0   | 1         | 0.69%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 34        | 29.31%  |
| BOE                     | 22        | 18.97%  |
| LG Display              | 16        | 13.79%  |
| Chimei Innolux          | 13        | 11.21%  |
| Samsung Electronics     | 6         | 5.17%   |
| InfoVision              | 4         | 3.45%   |
| AOC                     | 4         | 3.45%   |
| Lenovo                  | 3         | 2.59%   |
| Goldstar                | 3         | 2.59%   |
| Dell                    | 3         | 2.59%   |
| Apple                   | 2         | 1.72%   |
| Philips                 | 1         | 0.86%   |
| PANDA                   | 1         | 0.86%   |
| MTD                     | 1         | 0.86%   |
| JDI                     | 1         | 0.86%   |
| Hewlett-Packard         | 1         | 0.86%   |
| Chi Mei Optoelectronics | 1         | 0.86%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD0385 1366x768 310x170mm 13.9-inch           | 4         | 3.45%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 340x190mm 15.3-inch         | 4         | 3.45%   |
| AU Optronics LCD Monitor AUO303C 1366x768 310x170mm 13.9-inch         | 3         | 2.59%   |
| LG Display LCD Monitor LGD0458 1366x768 310x170mm 13.9-inch           | 2         | 1.72%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch          | 2         | 1.72%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 310x170mm 13.9-inch       | 2         | 1.72%   |
| BOE LCD Monitor BOE0B38 2560x1600 340x210mm 15.7-inch                 | 2         | 1.72%   |
| BOE LCD Monitor BOE08CD 1366x768 340x190mm 15.3-inch                  | 2         | 1.72%   |
| BOE LCD Monitor BOE0812 1920x1080 340x190mm 15.3-inch                 | 2         | 1.72%   |
| BOE LCD Monitor BOE0757 1366x768 340x190mm 15.3-inch                  | 2         | 1.72%   |
| BOE LCD Monitor BOE05EF 1366x768 310x170mm 13.9-inch                  | 2         | 1.72%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch         | 2         | 1.72%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 340x190mm 15.3-inch         | 2         | 1.72%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 310x170mm 13.9-inch         | 2         | 1.72%   |
| AU Optronics LCD Monitor AUO263D 1920x1080 310x170mm 13.9-inch        | 2         | 1.72%   |
| AU Optronics LCD Monitor AUO183C 1366x768 310x170mm 13.9-inch         | 2         | 1.72%   |
| AOC T2242we AOC2242 1920x1080 480x270mm 21.7-inch                     | 2         | 1.72%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 340x190mm 15.3-inch  | 1         | 0.86%   |
| Samsung Electronics LCD Monitor SEC414C 1366x768 310x170mm 13.9-inch  | 1         | 0.86%   |
| Samsung Electronics LCD Monitor SEC3642 1024x600 220x130mm 10.1-inch  | 1         | 0.86%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 340x190mm 15.3-inch  | 1         | 0.86%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 380x210mm 17.1-inch | 1         | 0.86%   |
| Samsung Electronics LCD Monitor SAM0D4F 1920x1080 890x500mm 40.2-inch | 1         | 0.86%   |
| Philips PHL 193V5 PHLC0CD 1366x768 410x230mm 18.5-inch                | 1         | 0.86%   |
| PANDA LCD Monitor NCP0004 1920x1080 290x170mm 13.2-inch               | 1         | 0.86%   |
| MTD LCD Monitor MTD0001 1280x800 300x190mm 14.0-inch                  | 1         | 0.86%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 340x190mm 15.3-inch         | 1         | 0.86%   |
| LG Display LCD Monitor LGD05B1 1920x1080 310x170mm 13.9-inch          | 1         | 0.86%   |
| LG Display LCD Monitor LGD053C 1920x1080 310x170mm 13.9-inch          | 1         | 0.86%   |
| LG Display LCD Monitor LGD0505 1366x768 340x190mm 15.3-inch           | 1         | 0.86%   |
| LG Display LCD Monitor LGD03ED 1366x768 280x160mm 12.7-inch           | 1         | 0.86%   |
| LG Display LCD Monitor LGD03B7 1366x768 310x170mm 13.9-inch           | 1         | 0.86%   |
| LG Display LCD Monitor LGD03B5 1920x1080 290x170mm 13.2-inch          | 1         | 0.86%   |
| LG Display LCD Monitor LGD02D3 1366x768 280x160mm 12.7-inch           | 1         | 0.86%   |
| Lenovo LEN X24A LEN60CF 1920x1080 530x300mm 24.0-inch                 | 1         | 0.86%   |
| Lenovo LCD Monitor LEN4035 1280x800 300x190mm 14.0-inch               | 1         | 0.86%   |
| Lenovo LCD Monitor LEN4031 1280x800 300x190mm 14.0-inch               | 1         | 0.86%   |
| JDI GPD1001H JDI0031 2560x1600 890x500mm 40.2-inch                    | 1         | 0.86%   |
| InfoVision LCD Monitor IVO057D 1920x1080 310x170mm 13.9-inch          | 1         | 0.86%   |
| InfoVision LCD Monitor IVO057A 1366x768 310x170mm 13.9-inch           | 1         | 0.86%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1366x768 (WXGA)  | 64        | 57.14%  |
| 1920x1080 (FHD)  | 33        | 29.46%  |
| 1280x800 (WXGA)  | 4         | 3.57%   |
| 2560x1600        | 3         | 2.68%   |
| 1600x900 (HD+)   | 2         | 1.79%   |
| 1440x900 (WXGA+) | 2         | 1.79%   |
| 1024x600         | 2         | 1.79%   |
| 2560x1440 (QHD)  | 1         | 0.89%   |
| 2560x1080        | 1         | 0.89%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 13     | 49        | 42.24%  |
| 15     | 37        | 31.9%   |
| 12     | 6         | 5.17%   |
| 14     | 5         | 4.31%   |
| 24     | 4         | 3.45%   |
| 21     | 3         | 2.59%   |
| 23     | 2         | 1.72%   |
| 18     | 2         | 1.72%   |
| 10     | 2         | 1.72%   |
| 46     | 1         | 0.86%   |
| 40     | 1         | 0.86%   |
| 34     | 1         | 0.86%   |
| 20     | 1         | 0.86%   |
| 17     | 1         | 0.86%   |
| 11     | 1         | 0.86%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 82        | 70.69%  |
| 201-300     | 18        | 15.52%  |
| 501-600     | 6         | 5.17%   |
| 401-500     | 6         | 5.17%   |
| 801-900     | 1         | 0.86%   |
| 701-800     | 1         | 0.86%   |
| 351-400     | 1         | 0.86%   |
| 1001-1500   | 1         | 0.86%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 96        | 90.57%  |
| 16/10 | 9         | 8.49%   |
| 21/9  | 1         | 0.94%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 51        | 43.97%  |
| 91-100         | 33        | 28.45%  |
| 201-250        | 9         | 7.76%   |
| 61-70          | 6         | 5.17%   |
| 71-80          | 3         | 2.59%   |
| 41-50          | 2         | 1.72%   |
| 141-150        | 2         | 1.72%   |
| 111-120        | 2         | 1.72%   |
| 101-110        | 2         | 1.72%   |
| 501-1000       | 2         | 1.72%   |
| 51-60          | 1         | 0.86%   |
| 351-500        | 1         | 0.86%   |
| 151-200        | 1         | 0.86%   |
| 121-130        | 1         | 0.86%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 65        | 57.02%  |
| 121-160 | 30        | 26.32%  |
| 51-100  | 11        | 9.65%   |
| 161-240 | 7         | 6.14%   |
| 1-50    | 1         | 0.88%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 105       | 70.95%  |
| 0     | 28        | 18.92%  |
| 2     | 15        | 10.14%  |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 78        | 33.05%  |
| Intel                    | 63        | 26.69%  |
| Qualcomm Atheros         | 52        | 22.03%  |
| Broadcom                 | 17        | 7.2%    |
| Samsung Electronics      | 6         | 2.54%   |
| JMicron Technology       | 6         | 2.54%   |
| Ralink Technology        | 3         | 1.27%   |
| Nvidia                   | 3         | 1.27%   |
| MediaTek                 | 2         | 0.85%   |
| Marvell Technology Group | 2         | 0.85%   |
| Xiaomi                   | 1         | 0.42%   |
| TP-Link                  | 1         | 0.42%   |
| ICS Advent               | 1         | 0.42%   |
| D-Link                   | 1         | 0.42%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 38        | 13.77%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 30        | 10.87%  |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 18        | 6.52%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 14        | 5.07%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 7         | 2.54%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 7         | 2.54%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                             | 6         | 2.17%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 6         | 2.17%   |
| Intel Wireless 8265 / 8275                                             | 6         | 2.17%   |
| Intel Wi-Fi 6 AX201                                                    | 6         | 2.17%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 6         | 2.17%   |
| Intel Wireless 7265                                                    | 5         | 1.81%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 4         | 1.45%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 4         | 1.45%   |
| Intel Ethernet Connection (3) I218-LM                                  | 4         | 1.45%   |
| Broadcom BCM43224 802.11a/b/g/n                                        | 4         | 1.45%   |
| Realtek RTL8188EE Wireless Network Adapter                             | 3         | 1.09%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 3         | 1.09%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)         | 3         | 1.09%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 3         | 1.09%   |
| Intel Wireless 8260                                                    | 3         | 1.09%   |
| Intel Ethernet Connection I219-LM                                      | 3         | 1.09%   |
| Intel Ethernet Connection (4) I219-LM                                  | 3         | 1.09%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                        | 3         | 1.09%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 3         | 1.09%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 2         | 0.72%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 2         | 0.72%   |
| Ralink RT2870/RT3070 Wireless Adapter                                  | 2         | 0.72%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 2         | 0.72%   |
| Nvidia MCP89 Ethernet                                                  | 2         | 0.72%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                    | 2         | 0.72%   |
| Intel Wireless 3165                                                    | 2         | 0.72%   |
| Intel Wi-Fi 6 AX200                                                    | 2         | 0.72%   |
| Intel Raptor Lake PCH CNVi WiFi                                        | 2         | 0.72%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                  | 2         | 0.72%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                        | 2         | 0.72%   |
| Intel I211 Gigabit Network Connection                                  | 2         | 0.72%   |
| Intel Gemini Lake PCH CNVi WiFi                                        | 2         | 0.72%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 2         | 0.72%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 2         | 0.72%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 58        | 40.56%  |
| Qualcomm Atheros      | 51        | 35.66%  |
| Realtek Semiconductor | 17        | 11.89%  |
| Broadcom              | 11        | 7.69%   |
| Ralink Technology     | 3         | 2.1%    |
| TP-Link               | 1         | 0.7%    |
| MediaTek              | 1         | 0.7%    |
| D-Link                | 1         | 0.7%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 18        | 12.5%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 14        | 9.72%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 7         | 4.86%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                           | 6         | 4.17%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 6         | 4.17%   |
| Intel Wireless 8265 / 8275                                           | 6         | 4.17%   |
| Intel Wi-Fi 6 AX201                                                  | 6         | 4.17%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 6         | 4.17%   |
| Intel Wireless 7265                                                  | 5         | 3.47%   |
| Broadcom BCM43224 802.11a/b/g/n                                      | 4         | 2.78%   |
| Realtek RTL8188EE Wireless Network Adapter                           | 3         | 2.08%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 3         | 2.08%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)       | 3         | 2.08%   |
| Intel Wireless 8260                                                  | 3         | 2.08%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 3         | 2.08%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 2         | 1.39%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 2         | 1.39%   |
| Intel Wireless 3165                                                  | 2         | 1.39%   |
| Intel Wi-Fi 6 AX200                                                  | 2         | 1.39%   |
| Intel Raptor Lake PCH CNVi WiFi                                      | 2         | 1.39%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                | 2         | 1.39%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                      | 2         | 1.39%   |
| Intel Gemini Lake PCH CNVi WiFi                                      | 2         | 1.39%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 2         | 1.39%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 2         | 1.39%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 2         | 1.39%   |
| Intel Centrino Advanced-N 6235                                       | 2         | 1.39%   |
| Intel Centrino Advanced-N 6200                                       | 2         | 1.39%   |
| Broadcom BCM43225 802.11b/g/n                                        | 2         | 1.39%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]           | 1         | 0.69%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 1         | 0.69%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                           | 1         | 0.69%   |
| Realtek RTL8191SEvA Wireless LAN Controller                          | 1         | 0.69%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                               | 1         | 0.69%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 1         | 0.69%   |
| Realtek Bluetooth Adapter                                            | 1         | 0.69%   |
| Realtek 8811CU Wireless LAN 802.11ac USB NIC                         | 1         | 0.69%   |
| Ralink RT2501/RT2573 Wireless Adapter                                | 1         | 0.69%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330] | 1         | 0.69%   |
| Intel Wireless 7260                                                  | 1         | 0.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 69        | 53.08%  |
| Intel                    | 27        | 20.77%  |
| Broadcom                 | 8         | 6.15%   |
| Samsung Electronics      | 6         | 4.62%   |
| Qualcomm Atheros         | 6         | 4.62%   |
| JMicron Technology       | 6         | 4.62%   |
| Nvidia                   | 3         | 2.31%   |
| Marvell Technology Group | 2         | 1.54%   |
| Xiaomi                   | 1         | 0.77%   |
| MediaTek                 | 1         | 0.77%   |
| ICS Advent               | 1         | 0.77%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 38        | 29.01%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 30        | 22.9%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 7         | 5.34%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 4         | 3.05%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 4         | 3.05%   |
| Intel Ethernet Connection (3) I218-LM                                  | 4         | 3.05%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 3         | 2.29%   |
| Intel Ethernet Connection I219-LM                                      | 3         | 2.29%   |
| Intel Ethernet Connection (4) I219-LM                                  | 3         | 2.29%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 3         | 2.29%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 2         | 1.53%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 2         | 1.53%   |
| Nvidia MCP89 Ethernet                                                  | 2         | 1.53%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                    | 2         | 1.53%   |
| Intel I211 Gigabit Network Connection                                  | 2         | 1.53%   |
| Intel 82577LM Gigabit Network Connection                               | 2         | 1.53%   |
| Intel 82566MM Gigabit Network Connection                               | 2         | 1.53%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 2         | 1.53%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 0.76%   |
| Realtek Killer E2600 GbE Controller                                    | 1         | 0.76%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 1         | 0.76%   |
| Nvidia MCP79 Ethernet                                                  | 1         | 0.76%   |
| MediaTek USB Ethernet-RNDIS                                            | 1         | 0.76%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 1         | 0.76%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 1         | 0.76%   |
| Intel Ethernet Controller I225-V                                       | 1         | 0.76%   |
| Intel Ethernet Connection I218-LM                                      | 1         | 0.76%   |
| Intel Ethernet Connection (6) I219-LM                                  | 1         | 0.76%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection                   | 1         | 0.76%   |
| Intel 82574L Gigabit Network Connection                                | 1         | 0.76%   |
| ICS Advent DM9601 Fast Ethernet Adapter                                | 1         | 0.76%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 1         | 0.76%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                    | 1         | 0.76%   |
| Broadcom BCM4401-B0 100Base-TX                                         | 1         | 0.76%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 136       | 51.52%  |
| Ethernet | 126       | 47.73%  |
| Unknown  | 2         | 0.76%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 93        | 53.45%  |
| Ethernet | 80        | 45.98%  |
| Unknown  | 1         | 0.57%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 114       | 79.17%  |
| 1     | 24        | 16.67%  |
| 6     | 3         | 2.08%   |
| 0     | 2         | 1.39%   |
| 8     | 1         | 0.69%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 128       | 88.28%  |
| Yes  | 17        | 11.72%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 44        | 41.12%  |
| Qualcomm Atheros Communications | 31        | 28.97%  |
| Broadcom                        | 8         | 7.48%   |
| Apple                           | 7         | 6.54%   |
| Lite-On Technology              | 6         | 5.61%   |
| Realtek Semiconductor           | 4         | 3.74%   |
| Foxconn / Hon Hai               | 4         | 3.74%   |
| IMC Networks                    | 1         | 0.93%   |
| Dell                            | 1         | 0.93%   |
| Cambridge Silicon Radio         | 1         | 0.93%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 17        | 15.89%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 12        | 11.21%  |
| Qualcomm Atheros AR9462 Bluetooth                           | 7         | 6.54%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 7         | 6.54%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 6         | 5.61%   |
| Intel AX201 Bluetooth                                       | 5         | 4.67%   |
| Apple Bluetooth Host Controller                             | 5         | 4.67%   |
| Qualcomm Atheros Dell Wireless 1703 Bluetooth               | 4         | 3.74%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 3         | 2.8%    |
| Qualcomm Atheros AR3011 Bluetooth                           | 3         | 2.8%    |
| Intel Centrino Bluetooth Wireless Transceiver               | 3         | 2.8%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 3         | 2.8%    |
| Realtek Bluetooth Adapter                                   | 2         | 1.87%   |
| Lite-On Qualcomm Atheros Bluetooth                          | 2         | 1.87%   |
| Intel Wireless-AC 3168 Bluetooth                            | 2         | 1.87%   |
| Intel AX211 Bluetooth                                       | 2         | 1.87%   |
| Intel AX200 Bluetooth                                       | 2         | 1.87%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3011 Bluetooth Adapter | 2         | 1.87%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 2         | 1.87%   |
| Realtek CSR Bluetooth Chip                                  | 1         | 0.93%   |
| Realtek Bluetooth 4.0 Adapter                               | 1         | 0.93%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1         | 0.93%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 1         | 0.93%   |
| Lite-On MediaTek Bluetooth MT7921                           | 1         | 0.93%   |
| Lite-On Atheros Bluetooth                                   | 1         | 0.93%   |
| Lite-On Atheros AR3012 Bluetooth                            | 1         | 0.93%   |
| Intel AX210 Bluetooth                                       | 1         | 0.93%   |
| IMC Networks Bluetooth Module                               | 1         | 0.93%   |
| Foxconn / Hon Hai Qualcomm Atheros Bluetooth 4.0            | 1         | 0.93%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device             | 1         | 0.93%   |
| Dell Wireless 355 Bluetooth                                 | 1         | 0.93%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 1         | 0.93%   |
| Broadcom BCM2070 Bluetooth                                  | 1         | 0.93%   |
| Broadcom BCM2046 Bluetooth Device                           | 1         | 0.93%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 1         | 0.93%   |
| Apple Built-in iSight (no firmware loaded)                  | 1         | 0.93%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 1         | 0.93%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 126       | 80.77%  |
| Nvidia              | 12        | 7.69%   |
| AMD                 | 11        | 7.05%   |
| Texas Instruments   | 1         | 0.64%   |
| Plantronics         | 1         | 0.64%   |
| M-Audio             | 1         | 0.64%   |
| Logitech            | 1         | 0.64%   |
| Lenovo              | 1         | 0.64%   |
| C-Media Electronics | 1         | 0.64%   |
| -- KTMicro --       | 1         | 0.64%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 23        | 12.3%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 21        | 11.23%  |
| Intel Haswell-ULT HD Audio Controller                                                             | 12        | 6.42%   |
| Intel 8 Series HD Audio Controller                                                                | 12        | 6.42%   |
| Intel Broadwell-U Audio Controller                                                                | 10        | 5.35%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 10        | 5.35%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 9         | 4.81%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 6         | 3.21%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 6         | 3.21%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 5         | 2.67%   |
| AMD Ryzen HD Audio Controller                                                                     | 5         | 2.67%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 2.14%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 4         | 2.14%   |
| AMD Wrestler HDMI Audio                                                                           | 4         | 2.14%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 4         | 2.14%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 1.6%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 1.6%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 1.6%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 1.6%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 1.6%    |
| Nvidia MCP89 High Definition Audio                                                                | 2         | 1.07%   |
| Nvidia GA107 High Definition Audio Controller                                                     | 2         | 1.07%   |
| Intel Raptor Lake-P/U/H cAVS                                                                      | 2         | 1.07%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 1.07%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 1.07%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 1.07%   |
| Intel Cannon Lake PCH cAVS                                                                        | 2         | 1.07%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 1.07%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 1.07%   |
| AMD FCH Azalia Controller                                                                         | 2         | 1.07%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 1         | 0.53%   |
| Plantronics Plantronics Blackwire 3210 Series                                                     | 1         | 0.53%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.53%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.53%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 0.53%   |
| Nvidia AD107 High Definition Audio Controller                                                     | 1         | 0.53%   |
| M-Audio M-Audio Fast Track Pro                                                                    | 1         | 0.53%   |
| Logitech H390 headset with microphone                                                             | 1         | 0.53%   |
| Lenovo Realtek USB Audio                                                                          | 1         | 0.53%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1         | 0.53%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Smart               | 38        | 22.75%  |
| Samsung Electronics | 21        | 12.57%  |
| Kingston            | 19        | 11.38%  |
| Unknown             | 15        | 8.98%   |
| SK hynix            | 13        | 7.78%   |
| A-DATA Technology   | 11        | 6.59%   |
| Teikon              | 10        | 5.99%   |
| Smart Brazil        | 6         | 3.59%   |
| High Bridge         | 6         | 3.59%   |
| Crucial             | 5         | 2.99%   |
| Micron Technology   | 4         | 2.4%    |
| Unknown (ABCD)      | 2         | 1.2%    |
| Multilaser          | 2         | 1.2%    |
| Apacer              | 2         | 1.2%    |
| Unknown             | 2         | 1.2%    |
| Unknown (0x0B5E)    | 1         | 0.6%    |
| Smart Modular       | 1         | 0.6%    |
| PUSKILL             | 1         | 0.6%    |
| PNY                 | 1         | 0.6%    |
| Nanya Technology    | 1         | 0.6%    |
| Lenovo              | 1         | 0.6%    |
| Kllisre             | 1         | 0.6%    |
| Hikvision           | 1         | 0.6%    |
| Elpida              | 1         | 0.6%    |
| Corsair             | 1         | 0.6%    |
| 48spaces            | 1         | 0.6%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 7         | 3.91%   |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s            | 5         | 2.79%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 4         | 2.23%   |
| Smart RAM SH564568FH8NZPHSCR 2GB SODIMM DDR3 1334MT/s            | 4         | 2.23%   |
| Smart RAM SH564128FJ8NZRNSDG 4GB SODIMM DDR3 1600MT/s            | 4         | 2.23%   |
| Smart RAM SF4641G8CK8IEHLSBG 8GB SODIMM DDR4 2667MT/s            | 4         | 2.23%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                      | 3         | 1.68%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 3         | 1.68%   |
| Smart RAM SH564128FH8NZQNSCG 4GB SODIMM DDR3 1600MT/s            | 3         | 1.68%   |
| Smart RAM SH564128FH8NZPHSCR 4GB SODIMM DDR3 1333MT/s            | 3         | 1.68%   |
| Smart Brazil RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2400MT/s     | 3         | 1.68%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s            | 3         | 1.68%   |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 2         | 1.12%   |
| Teikon RAM TML251S6EFR8A-PBHC 4GB SODIMM DDR3 1600MT/s           | 2         | 1.12%   |
| Smart RAM SH564128FH8NZPHSCG 4GB SODIMM DDR3 1333MT/s            | 2         | 1.12%   |
| Smart RAM SF564128CJ8NWMNSEG 4GB SODIMM DDR3 1600MT/s            | 2         | 1.12%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.12%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 2         | 1.12%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 2         | 1.12%   |
| Multilaser RAM MS3512NSZ-CA3G1 4GB SODIMM DDR3 1600MT/s          | 2         | 1.12%   |
| Kingston RAM Module 8GB SODIMM DDR3 1600MT/s                     | 2         | 1.12%   |
| Kingston RAM KHX1600C9S3L/8G 8GB SODIMM DDR3 1600MT/s            | 2         | 1.12%   |
| High Bridge RAM HB3SU002GFM8MMB33. 2GB SODIMM DDR3 1334MT/s      | 2         | 1.12%   |
| High Bridge RAM HB3SU002GFM8DMA33. 2GB SODIMM DDR3 1334MT/s      | 2         | 1.12%   |
| A-DATA RAM AL1P32NC8W1-B1AS 8GB SODIMM DDR4 3200MT/s             | 2         | 1.12%   |
| Unknown                                                          | 2         | 1.12%   |
| Unknown SODIMM 2048MB SODIMM DDR2 667MT/s                        | 1         | 0.56%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 1         | 0.56%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 0.56%   |
| Unknown RAM Module 4GB SODIMM DDR2 800MT/s                       | 1         | 0.56%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 1         | 0.56%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 0.56%   |
| Unknown (0x0B5E) RAM HEMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s  | 1         | 0.56%   |
| Teikon RAM TMT451S6BFR8A-PBSC 4096MB SODIMM DDR3 1600MT/s        | 1         | 0.56%   |
| Teikon RAM TMT451S6BFR8A-PBHC 4GB SODIMM DDR3 1333MT/s           | 1         | 0.56%   |
| Teikon RAM TMT425S6CFR6A-PBNJ 2GB SODIMM DDR3 1600MT/s           | 1         | 0.56%   |
| Teikon RAM TMT41GS6BFR8A-PBSC 8GB SODIMM DDR3 1600MT/s           | 1         | 0.56%   |
| Teikon RAM TMT41GS6BFR8A-PBHJ 8GB SODIMM DDR3 1600MT/s           | 1         | 0.56%   |
| Teikon RAM TMT225S6FR8C-H9HC 2GB SODIMM DDR3 1334MT/s            | 1         | 0.56%   |
| Teikon RAM TMA851S6AFR6N-UHHC 4GB SODIMM DDR4 2400MT/s           | 1         | 0.56%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 79        | 60.31%  |
| DDR4   | 38        | 29.01%  |
| DDR2   | 9         | 6.87%   |
| LPDDR4 | 2         | 1.53%   |
| DDR5   | 2         | 1.53%   |
| DDR    | 1         | 0.76%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 128       | 96.97%  |
| Row Of Chips | 4         | 3.03%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 65        | 42.48%  |
| 8192  | 42        | 27.45%  |
| 2048  | 31        | 20.26%  |
| 16384 | 11        | 7.19%   |
| 1024  | 3         | 1.96%   |
| 32768 | 1         | 0.65%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 53        | 35.57%  |
| 2400    | 19        | 12.75%  |
| 1333    | 16        | 10.74%  |
| 2667    | 15        | 10.07%  |
| 1334    | 12        | 8.05%   |
| 3200    | 9         | 6.04%   |
| 667     | 5         | 3.36%   |
| 2133    | 4         | 2.68%   |
| 1067    | 3         | 2.01%   |
| 800     | 3         | 2.01%   |
| 533     | 3         | 2.01%   |
| 5600    | 2         | 1.34%   |
| Unknown | 2         | 1.34%   |
| 1867    | 1         | 0.67%   |
| 1066    | 1         | 0.67%   |
| 975     | 1         | 0.67%   |

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


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 29        | 25%     |
| Bison Electronics                      | 16        | 13.79%  |
| Microdia                               | 13        | 11.21%  |
| Realtek Semiconductor                  | 12        | 10.34%  |
| Silicon Motion                         | 10        | 8.62%   |
| Sunplus Innovation Technology          | 4         | 3.45%   |
| IMC Networks                           | 4         | 3.45%   |
| Syntek                                 | 3         | 2.59%   |
| Suyin                                  | 3         | 2.59%   |
| Luxvisions Innotech Limited            | 3         | 2.59%   |
| Unknown                                | 2         | 1.72%   |
| Logitech                               | 2         | 1.72%   |
| Lite-On Technology                     | 2         | 1.72%   |
| Lenovo                                 | 2         | 1.72%   |
| Apple                                  | 2         | 1.72%   |
| Alcor Micro                            | 2         | 1.72%   |
| Z-Star Microelectronics                | 1         | 0.86%   |
| Y Media                                | 1         | 0.86%   |
| Tripath Technology                     | 1         | 0.86%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 0.86%   |
| Quanta                                 | 1         | 0.86%   |
| Cheng Uei Precision Industry (Foxlink) | 1         | 0.86%   |
| ALi                                    | 1         | 0.86%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                                 | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                         | 6         | 5.13%   |
| Chicony HD WebCam                                     | 6         | 5.13%   |
| Bison Integrated Camera                               | 6         | 5.13%   |
| Chicony Integrated Camera                             | 5         | 4.27%   |
| Silicon Motion Realtek DMFT RGB                       | 4         | 3.42%   |
| Realtek Dell EasyCamera                               | 4         | 3.42%   |
| Microdia Dell Laptop Integrated Webcam HD             | 4         | 3.42%   |
| Syntek EasyCamera                                     | 3         | 2.56%   |
| Sunplus Integrated_Webcam_HD                          | 3         | 2.56%   |
| Silicon Motion Realtek USB 2.0 PC Camera              | 3         | 2.56%   |
| Luxvisions Innotech Limited Integrated Camera         | 3         | 2.56%   |
| Chicony Sony Visual Communication Camera              | 3         | 2.56%   |
| Bison Lenovo EasyCamera                               | 3         | 2.56%   |
| Unknown Realtek PC Camera                             | 2         | 1.71%   |
| Realtek Integrated Webcam                             | 2         | 1.71%   |
| Lite-On Integrated Camera                             | 2         | 1.71%   |
| IMC Networks EasyCamera                               | 2         | 1.71%   |
| Chicony Lenovo Integrated Camera (0.3MP)              | 2         | 1.71%   |
| Bison HD Webcam                                       | 2         | 1.71%   |
| Alcor Micro Acer Integrated Webcam                    | 2         | 1.71%   |
| Z-Star Webcam                                         | 1         | 0.85%   |
| Y Media USB Camera                                    | 1         | 0.85%   |
| Tripath USB Camera                                    | 1         | 0.85%   |
| Suyin WebCam                                          | 1         | 0.85%   |
| Suyin USB 2.0 UVC 1.3M WebCam                         | 1         | 0.85%   |
| Suyin Integrated_Webcam_HD                            | 1         | 0.85%   |
| Sunplus HD WebCam                                     | 1         | 0.85%   |
| Silicon Motion WebCam SCX Series                      | 1         | 0.85%   |
| Silicon Motion LG HD WebCam                           | 1         | 0.85%   |
| Silicon Motion ATIV VGA Camera                        | 1         | 0.85%   |
| Shenzhen Kingcome Optoelectronic USB2.0 HD UVC WebCam | 1         | 0.85%   |
| Realtek PC Camera                                     | 1         | 0.85%   |
| Realtek LG Camera                                     | 1         | 0.85%   |
| Realtek Integrated_Webcam_FHD                         | 1         | 0.85%   |
| Realtek Integrated_Webcam_8M                          | 1         | 0.85%   |
| Realtek Integrated Webcam HD                          | 1         | 0.85%   |
| Realtek Composite Webcam                              | 1         | 0.85%   |
| Realtek Acer 640 x 480 laptop camera                  | 1         | 0.85%   |
| Quanta HD Webcam                                      | 1         | 0.85%   |
| Microdia Laptop_Integrated_Webcam_HD                  | 1         | 0.85%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 7         | 35%     |
| Upek                       | 4         | 20%     |
| Synaptics                  | 3         | 15%     |
| Shenzhen Goodix Technology | 2         | 10%     |
| Elan Microelectronics      | 2         | 10%     |
| Samsung Electronics        | 1         | 5%      |
| Broadcom                   | 1         | 5%      |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 4         | 20%     |
| Validity Sensors VFS 5011 fingerprint sensor                                 | 3         | 15%     |
| Synaptics Metallica MOH Touch Fingerprint Reader                             | 2         | 10%     |
| Shenzhen Goodix Fingerprint Reader                                           | 2         | 10%     |
| Elan Fingerprint Sensor                                                      | 2         | 10%     |
| Validity Sensors VFS5011 Fingerprint Reader                                  | 1         | 5%      |
| Validity Sensors VFS495 Fingerprint Reader                                   | 1         | 5%      |
| Validity Sensors Synaptics WBDI                                              | 1         | 5%      |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                  | 1         | 5%      |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 1         | 5%      |
| Samsung CanvasBio Fingerprint Reader                                         | 1         | 5%      |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 5%      |

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
| 2     | 49        | 33.11%  |
| 1     | 45        | 30.41%  |
| 3     | 21        | 14.19%  |
| 0     | 19        | 12.84%  |
| 4     | 9         | 6.08%   |
| 5     | 5         | 3.38%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 112       | 46.67%  |
| Card reader              | 41        | 17.08%  |
| Bluetooth                | 36        | 15%     |
| Net/wireless             | 24        | 10%     |
| Fingerprint reader       | 19        | 7.92%   |
| Network                  | 3         | 1.25%   |
| Sound                    | 2         | 0.83%   |
| Storage                  | 1         | 0.42%   |
| Net/ethernet             | 1         | 0.42%   |
| Graphics card            | 1         | 0.42%   |

