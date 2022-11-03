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

Total: 213

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
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
| amd64 | 186       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 184       | 98.92%  |
| GNOME        | 2         | 1.08%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 186       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| SLiM | 186       | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 175       | 93.58%  |
| fr_FR | 3         | 1.6%    |
| es_ES | 3         | 1.6%    |
| C     | 3         | 1.6%    |
| uk_UA | 1         | 0.53%   |
| it_IT | 1         | 0.53%   |
| de_DE | 1         | 0.53%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 182       | 97.85%  |
| BIOS | 4         | 2.15%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Zfs    | 94        | 50%     |
| Cd9660 | 94        | 50%     |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 185       | 99.46%  |
| MBR  | 1         | 0.54%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 59        | 31.72%  |
| Hewlett-Packard     | 31        | 16.67%  |
| Dell                | 23        | 12.37%  |
| Acer                | 19        | 10.22%  |
| Apple               | 12        | 6.45%   |
| ASUSTek Computer    | 10        | 5.38%   |
| Toshiba             | 6         | 3.23%   |
| Samsung Electronics | 4         | 2.15%   |
| TUXEDO              | 3         | 1.61%   |
| Sony                | 2         | 1.08%   |
| MSI                 | 2         | 1.08%   |
| Fujitsu             | 2         | 1.08%   |
| TWINHEAD            | 1         | 0.54%   |
| Razer               | 1         | 0.54%   |
| Panasonic           | 1         | 0.54%   |
| Packard Bell        | 1         | 0.54%   |
| Notebook            | 1         | 0.54%   |
| LG Electronics      | 1         | 0.54%   |
| Itautec             | 1         | 0.54%   |
| HASEE Computer      | 1         | 0.54%   |
| Gateway             | 1         | 0.54%   |
| eMachines           | 1         | 0.54%   |
| DNS                 | 1         | 0.54%   |
| Alienware           | 1         | 0.54%   |
| Unknown             | 1         | 0.54%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                               | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Apple MacBook4,1                                   | 4         | 2.15%   |
| TUXEDO Aura 15 Gen1                                | 2         | 1.08%   |
| HP ProBook 4540s                                   | 2         | 1.08%   |
| Dell Precision 7710                                | 2         | 1.08%   |
| Dell Latitude E5470                                | 2         | 1.08%   |
| Apple MacBook6,1                                   | 2         | 1.08%   |
| Acer V5-131                                        | 2         | 1.08%   |
| Acer Aspire E1-522                                 | 2         | 1.08%   |
| Acer Aspire 5930                                   | 2         | 1.08%   |
| TWINHEAD U12CT                                     | 1         | 0.54%   |
| TUXEDO InfinityBook13V3                            | 1         | 0.54%   |
| Toshiba Satellite S55t-B                           | 1         | 0.54%   |
| Toshiba Satellite P300                             | 1         | 0.54%   |
| Toshiba Satellite L550                             | 1         | 0.54%   |
| Toshiba Satellite C640                             | 1         | 0.54%   |
| Toshiba Satellite C50-B                            | 1         | 0.54%   |
| Toshiba PORTEGE R700                               | 1         | 0.54%   |
| Sony VGN-NW25GF_S                                  | 1         | 0.54%   |
| Sony SVZ1311C5E                                    | 1         | 0.54%   |
| Samsung Q430/Q530                                  | 1         | 0.54%   |
| Samsung N150P/N210P/N220P                          | 1         | 0.54%   |
| Samsung N100                                       | 1         | 0.54%   |
| Samsung 305E4A/305E5A/305E7A                       | 1         | 0.54%   |
| Razer Blade 15 Base Model (Early 2020) - RZ09-0328 | 1         | 0.54%   |
| Panasonic CF-B11JWCYS                              | 1         | 0.54%   |
| Packard Bell EasyNote TE69HW                       | 1         | 0.54%   |
| Notebook N15_17RD                                  | 1         | 0.54%   |
| MSI GF65 Thin 10SER                                | 1         | 0.54%   |
| MSI GF63 Thin 10SC                                 | 1         | 0.54%   |
| LG E300-A.CP20T                                    | 1         | 0.54%   |
| Lenovo Z50-70 20354                                | 1         | 0.54%   |
| Lenovo V310-14IKB 80T2                             | 1         | 0.54%   |
| Lenovo ThinkPad X61 Tablet 7763AD6                 | 1         | 0.54%   |
| Lenovo ThinkPad X61 7675K2U                        | 1         | 0.54%   |
| Lenovo ThinkPad X270 W10DG 20K5S0BM01              | 1         | 0.54%   |
| Lenovo ThinkPad X270 20HMS2LL00                    | 1         | 0.54%   |
| Lenovo ThinkPad X260 20F5S45W00                    | 1         | 0.54%   |
| Lenovo ThinkPad X250 20CLS1WP01                    | 1         | 0.54%   |
| Lenovo ThinkPad X240 20AMS2QDOC                    | 1         | 0.54%   |
| Lenovo ThinkPad X220 Tablet 4298B65                | 1         | 0.54%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 40        | 21.51%  |
| Acer Aspire             | 15        | 8.06%   |
| Dell Latitude           | 11        | 5.91%   |
| HP Pavilion             | 9         | 4.84%   |
| Lenovo IdeaPad          | 8         | 4.3%    |
| HP ProBook              | 7         | 3.76%   |
| Dell Inspiron           | 6         | 3.23%   |
| Toshiba Satellite       | 5         | 2.69%   |
| HP Laptop               | 4         | 2.15%   |
| Apple MacBook4          | 4         | 2.15%   |
| HP EliteBook            | 3         | 1.61%   |
| Dell Precision          | 3         | 1.61%   |
| TUXEDO Aura             | 2         | 1.08%   |
| Lenovo Legion           | 2         | 1.08%   |
| HP Compaq               | 2         | 1.08%   |
| Fujitsu LIFEBOOK        | 2         | 1.08%   |
| Apple MacBookPro5       | 2         | 1.08%   |
| Apple MacBook6          | 2         | 1.08%   |
| Apple MacBook5          | 2         | 1.08%   |
| Acer V5-131             | 2         | 1.08%   |
| TWINHEAD U12CT          | 1         | 0.54%   |
| TUXEDO InfinityBook13V3 | 1         | 0.54%   |
| Toshiba PORTEGE         | 1         | 0.54%   |
| Sony VGN-NW25GF         | 1         | 0.54%   |
| Sony SVZ1311C5E         | 1         | 0.54%   |
| Samsung Q430            | 1         | 0.54%   |
| Samsung N150P           | 1         | 0.54%   |
| Samsung N100            | 1         | 0.54%   |
| Samsung 305E4A          | 1         | 0.54%   |
| Razer Blade             | 1         | 0.54%   |
| Panasonic CF-B11JWCYS   | 1         | 0.54%   |
| Packard Bell EasyNote   | 1         | 0.54%   |
| Notebook N15            | 1         | 0.54%   |
| MSI GF65                | 1         | 0.54%   |
| MSI GF63                | 1         | 0.54%   |
| LG E300-A.CP20T         | 1         | 0.54%   |
| Lenovo Z50-70           | 1         | 0.54%   |
| Lenovo V310-14IKB       | 1         | 0.54%   |
| Lenovo ThinkBook        | 1         | 0.54%   |
| Lenovo G51-35           | 1         | 0.54%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2013    | 19        | 10.22%  |
| 2016    | 16        | 8.6%    |
| 2011    | 16        | 8.6%    |
| 2010    | 15        | 8.06%   |
| 2021    | 14        | 7.53%   |
| 2018    | 14        | 7.53%   |
| 2015    | 14        | 7.53%   |
| 2020    | 12        | 6.45%   |
| 2017    | 11        | 5.91%   |
| 2012    | 11        | 5.91%   |
| 2008    | 10        | 5.38%   |
| 2014    | 9         | 4.84%   |
| 2009    | 9         | 4.84%   |
| 2007    | 6         | 3.23%   |
| 2019    | 4         | 2.15%   |
| 2022    | 3         | 1.61%   |
| 2006    | 2         | 1.08%   |
| Unknown | 1         | 0.54%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 186       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 186       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 72        | 38.71%  |
| 8.01-16.0   | 57        | 30.65%  |
| 16.01-24.0  | 31        | 16.67%  |
| 2.01-3.0    | 13        | 6.99%   |
| 32.01-64.0  | 6         | 3.23%   |
| 3.01-4.0    | 5         | 2.69%   |
| 24.01-32.0  | 1         | 0.54%   |
| 64.01-256.0 | 1         | 0.54%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 119       | 63.98%  |
| 0.51-1.0 | 49        | 26.34%  |
| 1.01-2.0 | 12        | 6.45%   |
| 2.01-3.0 | 6         | 3.23%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 140       | 74.47%  |
| 2      | 37        | 19.68%  |
| 0      | 8         | 4.26%   |
| 3      | 2         | 1.06%   |
| 4      | 1         | 0.53%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 102       | 54.84%  |
| Yes       | 84        | 45.16%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 173       | 93.01%  |
| No        | 13        | 6.99%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 185       | 99.46%  |
| No        | 1         | 0.54%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 124       | 66.67%  |
| No        | 62        | 33.33%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country             | Notebooks | Percent |
|---------------------|-----------|---------|
| USA                 | 30        | 16.13%  |
| Russia              | 15        | 8.06%   |
| Italy               | 11        | 5.91%   |
| Germany             | 11        | 5.91%   |
| UK                  | 10        | 5.38%   |
| Brazil              | 10        | 5.38%   |
| Spain               | 9         | 4.84%   |
| Netherlands         | 6         | 3.23%   |
| France              | 6         | 3.23%   |
| Romania             | 5         | 2.69%   |
| Mexico              | 5         | 2.69%   |
| China               | 5         | 2.69%   |
| Ukraine             | 4         | 2.15%   |
| Poland              | 4         | 2.15%   |
| Indonesia           | 4         | 2.15%   |
| Vietnam             | 3         | 1.61%   |
| India               | 3         | 1.61%   |
| Chile               | 3         | 1.61%   |
| Turkey              | 2         | 1.08%   |
| Sweden              | 2         | 1.08%   |
| Portugal            | 2         | 1.08%   |
| Peru                | 2         | 1.08%   |
| Norway              | 2         | 1.08%   |
| Hungary             | 2         | 1.08%   |
| Greece              | 2         | 1.08%   |
| Denmark             | 2         | 1.08%   |
| Czechia             | 2         | 1.08%   |
| Colombia            | 2         | 1.08%   |
| Trinidad and Tobago | 1         | 0.54%   |
| Tanzania            | 1         | 0.54%   |
| Taiwan              | 1         | 0.54%   |
| Switzerland         | 1         | 0.54%   |
| New Zealand         | 1         | 0.54%   |
| Myanmar             | 1         | 0.54%   |
| Malaysia            | 1         | 0.54%   |
| Lithuania           | 1         | 0.54%   |
| Latvia              | 1         | 0.54%   |
| Ireland             | 1         | 0.54%   |
| Iran                | 1         | 0.54%   |
| Georgia             | 1         | 0.54%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Moscow           | 4         | 2.13%   |
| Hanoi            | 3         | 1.6%    |
| Amsterdam        | 3         | 1.6%    |
| Warsaw           | 2         | 1.06%   |
| Madrid           | 2         | 1.06%   |
| Lima             | 2         | 1.06%   |
| Leatherhead      | 2         | 1.06%   |
| Jakarta          | 2         | 1.06%   |
| Dijon            | 2         | 1.06%   |
| Bucharest        | 2         | 1.06%   |
| Zhaoqing         | 1         | 0.53%   |
| Zaporizhzhya     | 1         | 0.53%   |
| Zapopan          | 1         | 0.53%   |
| Youngsville      | 1         | 0.53%   |
| Yichun           | 1         | 0.53%   |
| Yaphank          | 1         | 0.53%   |
| Yangon           | 1         | 0.53%   |
| Wroclaw          | 1         | 0.53%   |
| Windsor          | 1         | 0.53%   |
| Washington       | 1         | 0.53%   |
| Vilnius          | 1         | 0.53%   |
| Ventura          | 1         | 0.53%   |
| VÃ¤sterÃ¥s   | 1         | 0.53%   |
| Vaudreuil-Dorion | 1         | 0.53%   |
| Vandalia         | 1         | 0.53%   |
| Ugarchin         | 1         | 0.53%   |
| Turley           | 1         | 0.53%   |
| Turin            | 1         | 0.53%   |
| Tudela de Duero  | 1         | 0.53%   |
| Tsarskoye Selo   | 1         | 0.53%   |
| Tromsø          | 1         | 0.53%   |
| Torokszentmiklos | 1         | 0.53%   |
| Tolyatti         | 1         | 0.53%   |
| Tiruchi          | 1         | 0.53%   |
| Thessaloniki     | 1         | 0.53%   |
| Tehran           | 1         | 0.53%   |
| Tarragona        | 1         | 0.53%   |
| Taipei           | 1         | 0.53%   |
| Susanville       | 1         | 0.53%   |
| Suceava          | 1         | 0.53%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 40        | 41     | 18.1%   |
| Samsung Electronics | 32        | 34     | 14.48%  |
| Seagate             | 25        | 28     | 11.31%  |
| Kingston            | 17        | 18     | 7.69%   |
| Toshiba             | 16        | 16     | 7.24%   |
| Crucial             | 14        | 14     | 6.33%   |
| SanDisk             | 10        | 11     | 4.52%   |
| Intel               | 8         | 9      | 3.62%   |
| Hitachi             | 8         | 8      | 3.62%   |
| HGST                | 6         | 6      | 2.71%   |
| Micron Technology   | 5         | 5      | 2.26%   |
| Fujitsu             | 5         | 5      | 2.26%   |
| SPCC                | 3         | 4      | 1.36%   |
| Intenso             | 3         | 3      | 1.36%   |
| A-DATA Technology   | 3         | 3      | 1.36%   |
| SK hynix            | 2         | 2      | 0.9%    |
| Patriot             | 2         | 2      | 0.9%    |
| KingSpec            | 2         | 2      | 0.9%    |
| Corsair             | 2         | 2      | 0.9%    |
| Zheino              | 1         | 1      | 0.45%   |
| Transcend           | 1         | 1      | 0.45%   |
| Team                | 1         | 1      | 0.45%   |
| SSSTC               | 1         | 1      | 0.45%   |
| Smartbuy            | 1         | 1      | 0.45%   |
| Netac               | 1         | 1      | 0.45%   |
| Mushkin             | 1         | 1      | 0.45%   |
| LITEON              | 1         | 1      | 0.45%   |
| Lexar               | 1         | 1      | 0.45%   |
| Leven               | 1         | 1      | 0.45%   |
| KIOXIA              | 1         | 1      | 0.45%   |
| Integral            | 1         | 1      | 0.45%   |
| INDMEM              | 1         | 1      | 0.45%   |
| Hewlett-Packard     | 1         | 1      | 0.45%   |
| Apple               | 1         | 1      | 0.45%   |
| Apacer              | 1         | 1      | 0.45%   |
| ANACOMDA            | 1         | 1      | 0.45%   |
| AGI                 | 1         | 1      | 0.45%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| WDC WDS120G2G0A-00JH30 120GB       | 5         | 2.22%   |
| HGST HTS545050A7E680 500GB         | 5         | 2.22%   |
| Toshiba MQ01ABF050 500GB           | 4         | 1.78%   |
| Kingston SA400S37240G 240GB        | 4         | 1.78%   |
| Kingston SA400S37120G 120GB        | 3         | 1.33%   |
| Crucial CT500MX500SSD1 500GB       | 3         | 1.33%   |
| Crucial CT240BX500SSD1 240GB       | 3         | 1.33%   |
| WDC WDS240G2G0A-00JH30 240GB       | 2         | 0.89%   |
| WDC WD5000LPVX-22V0TT0 500GB       | 2         | 0.89%   |
| WDC WD5000LPCX-60VHAT0 500GB       | 2         | 0.89%   |
| WDC WD10JPCX-24UE4T0 1TB           | 2         | 0.89%   |
| Toshiba MQ01ABD100 1TB             | 2         | 0.89%   |
| SK hynix HFS256G39TND-N210A 256GB  | 2         | 0.89%   |
| Seagate ST9320423AS 320GB          | 2         | 0.89%   |
| Seagate ST9320325AS 320GB          | 2         | 0.89%   |
| Seagate ST500LT012-9WS142 500GB    | 2         | 0.89%   |
| Seagate ST1000LM035-1RK172 1TB     | 2         | 0.89%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 2         | 0.89%   |
| Samsung SSD PM871 2.5 7mm 128GB    | 2         | 0.89%   |
| Samsung SSD 860 EVO 250GB          | 2         | 0.89%   |
| Samsung SSD 850 EVO 500GB          | 2         | 0.89%   |
| Samsung MZVLW256HEHP-000L7 256GB   | 2         | 0.89%   |
| Hitachi HTS541680J9SA00 80GB       | 2         | 0.89%   |
| Crucial CT480BX500SSD1 480GB       | 2         | 0.89%   |
| Zheino CHN mSATAM1 256 256GB       | 1         | 0.44%   |
| WDC WDS500G2B0C-00PXH0 500GB       | 1         | 0.44%   |
| WDC WDS240G1G0A-00SS50 240GB       | 1         | 0.44%   |
| WDC WDBNCE5000PNC 500GB            | 1         | 0.44%   |
| WDC WD6400BPVT-60HXZT1 640GB       | 1         | 0.44%   |
| WDC WD6400BEVT-22A0RT0 640GB       | 1         | 0.44%   |
| WDC WD5000LPVX-80V0TT0 500GB       | 1         | 0.44%   |
| WDC WD5000LPLX-60ZNTT1 500GB       | 1         | 0.44%   |
| WDC WD5000LPCX-75VHAT0 500GB       | 1         | 0.44%   |
| WDC WD5000BPVT-22HXZT3 500GB       | 1         | 0.44%   |
| WDC WD5000BPKX-22HPJT0 500GB       | 1         | 0.44%   |
| WDC WD3200BPVT-80ZEST0 320GB       | 1         | 0.44%   |
| WDC WD3200BEVT-22ZCT0 320GB        | 1         | 0.44%   |
| WDC WD3200BEKX-60B7WT0 320GB       | 1         | 0.44%   |
| WDC WD2500BEVT-00ZCT0 250GB        | 1         | 0.44%   |
| WDC WD2500BEVS-22UST0 250GB        | 1         | 0.44%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 27        | 28     | 31.4%   |
| Seagate             | 25        | 28     | 29.07%  |
| Toshiba             | 14        | 14     | 16.28%  |
| Hitachi             | 8         | 8      | 9.3%    |
| HGST                | 6         | 6      | 6.98%   |
| Fujitsu             | 4         | 4      | 4.65%   |
| Samsung Electronics | 2         | 2      | 2.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 19        | 20     | 18.1%   |
| Kingston            | 14        | 14     | 13.33%  |
| Crucial             | 14        | 14     | 13.33%  |
| SanDisk             | 10        | 11     | 9.52%   |
| WDC                 | 9         | 9      | 8.57%   |
| Intel               | 5         | 5      | 4.76%   |
| SPCC                | 3         | 4      | 2.86%   |
| Intenso             | 3         | 3      | 2.86%   |
| SK hynix            | 2         | 2      | 1.9%    |
| Patriot             | 2         | 2      | 1.9%    |
| KingSpec            | 2         | 2      | 1.9%    |
| Corsair             | 2         | 2      | 1.9%    |
| A-DATA Technology   | 2         | 2      | 1.9%    |
| Zheino              | 1         | 1      | 0.95%   |
| Transcend           | 1         | 1      | 0.95%   |
| Toshiba             | 1         | 1      | 0.95%   |
| Team                | 1         | 1      | 0.95%   |
| Smartbuy            | 1         | 1      | 0.95%   |
| Netac               | 1         | 1      | 0.95%   |
| Mushkin             | 1         | 1      | 0.95%   |
| Micron Technology   | 1         | 1      | 0.95%   |
| LITEON              | 1         | 1      | 0.95%   |
| Lexar               | 1         | 1      | 0.95%   |
| Leven               | 1         | 1      | 0.95%   |
| Integral            | 1         | 1      | 0.95%   |
| INDMEM              | 1         | 1      | 0.95%   |
| Hewlett-Packard     | 1         | 1      | 0.95%   |
| Fujitsu             | 1         | 1      | 0.95%   |
| Apple               | 1         | 1      | 0.95%   |
| Apacer              | 1         | 1      | 0.95%   |
| ANACOMDA            | 1         | 1      | 0.95%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 93        | 108    | 45.81%  |
| HDD  | 80        | 90     | 39.41%  |
| NVMe | 30        | 33     | 14.78%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 163       | 198    | 84.46%  |
| NVMe | 30        | 33     | 15.54%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 137       | 160    | 79.65%  |
| 0.51-1.0   | 31        | 34     | 18.02%  |
| 1.01-2.0   | 3         | 3      | 1.74%   |
| 4.01-10.0  | 1         | 1      | 0.58%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 91        | 48.4%   |
| 101-250    | 44        | 23.4%   |
| 251-500    | 29        | 15.43%  |
| 501-1000   | 13        | 6.91%   |
| 21-50      | 6         | 3.19%   |
| 51-100     | 4         | 2.13%   |
| Unknown    | 1         | 0.53%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 182       | 97.85%  |
| 21-50   | 2         | 1.08%   |
| 101-250 | 1         | 0.54%   |
| Unknown | 1         | 0.54%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| WDC WD5000LPLX-60ZNTT1 500GB       | 1         | 1      | 2.17%   |
| WDC WD5000LPCX-75VHAT0 500GB       | 1         | 1      | 2.17%   |
| WDC WD5000LPCX-60VHAT0 500GB       | 1         | 1      | 2.17%   |
| WDC WD5000BPVT-22HXZT3 500GB       | 1         | 1      | 2.17%   |
| WDC WD3200BPVT-80ZEST0 320GB       | 1         | 1      | 2.17%   |
| WDC WD3200BEVT-22ZCT0 320GB        | 1         | 1      | 2.17%   |
| WDC WD1600BEVT-80A23T0 160GB       | 1         | 1      | 2.17%   |
| WDC WD1600BEKT-66F3T2 160GB        | 1         | 1      | 2.17%   |
| WDC WD10SPZX-24Z10T0 1TB           | 1         | 1      | 2.17%   |
| WDC WD10JPVX-22JC3T0 1TB           | 1         | 1      | 2.17%   |
| Toshiba THNSNX024GMNT 24GB         | 1         | 1      | 2.17%   |
| Toshiba MQ01ABF050 500GB           | 1         | 1      | 2.17%   |
| Toshiba MQ01ABD100 1TB             | 1         | 1      | 2.17%   |
| Toshiba MQ01ABD075 752GB           | 1         | 1      | 2.17%   |
| Toshiba MK8034GSX 80GB             | 1         | 1      | 2.17%   |
| Toshiba MK7559GSXF 752GB           | 1         | 1      | 2.17%   |
| Toshiba MK6034GSX 64GB             | 1         | 1      | 2.17%   |
| Toshiba MK3265GSXN 320GB           | 1         | 1      | 2.17%   |
| Toshiba MK3261GSYN 320GB           | 1         | 1      | 2.17%   |
| Seagate ST9640320AS 640GB          | 1         | 1      | 2.17%   |
| Seagate ST9500325AS 500GB          | 1         | 1      | 2.17%   |
| Seagate ST9320423AS 320GB          | 1         | 1      | 2.17%   |
| Seagate ST9320325AS 320GB          | 1         | 1      | 2.17%   |
| Seagate ST9160412AS 160GB          | 1         | 1      | 2.17%   |
| Seagate ST9120821AS 118GB          | 1         | 1      | 2.17%   |
| Seagate ST500LT012-9WS142 500GB    | 1         | 1      | 2.17%   |
| Seagate ST320LT020-9YG142 320GB    | 1         | 1      | 2.17%   |
| Seagate ST320LT007-9ZV142 320GB    | 1         | 1      | 2.17%   |
| Seagate ST3160212AS 160GB          | 1         | 1      | 2.17%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1         | 1      | 2.17%   |
| Seagate ST1000LM014-1EJ164 1TB     | 1         | 1      | 2.17%   |
| Samsung Electronics HS082HB 80GB   | 1         | 1      | 2.17%   |
| Samsung Electronics HM160HI 160GB  | 1         | 1      | 2.17%   |
| LITEON CV8-8E128-HP 128GB          | 1         | 1      | 2.17%   |
| Kingston SV300S37A120G 120GB       | 1         | 1      | 2.17%   |
| Kingston SUV500MS480G 480GB        | 1         | 1      | 2.17%   |
| Hitachi HTS723216L9SA60 160GB      | 1         | 1      | 2.17%   |
| Hitachi HTS547564A9E384 640GB      | 1         | 1      | 2.17%   |
| Hitachi HTS545050A7E380 500GB      | 1         | 1      | 2.17%   |
| Hitachi HTS545025B9SA02 250GB      | 1         | 1      | 2.17%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 12        | 12     | 26.09%  |
| WDC                 | 10        | 10     | 21.74%  |
| Toshiba             | 9         | 9      | 19.57%  |
| Hitachi             | 5         | 5      | 10.87%  |
| Samsung Electronics | 2         | 2      | 4.35%   |
| Kingston            | 2         | 2      | 4.35%   |
| HGST                | 2         | 2      | 4.35%   |
| LITEON              | 1         | 1      | 2.17%   |
| Fujitsu             | 1         | 1      | 2.17%   |
| Corsair             | 1         | 1      | 2.17%   |
| AGI                 | 1         | 1      | 2.17%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 12        | 12     | 30%     |
| WDC                 | 10        | 10     | 25%     |
| Toshiba             | 8         | 8      | 20%     |
| Hitachi             | 5         | 5      | 12.5%   |
| Samsung Electronics | 2         | 2      | 5%      |
| HGST                | 2         | 2      | 5%      |
| Fujitsu             | 1         | 1      | 2.5%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 37        | 40     | 86.05%  |
| SSD  | 5         | 5      | 11.63%  |
| NVMe | 1         | 1      | 2.33%   |

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
| Works    | 143       | 184    | 76.47%  |
| Malfunc  | 43        | 46     | 22.99%  |
| Detected | 1         | 1      | 0.53%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 152       | 74.15%  |
| AMD                              | 19        | 9.27%   |
| Samsung Electronics              | 12        | 5.85%   |
| Nvidia                           | 6         | 2.93%   |
| SanDisk                          | 4         | 1.95%   |
| Micron Technology                | 4         | 1.95%   |
| KIOXIA                           | 2         | 0.98%   |
| Kingston Technology Company      | 2         | 0.98%   |
| Solid State Storage Technology   | 1         | 0.49%   |
| Silicon Motion                   | 1         | 0.49%   |
| Silicon Integrated Systems [SiS] | 1         | 0.49%   |
| ADATA Technology                 | 1         | 0.49%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 20        | 8.89%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 19        | 8.44%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 18        | 8%      |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 14        | 6.22%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 12        | 5.33%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 12        | 5.33%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 11        | 4.89%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 10        | 4.44%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 9         | 4%      |
| Unknown                                                                          | 7         | 3.11%   |
| Nvidia MCP79 AHCI Controller                                                     | 6         | 2.67%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 6         | 2.67%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 6         | 2.67%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 5         | 2.22%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 5         | 2.22%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 5         | 2.22%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 4         | 1.78%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 4         | 1.78%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 4         | 1.78%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 3         | 1.33%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 3         | 1.33%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 3         | 1.33%   |
| Intel Comet Lake SATA AHCI Controller                                            | 3         | 1.33%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 2         | 0.89%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 2         | 0.89%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 2         | 0.89%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 2         | 0.89%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 2         | 0.89%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 2         | 0.89%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 2         | 0.89%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 2         | 0.89%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 2         | 0.89%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 0.44%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 0.44%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 1         | 0.44%   |
| SanDisk unknown                                                                  | 1         | 0.44%   |
| SanDisk PC SN530                                                                 | 1         | 0.44%   |
| Samsung NVMe SSD Controller 980                                                  | 1         | 0.44%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 1         | 0.44%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 1         | 0.44%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 164       | 74.55%  |
| NVMe | 29        | 13.18%  |
| IDE  | 20        | 9.09%   |
| RAID | 7         | 3.18%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 163       | 87.63%  |
| AMD    | 23        | 12.37%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz       | 8         | 4.3%    |
| Intel CPU Version                       | 5         | 2.69%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 5         | 2.69%   |
| Intel Core i5 CPU M 520 @ 2.40GHz       | 4         | 2.15%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz    | 4         | 2.15%   |
| Intel Core i7-3612QM CPU @ 2.10GHz      | 3         | 1.61%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 3         | 1.61%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 3         | 1.61%   |
| Intel Core i5-4300M CPU @ 2.60GHz       | 3         | 1.61%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 3         | 1.61%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 3         | 1.61%   |
| Intel Core i3-6006U CPU @ 2.00GHz       | 3         | 1.61%   |
| Intel Core i3-3110M CPU @ 2.40GHz       | 3         | 1.61%   |
| Intel Core 2 Duo CPU P7550 @ 2.26GHz    | 3         | 1.61%   |
| Intel Genuine CPU                       | 2         | 1.08%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 2         | 1.08%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 2         | 1.08%   |
| Intel Core i7-4600U CPU @ 2.10GHz       | 2         | 1.08%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 2         | 1.08%   |
| Intel Core i5-9300H CPU @ 2.40GHz       | 2         | 1.08%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 2         | 1.08%   |
| Intel Core i5-7300U CPU @ 2.60GHz       | 2         | 1.08%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 2         | 1.08%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 2         | 1.08%   |
| Intel Core i5-4200U CPU @ 1.60GHz       | 2         | 1.08%   |
| Intel Core i5-3317U CPU @ 1.70GHz       | 2         | 1.08%   |
| Intel Core i5-10300H CPU @ 2.50GHz      | 2         | 1.08%   |
| Intel Core i3-4005U CPU @ 1.70GHz       | 2         | 1.08%   |
| Intel Core i3-2310M CPU @ 2.10GHz       | 2         | 1.08%   |
| Intel Core i3 CPU M 330 @ 2.13GHz       | 2         | 1.08%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz    | 2         | 1.08%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz    | 2         | 1.08%   |
| Intel Core 2 Duo CPU T6600 @ 2.20GHz    | 2         | 1.08%   |
| Intel Celeron CPU N3350 @ 1.10GHz       | 2         | 1.08%   |
| Intel Celeron CPU N3060 @ 1.60GHz       | 2         | 1.08%   |
| Intel Atom CPU N450 @ 1.66GHz           | 2         | 1.08%   |
| AMD Ryzen 7 4700U with Radeon Graphics  | 2         | 1.08%   |
| AMD E1-1200 APU with Radeon HD Graphics | 2         | 1.08%   |
| Intel Xeon E-2276M CPU @ 2.80GHz        | 1         | 0.54%   |
| Intel Pentium M                         | 1         | 0.54%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 60        | 32.26%  |
| Intel Core i7           | 25        | 13.44%  |
| Intel Core 2 Duo        | 23        | 12.37%  |
| Intel Core i3           | 20        | 10.75%  |
| Intel Celeron           | 12        | 6.45%   |
| Other                   | 6         | 3.23%   |
| AMD Ryzen 5             | 6         | 3.23%   |
| Intel Pentium           | 5         | 2.69%   |
| AMD A6                  | 5         | 2.69%   |
| Intel Atom              | 3         | 1.61%   |
| AMD Ryzen 7             | 3         | 1.61%   |
| AMD E1                  | 3         | 1.61%   |
| Intel Pentium Dual-Core | 2         | 1.08%   |
| Intel Genuine           | 2         | 1.08%   |
| Intel Core 2            | 2         | 1.08%   |
| AMD E2                  | 2         | 1.08%   |
| Intel Xeon              | 1         | 0.54%   |
| Intel Pentium M         | 1         | 0.54%   |
| Intel Core M            | 1         | 0.54%   |
| Intel Celeron Dual-Core | 1         | 0.54%   |
| AMD Ryzen 3             | 1         | 0.54%   |
| AMD A8                  | 1         | 0.54%   |
| AMD A10                 | 1         | 0.54%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 108       | 58.06%  |
| 4       | 35        | 18.82%  |
| Unknown | 28        | 15.05%  |
| 8       | 6         | 3.23%   |
| 6       | 6         | 3.23%   |
| 12      | 2         | 1.08%   |
| 1       | 1         | 0.54%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 173       | 93.01%  |
| 2       | 11        | 5.91%   |
| Unknown | 2         | 1.08%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 108       | 58.06%  |
| 1       | 50        | 26.88%  |
| Unknown | 28        | 15.05%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| Penryn      | 24        | 12.9%   |
| IvyBridge   | 23        | 12.37%  |
| KabyLake    | 20        | 10.75%  |
| Haswell     | 17        | 9.14%   |
| Skylake     | 16        | 8.6%    |
| Westmere    | 15        | 8.06%   |
| SandyBridge | 15        | 8.06%   |
| Core        | 10        | 5.38%   |
| Silvermont  | 9         | 4.84%   |
| Broadwell   | 5         | 2.69%   |
| Zen+        | 4         | 2.15%   |
| Zen 2       | 4         | 2.15%   |
| CometLake   | 4         | 2.15%   |
| Jaguar      | 3         | 1.61%   |
| Bonnell     | 3         | 1.61%   |
| Bobcat      | 3         | 1.61%   |
| Zen         | 2         | 1.08%   |
| Puma        | 2         | 1.08%   |
| Goldmont    | 2         | 1.08%   |
| Excavator   | 2         | 1.08%   |
| Zen 3       | 1         | 0.54%   |
| Piledriver  | 1         | 0.54%   |
| K10 Llano   | 1         | 0.54%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 138       | 63.59%  |
| Nvidia | 40        | 18.43%  |
| AMD    | 39        | 17.97%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 22        | 9.48%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 15        | 6.47%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 12        | 5.17%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 11        | 4.74%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 11        | 4.74%   |
| Intel Core Processor Integrated Graphics Controller                                      | 11        | 4.74%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 10        | 4.31%   |
| Intel HD Graphics 620                                                                    | 8         | 3.45%   |
| Nvidia C79 [GeForce 9400M]                                                               | 5         | 2.16%   |
| Intel HD Graphics 530                                                                    | 5         | 2.16%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 2.16%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 2.16%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5         | 2.16%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 1.72%   |
| Intel HD Graphics 5500                                                                   | 4         | 1.72%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 4         | 1.72%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 1.72%   |
| AMD Renoir                                                                               | 4         | 1.72%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 1.29%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 3         | 1.29%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 3         | 1.29%   |
| Intel UHD Graphics 620                                                                   | 3         | 1.29%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 1.29%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 3         | 1.29%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/545v]                                        | 3         | 1.29%   |
| Nvidia TU117M                                                                            | 2         | 0.86%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 0.86%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 2         | 0.86%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 2         | 0.86%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 0.86%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 0.86%   |
| Intel HD Graphics 500                                                                    | 2         | 0.86%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 0.86%   |
| AMD Wrestler [Radeon HD 7310]                                                            | 2         | 0.86%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 2         | 0.86%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 0.86%   |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                             | 2         | 0.86%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 2         | 0.86%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 1         | 0.43%   |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 0.43%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 90        | 48.39%  |
| 1 x AMD        | 28        | 15.05%  |
| Intel + Nvidia | 21        | 11.29%  |
| 2 x Intel      | 20        | 10.75%  |
| 1 x Nvidia     | 15        | 8.06%   |
| Intel + AMD    | 7         | 3.76%   |
| AMD + Nvidia   | 3         | 1.61%   |
| 2 x Nvidia     | 1         | 0.54%   |
| 2 x AMD        | 1         | 0.54%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 166       | 89.25%  |
| Proprietary | 17        | 9.14%   |
| Unknown     | 3         | 1.61%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 143       | 76.88%  |
| 0.01-0.5   | 28        | 15.05%  |
| 0.51-1.0   | 7         | 3.76%   |
| 1.01-2.0   | 4         | 2.15%   |
| 5.01-6.0   | 2         | 1.08%   |
| 3.01-4.0   | 2         | 1.08%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 36        | 19.05%  |
| AU Optronics            | 32        | 16.93%  |
| Chimei Innolux          | 29        | 15.34%  |
| Samsung Electronics     | 26        | 13.76%  |
| Lenovo                  | 18        | 9.52%   |
| BOE                     | 17        | 8.99%   |
| Apple                   | 12        | 6.35%   |
| Chi Mei Optoelectronics | 3         | 1.59%   |
| Sharp                   | 2         | 1.06%   |
| Vestel Elektronik       | 1         | 0.53%   |
| Toshiba                 | 1         | 0.53%   |
| Sony                    | 1         | 0.53%   |
| SLD                     | 1         | 0.53%   |
| Philips                 | 1         | 0.53%   |
| PANDA                   | 1         | 0.53%   |
| LG Philips              | 1         | 0.53%   |
| Lenovo Group Limited    | 1         | 0.53%   |
| LED                     | 1         | 0.53%   |
| InfoVision              | 1         | 0.53%   |
| Goldstar                | 1         | 0.53%   |
| BenQ                    | 1         | 0.53%   |
| Ancor Communications    | 1         | 0.53%   |
| Acer                    | 1         | 0.53%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Lenovo LCD Monitor LEN4031 1280x800 300x190mm 14.0-inch               | 4         | 2.08%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch      | 4         | 2.08%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 340x190mm 15.3-inch       | 3         | 1.56%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 300x170mm 13.6-inch  | 2         | 1.04%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch  | 2         | 1.04%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 340x190mm 15.3-inch | 2         | 1.04%   |
| LG Display LCD Monitor LGD0459 1920x1080 380x210mm 17.1-inch          | 2         | 1.04%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch           | 2         | 1.04%   |
| LG Display LCD Monitor LGD0250 1366x768 350x190mm 15.7-inch           | 2         | 1.04%   |
| Lenovo LCD Monitor LEN40B0 1366x768 340x190mm 15.3-inch               | 2         | 1.04%   |
| Lenovo LCD Monitor LEN40A0 1366x768 310x170mm 13.9-inch               | 2         | 1.04%   |
| Lenovo LCD Monitor LEN4035 1280x800 300x190mm 14.0-inch               | 2         | 1.04%   |
| Chimei Innolux LCD Monitor CMN1492 1366x768 310x170mm 13.9-inch       | 2         | 1.04%   |
| AU Optronics LCD Monitor AUO325C 1366x768 260x140mm 11.6-inch         | 2         | 1.04%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 340x190mm 15.3-inch         | 2         | 1.04%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 310x170mm 13.9-inch        | 2         | 1.04%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch         | 2         | 1.04%   |
| Apple Color LCD APP9C5E 1280x800 290x190mm 13.6-inch                  | 2         | 1.04%   |
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 710x400mm 32.1-inch    | 1         | 0.52%   |
| Toshiba TV TSB0108 1360x768 700x390mm 31.5-inch                       | 1         | 0.52%   |
| Sony LCD SNY06FA 1600x900 290x160mm 13.0-inch                         | 1         | 0.52%   |
| SLD LCD Monitor SLD003C 1366x768 310x170mm 13.9-inch                  | 1         | 0.52%   |
| Sharp LQ140Z1JW01 SHP1401 3200x1800 310x170mm 13.9-inch               | 1         | 0.52%   |
| Sharp LCD Monitor SHP14BA 1920x1080 340x190mm 15.3-inch               | 1         | 0.52%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 610x350mm 27.7-inch     | 1         | 0.52%   |
| Samsung Electronics S27C350 SAM0A3E 1920x1080 600x340mm 27.2-inch     | 1         | 0.52%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch     | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 410x230mm 18.5-inch | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SEC4E41 1280x800 260x160mm 12.0-inch  | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SEC4542 1280x800 300x190mm 14.0-inch  | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SEC384A 1366x768 340x190mm 15.3-inch  | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SEC3847 1440x900 370x230mm 17.2-inch  | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SEC334A 1366x768 340x190mm 15.3-inch  | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 340x190mm 15.3-inch  | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SEC3157 1280x800 300x190mm 14.0-inch  | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 340x190mm 15.3-inch | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SEC3052 1024x600 220x130mm 10.1-inch  | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 310x170mm 13.9-inch  | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch  | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 340x190mm 15.3-inch  | 1         | 0.52%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 88        | 47.31%  |
| 1920x1080 (FHD)   | 47        | 25.27%  |
| 1280x800 (WXGA)   | 23        | 12.37%  |
| 1600x900 (HD+)    | 9         | 4.84%   |
| 3840x2160 (4K)    | 3         | 1.61%   |
| 1440x900 (WXGA+)  | 3         | 1.61%   |
| 1024x768 (XGA)    | 3         | 1.61%   |
| 2560x1440 (QHD)   | 2         | 1.08%   |
| 1920x540          | 2         | 1.08%   |
| 1024x600          | 2         | 1.08%   |
| 3200x1800 (QHD+)  | 1         | 0.54%   |
| 2560x1080         | 1         | 0.54%   |
| 1920x1200 (WUXGA) | 1         | 0.54%   |
| 1280x1024 (SXGA)  | 1         | 0.54%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 73        | 38.02%  |
| 13      | 52        | 27.08%  |
| 12      | 16        | 8.33%   |
| 17      | 11        | 5.73%   |
| 14      | 10        | 5.21%   |
| 11      | 6         | 3.13%   |
| 27      | 4         | 2.08%   |
| 24      | 3         | 1.56%   |
| 23      | 3         | 1.56%   |
| 10      | 3         | 1.56%   |
| 18      | 2         | 1.04%   |
| 64      | 1         | 0.52%   |
| 54      | 1         | 0.52%   |
| 42      | 1         | 0.52%   |
| 40      | 1         | 0.52%   |
| 34      | 1         | 0.52%   |
| 31      | 1         | 0.52%   |
| 20      | 1         | 0.52%   |
| 16      | 1         | 0.52%   |
| Unknown | 1         | 0.52%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 108       | 56.25%  |
| 201-300     | 52        | 27.08%  |
| 351-400     | 13        | 6.77%   |
| 501-600     | 9         | 4.69%   |
| 601-700     | 2         | 1.04%   |
| 401-500     | 2         | 1.04%   |
| 1001-1500   | 2         | 1.04%   |
| 801-900     | 1         | 0.52%   |
| 701-800     | 1         | 0.52%   |
| 901-1000    | 1         | 0.52%   |
| Unknown     | 1         | 0.52%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 144       | 80%     |
| 16/10   | 25        | 13.89%  |
| 3/2     | 5         | 2.78%   |
| 4/3     | 3         | 1.67%   |
| 5/4     | 1         | 0.56%   |
| 21/9    | 1         | 0.56%   |
| Unknown | 1         | 0.56%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 91-100         | 59        | 30.73%  |
| 81-90          | 54        | 28.13%  |
| 61-70          | 17        | 8.85%   |
| 101-110        | 15        | 7.81%   |
| 121-130        | 9         | 4.69%   |
| 71-80          | 7         | 3.65%   |
| 51-60          | 5         | 2.6%    |
| 201-250        | 5         | 2.6%    |
| 301-350        | 4         | 2.08%   |
| 41-50          | 3         | 1.56%   |
| More than 1000 | 2         | 1.04%   |
| 351-500        | 2         | 1.04%   |
| 141-150        | 2         | 1.04%   |
| 131-140        | 2         | 1.04%   |
| 501-1000       | 2         | 1.04%   |
| 251-300        | 1         | 0.52%   |
| 151-200        | 1         | 0.52%   |
| 111-120        | 1         | 0.52%   |
| Unknown        | 1         | 0.52%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 87        | 46.03%  |
| 121-160       | 70        | 37.04%  |
| 51-100        | 27        | 14.29%  |
| 161-240       | 3         | 1.59%   |
| More than 240 | 1         | 0.53%   |
| Unknown       | 1         | 0.53%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 165       | 88.24%  |
| 2     | 17        | 9.09%   |
| 0     | 5         | 2.67%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 97        | 31.29%  |
| Realtek Semiconductor             | 84        | 27.1%   |
| Qualcomm Atheros                  | 46        | 14.84%  |
| Broadcom                          | 35        | 11.29%  |
| Marvell Technology Group          | 11        | 3.55%   |
| Nvidia                            | 6         | 1.94%   |
| Ralink                            | 4         | 1.29%   |
| Xiaomi                            | 3         | 0.97%   |
| JMicron Technology                | 3         | 0.97%   |
| Sierra Wireless                   | 2         | 0.65%   |
| NetGear                           | 2         | 0.65%   |
| Ericsson Business Mobile Networks | 2         | 0.65%   |
| Edimax Technology                 | 2         | 0.65%   |
| Dell                              | 2         | 0.65%   |
| TP-Link                           | 1         | 0.32%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.32%   |
| Samsung Electronics               | 1         | 0.32%   |
| Ralink Technology                 | 1         | 0.32%   |
| OPPO Electronics                  | 1         | 0.32%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.32%   |
| Mercucys                          | 1         | 0.32%   |
| Huawei Technologies               | 1         | 0.32%   |
| Hewlett-Packard                   | 1         | 0.32%   |
| Google                            | 1         | 0.32%   |
| D-Link System                     | 1         | 0.32%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 61        | 15.68%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 17        | 4.37%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 15        | 3.86%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 14        | 3.6%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 13        | 3.34%   |
| Intel Wireless 8260                                               | 11        | 2.83%   |
| Intel Wireless 7260                                               | 9         | 2.31%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 8         | 2.06%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 7         | 1.8%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 7         | 1.8%    |
| Intel Centrino Advanced-N 6200                                    | 7         | 1.8%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 6         | 1.54%   |
| Nvidia MCP79 Ethernet                                             | 6         | 1.54%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 6         | 1.54%   |
| Intel 82577LM Gigabit Network Connection                          | 6         | 1.54%   |
| Intel Wireless 7265                                               | 5         | 1.29%   |
| Intel WiFi Link 5100                                              | 5         | 1.29%   |
| Intel Wi-Fi 6 AX200                                               | 5         | 1.29%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 5         | 1.29%   |
| Intel 82566MM Gigabit Network Connection                          | 5         | 1.29%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 5         | 1.29%   |
| Broadcom BCM4321 802.11a/b/g/n                                    | 5         | 1.29%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 1.03%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 4         | 1.03%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 4         | 1.03%   |
| Intel Wireless 8265 / 8275                                        | 4         | 1.03%   |
| Intel Ethernet Connection I219-LM                                 | 4         | 1.03%   |
| Intel Ethernet Connection I218-LM                                 | 4         | 1.03%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 1.03%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 4         | 1.03%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 3         | 0.77%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3         | 0.77%   |
| Realtek Realtek Bluetooth 4.2 Adapter                             | 3         | 0.77%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 0.77%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 3         | 0.77%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 0.77%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 3         | 0.77%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 3         | 0.77%   |
| Intel Centrino Advanced-N 6235                                    | 3         | 0.77%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3         | 0.77%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 96        | 48.24%  |
| Qualcomm Atheros      | 43        | 21.61%  |
| Realtek Semiconductor | 25        | 12.56%  |
| Broadcom              | 22        | 11.06%  |
| Ralink                | 4         | 2.01%   |
| NetGear               | 2         | 1.01%   |
| Edimax Technology     | 2         | 1.01%   |
| TP-Link               | 1         | 0.5%    |
| Sierra Wireless       | 1         | 0.5%    |
| Ralink Technology     | 1         | 0.5%    |
| Mercucys              | 1         | 0.5%    |
| Dell                  | 1         | 0.5%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 14        | 6.86%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 13        | 6.37%   |
| Intel Wireless 8260                                                     | 11        | 5.39%   |
| Intel Wireless 7260                                                     | 9         | 4.41%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 8         | 3.92%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 7         | 3.43%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 7         | 3.43%   |
| Intel Centrino Advanced-N 6200                                          | 7         | 3.43%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 6         | 2.94%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 6         | 2.94%   |
| Intel Wireless 7265                                                     | 5         | 2.45%   |
| Intel WiFi Link 5100                                                    | 5         | 2.45%   |
| Intel Wi-Fi 6 AX200                                                     | 5         | 2.45%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 5         | 2.45%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 5         | 2.45%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 5         | 2.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 1.96%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 4         | 1.96%   |
| Intel Wireless 8265 / 8275                                              | 4         | 1.96%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 4         | 1.96%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 3         | 1.47%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 3         | 1.47%   |
| Realtek Realtek Bluetooth 4.2 Adapter                                   | 3         | 1.47%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 3         | 1.47%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 1.47%   |
| Intel Centrino Advanced-N 6235                                          | 3         | 1.47%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3         | 1.47%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 3         | 1.47%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 3         | 1.47%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 2         | 0.98%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 0.98%   |
| Realtek 802.11n WLAN Adapter                                            | 2         | 0.98%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 2         | 0.98%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.98%   |
| Intel Ultimate N WiFi Link 5300                                         | 2         | 0.98%   |
| Intel Centrino Ultimate-N 6300                                          | 2         | 0.98%   |
| Broadcom BCM43142 802.11b/g/n                                           | 2         | 0.98%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                     | 1         | 0.49%   |
| Sierra Wireless Sierra Wireless EM7345 4G LTE                           | 1         | 0.49%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 0.49%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 78        | 43.82%  |
| Intel                            | 50        | 28.09%  |
| Broadcom                         | 13        | 7.3%    |
| Marvell Technology Group         | 11        | 6.18%   |
| Qualcomm Atheros                 | 9         | 5.06%   |
| Nvidia                           | 6         | 3.37%   |
| Xiaomi                           | 3         | 1.69%   |
| JMicron Technology               | 3         | 1.69%   |
| Silicon Integrated Systems [SiS] | 1         | 0.56%   |
| Samsung Electronics              | 1         | 0.56%   |
| OPPO Electronics                 | 1         | 0.56%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.56%   |
| Google                           | 1         | 0.56%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 61        | 34.27%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 17        | 9.55%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 15        | 8.43%   |
| Nvidia MCP79 Ethernet                                             | 6         | 3.37%   |
| Intel 82577LM Gigabit Network Connection                          | 6         | 3.37%   |
| Intel 82566MM Gigabit Network Connection                          | 5         | 2.81%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 4         | 2.25%   |
| Intel Ethernet Connection I219-LM                                 | 4         | 2.25%   |
| Intel Ethernet Connection I218-LM                                 | 4         | 2.25%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 2.25%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 1.69%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 3         | 1.69%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 1.69%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 3         | 1.69%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 1.12%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 1.12%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 2         | 1.12%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 2         | 1.12%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.12%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 2         | 1.12%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 2         | 1.12%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.56%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.56%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.56%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.56%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.56%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.56%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.56%   |
| OPPO SDM720G-IDP _SN:8A58D65F RNDIS Control RNDIS Ethernet Data   | 1         | 0.56%   |
| OnePlus (Shenzhen) OnePlus RNDIS Control RNDIS Ethernet Data      | 1         | 0.56%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 0.56%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller             | 1         | 0.56%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller              | 1         | 0.56%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.56%   |
| Intel Ethernet Connection I218-V                                  | 1         | 0.56%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.56%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 0.56%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.56%   |
| Intel 82573L Gigabit Ethernet Controller                          | 1         | 0.56%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.56%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 185       | 50.68%  |
| Ethernet | 173       | 47.4%   |
| Unknown  | 4         | 1.1%    |
| Modem    | 3         | 0.82%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 122       | 49.39%  |
| WiFi     | 121       | 48.99%  |
| Unknown  | 3         | 1.21%   |
| Modem    | 1         | 0.4%    |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 169       | 90.86%  |
| 1     | 16        | 8.6%    |
| 0     | 1         | 0.54%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 177       | 95.16%  |
| Yes  | 9         | 4.84%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 45        | 36.29%  |
| Broadcom                        | 17        | 13.71%  |
| Qualcomm Atheros Communications | 12        | 9.68%   |
| Realtek Semiconductor           | 11        | 8.87%   |
| Apple                           | 11        | 8.87%   |
| Lite-On Technology              | 7         | 5.65%   |
| Foxconn / Hon Hai               | 5         | 4.03%   |
| Ralink                          | 4         | 3.23%   |
| Hewlett-Packard                 | 4         | 3.23%   |
| IMC Networks                    | 3         | 2.42%   |
| Dell                            | 3         | 2.42%   |
| Cambridge Silicon Radio         | 2         | 1.61%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 27        | 21.43%  |
| Broadcom BCM2045B (BDC-2.1)                                 | 8         | 6.35%   |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                     | 6         | 4.76%   |
| Intel AX200 Bluetooth                                       | 5         | 3.97%   |
| Apple Bluetooth Host Controller                             | 5         | 3.97%   |
| Ralink RT3290 Bluetooth                                     | 4         | 3.17%   |
| Lite-On Atheros AR3012 Bluetooth                            | 4         | 3.17%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 4         | 3.17%   |
| Intel AX201 Bluetooth                                       | 4         | 3.17%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 4         | 3.17%   |
| Apple Built-in iSight (no firmware loaded)                  | 4         | 3.17%   |
| Realtek  Bluetooth 4.0 Adapter                              | 3         | 2.38%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 3         | 2.38%   |
| Realtek RTL8723B Bluetooth                                  | 2         | 1.59%   |
| Realtek  Bluetooth 4.2 Adapter                              | 2         | 1.59%   |
| Realtek Bluetooth Radio                                     | 2         | 1.59%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 2         | 1.59%   |
| Foxconn / Hon Hai Qualcomm Atheros Bluetooth 4.0            | 2         | 1.59%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 2         | 1.59%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 2         | 1.59%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 2         | 1.59%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 2         | 1.59%   |
| Realtek RTL8821A Bluetooth                                  | 1         | 0.79%   |
| Realtek  Bluetooth Adapter                                  | 1         | 0.79%   |
| Realtek  Bluetooth 4.0 + High Speed Chip                    | 1         | 0.79%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 1         | 0.79%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1         | 0.79%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 1         | 0.79%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 1         | 0.79%   |
| Qualcomm Atheros AR3012 Bluetooth                           | 1         | 0.79%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)             | 1         | 0.79%   |
| Lite-On Realtek Bluetooth Adapter                           | 1         | 0.79%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 1         | 0.79%   |
| Lite-On Qualcomm Atheros Bluetooth                          | 1         | 0.79%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 1         | 0.79%   |
| Intel Wireless-AC 3168 Bluetooth                            | 1         | 0.79%   |
| IMC Networks Realtek Bluetooth Adapter                      | 1         | 0.79%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS            | 1         | 0.79%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 1         | 0.79%   |
| HP Broadcom 2070 Bluetooth Combo                            | 1         | 0.79%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 155       | 74.16%  |
| AMD                              | 30        | 14.35%  |
| Nvidia                           | 19        | 9.09%   |
| GN Netcom                        | 2         | 0.96%   |
| Texas Instruments                | 1         | 0.48%   |
| Silicon Integrated Systems [SiS] | 1         | 0.48%   |
| Creative Technology              | 1         | 0.48%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 24        | 9.52%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 22        | 8.73%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 15        | 5.95%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 14        | 5.56%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 13        | 5.16%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 12        | 4.76%   |
| Intel 8 Series HD Audio Controller                                                                | 12        | 4.76%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 11        | 4.37%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 10        | 3.97%   |
| AMD FCH Azalia Controller                                                                         | 10        | 3.97%   |
| Nvidia MCP79 High Definition Audio                                                                | 6         | 2.38%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 6         | 2.38%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5         | 1.98%   |
| Intel Cannon Lake PCH cAVS                                                                        | 5         | 1.98%   |
| Intel Broadwell-U Audio Controller                                                                | 5         | 1.98%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 5         | 1.98%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 5         | 1.98%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 1.98%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 5         | 1.98%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 1.98%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 1.59%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 4         | 1.59%   |
| Intel Comet Lake PCH cAVS                                                                         | 4         | 1.59%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 1.59%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 4         | 1.59%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 4         | 1.59%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 3         | 1.19%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 1.19%   |
| AMD Wrestler HDMI Audio                                                                           | 3         | 1.19%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 0.79%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 0.79%   |
| AMD High Definition Audio Controller                                                              | 2         | 0.79%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 0.79%   |
| Texas Instruments PCM2900 Audio Codec                                                             | 1         | 0.4%    |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 0.4%    |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.4%    |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.4%    |
| Nvidia GK104 HDMI Audio Controller                                                                | 1         | 0.4%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.4%    |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.4%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 58        | 26.98%  |
| SK hynix            | 35        | 16.28%  |
| Kingston            | 27        | 12.56%  |
| Micron Technology   | 19        | 8.84%   |
| Unknown             | 16        | 7.44%   |
| Nanya Technology    | 8         | 3.72%   |
| Ramaxel Technology  | 7         | 3.26%   |
| Crucial             | 7         | 3.26%   |
| Elpida              | 6         | 2.79%   |
| Unknown             | 6         | 2.79%   |
| Smart               | 4         | 1.86%   |
| A-DATA Technology   | 4         | 1.86%   |
| Silicon Power       | 2         | 0.93%   |
| ASint Technology    | 2         | 0.93%   |
| 48spaces            | 2         | 0.93%   |
| Unknown (ABCD)      | 1         | 0.47%   |
| Unknown (0x0809)    | 1         | 0.47%   |
| Transcend           | 1         | 0.47%   |
| Smart Brazil        | 1         | 0.47%   |
| Sesame              | 1         | 0.47%   |
| PNY                 | 1         | 0.47%   |
| Kingmax             | 1         | 0.47%   |
| High Bridge         | 1         | 0.47%   |
| GOODRAM             | 1         | 0.47%   |
| Corsair             | 1         | 0.47%   |
| Avant               | 1         | 0.47%   |
| Apacer              | 1         | 0.47%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                                | 7         | 3.02%   |
| Unknown                                                                   | 6         | 2.59%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 5         | 2.16%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s                     | 5         | 2.16%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                                | 4         | 1.72%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 4         | 1.72%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 4         | 1.72%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s                     | 4         | 1.72%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s                     | 3         | 1.29%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 3         | 1.29%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s                    | 3         | 1.29%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s                     | 3         | 1.29%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s                     | 3         | 1.29%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s                     | 3         | 1.29%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s                   | 3         | 1.29%   |
| Unknown RAM Module 2GB SODIMM DDR2                                        | 2         | 0.86%   |
| SK hynix RAM HMT451S6MFR8A-PB 4GB SODIMM DDR3 800MT/s                     | 2         | 0.86%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s                    | 2         | 0.86%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 1333MT/s                     | 2         | 0.86%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                     | 2         | 0.86%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s                     | 2         | 0.86%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s                    | 2         | 0.86%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2400MT/s                     | 2         | 0.86%   |
| Ramaxel RAM RMT3170EB68F9W1600 4GB SODIMM DDR3 1600MT/s                   | 2         | 0.86%   |
| Ramaxel RAM RMSA3300ME78HBF-2666 16GB SODIMM DDR4 2667MT/s                | 2         | 0.86%   |
| Nanya RAM Module 1GB SODIMM DDR2 667MT/s                                  | 2         | 0.86%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s                     | 2         | 0.86%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                      | 2         | 0.86%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s                    | 2         | 0.86%   |
| Kingston RAM Module 2GB SODIMM DDR2 667MT/s                               | 2         | 0.86%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1333MT/s                     | 2         | 0.86%   |
| 48spaces RAM 012345678901234567890123456789012345 2GB SODIMM DDR2 667MT/s | 2         | 0.86%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                               | 1         | 0.43%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                               | 1         | 0.43%   |
| Unknown RAM Module 4GB SODIMM DDR3                                        | 1         | 0.43%   |
| Unknown RAM Module 4GB SODIMM DDR2 667MT/s                                | 1         | 0.43%   |
| Unknown RAM Module 2GB SODIMM DDR3 1067MT/s                               | 1         | 0.43%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2133MT/s          | 1         | 0.43%   |
| Unknown (0x0809) RAM Module 8GB SODIMM DDR3 800MT/s                       | 1         | 0.43%   |
| Transcend RAM TS512MSK64W6H 4GB SODIMM DDR3 1600MT/s                      | 1         | 0.43%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 102       | 56.04%  |
| DDR4    | 46        | 25.27%  |
| DDR2    | 25        | 13.74%  |
| Unknown | 3         | 1.65%   |
| LPDDR3  | 2         | 1.1%    |
| SDRAM   | 1         | 0.55%   |
| LPDDR4  | 1         | 0.55%   |
| DRAM    | 1         | 0.55%   |
| DDR     | 1         | 0.55%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 177       | 97.79%  |
| Row Of Chips | 2         | 1.1%    |
| DIMM         | 1         | 0.55%   |
| Chip         | 1         | 0.55%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 71        | 34.47%  |
| 2048  | 57        | 27.67%  |
| 8192  | 51        | 24.76%  |
| 16384 | 14        | 6.8%    |
| 1024  | 11        | 5.34%   |
| 32768 | 2         | 0.97%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 60        | 29.85%  |
| 2667    | 20        | 9.95%   |
| 1333    | 20        | 9.95%   |
| 667     | 20        | 9.95%   |
| 1334    | 15        | 7.46%   |
| 2400    | 11        | 5.47%   |
| 2133    | 11        | 5.47%   |
| 1067    | 11        | 5.47%   |
| 3200    | 10        | 4.98%   |
| 800     | 8         | 3.98%   |
| 1867    | 5         | 2.49%   |
| Unknown | 5         | 2.49%   |
| 975     | 3         | 1.49%   |
| 1066    | 1         | 0.5%    |
| 533     | 1         | 0.5%    |

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
| Chicony Electronics                    | 39        | 29.77%  |
| Realtek Semiconductor                  | 13        | 9.92%   |
| Microdia                               | 10        | 7.63%   |
| Acer                                   | 10        | 7.63%   |
| IMC Networks                           | 9         | 6.87%   |
| Quanta                                 | 8         | 6.11%   |
| Sunplus Innovation Technology          | 7         | 5.34%   |
| Lite-On Technology                     | 7         | 5.34%   |
| Syntek                                 | 5         | 3.82%   |
| Suyin                                  | 4         | 3.05%   |
| Lenovo                                 | 3         | 2.29%   |
| Alcor Micro                            | 3         | 2.29%   |
| Z-Star Microelectronics                | 2         | 1.53%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 1.53%   |
| ALi                                    | 2         | 1.53%   |
| Silicon Motion                         | 1         | 0.76%   |
| Ricoh                                  | 1         | 0.76%   |
| Primax Electronics                     | 1         | 0.76%   |
| Luxvisions Innotech Limited            | 1         | 0.76%   |
| Importek                               | 1         | 0.76%   |
| DigiTech                               | 1         | 0.76%   |
| Apple                                  | 1         | 0.76%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Chicony HD WebCam                         | 6         | 4.55%   |
| Chicony Lenovo Integrated Camera (0.3MP)  | 5         | 3.79%   |
| Realtek Integrated_Webcam_HD              | 4         | 3.03%   |
| Lite-On Integrated Camera                 | 4         | 3.03%   |
| Chicony Integrated Camera                 | 4         | 3.03%   |
| Syntek Lenovo EasyCamera                  | 3         | 2.27%   |
| Realtek USB Camera                        | 3         | 2.27%   |
| Realtek Realtek USB2.0 PC Camera          | 3         | 2.27%   |
| Microdia Integrated Webcam                | 3         | 2.27%   |
| IMC Networks Integrated Camera            | 3         | 2.27%   |
| Chicony HD WebCam (Acer)                  | 3         | 2.27%   |
| Chicony EasyCamera                        | 3         | 2.27%   |
| Syntek EasyCamera                         | 2         | 1.52%   |
| Suyin HD Video WebCam                     | 2         | 1.52%   |
| Sunplus HD WebCam                         | 2         | 1.52%   |
| Quanta Realtek DMFT - RGB                 | 2         | 1.52%   |
| Quanta HP Webcam                          | 2         | 1.52%   |
| Quanta HP TrueVision HD Camera            | 2         | 1.52%   |
| Microdia Sonix USB 2.0 Camera             | 2         | 1.52%   |
| Microdia Integrated_Webcam_HD             | 2         | 1.52%   |
| Microdia Dell Laptop Integrated Webcam HD | 2         | 1.52%   |
| Lite-On HP HD Camera                      | 2         | 1.52%   |
| Lenovo Integrated Webcam [R5U877]         | 2         | 1.52%   |
| IMC Networks USB2.0 HD UVC WebCam         | 2         | 1.52%   |
| Chicony HP HD Webcam [Fixed]              | 2         | 1.52%   |
| Chicony Chicony USB 2.0 Camera            | 2         | 1.52%   |
| ALi Gateway Webcam                        | 2         | 1.52%   |
| Acer SunplusIT INC. Integrated Camera     | 2         | 1.52%   |
| Acer Lenovo EasyCamera                    | 2         | 1.52%   |
| Acer Integrated Camera                    | 2         | 1.52%   |
| Z-Star WebCam SC-03FFL11739P              | 1         | 0.76%   |
| Z-Star Webcam                             | 1         | 0.76%   |
| Suyin Laptop_Integrated_Webcam_FHD        | 1         | 0.76%   |
| Suyin Integrated_Webcam_HD                | 1         | 0.76%   |
| Sunplus Laptop_Integrated_Webcam_FHD      | 1         | 0.76%   |
| Sunplus Integrated_Webcam_HD              | 1         | 0.76%   |
| Sunplus Integrated Camera                 | 1         | 0.76%   |
| Sunplus HP Universal Camera               | 1         | 0.76%   |
| Sunplus HP HD Webcam [Fixed]              | 1         | 0.76%   |
| Silicon Motion HP Webcam-50               | 1         | 0.76%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 15        | 35.71%  |
| Upek                       | 11        | 26.19%  |
| AuthenTec                  | 7         | 16.67%  |
| STMicroelectronics         | 4         | 9.52%   |
| Shenzhen Goodix Technology | 2         | 4.76%   |
| LighTuning Technology      | 2         | 4.76%   |
| Synaptics                  | 1         | 2.38%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 9         | 21.43%  |
| STMicroelectronics Fingerprint Reader                  | 4         | 9.52%   |
| Validity Sensors VFS491                                | 3         | 7.14%   |
| Validity Sensors VFS5011 Fingerprint Reader            | 2         | 4.76%   |
| Validity Sensors VFS495 Fingerprint Reader             | 2         | 4.76%   |
| Validity Sensors VFS471 Fingerprint Reader             | 2         | 4.76%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 2         | 4.76%   |
| Validity Sensors Synaptics WBDI                        | 2         | 4.76%   |
| Upek TCS5B Fingerprint sensor                          | 2         | 4.76%   |
| Shenzhen Goodix Fingerprint Reader                     | 2         | 4.76%   |
| AuthenTec AES2501 Fingerprint Sensor                   | 2         | 4.76%   |
| AuthenTec AES1600                                      | 2         | 4.76%   |
| Validity Sensors Swipe Fingerprint Sensor              | 1         | 2.38%   |
| Validity Sensors Fingerprint scanner                   | 1         | 2.38%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 1         | 2.38%   |
| LighTuning ES603 Swipe Fingerprint Sensor              | 1         | 2.38%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 2.38%   |
| AuthenTec AuthenTec Inc. AES1660                       | 1         | 2.38%   |
| AuthenTec AES2810                                      | 1         | 2.38%   |
| AuthenTec AES1660 Fingerprint Sensor                   | 1         | 2.38%   |

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
| 1     | 64        | 34.22%  |
| 2     | 57        | 30.48%  |
| 0     | 34        | 18.18%  |
| 3     | 24        | 12.83%  |
| 4     | 8         | 4.28%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 116       | 43.28%  |
| Net/wireless             | 48        | 17.91%  |
| Fingerprint reader       | 40        | 14.93%  |
| Bluetooth                | 31        | 11.57%  |
| Card reader              | 28        | 10.45%  |
| Storage                  | 3         | 1.12%   |
| Sound                    | 1         | 0.37%   |
| Network                  | 1         | 0.37%   |

