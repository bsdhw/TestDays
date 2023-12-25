BSD in Brazil - Tested Hardware & Statistics
--------------------------------------------

A project to collect tested hardware configurations for BSD in Brazil.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe/blob/master/INSTALL.BSD.md) tool:

    hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Brazil/Desktop/README.md) and [notebooks](/Location/Brazil/Notebook/README.md).

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

Total: 466

| Vendor        | Model                       | Form-Factor | Probe                                                     | Date         |
|---------------|-----------------------------|-------------|-----------------------------------------------------------|--------------|
| Apple         | MacBookAir5,2               | Notebook    | [2c652aa0a1](https://bsd-hardware.info/?probe=2c652aa0a1) | Dec 16, 2023 |
| ASRock        | J4005B-ITX                  | Desktop     | [2ffc965b2e](https://bsd-hardware.info/?probe=2ffc965b2e) | Dec 14, 2023 |
| Unknown       | Unknown                     | Desktop     | [0bc43bd220](https://bsd-hardware.info/?probe=0bc43bd220) | Dec 14, 2023 |
| Unknown       | Unknown                     | Desktop     | [79486fa5ff](https://bsd-hardware.info/?probe=79486fa5ff) | Dec 08, 2023 |
| Dell          | 0411GW A02                  | Desktop     | [f2bc8b79b0](https://bsd-hardware.info/?probe=f2bc8b79b0) | Dec 05, 2023 |
| Intel         | Geminilake                  | Desktop     | [59d13c77e8](https://bsd-hardware.info/?probe=59d13c77e8) | Dec 02, 2023 |
| Intel         | DQ77KB AAG81483-501         | Desktop     | [760a22c4b8](https://bsd-hardware.info/?probe=760a22c4b8) | Dec 02, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [a9b3beae66](https://bsd-hardware.info/?probe=a9b3beae66) | Dec 02, 2023 |
| Intel         | DQ77KB AAG81483-501         | Desktop     | [972ad3cb48](https://bsd-hardware.info/?probe=972ad3cb48) | Dec 02, 2023 |
| ASUSTek       | PRIME A520M-E               | Desktop     | [8d7c03be2f](https://bsd-hardware.info/?probe=8d7c03be2f) | Nov 28, 2023 |
| Acer          | Aspire E5-574               | Notebook    | [b11a972371](https://bsd-hardware.info/?probe=b11a972371) | Nov 24, 2023 |
| HP            | 3646h                       | Desktop     | [b3083001a4](https://bsd-hardware.info/?probe=b3083001a4) | Nov 24, 2023 |
| Intel         | NUC62R 2C                   | Mini pc     | [d47608f986](https://bsd-hardware.info/?probe=d47608f986) | Nov 23, 2023 |
| Acer          | Aspire E5-574               | Notebook    | [a4eded7a52](https://bsd-hardware.info/?probe=a4eded7a52) | Nov 22, 2023 |
| Acer          | Aspire ES1-572              | Notebook    | [2aa8175a33](https://bsd-hardware.info/?probe=2aa8175a33) | Nov 17, 2023 |
| Dell          | Inspiron 3442               | Notebook    | [3f63ee5447](https://bsd-hardware.info/?probe=3f63ee5447) | Nov 13, 2023 |
| Dell          | Inspiron N4050              | Notebook    | [9bc3c5e163](https://bsd-hardware.info/?probe=9bc3c5e163) | Nov 05, 2023 |
| Gigabyte      | B450M AORUS ELITE           | Desktop     | [e49d3f40b6](https://bsd-hardware.info/?probe=e49d3f40b6) | Nov 05, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [dfc8115b4a](https://bsd-hardware.info/?probe=dfc8115b4a) | Oct 24, 2023 |
| Intel         | DQ77KB AAG81483-501         | Desktop     | [81e77caff8](https://bsd-hardware.info/?probe=81e77caff8) | Oct 23, 2023 |
| Lenovo        | B40-30 80F1                 | Notebook    | [00c5e6adda](https://bsd-hardware.info/?probe=00c5e6adda) | Oct 03, 2023 |
| ASUSTek       | A88XM-A                     | Desktop     | [a32967cbc5](https://bsd-hardware.info/?probe=a32967cbc5) | Sep 30, 2023 |
| Dell          | 08D89F A00                  | Server      | [6a9c0620a0](https://bsd-hardware.info/?probe=6a9c0620a0) | Sep 28, 2023 |
| Dell          | 0J555H A00                  | Server      | [3c395551d4](https://bsd-hardware.info/?probe=3c395551d4) | Sep 28, 2023 |
| Dell          | 08D89F A00                  | Server      | [de921e42d3](https://bsd-hardware.info/?probe=de921e42d3) | Sep 28, 2023 |
| Dell          | 0VV3F2 A01                  | Server      | [69b9504be5](https://bsd-hardware.info/?probe=69b9504be5) | Sep 25, 2023 |
| GPD           | G1619-04                    | Notebook    | [30ad9b72b5](https://bsd-hardware.info/?probe=30ad9b72b5) | Sep 23, 2023 |
| Dell          | 0VRWRC A01                  | Desktop     | [6c85a42e64](https://bsd-hardware.info/?probe=6c85a42e64) | Sep 19, 2023 |
| Unknown       | Unknown                     | Desktop     | [50f509c032](https://bsd-hardware.info/?probe=50f509c032) | Sep 05, 2023 |
| Dell          | 0JCTF8 A00                  | Desktop     | [a2be5a5f0f](https://bsd-hardware.info/?probe=a2be5a5f0f) | Aug 30, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [e5cae16104](https://bsd-hardware.info/?probe=e5cae16104) | Aug 23, 2023 |
| MSI           | G31M3-L V2                  | Desktop     | [7335b3dea2](https://bsd-hardware.info/?probe=7335b3dea2) | Aug 22, 2023 |
| Daten Tecn... | DH110MXV                    | Desktop     | [bdd9c72e7c](https://bsd-hardware.info/?probe=bdd9c72e7c) | Aug 18, 2023 |
| Dell          | 05FT2M A04                  | Server      | [73afce6eeb](https://bsd-hardware.info/?probe=73afce6eeb) | Aug 17, 2023 |
| ASUSTek       | P5G41T-M LX2/BR             | Desktop     | [f25db83457](https://bsd-hardware.info/?probe=f25db83457) | Aug 15, 2023 |
| Sophos        | SG                          | Firewall    | [5d3b81800b](https://bsd-hardware.info/?probe=5d3b81800b) | Aug 09, 2023 |
| Sophos        | SG                          | Firewall    | [bcb2c49854](https://bsd-hardware.info/?probe=bcb2c49854) | Aug 09, 2023 |
| Intel         | H81                         | Desktop     | [80f40918ce](https://bsd-hardware.info/?probe=80f40918ce) | Aug 07, 2023 |
| Compaq        | Presario CQ-17              | Notebook    | [f97feb2db0](https://bsd-hardware.info/?probe=f97feb2db0) | Aug 04, 2023 |
| Supermicro    | X10SLL-F                    | Server      | [cbc7fc88d0](https://bsd-hardware.info/?probe=cbc7fc88d0) | Aug 03, 2023 |
| Unknown       | Unknown                     | Desktop     | [8b7315305c](https://bsd-hardware.info/?probe=8b7315305c) | Jul 31, 2023 |
| ChangWang     | CW56-58                     | Desktop     | [f418f5407c](https://bsd-hardware.info/?probe=f418f5407c) | Jul 30, 2023 |
| Dell          | 0GDG8Y A02                  | Desktop     | [651f6bf18f](https://bsd-hardware.info/?probe=651f6bf18f) | Jul 28, 2023 |
| Dell          | 0HD5W2 A01                  | Desktop     | [e26ef35879](https://bsd-hardware.info/?probe=e26ef35879) | Jul 28, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [1cd9d4cb7f](https://bsd-hardware.info/?probe=1cd9d4cb7f) | Jul 24, 2023 |
| Dell          | 0TD1J8 A00                  | Desktop     | [c99bc29ce0](https://bsd-hardware.info/?probe=c99bc29ce0) | Jul 24, 2023 |
| Intel         | H55                         | Desktop     | [11c9e5747f](https://bsd-hardware.info/?probe=11c9e5747f) | Jul 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [8ced2a3a4d](https://bsd-hardware.info/?probe=8ced2a3a4d) | Jul 17, 2023 |
| Intel         | H55                         | Desktop     | [da217d0606](https://bsd-hardware.info/?probe=da217d0606) | Jul 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [a9c88b1c80](https://bsd-hardware.info/?probe=a9c88b1c80) | Jul 11, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [c546c0a84f](https://bsd-hardware.info/?probe=c546c0a84f) | Jul 06, 2023 |
| Dell          | Latitude E6420              | Notebook    | [3151e6d3bb](https://bsd-hardware.info/?probe=3151e6d3bb) | Jul 05, 2023 |
| Dell          | 0TW855 A07                  | Server      | [6b0d9156a9](https://bsd-hardware.info/?probe=6b0d9156a9) | Jun 26, 2023 |
| Dell          | Latitude 5490               | Notebook    | [b638c1b2b1](https://bsd-hardware.info/?probe=b638c1b2b1) | Jun 23, 2023 |
| Dell          | 02YRK5 A03                  | Desktop     | [2d631e9745](https://bsd-hardware.info/?probe=2d631e9745) | Jun 23, 2023 |
| HP            | 1000                        | Notebook    | [21faecd7a6](https://bsd-hardware.info/?probe=21faecd7a6) | Jun 23, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [b6e5a7e7bc](https://bsd-hardware.info/?probe=b6e5a7e7bc) | Jun 18, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [2d50927445](https://bsd-hardware.info/?probe=2d50927445) | Jun 18, 2023 |
| Lenovo        | ThinkCentre A70 7099A5P     | Desktop     | [4e827b2cbf](https://bsd-hardware.info/?probe=4e827b2cbf) | Jun 16, 2023 |
| Lenovo        | ThinkCentre A70 7099A5P     | Desktop     | [3d71827388](https://bsd-hardware.info/?probe=3d71827388) | Jun 16, 2023 |
| IBM           | 69Y5698                     | Server      | [9f5eb975e0](https://bsd-hardware.info/?probe=9f5eb975e0) | Jun 16, 2023 |
| Dell          | 053CWD A00                  | Desktop     | [7a5418ac7e](https://bsd-hardware.info/?probe=7a5418ac7e) | Jun 16, 2023 |
| CNCTION-IA... | Unknown                     | Desktop     | [1a0573767e](https://bsd-hardware.info/?probe=1a0573767e) | Jun 16, 2023 |
| Unknown       | Unknown                     | Desktop     | [93dcd13cb6](https://bsd-hardware.info/?probe=93dcd13cb6) | Jun 15, 2023 |
| Dell          | 0HD5W2 A01                  | Desktop     | [a6c6c43f64](https://bsd-hardware.info/?probe=a6c6c43f64) | Jun 13, 2023 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [ffe9b51f78](https://bsd-hardware.info/?probe=ffe9b51f78) | Jun 12, 2023 |
| Lenovo        | B40-30 80F1                 | Notebook    | [769c678314](https://bsd-hardware.info/?probe=769c678314) | Jun 10, 2023 |
| Soyo          | SY-YL B550M                 | Desktop     | [1d1138e3c5](https://bsd-hardware.info/?probe=1d1138e3c5) | Jun 05, 2023 |
| Soyo          | SY-YL B550M                 | Desktop     | [79c6c2a177](https://bsd-hardware.info/?probe=79c6c2a177) | Jun 05, 2023 |
| YANYU         | N39SL                       | Desktop     | [e487646fbf](https://bsd-hardware.info/?probe=e487646fbf) | Jun 05, 2023 |
| Intel         | JSL MRD                     | Desktop     | [f4606f2c25](https://bsd-hardware.info/?probe=f4606f2c25) | Jun 03, 2023 |
| Intel         | JSL MRD                     | Desktop     | [3d5e12d1cf](https://bsd-hardware.info/?probe=3d5e12d1cf) | Jun 03, 2023 |
| Unknown       | Unknown                     | Desktop     | [13c80903b5](https://bsd-hardware.info/?probe=13c80903b5) | May 31, 2023 |
| Intel         | H81                         | Desktop     | [e0e15704fc](https://bsd-hardware.info/?probe=e0e15704fc) | May 29, 2023 |
| Dell          | 0GDG8Y A02                  | Desktop     | [fc6906c72a](https://bsd-hardware.info/?probe=fc6906c72a) | May 27, 2023 |
| Lenovo        | 36C5 SDK0L77767 WIN 3423... | Desktop     | [a19f434ae4](https://bsd-hardware.info/?probe=a19f434ae4) | May 26, 2023 |
| Acer          | Nitro AN515-57              | Notebook    | [c39ea00de5](https://bsd-hardware.info/?probe=c39ea00de5) | May 25, 2023 |
| ASUSTek       | PRIME A520M-E               | Desktop     | [efd50a99b7](https://bsd-hardware.info/?probe=efd50a99b7) | May 23, 2023 |
| ASUSTek       | PRIME A520M-E               | Desktop     | [6e82e43784](https://bsd-hardware.info/?probe=6e82e43784) | May 23, 2023 |
| Unknown       | Unknown                     | Desktop     | [fe3f8769f8](https://bsd-hardware.info/?probe=fe3f8769f8) | May 22, 2023 |
| Sony          | VPCEG15FB                   | Notebook    | [8777493861](https://bsd-hardware.info/?probe=8777493861) | May 21, 2023 |
| Unknown       | Apple MacBook Pro (13-in... | Notebook    | [5e25a49c65](https://bsd-hardware.info/?probe=5e25a49c65) | May 20, 2023 |
| Unknown       | Unknown                     | Desktop     | [d8bec309da](https://bsd-hardware.info/?probe=d8bec309da) | May 16, 2023 |
| Lenovo        | ThinkPad T61 7659AS5        | Notebook    | [7732b2cfa7](https://bsd-hardware.info/?probe=7732b2cfa7) | May 15, 2023 |
| Lenovo        | ThinkPad T61 7659AS5        | Notebook    | [b6071c549a](https://bsd-hardware.info/?probe=b6071c549a) | May 15, 2023 |
| Sony          | SVF14A15CBB                 | Notebook    | [4ada2dca25](https://bsd-hardware.info/?probe=4ada2dca25) | May 14, 2023 |
| Gigabyte      | B250M-Gaming 3-CF           | Desktop     | [2ce057e389](https://bsd-hardware.info/?probe=2ce057e389) | May 14, 2023 |
| Lenovo        | V14 G2 ITL 82NM             | Desktop     | [fa87f4741a](https://bsd-hardware.info/?probe=fa87f4741a) | May 13, 2023 |
| Lenovo        | V14 G2 ITL 82NM             | Desktop     | [bd81294acc](https://bsd-hardware.info/?probe=bd81294acc) | May 13, 2023 |
| Gigabyte      | B250M-Gaming 3-CF           | Desktop     | [cace71018f](https://bsd-hardware.info/?probe=cace71018f) | May 11, 2023 |
| Intel         | HuronRiver Platform         | Notebook    | [83494ffd65](https://bsd-hardware.info/?probe=83494ffd65) | May 11, 2023 |
| Gigabyte      | H61M-DS2H                   | Desktop     | [e1856048c0](https://bsd-hardware.info/?probe=e1856048c0) | May 10, 2023 |
| Gigabyte      | B250M-Gaming 3-CF           | Desktop     | [4353bb0195](https://bsd-hardware.info/?probe=4353bb0195) | May 09, 2023 |
| Intel         | NUC62R 2C                   | Mini pc     | [a1cb2ad4f4](https://bsd-hardware.info/?probe=a1cb2ad4f4) | May 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [ed836ce6e5](https://bsd-hardware.info/?probe=ed836ce6e5) | May 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [15c2e0790b](https://bsd-hardware.info/?probe=15c2e0790b) | Apr 27, 2023 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [b46f671e20](https://bsd-hardware.info/?probe=b46f671e20) | Apr 25, 2023 |
| Lenovo        | V14 G2 ITL 82NM             | Desktop     | [827308827b](https://bsd-hardware.info/?probe=827308827b) | Apr 24, 2023 |
| Dell          | Inspiron 3421               | Notebook    | [ef4870410f](https://bsd-hardware.info/?probe=ef4870410f) | Apr 23, 2023 |
| Lenovo        | V14 G2 ITL 82NM             | Desktop     | [a6141b809a](https://bsd-hardware.info/?probe=a6141b809a) | Apr 21, 2023 |
| Gigabyte      | H61M-S2PH                   | Desktop     | [024173445b](https://bsd-hardware.info/?probe=024173445b) | Apr 18, 2023 |
| Unknown       | Unknown                     | Desktop     | [cff3d92e32](https://bsd-hardware.info/?probe=cff3d92e32) | Apr 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [6d44a8e8c8](https://bsd-hardware.info/?probe=6d44a8e8c8) | Apr 15, 2023 |
| Apple         | MacBook3,1                  | Notebook    | [74986a169a](https://bsd-hardware.info/?probe=74986a169a) | Apr 15, 2023 |
| Samsung       | 370E4K                      | Notebook    | [c363d008bf](https://bsd-hardware.info/?probe=c363d008bf) | Apr 13, 2023 |
| Lenovo        | ThinkPad X230 23257EP       | Notebook    | [e94085cd2d](https://bsd-hardware.info/?probe=e94085cd2d) | Apr 12, 2023 |
| Gigabyte      | B250M-Gaming 3-CF           | Desktop     | [a149d0b4b5](https://bsd-hardware.info/?probe=a149d0b4b5) | Apr 10, 2023 |
| Gigabyte      | B250M-Gaming 3-CF           | Desktop     | [ffbe23b7d8](https://bsd-hardware.info/?probe=ffbe23b7d8) | Apr 09, 2023 |
| Gigabyte      | B250M-Gaming 3-CF           | Desktop     | [592e08cdd2](https://bsd-hardware.info/?probe=592e08cdd2) | Apr 09, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [c98356d42b](https://bsd-hardware.info/?probe=c98356d42b) | Apr 09, 2023 |
| Unknown       | Unknown                     | Desktop     | [4e1d6069e9](https://bsd-hardware.info/?probe=4e1d6069e9) | Apr 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [9cce6d0463](https://bsd-hardware.info/?probe=9cce6d0463) | Apr 03, 2023 |
| ASUSTek       | PRIME A520M-E               | Desktop     | [3592fe0b85](https://bsd-hardware.info/?probe=3592fe0b85) | Apr 03, 2023 |
| Unknown       | Unknown                     | Desktop     | [a0548bbb6e](https://bsd-hardware.info/?probe=a0548bbb6e) | Mar 31, 2023 |
| ASUSTek       | P5G41T-M LX2/BR             | Desktop     | [16d1e0aa3e](https://bsd-hardware.info/?probe=16d1e0aa3e) | Mar 31, 2023 |
| Dell          | 0MX4YF A01                  | Server      | [6a6b7d1e6d](https://bsd-hardware.info/?probe=6a6b7d1e6d) | Mar 29, 2023 |
| ASRock        | H61M-HVS                    | Desktop     | [98777ba333](https://bsd-hardware.info/?probe=98777ba333) | Mar 27, 2023 |
| Lenovo        | ThinkPad T430 2349G5P       | Notebook    | [9ea67d3893](https://bsd-hardware.info/?probe=9ea67d3893) | Mar 27, 2023 |
| Dell          | Inspiron 3442               | Notebook    | [cbb9f6bfbb](https://bsd-hardware.info/?probe=cbb9f6bfbb) | Mar 17, 2023 |
| Positivo      | POS-PIB150DT                | Desktop     | [f0158da9e1](https://bsd-hardware.info/?probe=f0158da9e1) | Mar 17, 2023 |
| Unknown       | SKYBAY                      | Desktop     | [7399558d80](https://bsd-hardware.info/?probe=7399558d80) | Mar 17, 2023 |
| Unknown       | SKYBAY                      | Desktop     | [3fb2d0d992](https://bsd-hardware.info/?probe=3fb2d0d992) | Mar 17, 2023 |
| Lenovo        | ThinkPad X201 36801T6       | Notebook    | [decaf0c347](https://bsd-hardware.info/?probe=decaf0c347) | Mar 17, 2023 |
| Dell          | Inspiron 5557               | Notebook    | [ff199c6d21](https://bsd-hardware.info/?probe=ff199c6d21) | Mar 16, 2023 |
| Samsung       | 275E4E/275E5E               | Notebook    | [dd4f7ef594](https://bsd-hardware.info/?probe=dd4f7ef594) | Mar 15, 2023 |
| T-bao         | MINI PC                     | Desktop     | [d4440566b0](https://bsd-hardware.info/?probe=d4440566b0) | Mar 13, 2023 |
| Positivo      | POS-PIB150DT                | Desktop     | [5f39c02bc9](https://bsd-hardware.info/?probe=5f39c02bc9) | Mar 13, 2023 |
| Intel         | DP55WB AAE64798-207         | Desktop     | [1c8295549c](https://bsd-hardware.info/?probe=1c8295549c) | Mar 10, 2023 |
| HP            | ProLiant DL160 Gen8         | Server      | [43c3eafd9d](https://bsd-hardware.info/?probe=43c3eafd9d) | Mar 07, 2023 |
| Dell          | 06X1TJ A00                  | Desktop     | [ac0118b05e](https://bsd-hardware.info/?probe=ac0118b05e) | Mar 03, 2023 |
| Dell          | 06X1TJ A00                  | Desktop     | [b663ccd3cb](https://bsd-hardware.info/?probe=b663ccd3cb) | Mar 01, 2023 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [a919e85270](https://bsd-hardware.info/?probe=a919e85270) | Feb 28, 2023 |
| Dell          | Inspiron 15 3515            | Notebook    | [b480a98b22](https://bsd-hardware.info/?probe=b480a98b22) | Feb 26, 2023 |
| Samsung       | 270E5K/270E5Q/271E5K/257... | Notebook    | [45549e4faf](https://bsd-hardware.info/?probe=45549e4faf) | Feb 25, 2023 |
| Dell          | 0WR7PY A00                  | Desktop     | [70b222c73b](https://bsd-hardware.info/?probe=70b222c73b) | Feb 23, 2023 |
| Acer          | Aspire E1-421               | Notebook    | [db00abb833](https://bsd-hardware.info/?probe=db00abb833) | Feb 19, 2023 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [fd39a615de](https://bsd-hardware.info/?probe=fd39a615de) | Feb 19, 2023 |
| Gigabyte      | B450M AORUS ELITE           | Desktop     | [6af537ff20](https://bsd-hardware.info/?probe=6af537ff20) | Feb 18, 2023 |
| Lenovo        | ThinkPad T430u 33522D5      | Notebook    | [d5bbbb8cbe](https://bsd-hardware.info/?probe=d5bbbb8cbe) | Feb 17, 2023 |
| ASRock        | A320M-DGS                   | Desktop     | [032d7f0c91](https://bsd-hardware.info/?probe=032d7f0c91) | Feb 17, 2023 |
| Dell          | 0CN7CM A06                  | Server      | [a4e6db54d8](https://bsd-hardware.info/?probe=a4e6db54d8) | Feb 10, 2023 |
| Acer          | Aspire 4739Z                | Notebook    | [1e97a0b938](https://bsd-hardware.info/?probe=1e97a0b938) | Feb 09, 2023 |
| Unknown       | Unknown                     | Desktop     | [34d9347fc3](https://bsd-hardware.info/?probe=34d9347fc3) | Feb 08, 2023 |
| Lenovo        | IdeaPad 3 15IML05 82BS      | Notebook    | [3345f50844](https://bsd-hardware.info/?probe=3345f50844) | Feb 06, 2023 |
| Dell          | 0DFXXD A00                  | Server      | [299fce37cb](https://bsd-hardware.info/?probe=299fce37cb) | Feb 06, 2023 |
| Dell          | 0DFXXD A00                  | Server      | [3c867871f2](https://bsd-hardware.info/?probe=3c867871f2) | Feb 06, 2023 |
| AZW           | U59                         | Desktop     | [8073f1f5f3](https://bsd-hardware.info/?probe=8073f1f5f3) | Feb 04, 2023 |
| Lenovo        | SKYBAY 31900002 WIN 1801... | All in one  | [725797b27e](https://bsd-hardware.info/?probe=725797b27e) | Feb 02, 2023 |
| ASRock        | J4005B-ITX                  | Desktop     | [c4bf6a3b8c](https://bsd-hardware.info/?probe=c4bf6a3b8c) | Feb 01, 2023 |
| ASUSTek       | H110M-CS/BR                 | Desktop     | [73b6128279](https://bsd-hardware.info/?probe=73b6128279) | Jan 31, 2023 |
| ASUSTek       | H110M-CS/BR                 | Desktop     | [3fa3b849a3](https://bsd-hardware.info/?probe=3fa3b849a3) | Jan 31, 2023 |
| Biostar       | TB250-BTC+                  | Desktop     | [0a39ffa716](https://bsd-hardware.info/?probe=0a39ffa716) | Jan 24, 2023 |
| Gigabyte      | GA-990X-Gaming SLI-CF       | Desktop     | [9cd4d2810a](https://bsd-hardware.info/?probe=9cd4d2810a) | Jan 23, 2023 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [6dc0fddda1](https://bsd-hardware.info/?probe=6dc0fddda1) | Jan 22, 2023 |
| Dell          | 0H723K A05                  | Server      | [561152d95d](https://bsd-hardware.info/?probe=561152d95d) | Jan 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [32477354bc](https://bsd-hardware.info/?probe=32477354bc) | Jan 19, 2023 |
| Lenovo        | B40-70 80F30005BR           | Notebook    | [17333d88cf](https://bsd-hardware.info/?probe=17333d88cf) | Jan 17, 2023 |
| Dell          | 0CN7CM A06                  | Server      | [33c450dade](https://bsd-hardware.info/?probe=33c450dade) | Jan 11, 2023 |
| Dell          | 0CN7CM A06                  | Server      | [7a63630a51](https://bsd-hardware.info/?probe=7a63630a51) | Jan 06, 2023 |
| Dell          | 0CN7CM A06                  | Server      | [996218def1](https://bsd-hardware.info/?probe=996218def1) | Jan 06, 2023 |
| AMI           | MNHO-048                    | Desktop     | [fbd9fa83d9](https://bsd-hardware.info/?probe=fbd9fa83d9) | Jan 05, 2023 |
| Dell          | 0CU409                      | Desktop     | [a547f05175](https://bsd-hardware.info/?probe=a547f05175) | Jan 02, 2023 |
| Intel         | S3420GP E51976-407          | Server      | [c614a1e46f](https://bsd-hardware.info/?probe=c614a1e46f) | Dec 20, 2022 |
| Dell          | 02YRK5 A03                  | Desktop     | [547b1abce0](https://bsd-hardware.info/?probe=547b1abce0) | Dec 16, 2022 |
| Lenovo        | ThinkPad T460 20FN002JUS    | Notebook    | [3a9623cfb4](https://bsd-hardware.info/?probe=3a9623cfb4) | Dec 16, 2022 |
| Lenovo        | ThinkPad T460 20FN002JUS    | Notebook    | [0314add226](https://bsd-hardware.info/?probe=0314add226) | Dec 16, 2022 |
| Dell          | 0CU409                      | Desktop     | [718c9c5c8b](https://bsd-hardware.info/?probe=718c9c5c8b) | Dec 15, 2022 |
| Dell          | 0CU409                      | Desktop     | [161da6b850](https://bsd-hardware.info/?probe=161da6b850) | Dec 15, 2022 |
| Dell          | 06X1TJ A00                  | Desktop     | [1115d508c1](https://bsd-hardware.info/?probe=1115d508c1) | Dec 09, 2022 |
| Dell          | Inspiron 3442               | Notebook    | [529cbab9aa](https://bsd-hardware.info/?probe=529cbab9aa) | Dec 01, 2022 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [84d1656c05](https://bsd-hardware.info/?probe=84d1656c05) | Nov 30, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [3dd9e3557c](https://bsd-hardware.info/?probe=3dd9e3557c) | Nov 30, 2022 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [88929a3594](https://bsd-hardware.info/?probe=88929a3594) | Nov 25, 2022 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [ef6190861c](https://bsd-hardware.info/?probe=ef6190861c) | Nov 25, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [76ecd68ff6](https://bsd-hardware.info/?probe=76ecd68ff6) | Nov 25, 2022 |
| Pegatron      | IPM41-D3                    | Desktop     | [898f645e32](https://bsd-hardware.info/?probe=898f645e32) | Nov 25, 2022 |
| Dell          | Vostro 3501                 | Notebook    | [61f8a35700](https://bsd-hardware.info/?probe=61f8a35700) | Nov 25, 2022 |
| Dell          | 0TW855 A07                  | Server      | [d2d859c434](https://bsd-hardware.info/?probe=d2d859c434) | Nov 22, 2022 |
| Dell          | 0TW855 A07                  | Server      | [dbeaf80924](https://bsd-hardware.info/?probe=dbeaf80924) | Nov 20, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [d3cbc9d6ca](https://bsd-hardware.info/?probe=d3cbc9d6ca) | Nov 19, 2022 |
| Dell          | Inspiron 3421               | Notebook    | [5c37012f33](https://bsd-hardware.info/?probe=5c37012f33) | Nov 10, 2022 |
| Dell          | 0F428D A00                  | Desktop     | [0a9ca655d3](https://bsd-hardware.info/?probe=0a9ca655d3) | Nov 08, 2022 |
| Supermicro    | X8DT6                       | Server      | [e7536e4a4c](https://bsd-hardware.info/?probe=e7536e4a4c) | Nov 07, 2022 |
| Dell          | 0CN7CM A06                  | Server      | [6efd22e598](https://bsd-hardware.info/?probe=6efd22e598) | Nov 04, 2022 |
| ASUSTek       | H110M-CS/BR                 | Desktop     | [0841d714d0](https://bsd-hardware.info/?probe=0841d714d0) | Nov 03, 2022 |
| maiyunda      | www.maiyunda.com            | Desktop     | [4dfd35f622](https://bsd-hardware.info/?probe=4dfd35f622) | Oct 31, 2022 |
| maiyunda      | www.maiyunda.com            | Desktop     | [ed59c93b79](https://bsd-hardware.info/?probe=ed59c93b79) | Oct 29, 2022 |
| Dell          | 0CN7CM A06                  | Server      | [764a816130](https://bsd-hardware.info/?probe=764a816130) | Oct 21, 2022 |
| Dell          | 0CN7CM A06                  | Server      | [09bca1b1ff](https://bsd-hardware.info/?probe=09bca1b1ff) | Oct 20, 2022 |
| Lenovo        | ThinkCentre M57p 6078AJ6    | Desktop     | [a808a7360d](https://bsd-hardware.info/?probe=a808a7360d) | Oct 14, 2022 |
| ASUSTek       | H110M-CS/BR                 | Desktop     | [097a263bfc](https://bsd-hardware.info/?probe=097a263bfc) | Oct 11, 2022 |
| PCWare        | IPMH81G1                    | Desktop     | [58b53464d1](https://bsd-hardware.info/?probe=58b53464d1) | Oct 10, 2022 |
| Dell          | 06X1TJ A00                  | Desktop     | [c70e4d6b3c](https://bsd-hardware.info/?probe=c70e4d6b3c) | Oct 10, 2022 |
| ASRock        | J4005B-ITX                  | Desktop     | [6cf37e95da](https://bsd-hardware.info/?probe=6cf37e95da) | Oct 10, 2022 |
| Gigabyte      | G31M-S2C                    | Desktop     | [8b8f621562](https://bsd-hardware.info/?probe=8b8f621562) | Oct 10, 2022 |
| Dell          | 06X1TJ A00                  | Desktop     | [21117c0374](https://bsd-hardware.info/?probe=21117c0374) | Oct 10, 2022 |
| ASRock        | J4005B-ITX                  | Desktop     | [0e0ff27c25](https://bsd-hardware.info/?probe=0e0ff27c25) | Oct 09, 2022 |
| HP            | 86FC MVB                    | Desktop     | [56453b00c8](https://bsd-hardware.info/?probe=56453b00c8) | Oct 08, 2022 |
| HP            | 86FC MVB                    | Desktop     | [c542b16d75](https://bsd-hardware.info/?probe=c542b16d75) | Oct 08, 2022 |
| Acer          | Aspire F5-573               | Notebook    | [9c092c9cd7](https://bsd-hardware.info/?probe=9c092c9cd7) | Oct 05, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [1fd10e86d9](https://bsd-hardware.info/?probe=1fd10e86d9) | Oct 04, 2022 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [122f6f6837](https://bsd-hardware.info/?probe=122f6f6837) | Oct 02, 2022 |
| ASRock        | A320M-HD                    | Desktop     | [6418fd0b23](https://bsd-hardware.info/?probe=6418fd0b23) | Sep 28, 2022 |
| Lenovo        | G475 20080                  | Notebook    | [fb07463a9a](https://bsd-hardware.info/?probe=fb07463a9a) | Sep 24, 2022 |
| Lenovo        | G475 20080                  | Notebook    | [c4b1acb6d1](https://bsd-hardware.info/?probe=c4b1acb6d1) | Sep 24, 2022 |
| Dell          | 02YRK5 A03                  | Desktop     | [2ec32e432d](https://bsd-hardware.info/?probe=2ec32e432d) | Sep 20, 2022 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [ca3b8f6b48](https://bsd-hardware.info/?probe=ca3b8f6b48) | Sep 20, 2022 |
| ASUSTek       | M5A88-M                     | Desktop     | [09b5ca588f](https://bsd-hardware.info/?probe=09b5ca588f) | Sep 16, 2022 |
| Techvision    | TVI7309X B0                 | Desktop     | [505feb51ca](https://bsd-hardware.info/?probe=505feb51ca) | Sep 15, 2022 |
| maiyunda      | www.maiyunda.com            | Desktop     | [8776541164](https://bsd-hardware.info/?probe=8776541164) | Sep 09, 2022 |
| Dell          | 0W0W22 A08                  | Server      | [4d371914ed](https://bsd-hardware.info/?probe=4d371914ed) | Sep 07, 2022 |
| Pegatron      | IPM41-D3                    | Desktop     | [2d3a5a5260](https://bsd-hardware.info/?probe=2d3a5a5260) | Sep 06, 2022 |
| Unknown       | Unknown                     | Desktop     | [f2a26e2adc](https://bsd-hardware.info/?probe=f2a26e2adc) | Sep 01, 2022 |
| Unknown       | Unknown                     | Desktop     | [05e28da420](https://bsd-hardware.info/?probe=05e28da420) | Aug 16, 2022 |
| Pegatron      | IPMIP-GS                    | Desktop     | [5ee5edb1d0](https://bsd-hardware.info/?probe=5ee5edb1d0) | Aug 16, 2022 |
| Pegatron      | IPMIP-GS                    | Desktop     | [f3c4668e00](https://bsd-hardware.info/?probe=f3c4668e00) | Aug 16, 2022 |
| ASUSTek       | P5GC-MX/CKD/SI              | Desktop     | [d61693dffb](https://bsd-hardware.info/?probe=d61693dffb) | Aug 05, 2022 |
| Dell          | 0VV3F2 A01                  | Server      | [ad01fbd5a3](https://bsd-hardware.info/?probe=ad01fbd5a3) | Aug 03, 2022 |
| Dell          | 0VV3F2 A01                  | Server      | [c0e6b1eb61](https://bsd-hardware.info/?probe=c0e6b1eb61) | Aug 03, 2022 |
| Lenovo        | ThinkPad T61 7661GY9        | Notebook    | [7ab5339eee](https://bsd-hardware.info/?probe=7ab5339eee) | Jul 30, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [e2a5a65135](https://bsd-hardware.info/?probe=e2a5a65135) | Jul 23, 2022 |
| Positivo      | POS-EINM70CS SIM            | Desktop     | [0b29806790](https://bsd-hardware.info/?probe=0b29806790) | Jul 23, 2022 |
| ASRock        | N68-S3 UCC                  | Desktop     | [e503017a9f](https://bsd-hardware.info/?probe=e503017a9f) | Jul 21, 2022 |
| Dell          | 0GDG8Y A02                  | Desktop     | [2f163e2a05](https://bsd-hardware.info/?probe=2f163e2a05) | Jul 21, 2022 |
| ASUSTek       | P5KPL-AM-CKD-VISUM-SI       | Desktop     | [f88fa027ab](https://bsd-hardware.info/?probe=f88fa027ab) | Jul 19, 2022 |
| Dell          | Inspiron MP061              | Notebook    | [56a7002cc5](https://bsd-hardware.info/?probe=56a7002cc5) | Jul 16, 2022 |
| Gigabyte      | C847N                       | Desktop     | [4be8944950](https://bsd-hardware.info/?probe=4be8944950) | Jul 15, 2022 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [87d68034db](https://bsd-hardware.info/?probe=87d68034db) | Jul 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [b09ba0c799](https://bsd-hardware.info/?probe=b09ba0c799) | Jul 12, 2022 |
| Acer          | Aspire E5-571G              | Notebook    | [56fae2295e](https://bsd-hardware.info/?probe=56fae2295e) | Jul 08, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [ba96a05e5c](https://bsd-hardware.info/?probe=ba96a05e5c) | Jul 08, 2022 |
| Pegatron      | IPM41-D3                    | Desktop     | [8b2af1b843](https://bsd-hardware.info/?probe=8b2af1b843) | Jul 06, 2022 |
| Pegatron      | IPM41-D3                    | Desktop     | [1cd93cd5d3](https://bsd-hardware.info/?probe=1cd93cd5d3) | Jul 04, 2022 |
| Biostar       | G41D3C                      | Desktop     | [118bd083bf](https://bsd-hardware.info/?probe=118bd083bf) | Jul 01, 2022 |
| Lenovo        | ThinkPad T410 2522CS7       | Notebook    | [a1561dacb2](https://bsd-hardware.info/?probe=a1561dacb2) | Jun 26, 2022 |
| ASUSTek       | P8B75-M LX PLUS             | Desktop     | [346bc6f0ae](https://bsd-hardware.info/?probe=346bc6f0ae) | Jun 20, 2022 |
| ASUSTek       | A88XM-A                     | Desktop     | [a464043744](https://bsd-hardware.info/?probe=a464043744) | Jun 19, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [af923daeda](https://bsd-hardware.info/?probe=af923daeda) | Jun 12, 2022 |
| ASUSTek       | P5G41T-M LX V2              | Desktop     | [bba161b618](https://bsd-hardware.info/?probe=bba161b618) | Jun 08, 2022 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [7be45ccc7e](https://bsd-hardware.info/?probe=7be45ccc7e) | Jun 08, 2022 |
| Positivo      | POS-PIQ77CL POSITIVO        | Desktop     | [848361c724](https://bsd-hardware.info/?probe=848361c724) | May 31, 2022 |
| Lenovo        | IdeaPad 3 15IGL05 82BU      | Notebook    | [6a6450f264](https://bsd-hardware.info/?probe=6a6450f264) | May 30, 2022 |
| Dell          | 0D28YY A00                  | Desktop     | [8f25636c51](https://bsd-hardware.info/?probe=8f25636c51) | May 19, 2022 |
| Acer          | Aspire 5742                 | Notebook    | [b0ea5e7a5e](https://bsd-hardware.info/?probe=b0ea5e7a5e) | May 19, 2022 |
| CNCTION-IA... | Unknown                     | Desktop     | [d6602975d3](https://bsd-hardware.info/?probe=d6602975d3) | May 16, 2022 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [8675ff74d8](https://bsd-hardware.info/?probe=8675ff74d8) | May 09, 2022 |
| Dell          | Inspiron 5437               | Notebook    | [830ea686ab](https://bsd-hardware.info/?probe=830ea686ab) | Apr 24, 2022 |
| HP            | 2820h                       | Desktop     | [d888b8b775](https://bsd-hardware.info/?probe=d888b8b775) | Apr 22, 2022 |
| Intel         | H55                         | Desktop     | [1478e4af73](https://bsd-hardware.info/?probe=1478e4af73) | Apr 20, 2022 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [11ec99d4b7](https://bsd-hardware.info/?probe=11ec99d4b7) | Apr 11, 2022 |
| ASUSTek       | P5G41T-M LX V2              | Desktop     | [64de6d6bb9](https://bsd-hardware.info/?probe=64de6d6bb9) | Mar 24, 2022 |
| Gateway       | NE56R                       | Notebook    | [87d177b9da](https://bsd-hardware.info/?probe=87d177b9da) | Mar 20, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [8460816b1f](https://bsd-hardware.info/?probe=8460816b1f) | Mar 13, 2022 |
| ASUSTek       | P5G41T-M LX V2              | Desktop     | [99ab8e7989](https://bsd-hardware.info/?probe=99ab8e7989) | Mar 11, 2022 |
| Acer          | Aspire E1-421               | Notebook    | [cc83218496](https://bsd-hardware.info/?probe=cc83218496) | Mar 10, 2022 |
| Pegatron      | IPM41-D3                    | Desktop     | [a58b9a4f8f](https://bsd-hardware.info/?probe=a58b9a4f8f) | Mar 09, 2022 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [62474001e3](https://bsd-hardware.info/?probe=62474001e3) | Mar 09, 2022 |
| Itautec       | Infoway w7535               | Notebook    | [b55f9d1bfb](https://bsd-hardware.info/?probe=b55f9d1bfb) | Mar 09, 2022 |
| Apple         | Mac-F2218EA9                | All in one  | [8b51036856](https://bsd-hardware.info/?probe=8b51036856) | Mar 06, 2022 |
| MSI           | U-100 Ver.001               | Desktop     | [50aba1dee8](https://bsd-hardware.info/?probe=50aba1dee8) | Mar 03, 2022 |
| MSI           | U-100 Ver.001               | Desktop     | [6859308aa9](https://bsd-hardware.info/?probe=6859308aa9) | Mar 01, 2022 |
| HP            | 1905                        | Desktop     | [e271589365](https://bsd-hardware.info/?probe=e271589365) | Mar 01, 2022 |
| HP            | 1905                        | Desktop     | [aa010e00f2](https://bsd-hardware.info/?probe=aa010e00f2) | Feb 28, 2022 |
| KLLISRE       | X99-B5 V1.0                 | Desktop     | [5dea1304b9](https://bsd-hardware.info/?probe=5dea1304b9) | Feb 26, 2022 |
| GALAX         | B365M G10b                  | Desktop     | [ceb2291168](https://bsd-hardware.info/?probe=ceb2291168) | Feb 22, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [aa484c30a8](https://bsd-hardware.info/?probe=aa484c30a8) | Feb 12, 2022 |
| HP            | 83E1                        | Desktop     | [d8e995126f](https://bsd-hardware.info/?probe=d8e995126f) | Feb 10, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [d57de875a6](https://bsd-hardware.info/?probe=d57de875a6) | Feb 07, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [5606f6d091](https://bsd-hardware.info/?probe=5606f6d091) | Feb 05, 2022 |
| Unknown       | YL-E3845L4-V2               | Desktop     | [24e60f4686](https://bsd-hardware.info/?probe=24e60f4686) | Feb 02, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [a07a15f667](https://bsd-hardware.info/?probe=a07a15f667) | Feb 02, 2022 |
| Dell          | 0GDG8Y A02                  | Desktop     | [343129f659](https://bsd-hardware.info/?probe=343129f659) | Feb 01, 2022 |
| Gigabyte      | C847N                       | Desktop     | [0d62b7756c](https://bsd-hardware.info/?probe=0d62b7756c) | Jan 24, 2022 |
| ASUSTek       | J1800I-C/BR                 | Desktop     | [13d6d1ed51](https://bsd-hardware.info/?probe=13d6d1ed51) | Jan 21, 2022 |
| Gateway       | NE56R                       | Notebook    | [a5aa8aa49a](https://bsd-hardware.info/?probe=a5aa8aa49a) | Jan 18, 2022 |
| Acer          | Aspire ES1-533              | Notebook    | [a9d2458de5](https://bsd-hardware.info/?probe=a9d2458de5) | Jan 13, 2022 |
| Sony          | VPCYB45JB                   | Notebook    | [cd18905620](https://bsd-hardware.info/?probe=cd18905620) | Jan 09, 2022 |
| Lenovo        | G550 2958                   | Notebook    | [21407195e3](https://bsd-hardware.info/?probe=21407195e3) | Jan 07, 2022 |
| Unknown       | Phitronics G31VS-M          | Desktop     | [820f706b46](https://bsd-hardware.info/?probe=820f706b46) | Jan 06, 2022 |
| Unknown       | G31T-M7                     | Desktop     | [ed7d80e01a](https://bsd-hardware.info/?probe=ed7d80e01a) | Jan 03, 2022 |
| Pegatron      | IPM41-D3                    | Desktop     | [6829928dad](https://bsd-hardware.info/?probe=6829928dad) | Dec 28, 2021 |
| Acidanther... | Mac-AA95B1DDAB278B95 iMa... | All in one  | [73076dd5de](https://bsd-hardware.info/?probe=73076dd5de) | Dec 21, 2021 |
| Samsung       | 530XBB                      | Notebook    | [fe0adb59d8](https://bsd-hardware.info/?probe=fe0adb59d8) | Dec 20, 2021 |
| Dell          | 0PV3YR A05                  | Server      | [ad308cc715](https://bsd-hardware.info/?probe=ad308cc715) | Dec 08, 2021 |
| Philco        | 10B                         | Notebook    | [a27148f35d](https://bsd-hardware.info/?probe=a27148f35d) | Dec 06, 2021 |
| Positivo      | C14CR01                     | Notebook    | [a33c158f9f](https://bsd-hardware.info/?probe=a33c158f9f) | Dec 05, 2021 |
| Dell          | 0PV3YR A05                  | Server      | [df981410a9](https://bsd-hardware.info/?probe=df981410a9) | Dec 04, 2021 |
| Samsung       | 530XBB                      | Notebook    | [8387645312](https://bsd-hardware.info/?probe=8387645312) | Dec 03, 2021 |
| Samsung       | 530XBB                      | Notebook    | [41d5f95889](https://bsd-hardware.info/?probe=41d5f95889) | Dec 03, 2021 |
| Samsung       | 530XBB                      | Notebook    | [e1983c2353](https://bsd-hardware.info/?probe=e1983c2353) | Dec 03, 2021 |
| Samsung       | 530XBB                      | Notebook    | [b344605891](https://bsd-hardware.info/?probe=b344605891) | Dec 02, 2021 |
| Dell          | Inspiron 5566               | Notebook    | [7c6b2f2013](https://bsd-hardware.info/?probe=7c6b2f2013) | Nov 14, 2021 |
| Toshiba       | STI NA 1401                 | Notebook    | [bbbf661ee8](https://bsd-hardware.info/?probe=bbbf661ee8) | Nov 14, 2021 |
| Unknown       | X79                         | Desktop     | [c80b658f36](https://bsd-hardware.info/?probe=c80b658f36) | Nov 09, 2021 |
| Itautec       | ST 4344 ST-4344 Padrao 0... | Desktop     | [ec13cb0829](https://bsd-hardware.info/?probe=ec13cb0829) | Nov 07, 2021 |
| HP            | 14                          | Notebook    | [e0c8e95e52](https://bsd-hardware.info/?probe=e0c8e95e52) | Nov 07, 2021 |
| Unknown       | X79                         | Desktop     | [ef88cbc606](https://bsd-hardware.info/?probe=ef88cbc606) | Nov 05, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [03be88ded4](https://bsd-hardware.info/?probe=03be88ded4) | Nov 02, 2021 |
| Dell          | 0M5DCD A02                  | Desktop     | [4ff4198768](https://bsd-hardware.info/?probe=4ff4198768) | Nov 02, 2021 |
| Gigabyte      | G41MT-S2                    | Desktop     | [2847d63db0](https://bsd-hardware.info/?probe=2847d63db0) | Oct 18, 2021 |
| Dell          | Inspiron 7460               | Notebook    | [3dbc09a4df](https://bsd-hardware.info/?probe=3dbc09a4df) | Oct 13, 2021 |
| ASUSTek       | PN50-E1                     | Mini pc     | [2781b31f9b](https://bsd-hardware.info/?probe=2781b31f9b) | Oct 10, 2021 |
| Lenovo        | ThinkPad X250 20CLS2A11K    | Notebook    | [e47f4113bf](https://bsd-hardware.info/?probe=e47f4113bf) | Oct 08, 2021 |
| ASRock        | A320M-DGS                   | Desktop     | [11cf5c923a](https://bsd-hardware.info/?probe=11cf5c923a) | Oct 08, 2021 |
| Dell          | 0PV3YR A05                  | Server      | [20f9d1c3f0](https://bsd-hardware.info/?probe=20f9d1c3f0) | Oct 06, 2021 |
| Dell          | 0PV3YR A05                  | Server      | [88d44cfe0c](https://bsd-hardware.info/?probe=88d44cfe0c) | Oct 05, 2021 |
| Itautec       | Infoway w7530               | Notebook    | [a376201681](https://bsd-hardware.info/?probe=a376201681) | Oct 05, 2021 |
| Dell          | Latitude 5490               | Notebook    | [f0f4370a9c](https://bsd-hardware.info/?probe=f0f4370a9c) | Sep 27, 2021 |
| ASUSTek       | J1800I-C/BR                 | Desktop     | [e7395898d8](https://bsd-hardware.info/?probe=e7395898d8) | Sep 25, 2021 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [b00f275d35](https://bsd-hardware.info/?probe=b00f275d35) | Sep 23, 2021 |
| ASUSTek       | J1800I-C/BR                 | Desktop     | [91642a928d](https://bsd-hardware.info/?probe=91642a928d) | Sep 20, 2021 |
| PCWare        | PW-945GCX                   | Desktop     | [04bbdf92d6](https://bsd-hardware.info/?probe=04bbdf92d6) | Sep 13, 2021 |
| Unknown       | Phitronics G31VS-M          | Desktop     | [0d13c20ba5](https://bsd-hardware.info/?probe=0d13c20ba5) | Sep 11, 2021 |
| Itautec       | Infoway w7530               | Notebook    | [d91ec24ce0](https://bsd-hardware.info/?probe=d91ec24ce0) | Aug 29, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [0a1be200c6](https://bsd-hardware.info/?probe=0a1be200c6) | Aug 29, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [a129f532bd](https://bsd-hardware.info/?probe=a129f532bd) | Aug 28, 2021 |
| Gigabyte      | H61M-S2-B3                  | Desktop     | [7c9c49f924](https://bsd-hardware.info/?probe=7c9c49f924) | Aug 27, 2021 |
| Itautec       | Infoway w7530               | Notebook    | [fe69db32c8](https://bsd-hardware.info/?probe=fe69db32c8) | Aug 27, 2021 |
| ECS-USA       | GeForce6100PM-M2            | Desktop     | [f6324966fb](https://bsd-hardware.info/?probe=f6324966fb) | Aug 26, 2021 |
| Acer          | Aspire 5750                 | Notebook    | [2bc72bf29e](https://bsd-hardware.info/?probe=2bc72bf29e) | Aug 23, 2021 |
| ASUSTek       | P5Q                         | Desktop     | [01c4a15001](https://bsd-hardware.info/?probe=01c4a15001) | Aug 22, 2021 |
| Avell High... | A60 MUV                     | Notebook    | [85f5c972a5](https://bsd-hardware.info/?probe=85f5c972a5) | Aug 21, 2021 |
| HC            | HCAR357-MI V1.0             | Desktop     | [3293b7bad9](https://bsd-hardware.info/?probe=3293b7bad9) | Aug 17, 2021 |
| Gigabyte      | C847N                       | Desktop     | [c19601f640](https://bsd-hardware.info/?probe=c19601f640) | Aug 07, 2021 |
| Dell          | 0PV3YR A05                  | Server      | [a40a382f62](https://bsd-hardware.info/?probe=a40a382f62) | Aug 06, 2021 |
| Dell          | 0PV3YR A05                  | Server      | [f43771bc21](https://bsd-hardware.info/?probe=f43771bc21) | Aug 05, 2021 |
| Samsung       | 300E5M/300E5L               | Notebook    | [ae874102c3](https://bsd-hardware.info/?probe=ae874102c3) | Aug 04, 2021 |
| Gigabyte      | H61M-S2-B3                  | Desktop     | [d1790c6aed](https://bsd-hardware.info/?probe=d1790c6aed) | Aug 04, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [1aad7a6eab](https://bsd-hardware.info/?probe=1aad7a6eab) | Aug 03, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [95573fe387](https://bsd-hardware.info/?probe=95573fe387) | Aug 03, 2021 |
| Unknown       | Unknown                     | Desktop     | [524215c510](https://bsd-hardware.info/?probe=524215c510) | Aug 03, 2021 |
| ECS           | BAT-I                       | Desktop     | [6741011e07](https://bsd-hardware.info/?probe=6741011e07) | Aug 02, 2021 |
| Dell          | Inspiron 3442               | Notebook    | [6283cb4190](https://bsd-hardware.info/?probe=6283cb4190) | Aug 01, 2021 |
| Yanling       | NS-1U8L                     | Desktop     | [6166362d7a](https://bsd-hardware.info/?probe=6166362d7a) | Jul 27, 2021 |
| Avell High... | A62 LIV                     | Notebook    | [5983302b1d](https://bsd-hardware.info/?probe=5983302b1d) | Jul 21, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [daa7e68a1f](https://bsd-hardware.info/?probe=daa7e68a1f) | Jul 21, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [98cefddb1b](https://bsd-hardware.info/?probe=98cefddb1b) | Jul 17, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [a857cdfd42](https://bsd-hardware.info/?probe=a857cdfd42) | Jul 07, 2021 |
| Acer          | Aspire A515-54G             | Notebook    | [08cafd05b1](https://bsd-hardware.info/?probe=08cafd05b1) | Jul 06, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [128c08e60f](https://bsd-hardware.info/?probe=128c08e60f) | Jul 04, 2021 |
| Dell          | 0PV3YR A05                  | Server      | [f6d72c011d](https://bsd-hardware.info/?probe=f6d72c011d) | Jul 01, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [ceb18e38a3](https://bsd-hardware.info/?probe=ceb18e38a3) | Jun 28, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [7623c94ba1](https://bsd-hardware.info/?probe=7623c94ba1) | Jun 25, 2021 |
| ULTRATOP      | C2017-LIVA-ZE               | Desktop     | [d091f171b7](https://bsd-hardware.info/?probe=d091f171b7) | Jun 23, 2021 |
| Acer          | Aspire 5750                 | Notebook    | [d59f20f88a](https://bsd-hardware.info/?probe=d59f20f88a) | Jun 22, 2021 |
| Acer          | Aspire 5750                 | Notebook    | [cc6dc71d37](https://bsd-hardware.info/?probe=cc6dc71d37) | Jun 21, 2021 |
| Gateway       | NE56R                       | Notebook    | [cc65e24aea](https://bsd-hardware.info/?probe=cc65e24aea) | Jun 20, 2021 |
| ASUSTek       | M5A78L-M LX/BR              | Desktop     | [5f9b56c8ae](https://bsd-hardware.info/?probe=5f9b56c8ae) | Jun 15, 2021 |
| Gateway       | NE56R                       | Notebook    | [932f5d03f3](https://bsd-hardware.info/?probe=932f5d03f3) | Jun 13, 2021 |
| Dell          | Vostro 5490                 | Notebook    | [cf3508718c](https://bsd-hardware.info/?probe=cf3508718c) | Jun 11, 2021 |
| Lenovo        | ThinkPad X220 4291ON5       | Notebook    | [66743a51cc](https://bsd-hardware.info/?probe=66743a51cc) | Jun 04, 2021 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [edebe87739](https://bsd-hardware.info/?probe=edebe87739) | Jun 04, 2021 |
| Acer          | Aspire A515-51G             | Notebook    | [53a69aa8c1](https://bsd-hardware.info/?probe=53a69aa8c1) | Jun 04, 2021 |
| Dell          | 0GDG8Y A02                  | Desktop     | [5b44835ac1](https://bsd-hardware.info/?probe=5b44835ac1) | Jun 03, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [c44be632d3](https://bsd-hardware.info/?probe=c44be632d3) | May 28, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [5675cca325](https://bsd-hardware.info/?probe=5675cca325) | May 28, 2021 |
| Gigabyte      | H61M-S2-B3                  | Desktop     | [b73e45e0df](https://bsd-hardware.info/?probe=b73e45e0df) | May 27, 2021 |
| Lenovo        | ThinkPad X270 20HM004JBR    | Notebook    | [88c27e65d7](https://bsd-hardware.info/?probe=88c27e65d7) | May 23, 2021 |
| Dell          | Inspiron 3442               | Notebook    | [0d1d75a914](https://bsd-hardware.info/?probe=0d1d75a914) | May 23, 2021 |
| Dell          | 0C7TDG A03                  | Server      | [25e20c3f35](https://bsd-hardware.info/?probe=25e20c3f35) | May 19, 2021 |
| HP            | ProLiant DL20 Gen9          | Server      | [0d13ec7ac2](https://bsd-hardware.info/?probe=0d13ec7ac2) | May 17, 2021 |
| Toshiba       | STI 005492G                 | Desktop     | [9a8e4a1328](https://bsd-hardware.info/?probe=9a8e4a1328) | May 17, 2021 |
| ASUSTek       | M5A78L-M LX/BR              | Desktop     | [e69be420df](https://bsd-hardware.info/?probe=e69be420df) | May 16, 2021 |
| Dell          | Inspiron 3442               | Notebook    | [076dc91b26](https://bsd-hardware.info/?probe=076dc91b26) | May 13, 2021 |
| HP            | ProLiant DL20 Gen9          | Server      | [a5c5f7dba6](https://bsd-hardware.info/?probe=a5c5f7dba6) | May 12, 2021 |
| Lenovo        | ThinkPad E490 20N9001SBR    | Notebook    | [852a900303](https://bsd-hardware.info/?probe=852a900303) | Apr 22, 2021 |
| AMI           | Aptio CRB 11                | Mini pc     | [e75df3aaa4](https://bsd-hardware.info/?probe=e75df3aaa4) | Apr 20, 2021 |
| Gateway       | NE56R                       | Notebook    | [bbbc827581](https://bsd-hardware.info/?probe=bbbc827581) | Apr 16, 2021 |
| Gateway       | NE56R                       | Notebook    | [af262c2350](https://bsd-hardware.info/?probe=af262c2350) | Apr 11, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [01cc3a3802](https://bsd-hardware.info/?probe=01cc3a3802) | Apr 11, 2021 |
| Gigabyte      | C847N                       | Desktop     | [1d9e74caab](https://bsd-hardware.info/?probe=1d9e74caab) | Apr 08, 2021 |
| Dell          | 04YP6J A03                  | Desktop     | [779e2e4d2d](https://bsd-hardware.info/?probe=779e2e4d2d) | Apr 05, 2021 |
| Pegatron      | IPM41-D3                    | Desktop     | [687047b3d2](https://bsd-hardware.info/?probe=687047b3d2) | Mar 30, 2021 |
| Dell          | 04YP6J A03                  | Desktop     | [59efed23b2](https://bsd-hardware.info/?probe=59efed23b2) | Mar 30, 2021 |
| Dell          | 0P301D A01                  | Desktop     | [bd0c36fe70](https://bsd-hardware.info/?probe=bd0c36fe70) | Mar 26, 2021 |
| ECS           | H55H-CM                     | Desktop     | [a2808d49c9](https://bsd-hardware.info/?probe=a2808d49c9) | Mar 25, 2021 |
| ECS           | H55H-CM                     | Desktop     | [3b13b3a934](https://bsd-hardware.info/?probe=3b13b3a934) | Mar 25, 2021 |
| Avell High... | A62                         | Notebook    | [df77dd6562](https://bsd-hardware.info/?probe=df77dd6562) | Mar 22, 2021 |
| Notebook      | N85_N87HCHNHZ               | Notebook    | [e84b5b6e5f](https://bsd-hardware.info/?probe=e84b5b6e5f) | Mar 22, 2021 |
| Lenovo        | ThinkPad X220 4291ON5       | Notebook    | [8d81204137](https://bsd-hardware.info/?probe=8d81204137) | Mar 22, 2021 |
| ECS           | H55H-CM                     | Desktop     | [5df8692ddd](https://bsd-hardware.info/?probe=5df8692ddd) | Mar 18, 2021 |
| ECS           | H55H-CM                     | Desktop     | [6a10af558b](https://bsd-hardware.info/?probe=6a10af558b) | Mar 18, 2021 |
| Pegatron      | IPM41-D3                    | Desktop     | [fdfc8e2b9b](https://bsd-hardware.info/?probe=fdfc8e2b9b) | Mar 17, 2021 |
| ASUSTek       | H81M-C/BR                   | Desktop     | [c4b2356821](https://bsd-hardware.info/?probe=c4b2356821) | Mar 17, 2021 |
| ASUSTek       | H81M-C/BR                   | Desktop     | [c23066d56d](https://bsd-hardware.info/?probe=c23066d56d) | Mar 17, 2021 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [cc3151bc6f](https://bsd-hardware.info/?probe=cc3151bc6f) | Mar 17, 2021 |
| Gigabyte      | H61M-S2-B3                  | Desktop     | [35f1d21b73](https://bsd-hardware.info/?probe=35f1d21b73) | Mar 16, 2021 |
| Dell          | Inspiron 7520               | Notebook    | [599d3e84d7](https://bsd-hardware.info/?probe=599d3e84d7) | Mar 16, 2021 |
| Dell          | Inspiron 3442               | Notebook    | [f156951052](https://bsd-hardware.info/?probe=f156951052) | Mar 14, 2021 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [49509bf7ee](https://bsd-hardware.info/?probe=49509bf7ee) | Mar 13, 2021 |
| Dell          | 0HN7XN A01                  | Desktop     | [3339a68c44](https://bsd-hardware.info/?probe=3339a68c44) | Mar 12, 2021 |
| Dell          | Inspiron 3543               | Notebook    | [525eeec663](https://bsd-hardware.info/?probe=525eeec663) | Mar 12, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [4b65be31e6](https://bsd-hardware.info/?probe=4b65be31e6) | Mar 11, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [3bdcd1ac80](https://bsd-hardware.info/?probe=3bdcd1ac80) | Mar 05, 2021 |
| ASRock        | 970A-G                      | Desktop     | [3e474f93cf](https://bsd-hardware.info/?probe=3e474f93cf) | Mar 04, 2021 |
| Dell          | 0H5FVJ A01                  | Server      | [efe3dbf989](https://bsd-hardware.info/?probe=efe3dbf989) | Mar 03, 2021 |
| ASUSTek       | H110M-K                     | Desktop     | [b33294491e](https://bsd-hardware.info/?probe=b33294491e) | Mar 02, 2021 |
| Dell          | 0DFXXD A00                  | Server      | [deb86bda7b](https://bsd-hardware.info/?probe=deb86bda7b) | Feb 26, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [5211d36066](https://bsd-hardware.info/?probe=5211d36066) | Feb 25, 2021 |
| MSI           | E350IS-E45                  | Desktop     | [2d4f50994d](https://bsd-hardware.info/?probe=2d4f50994d) | Feb 24, 2021 |
| Unknown       | Unknown                     | Notebook    | [d11ec93413](https://bsd-hardware.info/?probe=d11ec93413) | Feb 23, 2021 |
| ASUSTek       | P5Q                         | Desktop     | [22fa0d8178](https://bsd-hardware.info/?probe=22fa0d8178) | Feb 23, 2021 |
| Intel         | H61                         | Desktop     | [a8ae96a0ab](https://bsd-hardware.info/?probe=a8ae96a0ab) | Feb 23, 2021 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [467a915fc7](https://bsd-hardware.info/?probe=467a915fc7) | Feb 23, 2021 |
| LG Electro... | 14Z980-G.BH51P1             | Notebook    | [d8ee6bc4e3](https://bsd-hardware.info/?probe=d8ee6bc4e3) | Feb 22, 2021 |
| Lenovo        | ThinkPad X240 20AMS4V000    | Notebook    | [cbfa45fe44](https://bsd-hardware.info/?probe=cbfa45fe44) | Feb 22, 2021 |
| ASUSTek       | K46CA                       | Notebook    | [f286c1e784](https://bsd-hardware.info/?probe=f286c1e784) | Feb 21, 2021 |
| ASUSTek       | GRYPHON Z97 ARMOR EDITIO... | Desktop     | [405b36b911](https://bsd-hardware.info/?probe=405b36b911) | Feb 21, 2021 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [c9a8d5ade5](https://bsd-hardware.info/?probe=c9a8d5ade5) | Feb 21, 2021 |
| Dell          | 0M8K4M A00                  | Desktop     | [6d3defcde3](https://bsd-hardware.info/?probe=6d3defcde3) | Feb 21, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [5b163eb70f](https://bsd-hardware.info/?probe=5b163eb70f) | Feb 19, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [724e753eb9](https://bsd-hardware.info/?probe=724e753eb9) | Feb 19, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [337aa08686](https://bsd-hardware.info/?probe=337aa08686) | Feb 18, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [7699b1e79f](https://bsd-hardware.info/?probe=7699b1e79f) | Feb 18, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [7ef872c122](https://bsd-hardware.info/?probe=7ef872c122) | Feb 18, 2021 |
| ASRock        | A320M-DGS                   | Desktop     | [d8a1ca5210](https://bsd-hardware.info/?probe=d8a1ca5210) | Feb 17, 2021 |
| Dell          | Venue 11 Pro 7140           | Notebook    | [1a49b7921a](https://bsd-hardware.info/?probe=1a49b7921a) | Feb 17, 2021 |
| Lenovo        | ThinkPad T430 2349PMP       | Notebook    | [23de6449ad](https://bsd-hardware.info/?probe=23de6449ad) | Feb 17, 2021 |
| Pegatron      | IPM41-D3                    | Desktop     | [ffc1292c18](https://bsd-hardware.info/?probe=ffc1292c18) | Feb 16, 2021 |
| Pegatron      | IPM41-D3                    | Desktop     | [6e5c330c9c](https://bsd-hardware.info/?probe=6e5c330c9c) | Feb 16, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [32a87da376](https://bsd-hardware.info/?probe=32a87da376) | Feb 16, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [cf042892e7](https://bsd-hardware.info/?probe=cf042892e7) | Feb 16, 2021 |
| Dell          | Inspiron 3421               | Notebook    | [c5f6880081](https://bsd-hardware.info/?probe=c5f6880081) | Feb 15, 2021 |
| Dell          | 0GDG8Y A02                  | Desktop     | [5cda8abfad](https://bsd-hardware.info/?probe=5cda8abfad) | Feb 14, 2021 |
| ASUSTek       | GRYPHON Z97 ARMOR EDITIO... | Desktop     | [694204751b](https://bsd-hardware.info/?probe=694204751b) | Feb 13, 2021 |
| Dell          | Inspiron 3442               | Notebook    | [411797b4dc](https://bsd-hardware.info/?probe=411797b4dc) | Feb 13, 2021 |
| Clevo         | C41X0                       | Notebook    | [81c48d156a](https://bsd-hardware.info/?probe=81c48d156a) | Feb 12, 2021 |
| Apple         | MacBook6,1                  | Notebook    | [3a9335691f](https://bsd-hardware.info/?probe=3a9335691f) | Feb 11, 2021 |
| Dell          | 07N90W A02                  | Desktop     | [6bbd0de8d9](https://bsd-hardware.info/?probe=6bbd0de8d9) | Feb 08, 2021 |
| ASRock        | A320M-DGS                   | Desktop     | [7c179e0033](https://bsd-hardware.info/?probe=7c179e0033) | Feb 06, 2021 |
| HP            | ProLiant ML350 G6           | Desktop     | [0539585a88](https://bsd-hardware.info/?probe=0539585a88) | Feb 05, 2021 |
| Positivo      | POS-EAA75DE                 | Desktop     | [cb30dbeef2](https://bsd-hardware.info/?probe=cb30dbeef2) | Feb 05, 2021 |
| Positivo      | POS-EAA75DE                 | Desktop     | [c1fb910e23](https://bsd-hardware.info/?probe=c1fb910e23) | Feb 05, 2021 |
| Samsung       | 300E5M/300E5L               | Notebook    | [a667296c17](https://bsd-hardware.info/?probe=a667296c17) | Feb 03, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [7833038238](https://bsd-hardware.info/?probe=7833038238) | Feb 01, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [d46871a402](https://bsd-hardware.info/?probe=d46871a402) | Feb 01, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [52d17aa061](https://bsd-hardware.info/?probe=52d17aa061) | Jan 28, 2021 |
| Intel         | DH61WW AAG23116-206         | Desktop     | [85a0e6c728](https://bsd-hardware.info/?probe=85a0e6c728) | Jan 24, 2021 |
| Intel         | DH61WW AAG23116-206         | Desktop     | [3e468c1461](https://bsd-hardware.info/?probe=3e468c1461) | Jan 23, 2021 |
| PCWare        | IPX1800G2                   | Desktop     | [bc9bce51bc](https://bsd-hardware.info/?probe=bc9bce51bc) | Jan 22, 2021 |
| MSI           | J1800I                      | Desktop     | [98abf7d1f0](https://bsd-hardware.info/?probe=98abf7d1f0) | Jan 22, 2021 |
| MSI           | J1800I                      | Desktop     | [b6adf4005e](https://bsd-hardware.info/?probe=b6adf4005e) | Jan 21, 2021 |
| HP            | ProLiant ML310e Gen8 v2     | Desktop     | [ba328938c3](https://bsd-hardware.info/?probe=ba328938c3) | Jan 21, 2021 |
| Intel         | Q3XXG4-P V1.0               | Desktop     | [23e48fdef0](https://bsd-hardware.info/?probe=23e48fdef0) | Jan 21, 2021 |
| Lenovo        | ThinkPad T450s 20BWS05G0... | Notebook    | [bc2855974c](https://bsd-hardware.info/?probe=bc2855974c) | Dec 06, 2020 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [75e86a92f7](https://bsd-hardware.info/?probe=75e86a92f7) | Dec 05, 2020 |
| Unknown       | Unknown                     | Notebook    | [6953b9a9e4](https://bsd-hardware.info/?probe=6953b9a9e4) | Nov 22, 2020 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [825a724001](https://bsd-hardware.info/?probe=825a724001) | Oct 25, 2020 |
| HP            | ProLiant MicroServer        | Desktop     | [04b6ad9952](https://bsd-hardware.info/?probe=04b6ad9952) | Oct 25, 2020 |
| Dell          | Latitude 3490               | Notebook    | [b28cc12aeb](https://bsd-hardware.info/?probe=b28cc12aeb) | Sep 20, 2020 |
| ASUSTek       | Z8P                         | Desktop     | [7b0818f96a](https://bsd-hardware.info/?probe=7b0818f96a) | Sep 16, 2020 |
| ASUSTek       | STRIX B250G GAMING          | Desktop     | [a02398f78f](https://bsd-hardware.info/?probe=a02398f78f) | Sep 01, 2020 |
| Acer          | Spin SP111-32N              | Convertible | [b8fdb26064](https://bsd-hardware.info/?probe=b8fdb26064) | Sep 01, 2020 |
| Acer          | Spin SP111-32N              | Convertible | [33266821d4](https://bsd-hardware.info/?probe=33266821d4) | Sep 01, 2020 |
| Lenovo        | ThinkPad T490 20N30029BR    | Notebook    | [41dbfb6fdc](https://bsd-hardware.info/?probe=41dbfb6fdc) | Aug 06, 2020 |
| ASUSTek       | Z8P                         | Desktop     | [9f5845a398](https://bsd-hardware.info/?probe=9f5845a398) | Jul 27, 2020 |
| Itautec       | ST 4253 ST-4253 Padrao 0... | Desktop     | [7e845aab76](https://bsd-hardware.info/?probe=7e845aab76) | Jul 26, 2020 |
| Itautec       | ST 4253 ST-4253 Padrao 0... | Desktop     | [7febd3108d](https://bsd-hardware.info/?probe=7febd3108d) | Jul 26, 2020 |
| Procomp In... | G41MXE                      | Desktop     | [a76a3bb201](https://bsd-hardware.info/?probe=a76a3bb201) | Jul 25, 2020 |
| Samsung       | 270E5K/270E5Q/271E5K/257... | Notebook    | [1b84bffd9b](https://bsd-hardware.info/?probe=1b84bffd9b) | Jul 24, 2020 |
| Sony          | VPCEG17FB                   | Notebook    | [7d48bd3606](https://bsd-hardware.info/?probe=7d48bd3606) | Jul 13, 2020 |
| Lenovo        | ThinkPad X250 20CLS18S0Z    | Notebook    | [f668ce4e5b](https://bsd-hardware.info/?probe=f668ce4e5b) | Jul 05, 2020 |
| ASUSTek       | Z8P                         | Desktop     | [5071a32803](https://bsd-hardware.info/?probe=5071a32803) | Jun 05, 2020 |
| ASUSTek       | Z8P                         | Desktop     | [a0723b0566](https://bsd-hardware.info/?probe=a0723b0566) | Jun 05, 2020 |
| Dell          | 0PV3YR A05                  | Server      | [245d470945](https://bsd-hardware.info/?probe=245d470945) | Jun 05, 2020 |
| Dell          | 0PV3YR A05                  | Server      | [5e50c0fa57](https://bsd-hardware.info/?probe=5e50c0fa57) | Jun 05, 2020 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart_bsd/os_name.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| helloSystem 0.7.0    | 27        | 7.18%   |
| helloSystem 0.8.1    | 24        | 6.38%   |
| helloSystem 0.8.0    | 17        | 4.52%   |
| helloSystem 0.4.0    | 15        | 3.99%   |
| helloSystem 0.6.0    | 14        | 3.72%   |
| helloSystem 0.5.0    | 14        | 3.72%   |
| OPNsense 23.1.11     | 10        | 2.66%   |
| OPNsense 23.1.7      | 8         | 2.13%   |
| FreeBSD 13.0         | 8         | 2.13%   |
| OPNsense 23.1.5      | 7         | 1.86%   |
| OPNsense 22.1.10     | 7         | 1.86%   |
| FreeBSD 14.0-CURRENT | 7         | 1.86%   |
| OPNsense 23.7.9      | 6         | 1.6%    |
| OPNsense 23.1        | 6         | 1.6%    |
| OPNsense 22.7.4      | 6         | 1.6%    |
| OPNsense 21.1.3      | 6         | 1.6%    |
| OPNsense 21.1        | 6         | 1.6%    |
| OPNsense 20.7.8      | 6         | 1.6%    |
| OpenBSD 7.3          | 6         | 1.6%    |
| OPNsense 23.1.9      | 5         | 1.33%   |
| OPNsense 22.7.8      | 5         | 1.33%   |
| OPNsense 22.7.5      | 5         | 1.33%   |
| OPNsense 21.1.2      | 5         | 1.33%   |
| OPNsense 21.1.1      | 5         | 1.33%   |
| FreeBSD 13.2         | 5         | 1.33%   |
| OPNsense 23.1.1      | 4         | 1.06%   |
| OPNsense 22.7.6      | 4         | 1.06%   |
| OPNsense 22.1.8      | 4         | 1.06%   |
| helloSystem 0.9.0    | 4         | 1.06%   |
| FreeBSD 13.0-p3      | 4         | 1.06%   |
| FreeBSD 12.1         | 4         | 1.06%   |
| OPNsense 23.7        | 3         | 0.8%    |
| OPNsense 22.7.9      | 3         | 0.8%    |
| OPNsense 22.7.10     | 3         | 0.8%    |
| OPNsense 21.7.7      | 3         | 0.8%    |
| OPNsense 21.7.1      | 3         | 0.8%    |
| OPNsense 21.1.9      | 3         | 0.8%    |
| OPNsense 21.1.7      | 3         | 0.8%    |
| OPNsense 21.1.6      | 3         | 0.8%    |
| OPNsense 21.1.4      | 3         | 0.8%    |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart_bsd/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| OPNsense    | 122       | 39.1%   |
| helloSystem | 108       | 34.62%  |
| FreeBSD     | 56        | 17.95%  |
| OpenBSD     | 10        | 3.21%   |
| GhostBSD    | 5         | 1.6%    |
| TrueNAS     | 2         | 0.64%   |
| pfSense     | 2         | 0.64%   |
| NomadBSD    | 2         | 0.64%   |
| FreeNAS     | 2         | 0.64%   |
| OS108       | 1         | 0.32%   |
| NetBSD      | 1         | 0.32%   |
| DragonFly   | 1         | 0.32%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart_bsd/os_arch.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| amd64 | 302       | 98.37%  |
| i386  | 4         | 1.3%    |
| arm64 | 1         | 0.33%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart_bsd/os_de.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Console      | 136       | 43.73%  |
| helloDesktop | 114       | 36.66%  |
| KDE5         | 13        | 4.18%   |
| XFCE         | 11        | 3.54%   |
| MATE         | 9         | 2.89%   |
| GNOME        | 7         | 2.25%   |
| TWM          | 5         | 1.61%   |
| Openbox      | 5         | 1.61%   |
| i3           | 4         | 1.29%   |
| fvwm         | 2         | 0.64%   |
| X-Cinnamon   | 1         | 0.32%   |
| Window Maker | 1         | 0.32%   |
| spectrwm     | 1         | 0.32%   |
| LXQt         | 1         | 0.32%   |
| AwesomeWM    | 1         | 0.32%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart_bsd/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 169       | 54.87%  |
| Console | 139       | 45.13%  |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart_bsd/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Console | 160       | 51.61%  |
| SLiM    | 117       | 37.74%  |
| SDDM    | 13        | 4.19%   |
| LightDM | 10        | 3.23%   |
| GDM     | 6         | 1.94%   |
| XDM     | 4         | 1.29%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart_bsd/os_lang.svg)


| Lang            | Computers | Percent |
|-----------------|-----------|---------|
| Unknown         | 144       | 45.86%  |
| en_US           | 88        | 28.03%  |
| pt_BR           | 33        | 10.51%  |
| C               | 29        | 9.24%   |
| pt              | 8         | 2.55%   |
| fr_FR           | 8         | 2.55%   |
| fr              | 1         | 0.32%   |
| en_US.ISO8859-1 | 1         | 0.32%   |
| en_GB           | 1         | 0.32%   |
| en              | 1         | 0.32%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 268       | 85.9%   |
| BIOS | 44        | 14.1%   |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart_bsd/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Zfs     | 153       | 48.42%  |
| Ufs     | 115       | 36.39%  |
| Cd9660  | 37        | 11.71%  |
| Ffs     | 10        | 3.16%   |
| Hammer2 | 1         | 0.32%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart_bsd/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 290       | 93.25%  |
| MBR     | 18        | 5.79%   |
| Unknown | 3         | 0.96%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart_bsd/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 59        | 19.22%  |
| ASUSTek Computer        | 38        | 12.38%  |
| Lenovo                  | 34        | 11.07%  |
| Unknown                 | 23        | 7.49%   |
| Intel                   | 21        | 6.84%   |
| Hewlett-Packard         | 14        | 4.56%   |
| Acer                    | 14        | 4.56%   |
| Gigabyte Technology     | 12        | 3.91%   |
| Samsung Electronics     | 9         | 2.93%   |
| ASRock                  | 7         | 2.28%   |
| AMI                     | 7         | 2.28%   |
| Apple                   | 6         | 1.95%   |
| Positivo                | 5         | 1.63%   |
| Sony                    | 4         | 1.3%    |
| MSI                     | 4         | 1.3%    |
| Itautec                 | 4         | 1.3%    |
| Techvision              | 3         | 0.98%   |
| Pegatron                | 3         | 0.98%   |
| PCWare                  | 3         | 0.98%   |
| Avell High Performance  | 3         | 0.98%   |
| Supermicro              | 2         | 0.65%   |
| Semp Toshiba            | 2         | 0.65%   |
| Gateway                 | 2         | 0.65%   |
| ECS                     | 2         | 0.65%   |
| Biostar                 | 2         | 0.65%   |
| YANYU                   | 1         | 0.33%   |
| Yanling                 | 1         | 0.33%   |
| ULTRATOP                | 1         | 0.33%   |
| T-bao                   | 1         | 0.33%   |
| Soyo                    | 1         | 0.33%   |
| Sophos                  | 1         | 0.33%   |
| Procomp Ind. Eletronica | 1         | 0.33%   |
| Philco                  | 1         | 0.33%   |
| Notebook                | 1         | 0.33%   |
| maiyunda                | 1         | 0.33%   |
| LG Electronics          | 1         | 0.33%   |
| KLLISRE                 | 1         | 0.33%   |
| IBM                     | 1         | 0.33%   |
| HC                      | 1         | 0.33%   |
| GPD                     | 1         | 0.33%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart_bsd/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 24        | 7.82%   |
| Intel Q3XXG4-P V1.0                 | 8         | 2.61%   |
| Dell Inspiron 3442                  | 6         | 1.95%   |
| AMI Aptio CRB                       | 5         | 1.63%   |
| ASUS All Series                     | 4         | 1.3%    |
| Techvision TVI7309X                 | 3         | 0.98%   |
| Dell Inspiron 3421                  | 3         | 0.98%   |
| Samsung 340XAA/350XAA/550XAA        | 2         | 0.65%   |
| Samsung 270E5K/270E5Q/271E5K/2570EK | 2         | 0.65%   |
| Pegatron IPM41-D3                   | 2         | 0.65%   |
| Lenovo IdeaPadFlex 5 14ITL05 82LT   | 2         | 0.65%   |
| Intel H81                           | 2         | 0.65%   |
| Intel H55                           | 2         | 0.65%   |
| Gigabyte H61M-S2-B3                 | 2         | 0.65%   |
| Gateway NE56R                       | 2         | 0.65%   |
| Dell PowerEdge R620                 | 2         | 0.65%   |
| Dell PowerEdge 1950                 | 2         | 0.65%   |
| Dell OptiPlex 7040                  | 2         | 0.65%   |
| Dell Latitude 5490                  | 2         | 0.65%   |
| ASUS TUF Gaming B550M-PLUS          | 2         | 0.65%   |
| ASUS PRIME B450M-GAMING/BR          | 2         | 0.65%   |
| ASUS PRIME A520M-E                  | 2         | 0.65%   |
| ASUS P8H61-M LX3 PLUS R2.0          | 2         | 0.65%   |
| ASUS P5G41T-M LX2/BR                | 2         | 0.65%   |
| ASUS M5A78L-M LX/BR                 | 2         | 0.65%   |
| ASUS A88XM-A                        | 2         | 0.65%   |
| ASRock J4005B-ITX                   | 2         | 0.65%   |
| Acer Aspire 5750                    | 2         | 0.65%   |
| YANYU N39SL                         | 1         | 0.33%   |
| Yanling NS-1U8L                     | 1         | 0.33%   |
| ULTRATOP C2017-LIVA-ZE              | 1         | 0.33%   |
| T-bao MINI PC                       | 1         | 0.33%   |
| Supermicro X10SLL-F                 | 1         | 0.33%   |
| Supermicro NSMPX-17500              | 1         | 0.33%   |
| Soyo SY-YL B550M                    | 1         | 0.33%   |
| Sophos SG                           | 1         | 0.33%   |
| Sony VPCYB45JB                      | 1         | 0.33%   |
| Sony VPCEG17FB                      | 1         | 0.33%   |
| Sony VPCEG15FB                      | 1         | 0.33%   |
| Sony SVF14A15CBB                    | 1         | 0.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart_bsd/node_model_family.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Unknown                    | 24        | 7.82%   |
| Dell Inspiron              | 21        | 6.84%   |
| Lenovo ThinkPad            | 17        | 5.54%   |
| Dell PowerEdge             | 14        | 4.56%   |
| Dell OptiPlex              | 12        | 3.91%   |
| Acer Aspire                | 12        | 3.91%   |
| Intel Q3XXG4-P             | 8         | 2.61%   |
| HP ProLiant                | 6         | 1.95%   |
| Dell Vostro                | 6         | 1.95%   |
| AMI Aptio                  | 6         | 1.95%   |
| Lenovo IdeaPad             | 5         | 1.63%   |
| ASUS PRIME                 | 5         | 1.63%   |
| Itautec Infoway            | 4         | 1.3%    |
| Dell Latitude              | 4         | 1.3%    |
| ASUS All                   | 4         | 1.3%    |
| Techvision TVI7309X        | 3         | 0.98%   |
| Lenovo ThinkCentre         | 3         | 0.98%   |
| ASUS TUF                   | 3         | 0.98%   |
| ASUS P8H61-M               | 3         | 0.98%   |
| ASUS P5G41T-M              | 3         | 0.98%   |
| ASUS M5A78L-M              | 3         | 0.98%   |
| Semp Toshiba STI           | 2         | 0.65%   |
| Samsung 340XAA             | 2         | 0.65%   |
| Samsung 270E5K             | 2         | 0.65%   |
| Pegatron IPM41-D3          | 2         | 0.65%   |
| Lenovo IdeaPadFlex         | 2         | 0.65%   |
| Intel H81                  | 2         | 0.65%   |
| Intel H55                  | 2         | 0.65%   |
| HP Compaq                  | 2         | 0.65%   |
| Gigabyte H61M-S2-B3        | 2         | 0.65%   |
| Gateway NE56R              | 2         | 0.65%   |
| Avell High Performance A62 | 2         | 0.65%   |
| ASUS A88XM-A               | 2         | 0.65%   |
| ASRock J4005B-ITX          | 2         | 0.65%   |
| YANYU N39SL                | 1         | 0.33%   |
| Yanling NS-1U8L            | 1         | 0.33%   |
| ULTRATOP C2017-LIVA-ZE     | 1         | 0.33%   |
| T-bao MINI                 | 1         | 0.33%   |
| Supermicro X10SLL-F        | 1         | 0.33%   |
| Supermicro NSMPX-17500     | 1         | 0.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart_bsd/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2013    | 34        | 11.07%  |
| 2016    | 28        | 9.12%   |
| 2018    | 27        | 8.79%   |
| 2022    | 25        | 8.14%   |
| 2011    | 22        | 7.17%   |
| 2019    | 20        | 6.51%   |
| 2020    | 19        | 6.19%   |
| 2014    | 18        | 5.86%   |
| 2010    | 18        | 5.86%   |
| 2021    | 17        | 5.54%   |
| 2017    | 16        | 5.21%   |
| 2012    | 14        | 4.56%   |
| 2009    | 12        | 3.91%   |
| 2015    | 11        | 3.58%   |
| 2008    | 11        | 3.58%   |
| 2023    | 6         | 1.95%   |
| 2007    | 5         | 1.63%   |
| Unknown | 4         | 1.3%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart_bsd/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Desktop     | 166       | 54.07%  |
| Notebook    | 105       | 34.2%   |
| Server      | 20        | 6.51%   |
| Mini pc     | 8         | 2.61%   |
| All in one  | 4         | 1.3%    |
| Convertible | 3         | 0.98%   |
| Firewall    | 1         | 0.33%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart_bsd/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 307       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 128       | 40.38%  |
| 4.01-8.0    | 96        | 30.28%  |
| 16.01-24.0  | 55        | 17.35%  |
| 32.01-64.0  | 12        | 3.79%   |
| 2.01-3.0    | 12        | 3.79%   |
| 64.01-256.0 | 6         | 1.89%   |
| 24.01-32.0  | 5         | 1.58%   |
| 3.01-4.0    | 3         | 0.95%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart_bsd/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 0.01-0.5   | 191       | 60.44%  |
| 0.51-1.0   | 85        | 26.9%   |
| 1.01-2.0   | 24        | 7.59%   |
| 2.01-3.0   | 7         | 2.22%   |
| 4.01-8.0   | 3         | 0.95%   |
| Unknown    | 2         | 0.63%   |
| 32.01-64.0 | 1         | 0.32%   |
| 24.01-32.0 | 1         | 0.32%   |
| 16.01-24.0 | 1         | 0.32%   |
| 8.01-16.0  | 1         | 0.32%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart_bsd/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 210       | 66.67%  |
| 2      | 46        | 14.6%   |
| 0      | 37        | 11.75%  |
| 3      | 12        | 3.81%   |
| 4      | 5         | 1.59%   |
| 5      | 3         | 0.95%   |
| 7      | 1         | 0.32%   |
| 6      | 1         | 0.32%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 219       | 71.1%   |
| Yes       | 89        | 28.9%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 291       | 94.79%  |
| No        | 16        | 5.21%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 170       | 55.37%  |
| Yes       | 137       | 44.63%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 209       | 68.08%  |
| Yes       | 98        | 31.92%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart_bsd/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Brazil  | 307       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart_bsd/node_city.svg)


| City                      | Computers | Percent |
|---------------------------|-----------|---------|
| Sao Paulo                 | 26        | 7.65%   |
| SГЈo Paulo              | 19        | 5.59%   |
| Rio de Janeiro            | 19        | 5.59%   |
| Curitiba                  | 13        | 3.82%   |
| Sao José dos Campos      | 7         | 2.06%   |
| Campinas                  | 7         | 2.06%   |
| Blumenau                  | 7         | 2.06%   |
| Belo Horizonte            | 7         | 2.06%   |
| SÃ£o Paulo              | 6         | 1.76%   |
| Porto Alegre              | 6         | 1.76%   |
| Jaraguá do Sul           | 6         | 1.76%   |
| Manaus                    | 5         | 1.47%   |
| Fortaleza                 | 5         | 1.47%   |
| Brasília                 | 5         | 1.47%   |
| Osasco                    | 4         | 1.18%   |
| Florianópolis            | 4         | 1.18%   |
| SГЈo JosГ© dos Campos | 3         | 0.88%   |
| Novo Hamburgo             | 3         | 0.88%   |
| Maringá                  | 3         | 0.88%   |
| Londrina                  | 3         | 0.88%   |
| JoГЈo Pessoa            | 3         | 0.88%   |
| Uberaba                   | 2         | 0.59%   |
| Teresina                  | 2         | 0.59%   |
| Taubate                   | 2         | 0.59%   |
| Sorocaba                  | 2         | 0.59%   |
| Serra                     | 2         | 0.59%   |
| Sao Vicente               | 2         | 0.59%   |
| Sao Leopoldo              | 2         | 0.59%   |
| Sao Jose do Rio Preto     | 2         | 0.59%   |
| Sao Bernardo do Campo     | 2         | 0.59%   |
| Salvador                  | 2         | 0.59%   |
| RondonГіpolis           | 2         | 0.59%   |
| Rio das Ostras            | 2         | 0.59%   |
| Rio Claro                 | 2         | 0.59%   |
| Recife                    | 2         | 0.59%   |
| Pirapora                  | 2         | 0.59%   |
| Pelotas                   | 2         | 0.59%   |
| Maraba                    | 2         | 0.59%   |
| Maceió                   | 2         | 0.59%   |
| Jundiaí                  | 2         | 0.59%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 57        | 70     | 15.79%  |
| Kingston            | 55        | 73     | 15.24%  |
| Seagate             | 53        | 107    | 14.68%  |
| Samsung Electronics | 34        | 46     | 9.42%   |
| Toshiba             | 19        | 19     | 5.26%   |
| SanDisk             | 19        | 23     | 5.26%   |
| A-DATA Technology   | 15        | 16     | 4.16%   |
| Crucial             | 12        | 17     | 3.32%   |
| China               | 10        | 13     | 2.77%   |
| Hoodisk             | 8         | 8      | 2.22%   |
| Silicon Motion      | 7         | 8      | 1.94%   |
| KingSpec            | 7         | 8      | 1.94%   |
| NVMe                | 5         | 7      | 1.39%   |
| Hitachi             | 5         | 9      | 1.39%   |
| LITEON              | 4         | 4      | 1.11%   |
| XrayDisk            | 3         | 3      | 0.83%   |
| SSSTC               | 3         | 3      | 0.83%   |
| SK hynix            | 3         | 3      | 0.83%   |
| PNY                 | 3         | 3      | 0.83%   |
| Netac               | 3         | 3      | 0.83%   |
| Hewlett-Packard     | 3         | 4      | 0.83%   |
| Gigabyte Technology | 3         | 4      | 0.83%   |
| Fanxiang            | 3         | 4      | 0.83%   |
| Patriot             | 2         | 5      | 0.55%   |
| NTC                 | 2         | 2      | 0.55%   |
| Lexar               | 2         | 3      | 0.55%   |
| Kston               | 2         | 2      | 0.55%   |
| HGST                | 2         | 3      | 0.55%   |
| Transcend           | 1         | 2      | 0.28%   |
| SMI                 | 1         | 1      | 0.28%   |
| Smart               | 1         | 1      | 0.28%   |
| Silicon             | 1         | 1      | 0.28%   |
| Phison              | 1         | 1      | 0.28%   |
| Maxtor              | 1         | 1      | 0.28%   |
| MACROVIP            | 1         | 1      | 0.28%   |
| Intel               | 1         | 2      | 0.28%   |
| Indilinx            | 1         | 2      | 0.28%   |
| Hikvision           | 1         | 1      | 0.28%   |
| Faspeed             | 1         | 1      | 0.28%   |
| Drevo               | 1         | 6      | 0.28%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart_bsd/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB         | 14        | 3.63%   |
| SanDisk SSD PLUS 120GB              | 10        | 2.59%   |
| Kingston SA400S37120G 120GB         | 9         | 2.33%   |
| Kingston SA400S37480G 480GB         | 8         | 2.07%   |
| Seagate ST500DM002-1BD142 500GB     | 6         | 1.55%   |
| Hoodisk SSD 64GB                    | 6         | 1.55%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 5         | 1.3%    |
| Kingston SA400S37960G 960GB         | 5         | 1.3%    |
| Toshiba MQ01ABD100 1TB              | 4         | 1.04%   |
| Seagate ST1000DM010-2EP102 1TB      | 4         | 1.04%   |
| Samsung HD502HJ 500GB               | 4         | 1.04%   |
| Samsung HD322HJ 320GB               | 4         | 1.04%   |
| WDC WD10EZEX-00RKKA0 1TB            | 3         | 0.78%   |
| Seagate ST500LT012-9WS142 500GB     | 3         | 0.78%   |
| Seagate ST4000DM000-1F2168 4TB      | 3         | 0.78%   |
| Seagate ST1000LM048-2E7172 1TB      | 3         | 0.78%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 3         | 0.78%   |
| SanDisk SDSSDA240G 240GB            | 3         | 0.78%   |
| Samsung HM321HI 320GB               | 3         | 0.78%   |
| Samsung HD103SJ 1TB                 | 3         | 0.78%   |
| Kingston SUV400S37120G 120GB        | 3         | 0.78%   |
| Gigabyte GP-GSTFS31120GNTD 120GB    | 3         | 0.78%   |
| Crucial CT120BX500SSD1 120GB        | 3         | 0.78%   |
| A-DATA SU630 240GB                  | 3         | 0.78%   |
| WDC WDS480G2G0B-00EPW0 480GB        | 2         | 0.52%   |
| WDC WDS240G2G0A-00JH30 240GB        | 2         | 0.52%   |
| WDC WDS120G2G0A-00JH30 120GB        | 2         | 0.52%   |
| WDC WD5000AAKX-00U6AA0 500GB        | 2         | 0.52%   |
| WDC WD3200AAJS-00YZCA0 320GB        | 2         | 0.52%   |
| WDC WD2500BEVT-75ZCT2 250GB         | 2         | 0.52%   |
| WDC WD10SPZX-24Z10 1TB              | 2         | 0.52%   |
| WDC WD10JPVX-80JC3T0 1TB            | 2         | 0.52%   |
| SSSTC CL1-4D256 256GB               | 2         | 0.52%   |
| Silicon Motion NVME SSD 128GB       | 2         | 0.52%   |
| Silicon Motion NE-256 256GB         | 2         | 0.52%   |
| Seagate ST9320325AS 320GB           | 2         | 0.52%   |
| Seagate ST9160314AS 160GB           | 2         | 0.52%   |
| Seagate ST750LM022 HN-M750MBB 752GB | 2         | 0.52%   |
| Seagate ST2000LM007-1R8174 2TB      | 2         | 0.52%   |
| Seagate ST2000DM006-2DM164 2TB      | 2         | 0.52%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 53        | 107    | 33.33%  |
| WDC                 | 51        | 60     | 32.08%  |
| Samsung Electronics | 23        | 32     | 14.47%  |
| Toshiba             | 18        | 18     | 11.32%  |
| Hitachi             | 5         | 9      | 3.14%   |
| NVMe                | 3         | 5      | 1.89%   |
| Hewlett-Packard     | 3         | 4      | 1.89%   |
| SMI                 | 1         | 1      | 0.63%   |
| Maxtor              | 1         | 1      | 0.63%   |
| HGST                | 1         | 2      | 0.63%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 51        | 69     | 30%     |
| SanDisk             | 19        | 23     | 11.18%  |
| Crucial             | 11        | 16     | 6.47%   |
| China               | 10        | 13     | 5.88%   |
| A-DATA Technology   | 9         | 10     | 5.29%   |
| WDC                 | 8         | 10     | 4.71%   |
| Samsung Electronics | 8         | 8      | 4.71%   |
| Hoodisk             | 8         | 8      | 4.71%   |
| KingSpec            | 7         | 8      | 4.12%   |
| LITEON              | 4         | 4      | 2.35%   |
| XrayDisk            | 3         | 3      | 1.76%   |
| PNY                 | 3         | 3      | 1.76%   |
| Gigabyte Technology | 3         | 4      | 1.76%   |
| SK hynix            | 2         | 2      | 1.18%   |
| Patriot             | 2         | 5      | 1.18%   |
| NTC                 | 2         | 2      | 1.18%   |
| Kston               | 2         | 2      | 1.18%   |
| Transcend           | 1         | 2      | 0.59%   |
| Smart               | 1         | 1      | 0.59%   |
| Silicon             | 1         | 1      | 0.59%   |
| NVMe                | 1         | 1      | 0.59%   |
| Netac               | 1         | 1      | 0.59%   |
| MACROVIP            | 1         | 1      | 0.59%   |
| Lexar               | 1         | 1      | 0.59%   |
| Intel               | 1         | 2      | 0.59%   |
| Indilinx            | 1         | 2      | 0.59%   |
| Hikvision           | 1         | 1      | 0.59%   |
| HGST                | 1         | 1      | 0.59%   |
| Faspeed             | 1         | 1      | 0.59%   |
| Fanxiang            | 1         | 1      | 0.59%   |
| Drevo               | 1         | 6      | 0.59%   |
| Corsair             | 1         | 1      | 0.59%   |
| Biostar             | 1         | 1      | 0.59%   |
| BHT                 | 1         | 1      | 0.59%   |
| Apple               | 1         | 1      | 0.59%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart_bsd/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 153       | 216    | 47.66%  |
| HDD  | 134       | 239    | 41.74%  |
| NVMe | 34        | 40     | 10.59%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart_bsd/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 243       | 455    | 87.73%  |
| NVMe | 34        | 40     | 12.27%  |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart_bsd/drive_size.svg)


| Size in TB      | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 211       | 323    | 74.3%   |
| 0.51-1.0        | 52        | 71     | 18.31%  |
| 1.01-2.0        | 15        | 27     | 5.28%   |
| 3.01-4.0        | 5         | 33     | 1.76%   |
| More than 100.0 | 1         | 1      | 0.35%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart_bsd/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 101       | 30.61%  |
| 1-20           | 71        | 21.52%  |
| 251-500        | 53        | 16.06%  |
| 51-100         | 39        | 11.82%  |
| 21-50          | 29        | 8.79%   |
| 501-1000       | 23        | 6.97%   |
| 1001-2000      | 8         | 2.42%   |
| 2001-3000      | 4         | 1.21%   |
| More than 3000 | 1         | 0.3%    |
| Unknown        | 1         | 0.3%    |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart_bsd/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 275       | 88.42%  |
| 21-50     | 20        | 6.43%   |
| 101-250   | 6         | 1.93%   |
| 501-1000  | 5         | 1.61%   |
| 51-100    | 3         | 0.96%   |
| 2001-3000 | 1         | 0.32%   |
| Unknown   | 1         | 0.32%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart_bsd/drive_malfunc.svg)


| Model                                     | Computers | Drives | Percent |
|-------------------------------------------|-----------|--------|---------|
| Seagate ST500LT012-9WS142 500GB           | 3         | 3      | 3.33%   |
| Samsung Electronics HD322HJ 320GB         | 3         | 4      | 3.33%   |
| WDC WD10EZEX-00RKKA0 1TB                  | 2         | 2      | 2.22%   |
| Toshiba MQ01ABD100 1TB                    | 2         | 2      | 2.22%   |
| Seagate ST9320325AS 320GB                 | 2         | 2      | 2.22%   |
| Seagate ST9160314AS 160GB                 | 2         | 2      | 2.22%   |
| Seagate ST500DM002-1BD142 500GB           | 2         | 2      | 2.22%   |
| Samsung Electronics HM321HI 320GB         | 2         | 2      | 2.22%   |
| Samsung Electronics HD502HJ 500GB         | 2         | 3      | 2.22%   |
| Samsung Electronics HD161HJ 160GB         | 2         | 2      | 2.22%   |
| XrayDisk SSD 240GB                        | 1         | 1      | 1.11%   |
| WDC WD5000LPVX-22V0TT0 500GB              | 1         | 1      | 1.11%   |
| WDC WD5000B 500GB                         | 1         | 1      | 1.11%   |
| WDC WD5000AVVS-63H0B1 500GB               | 1         | 1      | 1.11%   |
| WDC WD5000AAKX-00U6AA0 500GB              | 1         | 1      | 1.11%   |
| WDC WD5000AAKX-00ERMA0 500GB              | 1         | 1      | 1.11%   |
| WDC WD5000AAKS-08V0A0 500GB               | 1         | 1      | 1.11%   |
| WDC WD5000AAKS-00UU3A0 500GB              | 1         | 1      | 1.11%   |
| WDC WD3200LPVX-22V0TT0 320GB              | 1         | 1      | 1.11%   |
| WDC WD3200BEVT-00A0RT0 233GB              | 1         | 1      | 1.11%   |
| WDC WD3200AAKS-00UU3A0 320GB              | 1         | 1      | 1.11%   |
| WDC WD3200AAJS-56M0A0 320GB               | 1         | 1      | 1.11%   |
| WDC WD3200AAJS-00YZCA0 320GB              | 1         | 1      | 1.11%   |
| WDC WD2500AAJS-75M0A0 250GB               | 1         | 1      | 1.11%   |
| WDC WD1600BEVS-60RST0 160GB               | 1         | 1      | 1.11%   |
| WDC WD10PURX-64E5EY0 1TB                  | 1         | 1      | 1.11%   |
| WDC WD10JPVX-75JC3T0 1TB                  | 1         | 1      | 1.11%   |
| WDC WD10EADS-65M2BX 1TB                   | 1         | 1      | 1.11%   |
| Transcend TS32GMSM610 32GB                | 1         | 2      | 1.11%   |
| Toshiba MQ01ABD050 500GB                  | 1         | 1      | 1.11%   |
| Toshiba MK8052GSX 80GB                    | 1         | 1      | 1.11%   |
| Toshiba MK6034GSX 64GB                    | 1         | 1      | 1.11%   |
| Toshiba MK5076GSX 500GB                   | 1         | 1      | 1.11%   |
| Toshiba MK3261GSYN 320GB                  | 1         | 1      | 1.11%   |
| Toshiba MK2555GSXF 250GB                  | 1         | 1      | 1.11%   |
| Toshiba MK1255GSX H 120GB                 | 1         | 1      | 1.11%   |
| Toshiba MK1252GSX 120GB                   | 1         | 1      | 1.11%   |
| Toshiba MK1246GSX 120GB                   | 1         | 1      | 1.11%   |
| SK hynix HFS128G39TND-N210A 128GB         | 1         | 1      | 1.11%   |
| Silicon Motion Asgard AN1TNVMe-M.2-80 1TB | 1         | 1      | 1.11%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 24        | 33     | 27.59%  |
| WDC                 | 17        | 19     | 19.54%  |
| Samsung Electronics | 13        | 17     | 14.94%  |
| Toshiba             | 11        | 11     | 12.64%  |
| Hitachi             | 5         | 9      | 5.75%   |
| Kingston            | 3         | 3      | 3.45%   |
| SanDisk             | 2         | 2      | 2.3%    |
| A-DATA Technology   | 2         | 2      | 2.3%    |
| XrayDisk            | 1         | 1      | 1.15%   |
| Transcend           | 1         | 2      | 1.15%   |
| SK hynix            | 1         | 1      | 1.15%   |
| Silicon Motion      | 1         | 1      | 1.15%   |
| Netac               | 1         | 1      | 1.15%   |
| Maxtor              | 1         | 1      | 1.15%   |
| LITEON              | 1         | 1      | 1.15%   |
| KingSpec            | 1         | 1      | 1.15%   |
| HGST                | 1         | 1      | 1.15%   |
| Corsair             | 1         | 1      | 1.15%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 24        | 33     | 33.8%   |
| WDC                 | 17        | 19     | 23.94%  |
| Samsung Electronics | 13        | 17     | 18.31%  |
| Toshiba             | 11        | 11     | 15.49%  |
| Hitachi             | 5         | 9      | 7.04%   |
| Maxtor              | 1         | 1      | 1.41%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 63        | 90     | 79.75%  |
| SSD  | 15        | 16     | 18.99%  |
| NVMe | 1         | 1      | 1.27%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart_bsd/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD3200AAJS-00YZCA0 320GB      | 1         | 1      | 33.33%  |
| Samsung Electronics HM500JJ 500GB | 1         | 1      | 33.33%  |
| Samsung Electronics HD103SJ 1TB   | 1         | 2      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart_bsd/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 2         | 3      | 66.67%  |
| WDC                 | 1         | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart_bsd/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 222       | 369    | 70.93%  |
| Malfunc  | 77        | 107    | 24.6%   |
| Detected | 11        | 15     | 3.51%   |
| Failed   | 3         | 4      | 0.96%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart_bsd/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 258       | 72.07%  |
| AMD                            | 36        | 10.06%  |
| Silicon Motion                 | 13        | 3.63%   |
| Broadcom / LSI                 | 12        | 3.35%   |
| ADATA Technology               | 6         | 1.68%   |
| Kingston Technology Company    | 5         | 1.4%    |
| Solid State Storage Technology | 4         | 1.12%   |
| Nvidia                         | 4         | 1.12%   |
| Samsung Electronics            | 3         | 0.84%   |
| SK hynix                       | 2         | 0.56%   |
| Realtek Semiconductor          | 2         | 0.56%   |
| MAXIO Technology (Hangzhou)    | 2         | 0.56%   |
| Hewlett-Packard                | 2         | 0.56%   |
| Toshiba                        | 1         | 0.28%   |
| Shenzhen Longsys Electronics   | 1         | 0.28%   |
| Phison Electronics             | 1         | 0.28%   |
| Micron/Crucial Technology      | 1         | 0.28%   |
| JMicron Technology             | 1         | 0.28%   |
| Integrated Technology Express  | 1         | 0.28%   |
| Biwin Storage Technology       | 1         | 0.28%   |
| ASMedia Technology             | 1         | 0.28%   |
| Adaptec                        | 1         | 0.28%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart_bsd/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 23        | 5.56%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 19        | 4.59%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 17        | 4.11%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 15        | 3.62%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 15        | 3.62%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 14        | 3.38%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 13        | 3.14%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 13        | 3.14%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 13        | 3.14%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 11        | 2.66%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 10        | 2.42%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 9         | 2.17%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 9         | 2.17%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 9         | 2.17%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 9         | 2.17%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 9         | 2.17%   |
| Intel Jasper Lake SATA AHCI Controller                                                  | 8         | 1.93%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 8         | 1.93%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 8         | 1.93%   |
| Intel SATA Controller [RAID mode]                                                       | 7         | 1.69%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 7         | 1.69%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 6         | 1.45%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 5         | 1.21%   |
| AMD 500 Series Chipset SATA Controller                                                  | 5         | 1.21%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                          | 4         | 0.97%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 4         | 0.97%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 4         | 0.97%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 4         | 0.97%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 4         | 0.97%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 4         | 0.97%   |
| Broadcom / LSI MegaRAID SAS 2008 [Falcon]                                               | 4         | 0.97%   |
| ADATA IM2P33F8 series NVMe SSD (DRAM-less)                                              | 4         | 0.97%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 3         | 0.72%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 3         | 0.72%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 3         | 0.72%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 3         | 0.72%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 3         | 0.72%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 3         | 0.72%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 3         | 0.72%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 3         | 0.72%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart_bsd/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 232       | 63.91%  |
| IDE  | 63        | 17.36%  |
| NVMe | 41        | 11.29%  |
| RAID | 25        | 6.89%   |
| SAS  | 1         | 0.28%   |
| SCSI | 1         | 0.28%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart_bsd/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 267       | 86.41%  |
| AMD     | 41        | 13.27%  |
| Unknown | 1         | 0.32%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Celeron N5105 @ 2.00GHz               | 6         | 1.94%   |
| Intel Core i3-4005U CPU @ 1.70GHz           | 5         | 1.61%   |
| Intel Celeron J4125 CPU @ 2.00GHz           | 5         | 1.61%   |
| Intel Celeron CPU J1900 @ 1.99GHz           | 5         | 1.61%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 4         | 1.29%   |
| Intel Core i3-7100 CPU @ 3.90GHz            | 4         | 1.29%   |
| Intel Core i3-5005U CPU @ 2.00GHz           | 4         | 1.29%   |
| Intel Celeron CPU J1800 @ 2.41GHz           | 4         | 1.29%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 3         | 0.97%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 3         | 0.97%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 3         | 0.97%   |
| Intel Core i5-3337U CPU @ 1.80GHz           | 3         | 0.97%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 3         | 0.97%   |
| Intel Core i3-6100U CPU @ 2.30GHz           | 3         | 0.97%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 3         | 0.97%   |
| Intel Core 2 Quad CPU Q8400 @ 2.66GHz       | 3         | 0.97%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 3         | 0.97%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 3         | 0.97%   |
| Intel Celeron CPU N3350 @ 1.10GHz           | 3         | 0.97%   |
| Intel Celeron CPU 847 @ 1.10GHz             | 3         | 0.97%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 3         | 0.97%   |
| AMD FX-8320E Eight-Core Processor           | 3         | 0.97%   |
| Intel Xeon CPU E5620 @ 2.40GHz              | 2         | 0.65%   |
| Intel Xeon CPU E5506 @ 2.13GHz              | 2         | 0.65%   |
| Intel Xeon CPU E5-2609 v2 @ 2.50GHz         | 2         | 0.65%   |
| Intel Xeon CPU E3-1220 v3 @ 3.10GHz         | 2         | 0.65%   |
| Intel Pentium Silver N6005 @ 2.00GHz        | 2         | 0.65%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 2         | 0.65%   |
| Intel CPU Version                           | 2         | 0.65%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 2         | 0.65%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 2         | 0.65%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 2         | 0.65%   |
| Intel Core i7-5600U CPU @ 2.60GHz           | 2         | 0.65%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 2         | 0.65%   |
| Intel Core i5-9400 CPU @ 2.90GHz            | 2         | 0.65%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 2         | 0.65%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 2         | 0.65%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 2         | 0.65%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 2         | 0.65%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 2         | 0.65%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart_bsd/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 68        | 22.01%  |
| Intel Core i3           | 47        | 15.21%  |
| Intel Celeron           | 41        | 13.27%  |
| Intel Xeon              | 28        | 9.06%   |
| Intel Core i7           | 24        | 7.77%   |
| Intel Core 2 Duo        | 19        | 6.15%   |
| Other                   | 10        | 3.24%   |
| AMD Ryzen 7             | 8         | 2.59%   |
| AMD FX                  | 8         | 2.59%   |
| Intel Pentium           | 7         | 2.27%   |
| AMD Ryzen 5             | 7         | 2.27%   |
| Intel Pentium Dual-Core | 6         | 1.94%   |
| Intel Atom              | 6         | 1.94%   |
| Intel Core 2 Quad       | 5         | 1.62%   |
| Intel Pentium Silver    | 2         | 0.65%   |
| AMD E1                  | 2         | 0.65%   |
| AMD E                   | 2         | 0.65%   |
| AMD A10                 | 2         | 0.65%   |
| Intel Xeon Silver       | 1         | 0.32%   |
| Intel Pentium M         | 1         | 0.32%   |
| Intel Pentium Dual      | 1         | 0.32%   |
| Intel Genuine           | 1         | 0.32%   |
| Intel Core M            | 1         | 0.32%   |
| Intel Core 2            | 1         | 0.32%   |
| AMD Turion II Neo       | 1         | 0.32%   |
| AMD Ryzen 5 PRO         | 1         | 0.32%   |
| AMD Ryzen 3 PRO         | 1         | 0.32%   |
| AMD Ryzen 3             | 1         | 0.32%   |
| AMD PRO A8              | 1         | 0.32%   |
| AMD Phenom              | 1         | 0.32%   |
| AMD C-60                | 1         | 0.32%   |
| AMD C-50                | 1         | 0.32%   |
| AMD Athlon II X2        | 1         | 0.32%   |
| AMD Athlon 64 X2        | 1         | 0.32%   |
| AMD Athlon              | 1         | 0.32%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart_bsd/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 144       | 46.3%   |
| 4       | 102       | 32.8%   |
| 8       | 23        | 7.4%    |
| Unknown | 14        | 4.5%    |
| 6       | 13        | 4.18%   |
| 12      | 7         | 2.25%   |
| 16      | 5         | 1.61%   |
| 1       | 2         | 0.64%   |
| 24      | 1         | 0.32%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 291       | 94.79%  |
| 2       | 14        | 4.56%   |
| Unknown | 2         | 0.65%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart_bsd/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 161       | 52.27%  |
| 2       | 133       | 43.18%  |
| Unknown | 14        | 4.55%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart_bsd/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 38        | 12.26%  |
| Penryn        | 30        | 9.68%   |
| IvyBridge     | 30        | 9.68%   |
| SandyBridge   | 28        | 9.03%   |
| Haswell       | 28        | 9.03%   |
| Unknown       | 18        | 5.81%   |
| Skylake       | 17        | 5.48%   |
| Silvermont    | 14        | 4.52%   |
| Broadwell     | 13        | 4.19%   |
| Westmere      | 12        | 3.87%   |
| Goldmont plus | 10        | 3.23%   |
| Core          | 10        | 3.23%   |
| Zen+          | 9         | 2.9%    |
| Piledriver    | 6         | 1.94%   |
| Nehalem       | 6         | 1.94%   |
| Bobcat        | 6         | 1.94%   |
| Zen 3         | 5         | 1.61%   |
| Goldmont      | 4         | 1.29%   |
| CometLake     | 4         | 1.29%   |
| Bonnell       | 4         | 1.29%   |
| TigerLake     | 3         | 0.97%   |
| Steamroller   | 3         | 0.97%   |
| K10           | 3         | 0.97%   |
| Zen 2         | 2         | 0.65%   |
| Zen           | 2         | 0.65%   |
| IceLake       | 2         | 0.65%   |
| Bulldozer     | 2         | 0.65%   |
| K8 Hammer     | 1         | 0.32%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart_bsd/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 221       | 66.57%  |
| AMD                        | 50        | 15.06%  |
| Nvidia                     | 41        | 12.35%  |
| Matrox Electronics Systems | 18        | 5.42%   |
| ASPEED Technology          | 2         | 0.6%    |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart_bsd/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 23        | 6.78%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 14        | 4.13%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 14        | 4.13%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 13        | 3.83%   |
| Intel HD Graphics 5500                                                      | 12        | 3.54%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 12        | 3.54%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 10        | 2.95%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 9         | 2.65%   |
| Intel JasperLake [UHD Graphics]                                             | 9         | 2.65%   |
| Intel HD Graphics 630                                                       | 9         | 2.65%   |
| Intel Core Processor Integrated Graphics Controller                         | 9         | 2.65%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 8         | 2.36%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 8         | 2.36%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 7         | 2.06%   |
| Intel UHD Graphics 620                                                      | 6         | 1.77%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 6         | 1.77%   |
| Matrox Electronics Systems G200eR2                                          | 5         | 1.47%   |
| Intel HD Graphics 530                                                       | 5         | 1.47%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 5         | 1.47%   |
| Matrox Electronics Systems MGA G200eW WPCM450                               | 4         | 1.18%   |
| Matrox Electronics Systems MGA G200EH                                       | 4         | 1.18%   |
| Intel HD Graphics 620                                                       | 4         | 1.18%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 4         | 1.18%   |
| AMD ES1000                                                                  | 4         | 1.18%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 4         | 1.18%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 3         | 0.88%   |
| Nvidia GK208B [GeForce GT 710]                                              | 3         | 0.88%   |
| Matrox Electronics Systems Integrated Matrox G200eW3 Graphics Controller    | 3         | 0.88%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 3         | 0.88%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 3         | 0.88%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)         | 3         | 0.88%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)           | 3         | 0.88%   |
| Intel HD Graphics 500                                                       | 3         | 0.88%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 3         | 0.88%   |
| AMD RV710 [Radeon HD 4350/4550]                                             | 3         | 0.88%   |
| AMD Kaveri [Radeon R7 Graphics]                                             | 3         | 0.88%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 3         | 0.88%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 3         | 0.88%   |
| Nvidia GT218 [GeForce 210]                                                  | 2         | 0.59%   |
| Nvidia GP108M [GeForce MX250]                                               | 2         | 0.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart_bsd/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 184       | 59.35%  |
| 1 x AMD        | 44        | 14.19%  |
| 1 x Nvidia     | 22        | 7.1%    |
| Intel + Nvidia | 19        | 6.13%   |
| 1 x Matrox     | 18        | 5.81%   |
| 2 x Intel      | 12        | 3.87%   |
| Intel + AMD    | 6         | 1.94%   |
| Other          | 3         | 0.97%   |
| 1 x ASPEED     | 2         | 0.65%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 286       | 92.56%  |
| Proprietary | 18        | 5.83%   |
| Unknown     | 5         | 1.62%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 267       | 85.3%   |
| 0.01-0.5   | 12        | 3.83%   |
| 0.51-1.0   | 11        | 3.51%   |
| 1.01-2.0   | 10        | 3.19%   |
| 3.01-4.0   | 9         | 2.88%   |
| 7.01-8.0   | 3         | 0.96%   |
| 2.01-3.0   | 1         | 0.32%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 27        | 19.15%  |
| Goldstar                | 22        | 15.6%   |
| Samsung Electronics     | 19        | 13.48%  |
| LG Display              | 14        | 9.93%   |
| BOE                     | 11        | 7.8%    |
| Chimei Innolux          | 10        | 7.09%   |
| AOC                     | 7         | 4.96%   |
| Philips                 | 5         | 3.55%   |
| Lenovo                  | 4         | 2.84%   |
| InfoVision              | 3         | 2.13%   |
| Dell                    | 3         | 2.13%   |
| Apple                   | 3         | 2.13%   |
| Hewlett-Packard         | 2         | 1.42%   |
| VIE                     | 1         | 0.71%   |
| Semp Toshiba            | 1         | 0.71%   |
| PANDA                   | 1         | 0.71%   |
| Panasonic               | 1         | 0.71%   |
| MStar                   | 1         | 0.71%   |
| LG Electronics          | 1         | 0.71%   |
| JDI                     | 1         | 0.71%   |
| ITE                     | 1         | 0.71%   |
| Chi Mei Optoelectronics | 1         | 0.71%   |
| ASUSTek Computer        | 1         | 0.71%   |
| AGO                     | 1         | 0.71%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD0385 1366x768 310x170mm 13.9-inch           | 4         | 2.74%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 340x190mm 15.3-inch         | 4         | 2.74%   |
| Samsung Electronics SyncMaster SAM0601 1600x900                       | 2         | 1.37%   |
| Samsung Electronics SMT22A300 SAM087B 1920x1080 480x270mm 21.7-inch   | 2         | 1.37%   |
| LG Display LCD Monitor LGD0458 1366x768 310x170mm 13.9-inch           | 2         | 1.37%   |
| LG Display LCD Monitor LGD0437 1920x1080 280x160mm 12.7-inch          | 2         | 1.37%   |
| BOE LCD Monitor BOE0757 1366x768 340x190mm 15.3-inch                  | 2         | 1.37%   |
| BOE LCD Monitor BOE05EF 1366x768 310x170mm 13.9-inch                  | 2         | 1.37%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch         | 2         | 1.37%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 340x190mm 15.3-inch         | 2         | 1.37%   |
| AU Optronics LCD Monitor AUO303C 1366x768 310x170mm 13.9-inch         | 2         | 1.37%   |
| AU Optronics LCD Monitor AUO263D 1920x1080 310x170mm 13.9-inch        | 2         | 1.37%   |
| AU Optronics LCD Monitor AUO183C 1366x768 310x170mm 13.9-inch         | 2         | 1.37%   |
| AOC T2242we AOC2242 1920x1080 480x270mm 21.7-inch                     | 2         | 1.37%   |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                        | 2         | 1.37%   |
| VIE E195 VIE1950 1600x900 410x280mm 19.5-inch                         | 1         | 0.68%   |
| Semp Toshiba MLE1951 STI1951 1366x768 410x230mm 18.5-inch             | 1         | 0.68%   |
| Samsung Electronics SyncMaster SAM060B 1920x1080 510x290mm 23.1-inch  | 1         | 0.68%   |
| Samsung Electronics SyncMaster SAM0600 1600x900 440x250mm 19.9-inch   | 1         | 0.68%   |
| Samsung Electronics SyncMaster SAM05FF 1600x900 440x250mm 19.9-inch   | 1         | 0.68%   |
| Samsung Electronics SyncMaster SAM05FC 1920x1080                      | 1         | 0.68%   |
| Samsung Electronics SyncMaster SAM058F 1920x1080 480x270mm 21.7-inch  | 1         | 0.68%   |
| Samsung Electronics SyncMaster SAM04E4 1600x900 440x250mm 19.9-inch   | 1         | 0.68%   |
| Samsung Electronics SyncMaster SAM03E0 1440x900 410x260mm 19.1-inch   | 1         | 0.68%   |
| Samsung Electronics SyncMaster SAM0364 1360x768 340x190mm 15.3-inch   | 1         | 0.68%   |
| Samsung Electronics SyncMaster SAM0117 1280x1024 310x230mm 15.2-inch  | 1         | 0.68%   |
| Samsung Electronics SyncMaster SAM0116 1024x768 280x210mm 13.8-inch   | 1         | 0.68%   |
| Samsung Electronics SA300/SA350 SAM078C 1600x900 440x250mm 19.9-inch  | 1         | 0.68%   |
| Samsung Electronics S23C550 SAM0A42 1920x1080 510x290mm 23.1-inch     | 1         | 0.68%   |
| Samsung Electronics S19B300 SAM08A6 1366x768 410x230mm 18.5-inch      | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SMT27A550 1920x1080                   | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 340x190mm 15.3-inch  | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SEC414C 1366x768 310x170mm 13.9-inch  | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 340x190mm 15.3-inch  | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 340x190mm 15.3-inch | 1         | 0.68%   |
| Samsung Electronics LCD Monitor SAM0D4F 1920x1080 890x500mm 40.2-inch | 1         | 0.68%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 520x290mm 23.4-inch               | 1         | 0.68%   |
| Philips PHL 221V8 PHLC211 1920x1080 480x270mm 21.7-inch               | 1         | 0.68%   |
| Philips PHL 193V5 PHLC0CD 1366x768 410x230mm 18.5-inch                | 1         | 0.68%   |
| Philips LCD Monitor PHL2051 1600x900 440x250mm 19.9-inch              | 1         | 0.68%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 56        | 40%     |
| 1920x1080 (FHD)    | 49        | 35%     |
| 1600x900 (HD+)     | 10        | 7.14%   |
| 1440x900 (WXGA+)   | 4         | 2.86%   |
| 2560x1080          | 3         | 2.14%   |
| 1280x800 (WXGA)    | 3         | 2.14%   |
| 1280x1024 (SXGA)   | 3         | 2.14%   |
| 1680x1050 (WSXGA+) | 2         | 1.43%   |
| 1360x768           | 2         | 1.43%   |
| 1024x768 (XGA)     | 2         | 1.43%   |
| 3640x1920          | 1         | 0.71%   |
| 2560x1600          | 1         | 0.71%   |
| 2560x1440 (QHD)    | 1         | 0.71%   |
| 1280x720 (HD)      | 1         | 0.71%   |
| 1024x600           | 1         | 0.71%   |
| Unknown            | 1         | 0.71%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 13      | 39        | 27.08%  |
| 15      | 29        | 20.14%  |
| 21      | 13        | 9.03%   |
| 23      | 10        | 6.94%   |
| 18      | 9         | 6.25%   |
| 19      | 8         | 5.56%   |
| 24      | 6         | 4.17%   |
| 14      | 6         | 4.17%   |
| Unknown | 5         | 3.47%   |
| 20      | 4         | 2.78%   |
| 12      | 4         | 2.78%   |
| 34      | 3         | 2.08%   |
| 52      | 1         | 0.69%   |
| 46      | 1         | 0.69%   |
| 40      | 1         | 0.69%   |
| 31      | 1         | 0.69%   |
| 27      | 1         | 0.69%   |
| 17      | 1         | 0.69%   |
| 11      | 1         | 0.69%   |
| 10      | 1         | 0.69%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart_bsd/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 66        | 46.15%  |
| 401-500     | 33        | 23.08%  |
| 501-600     | 16        | 11.19%  |
| 201-300     | 15        | 10.49%  |
| Unknown     | 5         | 3.5%    |
| 701-800     | 3         | 2.1%    |
| 1001-1500   | 2         | 1.4%    |
| 801-900     | 1         | 0.7%    |
| 601-700     | 1         | 0.7%    |
| 351-400     | 1         | 0.7%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 109       | 83.21%  |
| 16/10   | 9         | 6.87%   |
| 4/3     | 4         | 3.05%   |
| 21/9    | 3         | 2.29%   |
| 5/4     | 2         | 1.53%   |
| 3/2     | 2         | 1.53%   |
| Unknown | 2         | 1.53%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 41        | 28.47%  |
| 201-250        | 29        | 20.14%  |
| 91-100         | 28        | 19.44%  |
| 151-200        | 12        | 8.33%   |
| 141-150        | 10        | 6.94%   |
| Unknown        | 5         | 3.47%   |
| 61-70          | 4         | 2.78%   |
| 351-500        | 4         | 2.78%   |
| 101-110        | 3         | 2.08%   |
| 501-1000       | 2         | 1.39%   |
| More than 1000 | 1         | 0.69%   |
| 71-80          | 1         | 0.69%   |
| 51-60          | 1         | 0.69%   |
| 41-50          | 1         | 0.69%   |
| 301-350        | 1         | 0.69%   |
| 111-120        | 1         | 0.69%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart_bsd/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 101-120 | 63        | 44.68%  |
| 51-100  | 44        | 31.21%  |
| 121-160 | 23        | 16.31%  |
| Unknown | 5         | 3.55%   |
| 1-50    | 3         | 2.13%   |
| 161-240 | 3         | 2.13%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart_bsd/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 152       | 48.87%  |
| 1     | 140       | 45.02%  |
| 2     | 19        | 6.11%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart_bsd/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 173       | 38.53%  |
| Intel                    | 138       | 30.73%  |
| Qualcomm Atheros         | 60        | 13.36%  |
| Broadcom                 | 41        | 9.13%   |
| JMicron Technology       | 5         | 1.11%   |
| Samsung Electronics      | 4         | 0.89%   |
| Ralink Technology        | 4         | 0.89%   |
| Ralink                   | 4         | 0.89%   |
| D-Link System            | 3         | 0.67%   |
| TP-Link                  | 2         | 0.45%   |
| Nvidia                   | 2         | 0.45%   |
| MediaTek                 | 2         | 0.45%   |
| Xiaomi                   | 1         | 0.22%   |
| SysKonnect               | 1         | 0.22%   |
| STMicroelectronics       | 1         | 0.22%   |
| Marvell Technology Group | 1         | 0.22%   |
| IMC Networks             | 1         | 0.22%   |
| ICS Advent               | 1         | 0.22%   |
| IBM                      | 1         | 0.22%   |
| Edimax Technology        | 1         | 0.22%   |
| Dell                     | 1         | 0.22%   |
| Arduino SA               | 1         | 0.22%   |
| 3Com                     | 1         | 0.22%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart_bsd/net_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 119       | 22.75%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 40        | 7.65%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 16        | 3.06%   |
| Intel I211 Gigabit Network Connection                                         | 16        | 3.06%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 14        | 2.68%   |
| Intel Ethernet Controller I226-V                                              | 11        | 2.1%    |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 10        | 1.91%   |
| Intel Ethernet Controller I225-V                                              | 9         | 1.72%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 9         | 1.72%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 8         | 1.53%   |
| Intel 82574L Gigabit Network Connection                                       | 7         | 1.34%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 6         | 1.15%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 6         | 1.15%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 6         | 1.15%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 6         | 1.15%   |
| Intel Wireless 7265                                                           | 6         | 1.15%   |
| Intel I350 Gigabit Network Connection                                         | 6         | 1.15%   |
| Intel 82576 Gigabit Network Connection                                        | 6         | 1.15%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 5         | 0.96%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 5         | 0.96%   |
| Intel Wireless 8265 / 8275                                                    | 5         | 0.96%   |
| Intel I210 Gigabit Network Connection                                         | 5         | 0.96%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 5         | 0.96%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 5         | 0.96%   |
| Realtek RTL8125 2.5GbE Controller                                             | 4         | 0.76%   |
| Intel Ethernet Connection I217-LM                                             | 4         | 0.76%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 4         | 0.76%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 3         | 0.57%   |
| Realtek 8811CU Wireless LAN 802.11ac USB NIC                                  | 3         | 0.57%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 3         | 0.57%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 3         | 0.57%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 3         | 0.57%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                        | 3         | 0.57%   |
| Intel Wireless 3165                                                           | 3         | 0.57%   |
| Intel Wi-Fi 6 AX201                                                           | 3         | 0.57%   |
| Intel Wi-Fi 6 AX200                                                           | 3         | 0.57%   |
| Intel Ethernet Connection (4) I219-LM                                         | 3         | 0.57%   |
| Intel Ethernet Connection (3) I218-LM                                         | 3         | 0.57%   |
| Intel Ethernet Connection (2) I219-LM                                         | 3         | 0.57%   |
| Intel 82583V Gigabit Network Connection                                       | 3         | 0.57%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Qualcomm Atheros      | 52        | 35.37%  |
| Intel                 | 49        | 33.33%  |
| Realtek Semiconductor | 25        | 17.01%  |
| Broadcom              | 8         | 5.44%   |
| Ralink Technology     | 4         | 2.72%   |
| Ralink                | 4         | 2.72%   |
| TP-Link               | 2         | 1.36%   |
| IMC Networks          | 1         | 0.68%   |
| Edimax Technology     | 1         | 0.68%   |
| D-Link System         | 1         | 0.68%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 16        | 10.74%  |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 14        | 9.4%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 8         | 5.37%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 6         | 4.03%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 6         | 4.03%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 6         | 4.03%   |
| Intel Wireless 7265                                            | 6         | 4.03%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 5         | 3.36%   |
| Intel Wireless 8265 / 8275                                     | 5         | 3.36%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 4         | 2.68%   |
| Realtek 8811CU Wireless LAN 802.11ac USB NIC                   | 3         | 2.01%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 3         | 2.01%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 3         | 2.01%   |
| Intel Wireless 3165                                            | 3         | 2.01%   |
| Intel Wi-Fi 6 AX201                                            | 3         | 2.01%   |
| Intel Wi-Fi 6 AX200                                            | 3         | 2.01%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 2         | 1.34%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 2         | 1.34%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                           | 2         | 1.34%   |
| Ralink RT2561/RT61 rev B 802.11g                               | 2         | 1.34%   |
| Intel Wireless 8260                                            | 2         | 1.34%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 2         | 1.34%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 2         | 1.34%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 2         | 1.34%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 2         | 1.34%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 2         | 1.34%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 2         | 1.34%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 2         | 1.34%   |
| Intel Centrino Advanced-N 6200                                 | 2         | 1.34%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 2         | 1.34%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 0.67%   |
| Realtek RTL8191SEvA Wireless LAN Controller                    | 1         | 0.67%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                         | 1         | 0.67%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 1         | 0.67%   |
| Realtek RTL8187SE Wireless LAN Controller                      | 1         | 0.67%   |
| Ralink RT5370 Wireless Adapter                                 | 1         | 0.67%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 1         | 0.67%   |
| Ralink RT2501/RT2573 Wireless Adapter                          | 1         | 0.67%   |
| Ralink MT7601U Wireless Adapter                                | 1         | 0.67%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 1         | 0.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 164       | 47.67%  |
| Intel                    | 113       | 32.85%  |
| Broadcom                 | 34        | 9.88%   |
| Qualcomm Atheros         | 13        | 3.78%   |
| JMicron Technology       | 5         | 1.45%   |
| Samsung Electronics      | 4         | 1.16%   |
| Nvidia                   | 2         | 0.58%   |
| MediaTek                 | 2         | 0.58%   |
| D-Link System            | 2         | 0.58%   |
| Xiaomi                   | 1         | 0.29%   |
| SysKonnect               | 1         | 0.29%   |
| Marvell Technology Group | 1         | 0.29%   |
| ICS Advent               | 1         | 0.29%   |
| 3Com                     | 1         | 0.29%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller             | 119       | 32.25%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                         | 40        | 10.84%  |
| Intel I211 Gigabit Network Connection                                         | 16        | 4.34%   |
| Intel Ethernet Controller I226-V                                              | 11        | 2.98%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                              | 10        | 2.71%   |
| Intel Ethernet Controller I225-V                                              | 9         | 2.44%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                         | 9         | 2.44%   |
| Intel 82574L Gigabit Network Connection                                       | 7         | 1.9%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                         | 6         | 1.63%   |
| Intel I350 Gigabit Network Connection                                         | 6         | 1.63%   |
| Intel 82576 Gigabit Network Connection                                        | 6         | 1.63%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                 | 5         | 1.36%   |
| Intel I210 Gigabit Network Connection                                         | 5         | 1.36%   |
| Intel 82571EB/82571GB Gigabit Ethernet Controller D0/D1 (copper applications) | 5         | 1.36%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                                | 5         | 1.36%   |
| Realtek RTL8125 2.5GbE Controller                                             | 4         | 1.08%   |
| Intel Ethernet Connection I217-LM                                             | 4         | 1.08%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                               | 3         | 0.81%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                    | 3         | 0.81%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                        | 3         | 0.81%   |
| Intel Ethernet Connection (4) I219-LM                                         | 3         | 0.81%   |
| Intel Ethernet Connection (3) I218-LM                                         | 3         | 0.81%   |
| Intel Ethernet Connection (2) I219-LM                                         | 3         | 0.81%   |
| Intel 82583V Gigabit Network Connection                                       | 3         | 0.81%   |
| Intel 82578DC Gigabit Network Connection                                      | 3         | 0.81%   |
| Broadcom NetXtreme II BCM57800 1/10 Gigabit Ethernet                          | 3         | 0.81%   |
| Broadcom NetXtreme II BCM5708 Gigabit Ethernet                                | 3         | 0.81%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                              | 3         | 0.81%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                               | 3         | 0.81%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                   | 2         | 0.54%   |
| Samsung Galaxy series, misc. (tethering mode)                                 | 2         | 0.54%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                    | 2         | 0.54%   |
| Nvidia MCP79 Ethernet                                                         | 2         | 0.54%   |
| MediaTek USB Ethernet-RNDIS                                                   | 2         | 0.54%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                           | 2         | 0.54%   |
| Intel Ethernet Connection I219-LM                                             | 2         | 0.54%   |
| Intel Ethernet Connection (7) I219-LM                                         | 2         | 0.54%   |
| Intel Ethernet Connection (2) I219-V                                          | 2         | 0.54%   |
| Intel Ethernet Connection (2) I218-V                                          | 2         | 0.54%   |
| Intel 82579V Gigabit Network Connection                                       | 2         | 0.54%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart_bsd/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 291       | 67.21%  |
| WiFi     | 137       | 31.64%  |
| Modem    | 3         | 0.69%   |
| Unknown  | 2         | 0.46%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart_bsd/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 260       | 74.71%  |
| WiFi     | 88        | 25.29%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart_bsd/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 142       | 45.51%  |
| 1     | 72        | 23.08%  |
| 4     | 46        | 14.74%  |
| 3     | 24        | 7.69%   |
| 6     | 14        | 4.49%   |
| 5     | 10        | 3.21%   |
| 8     | 3         | 0.96%   |
| 7     | 1         | 0.32%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart_bsd/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 284       | 91.03%  |
| Yes  | 28        | 8.97%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 35        | 35.71%  |
| Qualcomm Atheros Communications | 28        | 28.57%  |
| Realtek Semiconductor           | 8         | 8.16%   |
| Broadcom                        | 6         | 6.12%   |
| Apple                           | 6         | 6.12%   |
| Lite-On Technology              | 5         | 5.1%    |
| Foxconn / Hon Hai               | 4         | 4.08%   |
| Cambridge Silicon Radio         | 4         | 4.08%   |
| IMC Networks                    | 1         | 1.02%   |
| Dell                            | 1         | 1.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 14        | 14.29%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 10        | 10.2%   |
| Realtek Bluetooth Adapter                                   | 7         | 7.14%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 6         | 6.12%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 6         | 6.12%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 6         | 6.12%   |
| Qualcomm Atheros Dell Wireless 1703 Bluetooth               | 4         | 4.08%   |
| Intel AX201 Bluetooth                                       | 4         | 4.08%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 4         | 4.08%   |
| Qualcomm Atheros Dell Wireless 1820 Bluetooth 4.1LE         | 3         | 3.06%   |
| Qualcomm Atheros AR3011 Bluetooth                           | 3         | 3.06%   |
| Intel AX200 Bluetooth                                       | 3         | 3.06%   |
| Apple Bluetooth Host Controller                             | 3         | 3.06%   |
| Lite-On Qualcomm Atheros Bluetooth                          | 2         | 2.04%   |
| Intel AX210 Bluetooth                                       | 2         | 2.04%   |
| Foxconn / Hon Hai Qualcomm Atheros AR3011 Bluetooth Adapter | 2         | 2.04%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 2         | 2.04%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 2         | 2.04%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 2         | 2.04%   |
| Realtek CSR Bluetooth Chip                                  | 1         | 1.02%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 1         | 1.02%   |
| Lite-On Atheros Bluetooth                                   | 1         | 1.02%   |
| Lite-On Atheros AR3012 Bluetooth                            | 1         | 1.02%   |
| Intel Wireless-AC 3168 Bluetooth                            | 1         | 1.02%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 1         | 1.02%   |
| IMC Networks Bluetooth Module                               | 1         | 1.02%   |
| Foxconn / Hon Hai Qualcomm Atheros Bluetooth 4.0            | 1         | 1.02%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device             | 1         | 1.02%   |
| Dell Wireless 355 Bluetooth                                 | 1         | 1.02%   |
| Broadcom BCM2046 Bluetooth Device                           | 1         | 1.02%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 1         | 1.02%   |
| Apple Built-in iSight (no firmware loaded)                  | 1         | 1.02%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart_bsd/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 220       | 70.51%  |
| AMD                                             | 50        | 16.03%  |
| Nvidia                                          | 27        | 8.65%   |
| C-Media Electronics                             | 6         | 1.92%   |
| Texas Instruments                               | 1         | 0.32%   |
| Plantronics                                     | 1         | 0.32%   |
| M-Audio                                         | 1         | 0.32%   |
| Logitech                                        | 1         | 0.32%   |
| Licensed by Sony Computer Entertainment America | 1         | 0.32%   |
| Lenovo                                          | 1         | 0.32%   |
| KTMicro                                         | 1         | 0.32%   |
| Generalplus Technology                          | 1         | 0.32%   |
| DSEA A/S                                        | 1         | 0.32%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart_bsd/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 24        | 6.45%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 24        | 6.45%   |
| Intel Sunrise Point-LP HD Audio                                            | 20        | 5.38%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 20        | 5.38%   |
| AMD Family 17h/19h HD Audio Controller                                     | 15        | 4.03%   |
| Intel Haswell-ULT HD Audio Controller                                      | 13        | 3.49%   |
| Intel Broadwell-U Audio Controller                                         | 13        | 3.49%   |
| Intel 8 Series HD Audio Controller                                         | 13        | 3.49%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 12        | 3.23%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 12        | 3.23%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 11        | 2.96%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 10        | 2.69%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 9         | 2.42%   |
| Intel Jasper Lake HD Audio                                                 | 9         | 2.42%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 9         | 2.42%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 9         | 2.42%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 7         | 1.88%   |
| Intel 200 Series PCH HD Audio                                              | 7         | 1.88%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 7         | 1.88%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 7         | 1.88%   |
| AMD FCH Azalia Controller                                                  | 6         | 1.61%   |
| AMD Wrestler HDMI Audio                                                    | 5         | 1.34%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 4         | 1.08%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 4         | 1.08%   |
| Intel Cannon Lake PCH cAVS                                                 | 4         | 1.08%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4         | 1.08%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 0.81%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 3         | 0.81%   |
| Nvidia GK107 HDMI Audio Controller                                         | 3         | 0.81%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 3         | 0.81%   |
| Intel Comet Lake PCH-LP cAVS                                               | 3         | 0.81%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 3         | 0.81%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 3         | 0.81%   |
| C-Media Electronics CM108 Audio Controller                                 | 3         | 0.81%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 3         | 0.81%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 3         | 0.81%   |
| AMD Kaveri HDMI/DP Audio Controller                                        | 3         | 0.81%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 3         | 0.81%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 3         | 0.81%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 3         | 0.81%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 55        | 16.08%  |
| Kingston            | 48        | 14.04%  |
| Smart               | 46        | 13.45%  |
| Samsung Electronics | 35        | 10.23%  |
| SK hynix            | 20        | 5.85%   |
| Teikon              | 16        | 4.68%   |
| Crucial             | 16        | 4.68%   |
| A-DATA Technology   | 13        | 3.8%    |
| Micron Technology   | 12        | 3.51%   |
| Unknown             | 12        | 3.51%   |
| Corsair             | 6         | 1.75%   |
| Smart Brazil        | 5         | 1.46%   |
| High Bridge         | 5         | 1.46%   |
| Hewlett-Packard     | 4         | 1.17%   |
| Multilaser          | 3         | 0.88%   |
| G.Skill             | 3         | 0.88%   |
| Apacer              | 3         | 0.88%   |
| Unknown (ABCD)      | 2         | 0.58%   |
| Toshiba             | 2         | 0.58%   |
| Smart Modular       | 2         | 0.58%   |
| Patriot             | 2         | 0.58%   |
| Nanya Technology    | 2         | 0.58%   |
| Kllisre             | 2         | 0.58%   |
| Atermiter           | 2         | 0.58%   |
| 019400B300CE        | 2         | 0.58%   |
| Unknown (8A02)      | 1         | 0.29%   |
| Unknown (0x5846)    | 1         | 0.29%   |
| Unknown (0x0B45)    | 1         | 0.29%   |
| Transcend           | 1         | 0.29%   |
| Tigo                | 1         | 0.29%   |
| SK_Hynix            | 1         | 0.29%   |
| RZX                 | 1         | 0.29%   |
| PUSKILL             | 1         | 0.29%   |
| PNY                 | 1         | 0.29%   |
| MemoWise            | 1         | 0.29%   |
| Lexar               | 1         | 0.29%   |
| Kreton              | 1         | 0.29%   |
| KingSpec            | 1         | 0.29%   |
| Kimtigo             | 1         | 0.29%   |
| Juhor               | 1         | 0.29%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart_bsd/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Unknown                                                      | 12        | 3.28%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s        | 5         | 1.37%   |
| Unknown RAM Module 2GB DIMM SDRAM                            | 4         | 1.09%   |
| Smart RAM SH564568FH8NZPHSCR 2GB SODIMM DDR3 1334MT/s        | 4         | 1.09%   |
| Smart RAM SH564128FJ8NZRNSDG 4GB SODIMM DDR3 1600MT/s        | 4         | 1.09%   |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s        | 4         | 1.09%   |
| Smart RAM SH564128FH8N6TNSQG 4GB DIMM DDR3 1600MT/s          | 4         | 1.09%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                    | 3         | 0.82%   |
| Unknown RAM Module 4GB DIMM SDRAM                            | 3         | 0.82%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                    | 3         | 0.82%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                    | 3         | 0.82%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                     | 3         | 0.82%   |
| Unknown RAM Module 2GB DIMM DDR2                             | 3         | 0.82%   |
| Unknown RAM Module 2GB DIMM                                  | 3         | 0.82%   |
| Smart RAM SH564128FH8NZQNSCG 4GB SODIMM DDR3 1600MT/s        | 3         | 0.82%   |
| Smart RAM SH564128FH8NZPHSCR 4GB SODIMM DDR3 1333MT/s        | 3         | 0.82%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                         | 2         | 0.55%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                   | 2         | 0.55%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                    | 2         | 0.55%   |
| Unknown RAM Module 1GB DIMM SDRAM                            | 2         | 0.55%   |
| Teikon RAM TMTS8G58DFRBFKB-16 8GB SODIMM DDR3 1600MT/s       | 2         | 0.55%   |
| Teikon RAM TML251S6EFR8A-PBHC 4GB SODIMM DDR3 1600MT/s       | 2         | 0.55%   |
| Teikon RAM TMA81GS6AFR8N-UHSC 8GB SODIMM DDR4 2400MT/s       | 2         | 0.55%   |
| Smart RAM SH564568FH8N6PHSFG 2GB DIMM DDR3 1333MT/s          | 2         | 0.55%   |
| Smart RAM SH564568FH8N0QHSCG 2GB DIMM DDR3 1333MT/s          | 2         | 0.55%   |
| Smart RAM SH564128FH8NZPHSCG 4GB SODIMM DDR3 1333MT/s        | 2         | 0.55%   |
| Smart RAM SF564128CJ8NWMNSEG 4GB SODIMM DDR3 1600MT/s        | 2         | 0.55%   |
| Smart RAM SF4641G8CK8IEHLSBG 8GB SODIMM DDR4 2667MT/s        | 2         | 0.55%   |
| Smart Brazil RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2400MT/s | 2         | 0.55%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 0.55%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s        | 2         | 0.55%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s        | 2         | 0.55%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2400MT/s        | 2         | 0.55%   |
| Patriot RAM 2666 C16 Series 4GB DIMM DDR4 3000MT/s           | 2         | 0.55%   |
| Multilaser RAM MS3512NSZ-CA3G1 4GB SODIMM DDR3 1600MT/s      | 2         | 0.55%   |
| Kingston RAM Module 8GB SODIMM DDR3 1600MT/s                 | 2         | 0.55%   |
| Kingston RAM Module 2GB DIMM DDR2 800MT/s                    | 2         | 0.55%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2400MT/s            | 2         | 0.55%   |
| Kingston RAM KHX1600C10D3/ 8GB DIMM DDR3 1866MT/s            | 2         | 0.55%   |
| Kingston RAM 99U5471-054.A00LF 8GB DIMM DDR3 1600MT/s        | 2         | 0.55%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart_bsd/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 146       | 51.05%  |
| DDR4    | 85        | 29.72%  |
| DDR2    | 22        | 7.69%   |
| Unknown | 15        | 5.24%   |
| SDRAM   | 13        | 4.55%   |
| LPDDR4  | 3         | 1.05%   |
| DDR5    | 1         | 0.35%   |
| DDR     | 1         | 0.35%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 144       | 50.7%   |
| SODIMM       | 133       | 46.83%  |
| Row Of Chips | 3         | 1.06%   |
| FB-DIMM      | 3         | 1.06%   |
| Chip         | 1         | 0.35%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart_bsd/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 114       | 35.96%  |
| 8192  | 96        | 30.28%  |
| 2048  | 72        | 22.71%  |
| 16384 | 26        | 8.2%    |
| 1024  | 6         | 1.89%   |
| 32768 | 3         | 0.95%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart_bsd/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 87        | 27.88%  |
| 1333    | 54        | 17.31%  |
| 2400    | 32        | 10.26%  |
| 2667    | 26        | 8.33%   |
| Unknown | 20        | 6.41%   |
| 3200    | 17        | 5.45%   |
| 2133    | 12        | 3.85%   |
| 800     | 12        | 3.85%   |
| 1334    | 10        | 3.21%   |
| 667     | 9         | 2.88%   |
| 2666    | 6         | 1.92%   |
| 1066    | 5         | 1.6%    |
| 1067    | 4         | 1.28%   |
| 1867    | 3         | 0.96%   |
| 1866    | 3         | 0.96%   |
| 533     | 3         | 0.96%   |
| 3000    | 2         | 0.64%   |
| 400     | 2         | 0.64%   |
| 4800    | 1         | 0.32%   |
| 4000    | 1         | 0.32%   |
| 2933    | 1         | 0.32%   |
| 975     | 1         | 0.32%   |
| 333     | 1         | 0.32%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart_bsd/printer_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| ELGIN  | 2         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart_bsd/printer_model.svg)


| Model        | Computers | Percent |
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

![Camera Vendor](./All/images/pie_chart_bsd/camera_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Chicony Electronics           | 22        | 22.45%  |
| Bison Electronics             | 17        | 17.35%  |
| Microdia                      | 11        | 11.22%  |
| Realtek Semiconductor         | 10        | 10.2%   |
| Silicon Motion                | 7         | 7.14%   |
| Logitech                      | 4         | 4.08%   |
| Suyin                         | 3         | 3.06%   |
| Sunplus Innovation Technology | 3         | 3.06%   |
| IMC Networks                  | 3         | 3.06%   |
| Apple                         | 3         | 3.06%   |
| Unknown                       | 2         | 2.04%   |
| Syntek                        | 2         | 2.04%   |
| Luxvisions Innotech Limited   | 2         | 2.04%   |
| Lenovo                        | 2         | 2.04%   |
| Alcor Micro                   | 2         | 2.04%   |
| Z-Star Microelectronics       | 1         | 1.02%   |
| Tripath Technology            | 1         | 1.02%   |
| Quanta                        | 1         | 1.02%   |
| Lite-On Technology            | 1         | 1.02%   |
| Aveo Technology               | 1         | 1.02%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart_bsd/camera_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Bison Integrated Camera                       | 8         | 8.08%   |
| Chicony HD WebCam                             | 6         | 6.06%   |
| Silicon Motion Realtek DMFT RGB               | 4         | 4.04%   |
| Microdia Integrated_Webcam_HD                 | 4         | 4.04%   |
| Microdia Dell Laptop Integrated Webcam HD     | 4         | 4.04%   |
| Realtek Dell EasyCamera                       | 3         | 3.03%   |
| Chicony Sony Visual Communication Camera      | 3         | 3.03%   |
| Bison Lenovo EasyCamera                       | 3         | 3.03%   |
| Unknown Realtek PC Camera                     | 2         | 2.02%   |
| Syntek EasyCamera                             | 2         | 2.02%   |
| Sunplus Integrated_Webcam_HD                  | 2         | 2.02%   |
| Realtek Integrated Webcam                     | 2         | 2.02%   |
| Luxvisions Innotech Limited Integrated Camera | 2         | 2.02%   |
| Logitech Webcam C270                          | 2         | 2.02%   |
| Chicony Integrated Camera                     | 2         | 2.02%   |
| Bison HD Webcam                               | 2         | 2.02%   |
| Apple FaceTime HD Camera                      | 2         | 2.02%   |
| Alcor Micro Acer Integrated Webcam            | 2         | 2.02%   |
| Z-Star Venus USB2.0 Camera                    | 1         | 1.01%   |
| Tripath USB Camera                            | 1         | 1.01%   |
| Suyin WebCam                                  | 1         | 1.01%   |
| Suyin USB 2.0 UVC 1.3M WebCam                 | 1         | 1.01%   |
| Suyin Integrated_Webcam_HD                    | 1         | 1.01%   |
| Sunplus HD WebCam                             | 1         | 1.01%   |
| Silicon Motion WebCam SCX Series              | 1         | 1.01%   |
| Silicon Motion Realtek USB 2.0 PC Camera      | 1         | 1.01%   |
| Silicon Motion ATIV VGA Camera                | 1         | 1.01%   |
| Realtek LG Camera                             | 1         | 1.01%   |
| Realtek Integrated_Webcam_FHD                 | 1         | 1.01%   |
| Realtek Integrated_Webcam_8M                  | 1         | 1.01%   |
| Realtek Integrated Webcam HD                  | 1         | 1.01%   |
| Realtek Composite Webcam                      | 1         | 1.01%   |
| Realtek Acer 640 x 480 laptop camera          | 1         | 1.01%   |
| Quanta HD Webcam                              | 1         | 1.01%   |
| Microdia Laptop_Integrated_Webcam_HD          | 1         | 1.01%   |
| Microdia Laptop_Integrated_Webcam_1.3M        | 1         | 1.01%   |
| Microdia Integrated Webcam HD                 | 1         | 1.01%   |
| Logitech HD Pro Webcam C920                   | 1         | 1.01%   |
| Logitech C922 Pro Stream Webcam               | 1         | 1.01%   |
| Lite-On Integrated Camera                     | 1         | 1.01%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 6         | 33.33%  |
| Upek                       | 4         | 22.22%  |
| Synaptics                  | 4         | 22.22%  |
| Shenzhen Goodix Technology | 2         | 11.11%  |
| Samsung Electronics        | 1         | 5.56%   |
| Broadcom                   | 1         | 5.56%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                       | 4         | 22.22%  |
| Validity Sensors VFS 5011 fingerprint sensor                                 | 2         | 11.11%  |
| Synaptics WBDI                                                               | 2         | 11.11%  |
| Shenzhen Goodix Fingerprint Reader                                           | 2         | 11.11%  |
| Validity Sensors VFS5011 Fingerprint Reader                                  | 1         | 5.56%   |
| Validity Sensors VFS495 Fingerprint Reader                                   | 1         | 5.56%   |
| Validity Sensors Synaptics WBDI                                              | 1         | 5.56%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                  | 1         | 5.56%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                            | 1         | 5.56%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                             | 1         | 5.56%   |
| Samsung CanvasBio Fingerprint Reader                                         | 1         | 5.56%   |
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

![Unsupported Devices](./All/images/pie_chart_bsd/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 123       | 39.81%  |
| 0     | 97        | 31.39%  |
| 2     | 51        | 16.5%   |
| 3     | 23        | 7.44%   |
| 4     | 10        | 3.24%   |
| 5     | 5         | 1.62%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 191       | 59.32%  |
| Card reader              | 38        | 11.8%   |
| Net/wireless             | 31        | 9.63%   |
| Bluetooth                | 30        | 9.32%   |
| Fingerprint reader       | 17        | 5.28%   |
| Sound                    | 6         | 1.86%   |
| Network                  | 3         | 0.93%   |
| Net/ethernet             | 2         | 0.62%   |
| Graphics card            | 2         | 0.62%   |
| Storage                  | 1         | 0.31%   |
| Firewire controller      | 1         | 0.31%   |

