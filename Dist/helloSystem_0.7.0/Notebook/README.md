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

Total: 252

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
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
| Acidanther... | MacBookPro15,1              | [57c3a4005a](https://bsd-hardware.info/?probe=57c3a4005a) | Dec 01, 2022 |
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
| amd64 | 220       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 218       | 99.09%  |
| GNOME        | 2         | 0.91%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 220       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| SLiM | 220       | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 207       | 93.67%  |
| es_ES | 5         | 2.26%   |
| fr_FR | 3         | 1.36%   |
| C     | 3         | 1.36%   |
| uk_UA | 1         | 0.45%   |
| it_IT | 1         | 0.45%   |
| de_DE | 1         | 0.45%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 216       | 98.18%  |
| BIOS | 4         | 1.82%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Zfs    | 113       | 50.67%  |
| Cd9660 | 110       | 49.33%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 219       | 99.55%  |
| MBR  | 1         | 0.45%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 69        | 31.36%  |
| Hewlett-Packard     | 37        | 16.82%  |
| Dell                | 26        | 11.82%  |
| Acer                | 24        | 10.91%  |
| Apple               | 14        | 6.36%   |
| ASUSTek Computer    | 12        | 5.45%   |
| Toshiba             | 6         | 2.73%   |
| Samsung Electronics | 5         | 2.27%   |
| TUXEDO              | 3         | 1.36%   |
| Sony                | 3         | 1.36%   |
| Razer               | 2         | 0.91%   |
| MSI                 | 2         | 0.91%   |
| HASEE Computer      | 2         | 0.91%   |
| Fujitsu             | 2         | 0.91%   |
| TWINHEAD            | 1         | 0.45%   |
| Panasonic           | 1         | 0.45%   |
| Packard Bell        | 1         | 0.45%   |
| Notebook            | 1         | 0.45%   |
| LG Electronics      | 1         | 0.45%   |
| Itautec             | 1         | 0.45%   |
| GPD                 | 1         | 0.45%   |
| Gateway             | 1         | 0.45%   |
| eMachines           | 1         | 0.45%   |
| DNS                 | 1         | 0.45%   |
| Alienware           | 1         | 0.45%   |
| Acidanthera         | 1         | 0.45%   |
| Unknown             | 1         | 0.45%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                               | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Apple MacBook4,1                                   | 4         | 1.82%   |
| TUXEDO Aura 15 Gen1                                | 2         | 0.91%   |
| Lenovo IdeaPad 110-14AST 80TQ                      | 2         | 0.91%   |
| HP ProBook 4540s                                   | 2         | 0.91%   |
| HP Pavilion g6                                     | 2         | 0.91%   |
| HP Pavilion dv6                                    | 2         | 0.91%   |
| HP 2000                                            | 2         | 0.91%   |
| Dell Precision 7710                                | 2         | 0.91%   |
| Dell Latitude E5470                                | 2         | 0.91%   |
| Dell Latitude D630                                 | 2         | 0.91%   |
| Apple MacBook6,1                                   | 2         | 0.91%   |
| Apple MacBook5,1                                   | 2         | 0.91%   |
| Acer V5-131                                        | 2         | 0.91%   |
| Acer Aspire ES1-533                                | 2         | 0.91%   |
| Acer Aspire E1-522                                 | 2         | 0.91%   |
| Acer Aspire 5930                                   | 2         | 0.91%   |
| TWINHEAD U12CT                                     | 1         | 0.45%   |
| TUXEDO InfinityBook13V3                            | 1         | 0.45%   |
| Toshiba Satellite S55t-B                           | 1         | 0.45%   |
| Toshiba Satellite P300                             | 1         | 0.45%   |
| Toshiba Satellite L550                             | 1         | 0.45%   |
| Toshiba Satellite C640                             | 1         | 0.45%   |
| Toshiba Satellite C50-B                            | 1         | 0.45%   |
| Toshiba PORTEGE R700                               | 1         | 0.45%   |
| Sony VPCSB11FX                                     | 1         | 0.45%   |
| Sony VGN-NW25GF_S                                  | 1         | 0.45%   |
| Sony SVZ1311C5E                                    | 1         | 0.45%   |
| Samsung Q430/Q530                                  | 1         | 0.45%   |
| Samsung N150P/N210P/N220P                          | 1         | 0.45%   |
| Samsung N100                                       | 1         | 0.45%   |
| Samsung 305E4A/305E5A/305E7A                       | 1         | 0.45%   |
| Samsung 300E4C/300E5C/300E7C                       | 1         | 0.45%   |
| Razer Blade Stealth                                | 1         | 0.45%   |
| Razer Blade 15 Base Model (Early 2020) - RZ09-0328 | 1         | 0.45%   |
| Panasonic CF-B11JWCYS                              | 1         | 0.45%   |
| Packard Bell EasyNote TE69HW                       | 1         | 0.45%   |
| Notebook N15_17RD                                  | 1         | 0.45%   |
| MSI GF65 Thin 10SER                                | 1         | 0.45%   |
| MSI GF63 Thin 10SC                                 | 1         | 0.45%   |
| LG E300-A.CP20T                                    | 1         | 0.45%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 46        | 20.91%  |
| Acer Aspire             | 19        | 8.64%   |
| HP Pavilion             | 13        | 5.91%   |
| Dell Latitude           | 12        | 5.45%   |
| Lenovo IdeaPad          | 10        | 4.55%   |
| Dell Inspiron           | 8         | 3.64%   |
| HP ProBook              | 7         | 3.18%   |
| Toshiba Satellite       | 5         | 2.27%   |
| HP Laptop               | 4         | 1.82%   |
| Apple MacBook4          | 4         | 1.82%   |
| HP EliteBook            | 3         | 1.36%   |
| Dell Precision          | 3         | 1.36%   |
| Apple MacBook5          | 3         | 1.36%   |
| TUXEDO Aura             | 2         | 0.91%   |
| Razer Blade             | 2         | 0.91%   |
| Lenovo Legion           | 2         | 0.91%   |
| HP Compaq               | 2         | 0.91%   |
| HP 2000                 | 2         | 0.91%   |
| Fujitsu LIFEBOOK        | 2         | 0.91%   |
| Apple MacBookPro5       | 2         | 0.91%   |
| Apple MacBook6          | 2         | 0.91%   |
| Acer V5-131             | 2         | 0.91%   |
| TWINHEAD U12CT          | 1         | 0.45%   |
| TUXEDO InfinityBook13V3 | 1         | 0.45%   |
| Toshiba PORTEGE         | 1         | 0.45%   |
| Sony VPCSB11FX          | 1         | 0.45%   |
| Sony VGN-NW25GF         | 1         | 0.45%   |
| Sony SVZ1311C5E         | 1         | 0.45%   |
| Samsung Q430            | 1         | 0.45%   |
| Samsung N150P           | 1         | 0.45%   |
| Samsung N100            | 1         | 0.45%   |
| Samsung 305E4A          | 1         | 0.45%   |
| Samsung 300E4C          | 1         | 0.45%   |
| Panasonic CF-B11JWCYS   | 1         | 0.45%   |
| Packard Bell EasyNote   | 1         | 0.45%   |
| Notebook N15            | 1         | 0.45%   |
| MSI GF65                | 1         | 0.45%   |
| MSI GF63                | 1         | 0.45%   |
| LG E300-A.CP20T         | 1         | 0.45%   |
| Lenovo Z50-70           | 1         | 0.45%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2016    | 21        | 9.55%   |
| 2012    | 18        | 8.18%   |
| 2021    | 17        | 7.73%   |
| 2018    | 17        | 7.73%   |
| 2015    | 17        | 7.73%   |
| 2013    | 17        | 7.73%   |
| 2011    | 17        | 7.73%   |
| 2010    | 16        | 7.27%   |
| 2017    | 13        | 5.91%   |
| 2014    | 13        | 5.91%   |
| 2008    | 13        | 5.91%   |
| 2020    | 12        | 5.45%   |
| 2009    | 12        | 5.45%   |
| 2007    | 7         | 3.18%   |
| 2019    | 4         | 1.82%   |
| 2022    | 3         | 1.36%   |
| 2006    | 2         | 0.91%   |
| Unknown | 1         | 0.45%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 220       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 220       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 85        | 38.64%  |
| 8.01-16.0   | 72        | 32.73%  |
| 16.01-24.0  | 37        | 16.82%  |
| 2.01-3.0    | 13        | 5.91%   |
| 32.01-64.0  | 6         | 2.73%   |
| 3.01-4.0    | 5         | 2.27%   |
| 24.01-32.0  | 1         | 0.45%   |
| 64.01-256.0 | 1         | 0.45%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 140       | 63.64%  |
| 0.51-1.0 | 59        | 26.82%  |
| 1.01-2.0 | 14        | 6.36%   |
| 2.01-3.0 | 7         | 3.18%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 169       | 76.13%  |
| 2      | 41        | 18.47%  |
| 0      | 9         | 4.05%   |
| 3      | 2         | 0.9%    |
| 4      | 1         | 0.45%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 119       | 54.09%  |
| Yes       | 101       | 45.91%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 201       | 91.36%  |
| No        | 19        | 8.64%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 219       | 99.55%  |
| No        | 1         | 0.45%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 150       | 67.87%  |
| No        | 71        | 32.13%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country             | Notebooks | Percent |
|---------------------|-----------|---------|
| USA                 | 31        | 14.09%  |
| Spain               | 16        | 7.27%   |
| Russia              | 15        | 6.82%   |
| Germany             | 12        | 5.45%   |
| Brazil              | 12        | 5.45%   |
| Italy               | 11        | 5%      |
| UK                  | 10        | 4.55%   |
| Netherlands         | 8         | 3.64%   |
| Indonesia           | 8         | 3.64%   |
| China               | 8         | 3.64%   |
| Romania             | 6         | 2.73%   |
| Mexico              | 6         | 2.73%   |
| France              | 6         | 2.73%   |
| Vietnam             | 4         | 1.82%   |
| Ukraine             | 4         | 1.82%   |
| Poland              | 4         | 1.82%   |
| India               | 4         | 1.82%   |
| Hungary             | 3         | 1.36%   |
| Colombia            | 3         | 1.36%   |
| Chile               | 3         | 1.36%   |
| Canada              | 3         | 1.36%   |
| Turkey              | 2         | 0.91%   |
| Sweden              | 2         | 0.91%   |
| Portugal            | 2         | 0.91%   |
| Peru                | 2         | 0.91%   |
| Norway              | 2         | 0.91%   |
| Greece              | 2         | 0.91%   |
| Egypt               | 2         | 0.91%   |
| Denmark             | 2         | 0.91%   |
| Czechia             | 2         | 0.91%   |
| Bulgaria            | 2         | 0.91%   |
| Trinidad and Tobago | 1         | 0.45%   |
| Tanzania            | 1         | 0.45%   |
| Taiwan              | 1         | 0.45%   |
| Switzerland         | 1         | 0.45%   |
| Singapore           | 1         | 0.45%   |
| New Zealand         | 1         | 0.45%   |
| Myanmar             | 1         | 0.45%   |
| Malaysia            | 1         | 0.45%   |
| Lithuania           | 1         | 0.45%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Moscow           | 4         | 1.79%   |
| Madrid           | 3         | 1.35%   |
| Hanoi            | 3         | 1.35%   |
| Amsterdam        | 3         | 1.35%   |
| Warsaw           | 2         | 0.9%    |
| Lima             | 2         | 0.9%    |
| Leatherhead      | 2         | 0.9%    |
| Jakarta          | 2         | 0.9%    |
| Dijon            | 2         | 0.9%    |
| Curitiba         | 2         | 0.9%    |
| Cluj-Napoca      | 2         | 0.9%    |
| Budapest         | 2         | 0.9%    |
| Bucharest        | 2         | 0.9%    |
| Alcobendas       | 2         | 0.9%    |
| Zhaoqing         | 1         | 0.45%   |
| Zaporizhzhya     | 1         | 0.45%   |
| Zapopan          | 1         | 0.45%   |
| Youngsville      | 1         | 0.45%   |
| Yichun           | 1         | 0.45%   |
| Yaphank          | 1         | 0.45%   |
| Yangon           | 1         | 0.45%   |
| Yambol           | 1         | 0.45%   |
| Wroclaw          | 1         | 0.45%   |
| Windsor          | 1         | 0.45%   |
| West Linn        | 1         | 0.45%   |
| Washington       | 1         | 0.45%   |
| Vilnius          | 1         | 0.45%   |
| Ventura          | 1         | 0.45%   |
| VÃ¤sterÃ¥s   | 1         | 0.45%   |
| Vaudreuil-Dorion | 1         | 0.45%   |
| Vandalia         | 1         | 0.45%   |
| Valencia         | 1         | 0.45%   |
| Urnieta          | 1         | 0.45%   |
| Ugarchin         | 1         | 0.45%   |
| Turley           | 1         | 0.45%   |
| Turin            | 1         | 0.45%   |
| Tudela de Duero  | 1         | 0.45%   |
| Tsarskoye Selo   | 1         | 0.45%   |
| Tromsø          | 1         | 0.45%   |
| Toronto          | 1         | 0.45%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 46        | 49     | 17.83%  |
| Samsung Electronics | 38        | 40     | 14.73%  |
| Seagate             | 29        | 34     | 11.24%  |
| Toshiba             | 20        | 20     | 7.75%   |
| Kingston            | 19        | 20     | 7.36%   |
| Crucial             | 15        | 15     | 5.81%   |
| SanDisk             | 11        | 12     | 4.26%   |
| Hitachi             | 11        | 11     | 4.26%   |
| Intel               | 9         | 10     | 3.49%   |
| HGST                | 6         | 6      | 2.33%   |
| Micron Technology   | 5         | 5      | 1.94%   |
| Fujitsu             | 5         | 5      | 1.94%   |
| A-DATA Technology   | 4         | 4      | 1.55%   |
| SPCC                | 3         | 4      | 1.16%   |
| KingSpec            | 3         | 3      | 1.16%   |
| Intenso             | 3         | 3      | 1.16%   |
| Zheino              | 2         | 2      | 0.78%   |
| SK hynix            | 2         | 2      | 0.78%   |
| Patriot             | 2         | 2      | 0.78%   |
| Corsair             | 2         | 2      | 0.78%   |
| V-GeN               | 1         | 1      | 0.39%   |
| Transcend           | 1         | 1      | 0.39%   |
| Team                | 1         | 1      | 0.39%   |
| SSSTC               | 1         | 1      | 0.39%   |
| Smartbuy            | 1         | 1      | 0.39%   |
| PNY                 | 1         | 1      | 0.39%   |
| Plextor             | 1         | 1      | 0.39%   |
| Phison              | 1         | 1      | 0.39%   |
| Netac               | 1         | 1      | 0.39%   |
| Mushkin             | 1         | 1      | 0.39%   |
| LITEON              | 1         | 1      | 0.39%   |
| Lexar               | 1         | 1      | 0.39%   |
| Leven               | 1         | 1      | 0.39%   |
| KIOXIA              | 1         | 1      | 0.39%   |
| Integral            | 1         | 1      | 0.39%   |
| INDMEM              | 1         | 1      | 0.39%   |
| Hikvision           | 1         | 1      | 0.39%   |
| Hewlett-Packard     | 1         | 1      | 0.39%   |
| BIWIN               | 1         | 1      | 0.39%   |
| Apple               | 1         | 1      | 0.39%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| WDC WDS120G2G0A-00JH30 120GB       | 5         | 1.9%    |
| Kingston SA400S37240G 240GB        | 5         | 1.9%    |
| HGST HTS545050A7E680 500GB         | 5         | 1.9%    |
| Toshiba MQ01ABF050 500GB           | 4         | 1.52%   |
| WDC WD5000LPVX-22V0TT0 500GB       | 3         | 1.14%   |
| Toshiba MQ01ABD100 1TB             | 3         | 1.14%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 3         | 1.14%   |
| Samsung SSD 860 EVO 250GB          | 3         | 1.14%   |
| Kingston SA400S37120G 120GB        | 3         | 1.14%   |
| Crucial CT500MX500SSD1 500GB       | 3         | 1.14%   |
| Crucial CT240BX500SSD1 240GB       | 3         | 1.14%   |
| WDC WDS240G2G0A-00JH30 240GB       | 2         | 0.76%   |
| WDC WD5000LPCX-60VHAT0 500GB       | 2         | 0.76%   |
| WDC WD10JPCX-24UE4T0 1TB           | 2         | 0.76%   |
| Toshiba MK3261GSYN 320GB           | 2         | 0.76%   |
| SK hynix HFS256G39TND-N210A 256GB  | 2         | 0.76%   |
| Seagate ST9320423AS 320GB          | 2         | 0.76%   |
| Seagate ST9320325AS 320GB          | 2         | 0.76%   |
| Seagate ST500LT012-9WS142 500GB    | 2         | 0.76%   |
| Seagate ST320LT020-9YG142 320GB    | 2         | 0.76%   |
| Seagate ST1000LM035-1RK172 1TB     | 2         | 0.76%   |
| Samsung SSD PM871 2.5 7mm 128GB    | 2         | 0.76%   |
| Samsung SSD 850 EVO 500GB          | 2         | 0.76%   |
| Samsung SSD 750 EVO 250GB          | 2         | 0.76%   |
| Samsung MZVLW256HEHP-000L7 256GB   | 2         | 0.76%   |
| Kingston SV300S37A120G 120GB       | 2         | 0.76%   |
| Hitachi HTS541680J9SA00 80GB       | 2         | 0.76%   |
| Crucial CT480BX500SSD1 480GB       | 2         | 0.76%   |
| Crucial CT250BX100SSD1 250GB       | 2         | 0.76%   |
| Zheino CHN-25SATAC3-120 120GB      | 1         | 0.38%   |
| Zheino CHN mSATAM1 256 256GB       | 1         | 0.38%   |
| WDC WDS500G2B0C-00PXH0 500GB       | 1         | 0.38%   |
| WDC WDS240G1G0A-00SS50 240GB       | 1         | 0.38%   |
| WDC WDBNCE5000PNC 500GB            | 1         | 0.38%   |
| WDC WD6400BPVT-60HXZT1 640GB       | 1         | 0.38%   |
| WDC WD6400BEVT-22A0RT0 640GB       | 1         | 0.38%   |
| WDC WD5000LPVX-80V0TT0 500GB       | 1         | 0.38%   |
| WDC WD5000LPLX-60ZNTT1 500GB       | 1         | 0.38%   |
| WDC WD5000LPCX-75VHAT0 500GB       | 1         | 0.38%   |
| WDC WD5000BPVT-22HXZT3 500GB       | 1         | 0.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 33        | 35     | 32.04%  |
| Seagate             | 29        | 34     | 28.16%  |
| Toshiba             | 18        | 18     | 17.48%  |
| Hitachi             | 11        | 11     | 10.68%  |
| HGST                | 6         | 6      | 5.83%   |
| Fujitsu             | 4         | 4      | 3.88%   |
| Samsung Electronics | 2         | 2      | 1.94%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 23        | 24     | 19.01%  |
| Kingston            | 16        | 16     | 13.22%  |
| Crucial             | 15        | 15     | 12.4%   |
| SanDisk             | 11        | 12     | 9.09%   |
| WDC                 | 9         | 9      | 7.44%   |
| Intel               | 6         | 6      | 4.96%   |
| SPCC                | 3         | 4      | 2.48%   |
| KingSpec            | 3         | 3      | 2.48%   |
| Intenso             | 3         | 3      | 2.48%   |
| A-DATA Technology   | 3         | 3      | 2.48%   |
| Zheino              | 2         | 2      | 1.65%   |
| SK hynix            | 2         | 2      | 1.65%   |
| Patriot             | 2         | 2      | 1.65%   |
| Corsair             | 2         | 2      | 1.65%   |
| V-GeN               | 1         | 1      | 0.83%   |
| Transcend           | 1         | 1      | 0.83%   |
| Toshiba             | 1         | 1      | 0.83%   |
| Team                | 1         | 1      | 0.83%   |
| Smartbuy            | 1         | 1      | 0.83%   |
| PNY                 | 1         | 1      | 0.83%   |
| Plextor             | 1         | 1      | 0.83%   |
| Phison              | 1         | 1      | 0.83%   |
| Netac               | 1         | 1      | 0.83%   |
| Mushkin             | 1         | 1      | 0.83%   |
| Micron Technology   | 1         | 1      | 0.83%   |
| LITEON              | 1         | 1      | 0.83%   |
| Lexar               | 1         | 1      | 0.83%   |
| Leven               | 1         | 1      | 0.83%   |
| Integral            | 1         | 1      | 0.83%   |
| INDMEM              | 1         | 1      | 0.83%   |
| Hewlett-Packard     | 1         | 1      | 0.83%   |
| Fujitsu             | 1         | 1      | 0.83%   |
| Apple               | 1         | 1      | 0.83%   |
| Apacer              | 1         | 1      | 0.83%   |
| ANACOMDA            | 1         | 1      | 0.83%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 109       | 124    | 45.42%  |
| HDD  | 96        | 110    | 40%     |
| NVMe | 35        | 38     | 14.58%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 193       | 234    | 84.65%  |
| NVMe | 35        | 38     | 15.35%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 159       | 186    | 78.33%  |
| 0.51-1.0   | 39        | 43     | 19.21%  |
| 1.01-2.0   | 4         | 4      | 1.97%   |
| 4.01-10.0  | 1         | 1      | 0.49%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 106       | 47.53%  |
| 101-250    | 55        | 24.66%  |
| 251-500    | 34        | 15.25%  |
| 501-1000   | 16        | 7.17%   |
| 21-50      | 6         | 2.69%   |
| 51-100     | 5         | 2.24%   |
| Unknown    | 1         | 0.45%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 216       | 98.18%  |
| 21-50   | 2         | 0.91%   |
| 101-250 | 1         | 0.45%   |
| Unknown | 1         | 0.45%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST320LT020-9YG142 320GB    | 2         | 2      | 3.7%    |
| Seagate ST1000LM024 HN-M101MBB 1TB | 2         | 2      | 3.7%    |
| WDC WD5000LPLX-60ZNTT1 500GB       | 1         | 1      | 1.85%   |
| WDC WD5000LPCX-75VHAT0 500GB       | 1         | 1      | 1.85%   |
| WDC WD5000LPCX-60VHAT0 500GB       | 1         | 1      | 1.85%   |
| WDC WD5000BPVT-22HXZT3 500GB       | 1         | 1      | 1.85%   |
| WDC WD3200BPVT-80ZEST0 320GB       | 1         | 1      | 1.85%   |
| WDC WD3200BEVT-60A23T0 320GB       | 1         | 1      | 1.85%   |
| WDC WD3200BEVT-22ZCT0 320GB        | 1         | 1      | 1.85%   |
| WDC WD1600BEVT-80A23T0 160GB       | 1         | 1      | 1.85%   |
| WDC WD1600BEKT-66F3T2 160GB        | 1         | 1      | 1.85%   |
| WDC WD10SPZX-24Z10T0 1TB           | 1         | 1      | 1.85%   |
| WDC WD10SPZX-21Z10T0 1TB           | 1         | 1      | 1.85%   |
| WDC WD10JPVX-22JC3T0 1TB           | 1         | 1      | 1.85%   |
| WDC WD10JMVW-11AJGS2 1TB           | 1         | 1      | 1.85%   |
| Toshiba THNSNX024GMNT 24GB         | 1         | 1      | 1.85%   |
| Toshiba MQ01ABF050 500GB           | 1         | 1      | 1.85%   |
| Toshiba MQ01ABD100 1TB             | 1         | 1      | 1.85%   |
| Toshiba MQ01ABD075 752GB           | 1         | 1      | 1.85%   |
| Toshiba MK8034GSX 80GB             | 1         | 1      | 1.85%   |
| Toshiba MK7559GSXF 752GB           | 1         | 1      | 1.85%   |
| Toshiba MK6034GSX 64GB             | 1         | 1      | 1.85%   |
| Toshiba MK3265GSXN 320GB           | 1         | 1      | 1.85%   |
| Toshiba MK3261GSYN 320GB           | 1         | 1      | 1.85%   |
| Toshiba MK1059GSM 1TB              | 1         | 1      | 1.85%   |
| Seagate ST9640320AS 640GB          | 1         | 1      | 1.85%   |
| Seagate ST9500325AS 500GB          | 1         | 1      | 1.85%   |
| Seagate ST9320423AS 320GB          | 1         | 1      | 1.85%   |
| Seagate ST9320325AS 320GB          | 1         | 1      | 1.85%   |
| Seagate ST9160412AS 160GB          | 1         | 1      | 1.85%   |
| Seagate ST9120821AS 118GB          | 1         | 1      | 1.85%   |
| Seagate ST500LT012-9WS142 500GB    | 1         | 1      | 1.85%   |
| Seagate ST320LT007-9ZV142 320GB    | 1         | 1      | 1.85%   |
| Seagate ST3160212AS 160GB          | 1         | 1      | 1.85%   |
| Seagate ST1000LM014-1EJ164 1TB     | 1         | 1      | 1.85%   |
| Samsung Electronics HS082HB 80GB   | 1         | 1      | 1.85%   |
| Samsung Electronics HM160HI 160GB  | 1         | 1      | 1.85%   |
| LITEON CV8-8E128-HP 128GB          | 1         | 1      | 1.85%   |
| Kingston SV300S37A120G 120GB       | 1         | 1      | 1.85%   |
| Kingston SUV500MS480G 480GB        | 1         | 1      | 1.85%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 14        | 14     | 25.93%  |
| WDC                 | 13        | 13     | 24.07%  |
| Toshiba             | 10        | 10     | 18.52%  |
| Hitachi             | 7         | 7      | 12.96%  |
| Samsung Electronics | 2         | 2      | 3.7%    |
| Kingston            | 2         | 2      | 3.7%    |
| HGST                | 2         | 2      | 3.7%    |
| LITEON              | 1         | 1      | 1.85%   |
| Fujitsu             | 1         | 1      | 1.85%   |
| Corsair             | 1         | 1      | 1.85%   |
| AGI                 | 1         | 1      | 1.85%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 14        | 14     | 29.17%  |
| WDC                 | 13        | 13     | 27.08%  |
| Toshiba             | 9         | 9      | 18.75%  |
| Hitachi             | 7         | 7      | 14.58%  |
| Samsung Electronics | 2         | 2      | 4.17%   |
| HGST                | 2         | 2      | 4.17%   |
| Fujitsu             | 1         | 1      | 2.08%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 44        | 48     | 88%     |
| SSD  | 5         | 5      | 10%     |
| NVMe | 1         | 1      | 2%      |

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
| Works    | 170       | 217    | 76.92%  |
| Malfunc  | 50        | 54     | 22.62%  |
| Detected | 1         | 1      | 0.45%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 176       | 72.73%  |
| AMD                              | 26        | 10.74%  |
| Samsung Electronics              | 14        | 5.79%   |
| Nvidia                           | 7         | 2.89%   |
| SanDisk                          | 5         | 2.07%   |
| Micron Technology                | 4         | 1.65%   |
| Silicon Motion                   | 2         | 0.83%   |
| KIOXIA                           | 2         | 0.83%   |
| Kingston Technology Company      | 2         | 0.83%   |
| Solid State Storage Technology   | 1         | 0.41%   |
| Silicon Integrated Systems [SiS] | 1         | 0.41%   |
| Biwin Storage Technology         | 1         | 0.41%   |
| ADATA Technology                 | 1         | 0.41%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 25        | 9.43%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 23        | 8.68%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 21        | 7.92%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 17        | 6.42%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 15        | 5.66%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 15        | 5.66%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 14        | 5.28%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 13        | 4.91%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 9         | 3.4%    |
| Unknown                                                                          | 8         | 3.02%   |
| Nvidia MCP79 AHCI Controller                                                     | 7         | 2.64%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 6         | 2.26%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 6         | 2.26%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 6         | 2.26%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 6         | 2.26%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 6         | 2.26%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 5         | 1.89%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 5         | 1.89%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 4         | 1.51%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 4         | 1.51%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 3         | 1.13%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 3         | 1.13%   |
| Intel Comet Lake SATA AHCI Controller                                            | 3         | 1.13%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 3         | 1.13%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 2         | 0.75%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 2         | 0.75%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 2         | 0.75%   |
| Samsung NVMe SSD Controller 980                                                  | 2         | 0.75%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 2         | 0.75%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 2         | 0.75%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 2         | 0.75%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 2         | 0.75%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 2         | 0.75%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 0.38%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                    | 1         | 0.38%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 0.38%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 1         | 0.38%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 1         | 0.38%   |
| SanDisk unknown                                                                  | 1         | 0.38%   |
| SanDisk PC SN530                                                                 | 1         | 0.38%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 196       | 75.38%  |
| NVMe | 34        | 13.08%  |
| IDE  | 23        | 8.85%   |
| RAID | 7         | 2.69%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 190       | 86.36%  |
| AMD    | 30        | 13.64%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz       | 8         | 3.64%   |
| Intel CPU Version                       | 6         | 2.73%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 5         | 2.27%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 5         | 2.27%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 4         | 1.82%   |
| Intel Core i5 CPU M 520 @ 2.40GHz       | 4         | 1.82%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz    | 4         | 1.82%   |
| Intel Core i7-3612QM CPU @ 2.10GHz      | 3         | 1.36%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 3         | 1.36%   |
| Intel Core i5-4300M CPU @ 2.60GHz       | 3         | 1.36%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 3         | 1.36%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 3         | 1.36%   |
| Intel Core i3-6006U CPU @ 2.00GHz       | 3         | 1.36%   |
| Intel Core i3-4005U CPU @ 1.70GHz       | 3         | 1.36%   |
| Intel Core i3-3110M CPU @ 2.40GHz       | 3         | 1.36%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz    | 3         | 1.36%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz    | 3         | 1.36%   |
| Intel Core 2 Duo CPU P7550 @ 2.26GHz    | 3         | 1.36%   |
| AMD E1-2500 APU with Radeon HD Graphics | 3         | 1.36%   |
| Intel Genuine CPU                       | 2         | 0.91%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 2         | 0.91%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 2         | 0.91%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz      | 2         | 0.91%   |
| Intel Core i7-4600U CPU @ 2.10GHz       | 2         | 0.91%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 2         | 0.91%   |
| Intel Core i5-9300H CPU @ 2.40GHz       | 2         | 0.91%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 2         | 0.91%   |
| Intel Core i5-7300U CPU @ 2.60GHz       | 2         | 0.91%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 2         | 0.91%   |
| Intel Core i5-4200U CPU @ 1.60GHz       | 2         | 0.91%   |
| Intel Core i5-3317U CPU @ 1.70GHz       | 2         | 0.91%   |
| Intel Core i5-2410M CPU @ 2.30GHz       | 2         | 0.91%   |
| Intel Core i5-10300H CPU @ 2.50GHz      | 2         | 0.91%   |
| Intel Core i3-5005U CPU @ 2.00GHz       | 2         | 0.91%   |
| Intel Core i3-2330M CPU @ 2.20GHz       | 2         | 0.91%   |
| Intel Core i3-2310M CPU @ 2.10GHz       | 2         | 0.91%   |
| Intel Core i3 CPU M 330 @ 2.13GHz       | 2         | 0.91%   |
| Intel Core 2 Duo CPU T9400 @ 2.53GHz    | 2         | 0.91%   |
| Intel Core 2 Duo CPU T6600 @ 2.20GHz    | 2         | 0.91%   |
| Intel Core 2 Duo                        | 2         | 0.91%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 68        | 30.91%  |
| Intel Core i7           | 30        | 13.64%  |
| Intel Core 2 Duo        | 28        | 12.73%  |
| Intel Core i3           | 23        | 10.45%  |
| Intel Celeron           | 15        | 6.82%   |
| Other                   | 10        | 4.55%   |
| AMD Ryzen 5             | 8         | 3.64%   |
| Intel Pentium           | 5         | 2.27%   |
| AMD E1                  | 5         | 2.27%   |
| AMD A6                  | 5         | 2.27%   |
| Intel Atom              | 3         | 1.36%   |
| AMD Ryzen 7             | 3         | 1.36%   |
| Intel Pentium Dual-Core | 2         | 0.91%   |
| Intel Genuine           | 2         | 0.91%   |
| Intel Core 2            | 2         | 0.91%   |
| AMD E2                  | 2         | 0.91%   |
| Intel Xeon              | 1         | 0.45%   |
| Intel Pentium Silver    | 1         | 0.45%   |
| Intel Pentium M         | 1         | 0.45%   |
| Intel Pentium Dual      | 1         | 0.45%   |
| Intel Core M            | 1         | 0.45%   |
| Intel Celeron Dual-Core | 1         | 0.45%   |
| AMD Ryzen 3             | 1         | 0.45%   |
| AMD A8                  | 1         | 0.45%   |
| AMD A10                 | 1         | 0.45%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 129       | 58.64%  |
| 4       | 40        | 18.18%  |
| Unknown | 33        | 15%     |
| 8       | 7         | 3.18%   |
| 6       | 7         | 3.18%   |
| 12      | 3         | 1.36%   |
| 1       | 1         | 0.45%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 205       | 93.18%  |
| 2       | 13        | 5.91%   |
| Unknown | 2         | 0.91%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 123       | 55.91%  |
| 1       | 64        | 29.09%  |
| Unknown | 33        | 15%     |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| Penryn      | 29        | 13.18%  |
| IvyBridge   | 26        | 11.82%  |
| KabyLake    | 23        | 10.45%  |
| Haswell     | 21        | 9.55%   |
| Skylake     | 18        | 8.18%   |
| SandyBridge | 18        | 8.18%   |
| Westmere    | 15        | 6.82%   |
| Core        | 12        | 5.45%   |
| Silvermont  | 11        | 5%      |
| Broadwell   | 6         | 2.73%   |
| Zen+        | 5         | 2.27%   |
| Zen 2       | 5         | 2.27%   |
| Jaguar      | 5         | 2.27%   |
| Excavator   | 5         | 2.27%   |
| CometLake   | 4         | 1.82%   |
| Goldmont    | 3         | 1.36%   |
| Bonnell     | 3         | 1.36%   |
| Bobcat      | 3         | 1.36%   |
| Zen         | 2         | 0.91%   |
| Puma        | 2         | 0.91%   |
| Zen 3       | 1         | 0.45%   |
| Piledriver  | 1         | 0.45%   |
| K10 Llano   | 1         | 0.45%   |
| Unknown     | 1         | 0.45%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 163       | 62.93%  |
| AMD    | 50        | 19.31%  |
| Nvidia | 46        | 17.76%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 25        | 9.03%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 18        | 6.5%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 15        | 5.42%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 14        | 5.05%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 14        | 5.05%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 12        | 4.33%   |
| Intel Core Processor Integrated Graphics Controller                                      | 11        | 3.97%   |
| Intel HD Graphics 620                                                                    | 9         | 3.25%   |
| Nvidia C79 [GeForce 9400M]                                                               | 6         | 2.17%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 6         | 2.17%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 6         | 2.17%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 6         | 2.17%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 6         | 2.17%   |
| Intel HD Graphics 5500                                                                   | 5         | 1.81%   |
| Intel HD Graphics 530                                                                    | 5         | 1.81%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 1.81%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 5         | 1.81%   |
| AMD Renoir                                                                               | 5         | 1.81%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 4         | 1.44%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/545v]                                        | 4         | 1.44%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 1.08%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 3         | 1.08%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 3         | 1.08%   |
| Intel UHD Graphics 620                                                                   | 3         | 1.08%   |
| Intel HD Graphics 500                                                                    | 3         | 1.08%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 1.08%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 1.08%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 3         | 1.08%   |
| AMD Kabini [Radeon HD 8240 / R3 Series]                                                  | 3         | 1.08%   |
| Nvidia TU117M                                                                            | 2         | 0.72%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 0.72%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 2         | 0.72%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 2         | 0.72%   |
| Nvidia GF119M [GeForce 610M]                                                             | 2         | 0.72%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 0.72%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 0.72%   |
| AMD Wrestler [Radeon HD 7310]                                                            | 2         | 0.72%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 2         | 0.72%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 2         | 0.72%   |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                             | 2         | 0.72%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 103       | 46.82%  |
| 1 x AMD        | 35        | 15.91%  |
| 2 x Intel      | 25        | 11.36%  |
| Intel + Nvidia | 25        | 11.36%  |
| 1 x Nvidia     | 16        | 7.27%   |
| Intel + AMD    | 10        | 4.55%   |
| AMD + Nvidia   | 4         | 1.82%   |
| 2 x Nvidia     | 1         | 0.45%   |
| 2 x AMD        | 1         | 0.45%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 197       | 89.55%  |
| Proprietary | 19        | 8.64%   |
| Unknown     | 4         | 1.82%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 168       | 76.36%  |
| 0.01-0.5   | 35        | 15.91%  |
| 0.51-1.0   | 7         | 3.18%   |
| 1.01-2.0   | 5         | 2.27%   |
| 5.01-6.0   | 2         | 0.91%   |
| 3.01-4.0   | 2         | 0.91%   |
| 2.01-3.0   | 1         | 0.45%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 42        | 18.83%  |
| AU Optronics            | 35        | 15.7%   |
| Chimei Innolux          | 33        | 14.8%   |
| Samsung Electronics     | 28        | 12.56%  |
| BOE                     | 23        | 10.31%  |
| Lenovo                  | 20        | 8.97%   |
| Apple                   | 14        | 6.28%   |
| Chi Mei Optoelectronics | 5         | 2.24%   |
| Sharp                   | 3         | 1.35%   |
| PANDA                   | 3         | 1.35%   |
| LG Philips              | 2         | 0.9%    |
| Goldstar                | 2         | 0.9%    |
| Vestel Elektronik       | 1         | 0.45%   |
| Toshiba                 | 1         | 0.45%   |
| Sony                    | 1         | 0.45%   |
| SLD                     | 1         | 0.45%   |
| Philips                 | 1         | 0.45%   |
| NCS                     | 1         | 0.45%   |
| Lenovo Group Limited    | 1         | 0.45%   |
| LED                     | 1         | 0.45%   |
| InfoVision              | 1         | 0.45%   |
| BenQ                    | 1         | 0.45%   |
| AOC                     | 1         | 0.45%   |
| Ancor Communications    | 1         | 0.45%   |
| Acer                    | 1         | 0.45%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Lenovo LCD Monitor LEN4031 1280x800 300x190mm 14.0-inch               | 5         | 2.21%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch      | 4         | 1.77%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 340x190mm 15.3-inch  | 3         | 1.33%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 340x190mm 15.3-inch       | 3         | 1.33%   |
| BOE LCD Monitor BOE0698 1366x768 310x170mm 13.9-inch                  | 3         | 1.33%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 340x190mm 15.3-inch         | 3         | 1.33%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch  | 2         | 0.88%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 340x190mm 15.3-inch | 2         | 0.88%   |
| LG Display LCD Monitor LGD0459 1920x1080 380x210mm 17.1-inch          | 2         | 0.88%   |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch           | 2         | 0.88%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch           | 2         | 0.88%   |
| LG Display LCD Monitor LGD0250 1366x768 350x190mm 15.7-inch           | 2         | 0.88%   |
| Lenovo LCD Monitor LEN40B0 1366x768 340x190mm 15.3-inch               | 2         | 0.88%   |
| Lenovo LCD Monitor LEN40A0 1366x768 310x170mm 13.9-inch               | 2         | 0.88%   |
| Lenovo LCD Monitor LEN4050 1280x800 330x210mm 15.4-inch               | 2         | 0.88%   |
| Lenovo LCD Monitor LEN4035 1280x800 300x190mm 14.0-inch               | 2         | 0.88%   |
| Chimei Innolux LCD Monitor CMN1492 1366x768 310x170mm 13.9-inch       | 2         | 0.88%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 310x170mm 13.9-inch       | 2         | 0.88%   |
| AU Optronics LCD Monitor AUO325C 1366x768 260x140mm 11.6-inch         | 2         | 0.88%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 310x170mm 13.9-inch        | 2         | 0.88%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch         | 2         | 0.88%   |
| Apple LCD Monitor APP9C5F 1280x800 290x180mm 13.4-inch                | 2         | 0.88%   |
| Apple Color LCD APP9C5E 1280x800 290x190mm 13.6-inch                  | 2         | 0.88%   |
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 710x400mm 32.1-inch    | 1         | 0.44%   |
| Toshiba TV TSB0108 1360x768 700x390mm 31.5-inch                       | 1         | 0.44%   |
| Sony LCD SNY06FA 1600x900 290x160mm 13.0-inch                         | 1         | 0.44%   |
| SLD LCD Monitor SLD003C 1366x768 310x170mm 13.9-inch                  | 1         | 0.44%   |
| Sharp LQ140Z1JW01 SHP1401 3200x1800 310x170mm 13.9-inch               | 1         | 0.44%   |
| Sharp LCD Monitor SHP14BA 1920x1080 340x190mm 15.3-inch               | 1         | 0.44%   |
| Sharp LCD Monitor SHP144D 3840x2160 280x160mm 12.7-inch               | 1         | 0.44%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 610x350mm 27.7-inch     | 1         | 0.44%   |
| Samsung Electronics S27C350 SAM0A3E 1920x1080 600x340mm 27.2-inch     | 1         | 0.44%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch     | 1         | 0.44%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 410x230mm 18.5-inch | 1         | 0.44%   |
| Samsung Electronics LCD Monitor SEC4E41 1280x800 260x160mm 12.0-inch  | 1         | 0.44%   |
| Samsung Electronics LCD Monitor SEC4542 1280x800 300x190mm 14.0-inch  | 1         | 0.44%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 340x190mm 15.3-inch  | 1         | 0.44%   |
| Samsung Electronics LCD Monitor SEC384A 1366x768 340x190mm 15.3-inch  | 1         | 0.44%   |
| Samsung Electronics LCD Monitor SEC3847 1440x900 370x230mm 17.2-inch  | 1         | 0.44%   |
| Samsung Electronics LCD Monitor SEC334A 1366x768 340x190mm 15.3-inch  | 1         | 0.44%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 106       | 48.18%  |
| 1920x1080 (FHD)   | 54        | 24.55%  |
| 1280x800 (WXGA)   | 28        | 12.73%  |
| 1600x900 (HD+)    | 11        | 5%      |
| 3840x2160 (4K)    | 4         | 1.82%   |
| 1440x900 (WXGA+)  | 4         | 1.82%   |
| 1024x768 (XGA)    | 3         | 1.36%   |
| 2560x1440 (QHD)   | 2         | 0.91%   |
| 1920x540          | 2         | 0.91%   |
| 1024x600          | 2         | 0.91%   |
| 3200x1800 (QHD+)  | 1         | 0.45%   |
| 2560x1080         | 1         | 0.45%   |
| 1920x1200 (WUXGA) | 1         | 0.45%   |
| 1280x1024 (SXGA)  | 1         | 0.45%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 85        | 37.61%  |
| 13      | 64        | 28.32%  |
| 12      | 18        | 7.96%   |
| 14      | 14        | 6.19%   |
| 17      | 11        | 4.87%   |
| 11      | 8         | 3.54%   |
| 27      | 4         | 1.77%   |
| 24      | 3         | 1.33%   |
| 23      | 3         | 1.33%   |
| 10      | 3         | 1.33%   |
| 18      | 2         | 0.88%   |
| 64      | 1         | 0.44%   |
| 54      | 1         | 0.44%   |
| 42      | 1         | 0.44%   |
| 40      | 1         | 0.44%   |
| 34      | 1         | 0.44%   |
| 31      | 1         | 0.44%   |
| 21      | 1         | 0.44%   |
| 20      | 1         | 0.44%   |
| 19      | 1         | 0.44%   |
| 16      | 1         | 0.44%   |
| Unknown | 1         | 0.44%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 130       | 57.52%  |
| 201-300     | 62        | 27.43%  |
| 351-400     | 13        | 5.75%   |
| 501-600     | 9         | 3.98%   |
| 401-500     | 4         | 1.77%   |
| 601-700     | 2         | 0.88%   |
| 1001-1500   | 2         | 0.88%   |
| 801-900     | 1         | 0.44%   |
| 701-800     | 1         | 0.44%   |
| 901-1000    | 1         | 0.44%   |
| Unknown     | 1         | 0.44%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 169       | 79.34%  |
| 16/10   | 32        | 15.02%  |
| 3/2     | 5         | 2.35%   |
| 4/3     | 4         | 1.88%   |
| 5/4     | 1         | 0.47%   |
| 21/9    | 1         | 0.47%   |
| Unknown | 1         | 0.47%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 69        | 30.53%  |
| 91-100         | 68        | 30.09%  |
| 61-70          | 19        | 8.41%   |
| 101-110        | 19        | 8.41%   |
| 121-130        | 9         | 3.98%   |
| 71-80          | 7         | 3.1%    |
| 51-60          | 7         | 3.1%    |
| 201-250        | 6         | 2.65%   |
| 301-350        | 4         | 1.77%   |
| 41-50          | 3         | 1.33%   |
| More than 1000 | 2         | 0.88%   |
| 351-500        | 2         | 0.88%   |
| 151-200        | 2         | 0.88%   |
| 141-150        | 2         | 0.88%   |
| 131-140        | 2         | 0.88%   |
| 501-1000       | 2         | 0.88%   |
| 251-300        | 1         | 0.44%   |
| 111-120        | 1         | 0.44%   |
| Unknown        | 1         | 0.44%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 105       | 47.3%   |
| 121-160       | 79        | 35.59%  |
| 51-100        | 31        | 13.96%  |
| 161-240       | 4         | 1.8%    |
| More than 240 | 2         | 0.9%    |
| Unknown       | 1         | 0.45%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 195       | 88.24%  |
| 2     | 20        | 9.05%   |
| 0     | 6         | 2.71%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 111       | 30.33%  |
| Realtek Semiconductor                  | 104       | 28.42%  |
| Qualcomm Atheros                       | 56        | 15.3%   |
| Broadcom                               | 42        | 11.48%  |
| Marvell Technology Group               | 12        | 3.28%   |
| Nvidia                                 | 7         | 1.91%   |
| Ralink                                 | 4         | 1.09%   |
| Xiaomi                                 | 3         | 0.82%   |
| JMicron Technology                     | 3         | 0.82%   |
| Sierra Wireless                        | 2         | 0.55%   |
| Ralink Technology                      | 2         | 0.55%   |
| NetGear                                | 2         | 0.55%   |
| Ericsson Business Mobile Networks      | 2         | 0.55%   |
| Edimax Technology                      | 2         | 0.55%   |
| Dell                                   | 2         | 0.55%   |
| D-Link System                          | 2         | 0.55%   |
| TP-Link                                | 1         | 0.27%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.27%   |
| Silicon Integrated Systems [SiS]       | 1         | 0.27%   |
| Samsung Electronics                    | 1         | 0.27%   |
| OPPO Electronics                       | 1         | 0.27%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.27%   |
| Mercucys                               | 1         | 0.27%   |
| Huawei Technologies                    | 1         | 0.27%   |
| Hewlett-Packard                        | 1         | 0.27%   |
| Google                                 | 1         | 0.27%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 74        | 16.19%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 24        | 5.25%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 19        | 4.16%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 15        | 3.28%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 14        | 3.06%   |
| Intel Wireless 8260                                                     | 13        | 2.84%   |
| Intel Wireless 7260                                                     | 11        | 2.41%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 9         | 1.97%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 8         | 1.75%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 8         | 1.75%   |
| Nvidia MCP79 Ethernet                                                   | 7         | 1.53%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 7         | 1.53%   |
| Intel Centrino Advanced-N 6200                                          | 7         | 1.53%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 6         | 1.31%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 6         | 1.31%   |
| Intel Ethernet Connection I219-LM                                       | 6         | 1.31%   |
| Intel 82577LM Gigabit Network Connection                                | 6         | 1.31%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 6         | 1.31%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 6         | 1.31%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 5         | 1.09%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                 | 5         | 1.09%   |
| Intel Wireless 8265 / 8275                                              | 5         | 1.09%   |
| Intel Wireless 7265                                                     | 5         | 1.09%   |
| Intel WiFi Link 5100                                                    | 5         | 1.09%   |
| Intel Wi-Fi 6 AX200                                                     | 5         | 1.09%   |
| Intel 82566MM Gigabit Network Connection                                | 5         | 1.09%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 5         | 1.09%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 0.88%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 4         | 0.88%   |
| Realtek Realtek Bluetooth 4.2 Adapter                                   | 4         | 0.88%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 4         | 0.88%   |
| Intel Ethernet Connection I218-LM                                       | 4         | 0.88%   |
| Intel Ethernet Connection I217-LM                                       | 4         | 0.88%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 4         | 0.88%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 4         | 0.88%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 4         | 0.88%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 3         | 0.66%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3         | 0.66%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 3         | 0.66%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 0.66%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 110       | 46.41%  |
| Qualcomm Atheros      | 53        | 22.36%  |
| Realtek Semiconductor | 32        | 13.5%   |
| Broadcom              | 27        | 11.39%  |
| Ralink                | 4         | 1.69%   |
| Ralink Technology     | 2         | 0.84%   |
| NetGear               | 2         | 0.84%   |
| Edimax Technology     | 2         | 0.84%   |
| TP-Link               | 1         | 0.42%   |
| Sierra Wireless       | 1         | 0.42%   |
| Mercucys              | 1         | 0.42%   |
| Dell                  | 1         | 0.42%   |
| D-Link System         | 1         | 0.42%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 19        | 7.82%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 14        | 5.76%   |
| Intel Wireless 8260                                                     | 13        | 5.35%   |
| Intel Wireless 7260                                                     | 11        | 4.53%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 9         | 3.7%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 8         | 3.29%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 8         | 3.29%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 7         | 2.88%   |
| Intel Centrino Advanced-N 6200                                          | 7         | 2.88%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 6         | 2.47%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 6         | 2.47%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 6         | 2.47%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 6         | 2.47%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 5         | 2.06%   |
| Intel Wireless 8265 / 8275                                              | 5         | 2.06%   |
| Intel Wireless 7265                                                     | 5         | 2.06%   |
| Intel WiFi Link 5100                                                    | 5         | 2.06%   |
| Intel Wi-Fi 6 AX200                                                     | 5         | 2.06%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 5         | 2.06%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 1.65%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 4         | 1.65%   |
| Realtek Realtek Bluetooth 4.2 Adapter                                   | 4         | 1.65%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 4         | 1.65%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 4         | 1.65%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 4         | 1.65%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 4         | 1.65%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 3         | 1.23%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3         | 1.23%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 1.23%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 1.23%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 1.23%   |
| Intel Centrino Advanced-N 6235                                          | 3         | 1.23%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 3         | 1.23%   |
| Broadcom BCM43142 802.11b/g/n                                           | 3         | 1.23%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.82%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 2         | 0.82%   |
| Realtek 802.11n WLAN Adapter                                            | 2         | 0.82%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 0.82%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 2         | 0.82%   |
| Intel Ultimate N WiFi Link 5300                                         | 2         | 0.82%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 98        | 47.34%  |
| Intel                                  | 53        | 25.6%   |
| Broadcom                               | 15        | 7.25%   |
| Marvell Technology Group               | 12        | 5.8%    |
| Qualcomm Atheros                       | 10        | 4.83%   |
| Nvidia                                 | 7         | 3.38%   |
| Xiaomi                                 | 3         | 1.45%   |
| JMicron Technology                     | 3         | 1.45%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.48%   |
| Silicon Integrated Systems [SiS]       | 1         | 0.48%   |
| Samsung Electronics                    | 1         | 0.48%   |
| OPPO Electronics                       | 1         | 0.48%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.48%   |
| Google                                 | 1         | 0.48%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 74        | 35.75%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 24        | 11.59%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 15        | 7.25%   |
| Nvidia MCP79 Ethernet                                             | 7         | 3.38%   |
| Intel Ethernet Connection I219-LM                                 | 6         | 2.9%    |
| Intel 82577LM Gigabit Network Connection                          | 6         | 2.9%    |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 5         | 2.42%   |
| Intel 82566MM Gigabit Network Connection                          | 5         | 2.42%   |
| Intel Ethernet Connection I218-LM                                 | 4         | 1.93%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 1.93%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 1.45%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 3         | 1.45%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 1.45%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 3         | 1.45%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.97%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 0.97%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.97%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 2         | 0.97%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 2         | 0.97%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.97%   |
| Intel 82567LM Gigabit Network Connection                          | 2         | 0.97%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express          | 2         | 0.97%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 2         | 0.97%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 2         | 0.97%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 2         | 0.97%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.48%   |
| Sony Ericsson Mobile AB SOV41 RNDIS Control RNDIS Ethernet Data   | 1         | 0.48%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.48%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.48%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.48%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.48%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.48%   |
| OPPO CPH1909 RNDIS Control RNDIS Ethernet Data                    | 1         | 0.48%   |
| OnePlus (Shenzhen) OnePlus RNDIS Control RNDIS Ethernet Data      | 1         | 0.48%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 0.48%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller             | 1         | 0.48%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller              | 1         | 0.48%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.48%   |
| Intel Ethernet Connection I218-V                                  | 1         | 0.48%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.48%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 219       | 51.29%  |
| Ethernet | 201       | 47.07%  |
| Unknown  | 4         | 0.94%   |
| Modem    | 3         | 0.7%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 140       | 50.36%  |
| Ethernet | 134       | 48.2%   |
| Unknown  | 3         | 1.08%   |
| Modem    | 1         | 0.36%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 197       | 89.55%  |
| 1     | 22        | 10%     |
| 0     | 1         | 0.45%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 210       | 95.45%  |
| Yes  | 10        | 4.55%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 53        | 35.57%  |
| Broadcom                        | 19        | 12.75%  |
| Qualcomm Atheros Communications | 15        | 10.07%  |
| Realtek Semiconductor           | 14        | 9.4%    |
| Apple                           | 13        | 8.72%   |
| Foxconn / Hon Hai               | 8         | 5.37%   |
| Lite-On Technology              | 7         | 4.7%    |
| Hewlett-Packard                 | 5         | 3.36%   |
| Ralink                          | 4         | 2.68%   |
| Dell                            | 4         | 2.68%   |
| Cambridge Silicon Radio         | 4         | 2.68%   |
| IMC Networks                    | 3         | 2.01%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 31        | 20.53%  |
| Broadcom BCM2045B (BDC-2.1)                                 | 8         | 5.3%    |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                     | 6         | 3.97%   |
| Apple Bluetooth Host Controller                             | 6         | 3.97%   |
| Intel AX201 Bluetooth                                       | 5         | 3.31%   |
| Intel AX200 Bluetooth                                       | 5         | 3.31%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 5         | 3.31%   |
| Apple Built-in iSight (no firmware loaded)                  | 5         | 3.31%   |
| Ralink RT3290 Bluetooth                                     | 4         | 2.65%   |
| Lite-On Atheros AR3012 Bluetooth                            | 4         | 2.65%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 4         | 2.65%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 4         | 2.65%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 4         | 2.65%   |
| Realtek RTL8821A Bluetooth                                  | 3         | 1.99%   |
| Realtek  Bluetooth 4.2 Adapter                              | 3         | 1.99%   |
| Realtek  Bluetooth 4.0 Adapter                              | 3         | 1.99%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 3         | 1.99%   |
| Intel Wireless-AC 3168 Bluetooth                            | 3         | 1.99%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 3         | 1.99%   |
| Foxconn / Hon Hai Qualcomm Atheros Bluetooth 4.0            | 3         | 1.99%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 3         | 1.99%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 3         | 1.99%   |
| Realtek RTL8723B Bluetooth                                  | 2         | 1.32%   |
| Realtek Bluetooth Radio                                     | 2         | 1.32%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 2         | 1.32%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 2         | 1.32%   |
| Realtek  Bluetooth Adapter                                  | 1         | 0.66%   |
| Realtek  Bluetooth 4.0 + High Speed Chip                    | 1         | 0.66%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 1         | 0.66%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1         | 0.66%   |
| Qualcomm Atheros AR3012 Bluetooth                           | 1         | 0.66%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)             | 1         | 0.66%   |
| Lite-On Realtek Bluetooth Adapter                           | 1         | 0.66%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 1         | 0.66%   |
| Lite-On Qualcomm Atheros Bluetooth                          | 1         | 0.66%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 1         | 0.66%   |
| IMC Networks Realtek Bluetooth Adapter                      | 1         | 0.66%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS            | 1         | 0.66%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 1         | 0.66%   |
| HP Broadcom 2070 Bluetooth Combo                            | 1         | 0.66%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 181       | 73.58%  |
| AMD                              | 38        | 15.45%  |
| Nvidia                           | 21        | 8.54%   |
| Texas Instruments                | 2         | 0.81%   |
| GN Netcom                        | 2         | 0.81%   |
| Silicon Integrated Systems [SiS] | 1         | 0.41%   |
| Creative Technology              | 1         | 0.41%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 27        | 9%      |
| Intel Sunrise Point-LP HD Audio                                                                   | 25        | 8.33%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 17        | 5.67%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 16        | 5.33%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 15        | 5%      |
| Intel 8 Series HD Audio Controller                                                                | 15        | 5%      |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 15        | 5%      |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 13        | 4.33%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 13        | 4.33%   |
| AMD FCH Azalia Controller                                                                         | 12        | 4%      |
| Nvidia MCP79 High Definition Audio                                                                | 7         | 2.33%   |
| AMD Kabini HDMI/DP Audio                                                                          | 7         | 2.33%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 6         | 2%      |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 6         | 2%      |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 2%      |
| Intel Broadwell-U Audio Controller                                                                | 6         | 2%      |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 6         | 2%      |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 6         | 2%      |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 6         | 2%      |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 5         | 1.67%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 5         | 1.67%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 1.67%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 5         | 1.67%   |
| AMD High Definition Audio Controller                                                              | 5         | 1.67%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 5         | 1.67%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 1.33%   |
| Intel Comet Lake PCH cAVS                                                                         | 4         | 1.33%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 4         | 1.33%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 3         | 1%      |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 1%      |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3         | 1%      |
| AMD Wrestler HDMI Audio                                                                           | 3         | 1%      |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 0.67%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 0.67%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 1         | 0.33%   |
| Texas Instruments PCM2900 Audio Codec                                                             | 1         | 0.33%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 0.33%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.33%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 1         | 0.33%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.33%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 64        | 25%     |
| SK hynix                     | 44        | 17.19%  |
| Kingston                     | 34        | 13.28%  |
| Micron Technology            | 23        | 8.98%   |
| Unknown                      | 18        | 7.03%   |
| Ramaxel Technology           | 11        | 4.3%    |
| Nanya Technology             | 8         | 3.13%   |
| Crucial                      | 8         | 3.13%   |
| Elpida                       | 7         | 2.73%   |
| Unknown                      | 7         | 2.73%   |
| A-DATA Technology            | 6         | 2.34%   |
| Smart                        | 5         | 1.95%   |
| Transcend                    | 2         | 0.78%   |
| Silicon Power                | 2         | 0.78%   |
| ASint Technology             | 2         | 0.78%   |
| 48spaces                     | 2         | 0.78%   |
| Unknown (ABCD)               | 1         | 0.39%   |
| Unknown (8AFD)               | 1         | 0.39%   |
| Unknown (0x3D7F000000000000) | 1         | 0.39%   |
| Unknown (0x0809)             | 1         | 0.39%   |
| Smart Brazil                 | 1         | 0.39%   |
| Sesame                       | 1         | 0.39%   |
| PNY                          | 1         | 0.39%   |
| Kingmax                      | 1         | 0.39%   |
| High Bridge                  | 1         | 0.39%   |
| GOODRAM                      | 1         | 0.39%   |
| Corsair                      | 1         | 0.39%   |
| Avant                        | 1         | 0.39%   |
| Apacer                       | 1         | 0.39%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                 | 8         | 2.92%   |
| Unknown                                                    | 7         | 2.55%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s     | 6         | 2.19%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s      | 5         | 1.82%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s      | 5         | 1.82%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                 | 4         | 1.46%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s     | 4         | 1.46%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s      | 4         | 1.46%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s      | 4         | 1.46%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s      | 4         | 1.46%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s      | 3         | 1.09%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s     | 3         | 1.09%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 1333MT/s      | 3         | 1.09%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s   | 3         | 1.09%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s      | 3         | 1.09%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s      | 3         | 1.09%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2400MT/s      | 3         | 1.09%   |
| Ramaxel RAM RMT3170EB68F9W1600 4GB SODIMM DDR3 1600MT/s    | 3         | 1.09%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s    | 3         | 1.09%   |
| Unknown RAM Module 4GB SODIMM DDR3                         | 2         | 0.73%   |
| Unknown RAM Module 2GB SODIMM DDR2                         | 2         | 0.73%   |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s      | 2         | 0.73%   |
| SK hynix RAM HMT451S6MFR8A-PB 4GB SODIMM DDR3 800MT/s      | 2         | 0.73%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s     | 2         | 0.73%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2133MT/s     | 2         | 0.73%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s     | 2         | 0.73%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s      | 2         | 0.73%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s     | 2         | 0.73%   |
| Ramaxel RAM RMT3160MP68FAF1600 8GB SODIMM DDR3 1600MT/s    | 2         | 0.73%   |
| Ramaxel RAM RMSA3300ME78HBF-2666 16GB SODIMM DDR4 2667MT/s | 2         | 0.73%   |
| Nanya RAM Module 1GB SODIMM DDR2 667MT/s                   | 2         | 0.73%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s      | 2         | 0.73%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s       | 2         | 0.73%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s     | 2         | 0.73%   |
| Micron RAM 16JSF25664HZ-1G1F1 2GB SODIMM DDR3 1067MT/s     | 2         | 0.73%   |
| Kingston RAM Module 2GB SODIMM DDR2 667MT/s                | 2         | 0.73%   |
| Kingston RAM 99U5469-045.A00LF 4GB SODIMM DDR3 1600MT/s    | 2         | 0.73%   |
| Kingston RAM 99U5295-013.A00LF 2GB SODIMM DDR 667MT/s      | 2         | 0.73%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s      | 2         | 0.73%   |
| A-DATA RAM AM1L16BC4R1-B1GS 4GB SODIMM DDR3 1333MT/s       | 2         | 0.73%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 123       | 56.68%  |
| DDR4    | 54        | 24.88%  |
| DDR2    | 29        | 13.36%  |
| LPDDR3  | 3         | 1.38%   |
| Unknown | 3         | 1.38%   |
| LPDDR4  | 2         | 0.92%   |
| SDRAM   | 1         | 0.46%   |
| DRAM    | 1         | 0.46%   |
| DDR     | 1         | 0.46%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 207       | 96.28%  |
| Row Of Chips | 4         | 1.86%   |
| Chip         | 3         | 1.4%    |
| DIMM         | 1         | 0.47%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 89        | 36.93%  |
| 2048  | 64        | 26.56%  |
| 8192  | 60        | 24.9%   |
| 16384 | 15        | 6.22%   |
| 1024  | 11        | 4.56%   |
| 32768 | 2         | 0.83%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 73        | 30.42%  |
| 1333    | 25        | 10.42%  |
| 667     | 24        | 10%     |
| 2667    | 23        | 9.58%   |
| 1334    | 18        | 7.5%    |
| 1067    | 14        | 5.83%   |
| 2400    | 13        | 5.42%   |
| 2133    | 13        | 5.42%   |
| 3200    | 11        | 4.58%   |
| 1867    | 7         | 2.92%   |
| 800     | 7         | 2.92%   |
| Unknown | 6         | 2.5%    |
| 975     | 3         | 1.25%   |
| 4267    | 1         | 0.42%   |
| 1066    | 1         | 0.42%   |
| 533     | 1         | 0.42%   |

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
| Chicony Electronics                    | 47        | 29.75%  |
| Realtek Semiconductor                  | 15        | 9.49%   |
| IMC Networks                           | 13        | 8.23%   |
| Microdia                               | 12        | 7.59%   |
| Acer                                   | 12        | 7.59%   |
| Quanta                                 | 9         | 5.7%    |
| Suyin                                  | 7         | 4.43%   |
| Sunplus Innovation Technology          | 7         | 4.43%   |
| Lite-On Technology                     | 7         | 4.43%   |
| Syntek                                 | 6         | 3.8%    |
| Alcor Micro                            | 4         | 2.53%   |
| Z-Star Microelectronics                | 3         | 1.9%    |
| Lenovo                                 | 3         | 1.9%    |
| Cheng Uei Precision Industry (Foxlink) | 3         | 1.9%    |
| ALi                                    | 2         | 1.27%   |
| Silicon Motion                         | 1         | 0.63%   |
| Ricoh                                  | 1         | 0.63%   |
| Primax Electronics                     | 1         | 0.63%   |
| Luxvisions Innotech Limited            | 1         | 0.63%   |
| Importek                               | 1         | 0.63%   |
| icSpring                               | 1         | 0.63%   |
| DigiTech                               | 1         | 0.63%   |
| Apple                                  | 1         | 0.63%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Chicony HD WebCam                         | 7         | 4.4%    |
| Chicony Integrated Camera                 | 6         | 3.77%   |
| Chicony Lenovo Integrated Camera (0.3MP)  | 5         | 3.14%   |
| Syntek Lenovo EasyCamera                  | 4         | 2.52%   |
| Realtek USB Camera                        | 4         | 2.52%   |
| Realtek Integrated_Webcam_HD              | 4         | 2.52%   |
| Lite-On Integrated Camera                 | 4         | 2.52%   |
| Realtek Realtek USB2.0 PC Camera          | 3         | 1.89%   |
| Quanta HP TrueVision HD Camera            | 3         | 1.89%   |
| Microdia Integrated_Webcam_HD             | 3         | 1.89%   |
| Microdia Integrated Webcam                | 3         | 1.89%   |
| IMC Networks USB2.0 HD UVC WebCam         | 3         | 1.89%   |
| IMC Networks Integrated Camera            | 3         | 1.89%   |
| IMC Networks EasyCamera                   | 3         | 1.89%   |
| Chicony HD WebCam (Acer)                  | 3         | 1.89%   |
| Chicony EasyCamera                        | 3         | 1.89%   |
| Acer Lenovo EasyCamera                    | 3         | 1.89%   |
| Acer Integrated Camera                    | 3         | 1.89%   |
| Z-Star WebCam SC-03FFL11739P              | 2         | 1.26%   |
| Syntek EasyCamera                         | 2         | 1.26%   |
| Suyin Integrated_Webcam_HD                | 2         | 1.26%   |
| Suyin HD Video WebCam                     | 2         | 1.26%   |
| Sunplus HD WebCam                         | 2         | 1.26%   |
| Quanta Realtek DMFT - RGB                 | 2         | 1.26%   |
| Quanta HP Webcam                          | 2         | 1.26%   |
| Microdia Sonix USB 2.0 Camera             | 2         | 1.26%   |
| Microdia Dell Laptop Integrated Webcam HD | 2         | 1.26%   |
| Lite-On HP HD Camera                      | 2         | 1.26%   |
| Lenovo Integrated Webcam [R5U877]         | 2         | 1.26%   |
| IMC Networks Integrated Webcam            | 2         | 1.26%   |
| Chicony VGA Webcam                        | 2         | 1.26%   |
| Chicony Realtek DMFT - RGB                | 2         | 1.26%   |
| Chicony HP HD Webcam [Fixed]              | 2         | 1.26%   |
| Chicony Chicony USB 2.0 Camera            | 2         | 1.26%   |
| ALi Gateway Webcam                        | 2         | 1.26%   |
| Acer SunplusIT INC. Integrated Camera     | 2         | 1.26%   |
| Z-Star Webcam                             | 1         | 0.63%   |
| Suyin Laptop_Integrated_Webcam_FHD        | 1         | 0.63%   |
| Suyin HP webcam [dv6-1190en]              | 1         | 0.63%   |
| Suyin Acer/HP Integrated Webcam [CN0314]  | 1         | 0.63%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 19        | 41.3%   |
| Upek                       | 11        | 23.91%  |
| AuthenTec                  | 7         | 15.22%  |
| STMicroelectronics         | 4         | 8.7%    |
| Shenzhen Goodix Technology | 2         | 4.35%   |
| LighTuning Technology      | 2         | 4.35%   |
| Synaptics                  | 1         | 2.17%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 9         | 19.57%  |
| STMicroelectronics Fingerprint Reader                  | 4         | 8.7%    |
| Validity Sensors VFS5011 Fingerprint Reader            | 3         | 6.52%   |
| Validity Sensors VFS491                                | 3         | 6.52%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 3         | 6.52%   |
| Validity Sensors VFS495 Fingerprint Reader             | 2         | 4.35%   |
| Validity Sensors VFS471 Fingerprint Reader             | 2         | 4.35%   |
| Validity Sensors Synaptics WBDI                        | 2         | 4.35%   |
| Validity Sensors Fingerprint scanner                   | 2         | 4.35%   |
| Upek TCS5B Fingerprint sensor                          | 2         | 4.35%   |
| Shenzhen Goodix Fingerprint Reader                     | 2         | 4.35%   |
| AuthenTec AES2501 Fingerprint Sensor                   | 2         | 4.35%   |
| AuthenTec AES1600                                      | 2         | 4.35%   |
| Validity Sensors VFS101 Fingerprint Reader             | 1         | 2.17%   |
| Validity Sensors Swipe Fingerprint Sensor              | 1         | 2.17%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 1         | 2.17%   |
| LighTuning ES603 Swipe Fingerprint Sensor              | 1         | 2.17%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 2.17%   |
| AuthenTec AuthenTec Inc. AES1660                       | 1         | 2.17%   |
| AuthenTec AES2810                                      | 1         | 2.17%   |
| AuthenTec AES1660 Fingerprint Sensor                   | 1         | 2.17%   |

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
| 1     | 77        | 34.84%  |
| 2     | 64        | 28.96%  |
| 0     | 41        | 18.55%  |
| 3     | 30        | 13.57%  |
| 4     | 9         | 4.07%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 135       | 43.13%  |
| Net/wireless             | 58        | 18.53%  |
| Fingerprint reader       | 44        | 14.06%  |
| Bluetooth                | 37        | 11.82%  |
| Card reader              | 34        | 10.86%  |
| Storage                  | 3         | 0.96%   |
| Sound                    | 1         | 0.32%   |
| Network                  | 1         | 0.32%   |

