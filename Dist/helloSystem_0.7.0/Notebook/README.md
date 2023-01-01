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

Total: 237

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
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
| amd64 | 207       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 205       | 99.03%  |
| GNOME        | 2         | 0.97%   |

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
| SLiM | 207       | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 194       | 93.27%  |
| es_ES | 5         | 2.4%    |
| fr_FR | 3         | 1.44%   |
| C     | 3         | 1.44%   |
| uk_UA | 1         | 0.48%   |
| it_IT | 1         | 0.48%   |
| de_DE | 1         | 0.48%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 203       | 98.07%  |
| BIOS | 4         | 1.93%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Zfs    | 106       | 50.72%  |
| Cd9660 | 103       | 49.28%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 206       | 99.52%  |
| MBR  | 1         | 0.48%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 62        | 29.95%  |
| Hewlett-Packard     | 35        | 16.91%  |
| Dell                | 26        | 12.56%  |
| Acer                | 21        | 10.14%  |
| Apple               | 14        | 6.76%   |
| ASUSTek Computer    | 12        | 5.8%    |
| Toshiba             | 6         | 2.9%    |
| Samsung Electronics | 5         | 2.42%   |
| TUXEDO              | 3         | 1.45%   |
| Sony                | 3         | 1.45%   |
| MSI                 | 2         | 0.97%   |
| HASEE Computer      | 2         | 0.97%   |
| Fujitsu             | 2         | 0.97%   |
| TWINHEAD            | 1         | 0.48%   |
| Razer               | 1         | 0.48%   |
| Panasonic           | 1         | 0.48%   |
| Packard Bell        | 1         | 0.48%   |
| Notebook            | 1         | 0.48%   |
| LG Electronics      | 1         | 0.48%   |
| Itautec             | 1         | 0.48%   |
| GPD                 | 1         | 0.48%   |
| Gateway             | 1         | 0.48%   |
| eMachines           | 1         | 0.48%   |
| DNS                 | 1         | 0.48%   |
| Alienware           | 1         | 0.48%   |
| Acidanthera         | 1         | 0.48%   |
| Unknown             | 1         | 0.48%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                               | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Apple MacBook4,1                                   | 4         | 1.93%   |
| TUXEDO Aura 15 Gen1                                | 2         | 0.97%   |
| HP ProBook 4540s                                   | 2         | 0.97%   |
| HP 2000                                            | 2         | 0.97%   |
| Dell Precision 7710                                | 2         | 0.97%   |
| Dell Latitude E5470                                | 2         | 0.97%   |
| Dell Latitude D630                                 | 2         | 0.97%   |
| Apple MacBook6,1                                   | 2         | 0.97%   |
| Apple MacBook5,1                                   | 2         | 0.97%   |
| Acer V5-131                                        | 2         | 0.97%   |
| Acer Aspire ES1-533                                | 2         | 0.97%   |
| Acer Aspire E1-522                                 | 2         | 0.97%   |
| Acer Aspire 5930                                   | 2         | 0.97%   |
| TWINHEAD U12CT                                     | 1         | 0.48%   |
| TUXEDO InfinityBook13V3                            | 1         | 0.48%   |
| Toshiba Satellite S55t-B                           | 1         | 0.48%   |
| Toshiba Satellite P300                             | 1         | 0.48%   |
| Toshiba Satellite L550                             | 1         | 0.48%   |
| Toshiba Satellite C640                             | 1         | 0.48%   |
| Toshiba Satellite C50-B                            | 1         | 0.48%   |
| Toshiba PORTEGE R700                               | 1         | 0.48%   |
| Sony VPCSB11FX                                     | 1         | 0.48%   |
| Sony VGN-NW25GF_S                                  | 1         | 0.48%   |
| Sony SVZ1311C5E                                    | 1         | 0.48%   |
| Samsung Q430/Q530                                  | 1         | 0.48%   |
| Samsung N150P/N210P/N220P                          | 1         | 0.48%   |
| Samsung N100                                       | 1         | 0.48%   |
| Samsung 305E4A/305E5A/305E7A                       | 1         | 0.48%   |
| Samsung 300E4C/300E5C/300E7C                       | 1         | 0.48%   |
| Razer Blade 15 Base Model (Early 2020) - RZ09-0328 | 1         | 0.48%   |
| Panasonic CF-B11JWCYS                              | 1         | 0.48%   |
| Packard Bell EasyNote TE69HW                       | 1         | 0.48%   |
| Notebook N15_17RD                                  | 1         | 0.48%   |
| MSI GF65 Thin 10SER                                | 1         | 0.48%   |
| MSI GF63 Thin 10SC                                 | 1         | 0.48%   |
| LG E300-A.CP20T                                    | 1         | 0.48%   |
| Lenovo Z50-70 20354                                | 1         | 0.48%   |
| Lenovo V310-14IKB 80T2                             | 1         | 0.48%   |
| Lenovo ThinkPad X61 Tablet 7763AD6                 | 1         | 0.48%   |
| Lenovo ThinkPad X61 7675K2U                        | 1         | 0.48%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 42        | 20.29%  |
| Acer Aspire             | 17        | 8.21%   |
| Dell Latitude           | 12        | 5.8%    |
| HP Pavilion             | 11        | 5.31%   |
| Lenovo IdeaPad          | 8         | 3.86%   |
| Dell Inspiron           | 8         | 3.86%   |
| HP ProBook              | 7         | 3.38%   |
| Toshiba Satellite       | 5         | 2.42%   |
| HP Laptop               | 4         | 1.93%   |
| Apple MacBook4          | 4         | 1.93%   |
| HP EliteBook            | 3         | 1.45%   |
| Dell Precision          | 3         | 1.45%   |
| Apple MacBook5          | 3         | 1.45%   |
| TUXEDO Aura             | 2         | 0.97%   |
| Lenovo Legion           | 2         | 0.97%   |
| HP Compaq               | 2         | 0.97%   |
| HP 2000                 | 2         | 0.97%   |
| Fujitsu LIFEBOOK        | 2         | 0.97%   |
| Apple MacBookPro5       | 2         | 0.97%   |
| Apple MacBook6          | 2         | 0.97%   |
| Acer V5-131             | 2         | 0.97%   |
| TWINHEAD U12CT          | 1         | 0.48%   |
| TUXEDO InfinityBook13V3 | 1         | 0.48%   |
| Toshiba PORTEGE         | 1         | 0.48%   |
| Sony VPCSB11FX          | 1         | 0.48%   |
| Sony VGN-NW25GF         | 1         | 0.48%   |
| Sony SVZ1311C5E         | 1         | 0.48%   |
| Samsung Q430            | 1         | 0.48%   |
| Samsung N150P           | 1         | 0.48%   |
| Samsung N100            | 1         | 0.48%   |
| Samsung 305E4A          | 1         | 0.48%   |
| Samsung 300E4C          | 1         | 0.48%   |
| Razer Blade             | 1         | 0.48%   |
| Panasonic CF-B11JWCYS   | 1         | 0.48%   |
| Packard Bell EasyNote   | 1         | 0.48%   |
| Notebook N15            | 1         | 0.48%   |
| MSI GF65                | 1         | 0.48%   |
| MSI GF63                | 1         | 0.48%   |
| LG E300-A.CP20T         | 1         | 0.48%   |
| Lenovo Z50-70           | 1         | 0.48%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2016    | 17        | 8.21%   |
| 2013    | 17        | 8.21%   |
| 2012    | 17        | 8.21%   |
| 2011    | 17        | 8.21%   |
| 2021    | 16        | 7.73%   |
| 2018    | 16        | 7.73%   |
| 2010    | 16        | 7.73%   |
| 2015    | 15        | 7.25%   |
| 2017    | 13        | 6.28%   |
| 2008    | 13        | 6.28%   |
| 2020    | 12        | 5.8%    |
| 2014    | 11        | 5.31%   |
| 2009    | 10        | 4.83%   |
| 2007    | 6         | 2.9%    |
| 2022    | 4         | 1.93%   |
| 2019    | 4         | 1.93%   |
| 2006    | 2         | 0.97%   |
| Unknown | 1         | 0.48%   |

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
| No   | 207       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 77        | 37.2%   |
| 8.01-16.0   | 68        | 32.85%  |
| 16.01-24.0  | 36        | 17.39%  |
| 2.01-3.0    | 13        | 6.28%   |
| 32.01-64.0  | 6         | 2.9%    |
| 3.01-4.0    | 5         | 2.42%   |
| 24.01-32.0  | 1         | 0.48%   |
| 64.01-256.0 | 1         | 0.48%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 131       | 63.29%  |
| 0.51-1.0 | 55        | 26.57%  |
| 1.01-2.0 | 14        | 6.76%   |
| 2.01-3.0 | 7         | 3.38%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 157       | 75.12%  |
| 2      | 40        | 19.14%  |
| 0      | 9         | 4.31%   |
| 3      | 2         | 0.96%   |
| 4      | 1         | 0.48%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 112       | 54.11%  |
| Yes       | 95        | 45.89%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 191       | 92.27%  |
| No        | 16        | 7.73%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 206       | 99.52%  |
| No        | 1         | 0.48%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 140       | 67.63%  |
| No        | 67        | 32.37%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country             | Notebooks | Percent |
|---------------------|-----------|---------|
| USA                 | 31        | 14.98%  |
| Russia              | 15        | 7.25%   |
| Spain               | 14        | 6.76%   |
| Germany             | 12        | 5.8%    |
| Italy               | 11        | 5.31%   |
| Brazil              | 11        | 5.31%   |
| UK                  | 10        | 4.83%   |
| China               | 8         | 3.86%   |
| Romania             | 6         | 2.9%    |
| Netherlands         | 6         | 2.9%    |
| Mexico              | 6         | 2.9%    |
| France              | 6         | 2.9%    |
| Vietnam             | 4         | 1.93%   |
| Ukraine             | 4         | 1.93%   |
| Poland              | 4         | 1.93%   |
| Indonesia           | 4         | 1.93%   |
| India               | 4         | 1.93%   |
| Colombia            | 3         | 1.45%   |
| Chile               | 3         | 1.45%   |
| Turkey              | 2         | 0.97%   |
| Sweden              | 2         | 0.97%   |
| Portugal            | 2         | 0.97%   |
| Peru                | 2         | 0.97%   |
| Norway              | 2         | 0.97%   |
| Hungary             | 2         | 0.97%   |
| Greece              | 2         | 0.97%   |
| Denmark             | 2         | 0.97%   |
| Czechia             | 2         | 0.97%   |
| Canada              | 2         | 0.97%   |
| Trinidad and Tobago | 1         | 0.48%   |
| Tanzania            | 1         | 0.48%   |
| Taiwan              | 1         | 0.48%   |
| Switzerland         | 1         | 0.48%   |
| Singapore           | 1         | 0.48%   |
| New Zealand         | 1         | 0.48%   |
| Myanmar             | 1         | 0.48%   |
| Malaysia            | 1         | 0.48%   |
| Lithuania           | 1         | 0.48%   |
| Latvia              | 1         | 0.48%   |
| Ireland             | 1         | 0.48%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Moscow           | 4         | 1.9%    |
| Hanoi            | 3         | 1.43%   |
| Amsterdam        | 3         | 1.43%   |
| Warsaw           | 2         | 0.95%   |
| Madrid           | 2         | 0.95%   |
| Lima             | 2         | 0.95%   |
| Leatherhead      | 2         | 0.95%   |
| Jakarta          | 2         | 0.95%   |
| Dijon            | 2         | 0.95%   |
| Curitiba         | 2         | 0.95%   |
| Cluj-Napoca      | 2         | 0.95%   |
| Bucharest        | 2         | 0.95%   |
| Alcobendas       | 2         | 0.95%   |
| Zhaoqing         | 1         | 0.48%   |
| Zaporizhzhya     | 1         | 0.48%   |
| Zapopan          | 1         | 0.48%   |
| Youngsville      | 1         | 0.48%   |
| Yichun           | 1         | 0.48%   |
| Yaphank          | 1         | 0.48%   |
| Yangon           | 1         | 0.48%   |
| Wroclaw          | 1         | 0.48%   |
| Windsor          | 1         | 0.48%   |
| West Linn        | 1         | 0.48%   |
| Washington       | 1         | 0.48%   |
| Vilnius          | 1         | 0.48%   |
| Ventura          | 1         | 0.48%   |
| VÃ¤sterÃ¥s   | 1         | 0.48%   |
| Vaudreuil-Dorion | 1         | 0.48%   |
| Vandalia         | 1         | 0.48%   |
| Valencia         | 1         | 0.48%   |
| Urnieta          | 1         | 0.48%   |
| Ugarchin         | 1         | 0.48%   |
| Turley           | 1         | 0.48%   |
| Turin            | 1         | 0.48%   |
| Tudela de Duero  | 1         | 0.48%   |
| Tsarskoye Selo   | 1         | 0.48%   |
| Tromsø          | 1         | 0.48%   |
| Torokszentmiklos | 1         | 0.48%   |
| Tolyatti         | 1         | 0.48%   |
| Tiruchi          | 1         | 0.48%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 44        | 46     | 18.11%  |
| Samsung Electronics | 34        | 36     | 13.99%  |
| Seagate             | 26        | 31     | 10.7%   |
| Toshiba             | 19        | 19     | 7.82%   |
| Kingston            | 17        | 18     | 7%      |
| Crucial             | 15        | 15     | 6.17%   |
| SanDisk             | 11        | 12     | 4.53%   |
| Hitachi             | 10        | 10     | 4.12%   |
| Intel               | 9         | 10     | 3.7%    |
| HGST                | 6         | 6      | 2.47%   |
| Micron Technology   | 5         | 5      | 2.06%   |
| Fujitsu             | 5         | 5      | 2.06%   |
| A-DATA Technology   | 4         | 4      | 1.65%   |
| SPCC                | 3         | 4      | 1.23%   |
| Intenso             | 3         | 3      | 1.23%   |
| Zheino              | 2         | 2      | 0.82%   |
| SK hynix            | 2         | 2      | 0.82%   |
| Patriot             | 2         | 2      | 0.82%   |
| KingSpec            | 2         | 2      | 0.82%   |
| Corsair             | 2         | 2      | 0.82%   |
| Transcend           | 1         | 1      | 0.41%   |
| Team                | 1         | 1      | 0.41%   |
| SSSTC               | 1         | 1      | 0.41%   |
| Smartbuy            | 1         | 1      | 0.41%   |
| PNY                 | 1         | 1      | 0.41%   |
| Plextor             | 1         | 1      | 0.41%   |
| Phison              | 1         | 1      | 0.41%   |
| Netac               | 1         | 1      | 0.41%   |
| Mushkin             | 1         | 1      | 0.41%   |
| LITEON              | 1         | 1      | 0.41%   |
| Lexar               | 1         | 1      | 0.41%   |
| Leven               | 1         | 1      | 0.41%   |
| KIOXIA              | 1         | 1      | 0.41%   |
| Integral            | 1         | 1      | 0.41%   |
| INDMEM              | 1         | 1      | 0.41%   |
| Hikvision           | 1         | 1      | 0.41%   |
| Hewlett-Packard     | 1         | 1      | 0.41%   |
| BIWIN               | 1         | 1      | 0.41%   |
| Apple               | 1         | 1      | 0.41%   |
| Apacer              | 1         | 1      | 0.41%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| WDC WDS120G2G0A-00JH30 120GB       | 5         | 2.02%   |
| HGST HTS545050A7E680 500GB         | 5         | 2.02%   |
| Toshiba MQ01ABF050 500GB           | 4         | 1.61%   |
| Kingston SA400S37240G 240GB        | 4         | 1.61%   |
| Toshiba MQ01ABD100 1TB             | 3         | 1.21%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 3         | 1.21%   |
| Kingston SA400S37120G 120GB        | 3         | 1.21%   |
| Crucial CT500MX500SSD1 500GB       | 3         | 1.21%   |
| Crucial CT240BX500SSD1 240GB       | 3         | 1.21%   |
| WDC WDS240G2G0A-00JH30 240GB       | 2         | 0.81%   |
| WDC WD5000LPVX-22V0TT0 500GB       | 2         | 0.81%   |
| WDC WD5000LPCX-60VHAT0 500GB       | 2         | 0.81%   |
| WDC WD10JPCX-24UE4T0 1TB           | 2         | 0.81%   |
| Toshiba MK3261GSYN 320GB           | 2         | 0.81%   |
| SK hynix HFS256G39TND-N210A 256GB  | 2         | 0.81%   |
| Seagate ST9320423AS 320GB          | 2         | 0.81%   |
| Seagate ST9320325AS 320GB          | 2         | 0.81%   |
| Seagate ST500LT012-9WS142 500GB    | 2         | 0.81%   |
| Seagate ST1000LM035-1RK172 1TB     | 2         | 0.81%   |
| Samsung SSD PM871 2.5 7mm 128GB    | 2         | 0.81%   |
| Samsung SSD 860 EVO 250GB          | 2         | 0.81%   |
| Samsung SSD 850 EVO 500GB          | 2         | 0.81%   |
| Samsung SSD 750 EVO 250GB          | 2         | 0.81%   |
| Samsung MZVLW256HEHP-000L7 256GB   | 2         | 0.81%   |
| Hitachi HTS541680J9SA00 80GB       | 2         | 0.81%   |
| Crucial CT480BX500SSD1 480GB       | 2         | 0.81%   |
| Crucial CT250BX100SSD1 250GB       | 2         | 0.81%   |
| Zheino CHN-25SATAC3-120 120GB      | 1         | 0.4%    |
| Zheino CHN mSATAM1 256 256GB       | 1         | 0.4%    |
| WDC WDS500G2B0C-00PXH0 500GB       | 1         | 0.4%    |
| WDC WDS240G1G0A-00SS50 240GB       | 1         | 0.4%    |
| WDC WDBNCE5000PNC 500GB            | 1         | 0.4%    |
| WDC WD6400BPVT-60HXZT1 640GB       | 1         | 0.4%    |
| WDC WD6400BEVT-22A0RT0 640GB       | 1         | 0.4%    |
| WDC WD5000LPVX-80V0TT0 500GB       | 1         | 0.4%    |
| WDC WD5000LPLX-60ZNTT1 500GB       | 1         | 0.4%    |
| WDC WD5000LPCX-75VHAT0 500GB       | 1         | 0.4%    |
| WDC WD5000BPVT-22HXZT3 500GB       | 1         | 0.4%    |
| WDC WD5000BPKX-22HPJT0 500GB       | 1         | 0.4%    |
| WDC WD3200LPVX-60V0TT0 320GB       | 1         | 0.4%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 31        | 32     | 32.29%  |
| Seagate             | 26        | 31     | 27.08%  |
| Toshiba             | 17        | 17     | 17.71%  |
| Hitachi             | 10        | 10     | 10.42%  |
| HGST                | 6         | 6      | 6.25%   |
| Fujitsu             | 4         | 4      | 4.17%   |
| Samsung Electronics | 2         | 2      | 2.08%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 20        | 21     | 17.54%  |
| Crucial             | 15        | 15     | 13.16%  |
| Kingston            | 14        | 14     | 12.28%  |
| SanDisk             | 11        | 12     | 9.65%   |
| WDC                 | 9         | 9      | 7.89%   |
| Intel               | 6         | 6      | 5.26%   |
| SPCC                | 3         | 4      | 2.63%   |
| Intenso             | 3         | 3      | 2.63%   |
| A-DATA Technology   | 3         | 3      | 2.63%   |
| Zheino              | 2         | 2      | 1.75%   |
| SK hynix            | 2         | 2      | 1.75%   |
| Patriot             | 2         | 2      | 1.75%   |
| KingSpec            | 2         | 2      | 1.75%   |
| Corsair             | 2         | 2      | 1.75%   |
| Transcend           | 1         | 1      | 0.88%   |
| Toshiba             | 1         | 1      | 0.88%   |
| Team                | 1         | 1      | 0.88%   |
| Smartbuy            | 1         | 1      | 0.88%   |
| PNY                 | 1         | 1      | 0.88%   |
| Plextor             | 1         | 1      | 0.88%   |
| Phison              | 1         | 1      | 0.88%   |
| Netac               | 1         | 1      | 0.88%   |
| Mushkin             | 1         | 1      | 0.88%   |
| Micron Technology   | 1         | 1      | 0.88%   |
| LITEON              | 1         | 1      | 0.88%   |
| Lexar               | 1         | 1      | 0.88%   |
| Leven               | 1         | 1      | 0.88%   |
| Integral            | 1         | 1      | 0.88%   |
| INDMEM              | 1         | 1      | 0.88%   |
| Hewlett-Packard     | 1         | 1      | 0.88%   |
| Fujitsu             | 1         | 1      | 0.88%   |
| Apple               | 1         | 1      | 0.88%   |
| Apacer              | 1         | 1      | 0.88%   |
| ANACOMDA            | 1         | 1      | 0.88%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 102       | 117    | 45.13%  |
| HDD  | 90        | 102    | 39.82%  |
| NVMe | 34        | 37     | 15.04%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 181       | 219    | 84.19%  |
| NVMe | 34        | 37     | 15.81%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 149       | 175    | 78.42%  |
| 0.51-1.0   | 36        | 39     | 18.95%  |
| 1.01-2.0   | 4         | 4      | 2.11%   |
| 4.01-10.0  | 1         | 1      | 0.53%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 99        | 47.37%  |
| 101-250    | 51        | 24.4%   |
| 251-500    | 32        | 15.31%  |
| 501-1000   | 15        | 7.18%   |
| 21-50      | 6         | 2.87%   |
| 51-100     | 5         | 2.39%   |
| Unknown    | 1         | 0.48%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 203       | 98.07%  |
| 21-50   | 2         | 0.97%   |
| 101-250 | 1         | 0.48%   |
| Unknown | 1         | 0.48%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB | 2         | 2      | 4%      |
| WDC WD5000LPLX-60ZNTT1 500GB       | 1         | 1      | 2%      |
| WDC WD5000LPCX-75VHAT0 500GB       | 1         | 1      | 2%      |
| WDC WD5000LPCX-60VHAT0 500GB       | 1         | 1      | 2%      |
| WDC WD5000BPVT-22HXZT3 500GB       | 1         | 1      | 2%      |
| WDC WD3200BPVT-80ZEST0 320GB       | 1         | 1      | 2%      |
| WDC WD3200BEVT-60A23T0 320GB       | 1         | 1      | 2%      |
| WDC WD3200BEVT-22ZCT0 320GB        | 1         | 1      | 2%      |
| WDC WD1600BEVT-80A23T0 160GB       | 1         | 1      | 2%      |
| WDC WD1600BEKT-66F3T2 160GB        | 1         | 1      | 2%      |
| WDC WD10SPZX-24Z10T0 1TB           | 1         | 1      | 2%      |
| WDC WD10SPZX-21Z10T0 1TB           | 1         | 1      | 2%      |
| WDC WD10JPVX-22JC3T0 1TB           | 1         | 1      | 2%      |
| Toshiba THNSNX024GMNT 24GB         | 1         | 1      | 2%      |
| Toshiba MQ01ABF050 500GB           | 1         | 1      | 2%      |
| Toshiba MQ01ABD100 1TB             | 1         | 1      | 2%      |
| Toshiba MQ01ABD075 752GB           | 1         | 1      | 2%      |
| Toshiba MK8034GSX 80GB             | 1         | 1      | 2%      |
| Toshiba MK7559GSXF 752GB           | 1         | 1      | 2%      |
| Toshiba MK6034GSX 64GB             | 1         | 1      | 2%      |
| Toshiba MK3265GSXN 320GB           | 1         | 1      | 2%      |
| Toshiba MK3261GSYN 320GB           | 1         | 1      | 2%      |
| Seagate ST9640320AS 640GB          | 1         | 1      | 2%      |
| Seagate ST9500325AS 500GB          | 1         | 1      | 2%      |
| Seagate ST9320423AS 320GB          | 1         | 1      | 2%      |
| Seagate ST9320325AS 320GB          | 1         | 1      | 2%      |
| Seagate ST9160412AS 160GB          | 1         | 1      | 2%      |
| Seagate ST9120821AS 118GB          | 1         | 1      | 2%      |
| Seagate ST500LT012-9WS142 500GB    | 1         | 1      | 2%      |
| Seagate ST320LT020-9YG142 320GB    | 1         | 1      | 2%      |
| Seagate ST320LT007-9ZV142 320GB    | 1         | 1      | 2%      |
| Seagate ST3160212AS 160GB          | 1         | 1      | 2%      |
| Seagate ST1000LM014-1EJ164 1TB     | 1         | 1      | 2%      |
| Samsung Electronics HS082HB 80GB   | 1         | 1      | 2%      |
| Samsung Electronics HM160HI 160GB  | 1         | 1      | 2%      |
| LITEON CV8-8E128-HP 128GB          | 1         | 1      | 2%      |
| Kingston SV300S37A120G 120GB       | 1         | 1      | 2%      |
| Kingston SUV500MS480G 480GB        | 1         | 1      | 2%      |
| Hitachi HTS723216L9SA60 160GB      | 1         | 1      | 2%      |
| Hitachi HTS547564A9E384 640GB      | 1         | 1      | 2%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 13        | 13     | 26%     |
| WDC                 | 12        | 12     | 24%     |
| Toshiba             | 9         | 9      | 18%     |
| Hitachi             | 6         | 6      | 12%     |
| Samsung Electronics | 2         | 2      | 4%      |
| Kingston            | 2         | 2      | 4%      |
| HGST                | 2         | 2      | 4%      |
| LITEON              | 1         | 1      | 2%      |
| Fujitsu             | 1         | 1      | 2%      |
| Corsair             | 1         | 1      | 2%      |
| AGI                 | 1         | 1      | 2%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 13        | 13     | 29.55%  |
| WDC                 | 12        | 12     | 27.27%  |
| Toshiba             | 8         | 8      | 18.18%  |
| Hitachi             | 6         | 6      | 13.64%  |
| Samsung Electronics | 2         | 2      | 4.55%   |
| HGST                | 2         | 2      | 4.55%   |
| Fujitsu             | 1         | 1      | 2.27%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 41        | 44     | 87.23%  |
| SSD  | 5         | 5      | 10.64%  |
| NVMe | 1         | 1      | 2.13%   |

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
| Works    | 159       | 205    | 76.81%  |
| Malfunc  | 47        | 50     | 22.71%  |
| Detected | 1         | 1      | 0.48%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 167       | 72.93%  |
| AMD                              | 23        | 10.04%  |
| Samsung Electronics              | 13        | 5.68%   |
| Nvidia                           | 7         | 3.06%   |
| SanDisk                          | 5         | 2.18%   |
| Micron Technology                | 4         | 1.75%   |
| Silicon Motion                   | 2         | 0.87%   |
| KIOXIA                           | 2         | 0.87%   |
| Kingston Technology Company      | 2         | 0.87%   |
| Solid State Storage Technology   | 1         | 0.44%   |
| Silicon Integrated Systems [SiS] | 1         | 0.44%   |
| Biwin Storage Technology         | 1         | 0.44%   |
| ADATA Technology                 | 1         | 0.44%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 23        | 9.16%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 22        | 8.76%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 20        | 7.97%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 15        | 5.98%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 14        | 5.58%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 13        | 5.18%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 13        | 5.18%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 12        | 4.78%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 9         | 3.59%   |
| Unknown                                                                          | 8         | 3.19%   |
| Nvidia MCP79 AHCI Controller                                                     | 7         | 2.79%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 6         | 2.39%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 6         | 2.39%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 6         | 2.39%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 6         | 2.39%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 5         | 1.99%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 5         | 1.99%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 4         | 1.59%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 4         | 1.59%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 3         | 1.2%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 3         | 1.2%    |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 3         | 1.2%    |
| Intel Comet Lake SATA AHCI Controller                                            | 3         | 1.2%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 3         | 1.2%    |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 2         | 0.8%    |
| Samsung NVMe SSD Controller SM951/PM951                                          | 2         | 0.8%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 2         | 0.8%    |
| Samsung NVMe SSD Controller 980                                                  | 2         | 0.8%    |
| KIOXIA NVMe SSD Controller BG4                                                   | 2         | 0.8%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 2         | 0.8%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 2         | 0.8%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 2         | 0.8%    |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 2         | 0.8%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 0.4%    |
| Silicon Motion SM2262/SM2262EN SSD Controller                                    | 1         | 0.4%    |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 0.4%    |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 1         | 0.4%    |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 1         | 0.4%    |
| SanDisk unknown                                                                  | 1         | 0.4%    |
| SanDisk PC SN530                                                                 | 1         | 0.4%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 184       | 74.8%   |
| NVMe | 33        | 13.41%  |
| IDE  | 22        | 8.94%   |
| RAID | 7         | 2.85%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 180       | 86.96%  |
| AMD    | 27        | 13.04%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz    | 8         | 3.86%   |
| Intel CPU Version                    | 6         | 2.9%    |
| Intel Core i5-7200U CPU @ 2.50GHz    | 5         | 2.42%   |
| Intel Core i5-6300U CPU @ 2.40GHz    | 4         | 1.93%   |
| Intel Core i5-3210M CPU @ 2.50GHz    | 4         | 1.93%   |
| Intel Core i5 CPU M 520 @ 2.40GHz    | 4         | 1.93%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz | 4         | 1.93%   |
| Intel Core i7-3612QM CPU @ 2.10GHz   | 3         | 1.45%   |
| Intel Core i5-5200U CPU @ 2.20GHz    | 3         | 1.45%   |
| Intel Core i5-4300M CPU @ 2.60GHz    | 3         | 1.45%   |
| Intel Core i5-4210U CPU @ 1.70GHz    | 3         | 1.45%   |
| Intel Core i5-3320M CPU @ 2.60GHz    | 3         | 1.45%   |
| Intel Core i3-6006U CPU @ 2.00GHz    | 3         | 1.45%   |
| Intel Core i3-3110M CPU @ 2.40GHz    | 3         | 1.45%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz | 3         | 1.45%   |
| Intel Core 2 Duo CPU P7550 @ 2.26GHz | 3         | 1.45%   |
| Intel Genuine CPU                    | 2         | 0.97%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz   | 2         | 0.97%   |
| Intel Core i7-6500U CPU @ 2.50GHz    | 2         | 0.97%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz   | 2         | 0.97%   |
| Intel Core i7-4600U CPU @ 2.10GHz    | 2         | 0.97%   |
| Intel Core i7-10510U CPU @ 1.80GHz   | 2         | 0.97%   |
| Intel Core i5-9300H CPU @ 2.40GHz    | 2         | 0.97%   |
| Intel Core i5-8250U CPU @ 1.60GHz    | 2         | 0.97%   |
| Intel Core i5-7300U CPU @ 2.60GHz    | 2         | 0.97%   |
| Intel Core i5-6200U CPU @ 2.30GHz    | 2         | 0.97%   |
| Intel Core i5-4200U CPU @ 1.60GHz    | 2         | 0.97%   |
| Intel Core i5-3317U CPU @ 1.70GHz    | 2         | 0.97%   |
| Intel Core i5-2410M CPU @ 2.30GHz    | 2         | 0.97%   |
| Intel Core i5-10300H CPU @ 2.50GHz   | 2         | 0.97%   |
| Intel Core i3-5005U CPU @ 2.00GHz    | 2         | 0.97%   |
| Intel Core i3-4005U CPU @ 1.70GHz    | 2         | 0.97%   |
| Intel Core i3-2310M CPU @ 2.10GHz    | 2         | 0.97%   |
| Intel Core i3 CPU M 330 @ 2.13GHz    | 2         | 0.97%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz | 2         | 0.97%   |
| Intel Core 2 Duo CPU T6600 @ 2.20GHz | 2         | 0.97%   |
| Intel Core 2 Duo                     | 2         | 0.97%   |
| Intel Celeron CPU N3350 @ 1.10GHz    | 2         | 0.97%   |
| Intel Celeron CPU N3060 @ 1.60GHz    | 2         | 0.97%   |
| Intel Atom CPU N450 @ 1.66GHz        | 2         | 0.97%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 66        | 31.88%  |
| Intel Core i7           | 28        | 13.53%  |
| Intel Core 2 Duo        | 26        | 12.56%  |
| Intel Core i3           | 21        | 10.14%  |
| Intel Celeron           | 13        | 6.28%   |
| Other                   | 8         | 3.86%   |
| AMD Ryzen 5             | 8         | 3.86%   |
| Intel Pentium           | 5         | 2.42%   |
| AMD A6                  | 5         | 2.42%   |
| AMD E1                  | 4         | 1.93%   |
| Intel Atom              | 3         | 1.45%   |
| AMD Ryzen 7             | 3         | 1.45%   |
| Intel Pentium Dual-Core | 2         | 0.97%   |
| Intel Genuine           | 2         | 0.97%   |
| Intel Core 2            | 2         | 0.97%   |
| AMD E2                  | 2         | 0.97%   |
| Intel Xeon              | 1         | 0.48%   |
| Intel Pentium Silver    | 1         | 0.48%   |
| Intel Pentium M         | 1         | 0.48%   |
| Intel Pentium Dual      | 1         | 0.48%   |
| Intel Core M            | 1         | 0.48%   |
| Intel Celeron Dual-Core | 1         | 0.48%   |
| AMD Ryzen 3             | 1         | 0.48%   |
| AMD A8                  | 1         | 0.48%   |
| AMD A10                 | 1         | 0.48%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 118       | 57%     |
| 4       | 40        | 19.32%  |
| Unknown | 31        | 14.98%  |
| 8       | 7         | 3.38%   |
| 6       | 7         | 3.38%   |
| 12      | 3         | 1.45%   |
| 1       | 1         | 0.48%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 192       | 92.75%  |
| 2       | 13        | 6.28%   |
| Unknown | 2         | 0.97%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 117       | 56.52%  |
| 1       | 59        | 28.5%   |
| Unknown | 31        | 14.98%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| Penryn      | 27        | 13.04%  |
| IvyBridge   | 26        | 12.56%  |
| KabyLake    | 22        | 10.63%  |
| Haswell     | 19        | 9.18%   |
| Skylake     | 17        | 8.21%   |
| SandyBridge | 16        | 7.73%   |
| Westmere    | 15        | 7.25%   |
| Core        | 12        | 5.8%    |
| Silvermont  | 9         | 4.35%   |
| Broadwell   | 6         | 2.9%    |
| Zen+        | 5         | 2.42%   |
| Zen 2       | 5         | 2.42%   |
| Jaguar      | 4         | 1.93%   |
| CometLake   | 4         | 1.93%   |
| Goldmont    | 3         | 1.45%   |
| Excavator   | 3         | 1.45%   |
| Bonnell     | 3         | 1.45%   |
| Bobcat      | 3         | 1.45%   |
| Zen         | 2         | 0.97%   |
| Puma        | 2         | 0.97%   |
| Zen 3       | 1         | 0.48%   |
| Piledriver  | 1         | 0.48%   |
| K10 Llano   | 1         | 0.48%   |
| Unknown     | 1         | 0.48%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 153       | 62.45%  |
| Nvidia | 46        | 18.78%  |
| AMD    | 46        | 18.78%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 25        | 9.54%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 16        | 6.11%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 13        | 4.96%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 13        | 4.96%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 13        | 4.96%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 11        | 4.2%    |
| Intel Core Processor Integrated Graphics Controller                                      | 11        | 4.2%    |
| Intel HD Graphics 620                                                                    | 8         | 3.05%   |
| Nvidia C79 [GeForce 9400M]                                                               | 6         | 2.29%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 6         | 2.29%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 6         | 2.29%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 5         | 1.91%   |
| Intel HD Graphics 5500                                                                   | 5         | 1.91%   |
| Intel HD Graphics 530                                                                    | 5         | 1.91%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 1.91%   |
| AMD Renoir                                                                               | 5         | 1.91%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 4         | 1.53%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 1.53%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/545v]                                        | 4         | 1.53%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 1.15%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 3         | 1.15%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 3         | 1.15%   |
| Intel UHD Graphics 620                                                                   | 3         | 1.15%   |
| Intel HD Graphics 500                                                                    | 3         | 1.15%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 1.15%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 1.15%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 3         | 1.15%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 3         | 1.15%   |
| Nvidia TU117M                                                                            | 2         | 0.76%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 0.76%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 2         | 0.76%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 2         | 0.76%   |
| Nvidia GF119M [GeForce 610M]                                                             | 2         | 0.76%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 0.76%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 0.76%   |
| AMD Wrestler [Radeon HD 7310]                                                            | 2         | 0.76%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 2         | 0.76%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 2         | 0.76%   |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                             | 2         | 0.76%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 2         | 0.76%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 96        | 46.38%  |
| 1 x AMD        | 32        | 15.46%  |
| Intel + Nvidia | 25        | 12.08%  |
| 2 x Intel      | 23        | 11.11%  |
| 1 x Nvidia     | 16        | 7.73%   |
| Intel + AMD    | 9         | 4.35%   |
| AMD + Nvidia   | 4         | 1.93%   |
| 2 x Nvidia     | 1         | 0.48%   |
| 2 x AMD        | 1         | 0.48%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 184       | 88.89%  |
| Proprietary | 19        | 9.18%   |
| Unknown     | 4         | 1.93%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 158       | 76.33%  |
| 0.01-0.5   | 32        | 15.46%  |
| 0.51-1.0   | 7         | 3.38%   |
| 1.01-2.0   | 5         | 2.42%   |
| 5.01-6.0   | 2         | 0.97%   |
| 3.01-4.0   | 2         | 0.97%   |
| 2.01-3.0   | 1         | 0.48%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 39        | 18.66%  |
| AU Optronics            | 33        | 15.79%  |
| Chimei Innolux          | 31        | 14.83%  |
| Samsung Electronics     | 27        | 12.92%  |
| BOE                     | 21        | 10.05%  |
| Lenovo                  | 18        | 8.61%   |
| Apple                   | 14        | 6.7%    |
| Chi Mei Optoelectronics | 5         | 2.39%   |
| PANDA                   | 3         | 1.44%   |
| Sharp                   | 2         | 0.96%   |
| LG Philips              | 2         | 0.96%   |
| Goldstar                | 2         | 0.96%   |
| Vestel Elektronik       | 1         | 0.48%   |
| Toshiba                 | 1         | 0.48%   |
| Sony                    | 1         | 0.48%   |
| SLD                     | 1         | 0.48%   |
| Philips                 | 1         | 0.48%   |
| Lenovo Group Limited    | 1         | 0.48%   |
| LED                     | 1         | 0.48%   |
| InfoVision              | 1         | 0.48%   |
| BenQ                    | 1         | 0.48%   |
| AOC                     | 1         | 0.48%   |
| Ancor Communications    | 1         | 0.48%   |
| Acer                    | 1         | 0.48%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Lenovo LCD Monitor LEN4031 1280x800 300x190mm 14.0-inch               | 4         | 1.89%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch      | 4         | 1.89%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 340x190mm 15.3-inch  | 3         | 1.42%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 340x190mm 15.3-inch       | 3         | 1.42%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 340x190mm 15.3-inch         | 3         | 1.42%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch  | 2         | 0.94%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 340x190mm 15.3-inch | 2         | 0.94%   |
| LG Display LCD Monitor LGD0459 1920x1080 380x210mm 17.1-inch          | 2         | 0.94%   |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch           | 2         | 0.94%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch           | 2         | 0.94%   |
| LG Display LCD Monitor LGD0250 1366x768 350x190mm 15.7-inch           | 2         | 0.94%   |
| Lenovo LCD Monitor LEN40B0 1366x768 340x190mm 15.3-inch               | 2         | 0.94%   |
| Lenovo LCD Monitor LEN40A0 1366x768 310x170mm 13.9-inch               | 2         | 0.94%   |
| Lenovo LCD Monitor LEN4035 1280x800 300x190mm 14.0-inch               | 2         | 0.94%   |
| Chimei Innolux LCD Monitor CMN1492 1366x768 310x170mm 13.9-inch       | 2         | 0.94%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 310x170mm 13.9-inch       | 2         | 0.94%   |
| AU Optronics LCD Monitor AUO325C 1366x768 260x140mm 11.6-inch         | 2         | 0.94%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 310x170mm 13.9-inch        | 2         | 0.94%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch         | 2         | 0.94%   |
| Apple LCD Monitor APP9C5F 1280x800 290x180mm 13.4-inch                | 2         | 0.94%   |
| Apple Color LCD APP9C5E 1280x800 290x190mm 13.6-inch                  | 2         | 0.94%   |
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 710x400mm 32.1-inch    | 1         | 0.47%   |
| Toshiba TV TSB0108 1360x768 700x390mm 31.5-inch                       | 1         | 0.47%   |
| Sony LCD SNY06FA 1600x900 290x160mm 13.0-inch                         | 1         | 0.47%   |
| SLD LCD Monitor SLD003C 1366x768 310x170mm 13.9-inch                  | 1         | 0.47%   |
| Sharp LQ140Z1JW01 SHP1401 3200x1800 310x170mm 13.9-inch               | 1         | 0.47%   |
| Sharp LCD Monitor SHP14BA 1920x1080 340x190mm 15.3-inch               | 1         | 0.47%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 610x350mm 27.7-inch     | 1         | 0.47%   |
| Samsung Electronics S27C350 SAM0A3E 1920x1080 600x340mm 27.2-inch     | 1         | 0.47%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch     | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 410x230mm 18.5-inch | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC4E41 1280x800 260x160mm 12.0-inch  | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC4542 1280x800 300x190mm 14.0-inch  | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC384A 1366x768 340x190mm 15.3-inch  | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC3847 1440x900 370x230mm 17.2-inch  | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC334A 1366x768 340x190mm 15.3-inch  | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 340x190mm 15.3-inch  | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC3157 1280x800 300x190mm 14.0-inch  | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 340x190mm 15.3-inch | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC3052 1024x600 220x130mm 10.1-inch  | 1         | 0.47%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 98        | 47.57%  |
| 1920x1080 (FHD)   | 51        | 24.76%  |
| 1280x800 (WXGA)   | 26        | 12.62%  |
| 1600x900 (HD+)    | 11        | 5.34%   |
| 1440x900 (WXGA+)  | 4         | 1.94%   |
| 3840x2160 (4K)    | 3         | 1.46%   |
| 1024x768 (XGA)    | 3         | 1.46%   |
| 2560x1440 (QHD)   | 2         | 0.97%   |
| 1920x540          | 2         | 0.97%   |
| 1024x600          | 2         | 0.97%   |
| 3200x1800 (QHD+)  | 1         | 0.49%   |
| 2560x1080         | 1         | 0.49%   |
| 1920x1200 (WUXGA) | 1         | 0.49%   |
| 1280x1024 (SXGA)  | 1         | 0.49%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 81        | 38.21%  |
| 13      | 60        | 28.3%   |
| 12      | 16        | 7.55%   |
| 14      | 12        | 5.66%   |
| 17      | 11        | 5.19%   |
| 11      | 6         | 2.83%   |
| 27      | 4         | 1.89%   |
| 24      | 3         | 1.42%   |
| 23      | 3         | 1.42%   |
| 10      | 3         | 1.42%   |
| 18      | 2         | 0.94%   |
| 64      | 1         | 0.47%   |
| 54      | 1         | 0.47%   |
| 42      | 1         | 0.47%   |
| 40      | 1         | 0.47%   |
| 34      | 1         | 0.47%   |
| 31      | 1         | 0.47%   |
| 21      | 1         | 0.47%   |
| 20      | 1         | 0.47%   |
| 19      | 1         | 0.47%   |
| 16      | 1         | 0.47%   |
| Unknown | 1         | 0.47%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 122       | 57.55%  |
| 201-300     | 56        | 26.42%  |
| 351-400     | 13        | 6.13%   |
| 501-600     | 9         | 4.25%   |
| 401-500     | 4         | 1.89%   |
| 601-700     | 2         | 0.94%   |
| 1001-1500   | 2         | 0.94%   |
| 801-900     | 1         | 0.47%   |
| 701-800     | 1         | 0.47%   |
| 901-1000    | 1         | 0.47%   |
| Unknown     | 1         | 0.47%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 158       | 79.4%   |
| 16/10   | 30        | 15.08%  |
| 3/2     | 5         | 2.51%   |
| 4/3     | 3         | 1.51%   |
| 5/4     | 1         | 0.5%    |
| 21/9    | 1         | 0.5%    |
| Unknown | 1         | 0.5%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 91-100         | 65        | 30.66%  |
| 81-90          | 64        | 30.19%  |
| 61-70          | 17        | 8.02%   |
| 101-110        | 17        | 8.02%   |
| 121-130        | 9         | 4.25%   |
| 71-80          | 7         | 3.3%    |
| 201-250        | 6         | 2.83%   |
| 51-60          | 5         | 2.36%   |
| 301-350        | 4         | 1.89%   |
| 41-50          | 3         | 1.42%   |
| More than 1000 | 2         | 0.94%   |
| 351-500        | 2         | 0.94%   |
| 151-200        | 2         | 0.94%   |
| 141-150        | 2         | 0.94%   |
| 131-140        | 2         | 0.94%   |
| 501-1000       | 2         | 0.94%   |
| 251-300        | 1         | 0.47%   |
| 111-120        | 1         | 0.47%   |
| Unknown        | 1         | 0.47%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 98        | 47.12%  |
| 121-160       | 75        | 36.06%  |
| 51-100        | 30        | 14.42%  |
| 161-240       | 3         | 1.44%   |
| More than 240 | 1         | 0.48%   |
| Unknown       | 1         | 0.48%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 183       | 87.98%  |
| 2     | 19        | 9.13%   |
| 0     | 6         | 2.88%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 106       | 30.64%  |
| Realtek Semiconductor             | 96        | 27.75%  |
| Qualcomm Atheros                  | 53        | 15.32%  |
| Broadcom                          | 39        | 11.27%  |
| Marvell Technology Group          | 12        | 3.47%   |
| Nvidia                            | 7         | 2.02%   |
| Ralink                            | 4         | 1.16%   |
| Xiaomi                            | 3         | 0.87%   |
| JMicron Technology                | 3         | 0.87%   |
| Sierra Wireless                   | 2         | 0.58%   |
| Ralink Technology                 | 2         | 0.58%   |
| NetGear                           | 2         | 0.58%   |
| Ericsson Business Mobile Networks | 2         | 0.58%   |
| Edimax Technology                 | 2         | 0.58%   |
| Dell                              | 2         | 0.58%   |
| D-Link System                     | 2         | 0.58%   |
| TP-Link                           | 1         | 0.29%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.29%   |
| Samsung Electronics               | 1         | 0.29%   |
| OPPO Electronics                  | 1         | 0.29%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.29%   |
| Mercucys                          | 1         | 0.29%   |
| Huawei Technologies               | 1         | 0.29%   |
| Hewlett-Packard                   | 1         | 0.29%   |
| Google                            | 1         | 0.29%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 69        | 15.94%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 21        | 4.85%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 16        | 3.7%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 15        | 3.46%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 14        | 3.23%   |
| Intel Wireless 8260                                                     | 12        | 2.77%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 9         | 2.08%   |
| Intel Wireless 7260                                                     | 9         | 2.08%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 8         | 1.85%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 8         | 1.85%   |
| Nvidia MCP79 Ethernet                                                   | 7         | 1.62%   |
| Intel Centrino Advanced-N 6200                                          | 7         | 1.62%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 6         | 1.39%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 6         | 1.39%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 6         | 1.39%   |
| Intel 82577LM Gigabit Network Connection                                | 6         | 1.39%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 6         | 1.39%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 5         | 1.15%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                 | 5         | 1.15%   |
| Intel Wireless 8265 / 8275                                              | 5         | 1.15%   |
| Intel Wireless 7265                                                     | 5         | 1.15%   |
| Intel WiFi Link 5100                                                    | 5         | 1.15%   |
| Intel Wi-Fi 6 AX200                                                     | 5         | 1.15%   |
| Intel Ethernet Connection I219-LM                                       | 5         | 1.15%   |
| Intel 82566MM Gigabit Network Connection                                | 5         | 1.15%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 5         | 1.15%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 0.92%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 4         | 0.92%   |
| Realtek Realtek Bluetooth 4.2 Adapter                                   | 4         | 0.92%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 4         | 0.92%   |
| Intel Ethernet Connection I218-LM                                       | 4         | 0.92%   |
| Intel Ethernet Connection I217-LM                                       | 4         | 0.92%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 4         | 0.92%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 4         | 0.92%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 4         | 0.92%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 0.92%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3         | 0.69%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 3         | 0.69%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 0.69%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                  | 3         | 0.69%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 105       | 46.88%  |
| Qualcomm Atheros      | 50        | 22.32%  |
| Realtek Semiconductor | 30        | 13.39%  |
| Broadcom              | 24        | 10.71%  |
| Ralink                | 4         | 1.79%   |
| Ralink Technology     | 2         | 0.89%   |
| NetGear               | 2         | 0.89%   |
| Edimax Technology     | 2         | 0.89%   |
| TP-Link               | 1         | 0.45%   |
| Sierra Wireless       | 1         | 0.45%   |
| Mercucys              | 1         | 0.45%   |
| Dell                  | 1         | 0.45%   |
| D-Link System         | 1         | 0.45%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 16        | 6.96%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 14        | 6.09%   |
| Intel Wireless 8260                                                     | 12        | 5.22%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 9         | 3.91%   |
| Intel Wireless 7260                                                     | 9         | 3.91%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 8         | 3.48%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 8         | 3.48%   |
| Intel Centrino Advanced-N 6200                                          | 7         | 3.04%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 6         | 2.61%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 6         | 2.61%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 6         | 2.61%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 6         | 2.61%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 5         | 2.17%   |
| Intel Wireless 8265 / 8275                                              | 5         | 2.17%   |
| Intel Wireless 7265                                                     | 5         | 2.17%   |
| Intel WiFi Link 5100                                                    | 5         | 2.17%   |
| Intel Wi-Fi 6 AX200                                                     | 5         | 2.17%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 5         | 2.17%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 1.74%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 4         | 1.74%   |
| Realtek Realtek Bluetooth 4.2 Adapter                                   | 4         | 1.74%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 4         | 1.74%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 4         | 1.74%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 4         | 1.74%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 4         | 1.74%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 1.74%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3         | 1.3%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 1.3%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 1.3%    |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 1.3%    |
| Intel Centrino Advanced-N 6235                                          | 3         | 1.3%    |
| Broadcom BCM43224 802.11a/b/g/n                                         | 3         | 1.3%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.87%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 2         | 0.87%   |
| Realtek 802.11n WLAN Adapter                                            | 2         | 0.87%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 0.87%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 2         | 0.87%   |
| Intel Ultimate N WiFi Link 5300                                         | 2         | 0.87%   |
| Intel Centrino Ultimate-N 6300                                          | 2         | 0.87%   |
| Broadcom BCM43142 802.11b/g/n                                           | 2         | 0.87%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 90        | 45.92%  |
| Intel                            | 51        | 26.02%  |
| Broadcom                         | 15        | 7.65%   |
| Marvell Technology Group         | 12        | 6.12%   |
| Qualcomm Atheros                 | 10        | 5.1%    |
| Nvidia                           | 7         | 3.57%   |
| Xiaomi                           | 3         | 1.53%   |
| JMicron Technology               | 3         | 1.53%   |
| Silicon Integrated Systems [SiS] | 1         | 0.51%   |
| Samsung Electronics              | 1         | 0.51%   |
| OPPO Electronics                 | 1         | 0.51%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.51%   |
| Google                           | 1         | 0.51%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 69        | 35.2%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 21        | 10.71%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 15        | 7.65%   |
| Nvidia MCP79 Ethernet                                             | 7         | 3.57%   |
| Intel 82577LM Gigabit Network Connection                          | 6         | 3.06%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 5         | 2.55%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 2.55%   |
| Intel 82566MM Gigabit Network Connection                          | 5         | 2.55%   |
| Intel Ethernet Connection I218-LM                                 | 4         | 2.04%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 2.04%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 1.53%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 3         | 1.53%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 1.53%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 3         | 1.53%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 1.02%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 1.02%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 1.02%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 2         | 1.02%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 2         | 1.02%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.02%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express          | 2         | 1.02%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 2         | 1.02%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 2         | 1.02%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 2         | 1.02%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.51%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.51%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.51%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.51%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.51%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.51%   |
| OPPO SDM720G-IDP _SN:8A58D65F RNDIS Control RNDIS Ethernet Data   | 1         | 0.51%   |
| OnePlus (Shenzhen) OnePlus RNDIS Control RNDIS Ethernet Data      | 1         | 0.51%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 0.51%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller             | 1         | 0.51%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller              | 1         | 0.51%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.51%   |
| Intel Ethernet Connection I218-V                                  | 1         | 0.51%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.51%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 0.51%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.51%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 206       | 50.99%  |
| Ethernet | 191       | 47.28%  |
| Unknown  | 4         | 0.99%   |
| Modem    | 3         | 0.74%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 133       | 50%     |
| Ethernet | 129       | 48.5%   |
| Unknown  | 3         | 1.13%   |
| Modem    | 1         | 0.38%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 187       | 90.34%  |
| 1     | 19        | 9.18%   |
| 0     | 1         | 0.48%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 198       | 95.65%  |
| Yes  | 9         | 4.35%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 52        | 37.14%  |
| Broadcom                        | 18        | 12.86%  |
| Qualcomm Atheros Communications | 14        | 10%     |
| Apple                           | 13        | 9.29%   |
| Realtek Semiconductor           | 12        | 8.57%   |
| Lite-On Technology              | 7         | 5%      |
| Hewlett-Packard                 | 5         | 3.57%   |
| Foxconn / Hon Hai               | 5         | 3.57%   |
| Ralink                          | 4         | 2.86%   |
| Dell                            | 4         | 2.86%   |
| IMC Networks                    | 3         | 2.14%   |
| Cambridge Silicon Radio         | 3         | 2.14%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 30        | 21.13%  |
| Broadcom BCM2045B (BDC-2.1)                                 | 8         | 5.63%   |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                     | 6         | 4.23%   |
| Apple Bluetooth Host Controller                             | 6         | 4.23%   |
| Intel AX201 Bluetooth                                       | 5         | 3.52%   |
| Intel AX200 Bluetooth                                       | 5         | 3.52%   |
| Apple Built-in iSight (no firmware loaded)                  | 5         | 3.52%   |
| Ralink RT3290 Bluetooth                                     | 4         | 2.82%   |
| Lite-On Atheros AR3012 Bluetooth                            | 4         | 2.82%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 4         | 2.82%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 4         | 2.82%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 4         | 2.82%   |
| Realtek  Bluetooth 4.2 Adapter                              | 3         | 2.11%   |
| Realtek  Bluetooth 4.0 Adapter                              | 3         | 2.11%   |
| Intel Wireless-AC 3168 Bluetooth                            | 3         | 2.11%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 3         | 2.11%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 3         | 2.11%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 3         | 2.11%   |
| Realtek RTL8723B Bluetooth                                  | 2         | 1.41%   |
| Realtek Bluetooth Radio                                     | 2         | 1.41%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 2         | 1.41%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 2         | 1.41%   |
| Foxconn / Hon Hai Qualcomm Atheros Bluetooth 4.0            | 2         | 1.41%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 2         | 1.41%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 2         | 1.41%   |
| Realtek RTL8821A Bluetooth                                  | 1         | 0.7%    |
| Realtek  Bluetooth Adapter                                  | 1         | 0.7%    |
| Realtek  Bluetooth 4.0 + High Speed Chip                    | 1         | 0.7%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 1         | 0.7%    |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1         | 0.7%    |
| Qualcomm Atheros AR3012 Bluetooth                           | 1         | 0.7%    |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)             | 1         | 0.7%    |
| Lite-On Realtek Bluetooth Adapter                           | 1         | 0.7%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 1         | 0.7%    |
| Lite-On Qualcomm Atheros Bluetooth                          | 1         | 0.7%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 1         | 0.7%    |
| IMC Networks Realtek Bluetooth Adapter                      | 1         | 0.7%    |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS            | 1         | 0.7%    |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 1         | 0.7%    |
| HP Broadcom 2070 Bluetooth Combo                            | 1         | 0.7%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 171       | 73.39%  |
| AMD                              | 35        | 15.02%  |
| Nvidia                           | 21        | 9.01%   |
| Texas Instruments                | 2         | 0.86%   |
| GN Netcom                        | 2         | 0.86%   |
| Silicon Integrated Systems [SiS] | 1         | 0.43%   |
| Creative Technology              | 1         | 0.43%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 27        | 9.57%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 23        | 8.16%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 15        | 5.32%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 15        | 5.32%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 15        | 5.32%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 13        | 4.61%   |
| Intel 8 Series HD Audio Controller                                                                | 13        | 4.61%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 13        | 4.61%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 12        | 4.26%   |
| AMD FCH Azalia Controller                                                                         | 11        | 3.9%    |
| Nvidia MCP79 High Definition Audio                                                                | 7         | 2.48%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 6         | 2.13%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 6         | 2.13%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 2.13%   |
| Intel Broadwell-U Audio Controller                                                                | 6         | 2.13%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 6         | 2.13%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 6         | 2.13%   |
| AMD Kabini HDMI/DP Audio                                                                          | 6         | 2.13%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 5         | 1.77%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 5         | 1.77%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 1.77%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 5         | 1.77%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 1.42%   |
| Intel Comet Lake PCH cAVS                                                                         | 4         | 1.42%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 1.42%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 4         | 1.42%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 3         | 1.06%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 1.06%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3         | 1.06%   |
| AMD Wrestler HDMI Audio                                                                           | 3         | 1.06%   |
| AMD High Definition Audio Controller                                                              | 3         | 1.06%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 1.06%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 0.71%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 0.71%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 1         | 0.35%   |
| Texas Instruments PCM2900 Audio Codec                                                             | 1         | 0.35%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 0.35%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.35%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 1         | 0.35%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.35%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 63        | 26.14%  |
| SK hynix                     | 40        | 16.6%   |
| Kingston                     | 32        | 13.28%  |
| Micron Technology            | 20        | 8.3%    |
| Unknown                      | 17        | 7.05%   |
| Ramaxel Technology           | 9         | 3.73%   |
| Nanya Technology             | 8         | 3.32%   |
| Crucial                      | 8         | 3.32%   |
| Elpida                       | 7         | 2.9%    |
| Unknown                      | 7         | 2.9%    |
| A-DATA Technology            | 5         | 2.07%   |
| Smart                        | 4         | 1.66%   |
| Transcend                    | 2         | 0.83%   |
| Silicon Power                | 2         | 0.83%   |
| ASint Technology             | 2         | 0.83%   |
| 48spaces                     | 2         | 0.83%   |
| Unknown (ABCD)               | 1         | 0.41%   |
| Unknown (8AFD)               | 1         | 0.41%   |
| Unknown (0x3D7F000000000000) | 1         | 0.41%   |
| Unknown (0x0809)             | 1         | 0.41%   |
| Smart Brazil                 | 1         | 0.41%   |
| Sesame                       | 1         | 0.41%   |
| PNY                          | 1         | 0.41%   |
| Kingmax                      | 1         | 0.41%   |
| High Bridge                  | 1         | 0.41%   |
| GOODRAM                      | 1         | 0.41%   |
| Corsair                      | 1         | 0.41%   |
| Avant                        | 1         | 0.41%   |
| Apacer                       | 1         | 0.41%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                                | 7         | 2.71%   |
| Unknown                                                                   | 7         | 2.71%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 5         | 1.94%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s                     | 5         | 1.94%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                                | 4         | 1.55%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 4         | 1.55%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 4         | 1.55%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 4         | 1.55%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s                     | 4         | 1.55%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s                     | 4         | 1.55%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s                     | 3         | 1.16%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s                    | 3         | 1.16%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s                     | 3         | 1.16%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s                     | 3         | 1.16%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s                     | 3         | 1.16%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2400MT/s                     | 3         | 1.16%   |
| Ramaxel RAM RMT3170EB68F9W1600 4GB SODIMM DDR3 1600MT/s                   | 3         | 1.16%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s                   | 3         | 1.16%   |
| Unknown RAM Module 4GB SODIMM DDR3                                        | 2         | 0.78%   |
| Unknown RAM Module 2GB SODIMM DDR2                                        | 2         | 0.78%   |
| SK hynix RAM HMT451S6MFR8A-PB 4GB SODIMM DDR3 800MT/s                     | 2         | 0.78%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s                    | 2         | 0.78%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s                    | 2         | 0.78%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 1333MT/s                     | 2         | 0.78%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                     | 2         | 0.78%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s                    | 2         | 0.78%   |
| Ramaxel RAM RMSA3300ME78HBF-2666 16GB SODIMM DDR4 2667MT/s                | 2         | 0.78%   |
| Nanya RAM Module 1GB SODIMM DDR2 667MT/s                                  | 2         | 0.78%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s                     | 2         | 0.78%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                      | 2         | 0.78%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s                    | 2         | 0.78%   |
| Kingston RAM Module 2GB SODIMM DDR2 667MT/s                               | 2         | 0.78%   |
| Kingston RAM 99U5295-013.A00LF 2GB SODIMM DDR 667MT/s                     | 2         | 0.78%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1333MT/s                     | 2         | 0.78%   |
| A-DATA RAM AM1L16BC4R1-B1GS 4GB SODIMM DDR3 1333MT/s                      | 2         | 0.78%   |
| 48spaces RAM 012345678901234567890123456789012345 2GB SODIMM DDR2 667MT/s | 2         | 0.78%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                               | 1         | 0.39%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                               | 1         | 0.39%   |
| Unknown RAM Module 4GB SODIMM DDR2 667MT/s                                | 1         | 0.39%   |
| Unknown RAM Module 2GB SODIMM DDR3 1067MT/s                               | 1         | 0.39%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 114       | 56.16%  |
| DDR4    | 51        | 25.12%  |
| DDR2    | 28        | 13.79%  |
| Unknown | 3         | 1.48%   |
| LPDDR4  | 2         | 0.99%   |
| LPDDR3  | 2         | 0.99%   |
| SDRAM   | 1         | 0.49%   |
| DRAM    | 1         | 0.49%   |
| DDR     | 1         | 0.49%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 196       | 97.03%  |
| Row Of Chips | 3         | 1.49%   |
| Chip         | 2         | 0.99%   |
| DIMM         | 1         | 0.5%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 80        | 35.24%  |
| 2048  | 61        | 26.87%  |
| 8192  | 58        | 25.55%  |
| 16384 | 15        | 6.61%   |
| 1024  | 11        | 4.85%   |
| 32768 | 2         | 0.88%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 66        | 29.6%   |
| 1333    | 24        | 10.76%  |
| 2667    | 23        | 10.31%  |
| 667     | 23        | 10.31%  |
| 1334    | 15        | 6.73%   |
| 1067    | 13        | 5.83%   |
| 2400    | 12        | 5.38%   |
| 3200    | 11        | 4.93%   |
| 2133    | 11        | 4.93%   |
| 800     | 7         | 3.14%   |
| 1867    | 6         | 2.69%   |
| Unknown | 6         | 2.69%   |
| 975     | 3         | 1.35%   |
| 4267    | 1         | 0.45%   |
| 1066    | 1         | 0.45%   |
| 533     | 1         | 0.45%   |

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
| Chicony Electronics                    | 42        | 28.57%  |
| Realtek Semiconductor                  | 14        | 9.52%   |
| Microdia                               | 12        | 8.16%   |
| Acer                                   | 11        | 7.48%   |
| IMC Networks                           | 10        | 6.8%    |
| Quanta                                 | 9         | 6.12%   |
| Suyin                                  | 7         | 4.76%   |
| Sunplus Innovation Technology          | 7         | 4.76%   |
| Lite-On Technology                     | 7         | 4.76%   |
| Syntek                                 | 6         | 4.08%   |
| Alcor Micro                            | 4         | 2.72%   |
| Z-Star Microelectronics                | 3         | 2.04%   |
| Lenovo                                 | 3         | 2.04%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 1.36%   |
| ALi                                    | 2         | 1.36%   |
| Silicon Motion                         | 1         | 0.68%   |
| Ricoh                                  | 1         | 0.68%   |
| Primax Electronics                     | 1         | 0.68%   |
| Luxvisions Innotech Limited            | 1         | 0.68%   |
| Importek                               | 1         | 0.68%   |
| icSpring                               | 1         | 0.68%   |
| DigiTech                               | 1         | 0.68%   |
| Apple                                  | 1         | 0.68%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Chicony HD WebCam                         | 6         | 4.05%   |
| Chicony Lenovo Integrated Camera (0.3MP)  | 5         | 3.38%   |
| Syntek Lenovo EasyCamera                  | 4         | 2.7%    |
| Realtek Integrated_Webcam_HD              | 4         | 2.7%    |
| Lite-On Integrated Camera                 | 4         | 2.7%    |
| Chicony Integrated Camera                 | 4         | 2.7%    |
| Realtek USB Camera                        | 3         | 2.03%   |
| Realtek Realtek USB2.0 PC Camera          | 3         | 2.03%   |
| Quanta HP TrueVision HD Camera            | 3         | 2.03%   |
| Microdia Integrated_Webcam_HD             | 3         | 2.03%   |
| Microdia Integrated Webcam                | 3         | 2.03%   |
| IMC Networks USB2.0 HD UVC WebCam         | 3         | 2.03%   |
| IMC Networks Integrated Camera            | 3         | 2.03%   |
| Chicony HD WebCam (Acer)                  | 3         | 2.03%   |
| Chicony EasyCamera                        | 3         | 2.03%   |
| Acer Integrated Camera                    | 3         | 2.03%   |
| Z-Star WebCam SC-03FFL11739P              | 2         | 1.35%   |
| Syntek EasyCamera                         | 2         | 1.35%   |
| Suyin Integrated_Webcam_HD                | 2         | 1.35%   |
| Suyin HD Video WebCam                     | 2         | 1.35%   |
| Sunplus HD WebCam                         | 2         | 1.35%   |
| Quanta Realtek DMFT - RGB                 | 2         | 1.35%   |
| Quanta HP Webcam                          | 2         | 1.35%   |
| Microdia Sonix USB 2.0 Camera             | 2         | 1.35%   |
| Microdia Dell Laptop Integrated Webcam HD | 2         | 1.35%   |
| Lite-On HP HD Camera                      | 2         | 1.35%   |
| Lenovo Integrated Webcam [R5U877]         | 2         | 1.35%   |
| Chicony Realtek DMFT - RGB                | 2         | 1.35%   |
| Chicony HP HD Webcam [Fixed]              | 2         | 1.35%   |
| Chicony Chicony USB 2.0 Camera            | 2         | 1.35%   |
| ALi Gateway Webcam                        | 2         | 1.35%   |
| Acer SunplusIT INC. Integrated Camera     | 2         | 1.35%   |
| Acer Lenovo EasyCamera                    | 2         | 1.35%   |
| Z-Star Webcam                             | 1         | 0.68%   |
| Suyin Laptop_Integrated_Webcam_FHD        | 1         | 0.68%   |
| Suyin HP webcam [dv6-1190en]              | 1         | 0.68%   |
| Suyin Acer/HP Integrated Webcam [CN0314]  | 1         | 0.68%   |
| Sunplus Laptop_Integrated_Webcam_FHD      | 1         | 0.68%   |
| Sunplus Integrated_Webcam_HD              | 1         | 0.68%   |
| Sunplus Integrated Camera                 | 1         | 0.68%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 16        | 37.21%  |
| Upek                       | 11        | 25.58%  |
| AuthenTec                  | 7         | 16.28%  |
| STMicroelectronics         | 4         | 9.3%    |
| Shenzhen Goodix Technology | 2         | 4.65%   |
| LighTuning Technology      | 2         | 4.65%   |
| Synaptics                  | 1         | 2.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 9         | 20.93%  |
| STMicroelectronics Fingerprint Reader                  | 4         | 9.3%    |
| Validity Sensors VFS491                                | 3         | 6.98%   |
| Validity Sensors VFS5011 Fingerprint Reader            | 2         | 4.65%   |
| Validity Sensors VFS495 Fingerprint Reader             | 2         | 4.65%   |
| Validity Sensors VFS471 Fingerprint Reader             | 2         | 4.65%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 2         | 4.65%   |
| Validity Sensors Synaptics WBDI                        | 2         | 4.65%   |
| Upek TCS5B Fingerprint sensor                          | 2         | 4.65%   |
| Shenzhen Goodix Fingerprint Reader                     | 2         | 4.65%   |
| AuthenTec AES2501 Fingerprint Sensor                   | 2         | 4.65%   |
| AuthenTec AES1600                                      | 2         | 4.65%   |
| Validity Sensors VFS101 Fingerprint Reader             | 1         | 2.33%   |
| Validity Sensors Swipe Fingerprint Sensor              | 1         | 2.33%   |
| Validity Sensors Fingerprint scanner                   | 1         | 2.33%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 1         | 2.33%   |
| LighTuning ES603 Swipe Fingerprint Sensor              | 1         | 2.33%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 2.33%   |
| AuthenTec AuthenTec Inc. AES1660                       | 1         | 2.33%   |
| AuthenTec AES2810                                      | 1         | 2.33%   |
| AuthenTec AES1660 Fingerprint Sensor                   | 1         | 2.33%   |

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
| 1     | 71        | 34.13%  |
| 2     | 62        | 29.81%  |
| 0     | 39        | 18.75%  |
| 3     | 27        | 12.98%  |
| 4     | 9         | 4.33%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 128       | 43.39%  |
| Net/wireless             | 53        | 17.97%  |
| Fingerprint reader       | 41        | 13.9%   |
| Bluetooth                | 36        | 12.2%   |
| Card reader              | 32        | 10.85%  |
| Storage                  | 3         | 1.02%   |
| Sound                    | 1         | 0.34%   |
| Network                  | 1         | 0.34%   |

