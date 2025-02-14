helloSystem 0.7.0 - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------------

A project to collect tested hardware configurations for helloSystem 0.7.0.

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

Total: 262

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
| Lenovo        | ThinkPad P51 20HHCTO1WW     | [fa70f945fe](https://bsd-hardware.info/?probe=fa70f945fe) | Nov 03, 2024 |
| Lenovo        | ThinkPad P51 20HHCTO1WW     | [c1a712cb6a](https://bsd-hardware.info/?probe=c1a712cb6a) | Sep 30, 2024 |
| Lenovo        | Legion Y7000P 81HC          | [3dff76a9dd](https://bsd-hardware.info/?probe=3dff76a9dd) | Apr 27, 2024 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [20090cb5c6](https://bsd-hardware.info/?probe=20090cb5c6) | Jan 15, 2024 |
| Acer          | Monserrat                   | [9c79dbac8b](https://bsd-hardware.info/?probe=9c79dbac8b) | Sep 10, 2023 |
| ASUSTek       | 1015P                       | [c700224684](https://bsd-hardware.info/?probe=c700224684) | Jun 14, 2023 |
| LG Electro... | COLUMBIA                    | [4872f6c377](https://bsd-hardware.info/?probe=4872f6c377) | Mar 27, 2023 |
| Lenovo        | G70-70 80HW006AGE           | [a52e13cf4e](https://bsd-hardware.info/?probe=a52e13cf4e) | Feb 04, 2023 |
| Monster       | ABRA A7 V11.2               | [3e58da5c30](https://bsd-hardware.info/?probe=3e58da5c30) | Feb 02, 2023 |
| Monster       | ABRA A7 V11.2               | [3309453ed5](https://bsd-hardware.info/?probe=3309453ed5) | Feb 02, 2023 |
| Acer          | Aspire ES1-520              | [efac696b1a](https://bsd-hardware.info/?probe=efac696b1a) | Jan 31, 2023 |
| Razer         | Blade Stealth               | [c0b9641604](https://bsd-hardware.info/?probe=c0b9641604) | Jan 29, 2023 |
| Lenovo        | IdeaPad 110-14AST 80TQ      | [aed5292edc](https://bsd-hardware.info/?probe=aed5292edc) | Jan 28, 2023 |
| Lenovo        | ThinkPad T460 20FMS06V00    | [6914f6aab5](https://bsd-hardware.info/?probe=6914f6aab5) | Jan 28, 2023 |
| Acer          | ES1-131-C2BM                | [400ef90a79](https://bsd-hardware.info/?probe=400ef90a79) | Jan 28, 2023 |
| Acer          | Aspire E3-112               | [513c7ff4be](https://bsd-hardware.info/?probe=513c7ff4be) | Jan 27, 2023 |
| Lenovo        | ThinkPad S1 Yoga 20CD003... | [17fd94a4c0](https://bsd-hardware.info/?probe=17fd94a4c0) | Jan 23, 2023 |
| Lenovo        | IdeaPad 110-14AST 80TQ      | [8ae819f673](https://bsd-hardware.info/?probe=8ae819f673) | Jan 21, 2023 |
| Lenovo        | ThinkPad T61 64644YG        | [3497ee2fcc](https://bsd-hardware.info/?probe=3497ee2fcc) | Jan 21, 2023 |
| Lenovo        | B40-70 80F30005BR           | [17333d88cf](https://bsd-hardware.info/?probe=17333d88cf) | Jan 17, 2023 |
| HP            | Pavilion dv6                | [9d87e4009a](https://bsd-hardware.info/?probe=9d87e4009a) | Jan 16, 2023 |
| HP            | Pavilion dv6                | [e42082b1c1](https://bsd-hardware.info/?probe=e42082b1c1) | Jan 15, 2023 |
| HP            | Pavilion g6                 | [ceb79702f2](https://bsd-hardware.info/?probe=ceb79702f2) | Jan 13, 2023 |
| HP            | 2000                        | [7f29899321](https://bsd-hardware.info/?probe=7f29899321) | Jan 09, 2023 |
| Lenovo        | ThinkPad T400 2764CTO       | [26f8459193](https://bsd-hardware.info/?probe=26f8459193) | Jan 06, 2023 |
| Sony          | VPCSB11FX                   | [966183e570](https://bsd-hardware.info/?probe=966183e570) | Dec 23, 2022 |
| Acer          | Aspire ES1-533              | [570b96d0f7](https://bsd-hardware.info/?probe=570b96d0f7) | Dec 23, 2022 |
| Dell          | Inspiron 15-3552            | [eea4262af2](https://bsd-hardware.info/?probe=eea4262af2) | Dec 22, 2022 |
| Dell          | Inspiron 15-3552            | [cae00eb4d6](https://bsd-hardware.info/?probe=cae00eb4d6) | Dec 22, 2022 |
| Lenovo        | G510 20238                  | [e5c4d51eab](https://bsd-hardware.info/?probe=e5c4d51eab) | Dec 15, 2022 |
| HP            | Pavilion dv4                | [ee94a86a43](https://bsd-hardware.info/?probe=ee94a86a43) | Dec 12, 2022 |
| Apple         | MacBook3,1                  | [7aef0a996b](https://bsd-hardware.info/?probe=7aef0a996b) | Dec 10, 2022 |
| HP            | 2000                        | [5414b7c943](https://bsd-hardware.info/?probe=5414b7c943) | Dec 09, 2022 |
| HP            | 245 G6                      | [49ce6aa725](https://bsd-hardware.info/?probe=49ce6aa725) | Dec 07, 2022 |
| HASEE Comp... | N95XKP6                     | [0bc2996a6d](https://bsd-hardware.info/?probe=0bc2996a6d) | Dec 02, 2022 |
| Dell          | Inspiron 3442               | [529cbab9aa](https://bsd-hardware.info/?probe=529cbab9aa) | Dec 01, 2022 |
| Lenovo        | Legion Y7000P 81HC          | [57c3a4005a](https://bsd-hardware.info/?probe=57c3a4005a) | Dec 01, 2022 |
| GPD           | P3 MAX                      | [4a467c9616](https://bsd-hardware.info/?probe=4a467c9616) | Nov 30, 2022 |
| Lenovo        | ThinkPad T460 20FMS0XL23    | [bc7585ec56](https://bsd-hardware.info/?probe=bc7585ec56) | Nov 28, 2022 |
| Apple         | MacBook5,1                  | [3541df7dd2](https://bsd-hardware.info/?probe=3541df7dd2) | Nov 27, 2022 |
| Dell          | Inspiron 5558               | [10bece0518](https://bsd-hardware.info/?probe=10bece0518) | Nov 27, 2022 |
| Acer          | Aspire 5738                 | [067e8e4d58](https://bsd-hardware.info/?probe=067e8e4d58) | Nov 26, 2022 |
| ASUSTek       | K55VD                       | [6fa29c4e4d](https://bsd-hardware.info/?probe=6fa29c4e4d) | Nov 24, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [3c11fc31b2](https://bsd-hardware.info/?probe=3c11fc31b2) | Nov 24, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | [e32a104392](https://bsd-hardware.info/?probe=e32a104392) | Nov 24, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | [a4d92a3b73](https://bsd-hardware.info/?probe=a4d92a3b73) | Nov 23, 2022 |
| Dell          | Latitude D630               | [1c600cc283](https://bsd-hardware.info/?probe=1c600cc283) | Nov 18, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [7650f7619d](https://bsd-hardware.info/?probe=7650f7619d) | Nov 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3448A... | [1d2be7d46a](https://bsd-hardware.info/?probe=1d2be7d46a) | Nov 13, 2022 |
| Lenovo        | ThinkPad W530 24491A0       | [4a700f43f8](https://bsd-hardware.info/?probe=4a700f43f8) | Oct 30, 2022 |
| Samsung       | Q430/Q530                   | [fb98c8c797](https://bsd-hardware.info/?probe=fb98c8c797) | Oct 29, 2022 |
| Apple         | MacBook4,1                  | [015f0a0a6d](https://bsd-hardware.info/?probe=015f0a0a6d) | Oct 27, 2022 |
| Samsung       | Q430/Q530                   | [4965215a13](https://bsd-hardware.info/?probe=4965215a13) | Oct 25, 2022 |
| Lenovo        | G500 20236                  | [8a4e3767e9](https://bsd-hardware.info/?probe=8a4e3767e9) | Oct 22, 2022 |
| Lenovo        | ThinkPad T61 765912G        | [50c3c93790](https://bsd-hardware.info/?probe=50c3c93790) | Oct 17, 2022 |
| HP            | SpectreXT Pro 13-b000 PC    | [f45ea42873](https://bsd-hardware.info/?probe=f45ea42873) | Oct 16, 2022 |
| HP            | Laptop 15q-bu0xx            | [99c01654a2](https://bsd-hardware.info/?probe=99c01654a2) | Oct 15, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [dec7108b53](https://bsd-hardware.info/?probe=dec7108b53) | Oct 11, 2022 |
| Acer          | Aspire 5336                 | [127ddc93fb](https://bsd-hardware.info/?probe=127ddc93fb) | Oct 10, 2022 |
| Acer          | Aspire E5-722G              | [7a4eb565fe](https://bsd-hardware.info/?probe=7a4eb565fe) | Oct 10, 2022 |
| Dell          | Latitude E6420              | [48c26d2a17](https://bsd-hardware.info/?probe=48c26d2a17) | Oct 10, 2022 |
| Fujitsu       | LIFEBOOK U904               | [3a86733538](https://bsd-hardware.info/?probe=3a86733538) | Oct 09, 2022 |
| Acer          | Aspire F5-573               | [9c092c9cd7](https://bsd-hardware.info/?probe=9c092c9cd7) | Oct 05, 2022 |
| HP            | ProBook 4540s               | [df94757940](https://bsd-hardware.info/?probe=df94757940) | Oct 02, 2022 |
| Lenovo        | ThinkPad E15 2ORES4XJ00     | [323a95e6a9](https://bsd-hardware.info/?probe=323a95e6a9) | Oct 01, 2022 |
| Lenovo        | Legion Y540-17IRH 81Q4      | [62b9a56103](https://bsd-hardware.info/?probe=62b9a56103) | Sep 29, 2022 |
| Lenovo        | ThinkPad X61 Tablet 7763... | [1f37ebf2bb](https://bsd-hardware.info/?probe=1f37ebf2bb) | Sep 28, 2022 |
| Dell          | Precision 7710              | [4c4937d824](https://bsd-hardware.info/?probe=4c4937d824) | Sep 18, 2022 |
| Lenovo        | G50-30 80G0                 | [da4bd87fee](https://bsd-hardware.info/?probe=da4bd87fee) | Sep 17, 2022 |
| Lenovo        | ThinkPad X270 20HMS2LL00    | [12f6a8866f](https://bsd-hardware.info/?probe=12f6a8866f) | Sep 14, 2022 |
| Lenovo        | ThinkPad T440 20B7S2LT00    | [5104875f94](https://bsd-hardware.info/?probe=5104875f94) | Sep 06, 2022 |
| Apple         | MacBookPro5,1               | [f4d84edb3b](https://bsd-hardware.info/?probe=f4d84edb3b) | Sep 04, 2022 |
| Dell          | Precision 7710              | [339099bbf0](https://bsd-hardware.info/?probe=339099bbf0) | Sep 01, 2022 |
| Dell          | Precision 5540              | [0c5089634d](https://bsd-hardware.info/?probe=0c5089634d) | Aug 30, 2022 |
| Dell          | Precision 5540              | [afb80a84fb](https://bsd-hardware.info/?probe=afb80a84fb) | Aug 30, 2022 |
| Dell          | Studio 1537                 | [a185649600](https://bsd-hardware.info/?probe=a185649600) | Aug 17, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [f8c10bf25a](https://bsd-hardware.info/?probe=f8c10bf25a) | Aug 15, 2022 |
| HP            | ProBook 4540s               | [0a7891d53f](https://bsd-hardware.info/?probe=0a7891d53f) | Aug 06, 2022 |
| eMachines     | eME728                      | [96d745589c](https://bsd-hardware.info/?probe=96d745589c) | Aug 06, 2022 |
| Acer          | Aspire 5930                 | [4bd9ec4253](https://bsd-hardware.info/?probe=4bd9ec4253) | Aug 02, 2022 |
| Lenovo        | ThinkPad T61 7661GY9        | [7ab5339eee](https://bsd-hardware.info/?probe=7ab5339eee) | Jul 30, 2022 |
| HP            | ProBook 430 G4              | [2a9d4e9b0b](https://bsd-hardware.info/?probe=2a9d4e9b0b) | Jul 30, 2022 |
| Apple         | MacBook6,1                  | [55ab4bc8d6](https://bsd-hardware.info/?probe=55ab4bc8d6) | Jul 29, 2022 |
| Dell          | Latitude E7440              | [03497b7b2a](https://bsd-hardware.info/?probe=03497b7b2a) | Jul 27, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [e2a5a65135](https://bsd-hardware.info/?probe=e2a5a65135) | Jul 23, 2022 |
| HP            | ProBook 4730s               | [e70725dd32](https://bsd-hardware.info/?probe=e70725dd32) | Jul 23, 2022 |
| Lenovo        | ThinkPad L450 20DSS1S402    | [b779706b7a](https://bsd-hardware.info/?probe=b779706b7a) | Jul 21, 2022 |
| Lenovo        | ThinkPad L412 0585AD9       | [cba0fc2340](https://bsd-hardware.info/?probe=cba0fc2340) | Jul 20, 2022 |
| Dell          | Inspiron MP061              | [56a7002cc5](https://bsd-hardware.info/?probe=56a7002cc5) | Jul 16, 2022 |
| Apple         | MacBook4,1                  | [db03ba8975](https://bsd-hardware.info/?probe=db03ba8975) | Jul 14, 2022 |
| MSI           | GF63 Thin 10SC              | [139855ab73](https://bsd-hardware.info/?probe=139855ab73) | Jul 12, 2022 |
| Acer          | Aspire E1-522               | [d680e0d05d](https://bsd-hardware.info/?probe=d680e0d05d) | Jul 10, 2022 |
| Fujitsu       | LIFEBOOK A555               | [1062220932](https://bsd-hardware.info/?probe=1062220932) | Jul 07, 2022 |
| Lenovo        | ThinkPad T430s 2356CV6      | [20df9d5df2](https://bsd-hardware.info/?probe=20df9d5df2) | Jun 29, 2022 |
| Toshiba       | PORTEGE R700                | [d9c359c2ab](https://bsd-hardware.info/?probe=d9c359c2ab) | Jun 28, 2022 |
| Lenovo        | ThinkPad T460 20FN004CUK    | [18b5875c95](https://bsd-hardware.info/?probe=18b5875c95) | Jun 26, 2022 |
| Lenovo        | ThinkPad T410 2522CS7       | [a1561dacb2](https://bsd-hardware.info/?probe=a1561dacb2) | Jun 26, 2022 |
| HP            | Compaq tc4400 (EN357UT#A... | [f4e4e3826b](https://bsd-hardware.info/?probe=f4e4e3826b) | Jun 19, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [aaf7ed146a](https://bsd-hardware.info/?probe=aaf7ed146a) | Jun 16, 2022 |
| HP            | Pavilion Notebook           | [6116216a6d](https://bsd-hardware.info/?probe=6116216a6d) | Jun 15, 2022 |
| Alienware     | M18xR2                      | [6d55881f6a](https://bsd-hardware.info/?probe=6d55881f6a) | Jun 15, 2022 |
| Apple         | MacBook5,1                  | [8ba77d7208](https://bsd-hardware.info/?probe=8ba77d7208) | Jun 13, 2022 |
| Lenovo        | G40-30 80FY                 | [f478f5edc1](https://bsd-hardware.info/?probe=f478f5edc1) | Jun 13, 2022 |
| Lenovo        | ThinkPad X260 20F5S45W00    | [acfa5c94d5](https://bsd-hardware.info/?probe=acfa5c94d5) | Jun 12, 2022 |
| HP            | ProBook 4230s               | [8c853f8ca9](https://bsd-hardware.info/?probe=8c853f8ca9) | Jun 11, 2022 |
| Acer          | Aspire E5-571               | [4be2393c8d](https://bsd-hardware.info/?probe=4be2393c8d) | Jun 11, 2022 |
| Lenovo        | ThinkPad T420 4236MY0       | [94095d4c11](https://bsd-hardware.info/?probe=94095d4c11) | Jun 06, 2022 |
| Lenovo        | ThinkPad T440p 20AWS0DU0... | [8029eb2018](https://bsd-hardware.info/?probe=8029eb2018) | Jun 04, 2022 |
| HP            | Pavilion g4                 | [79d8ca2681](https://bsd-hardware.info/?probe=79d8ca2681) | Jun 04, 2022 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | [9e2661b9e0](https://bsd-hardware.info/?probe=9e2661b9e0) | May 24, 2022 |
| ASUSTek       | F50SL                       | [e26b522868](https://bsd-hardware.info/?probe=e26b522868) | May 22, 2022 |
| HP            | Pavilion dv6                | [73e328ad87](https://bsd-hardware.info/?probe=73e328ad87) | May 20, 2022 |
| Acer          | Aspire E1-522               | [23396b461f](https://bsd-hardware.info/?probe=23396b461f) | May 18, 2022 |
| Acer          | Aspire E1-522               | [55cda59c51](https://bsd-hardware.info/?probe=55cda59c51) | May 17, 2022 |
| ASUSTek       | K52F                        | [6e86ce2a12](https://bsd-hardware.info/?probe=6e86ce2a12) | May 15, 2022 |
| ASUSTek       | K52F                        | [4c12c55177](https://bsd-hardware.info/?probe=4c12c55177) | May 15, 2022 |
| Dell          | Inspiron 15-3552            | [5e781a451d](https://bsd-hardware.info/?probe=5e781a451d) | May 12, 2022 |
| Razer         | Blade 15 Base Model (Ear... | [34ac291019](https://bsd-hardware.info/?probe=34ac291019) | May 11, 2022 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [3ff916acf7](https://bsd-hardware.info/?probe=3ff916acf7) | May 09, 2022 |
| HP            | ProBook 4340s               | [6cc978f98f](https://bsd-hardware.info/?probe=6cc978f98f) | May 09, 2022 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [33367fe342](https://bsd-hardware.info/?probe=33367fe342) | May 09, 2022 |
| Unknown       | W1415A                      | [1b2c63a845](https://bsd-hardware.info/?probe=1b2c63a845) | May 07, 2022 |
| Sony          | VGN-NW25GF_S                | [84b50ca3f1](https://bsd-hardware.info/?probe=84b50ca3f1) | May 06, 2022 |
| Toshiba       | Satellite P300              | [fca7b38039](https://bsd-hardware.info/?probe=fca7b38039) | May 04, 2022 |
| Lenovo        | B470 HuronRiver Platform    | [e0ef68c720](https://bsd-hardware.info/?probe=e0ef68c720) | May 04, 2022 |
| HP            | Pavilion m6                 | [c720817018](https://bsd-hardware.info/?probe=c720817018) | May 03, 2022 |
| HP            | Pavilion g6                 | [4b8ee6729a](https://bsd-hardware.info/?probe=4b8ee6729a) | May 02, 2022 |
| Acer          | Aspire A315-41              | [c59d8482e8](https://bsd-hardware.info/?probe=c59d8482e8) | May 01, 2022 |
| Apple         | MacBookPro5,5               | [807676e010](https://bsd-hardware.info/?probe=807676e010) | Apr 30, 2022 |
| Lenovo        | ThinkPad T420 4236BD5       | [867ed989e2](https://bsd-hardware.info/?probe=867ed989e2) | Apr 27, 2022 |
| MSI           | GF65 Thin 10SER             | [cedf98c955](https://bsd-hardware.info/?probe=cedf98c955) | Apr 26, 2022 |
| Dell          | Inspiron 5437               | [830ea686ab](https://bsd-hardware.info/?probe=830ea686ab) | Apr 24, 2022 |
| HP            | 2000                        | [e9599a9bc3](https://bsd-hardware.info/?probe=e9599a9bc3) | Apr 22, 2022 |
| ASUSTek       | X556UJ                      | [ca63749774](https://bsd-hardware.info/?probe=ca63749774) | Apr 19, 2022 |
| Lenovo        | G51-35 80M8                 | [285328cb61](https://bsd-hardware.info/?probe=285328cb61) | Apr 16, 2022 |
| Sony          | SVZ1311C5E                  | [c1c429a7e6](https://bsd-hardware.info/?probe=c1c429a7e6) | Apr 15, 2022 |
| Dell          | Latitude E6540              | [a3da09ae5e](https://bsd-hardware.info/?probe=a3da09ae5e) | Apr 15, 2022 |
| System76      | Lemur Pro                   | [276ee4e96e](https://bsd-hardware.info/?probe=276ee4e96e) | Apr 13, 2022 |
| Lenovo        | ThinkPad X61 7675K2U        | [24f93b9532](https://bsd-hardware.info/?probe=24f93b9532) | Apr 10, 2022 |
| Panasonic     | CF-B11JWCYS                 | [6699d408ad](https://bsd-hardware.info/?probe=6699d408ad) | Apr 08, 2022 |
| HP            | Pavilion 11                 | [a13373b255](https://bsd-hardware.info/?probe=a13373b255) | Apr 07, 2022 |
| DNS           | W9x0LU                      | [8ac57e3b59](https://bsd-hardware.info/?probe=8ac57e3b59) | Apr 06, 2022 |
| TUXEDO        | Aura 15 Gen1                | [e72b47b6de](https://bsd-hardware.info/?probe=e72b47b6de) | Apr 04, 2022 |
| LG Electro... | E300-A.CP20T                | [304701f666](https://bsd-hardware.info/?probe=304701f666) | Apr 02, 2022 |
| TUXEDO        | Aura 15 Gen1                | [1be95af210](https://bsd-hardware.info/?probe=1be95af210) | Apr 01, 2022 |
| HP            | Compaq 6510b (GF910AW#AB... | [a7bccf74e4](https://bsd-hardware.info/?probe=a7bccf74e4) | Mar 31, 2022 |
| Dell          | Latitude E6540              | [0ac0f8f1d8](https://bsd-hardware.info/?probe=0ac0f8f1d8) | Mar 26, 2022 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | [00213ecee9](https://bsd-hardware.info/?probe=00213ecee9) | Mar 25, 2022 |
| Dell          | Vostro 3490                 | [34956934f5](https://bsd-hardware.info/?probe=34956934f5) | Mar 22, 2022 |
| Packard Be... | EasyNote TE69HW             | [851eea349f](https://bsd-hardware.info/?probe=851eea349f) | Mar 17, 2022 |
| Lenovo        | ThinkPad X220 4293B43       | [148a268a0f](https://bsd-hardware.info/?probe=148a268a0f) | Mar 16, 2022 |
| HASEE Comp... | CW35S                       | [737c8bb48a](https://bsd-hardware.info/?probe=737c8bb48a) | Mar 14, 2022 |
| Lenovo        | ThinkPad L440 20ASS0FP00    | [0fbc782835](https://bsd-hardware.info/?probe=0fbc782835) | Mar 14, 2022 |
| Dell          | Latitude E6540              | [e0576dd008](https://bsd-hardware.info/?probe=e0576dd008) | Mar 13, 2022 |
| Acer          | Aspire E1-421               | [cc83218496](https://bsd-hardware.info/?probe=cc83218496) | Mar 10, 2022 |
| Lenovo        | Z50-70 20354                | [a1f85aff27](https://bsd-hardware.info/?probe=a1f85aff27) | Mar 10, 2022 |
| Lenovo        | IdeaPad N585                | [e22da97709](https://bsd-hardware.info/?probe=e22da97709) | Mar 10, 2022 |
| Lenovo        | Z50-70 20354                | [ab71ed7239](https://bsd-hardware.info/?probe=ab71ed7239) | Mar 10, 2022 |
| Itautec       | Infoway w7535               | [b55f9d1bfb](https://bsd-hardware.info/?probe=b55f9d1bfb) | Mar 09, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | [dbd5c6e5e3](https://bsd-hardware.info/?probe=dbd5c6e5e3) | Mar 07, 2022 |
| HP            | EliteBook Folio 9470m       | [e2cc942e3e](https://bsd-hardware.info/?probe=e2cc942e3e) | Feb 28, 2022 |
| Acer          | V5-131                      | [d175137636](https://bsd-hardware.info/?probe=d175137636) | Feb 27, 2022 |
| Dell          | Latitude E4310              | [ba69f80b7f](https://bsd-hardware.info/?probe=ba69f80b7f) | Feb 22, 2022 |
| Apple         | MacBook4,1                  | [e0cf5200de](https://bsd-hardware.info/?probe=e0cf5200de) | Feb 22, 2022 |
| Lenovo        | ThinkPad T61 766301U        | [f5f25efdcc](https://bsd-hardware.info/?probe=f5f25efdcc) | Feb 22, 2022 |
| Apple         | MacBook6,1                  | [d680290d84](https://bsd-hardware.info/?probe=d680290d84) | Feb 22, 2022 |
| Apple         | MacBook6,1                  | [304508ed18](https://bsd-hardware.info/?probe=304508ed18) | Feb 21, 2022 |
| Dell          | Latitude E5470              | [9e479e9c50](https://bsd-hardware.info/?probe=9e479e9c50) | Feb 21, 2022 |
| Dell          | Inspiron 3537               | [932550132e](https://bsd-hardware.info/?probe=932550132e) | Feb 20, 2022 |
| Lenovo        | ThinkPad T61 766301U        | [6eec3232e2](https://bsd-hardware.info/?probe=6eec3232e2) | Feb 19, 2022 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | [2f90d5c2bd](https://bsd-hardware.info/?probe=2f90d5c2bd) | Feb 18, 2022 |
| TUXEDO        | InfinityBook13V3            | [5a75db9142](https://bsd-hardware.info/?probe=5a75db9142) | Feb 17, 2022 |
| TUXEDO        | InfinityBook13V3            | [edc2c4ec36](https://bsd-hardware.info/?probe=edc2c4ec36) | Feb 17, 2022 |
| Lenovo        | ThinkPad T450 20BUS0VH08    | [fa2cd8964e](https://bsd-hardware.info/?probe=fa2cd8964e) | Feb 17, 2022 |
| Samsung       | N100                        | [3125d76ba4](https://bsd-hardware.info/?probe=3125d76ba4) | Feb 16, 2022 |
| Lenovo        | E31-80 80MX                 | [098afac660](https://bsd-hardware.info/?probe=098afac660) | Feb 16, 2022 |
| Lenovo        | ThinkPad T430 2349AK1       | [86fd351c81](https://bsd-hardware.info/?probe=86fd351c81) | Feb 16, 2022 |
| Acer          | V5-131                      | [2d5bfae3b4](https://bsd-hardware.info/?probe=2d5bfae3b4) | Feb 15, 2022 |
| ASUSTek       | X555LA                      | [28b3002182](https://bsd-hardware.info/?probe=28b3002182) | Feb 10, 2022 |
| ASUSTek       | X555LA                      | [9aa18b2e33](https://bsd-hardware.info/?probe=9aa18b2e33) | Feb 09, 2022 |
| Acer          | Aspire E5-511G              | [b14c4c1ac5](https://bsd-hardware.info/?probe=b14c4c1ac5) | Feb 07, 2022 |
| TWINHEAD      | U12CT                       | [32247012ca](https://bsd-hardware.info/?probe=32247012ca) | Feb 06, 2022 |
| Dell          | Latitude D630               | [b34db656b5](https://bsd-hardware.info/?probe=b34db656b5) | Feb 05, 2022 |
| Lenovo        | ThinkPad T440p 20AWS3RH0... | [a6c02e440b](https://bsd-hardware.info/?probe=a6c02e440b) | Feb 05, 2022 |
| Dell          | Venue 11 Pro 7140           | [328f9e8d94](https://bsd-hardware.info/?probe=328f9e8d94) | Feb 04, 2022 |
| HP            | EliteBook 6930p             | [d8fb34de12](https://bsd-hardware.info/?probe=d8fb34de12) | Feb 04, 2022 |
| Lenovo        | ThinkPad X220 4291H77       | [dd4d3a9dcc](https://bsd-hardware.info/?probe=dd4d3a9dcc) | Feb 02, 2022 |
| HP            | Mini 210-1000               | [8a8bfdaee1](https://bsd-hardware.info/?probe=8a8bfdaee1) | Feb 02, 2022 |
| HP            | G62                         | [476193bfd0](https://bsd-hardware.info/?probe=476193bfd0) | Feb 01, 2022 |
| Lenovo        | ThinkPad T510 4384AJ6       | [70a56029e7](https://bsd-hardware.info/?probe=70a56029e7) | Jan 31, 2022 |
| HP            | Laptop 15-rb0xx             | [8e9a6cff62](https://bsd-hardware.info/?probe=8e9a6cff62) | Jan 31, 2022 |
| Apple         | MacBook4,1                  | [e89404ebed](https://bsd-hardware.info/?probe=e89404ebed) | Jan 29, 2022 |
| Samsung       | N150P/N210P/N220P           | [901a483718](https://bsd-hardware.info/?probe=901a483718) | Jan 29, 2022 |
| Apple         | MacBook5,2                  | [ee6e794728](https://bsd-hardware.info/?probe=ee6e794728) | Jan 29, 2022 |
| Acer          | Aspire 5930                 | [754db09c98](https://bsd-hardware.info/?probe=754db09c98) | Jan 28, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [11bbfce5d4](https://bsd-hardware.info/?probe=11bbfce5d4) | Jan 27, 2022 |
| Dell          | Latitude 7280               | [089b61bb38](https://bsd-hardware.info/?probe=089b61bb38) | Jan 27, 2022 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [b1d702812e](https://bsd-hardware.info/?probe=b1d702812e) | Jan 26, 2022 |
| MSI           | GE75 Raider 10SFS           | [306f312c47](https://bsd-hardware.info/?probe=306f312c47) | Jan 25, 2022 |
| HP            | Laptop 15-bw0xx             | [1c8f50f7eb](https://bsd-hardware.info/?probe=1c8f50f7eb) | Jan 24, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [7859f220b9](https://bsd-hardware.info/?probe=7859f220b9) | Jan 22, 2022 |
| Acer          | Aspire ES1-311              | [83addddaa5](https://bsd-hardware.info/?probe=83addddaa5) | Jan 22, 2022 |
| Dell          | Latitude E6540              | [529768f8c8](https://bsd-hardware.info/?probe=529768f8c8) | Jan 21, 2022 |
| HP            | EliteBook 2560p             | [4d04ececbb](https://bsd-hardware.info/?probe=4d04ececbb) | Jan 19, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | [384d2f888b](https://bsd-hardware.info/?probe=384d2f888b) | Jan 18, 2022 |
| Gateway       | NE56R                       | [a5aa8aa49a](https://bsd-hardware.info/?probe=a5aa8aa49a) | Jan 18, 2022 |
| Lenovo        | ThinkPad T410 2522E38       | [2dbb2679f1](https://bsd-hardware.info/?probe=2dbb2679f1) | Jan 17, 2022 |
| Dell          | Latitude E5430 non-vPro     | [e795c7ec91](https://bsd-hardware.info/?probe=e795c7ec91) | Jan 17, 2022 |
| Lenovo        | ThinkPad T440 20B7000PHV    | [9584ae69fa](https://bsd-hardware.info/?probe=9584ae69fa) | Jan 16, 2022 |
| Lenovo        | ThinkPad R61 8935WCS        | [9cc0f26f6f](https://bsd-hardware.info/?probe=9cc0f26f6f) | Jan 16, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | [5a585443b2](https://bsd-hardware.info/?probe=5a585443b2) | Jan 15, 2022 |
| Acer          | V5-131                      | [e4d0f66ff8](https://bsd-hardware.info/?probe=e4d0f66ff8) | Jan 13, 2022 |
| Acer          | Aspire ES1-533              | [a9d2458de5](https://bsd-hardware.info/?probe=a9d2458de5) | Jan 13, 2022 |
| Acer          | Aspire E5-476G              | [2a8624ee35](https://bsd-hardware.info/?probe=2a8624ee35) | Jan 10, 2022 |
| Lenovo        | ThinkPad L450 20DSS1S402    | [3c27c8bf31](https://bsd-hardware.info/?probe=3c27c8bf31) | Jan 09, 2022 |
| Dell          | Latitude E6530              | [0fa21bcf23](https://bsd-hardware.info/?probe=0fa21bcf23) | Jan 09, 2022 |
| Dell          | Inspiron 3505               | [8d4b342fda](https://bsd-hardware.info/?probe=8d4b342fda) | Jan 08, 2022 |
| Dell          | Inspiron 3505               | [8cbe3d4581](https://bsd-hardware.info/?probe=8cbe3d4581) | Jan 08, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [7aea2ccaa7](https://bsd-hardware.info/?probe=7aea2ccaa7) | Jan 08, 2022 |
| Lenovo        | ThinkPad E15 20RD0011MX     | [0fa4700d17](https://bsd-hardware.info/?probe=0fa4700d17) | Jan 07, 2022 |
| HP            | Laptop 14-dk0xxx            | [e7b40f6e3b](https://bsd-hardware.info/?probe=e7b40f6e3b) | Jan 06, 2022 |
| Notebook      | N15_17RD                    | [47c30b962d](https://bsd-hardware.info/?probe=47c30b962d) | Jan 05, 2022 |
| Lenovo        | ThinkPad L450 20DSS1S402    | [bf95cdeb53](https://bsd-hardware.info/?probe=bf95cdeb53) | Jan 04, 2022 |
| Dell          | Latitude 7380               | [590b374836](https://bsd-hardware.info/?probe=590b374836) | Jan 02, 2022 |
| Dell          | Latitude E6540              | [f5a43a9f8b](https://bsd-hardware.info/?probe=f5a43a9f8b) | Jan 02, 2022 |
| Lenovo        | ThinkPad X220 4293AF4       | [8c7992e557](https://bsd-hardware.info/?probe=8c7992e557) | Jan 01, 2022 |
| Dell          | Latitude E6540              | [97d152656e](https://bsd-hardware.info/?probe=97d152656e) | Dec 31, 2021 |
| HP            | ProBook 655 G1              | [da312d7c14](https://bsd-hardware.info/?probe=da312d7c14) | Dec 30, 2021 |
| Acer          | Aspire 5742G                | [b77a4ee97c](https://bsd-hardware.info/?probe=b77a4ee97c) | Dec 30, 2021 |
| ASUSTek       | S550CA                      | [1263a5fb37](https://bsd-hardware.info/?probe=1263a5fb37) | Dec 29, 2021 |
| Lenovo        | ThinkPad E580 20KS005BRI    | [b533989df5](https://bsd-hardware.info/?probe=b533989df5) | Dec 29, 2021 |
| Dell          | Inspiron 3521               | [b246d110af](https://bsd-hardware.info/?probe=b246d110af) | Dec 28, 2021 |
| Lenovo        | ThinkPad T460 20FMS75800    | [5f17e74f2f](https://bsd-hardware.info/?probe=5f17e74f2f) | Dec 27, 2021 |
| Acer          | Aspire 5742G                | [b650885b00](https://bsd-hardware.info/?probe=b650885b00) | Dec 24, 2021 |
| Acer          | TravelMate 5760G            | [46204b90d0](https://bsd-hardware.info/?probe=46204b90d0) | Dec 24, 2021 |
| Lenovo        | ThinkPad SL510 2847R96      | [b0a9802877](https://bsd-hardware.info/?probe=b0a9802877) | Dec 22, 2021 |
| Lenovo        | ThinkPad T410 2537EA8       | [8b457cd635](https://bsd-hardware.info/?probe=8b457cd635) | Dec 22, 2021 |
| Lenovo        | ThinkPad X250 20CLS1WP01    | [87bc0b8924](https://bsd-hardware.info/?probe=87bc0b8924) | Dec 22, 2021 |
| Toshiba       | Satellite C50-B             | [6b03a2c4c2](https://bsd-hardware.info/?probe=6b03a2c4c2) | Dec 22, 2021 |
| Samsung       | 305E4A/305E5A/305E7A        | [5188a12b26](https://bsd-hardware.info/?probe=5188a12b26) | Dec 21, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [2e1c585715](https://bsd-hardware.info/?probe=2e1c585715) | Dec 21, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [4c22212c20](https://bsd-hardware.info/?probe=4c22212c20) | Dec 20, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [1a193c7bf9](https://bsd-hardware.info/?probe=1a193c7bf9) | Dec 20, 2021 |
| Toshiba       | Satellite L550              | [977298a601](https://bsd-hardware.info/?probe=977298a601) | Dec 20, 2021 |
| ASUSTek       | N56VB                       | [f53b3fba5c](https://bsd-hardware.info/?probe=f53b3fba5c) | Dec 20, 2021 |
| HP            | 15 Notebook PC              | [1e888f2278](https://bsd-hardware.info/?probe=1e888f2278) | Dec 20, 2021 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [6321f4bd3a](https://bsd-hardware.info/?probe=6321f4bd3a) | Dec 20, 2021 |
| Dell          | Latitude E5470              | [18470afd9d](https://bsd-hardware.info/?probe=18470afd9d) | Dec 19, 2021 |
| HP            | ZBook Studio G4             | [cdc6f54d97](https://bsd-hardware.info/?probe=cdc6f54d97) | Dec 14, 2021 |
| Apple         | MacBookAir1,1               | [61c7028e83](https://bsd-hardware.info/?probe=61c7028e83) | Dec 07, 2021 |
| ASUSTek       | X540LA                      | [fa809be73f](https://bsd-hardware.info/?probe=fa809be73f) | Dec 04, 2021 |
| ASUSTek       | X540LA                      | [cf5fd87781](https://bsd-hardware.info/?probe=cf5fd87781) | Dec 04, 2021 |
| Acer          | Swift SF314-52              | [e3ece211a0](https://bsd-hardware.info/?probe=e3ece211a0) | Dec 03, 2021 |
| Toshiba       | Satellite S55t-B            | [f6983391aa](https://bsd-hardware.info/?probe=f6983391aa) | Nov 28, 2021 |
| Lenovo        | ThinkPad X240 20AMS2QDOC    | [66cfdd2419](https://bsd-hardware.info/?probe=66cfdd2419) | Nov 27, 2021 |
| Lenovo        | V310-14IKB 80T2             | [f5421b8fe0](https://bsd-hardware.info/?probe=f5421b8fe0) | Nov 23, 2021 |
| Toshiba       | Satellite C640              | [2d60f00479](https://bsd-hardware.info/?probe=2d60f00479) | Nov 17, 2021 |
| Toshiba       | Satellite C640              | [89a9551487](https://bsd-hardware.info/?probe=89a9551487) | Nov 17, 2021 |
| Lenovo        | ThinkPad T60 1951FEG        | [e2d5391a1a](https://bsd-hardware.info/?probe=e2d5391a1a) | Nov 14, 2021 |
| ASUSTek       | K52Jc                       | [92b975763f](https://bsd-hardware.info/?probe=92b975763f) | Nov 08, 2021 |
| Apple         | MacBookAir5,1               | [10d629e1a0](https://bsd-hardware.info/?probe=10d629e1a0) | Nov 04, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [3c64328fbe](https://bsd-hardware.info/?probe=3c64328fbe) | Oct 13, 2021 |

System
------

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart_bsd/os_arch.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| amd64 | 227       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 225       | 99.12%  |
| GNOME        | 2         | 0.88%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 227       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| SLiM | 227       | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 213       | 93.42%  |
| es_ES | 5         | 2.19%   |
| fr_FR | 3         | 1.32%   |
| C     | 3         | 1.32%   |
| uk_UA | 1         | 0.44%   |
| tr_TR | 1         | 0.44%   |
| it_IT | 1         | 0.44%   |
| de_DE | 1         | 0.44%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 223       | 98.24%  |
| BIOS | 4         | 1.76%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Zfs    | 119       | 51.52%  |
| Cd9660 | 112       | 48.48%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 226       | 99.56%  |
| MBR  | 1         | 0.44%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 73        | 32.16%  |
| Hewlett-Packard     | 37        | 16.3%   |
| Dell                | 26        | 11.45%  |
| Acer                | 25        | 11.01%  |
| Apple               | 14        | 6.17%   |
| ASUSTek Computer    | 13        | 5.73%   |
| Toshiba             | 6         | 2.64%   |
| Samsung Electronics | 5         | 2.2%    |
| TUXEDO              | 3         | 1.32%   |
| Sony                | 3         | 1.32%   |
| Razer               | 2         | 0.88%   |
| MSI                 | 2         | 0.88%   |
| LG Electronics      | 2         | 0.88%   |
| HASEE Computer      | 2         | 0.88%   |
| Fujitsu             | 2         | 0.88%   |
| TWINHEAD            | 1         | 0.44%   |
| Panasonic           | 1         | 0.44%   |
| Packard Bell        | 1         | 0.44%   |
| Notebook            | 1         | 0.44%   |
| Monster             | 1         | 0.44%   |
| Itautec             | 1         | 0.44%   |
| GPD                 | 1         | 0.44%   |
| Gateway             | 1         | 0.44%   |
| eMachines           | 1         | 0.44%   |
| DNS                 | 1         | 0.44%   |
| Alienware           | 1         | 0.44%   |
| Unknown             | 1         | 0.44%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                               | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Apple MacBook4,1                                   | 4         | 1.76%   |
| TUXEDO Aura 15 Gen1                                | 2         | 0.88%   |
| Lenovo IdeaPad 110-14AST 80TQ                      | 2         | 0.88%   |
| HP ProBook 4540s                                   | 2         | 0.88%   |
| HP Pavilion g6                                     | 2         | 0.88%   |
| HP Pavilion dv6                                    | 2         | 0.88%   |
| HP 2000                                            | 2         | 0.88%   |
| Dell Precision 7710                                | 2         | 0.88%   |
| Dell Latitude E5470                                | 2         | 0.88%   |
| Dell Latitude D630                                 | 2         | 0.88%   |
| Apple MacBook6,1                                   | 2         | 0.88%   |
| Apple MacBook5,1                                   | 2         | 0.88%   |
| Acer V5-131                                        | 2         | 0.88%   |
| Acer Aspire ES1-533                                | 2         | 0.88%   |
| Acer Aspire E1-522                                 | 2         | 0.88%   |
| Acer Aspire 5930                                   | 2         | 0.88%   |
| TWINHEAD U12CT                                     | 1         | 0.44%   |
| TUXEDO InfinityBook13V3                            | 1         | 0.44%   |
| Toshiba Satellite S55t-B                           | 1         | 0.44%   |
| Toshiba Satellite P300                             | 1         | 0.44%   |
| Toshiba Satellite L550                             | 1         | 0.44%   |
| Toshiba Satellite C640                             | 1         | 0.44%   |
| Toshiba Satellite C50-B                            | 1         | 0.44%   |
| Toshiba PORTEGE R700                               | 1         | 0.44%   |
| Sony VPCSB11FX                                     | 1         | 0.44%   |
| Sony VGN-NW25GF_S                                  | 1         | 0.44%   |
| Sony SVZ1311C5E                                    | 1         | 0.44%   |
| Samsung Q430/Q530                                  | 1         | 0.44%   |
| Samsung N150P/N210P/N220P                          | 1         | 0.44%   |
| Samsung N100                                       | 1         | 0.44%   |
| Samsung 305E4A/305E5A/305E7A                       | 1         | 0.44%   |
| Samsung 300E4C/300E5C/300E7C                       | 1         | 0.44%   |
| Razer Blade Stealth                                | 1         | 0.44%   |
| Razer Blade 15 Base Model (Early 2020) - RZ09-0328 | 1         | 0.44%   |
| Panasonic CF-B11JWCYS                              | 1         | 0.44%   |
| Packard Bell EasyNote TE69HW                       | 1         | 0.44%   |
| Notebook N15_17RD                                  | 1         | 0.44%   |
| MSI GF65 Thin 10SER                                | 1         | 0.44%   |
| MSI GF63 Thin 10SC                                 | 1         | 0.44%   |
| Monster ABRA A7 V11.2                              | 1         | 0.44%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 47        | 20.7%   |
| Acer Aspire             | 19        | 8.37%   |
| HP Pavilion             | 13        | 5.73%   |
| Dell Latitude           | 12        | 5.29%   |
| Lenovo IdeaPad          | 11        | 4.85%   |
| Dell Inspiron           | 8         | 3.52%   |
| HP ProBook              | 7         | 3.08%   |
| Toshiba Satellite       | 5         | 2.2%    |
| HP Laptop               | 4         | 1.76%   |
| Apple MacBook4          | 4         | 1.76%   |
| Lenovo Legion           | 3         | 1.32%   |
| HP EliteBook            | 3         | 1.32%   |
| Dell Precision          | 3         | 1.32%   |
| Apple MacBook5          | 3         | 1.32%   |
| TUXEDO Aura             | 2         | 0.88%   |
| Razer Blade             | 2         | 0.88%   |
| HP Compaq               | 2         | 0.88%   |
| HP 2000                 | 2         | 0.88%   |
| Fujitsu LIFEBOOK        | 2         | 0.88%   |
| Apple MacBookPro5       | 2         | 0.88%   |
| Apple MacBook6          | 2         | 0.88%   |
| Acer V5-131             | 2         | 0.88%   |
| Acer TravelMate         | 2         | 0.88%   |
| TWINHEAD U12CT          | 1         | 0.44%   |
| TUXEDO InfinityBook13V3 | 1         | 0.44%   |
| Toshiba PORTEGE         | 1         | 0.44%   |
| Sony VPCSB11FX          | 1         | 0.44%   |
| Sony VGN-NW25GF         | 1         | 0.44%   |
| Sony SVZ1311C5E         | 1         | 0.44%   |
| Samsung Q430            | 1         | 0.44%   |
| Samsung N150P           | 1         | 0.44%   |
| Samsung N100            | 1         | 0.44%   |
| Samsung 305E4A          | 1         | 0.44%   |
| Samsung 300E4C          | 1         | 0.44%   |
| Panasonic CF-B11JWCYS   | 1         | 0.44%   |
| Packard Bell EasyNote   | 1         | 0.44%   |
| Notebook N15            | 1         | 0.44%   |
| MSI GF65                | 1         | 0.44%   |
| MSI GF63                | 1         | 0.44%   |
| Monster ABRA            | 1         | 0.44%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2016    | 21        | 9.25%   |
| 2013    | 19        | 8.37%   |
| 2011    | 19        | 8.37%   |
| 2010    | 19        | 8.37%   |
| 2020    | 18        | 7.93%   |
| 2012    | 17        | 7.49%   |
| 2014    | 16        | 7.05%   |
| 2021    | 14        | 6.17%   |
| 2017    | 14        | 6.17%   |
| 2015    | 14        | 6.17%   |
| 2009    | 14        | 6.17%   |
| 2008    | 14        | 6.17%   |
| 2018    | 13        | 5.73%   |
| 2007    | 7         | 3.08%   |
| 2019    | 4         | 1.76%   |
| 2006    | 2         | 0.88%   |
| 2022    | 1         | 0.44%   |
| Unknown | 1         | 0.44%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 227       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 227       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 87        | 38.33%  |
| 8.01-16.0   | 73        | 32.16%  |
| 16.01-24.0  | 38        | 16.74%  |
| 2.01-3.0    | 14        | 6.17%   |
| 32.01-64.0  | 7         | 3.08%   |
| 3.01-4.0    | 5         | 2.2%    |
| 24.01-32.0  | 2         | 0.88%   |
| 64.01-256.0 | 1         | 0.44%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 144       | 63.16%  |
| 0.51-1.0 | 61        | 26.75%  |
| 1.01-2.0 | 16        | 7.02%   |
| 2.01-3.0 | 7         | 3.07%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 176       | 76.19%  |
| 2      | 43        | 18.61%  |
| 0      | 9         | 3.9%    |
| 3      | 2         | 0.87%   |
| 4      | 1         | 0.43%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 123       | 54.19%  |
| Yes       | 104       | 45.81%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 208       | 91.63%  |
| No        | 19        | 8.37%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 226       | 99.56%  |
| No        | 1         | 0.44%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 155       | 67.98%  |
| No        | 73        | 32.02%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country             | Notebooks | Percent |
|---------------------|-----------|---------|
| USA                 | 32        | 14.1%   |
| Spain               | 16        | 7.05%   |
| Russia              | 16        | 7.05%   |
| Italy               | 13        | 5.73%   |
| Germany             | 13        | 5.73%   |
| Brazil              | 12        | 5.29%   |
| UK                  | 10        | 4.41%   |
| Netherlands         | 8         | 3.52%   |
| Indonesia           | 8         | 3.52%   |
| China               | 8         | 3.52%   |
| Romania             | 6         | 2.64%   |
| Mexico              | 6         | 2.64%   |
| France              | 6         | 2.64%   |
| Vietnam             | 4         | 1.76%   |
| Ukraine             | 4         | 1.76%   |
| Poland              | 4         | 1.76%   |
| India               | 4         | 1.76%   |
| Turkey              | 3         | 1.32%   |
| Hungary             | 3         | 1.32%   |
| Colombia            | 3         | 1.32%   |
| Chile               | 3         | 1.32%   |
| Canada              | 3         | 1.32%   |
| Bulgaria            | 3         | 1.32%   |
| Sweden              | 2         | 0.88%   |
| Portugal            | 2         | 0.88%   |
| Peru                | 2         | 0.88%   |
| Norway              | 2         | 0.88%   |
| Greece              | 2         | 0.88%   |
| Egypt               | 2         | 0.88%   |
| Denmark             | 2         | 0.88%   |
| Czechia             | 2         | 0.88%   |
| Trinidad and Tobago | 1         | 0.44%   |
| Tanzania            | 1         | 0.44%   |
| Taiwan              | 1         | 0.44%   |
| Switzerland         | 1         | 0.44%   |
| Singapore           | 1         | 0.44%   |
| New Zealand         | 1         | 0.44%   |
| Myanmar             | 1         | 0.44%   |
| Malaysia            | 1         | 0.44%   |
| Lithuania           | 1         | 0.44%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Moscow           | 4         | 1.73%   |
| Madrid           | 3         | 1.3%    |
| Hanoi            | 3         | 1.3%    |
| Amsterdam        | 3         | 1.3%    |
| Yambol           | 2         | 0.87%   |
| Warsaw           | 2         | 0.87%   |
| Pflugerville     | 2         | 0.87%   |
| Milan            | 2         | 0.87%   |
| Lima             | 2         | 0.87%   |
| Leatherhead      | 2         | 0.87%   |
| Jakarta          | 2         | 0.87%   |
| Dijon            | 2         | 0.87%   |
| Curitiba         | 2         | 0.87%   |
| Cluj-Napoca      | 2         | 0.87%   |
| Budapest         | 2         | 0.87%   |
| Bucharest        | 2         | 0.87%   |
| Ankara           | 2         | 0.87%   |
| Alcobendas       | 2         | 0.87%   |
| Zhaoqing         | 1         | 0.43%   |
| Zaporizhzhya     | 1         | 0.43%   |
| Zapopan          | 1         | 0.43%   |
| Youngsville      | 1         | 0.43%   |
| Yichun           | 1         | 0.43%   |
| Yaphank          | 1         | 0.43%   |
| Yangon           | 1         | 0.43%   |
| Wuhan            | 1         | 0.43%   |
| Wroclaw          | 1         | 0.43%   |
| Windsor          | 1         | 0.43%   |
| West Linn        | 1         | 0.43%   |
| Washington       | 1         | 0.43%   |
| Vilnius          | 1         | 0.43%   |
| Ventura          | 1         | 0.43%   |
| VÃ¤sterÃ¥s   | 1         | 0.43%   |
| Vaudreuil-Dorion | 1         | 0.43%   |
| Vandalia         | 1         | 0.43%   |
| Valencia         | 1         | 0.43%   |
| Urnieta          | 1         | 0.43%   |
| Ugarchin         | 1         | 0.43%   |
| Turley           | 1         | 0.43%   |
| Turin            | 1         | 0.43%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 46        | 49     | 17.23%  |
| Samsung Electronics | 41        | 43     | 15.36%  |
| Seagate             | 30        | 35     | 11.24%  |
| Kingston            | 21        | 22     | 7.87%   |
| Toshiba             | 20        | 20     | 7.49%   |
| Crucial             | 15        | 15     | 5.62%   |
| Hitachi             | 12        | 12     | 4.49%   |
| SanDisk             | 11        | 12     | 4.12%   |
| Intel               | 9         | 10     | 3.37%   |
| HGST                | 6         | 6      | 2.25%   |
| Micron Technology   | 5         | 5      | 1.87%   |
| Fujitsu             | 5         | 5      | 1.87%   |
| SPCC                | 4         | 6      | 1.5%    |
| A-DATA Technology   | 4         | 4      | 1.5%    |
| KingSpec            | 3         | 3      | 1.12%   |
| Intenso             | 3         | 3      | 1.12%   |
| Zheino              | 2         | 2      | 0.75%   |
| SK hynix            | 2         | 2      | 0.75%   |
| Patriot             | 2         | 2      | 0.75%   |
| Corsair             | 2         | 2      | 0.75%   |
| V-GeN               | 1         | 1      | 0.37%   |
| Transcend           | 1         | 1      | 0.37%   |
| Team                | 1         | 1      | 0.37%   |
| SSSTC               | 1         | 1      | 0.37%   |
| Smartbuy            | 1         | 1      | 0.37%   |
| PNY                 | 1         | 1      | 0.37%   |
| Plextor             | 1         | 2      | 0.37%   |
| Phison              | 1         | 1      | 0.37%   |
| Netac               | 1         | 1      | 0.37%   |
| Mushkin             | 1         | 1      | 0.37%   |
| LITEON              | 1         | 1      | 0.37%   |
| Lexar               | 1         | 1      | 0.37%   |
| Leven               | 1         | 1      | 0.37%   |
| KIOXIA-EXCERIA      | 1         | 1      | 0.37%   |
| KIOXIA              | 1         | 1      | 0.37%   |
| Integral            | 1         | 1      | 0.37%   |
| INDMEM              | 1         | 1      | 0.37%   |
| Hikvision           | 1         | 1      | 0.37%   |
| Hewlett-Packard     | 1         | 1      | 0.37%   |
| BIWIN               | 1         | 1      | 0.37%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| WDC WDS120G2G0A-00JH30 120GB       | 5         | 1.84%   |
| Kingston SA400S37240G 240GB        | 5         | 1.84%   |
| HGST HTS545050A7E680 500GB         | 5         | 1.84%   |
| Toshiba MQ01ABF050 500GB           | 4         | 1.47%   |
| WDC WD5000LPVX-22V0TT0 500GB       | 3         | 1.1%    |
| Toshiba MQ01ABD100 1TB             | 3         | 1.1%    |
| Seagate ST1000LM024 HN-M101MBB 1TB | 3         | 1.1%    |
| Samsung SSD 860 EVO 250GB          | 3         | 1.1%    |
| Kingston SV300S37A120G 120GB       | 3         | 1.1%    |
| Kingston SA400S37120G 120GB        | 3         | 1.1%    |
| Crucial CT500MX500SSD1 500GB       | 3         | 1.1%    |
| Crucial CT240BX500SSD1 240GB       | 3         | 1.1%    |
| WDC WDS240G2G0A-00JH30 240GB       | 2         | 0.74%   |
| WDC WD5000LPCX-60VHAT0 500GB       | 2         | 0.74%   |
| WDC WD10JPCX-24UE4T0 1TB           | 2         | 0.74%   |
| Toshiba MK3261GSYN 320GB           | 2         | 0.74%   |
| SK hynix HFS256G39TND-N210A 256GB  | 2         | 0.74%   |
| Seagate ST9320423AS 320GB          | 2         | 0.74%   |
| Seagate ST9320325AS 320GB          | 2         | 0.74%   |
| Seagate ST500LT012-9WS142 500GB    | 2         | 0.74%   |
| Seagate ST320LT020-9YG142 320GB    | 2         | 0.74%   |
| Seagate ST1000LM035-1RK172 1TB     | 2         | 0.74%   |
| Samsung SSD PM871 2.5 7mm 128GB    | 2         | 0.74%   |
| Samsung SSD 850 EVO 500GB          | 2         | 0.74%   |
| Samsung SSD 750 EVO 250GB          | 2         | 0.74%   |
| Samsung MZVLW256HEHP-000L7 256GB   | 2         | 0.74%   |
| Kingston SA400S37480G 480GB        | 2         | 0.74%   |
| Hitachi HTS545050B9A300 500GB      | 2         | 0.74%   |
| Hitachi HTS541680J9SA00 80GB       | 2         | 0.74%   |
| Crucial CT480BX500SSD1 480GB       | 2         | 0.74%   |
| Crucial CT250BX100SSD1 250GB       | 2         | 0.74%   |
| Zheino CHN-25SATAC3-120 120GB      | 1         | 0.37%   |
| Zheino CHN mSATAM1 256 256GB       | 1         | 0.37%   |
| WDC WDS500G2B0C-00PXH0 500GB       | 1         | 0.37%   |
| WDC WDS240G1G0A-00SS50 240GB       | 1         | 0.37%   |
| WDC WDBNCE5000PNC 500GB            | 1         | 0.37%   |
| WDC WD6400BPVT-60HXZT1 640GB       | 1         | 0.37%   |
| WDC WD6400BEVT-22A0RT0 640GB       | 1         | 0.37%   |
| WDC WD5000LPVX-80V0TT0 500GB       | 1         | 0.37%   |
| WDC WD5000LPLX-60ZNTT1 500GB       | 1         | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 33        | 35     | 31.43%  |
| Seagate             | 30        | 35     | 28.57%  |
| Toshiba             | 18        | 18     | 17.14%  |
| Hitachi             | 12        | 12     | 11.43%  |
| HGST                | 6         | 6      | 5.71%   |
| Fujitsu             | 4         | 4      | 3.81%   |
| Samsung Electronics | 2         | 2      | 1.9%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 24        | 25     | 19.2%   |
| Kingston            | 18        | 18     | 14.4%   |
| Crucial             | 15        | 15     | 12%     |
| SanDisk             | 11        | 12     | 8.8%    |
| WDC                 | 9         | 9      | 7.2%    |
| Intel               | 6         | 6      | 4.8%    |
| SPCC                | 3         | 4      | 2.4%    |
| KingSpec            | 3         | 3      | 2.4%    |
| Intenso             | 3         | 3      | 2.4%    |
| A-DATA Technology   | 3         | 3      | 2.4%    |
| Zheino              | 2         | 2      | 1.6%    |
| SK hynix            | 2         | 2      | 1.6%    |
| Patriot             | 2         | 2      | 1.6%    |
| Corsair             | 2         | 2      | 1.6%    |
| V-GeN               | 1         | 1      | 0.8%    |
| Transcend           | 1         | 1      | 0.8%    |
| Toshiba             | 1         | 1      | 0.8%    |
| Team                | 1         | 1      | 0.8%    |
| Smartbuy            | 1         | 1      | 0.8%    |
| PNY                 | 1         | 1      | 0.8%    |
| Plextor             | 1         | 2      | 0.8%    |
| Phison              | 1         | 1      | 0.8%    |
| Netac               | 1         | 1      | 0.8%    |
| Mushkin             | 1         | 1      | 0.8%    |
| Micron Technology   | 1         | 1      | 0.8%    |
| LITEON              | 1         | 1      | 0.8%    |
| Lexar               | 1         | 1      | 0.8%    |
| Leven               | 1         | 1      | 0.8%    |
| KIOXIA-EXCERIA      | 1         | 1      | 0.8%    |
| Integral            | 1         | 1      | 0.8%    |
| INDMEM              | 1         | 1      | 0.8%    |
| Hewlett-Packard     | 1         | 1      | 0.8%    |
| Fujitsu             | 1         | 1      | 0.8%    |
| Apple               | 1         | 1      | 0.8%    |
| Apacer              | 1         | 1      | 0.8%    |
| ANACOMDA            | 1         | 1      | 0.8%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 113       | 129    | 45.56%  |
| HDD  | 98        | 112    | 39.52%  |
| NVMe | 37        | 42     | 14.92%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 199       | 241    | 84.32%  |
| NVMe | 37        | 42     | 15.68%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 165       | 192    | 78.95%  |
| 0.51-1.0   | 39        | 44     | 18.66%  |
| 1.01-2.0   | 4         | 4      | 1.91%   |
| 4.01-10.0  | 1         | 1      | 0.48%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 108       | 46.55%  |
| 101-250    | 59        | 25.43%  |
| 251-500    | 36        | 15.52%  |
| 501-1000   | 17        | 7.33%   |
| 21-50      | 6         | 2.59%   |
| 51-100     | 5         | 2.16%   |
| Unknown    | 1         | 0.43%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 223       | 98.24%  |
| 21-50   | 2         | 0.88%   |
| 101-250 | 1         | 0.44%   |
| Unknown | 1         | 0.44%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST320LT020-9YG142 320GB    | 2         | 2      | 3.64%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 2         | 2      | 3.64%   |
| Hitachi HTS545050B9A300 500GB      | 2         | 2      | 3.64%   |
| WDC WD5000LPLX-60ZNTT1 500GB       | 1         | 1      | 1.82%   |
| WDC WD5000LPCX-75VHAT0 500GB       | 1         | 1      | 1.82%   |
| WDC WD5000LPCX-60VHAT0 500GB       | 1         | 1      | 1.82%   |
| WDC WD5000BPVT-22HXZT3 500GB       | 1         | 1      | 1.82%   |
| WDC WD3200BPVT-80ZEST0 320GB       | 1         | 1      | 1.82%   |
| WDC WD3200BEVT-60A23T0 320GB       | 1         | 1      | 1.82%   |
| WDC WD3200BEVT-22ZCT0 320GB        | 1         | 1      | 1.82%   |
| WDC WD1600BEVT-80A23T0 160GB       | 1         | 1      | 1.82%   |
| WDC WD1600BEKT-66F3T2 160GB        | 1         | 1      | 1.82%   |
| WDC WD10SPZX-24Z10T0 1TB           | 1         | 1      | 1.82%   |
| WDC WD10SPZX-21Z10T0 1TB           | 1         | 1      | 1.82%   |
| WDC WD10JPVX-22JC3T0 1TB           | 1         | 1      | 1.82%   |
| WDC WD10JMVW-11AJGS2 1TB           | 1         | 1      | 1.82%   |
| Toshiba THNSNX024GMNT 24GB         | 1         | 1      | 1.82%   |
| Toshiba MQ01ABF050 500GB           | 1         | 1      | 1.82%   |
| Toshiba MQ01ABD100 1TB             | 1         | 1      | 1.82%   |
| Toshiba MQ01ABD075 752GB           | 1         | 1      | 1.82%   |
| Toshiba MK8034GSX 80GB             | 1         | 1      | 1.82%   |
| Toshiba MK7559GSXF 752GB           | 1         | 1      | 1.82%   |
| Toshiba MK6034GSX 64GB             | 1         | 1      | 1.82%   |
| Toshiba MK3265GSXN 320GB           | 1         | 1      | 1.82%   |
| Toshiba MK3261GSYN 320GB           | 1         | 1      | 1.82%   |
| Toshiba MK1059GSM 1TB              | 1         | 1      | 1.82%   |
| Seagate ST9640320AS 640GB          | 1         | 1      | 1.82%   |
| Seagate ST9500325AS 500GB          | 1         | 1      | 1.82%   |
| Seagate ST9320423AS 320GB          | 1         | 1      | 1.82%   |
| Seagate ST9320325AS 320GB          | 1         | 1      | 1.82%   |
| Seagate ST9160412AS 160GB          | 1         | 1      | 1.82%   |
| Seagate ST9120821AS 120GB          | 1         | 1      | 1.82%   |
| Seagate ST500LT012-9WS142 500GB    | 1         | 1      | 1.82%   |
| Seagate ST320LT007-9ZV142 320GB    | 1         | 1      | 1.82%   |
| Seagate ST3160212AS 160GB          | 1         | 1      | 1.82%   |
| Seagate ST1000LM014-1EJ164 1TB     | 1         | 1      | 1.82%   |
| Samsung Electronics HS082HB 80GB   | 1         | 1      | 1.82%   |
| Samsung Electronics HM160HI 160GB  | 1         | 1      | 1.82%   |
| LITEON CV8-8E128-HP 128GB          | 1         | 1      | 1.82%   |
| Kingston SV300S37A120G 120GB       | 1         | 1      | 1.82%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 14        | 14     | 25.45%  |
| WDC                 | 13        | 13     | 23.64%  |
| Toshiba             | 10        | 10     | 18.18%  |
| Hitachi             | 8         | 8      | 14.55%  |
| Samsung Electronics | 2         | 2      | 3.64%   |
| Kingston            | 2         | 2      | 3.64%   |
| HGST                | 2         | 2      | 3.64%   |
| LITEON              | 1         | 1      | 1.82%   |
| Fujitsu             | 1         | 1      | 1.82%   |
| Corsair             | 1         | 1      | 1.82%   |
| AGI                 | 1         | 1      | 1.82%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 14        | 14     | 28.57%  |
| WDC                 | 13        | 13     | 26.53%  |
| Toshiba             | 9         | 9      | 18.37%  |
| Hitachi             | 8         | 8      | 16.33%  |
| Samsung Electronics | 2         | 2      | 4.08%   |
| HGST                | 2         | 2      | 4.08%   |
| Fujitsu             | 1         | 1      | 2.04%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 45        | 49     | 88.24%  |
| SSD  | 5         | 5      | 9.8%    |
| NVMe | 1         | 1      | 1.96%   |

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
| Works    | 176       | 227    | 77.19%  |
| Malfunc  | 51        | 55     | 22.37%  |
| Detected | 1         | 1      | 0.44%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 182       | 72.51%  |
| AMD                              | 26        | 10.36%  |
| Samsung Electronics              | 16        | 6.37%   |
| Nvidia                           | 7         | 2.79%   |
| SanDisk                          | 5         | 1.99%   |
| Micron Technology                | 4         | 1.59%   |
| Silicon Motion                   | 2         | 0.8%    |
| KIOXIA                           | 2         | 0.8%    |
| Kingston Technology Company      | 2         | 0.8%    |
| Solid State Storage Technology   | 1         | 0.4%    |
| Silicon Integrated Systems [SiS] | 1         | 0.4%    |
| Realtek Semiconductor            | 1         | 0.4%    |
| Biwin Storage Technology         | 1         | 0.4%    |
| ADATA Technology                 | 1         | 0.4%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 25        | 9.09%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 23        | 8.36%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 22        | 8%      |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 17        | 6.18%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 16        | 5.82%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 16        | 5.82%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 15        | 5.45%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 14        | 5.09%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 9         | 3.27%   |
| Nvidia MCP79 AHCI Controller                                                     | 7         | 2.55%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 6         | 2.18%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 6         | 2.18%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 6         | 2.18%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 6         | 2.18%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 6         | 2.18%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 5         | 1.82%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 5         | 1.82%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 5         | 1.82%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 5         | 1.82%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 4         | 1.45%   |
| Micron 2200S NVMe SSD [Cassandra]                                                | 3         | 1.09%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 3         | 1.09%   |
| Intel Comet Lake SATA AHCI Controller                                            | 3         | 1.09%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 3         | 1.09%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)        | 2         | 0.73%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 2         | 0.73%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 2         | 0.73%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 2         | 0.73%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 2         | 0.73%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 2         | 0.73%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 2         | 0.73%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 2         | 0.73%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 2         | 0.73%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 2         | 0.73%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                   | 1         | 0.36%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 1         | 0.36%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                    | 1         | 0.36%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 0.36%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 1         | 0.36%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                            | 1         | 0.36%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 202       | 75.09%  |
| NVMe | 36        | 13.38%  |
| IDE  | 24        | 8.92%   |
| RAID | 7         | 2.6%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 197       | 86.78%  |
| AMD    | 30        | 13.22%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz       | 8         | 3.52%   |
| Intel CPU Version                       | 7         | 3.08%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 5         | 2.2%    |
| Intel Core i5-6300U CPU @ 2.40GHz       | 5         | 2.2%    |
| Intel Core i5-3210M CPU @ 2.50GHz       | 4         | 1.76%   |
| Intel Core i5 CPU M 520 @ 2.40GHz       | 4         | 1.76%   |
| Intel Core i3-4005U CPU @ 1.70GHz       | 4         | 1.76%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz    | 4         | 1.76%   |
| Intel Core i7-3612QM CPU @ 2.10GHz      | 3         | 1.32%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 3         | 1.32%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 3         | 1.32%   |
| Intel Core i5-4300M CPU @ 2.60GHz       | 3         | 1.32%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 3         | 1.32%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 3         | 1.32%   |
| Intel Core i3-6006U CPU @ 2.00GHz       | 3         | 1.32%   |
| Intel Core i3-3110M CPU @ 2.40GHz       | 3         | 1.32%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz    | 3         | 1.32%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz    | 3         | 1.32%   |
| Intel Core 2 Duo CPU P7550 @ 2.26GHz    | 3         | 1.32%   |
| AMD E1-2500 APU with Radeon HD Graphics | 3         | 1.32%   |
| Intel Genuine CPU                       | 2         | 0.88%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 2         | 0.88%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 2         | 0.88%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz      | 2         | 0.88%   |
| Intel Core i7-4600U CPU @ 2.10GHz       | 2         | 0.88%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 2         | 0.88%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 2         | 0.88%   |
| Intel Core i5-9300H CPU @ 2.40GHz       | 2         | 0.88%   |
| Intel Core i5-7300U CPU @ 2.60GHz       | 2         | 0.88%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 2         | 0.88%   |
| Intel Core i5-4200U CPU @ 1.60GHz       | 2         | 0.88%   |
| Intel Core i5-3317U CPU @ 1.70GHz       | 2         | 0.88%   |
| Intel Core i5-2410M CPU @ 2.30GHz       | 2         | 0.88%   |
| Intel Core i5-10300H CPU @ 2.50GHz      | 2         | 0.88%   |
| Intel Core i3-5005U CPU @ 2.00GHz       | 2         | 0.88%   |
| Intel Core i3-2330M CPU @ 2.20GHz       | 2         | 0.88%   |
| Intel Core i3-2310M CPU @ 2.10GHz       | 2         | 0.88%   |
| Intel Core i3 CPU M 330 @ 2.13GHz       | 2         | 0.88%   |
| Intel Core 2 Duo CPU T9400 @ 2.53GHz    | 2         | 0.88%   |
| Intel Core 2 Duo CPU T6600 @ 2.20GHz    | 2         | 0.88%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 69        | 30.4%   |
| Intel Core i7           | 32        | 14.1%   |
| Intel Core 2 Duo        | 28        | 12.33%  |
| Intel Core i3           | 24        | 10.57%  |
| Intel Celeron           | 15        | 6.61%   |
| Other                   | 11        | 4.85%   |
| AMD Ryzen 5             | 8         | 3.52%   |
| Intel Pentium           | 5         | 2.2%    |
| AMD E1                  | 5         | 2.2%    |
| AMD A6                  | 5         | 2.2%    |
| Intel Atom              | 4         | 1.76%   |
| Intel Core 2            | 3         | 1.32%   |
| AMD Ryzen 7             | 3         | 1.32%   |
| Intel Pentium Dual-Core | 2         | 0.88%   |
| Intel Genuine           | 2         | 0.88%   |
| AMD E2                  | 2         | 0.88%   |
| Intel Xeon              | 1         | 0.44%   |
| Intel Pentium Silver    | 1         | 0.44%   |
| Intel Pentium M         | 1         | 0.44%   |
| Intel Pentium Dual      | 1         | 0.44%   |
| Intel Core M            | 1         | 0.44%   |
| Intel Celeron Dual-Core | 1         | 0.44%   |
| AMD Ryzen 3             | 1         | 0.44%   |
| AMD A8                  | 1         | 0.44%   |
| AMD A10                 | 1         | 0.44%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 131       | 57.71%  |
| 4       | 42        | 18.5%   |
| Unknown | 34        | 14.98%  |
| 6       | 8         | 3.52%   |
| 8       | 7         | 3.08%   |
| 12      | 3         | 1.32%   |
| 1       | 2         | 0.88%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 212       | 93.39%  |
| 2       | 13        | 5.73%   |
| Unknown | 2         | 0.88%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 128       | 56.39%  |
| 1       | 65        | 28.63%  |
| Unknown | 34        | 14.98%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| Penryn      | 31        | 13.66%  |
| IvyBridge   | 26        | 11.45%  |
| KabyLake    | 25        | 11.01%  |
| Haswell     | 22        | 9.69%   |
| Skylake     | 18        | 7.93%   |
| SandyBridge | 18        | 7.93%   |
| Westmere    | 15        | 6.61%   |
| Core        | 12        | 5.29%   |
| Silvermont  | 11        | 4.85%   |
| Broadwell   | 6         | 2.64%   |
| Zen+        | 5         | 2.2%    |
| Zen 2       | 5         | 2.2%    |
| Jaguar      | 5         | 2.2%    |
| Excavator   | 5         | 2.2%    |
| CometLake   | 5         | 2.2%    |
| Bonnell     | 4         | 1.76%   |
| Goldmont    | 3         | 1.32%   |
| Bobcat      | 3         | 1.32%   |
| Zen         | 2         | 0.88%   |
| Puma        | 2         | 0.88%   |
| Zen 3       | 1         | 0.44%   |
| Piledriver  | 1         | 0.44%   |
| K10 Llano   | 1         | 0.44%   |
| Unknown     | 1         | 0.44%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 169       | 62.59%  |
| Nvidia | 51        | 18.89%  |
| AMD    | 50        | 18.52%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 25        | 8.68%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 18        | 6.25%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 16        | 5.56%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 14        | 4.86%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 14        | 4.86%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 12        | 4.17%   |
| Intel Core Processor Integrated Graphics Controller                                      | 11        | 3.82%   |
| Intel HD Graphics 620                                                                    | 9         | 3.13%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 7         | 2.43%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 6         | 2.08%   |
| Nvidia C79 [GeForce 9400M]                                                               | 6         | 2.08%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 6         | 2.08%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 6         | 2.08%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 6         | 2.08%   |
| Intel HD Graphics 5500                                                                   | 5         | 1.74%   |
| Intel HD Graphics 530                                                                    | 5         | 1.74%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 5         | 1.74%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 1.74%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 5         | 1.74%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 5         | 1.74%   |
| Intel UHD Graphics 620                                                                   | 4         | 1.39%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 4         | 1.39%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/5145/530v/540v/545v]                         | 4         | 1.39%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 3         | 1.04%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 3         | 1.04%   |
| Intel HD Graphics 500                                                                    | 3         | 1.04%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 1.04%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 1.04%   |
| AMD Kabini [Radeon HD 8240 / R3 Series]                                                  | 3         | 1.04%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 0.69%   |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 0.69%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 2         | 0.69%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 2         | 0.69%   |
| Nvidia GF119M [GeForce 610M]                                                             | 2         | 0.69%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 0.69%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 0.69%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 0.69%   |
| Intel HD Graphics 630                                                                    | 2         | 0.69%   |
| AMD Wrestler [Radeon HD 7310]                                                            | 2         | 0.69%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 2         | 0.69%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 103       | 45.18%  |
| 1 x AMD        | 35        | 15.35%  |
| Intel + Nvidia | 29        | 12.72%  |
| 2 x Intel      | 27        | 11.84%  |
| 1 x Nvidia     | 18        | 7.89%   |
| Intel + AMD    | 10        | 4.39%   |
| AMD + Nvidia   | 4         | 1.75%   |
| 2 x Nvidia     | 1         | 0.44%   |
| 2 x AMD        | 1         | 0.44%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 203       | 89.04%  |
| Proprietary | 21        | 9.21%   |
| Unknown     | 4         | 1.75%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 174       | 76.32%  |
| 0.01-0.5   | 36        | 15.79%  |
| 0.51-1.0   | 7         | 3.07%   |
| 1.01-2.0   | 5         | 2.19%   |
| 3.01-4.0   | 3         | 1.32%   |
| 5.01-6.0   | 2         | 0.88%   |
| 2.01-3.0   | 1         | 0.44%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 42        | 18.42%  |
| AU Optronics            | 37        | 16.23%  |
| Chimei Innolux          | 33        | 14.47%  |
| Samsung Electronics     | 28        | 12.28%  |
| BOE                     | 24        | 10.53%  |
| Lenovo                  | 20        | 8.77%   |
| Apple                   | 14        | 6.14%   |
| Chi Mei Optoelectronics | 5         | 2.19%   |
| Sharp                   | 3         | 1.32%   |
| PANDA                   | 3         | 1.32%   |
| LG Philips              | 2         | 0.88%   |
| Goldstar                | 2         | 0.88%   |
| Vestel Elektronik       | 1         | 0.44%   |
| Toshiba                 | 1         | 0.44%   |
| Sony                    | 1         | 0.44%   |
| SLD                     | 1         | 0.44%   |
| Philips                 | 1         | 0.44%   |
| NCS                     | 1         | 0.44%   |
| LPL                     | 1         | 0.44%   |
| Lenovo Group Limited    | 1         | 0.44%   |
| LED                     | 1         | 0.44%   |
| InfoVision              | 1         | 0.44%   |
| HannStar                | 1         | 0.44%   |
| BenQ                    | 1         | 0.44%   |
| AOC                     | 1         | 0.44%   |
| Ancor Communications    | 1         | 0.44%   |
| Acer                    | 1         | 0.44%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Lenovo LCD Monitor LEN4031 1280x800 300x190mm 14.0-inch               | 5         | 2.16%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch      | 4         | 1.73%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 330x210mm 15.4-inch  | 3         | 1.3%    |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 340x190mm 15.3-inch       | 3         | 1.3%    |
| BOE LCD Monitor BOE0698 1366x768 310x170mm 13.9-inch                  | 3         | 1.3%    |
| AU Optronics LCD Monitor AUO26EC 1366x768 340x190mm 15.3-inch         | 3         | 1.3%    |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch  | 2         | 0.87%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 340x190mm 15.3-inch | 2         | 0.87%   |
| LG Display LCD Monitor LGD0459 1920x1080 380x210mm 17.1-inch          | 2         | 0.87%   |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch           | 2         | 0.87%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch           | 2         | 0.87%   |
| LG Display LCD Monitor LGD0250 1366x768 350x190mm 15.7-inch           | 2         | 0.87%   |
| Lenovo LCD Monitor LEN40B0 1366x768 340x190mm 15.3-inch               | 2         | 0.87%   |
| Lenovo LCD Monitor LEN40A0 1366x768 310x170mm 13.9-inch               | 2         | 0.87%   |
| Lenovo LCD Monitor LEN4050 1280x800 330x210mm 15.4-inch               | 2         | 0.87%   |
| Lenovo LCD Monitor LEN4035 1280x800 300x190mm 14.0-inch               | 2         | 0.87%   |
| Chimei Innolux LCD Monitor CMN1492 1366x768 310x170mm 13.9-inch       | 2         | 0.87%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 310x170mm 13.9-inch       | 2         | 0.87%   |
| AU Optronics LCD Monitor AUO325C 1366x768 260x140mm 11.6-inch         | 2         | 0.87%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 310x170mm 13.9-inch        | 2         | 0.87%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch         | 2         | 0.87%   |
| Apple LCD Monitor APP9C5F 1280x800 290x180mm 13.4-inch                | 2         | 0.87%   |
| Apple Color LCD APP9C5E 1280x800 290x190mm 13.6-inch                  | 2         | 0.87%   |
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 710x400mm 32.1-inch    | 1         | 0.43%   |
| Toshiba TV TSB0108 1360x768 890x500mm 40.2-inch                       | 1         | 0.43%   |
| Sony LCD SNY06FA 1600x900 290x160mm 13.0-inch                         | 1         | 0.43%   |
| SLD LCD Monitor SLD003C 1366x768 310x170mm 13.9-inch                  | 1         | 0.43%   |
| Sharp LQ140Z1JW01 SHP1401 3200x1800 310x170mm 13.9-inch               | 1         | 0.43%   |
| Sharp LCD Monitor SHP14BA 1920x1080 340x190mm 15.3-inch               | 1         | 0.43%   |
| Sharp LCD Monitor SHP144D 3840x2160 280x160mm 12.7-inch               | 1         | 0.43%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 610x350mm 27.7-inch     | 1         | 0.43%   |
| Samsung Electronics S27C350 SAM0A3E 1920x1080 600x340mm 27.2-inch     | 1         | 0.43%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch     | 1         | 0.43%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 410x230mm 18.5-inch | 1         | 0.43%   |
| Samsung Electronics LCD Monitor SEC4E41 1366x768 350x200mm 15.9-inch  | 1         | 0.43%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 300x170mm 13.6-inch  | 1         | 0.43%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 340x190mm 15.3-inch  | 1         | 0.43%   |
| Samsung Electronics LCD Monitor SEC384A 1366x768 340x190mm 15.3-inch  | 1         | 0.43%   |
| Samsung Electronics LCD Monitor SEC3847 1440x900 370x230mm 17.2-inch  | 1         | 0.43%   |
| Samsung Electronics LCD Monitor SEC334A 1366x768 340x190mm 15.3-inch  | 1         | 0.43%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 107       | 47.56%  |
| 1920x1080 (FHD)    | 56        | 24.89%  |
| 1280x800 (WXGA)    | 26        | 11.56%  |
| 1600x900 (HD+)     | 11        | 4.89%   |
| 1440x900 (WXGA+)   | 6         | 2.67%   |
| 3840x2160 (4K)     | 4         | 1.78%   |
| 1024x768 (XGA)     | 3         | 1.33%   |
| 1024x600           | 3         | 1.33%   |
| 2560x1440 (QHD)    | 2         | 0.89%   |
| 1920x540           | 2         | 0.89%   |
| 3200x1800 (QHD+)   | 1         | 0.44%   |
| 2560x1080          | 1         | 0.44%   |
| 1920x1200 (WUXGA)  | 1         | 0.44%   |
| 1680x1050 (WSXGA+) | 1         | 0.44%   |
| 1280x1024 (SXGA)   | 1         | 0.44%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 89        | 38.53%  |
| 13      | 64        | 27.71%  |
| 12      | 17        | 7.36%   |
| 14      | 13        | 5.63%   |
| 17      | 12        | 5.19%   |
| 11      | 8         | 3.46%   |
| 27      | 4         | 1.73%   |
| 10      | 4         | 1.73%   |
| 24      | 3         | 1.3%    |
| 23      | 3         | 1.3%    |
| 40      | 2         | 0.87%   |
| 18      | 2         | 0.87%   |
| Unknown | 2         | 0.87%   |
| 64      | 1         | 0.43%   |
| 54      | 1         | 0.43%   |
| 42      | 1         | 0.43%   |
| 34      | 1         | 0.43%   |
| 21      | 1         | 0.43%   |
| 20      | 1         | 0.43%   |
| 19      | 1         | 0.43%   |
| 16      | 1         | 0.43%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 134       | 58.01%  |
| 201-300     | 61        | 26.41%  |
| 351-400     | 14        | 6.06%   |
| 501-600     | 9         | 3.9%    |
| 401-500     | 4         | 1.73%   |
| 801-900     | 2         | 0.87%   |
| 1001-1500   | 2         | 0.87%   |
| Unknown     | 2         | 0.87%   |
| 701-800     | 1         | 0.43%   |
| 601-700     | 1         | 0.43%   |
| 901-1000    | 1         | 0.43%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 172       | 78.9%   |
| 16/10   | 33        | 15.14%  |
| 3/2     | 5         | 2.29%   |
| 4/3     | 4         | 1.83%   |
| Unknown | 2         | 0.92%   |
| 5/4     | 1         | 0.46%   |
| 21/9    | 1         | 0.46%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 68        | 29.44%  |
| 91-100         | 68        | 29.44%  |
| 101-110        | 23        | 9.96%   |
| 61-70          | 18        | 7.79%   |
| 121-130        | 9         | 3.9%    |
| 71-80          | 7         | 3.03%   |
| 51-60          | 7         | 3.03%   |
| 201-250        | 6         | 2.6%    |
| 41-50          | 4         | 1.73%   |
| 301-350        | 4         | 1.73%   |
| 131-140        | 3         | 1.3%    |
| 501-1000       | 3         | 1.3%    |
| More than 1000 | 2         | 0.87%   |
| 151-200        | 2         | 0.87%   |
| 141-150        | 2         | 0.87%   |
| Unknown        | 2         | 0.87%   |
| 351-500        | 1         | 0.43%   |
| 251-300        | 1         | 0.43%   |
| 111-120        | 1         | 0.43%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 104       | 45.61%  |
| 121-160       | 80        | 35.09%  |
| 51-100        | 35        | 15.35%  |
| 161-240       | 4         | 1.75%   |
| More than 240 | 2         | 0.88%   |
| Unknown       | 2         | 0.88%   |
| 1-50          | 1         | 0.44%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 202       | 88.6%   |
| 2     | 20        | 8.77%   |
| 0     | 6         | 2.63%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 114       | 30%     |
| Realtek Semiconductor                  | 107       | 28.16%  |
| Qualcomm Atheros                       | 60        | 15.79%  |
| Broadcom                               | 43        | 11.32%  |
| Marvell Technology Group               | 12        | 3.16%   |
| Nvidia                                 | 7         | 1.84%   |
| Ralink                                 | 4         | 1.05%   |
| Dell                                   | 4         | 1.05%   |
| Xiaomi                                 | 3         | 0.79%   |
| JMicron Technology                     | 3         | 0.79%   |
| TP-Link                                | 2         | 0.53%   |
| Sierra Wireless                        | 2         | 0.53%   |
| Ralink Technology                      | 2         | 0.53%   |
| NetGear                                | 2         | 0.53%   |
| Ericsson Business Mobile Networks      | 2         | 0.53%   |
| Edimax Technology                      | 2         | 0.53%   |
| D-Link System                          | 2         | 0.53%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.26%   |
| Silicon Integrated Systems [SiS]       | 1         | 0.26%   |
| Samsung Electronics                    | 1         | 0.26%   |
| OPPO Electronics                       | 1         | 0.26%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.26%   |
| Mercucys                               | 1         | 0.26%   |
| Huawei Technologies                    | 1         | 0.26%   |
| Hewlett-Packard                        | 1         | 0.26%   |
| Google                                 | 1         | 0.26%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 77        | 16.21%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 24        | 5.05%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 20        | 4.21%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 15        | 3.16%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 14        | 2.95%   |
| Intel Wireless 8260                                                    | 13        | 2.74%   |
| Intel Wireless 7260                                                    | 11        | 2.32%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 9         | 1.89%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 9         | 1.89%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 9         | 1.89%   |
| Nvidia MCP79 Ethernet                                                  | 7         | 1.47%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection          | 7         | 1.47%   |
| Intel Centrino Advanced-N 6200                                         | 7         | 1.47%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 6         | 1.26%   |
| Intel Wireless 8265 / 8275                                             | 6         | 1.26%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                  | 6         | 1.26%   |
| Intel Ethernet Connection I219-LM                                      | 6         | 1.26%   |
| Intel 82577LM Gigabit Network Connection                               | 6         | 1.26%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                 | 6         | 1.26%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 6         | 1.26%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 5         | 1.05%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 5         | 1.05%   |
| Intel Wireless 7265                                                    | 5         | 1.05%   |
| Intel WiFi Link 5100                                                   | 5         | 1.05%   |
| Intel Wi-Fi 6 AX200                                                    | 5         | 1.05%   |
| Intel 82566MM Gigabit Network Connection                               | 5         | 1.05%   |
| Broadcom BCM4321 802.11a/b/g/n                                         | 5         | 1.05%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 4         | 0.84%   |
| Realtek RTL8723DE Wireless Network Adapter                             | 4         | 0.84%   |
| Realtek Realtek Bluetooth 4.2 Adapter                                  | 4         | 0.84%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                              | 4         | 0.84%   |
| Intel Ethernet Connection I218-LM                                      | 4         | 0.84%   |
| Intel Ethernet Connection I217-LM                                      | 4         | 0.84%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                        | 4         | 0.84%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 4         | 0.84%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                           | 4         | 0.84%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 4         | 0.84%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter               | 3         | 0.63%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                | 3         | 0.63%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                             | 3         | 0.63%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 112       | 45.53%  |
| Qualcomm Atheros      | 57        | 23.17%  |
| Realtek Semiconductor | 33        | 13.41%  |
| Broadcom              | 28        | 11.38%  |
| Ralink                | 4         | 1.63%   |
| TP-Link               | 2         | 0.81%   |
| Ralink Technology     | 2         | 0.81%   |
| NetGear               | 2         | 0.81%   |
| Edimax Technology     | 2         | 0.81%   |
| Sierra Wireless       | 1         | 0.41%   |
| Mercucys              | 1         | 0.41%   |
| Dell                  | 1         | 0.41%   |
| D-Link System         | 1         | 0.41%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 20        | 7.94%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 14        | 5.56%   |
| Intel Wireless 8260                                                     | 13        | 5.16%   |
| Intel Wireless 7260                                                     | 11        | 4.37%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 9         | 3.57%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 9         | 3.57%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 9         | 3.57%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 7         | 2.78%   |
| Intel Centrino Advanced-N 6200                                          | 7         | 2.78%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 6         | 2.38%   |
| Intel Wireless 8265 / 8275                                              | 6         | 2.38%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 6         | 2.38%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 6         | 2.38%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 6         | 2.38%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 5         | 1.98%   |
| Intel Wireless 7265                                                     | 5         | 1.98%   |
| Intel WiFi Link 5100                                                    | 5         | 1.98%   |
| Intel Wi-Fi 6 AX200                                                     | 5         | 1.98%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 5         | 1.98%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 1.59%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 4         | 1.59%   |
| Realtek Realtek Bluetooth 4.2 Adapter                                   | 4         | 1.59%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 4         | 1.59%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 4         | 1.59%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 4         | 1.59%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 4         | 1.59%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 4         | 1.59%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 3         | 1.19%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 3         | 1.19%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3         | 1.19%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 3         | 1.19%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 1.19%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 1.19%   |
| Intel Centrino Advanced-N 6235                                          | 3         | 1.19%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 3         | 1.19%   |
| Broadcom BCM43142 802.11b/g/n                                           | 3         | 1.19%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.79%   |
| Realtek 802.11n WLAN Adapter                                            | 2         | 0.79%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 2         | 0.79%   |
| Intel Ultimate N WiFi Link 5300                                         | 2         | 0.79%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 101       | 47.2%   |
| Intel                                  | 55        | 25.7%   |
| Broadcom                               | 16        | 7.48%   |
| Marvell Technology Group               | 12        | 5.61%   |
| Qualcomm Atheros                       | 11        | 5.14%   |
| Nvidia                                 | 7         | 3.27%   |
| Xiaomi                                 | 3         | 1.4%    |
| JMicron Technology                     | 3         | 1.4%    |
| Sony Ericsson Mobile Communications AB | 1         | 0.47%   |
| Silicon Integrated Systems [SiS]       | 1         | 0.47%   |
| Samsung Electronics                    | 1         | 0.47%   |
| OPPO Electronics                       | 1         | 0.47%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.47%   |
| Google                                 | 1         | 0.47%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 77        | 35.98%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 24        | 11.21%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 15        | 7.01%   |
| Nvidia MCP79 Ethernet                                                  | 7         | 3.27%   |
| Intel Ethernet Connection I219-LM                                      | 6         | 2.8%    |
| Intel 82577LM Gigabit Network Connection                               | 6         | 2.8%    |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 5         | 2.34%   |
| Intel 82566MM Gigabit Network Connection                               | 5         | 2.34%   |
| Intel Ethernet Connection I218-LM                                      | 4         | 1.87%   |
| Intel Ethernet Connection I217-LM                                      | 4         | 1.87%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 3         | 1.4%    |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 3         | 1.4%    |
| Intel Ethernet Connection (2) I219-LM                                  | 3         | 1.4%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 3         | 1.4%    |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 2         | 0.93%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 2         | 0.93%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 2         | 0.93%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller                | 2         | 0.93%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 2         | 0.93%   |
| Intel Ethernet Connection (4) I219-LM                                  | 2         | 0.93%   |
| Intel 82567LM Gigabit Network Connection                               | 2         | 0.93%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express               | 2         | 0.93%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                 | 2         | 0.93%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                        | 2         | 0.93%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 2         | 0.93%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 1         | 0.47%   |
| Sony Ericsson Mobile AB SOV41 RNDIS Control RNDIS Ethernet Data        | 1         | 0.47%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter          | 1         | 0.47%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 1         | 0.47%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1         | 0.47%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                             | 1         | 0.47%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 1         | 0.47%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 1         | 0.47%   |
| OPPO KALAMA-MTP_CID:0437_SN:B2767D06 RNDIS Control RNDIS Ethernet Data | 1         | 0.47%   |
| OnePlus (Shenzhen) Android Remote NDIS Device                          | 1         | 0.47%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                | 1         | 0.47%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller                  | 1         | 0.47%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                   | 1         | 0.47%   |
| Intel Ethernet Connection I219-V                                       | 1         | 0.47%   |
| Intel Ethernet Connection I218-V                                       | 1         | 0.47%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 226       | 51.02%  |
| Ethernet | 208       | 46.95%  |
| Unknown  | 6         | 1.35%   |
| Modem    | 3         | 0.68%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 143       | 50.53%  |
| Ethernet | 136       | 48.06%  |
| Unknown  | 3         | 1.06%   |
| Modem    | 1         | 0.35%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 204       | 89.87%  |
| 1     | 22        | 9.69%   |
| 0     | 1         | 0.44%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 217       | 95.18%  |
| Yes  | 11        | 4.82%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 55        | 35.71%  |
| Broadcom                        | 19        | 12.34%  |
| Qualcomm Atheros Communications | 17        | 11.04%  |
| Realtek Semiconductor           | 14        | 9.09%   |
| Apple                           | 13        | 8.44%   |
| Foxconn / Hon Hai               | 8         | 5.19%   |
| Lite-On Technology              | 7         | 4.55%   |
| Hewlett-Packard                 | 5         | 3.25%   |
| Cambridge Silicon Radio         | 5         | 3.25%   |
| Ralink                          | 4         | 2.6%    |
| Dell                            | 4         | 2.6%    |
| IMC Networks                    | 3         | 1.95%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 32        | 20.51%  |
| Broadcom BCM2045B (BDC-2.1)                                 | 8         | 5.13%   |
| Qualcomm Atheros QCA9377 Bluetooth 4.1                      | 7         | 4.49%   |
| Intel AX201 Bluetooth                                       | 6         | 3.85%   |
| Apple Bluetooth Host Controller                             | 6         | 3.85%   |
| Intel AX200 Bluetooth                                       | 5         | 3.21%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 5         | 3.21%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 5         | 3.21%   |
| Apple Built-in iSight (no firmware loaded)                  | 5         | 3.21%   |
| Ralink RT3290 Bluetooth                                     | 4         | 2.56%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 4         | 2.56%   |
| Lite-On Atheros AR3012 Bluetooth                            | 4         | 2.56%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 4         | 2.56%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 4         | 2.56%   |
| Realtek RTL8821A Bluetooth                                  | 3         | 1.92%   |
| Realtek Bluetooth 4.0 Adapter                               | 3         | 1.92%   |
| Intel Wireless-AC 3168 Bluetooth                            | 3         | 1.92%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 3         | 1.92%   |
| Foxconn / Hon Hai Qualcomm Atheros Bluetooth 4.0            | 3         | 1.92%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 3         | 1.92%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 3         | 1.92%   |
| Realtek RTL8723B Bluetooth                                  | 2         | 1.28%   |
| Realtek  Bluetooth 4.2 Adapter                              | 2         | 1.28%   |
| Realtek Bluetooth Adapter                                   | 2         | 1.28%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 2         | 1.28%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 2         | 1.28%   |
| Realtek Wireless Bluetooth Adapter                          | 1         | 0.64%   |
| Realtek Bluetooth 4.2 Adapter                               | 1         | 0.64%   |
| Realtek Bluetooth 4.0 + High Speed Chip                     | 1         | 0.64%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 1         | 0.64%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1         | 0.64%   |
| Qualcomm Atheros AR3012 Bluetooth                           | 1         | 0.64%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)             | 1         | 0.64%   |
| Lite-On Realtek Bluetooth Adapter                           | 1         | 0.64%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 1         | 0.64%   |
| Lite-On Qualcomm Atheros Bluetooth                          | 1         | 0.64%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 1         | 0.64%   |
| IMC Networks Realtek Bluetooth Adapter                      | 1         | 0.64%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS            | 1         | 0.64%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 1         | 0.64%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 188       | 74.02%  |
| AMD                              | 38        | 14.96%  |
| Nvidia                           | 22        | 8.66%   |
| Texas Instruments                | 2         | 0.79%   |
| GN Netcom                        | 2         | 0.79%   |
| Silicon Integrated Systems [SiS] | 1         | 0.39%   |
| Creative Technology              | 1         | 0.39%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 27        | 8.74%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 26        | 8.41%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 17        | 5.5%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 17        | 5.5%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 16        | 5.18%   |
| Intel 8 Series HD Audio Controller                                                                | 16        | 5.18%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 15        | 4.85%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 14        | 4.53%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 13        | 4.21%   |
| AMD FCH Azalia Controller                                                                         | 12        | 3.88%   |
| Nvidia MCP79 High Definition Audio                                                                | 7         | 2.27%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 7         | 2.27%   |
| AMD Kabini HDMI/DP Audio                                                                          | 7         | 2.27%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 6         | 1.94%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 1.94%   |
| Intel Broadwell-U Audio Controller                                                                | 6         | 1.94%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 6         | 1.94%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 6         | 1.94%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 6         | 1.94%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 5         | 1.62%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 5         | 1.62%   |
| Intel Comet Lake PCH cAVS                                                                         | 5         | 1.62%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 5         | 1.62%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 1.62%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 5         | 1.62%   |
| AMD High Definition Audio Controller                                                              | 5         | 1.62%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 5         | 1.62%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 4         | 1.29%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 3         | 0.97%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 0.97%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3         | 0.97%   |
| AMD Wrestler HDMI Audio                                                                           | 3         | 0.97%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 0.65%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 0.65%   |
| Intel CM238 HD Audio Controller                                                                   | 2         | 0.65%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 1         | 0.32%   |
| Texas Instruments PCM2900 Audio Codec                                                             | 1         | 0.32%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 0.32%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.32%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 1         | 0.32%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 67        | 25.19%  |
| SK hynix                     | 45        | 16.92%  |
| Kingston                     | 34        | 12.78%  |
| Micron Technology            | 25        | 9.4%    |
| Unknown                      | 21        | 7.89%   |
| Ramaxel Technology           | 11        | 4.14%   |
| Nanya Technology             | 8         | 3.01%   |
| Crucial                      | 8         | 3.01%   |
| Elpida                       | 7         | 2.63%   |
| Unknown                      | 7         | 2.63%   |
| A-DATA Technology            | 6         | 2.26%   |
| Smart                        | 5         | 1.88%   |
| Transcend                    | 2         | 0.75%   |
| Silicon Power                | 2         | 0.75%   |
| ASint Technology             | 2         | 0.75%   |
| Apacer                       | 2         | 0.75%   |
| 48spaces                     | 2         | 0.75%   |
| Unknown (ABCD)               | 1         | 0.38%   |
| Unknown (8AFD)               | 1         | 0.38%   |
| Unknown (0x3D7F000000000000) | 1         | 0.38%   |
| Unknown (0x0809)             | 1         | 0.38%   |
| Smart Brazil                 | 1         | 0.38%   |
| Sesame                       | 1         | 0.38%   |
| PNY                          | 1         | 0.38%   |
| Kingmax                      | 1         | 0.38%   |
| High Bridge                  | 1         | 0.38%   |
| GOODRAM                      | 1         | 0.38%   |
| Corsair                      | 1         | 0.38%   |
| Avant                        | 1         | 0.38%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                 | 9         | 3.16%   |
| Unknown                                                    | 7         | 2.46%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s     | 6         | 2.11%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s      | 5         | 1.75%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s      | 5         | 1.75%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                 | 4         | 1.4%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s     | 4         | 1.4%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s      | 4         | 1.4%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s      | 4         | 1.4%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s      | 4         | 1.4%    |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s      | 3         | 1.05%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s     | 3         | 1.05%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s     | 3         | 1.05%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 1333MT/s      | 3         | 1.05%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s      | 3         | 1.05%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s      | 3         | 1.05%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s      | 3         | 1.05%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s      | 3         | 1.05%   |
| Ramaxel RAM RMT3170EB68F9W1600 4GB SODIMM DDR3 1600MT/s    | 3         | 1.05%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s      | 3         | 1.05%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s    | 3         | 1.05%   |
| Unknown RAM Module 4GB SODIMM DDR3                         | 2         | 0.7%    |
| Unknown RAM Module 2GB SODIMM DDR2                         | 2         | 0.7%    |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s      | 2         | 0.7%    |
| SK hynix RAM HMT451S6MFR8A-PB 4GB SODIMM DDR3 800MT/s      | 2         | 0.7%    |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2133MT/s     | 2         | 0.7%    |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s     | 2         | 0.7%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s      | 2         | 0.7%    |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s      | 2         | 0.7%    |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s     | 2         | 0.7%    |
| Ramaxel RAM RMT3160MP68FAF1600 8GB SODIMM DDR3 1600MT/s    | 2         | 0.7%    |
| Ramaxel RAM RMSA3300ME78HBF-2666 16GB SODIMM DDR4 2667MT/s | 2         | 0.7%    |
| Nanya RAM Module 1GB SODIMM DDR2 667MT/s                   | 2         | 0.7%    |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s       | 2         | 0.7%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s       | 2         | 0.7%    |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s     | 2         | 0.7%    |
| Micron RAM 16JSF25664HZ-1G1F1 2GB SODIMM DDR3 1067MT/s     | 2         | 0.7%    |
| Kingston RAM Module 2GB SODIMM DDR2 667MT/s                | 2         | 0.7%    |
| Kingston RAM 99U5469-045.A00LF 4GB SODIMM DDR3 1600MT/s    | 2         | 0.7%    |
| Kingston RAM 99U5295-013.A00LF 2GB SODIMM DDR 667MT/s      | 2         | 0.7%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 123       | 54.67%  |
| DDR4    | 58        | 25.78%  |
| DDR2    | 31        | 13.78%  |
| Unknown | 4         | 1.78%   |
| LPDDR3  | 3         | 1.33%   |
| SDRAM   | 2         | 0.89%   |
| LPDDR4  | 2         | 0.89%   |
| DRAM    | 1         | 0.44%   |
| DDR     | 1         | 0.44%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 214       | 96.4%   |
| Row Of Chips | 4         | 1.8%    |
| Chip         | 3         | 1.35%   |
| DIMM         | 1         | 0.45%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 90        | 35.57%  |
| 2048  | 67        | 26.48%  |
| 8192  | 64        | 25.3%   |
| 16384 | 19        | 7.51%   |
| 1024  | 11        | 4.35%   |
| 32768 | 2         | 0.79%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 77        | 30.8%   |
| 2667    | 28        | 11.2%   |
| 667     | 24        | 9.6%    |
| 1333    | 20        | 8%      |
| 1334    | 19        | 7.6%    |
| 1067    | 14        | 5.6%    |
| 3200    | 13        | 5.2%    |
| 2400    | 13        | 5.2%    |
| 2133    | 12        | 4.8%    |
| 800     | 10        | 4%      |
| 1867    | 7         | 2.8%    |
| Unknown | 6         | 2.4%    |
| 975     | 3         | 1.2%    |
| 4267    | 1         | 0.4%    |
| 2048    | 1         | 0.4%    |
| 1066    | 1         | 0.4%    |
| 533     | 1         | 0.4%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

Zero info for selected period =(

Printer Model
-------------

Printer device models

Zero info for selected period =(

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
| Chicony Electronics                    | 50        | 30.49%  |
| Realtek Semiconductor                  | 15        | 9.15%   |
| IMC Networks                           | 14        | 8.54%   |
| Bison Electronics                      | 13        | 7.93%   |
| Microdia                               | 12        | 7.32%   |
| Quanta                                 | 9         | 5.49%   |
| Suyin                                  | 8         | 4.88%   |
| Sunplus Innovation Technology          | 7         | 4.27%   |
| Lite-On Technology                     | 7         | 4.27%   |
| Syntek                                 | 6         | 3.66%   |
| Alcor Micro                            | 4         | 2.44%   |
| Z-Star Microelectronics                | 3         | 1.83%   |
| Lenovo                                 | 3         | 1.83%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 1.83%   |
| ALi                                    | 2         | 1.22%   |
| USB Camera                             | 1         | 0.61%   |
| Silicon Motion                         | 1         | 0.61%   |
| Ricoh                                  | 1         | 0.61%   |
| Primax Electronics                     | 1         | 0.61%   |
| Luxvisions Innotech Limited            | 1         | 0.61%   |
| Importek                               | 1         | 0.61%   |
| DigiTech                               | 1         | 0.61%   |
| Apple                                  | 1         | 0.61%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Chicony Integrated Camera                 | 7         | 4.24%   |
| Chicony HD Webcam                         | 7         | 4.24%   |
| Chicony Lenovo Integrated Camera (0.3MP)  | 5         | 3.03%   |
| Syntek Lenovo EasyCamera                  | 4         | 2.42%   |
| Realtek USB Camera                        | 4         | 2.42%   |
| Realtek Integrated_Webcam_HD              | 4         | 2.42%   |
| Lite-On Integrated Camera                 | 4         | 2.42%   |
| Chicony EasyCamera                        | 4         | 2.42%   |
| Bison Lenovo EasyCamera                   | 4         | 2.42%   |
| Realtek USB 2.0 PC Camera                 | 3         | 1.82%   |
| Quanta HP TrueVision HD Camera            | 3         | 1.82%   |
| Microdia Integrated_Webcam_HD             | 3         | 1.82%   |
| Microdia Integrated Webcam                | 3         | 1.82%   |
| IMC Networks Realtek PC Camera            | 3         | 1.82%   |
| IMC Networks Integrated Camera            | 3         | 1.82%   |
| IMC Networks EasyCamera                   | 3         | 1.82%   |
| Chicony Realtek DMFT RGB                  | 3         | 1.82%   |
| Chicony HD WebCam (Acer)                  | 3         | 1.82%   |
| Bison Integrated Camera                   | 3         | 1.82%   |
| Z-Star WebCam SC-03FFL11739P              | 2         | 1.21%   |
| Syntek EasyCamera                         | 2         | 1.21%   |
| Suyin Integrated_Webcam_HD                | 2         | 1.21%   |
| Suyin HD Video WebCam                     | 2         | 1.21%   |
| Suyin Acer/HP Integrated Webcam [CN0314]  | 2         | 1.21%   |
| Sunplus HD WebCam                         | 2         | 1.21%   |
| Quanta Realtek DMFT RGB                   | 2         | 1.21%   |
| Quanta HP Webcam                          | 2         | 1.21%   |
| Microdia Sonix USB 2.0 Camera             | 2         | 1.21%   |
| Microdia Dell Laptop Integrated Webcam HD | 2         | 1.21%   |
| Lite-On HP HD Camera                      | 2         | 1.21%   |
| Lenovo Integrated Webcam [R5U877]         | 2         | 1.21%   |
| IMC Networks Integrated Webcam            | 2         | 1.21%   |
| Chicony VGA Webcam                        | 2         | 1.21%   |
| Chicony USB 2.0 Camera                    | 2         | 1.21%   |
| Chicony HP HD Webcam [Fixed]              | 2         | 1.21%   |
| Bison SunplusIT INC. Integrated Camera    | 2         | 1.21%   |
| ALi Gateway Webcam                        | 2         | 1.21%   |
| Z-Star Webcam                             | 1         | 0.61%   |
| USB Camera USB Camera                     | 1         | 0.61%   |
| Suyin Laptop_Integrated_Webcam_FHD        | 1         | 0.61%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 20        | 39.22%  |
| Upek                       | 11        | 21.57%  |
| AuthenTec                  | 8         | 15.69%  |
| STMicroelectronics         | 4         | 7.84%   |
| Elan Microelectronics      | 3         | 5.88%   |
| Shenzhen Goodix Technology | 2         | 3.92%   |
| LighTuning Technology      | 2         | 3.92%   |
| Synaptics                  | 1         | 1.96%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 9         | 17.65%  |
| STMicroelectronics Fingerprint Reader                  | 4         | 7.84%   |
| Validity Sensors VFS5011 Fingerprint Reader            | 3         | 5.88%   |
| Validity Sensors VFS491                                | 3         | 5.88%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 3         | 5.88%   |
| Validity Sensors Synaptics WBDI                        | 3         | 5.88%   |
| Elan Fingerprint Sensor                                | 3         | 5.88%   |
| AuthenTec AES1600                                      | 3         | 5.88%   |
| Validity Sensors VFS495 Fingerprint Reader             | 2         | 3.92%   |
| Validity Sensors VFS471 Fingerprint Reader             | 2         | 3.92%   |
| Validity Sensors Fingerprint scanner                   | 2         | 3.92%   |
| Upek TCS5B Fingerprint sensor                          | 2         | 3.92%   |
| Shenzhen Goodix Fingerprint Reader                     | 2         | 3.92%   |
| AuthenTec AES2501 Fingerprint Sensor                   | 2         | 3.92%   |
| Validity Sensors VFS101 Fingerprint Reader             | 1         | 1.96%   |
| Validity Sensors Swipe Fingerprint Sensor              | 1         | 1.96%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 1         | 1.96%   |
| LighTuning ES603 Swipe Fingerprint Sensor              | 1         | 1.96%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 1.96%   |
| AuthenTec AES2810                                      | 1         | 1.96%   |
| AuthenTec AES1660 Fingerprint Sensor                   | 1         | 1.96%   |
| AuthenTec AES1660                                      | 1         | 1.96%   |

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
| 1     | 77        | 33.77%  |
| 2     | 63        | 27.63%  |
| 0     | 42        | 18.42%  |
| 3     | 36        | 15.79%  |
| 4     | 9         | 3.95%   |
| 5     | 1         | 0.44%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 139       | 41.74%  |
| Net/wireless             | 61        | 18.32%  |
| Fingerprint reader       | 49        | 14.71%  |
| Bluetooth                | 40        | 12.01%  |
| Card reader              | 36        | 10.81%  |
| Storage                  | 4         | 1.2%    |
| Network                  | 3         | 0.9%    |
| Sound                    | 1         | 0.3%    |

