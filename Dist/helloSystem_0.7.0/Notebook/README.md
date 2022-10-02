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

Total: 199

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
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
| Acer          | V5-131                      | [ff427cb0c9](https://bsd-hardware.info/?probe=ff427cb0c9) | Jan 18, 2022 |
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
| amd64 | 172       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 170       | 98.84%  |
| GNOME        | 2         | 1.16%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 172       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| SLiM | 172       | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 161       | 93.06%  |
| fr_FR | 3         | 1.73%   |
| es_ES | 3         | 1.73%   |
| C     | 3         | 1.73%   |
| uk_UA | 1         | 0.58%   |
| it_IT | 1         | 0.58%   |
| de_DE | 1         | 0.58%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 168       | 97.67%  |
| BIOS | 4         | 2.33%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Cd9660 | 91        | 52.3%   |
| Zfs    | 83        | 47.7%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 171       | 99.42%  |
| MBR  | 1         | 0.58%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 55        | 31.98%  |
| Hewlett-Packard     | 28        | 16.28%  |
| Dell                | 22        | 12.79%  |
| Acer                | 16        | 9.3%    |
| Apple               | 11        | 6.4%    |
| ASUSTek Computer    | 10        | 5.81%   |
| Toshiba             | 6         | 3.49%   |
| TUXEDO              | 3         | 1.74%   |
| Samsung Electronics | 3         | 1.74%   |
| Sony                | 2         | 1.16%   |
| MSI                 | 2         | 1.16%   |
| TWINHEAD            | 1         | 0.58%   |
| Razer               | 1         | 0.58%   |
| Panasonic           | 1         | 0.58%   |
| Packard Bell        | 1         | 0.58%   |
| Notebook            | 1         | 0.58%   |
| LG Electronics      | 1         | 0.58%   |
| Itautec             | 1         | 0.58%   |
| HASEE Computer      | 1         | 0.58%   |
| Gateway             | 1         | 0.58%   |
| Fujitsu             | 1         | 0.58%   |
| eMachines           | 1         | 0.58%   |
| DNS                 | 1         | 0.58%   |
| Alienware           | 1         | 0.58%   |
| Unknown             | 1         | 0.58%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                               | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Apple MacBook4,1                                   | 3         | 1.74%   |
| TUXEDO Aura 15 Gen1                                | 2         | 1.16%   |
| Dell Precision 7710                                | 2         | 1.16%   |
| Dell Latitude E5470                                | 2         | 1.16%   |
| Apple MacBook6,1                                   | 2         | 1.16%   |
| Acer V5-131                                        | 2         | 1.16%   |
| Acer Aspire E1-522                                 | 2         | 1.16%   |
| Acer Aspire 5930                                   | 2         | 1.16%   |
| TWINHEAD U12CT                                     | 1         | 0.58%   |
| TUXEDO InfinityBook13V3                            | 1         | 0.58%   |
| Toshiba Satellite S55t-B                           | 1         | 0.58%   |
| Toshiba Satellite P300                             | 1         | 0.58%   |
| Toshiba Satellite L550                             | 1         | 0.58%   |
| Toshiba Satellite C640                             | 1         | 0.58%   |
| Toshiba Satellite C50-B                            | 1         | 0.58%   |
| Toshiba PORTEGE R700                               | 1         | 0.58%   |
| Sony VGN-NW25GF_S                                  | 1         | 0.58%   |
| Sony SVZ1311C5E                                    | 1         | 0.58%   |
| Samsung N150P/N210P/N220P                          | 1         | 0.58%   |
| Samsung N100                                       | 1         | 0.58%   |
| Samsung 305E4A/305E5A/305E7A                       | 1         | 0.58%   |
| Razer Blade 15 Base Model (Early 2020) - RZ09-0328 | 1         | 0.58%   |
| Panasonic CF-B11JWCYS                              | 1         | 0.58%   |
| Packard Bell EasyNote TE69HW                       | 1         | 0.58%   |
| Notebook N15_17RD                                  | 1         | 0.58%   |
| MSI GF65 Thin 10SER                                | 1         | 0.58%   |
| MSI GF63 Thin 10SC                                 | 1         | 0.58%   |
| LG E300-A.CP20T                                    | 1         | 0.58%   |
| Lenovo Z50-70 20354                                | 1         | 0.58%   |
| Lenovo V310-14IKB 80T2                             | 1         | 0.58%   |
| Lenovo ThinkPad X61 Tablet 7763AD6                 | 1         | 0.58%   |
| Lenovo ThinkPad X61 7675K2U                        | 1         | 0.58%   |
| Lenovo ThinkPad X270 W10DG 20K5S0BM01              | 1         | 0.58%   |
| Lenovo ThinkPad X270 20HMS2LL00                    | 1         | 0.58%   |
| Lenovo ThinkPad X260 20F5S45W00                    | 1         | 0.58%   |
| Lenovo ThinkPad X250 20CLS1WP01                    | 1         | 0.58%   |
| Lenovo ThinkPad X240 20AMS2QDOC                    | 1         | 0.58%   |
| Lenovo ThinkPad X220 Tablet 4298B65                | 1         | 0.58%   |
| Lenovo ThinkPad X220 Tablet 42962WU                | 1         | 0.58%   |
| Lenovo ThinkPad X220 4293B43                       | 1         | 0.58%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 38        | 22.09%  |
| Acer Aspire             | 12        | 6.98%   |
| Dell Latitude           | 10        | 5.81%   |
| HP Pavilion             | 9         | 5.23%   |
| Lenovo IdeaPad          | 7         | 4.07%   |
| HP ProBook              | 6         | 3.49%   |
| Dell Inspiron           | 6         | 3.49%   |
| Toshiba Satellite       | 5         | 2.91%   |
| HP Laptop               | 3         | 1.74%   |
| HP EliteBook            | 3         | 1.74%   |
| Dell Precision          | 3         | 1.74%   |
| Apple MacBook4          | 3         | 1.74%   |
| TUXEDO Aura             | 2         | 1.16%   |
| Lenovo Legion           | 2         | 1.16%   |
| HP Compaq               | 2         | 1.16%   |
| Apple MacBookPro5       | 2         | 1.16%   |
| Apple MacBook6          | 2         | 1.16%   |
| Apple MacBook5          | 2         | 1.16%   |
| Acer V5-131             | 2         | 1.16%   |
| TWINHEAD U12CT          | 1         | 0.58%   |
| TUXEDO InfinityBook13V3 | 1         | 0.58%   |
| Toshiba PORTEGE         | 1         | 0.58%   |
| Sony VGN-NW25GF         | 1         | 0.58%   |
| Sony SVZ1311C5E         | 1         | 0.58%   |
| Samsung N150P           | 1         | 0.58%   |
| Samsung N100            | 1         | 0.58%   |
| Samsung 305E4A          | 1         | 0.58%   |
| Razer Blade             | 1         | 0.58%   |
| Panasonic CF-B11JWCYS   | 1         | 0.58%   |
| Packard Bell EasyNote   | 1         | 0.58%   |
| Notebook N15            | 1         | 0.58%   |
| MSI GF65                | 1         | 0.58%   |
| MSI GF63                | 1         | 0.58%   |
| LG E300-A.CP20T         | 1         | 0.58%   |
| Lenovo Z50-70           | 1         | 0.58%   |
| Lenovo V310-14IKB       | 1         | 0.58%   |
| Lenovo ThinkBook        | 1         | 0.58%   |
| Lenovo G51-35           | 1         | 0.58%   |
| Lenovo G50-30           | 1         | 0.58%   |
| Lenovo G40-30           | 1         | 0.58%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2016    | 15        | 8.72%   |
| 2013    | 15        | 8.72%   |
| 2011    | 15        | 8.72%   |
| 2021    | 14        | 8.14%   |
| 2018    | 14        | 8.14%   |
| 2015    | 14        | 8.14%   |
| 2010    | 13        | 7.56%   |
| 2020    | 11        | 6.4%    |
| 2017    | 10        | 5.81%   |
| 2012    | 10        | 5.81%   |
| 2009    | 9         | 5.23%   |
| 2008    | 9         | 5.23%   |
| 2014    | 8         | 4.65%   |
| 2007    | 5         | 2.91%   |
| 2019    | 4         | 2.33%   |
| 2022    | 3         | 1.74%   |
| 2006    | 2         | 1.16%   |
| Unknown | 1         | 0.58%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 172       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 172       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 66        | 38.37%  |
| 8.01-16.0   | 52        | 30.23%  |
| 16.01-24.0  | 30        | 17.44%  |
| 2.01-3.0    | 12        | 6.98%   |
| 32.01-64.0  | 6         | 3.49%   |
| 3.01-4.0    | 4         | 2.33%   |
| 24.01-32.0  | 1         | 0.58%   |
| 64.01-256.0 | 1         | 0.58%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 108       | 62.79%  |
| 0.51-1.0 | 48        | 27.91%  |
| 1.01-2.0 | 11        | 6.4%    |
| 2.01-3.0 | 5         | 2.91%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 128       | 73.99%  |
| 2      | 34        | 19.65%  |
| 0      | 8         | 4.62%   |
| 3      | 2         | 1.16%   |
| 4      | 1         | 0.58%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 93        | 54.07%  |
| Yes       | 79        | 45.93%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 161       | 93.6%   |
| No        | 11        | 6.4%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 171       | 99.42%  |
| No        | 1         | 0.58%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 113       | 65.7%   |
| No        | 59        | 34.3%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country             | Notebooks | Percent |
|---------------------|-----------|---------|
| USA                 | 27        | 15.7%   |
| Russia              | 12        | 6.98%   |
| Germany             | 11        | 6.4%    |
| Italy               | 10        | 5.81%   |
| UK                  | 9         | 5.23%   |
| Brazil              | 9         | 5.23%   |
| Spain               | 7         | 4.07%   |
| Netherlands         | 6         | 3.49%   |
| France              | 6         | 3.49%   |
| Romania             | 5         | 2.91%   |
| Mexico              | 5         | 2.91%   |
| China               | 5         | 2.91%   |
| Ukraine             | 4         | 2.33%   |
| Indonesia           | 4         | 2.33%   |
| Vietnam             | 3         | 1.74%   |
| Poland              | 3         | 1.74%   |
| Chile               | 3         | 1.74%   |
| Turkey              | 2         | 1.16%   |
| Sweden              | 2         | 1.16%   |
| Portugal            | 2         | 1.16%   |
| Peru                | 2         | 1.16%   |
| Norway              | 2         | 1.16%   |
| India               | 2         | 1.16%   |
| Hungary             | 2         | 1.16%   |
| Greece              | 2         | 1.16%   |
| Denmark             | 2         | 1.16%   |
| Czechia             | 2         | 1.16%   |
| Colombia            | 2         | 1.16%   |
| Trinidad and Tobago | 1         | 0.58%   |
| Tanzania            | 1         | 0.58%   |
| Taiwan              | 1         | 0.58%   |
| Switzerland         | 1         | 0.58%   |
| New Zealand         | 1         | 0.58%   |
| Myanmar             | 1         | 0.58%   |
| Malaysia            | 1         | 0.58%   |
| Lithuania           | 1         | 0.58%   |
| Latvia              | 1         | 0.58%   |
| Ireland             | 1         | 0.58%   |
| Iran                | 1         | 0.58%   |
| Georgia             | 1         | 0.58%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Moscow           | 4         | 2.3%    |
| Hanoi            | 3         | 1.72%   |
| Amsterdam        | 3         | 1.72%   |
| Warsaw           | 2         | 1.15%   |
| Lima             | 2         | 1.15%   |
| Leatherhead      | 2         | 1.15%   |
| Jakarta          | 2         | 1.15%   |
| Dijon            | 2         | 1.15%   |
| Bucharest        | 2         | 1.15%   |
| Zhaoqing         | 1         | 0.57%   |
| Zaporizhzhya     | 1         | 0.57%   |
| Zapopan          | 1         | 0.57%   |
| Youngsville      | 1         | 0.57%   |
| Yichun           | 1         | 0.57%   |
| Yaphank          | 1         | 0.57%   |
| Yangon           | 1         | 0.57%   |
| Wroclaw          | 1         | 0.57%   |
| Windsor          | 1         | 0.57%   |
| Washington       | 1         | 0.57%   |
| Vilnius          | 1         | 0.57%   |
| Ventura          | 1         | 0.57%   |
| VÃ¤sterÃ¥s   | 1         | 0.57%   |
| Vaudreuil-Dorion | 1         | 0.57%   |
| Vandalia         | 1         | 0.57%   |
| Ugarchin         | 1         | 0.57%   |
| Turley           | 1         | 0.57%   |
| Turin            | 1         | 0.57%   |
| Tromsø          | 1         | 0.57%   |
| Torokszentmiklos | 1         | 0.57%   |
| Tolyatti         | 1         | 0.57%   |
| Tiruchi          | 1         | 0.57%   |
| Thessaloniki     | 1         | 0.57%   |
| Tehran           | 1         | 0.57%   |
| Tarragona        | 1         | 0.57%   |
| Taipei           | 1         | 0.57%   |
| Susanville       | 1         | 0.57%   |
| Suceava          | 1         | 0.57%   |
| St Petersburg    | 1         | 0.57%   |
| Smolensk         | 1         | 0.57%   |
| Shah Alam        | 1         | 0.57%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 38        | 39     | 18.54%  |
| Samsung Electronics | 29        | 31     | 14.15%  |
| Seagate             | 21        | 24     | 10.24%  |
| Kingston            | 17        | 18     | 8.29%   |
| Toshiba             | 16        | 16     | 7.8%    |
| Crucial             | 12        | 12     | 5.85%   |
| SanDisk             | 10        | 11     | 4.88%   |
| Intel               | 8         | 9      | 3.9%    |
| Hitachi             | 8         | 8      | 3.9%    |
| HGST                | 6         | 6      | 2.93%   |
| Micron Technology   | 5         | 5      | 2.44%   |
| Fujitsu             | 4         | 4      | 1.95%   |
| A-DATA Technology   | 3         | 3      | 1.46%   |
| SPCC                | 2         | 3      | 0.98%   |
| SK hynix            | 2         | 2      | 0.98%   |
| Patriot             | 2         | 2      | 0.98%   |
| KingSpec            | 2         | 2      | 0.98%   |
| Intenso             | 2         | 2      | 0.98%   |
| Zheino              | 1         | 1      | 0.49%   |
| Transcend           | 1         | 1      | 0.49%   |
| Team                | 1         | 1      | 0.49%   |
| SSSTC               | 1         | 1      | 0.49%   |
| Netac               | 1         | 1      | 0.49%   |
| Mushkin             | 1         | 1      | 0.49%   |
| LITEON              | 1         | 1      | 0.49%   |
| Lexar               | 1         | 1      | 0.49%   |
| Leven               | 1         | 1      | 0.49%   |
| KIOXIA              | 1         | 1      | 0.49%   |
| Integral            | 1         | 1      | 0.49%   |
| INDMEM              | 1         | 1      | 0.49%   |
| Hewlett-Packard     | 1         | 1      | 0.49%   |
| Corsair             | 1         | 1      | 0.49%   |
| Apple               | 1         | 1      | 0.49%   |
| Apacer              | 1         | 1      | 0.49%   |
| ANACOMDA            | 1         | 1      | 0.49%   |
| AGI                 | 1         | 1      | 0.49%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| HGST HTS545050A7E680 500GB         | 5         | 2.39%   |
| WDC WDS120G2G0A-00JH30 120GB       | 4         | 1.91%   |
| Toshiba MQ01ABF050 500GB           | 4         | 1.91%   |
| Kingston SA400S37240G 240GB        | 4         | 1.91%   |
| Kingston SA400S37120G 120GB        | 3         | 1.44%   |
| Crucial CT500MX500SSD1 500GB       | 3         | 1.44%   |
| Crucial CT240BX500SSD1 240GB       | 3         | 1.44%   |
| WDC WDS240G2G0A-00JH30 240GB       | 2         | 0.96%   |
| WDC WD5000LPVX-22V0TT0 500GB       | 2         | 0.96%   |
| WDC WD5000LPCX-60VHAT0 500GB       | 2         | 0.96%   |
| WDC WD10JPCX-24UE4T0 1TB           | 2         | 0.96%   |
| Toshiba MQ01ABD100 1TB             | 2         | 0.96%   |
| SK hynix HFS256G39TND-N210A 256GB  | 2         | 0.96%   |
| Seagate ST500LT012-9WS142 500GB    | 2         | 0.96%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 2         | 0.96%   |
| Samsung SSD PM871 2.5 7mm 128GB    | 2         | 0.96%   |
| Samsung SSD 850 EVO 500GB          | 2         | 0.96%   |
| Samsung MZVLW256HEHP-000L7 256GB   | 2         | 0.96%   |
| Hitachi HTS541680J9SA00 80GB       | 2         | 0.96%   |
| Zheino CHN mSATAM1 256 256GB       | 1         | 0.48%   |
| WDC WDS500G2B0C-00PXH0 500GB       | 1         | 0.48%   |
| WDC WDS240G1G0A-00SS50 240GB       | 1         | 0.48%   |
| WDC WDBNCE5000PNC 500GB            | 1         | 0.48%   |
| WDC WD6400BPVT-60HXZT1 640GB       | 1         | 0.48%   |
| WDC WD6400BEVT-22A0RT0 640GB       | 1         | 0.48%   |
| WDC WD5000LPVX-80V0TT0 500GB       | 1         | 0.48%   |
| WDC WD5000LPLX-60ZNTT1 500GB       | 1         | 0.48%   |
| WDC WD5000LPCX-75VHAT0 500GB       | 1         | 0.48%   |
| WDC WD5000BPVT-22HXZT3 500GB       | 1         | 0.48%   |
| WDC WD5000BPKX-22HPJT0 500GB       | 1         | 0.48%   |
| WDC WD3200BEVT-22ZCT0 320GB        | 1         | 0.48%   |
| WDC WD3200BEKX-60B7WT0 320GB       | 1         | 0.48%   |
| WDC WD2500BEVT-00ZCT0 250GB        | 1         | 0.48%   |
| WDC WD2500BEVS-22UST0 250GB        | 1         | 0.48%   |
| WDC WD1600BEVT-80A23T0 160GB       | 1         | 0.48%   |
| WDC WD1600BEVT-22A23T0 160GB       | 1         | 0.48%   |
| WDC WD1600BEKT-66F3T2 160GB        | 1         | 0.48%   |
| WDC WD1200BEVS-75UST0 120GB        | 1         | 0.48%   |
| WDC WD1200BEVS-07RST0 120GB        | 1         | 0.48%   |
| WDC WD10SPZX-24Z10T0 1TB           | 1         | 0.48%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 26        | 27     | 32.5%   |
| Seagate             | 21        | 24     | 26.25%  |
| Toshiba             | 14        | 14     | 17.5%   |
| Hitachi             | 8         | 8      | 10%     |
| HGST                | 6         | 6      | 7.5%    |
| Fujitsu             | 3         | 3      | 3.75%   |
| Samsung Electronics | 2         | 2      | 2.5%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 16        | 17     | 16.84%  |
| Kingston            | 14        | 14     | 14.74%  |
| Crucial             | 12        | 12     | 12.63%  |
| SanDisk             | 10        | 11     | 10.53%  |
| WDC                 | 8         | 8      | 8.42%   |
| Intel               | 5         | 5      | 5.26%   |
| SPCC                | 2         | 3      | 2.11%   |
| SK hynix            | 2         | 2      | 2.11%   |
| Patriot             | 2         | 2      | 2.11%   |
| KingSpec            | 2         | 2      | 2.11%   |
| Intenso             | 2         | 2      | 2.11%   |
| A-DATA Technology   | 2         | 2      | 2.11%   |
| Zheino              | 1         | 1      | 1.05%   |
| Transcend           | 1         | 1      | 1.05%   |
| Toshiba             | 1         | 1      | 1.05%   |
| Team                | 1         | 1      | 1.05%   |
| Netac               | 1         | 1      | 1.05%   |
| Mushkin             | 1         | 1      | 1.05%   |
| Micron Technology   | 1         | 1      | 1.05%   |
| LITEON              | 1         | 1      | 1.05%   |
| Lexar               | 1         | 1      | 1.05%   |
| Leven               | 1         | 1      | 1.05%   |
| Integral            | 1         | 1      | 1.05%   |
| INDMEM              | 1         | 1      | 1.05%   |
| Hewlett-Packard     | 1         | 1      | 1.05%   |
| Fujitsu             | 1         | 1      | 1.05%   |
| Corsair             | 1         | 1      | 1.05%   |
| Apple               | 1         | 1      | 1.05%   |
| Apacer              | 1         | 1      | 1.05%   |
| ANACOMDA            | 1         | 1      | 1.05%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 84        | 98     | 44.68%  |
| HDD  | 74        | 84     | 39.36%  |
| NVMe | 30        | 33     | 15.96%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 149       | 182    | 83.24%  |
| NVMe | 30        | 33     | 16.76%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 126       | 148    | 80.25%  |
| 0.51-1.0   | 28        | 31     | 17.83%  |
| 1.01-2.0   | 2         | 2      | 1.27%   |
| 4.01-10.0  | 1         | 1      | 0.64%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 88        | 50.57%  |
| 101-250    | 37        | 21.26%  |
| 251-500    | 27        | 15.52%  |
| 501-1000   | 11        | 6.32%   |
| 21-50      | 6         | 3.45%   |
| 51-100     | 4         | 2.3%    |
| Unknown    | 1         | 0.57%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 168       | 97.67%  |
| 21-50   | 2         | 1.16%   |
| 101-250 | 1         | 0.58%   |
| Unknown | 1         | 0.58%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| WDC WD5000LPLX-60ZNTT1 500GB       | 1         | 1      | 2.38%   |
| WDC WD5000LPCX-75VHAT0 500GB       | 1         | 1      | 2.38%   |
| WDC WD5000LPCX-60VHAT0 500GB       | 1         | 1      | 2.38%   |
| WDC WD5000BPVT-22HXZT3 500GB       | 1         | 1      | 2.38%   |
| WDC WD3200BEVT-22ZCT0 320GB        | 1         | 1      | 2.38%   |
| WDC WD1600BEVT-80A23T0 160GB       | 1         | 1      | 2.38%   |
| WDC WD1600BEKT-66F3T2 160GB        | 1         | 1      | 2.38%   |
| WDC WD10SPZX-24Z10T0 1TB           | 1         | 1      | 2.38%   |
| WDC WD10JPVX-22JC3T0 1TB           | 1         | 1      | 2.38%   |
| Toshiba THNSNX024GMNT 24GB         | 1         | 1      | 2.38%   |
| Toshiba MQ01ABF050 500GB           | 1         | 1      | 2.38%   |
| Toshiba MQ01ABD100 1TB             | 1         | 1      | 2.38%   |
| Toshiba MQ01ABD075 752GB           | 1         | 1      | 2.38%   |
| Toshiba MK8034GSX 80GB             | 1         | 1      | 2.38%   |
| Toshiba MK7559GSXF 752GB           | 1         | 1      | 2.38%   |
| Toshiba MK6034GSX 64GB             | 1         | 1      | 2.38%   |
| Toshiba MK3265GSXN 320GB           | 1         | 1      | 2.38%   |
| Toshiba MK3261GSYN 320GB           | 1         | 1      | 2.38%   |
| Seagate ST9640320AS 640GB          | 1         | 1      | 2.38%   |
| Seagate ST9500325AS 500GB          | 1         | 1      | 2.38%   |
| Seagate ST9320423AS 320GB          | 1         | 1      | 2.38%   |
| Seagate ST9160412AS 160GB          | 1         | 1      | 2.38%   |
| Seagate ST9120821AS 118GB          | 1         | 1      | 2.38%   |
| Seagate ST500LT012-9WS142 500GB    | 1         | 1      | 2.38%   |
| Seagate ST320LT020-9YG142 320GB    | 1         | 1      | 2.38%   |
| Seagate ST320LT007-9ZV142 320GB    | 1         | 1      | 2.38%   |
| Seagate ST3160212AS 160GB          | 1         | 1      | 2.38%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1         | 1      | 2.38%   |
| Samsung Electronics HS082HB 80GB   | 1         | 1      | 2.38%   |
| Samsung Electronics HM160HI 160GB  | 1         | 1      | 2.38%   |
| LITEON CV8-8E128-HP 128GB          | 1         | 1      | 2.38%   |
| Kingston SV300S37A120G 120GB       | 1         | 1      | 2.38%   |
| Kingston SUV500MS480G 480GB        | 1         | 1      | 2.38%   |
| Hitachi HTS723216L9SA60 160GB      | 1         | 1      | 2.38%   |
| Hitachi HTS547564A9E384 640GB      | 1         | 1      | 2.38%   |
| Hitachi HTS545050A7E380 500GB      | 1         | 1      | 2.38%   |
| Hitachi HTS545025B9SA02 250GB      | 1         | 1      | 2.38%   |
| Hitachi HTS542516K9SA00 160GB      | 1         | 1      | 2.38%   |
| HGST HTS545050A7E680 500GB         | 1         | 1      | 2.38%   |
| HGST HTS541075A7E630 752GB         | 1         | 1      | 2.38%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 10     | 23.81%  |
| WDC                 | 9         | 9      | 21.43%  |
| Toshiba             | 9         | 9      | 21.43%  |
| Hitachi             | 5         | 5      | 11.9%   |
| Samsung Electronics | 2         | 2      | 4.76%   |
| Kingston            | 2         | 2      | 4.76%   |
| HGST                | 2         | 2      | 4.76%   |
| LITEON              | 1         | 1      | 2.38%   |
| Fujitsu             | 1         | 1      | 2.38%   |
| AGI                 | 1         | 1      | 2.38%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 10     | 27.03%  |
| WDC                 | 9         | 9      | 24.32%  |
| Toshiba             | 8         | 8      | 21.62%  |
| Hitachi             | 5         | 5      | 13.51%  |
| Samsung Electronics | 2         | 2      | 5.41%   |
| HGST                | 2         | 2      | 5.41%   |
| Fujitsu             | 1         | 1      | 2.7%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 34        | 37     | 87.18%  |
| SSD  | 4         | 4      | 10.26%  |
| NVMe | 1         | 1      | 2.56%   |

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
| Works    | 132       | 172    | 76.74%  |
| Malfunc  | 39        | 42     | 22.67%  |
| Detected | 1         | 1      | 0.58%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 140       | 73.3%   |
| AMD                              | 17        | 8.9%    |
| Samsung Electronics              | 12        | 6.28%   |
| Nvidia                           | 6         | 3.14%   |
| SanDisk                          | 4         | 2.09%   |
| Micron Technology                | 4         | 2.09%   |
| KIOXIA                           | 2         | 1.05%   |
| Kingston Technology Company      | 2         | 1.05%   |
| Solid State Storage Technology   | 1         | 0.52%   |
| Silicon Motion                   | 1         | 0.52%   |
| Silicon Integrated Systems [SiS] | 1         | 0.52%   |
| ADATA Technology                 | 1         | 0.52%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 17        | 8.17%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 17        | 8.17%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 16        | 7.69%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 13        | 6.25%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 11        | 5.29%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 10        | 4.81%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 9         | 4.33%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 9         | 4.33%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 8         | 3.85%   |
| Unknown                                                                          | 7         | 3.37%   |
| Nvidia MCP79 AHCI Controller                                                     | 6         | 2.88%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 6         | 2.88%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 6         | 2.88%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 5         | 2.4%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 5         | 2.4%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 5         | 2.4%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 4         | 1.92%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 4         | 1.92%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 4         | 1.92%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 3         | 1.44%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 3         | 1.44%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 3         | 1.44%   |
| Intel Comet Lake SATA AHCI Controller                                            | 3         | 1.44%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 2         | 0.96%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 2         | 0.96%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 2         | 0.96%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 2         | 0.96%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 2         | 0.96%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 2         | 0.96%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 2         | 0.96%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 2         | 0.96%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 2         | 0.96%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 0.48%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 0.48%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 1         | 0.48%   |
| SanDisk unknown                                                                  | 1         | 0.48%   |
| SanDisk PC SN530                                                                 | 1         | 0.48%   |
| Samsung NVMe SSD Controller 980                                                  | 1         | 0.48%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 1         | 0.48%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 1         | 0.48%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 151       | 74.02%  |
| NVMe | 29        | 14.22%  |
| IDE  | 17        | 8.33%   |
| RAID | 7         | 3.43%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 151       | 87.79%  |
| AMD    | 21        | 12.21%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz           | 8         | 4.65%   |
| Intel CPU Version                           | 5         | 2.91%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 4         | 2.33%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 4         | 2.33%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz        | 4         | 2.33%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 3         | 1.74%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 3         | 1.74%   |
| Intel Core i5-4300M CPU @ 2.60GHz           | 3         | 1.74%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 3         | 1.74%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 3         | 1.74%   |
| Intel Core 2 Duo CPU P7550 @ 2.26GHz        | 3         | 1.74%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 2         | 1.16%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 2         | 1.16%   |
| Intel Core i7-3612QM CPU @ 2.10GHz          | 2         | 1.16%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 2         | 1.16%   |
| Intel Core i5-9300H CPU @ 2.40GHz           | 2         | 1.16%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 2         | 1.16%   |
| Intel Core i5-7300U CPU @ 2.60GHz           | 2         | 1.16%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 2         | 1.16%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 2         | 1.16%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 2         | 1.16%   |
| Intel Core i5-10300H CPU @ 2.50GHz          | 2         | 1.16%   |
| Intel Core i3-6006U CPU @ 2.00GHz           | 2         | 1.16%   |
| Intel Core i3-4005U CPU @ 1.70GHz           | 2         | 1.16%   |
| Intel Core i3-3110M CPU @ 2.40GHz           | 2         | 1.16%   |
| Intel Core i3-2310M CPU @ 2.10GHz           | 2         | 1.16%   |
| Intel Core i3 CPU M 330 @ 2.13GHz           | 2         | 1.16%   |
| Intel Core 2 Duo CPU T6600 @ 2.20GHz        | 2         | 1.16%   |
| Intel Celeron CPU N3350 @ 1.10GHz           | 2         | 1.16%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 2         | 1.16%   |
| Intel Atom CPU N450 @ 1.66GHz               | 2         | 1.16%   |
| AMD Ryzen 7 4700U with Radeon Graphics      | 2         | 1.16%   |
| AMD E1-1200 APU with Radeon HD Graphics     | 2         | 1.16%   |
| Intel Xeon E-2276M CPU @ 2.80GHz            | 1         | 0.58%   |
| Intel Pentium M                             | 1         | 0.58%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 1         | 0.58%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz | 1         | 0.58%   |
| Intel Pentium CPU P6200 @ 2.13GH            | 1         | 0.58%   |
| Intel Pentium CPU N3700 @ 1.60GHz           | 1         | 0.58%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 1         | 0.58%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 58        | 33.72%  |
| Intel Core i7           | 21        | 12.21%  |
| Intel Core 2 Duo        | 21        | 12.21%  |
| Intel Core i3           | 18        | 10.47%  |
| Intel Celeron           | 12        | 6.98%   |
| AMD Ryzen 5             | 6         | 3.49%   |
| Other                   | 5         | 2.91%   |
| Intel Pentium           | 5         | 2.91%   |
| AMD A6                  | 4         | 2.33%   |
| Intel Atom              | 3         | 1.74%   |
| AMD Ryzen 7             | 3         | 1.74%   |
| AMD E1                  | 3         | 1.74%   |
| Intel Pentium Dual-Core | 2         | 1.16%   |
| Intel Core 2            | 2         | 1.16%   |
| AMD E2                  | 2         | 1.16%   |
| Intel Xeon              | 1         | 0.58%   |
| Intel Pentium M         | 1         | 0.58%   |
| Intel Genuine           | 1         | 0.58%   |
| Intel Core M            | 1         | 0.58%   |
| AMD Ryzen 3             | 1         | 0.58%   |
| AMD A8                  | 1         | 0.58%   |
| AMD A10                 | 1         | 0.58%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 100       | 58.14%  |
| 4       | 32        | 18.6%   |
| Unknown | 25        | 14.53%  |
| 8       | 6         | 3.49%   |
| 6       | 6         | 3.49%   |
| 12      | 2         | 1.16%   |
| 1       | 1         | 0.58%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 160       | 93.02%  |
| 2       | 10        | 5.81%   |
| Unknown | 2         | 1.16%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 99        | 57.56%  |
| 1       | 48        | 27.91%  |
| Unknown | 25        | 14.53%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| Penryn      | 22        | 12.79%  |
| KabyLake    | 19        | 11.05%  |
| IvyBridge   | 19        | 11.05%  |
| Haswell     | 16        | 9.3%    |
| Skylake     | 15        | 8.72%   |
| Westmere    | 14        | 8.14%   |
| SandyBridge | 14        | 8.14%   |
| Silvermont  | 9         | 5.23%   |
| Core        | 9         | 5.23%   |
| Broadwell   | 5         | 2.91%   |
| Zen+        | 4         | 2.33%   |
| Zen 2       | 4         | 2.33%   |
| CometLake   | 4         | 2.33%   |
| Jaguar      | 3         | 1.74%   |
| Bonnell     | 3         | 1.74%   |
| Bobcat      | 3         | 1.74%   |
| Goldmont    | 2         | 1.16%   |
| Excavator   | 2         | 1.16%   |
| Zen 3       | 1         | 0.58%   |
| Zen         | 1         | 0.58%   |
| Puma        | 1         | 0.58%   |
| Piledriver  | 1         | 0.58%   |
| K10 Llano   | 1         | 0.58%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 127       | 62.87%  |
| Nvidia | 38        | 18.81%  |
| AMD    | 37        | 18.32%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 18        | 8.41%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 14        | 6.54%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 11        | 5.14%   |
| Intel Core Processor Integrated Graphics Controller                                      | 11        | 5.14%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 9         | 4.21%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 9         | 4.21%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 9         | 4.21%   |
| Intel HD Graphics 620                                                                    | 7         | 3.27%   |
| Nvidia C79 [GeForce 9400M]                                                               | 5         | 2.34%   |
| Intel HD Graphics 530                                                                    | 5         | 2.34%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 2.34%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 2.34%   |
| Intel HD Graphics 5500                                                                   | 4         | 1.87%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 4         | 1.87%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 1.87%   |
| AMD Renoir                                                                               | 4         | 1.87%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 1.87%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 1.4%    |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 3         | 1.4%    |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 3         | 1.4%    |
| Intel UHD Graphics 620                                                                   | 3         | 1.4%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 1.4%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 1.4%    |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 3         | 1.4%    |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/545v]                                        | 3         | 1.4%    |
| Nvidia TU117M                                                                            | 2         | 0.93%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 0.93%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 2         | 0.93%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 2         | 0.93%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 0.93%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 0.93%   |
| Intel HD Graphics 500                                                                    | 2         | 0.93%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 0.93%   |
| AMD Wrestler [Radeon HD 7310]                                                            | 2         | 0.93%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 2         | 0.93%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 0.93%   |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                             | 2         | 0.93%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 1         | 0.47%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 0.47%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1         | 0.47%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 83        | 48.26%  |
| 1 x AMD        | 27        | 15.7%   |
| Intel + Nvidia | 20        | 11.63%  |
| 2 x Intel      | 17        | 9.88%   |
| 1 x Nvidia     | 14        | 8.14%   |
| Intel + AMD    | 7         | 4.07%   |
| AMD + Nvidia   | 3         | 1.74%   |
| 2 x Nvidia     | 1         | 0.58%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 153       | 88.95%  |
| Proprietary | 16        | 9.3%    |
| Unknown     | 3         | 1.74%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 132       | 76.74%  |
| 0.01-0.5   | 27        | 15.7%   |
| 0.51-1.0   | 6         | 3.49%   |
| 1.01-2.0   | 3         | 1.74%   |
| 5.01-6.0   | 2         | 1.16%   |
| 3.01-4.0   | 2         | 1.16%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 35        | 20%     |
| AU Optronics            | 28        | 16%     |
| Chimei Innolux          | 27        | 15.43%  |
| Samsung Electronics     | 23        | 13.14%  |
| Lenovo                  | 17        | 9.71%   |
| BOE                     | 17        | 9.71%   |
| Apple                   | 11        | 6.29%   |
| Chi Mei Optoelectronics | 2         | 1.14%   |
| Vestel Elektronik       | 1         | 0.57%   |
| Toshiba                 | 1         | 0.57%   |
| Sony                    | 1         | 0.57%   |
| SLD                     | 1         | 0.57%   |
| Sharp                   | 1         | 0.57%   |
| Philips                 | 1         | 0.57%   |
| PANDA                   | 1         | 0.57%   |
| LG Philips              | 1         | 0.57%   |
| Lenovo Group Limited    | 1         | 0.57%   |
| LED                     | 1         | 0.57%   |
| InfoVision              | 1         | 0.57%   |
| Goldstar                | 1         | 0.57%   |
| BenQ                    | 1         | 0.57%   |
| Ancor Communications    | 1         | 0.57%   |
| Acer                    | 1         | 0.57%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch       | 4         | 2.25%   |
| Lenovo LCD Monitor LEN4031 1280x800 300x190mm 14.0-inch                | 3         | 1.69%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 340x190mm 15.3-inch        | 3         | 1.69%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch   | 2         | 1.12%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 340x190mm 15.3-inch  | 2         | 1.12%   |
| LG Display LCD Monitor LGD0459 1920x1080 380x210mm 17.1-inch           | 2         | 1.12%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch            | 2         | 1.12%   |
| LG Display LCD Monitor LGD0250 1366x768 350x190mm 15.7-inch            | 2         | 1.12%   |
| Lenovo LCD Monitor LEN40B0 1366x768 340x190mm 15.3-inch                | 2         | 1.12%   |
| Lenovo LCD Monitor LEN40A0 1366x768 310x170mm 13.9-inch                | 2         | 1.12%   |
| Lenovo LCD Monitor LEN4035 1280x800 300x190mm 14.0-inch                | 2         | 1.12%   |
| Chimei Innolux LCD Monitor CMN1492 1366x768 310x170mm 13.9-inch        | 2         | 1.12%   |
| AU Optronics LCD Monitor AUO325C 1366x768 260x140mm 11.6-inch          | 2         | 1.12%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 340x190mm 15.3-inch          | 2         | 1.12%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 310x170mm 13.9-inch         | 2         | 1.12%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch          | 2         | 1.12%   |
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 710x400mm 32.1-inch     | 1         | 0.56%   |
| Toshiba TV TSB0108 1360x768 700x390mm 31.5-inch                        | 1         | 0.56%   |
| Sony LCD SNY06FA 1600x900 290x160mm 13.0-inch                          | 1         | 0.56%   |
| SLD LCD Monitor SLD003C 1366x768 310x170mm 13.9-inch                   | 1         | 0.56%   |
| Sharp LCD Monitor SHP14BA 1920x1080 340x190mm 15.3-inch                | 1         | 0.56%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 610x350mm 27.7-inch      | 1         | 0.56%   |
| Samsung Electronics S27C350 SAM0A3E 1920x1080 600x340mm 27.2-inch      | 1         | 0.56%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch      | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 410x230mm 18.5-inch  | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 330x210mm 15.4-inch   | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SEC4E41 1280x800 260x160mm 12.0-inch   | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SEC4542 1280x800 300x190mm 14.0-inch   | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SEC384A 1366x768 340x190mm 15.3-inch   | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SEC3847 1440x900 370x230mm 17.2-inch   | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SEC334A 1366x768 340x190mm 15.3-inch   | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SEC3157 1280x800 300x190mm 14.0-inch   | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 340x190mm 15.3-inch  | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SEC3052 1024x600 220x130mm 10.1-inch   | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 350x200mm 15.9-inch   | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch   | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 340x190mm 15.3-inch   | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 340x190mm 15.3-inch   | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 1420x800mm 64.2-inch | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SAM0DF7 3840x2160 1020x570mm 46.0-inch | 1         | 0.56%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 79        | 45.93%  |
| 1920x1080 (FHD)   | 46        | 26.74%  |
| 1280x800 (WXGA)   | 21        | 12.21%  |
| 1600x900 (HD+)    | 8         | 4.65%   |
| 3840x2160 (4K)    | 3         | 1.74%   |
| 1440x900 (WXGA+)  | 3         | 1.74%   |
| 1024x768 (XGA)    | 3         | 1.74%   |
| 2560x1440 (QHD)   | 2         | 1.16%   |
| 1920x540          | 2         | 1.16%   |
| 1024x600          | 2         | 1.16%   |
| 2560x1080         | 1         | 0.58%   |
| 1920x1200 (WUXGA) | 1         | 0.58%   |
| 1280x1024 (SXGA)  | 1         | 0.58%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 64        | 35.96%  |
| 13      | 49        | 27.53%  |
| 12      | 16        | 8.99%   |
| 17      | 10        | 5.62%   |
| 14      | 9         | 5.06%   |
| 11      | 6         | 3.37%   |
| 27      | 4         | 2.25%   |
| 24      | 3         | 1.69%   |
| 23      | 3         | 1.69%   |
| 10      | 3         | 1.69%   |
| 18      | 2         | 1.12%   |
| 64      | 1         | 0.56%   |
| 54      | 1         | 0.56%   |
| 42      | 1         | 0.56%   |
| 40      | 1         | 0.56%   |
| 34      | 1         | 0.56%   |
| 31      | 1         | 0.56%   |
| 20      | 1         | 0.56%   |
| 16      | 1         | 0.56%   |
| Unknown | 1         | 0.56%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 97        | 54.49%  |
| 201-300     | 50        | 28.09%  |
| 351-400     | 12        | 6.74%   |
| 501-600     | 9         | 5.06%   |
| 601-700     | 2         | 1.12%   |
| 401-500     | 2         | 1.12%   |
| 1001-1500   | 2         | 1.12%   |
| 801-900     | 1         | 0.56%   |
| 701-800     | 1         | 0.56%   |
| 901-1000    | 1         | 0.56%   |
| Unknown     | 1         | 0.56%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 133       | 80.12%  |
| 16/10   | 23        | 13.86%  |
| 3/2     | 4         | 2.41%   |
| 4/3     | 3         | 1.81%   |
| 5/4     | 1         | 0.6%    |
| 21/9    | 1         | 0.6%    |
| Unknown | 1         | 0.6%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 91-100         | 51        | 28.65%  |
| 81-90          | 50        | 28.09%  |
| 61-70          | 17        | 9.55%   |
| 101-110        | 14        | 7.87%   |
| 121-130        | 8         | 4.49%   |
| 71-80          | 7         | 3.93%   |
| 51-60          | 5         | 2.81%   |
| 201-250        | 5         | 2.81%   |
| 301-350        | 4         | 2.25%   |
| 41-50          | 3         | 1.69%   |
| More than 1000 | 2         | 1.12%   |
| 351-500        | 2         | 1.12%   |
| 141-150        | 2         | 1.12%   |
| 131-140        | 2         | 1.12%   |
| 501-1000       | 2         | 1.12%   |
| 251-300        | 1         | 0.56%   |
| 151-200        | 1         | 0.56%   |
| 111-120        | 1         | 0.56%   |
| Unknown        | 1         | 0.56%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 76        | 43.43%  |
| 121-160 | 69        | 39.43%  |
| 51-100  | 26        | 14.86%  |
| 161-240 | 3         | 1.71%   |
| Unknown | 1         | 0.57%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 152       | 87.86%  |
| 2     | 16        | 9.25%   |
| 0     | 5         | 2.89%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 90        | 31.36%  |
| Realtek Semiconductor             | 80        | 27.87%  |
| Qualcomm Atheros                  | 41        | 14.29%  |
| Broadcom                          | 33        | 11.5%   |
| Marvell Technology Group          | 9         | 3.14%   |
| Nvidia                            | 6         | 2.09%   |
| Xiaomi                            | 3         | 1.05%   |
| Ralink                            | 3         | 1.05%   |
| JMicron Technology                | 3         | 1.05%   |
| NetGear                           | 2         | 0.7%    |
| Ericsson Business Mobile Networks | 2         | 0.7%    |
| Edimax Technology                 | 2         | 0.7%    |
| Dell                              | 2         | 0.7%    |
| TP-Link                           | 1         | 0.35%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.35%   |
| Sierra Wireless                   | 1         | 0.35%   |
| Samsung Electronics               | 1         | 0.35%   |
| OPPO Electronics                  | 1         | 0.35%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.35%   |
| Mercucys                          | 1         | 0.35%   |
| Huawei Technologies               | 1         | 0.35%   |
| Hewlett-Packard                   | 1         | 0.35%   |
| Google                            | 1         | 0.35%   |
| D-Link System                     | 1         | 0.35%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 57        | 15.83%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 17        | 4.72%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 13        | 3.61%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 12        | 3.33%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 12        | 3.33%   |
| Intel Wireless 8260                                               | 11        | 3.06%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 8         | 2.22%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 7         | 1.94%   |
| Intel Wireless 7260                                               | 7         | 1.94%   |
| Intel Centrino Advanced-N 6200                                    | 7         | 1.94%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 6         | 1.67%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 6         | 1.67%   |
| Nvidia MCP79 Ethernet                                             | 6         | 1.67%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 6         | 1.67%   |
| Intel 82577LM Gigabit Network Connection                          | 6         | 1.67%   |
| Intel Wireless 7265                                               | 5         | 1.39%   |
| Intel WiFi Link 5100                                              | 5         | 1.39%   |
| Intel Wi-Fi 6 AX200                                               | 5         | 1.39%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 5         | 1.39%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 1.11%   |
| Intel Wireless 8265 / 8275                                        | 4         | 1.11%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 4         | 1.11%   |
| Intel Ethernet Connection I219-LM                                 | 4         | 1.11%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 1.11%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 4         | 1.11%   |
| Intel 82566MM Gigabit Network Connection                          | 4         | 1.11%   |
| Broadcom BCM4321 802.11a/b/g/n                                    | 4         | 1.11%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3         | 0.83%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 3         | 0.83%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 0.83%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 3         | 0.83%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 3         | 0.83%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 0.83%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 0.83%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 3         | 0.83%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 3         | 0.83%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3         | 0.83%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 3         | 0.83%   |
| Broadcom BCM43224 802.11a/b/g/n                                   | 3         | 0.83%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 3         | 0.83%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 89        | 48.37%  |
| Qualcomm Atheros      | 39        | 21.2%   |
| Realtek Semiconductor | 24        | 13.04%  |
| Broadcom              | 21        | 11.41%  |
| Ralink                | 3         | 1.63%   |
| NetGear               | 2         | 1.09%   |
| Edimax Technology     | 2         | 1.09%   |
| TP-Link               | 1         | 0.54%   |
| Sierra Wireless       | 1         | 0.54%   |
| Mercucys              | 1         | 0.54%   |
| Dell                  | 1         | 0.54%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 12        | 6.38%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 12        | 6.38%   |
| Intel Wireless 8260                                                     | 11        | 5.85%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 8         | 4.26%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 7         | 3.72%   |
| Intel Wireless 7260                                                     | 7         | 3.72%   |
| Intel Centrino Advanced-N 6200                                          | 7         | 3.72%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 6         | 3.19%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 6         | 3.19%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 6         | 3.19%   |
| Intel Wireless 7265                                                     | 5         | 2.66%   |
| Intel WiFi Link 5100                                                    | 5         | 2.66%   |
| Intel Wi-Fi 6 AX200                                                     | 5         | 2.66%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 5         | 2.66%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 2.13%   |
| Intel Wireless 8265 / 8275                                              | 4         | 2.13%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 4         | 2.13%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 4         | 2.13%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 4         | 2.13%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 3         | 1.6%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 3         | 1.6%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 3         | 1.6%    |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 1.6%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3         | 1.6%    |
| Broadcom BCM43224 802.11a/b/g/n                                         | 3         | 1.6%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 3         | 1.6%    |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 1.06%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 2         | 1.06%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 1.06%   |
| Realtek Realtek Bluetooth 4.2 Adapter                                   | 2         | 1.06%   |
| Realtek 802.11n WLAN Adapter                                            | 2         | 1.06%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 2         | 1.06%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.06%   |
| Intel Centrino Ultimate-N 6300                                          | 2         | 1.06%   |
| Intel Centrino Advanced-N 6235                                          | 2         | 1.06%   |
| Broadcom BCM43142 802.11b/g/n                                           | 2         | 1.06%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                     | 1         | 0.53%   |
| Sierra Wireless Sierra Wireless EM7345 4G LTE                           | 1         | 0.53%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 0.53%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.53%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 74        | 44.58%  |
| Intel                            | 46        | 27.71%  |
| Broadcom                         | 12        | 7.23%   |
| Marvell Technology Group         | 9         | 5.42%   |
| Qualcomm Atheros                 | 8         | 4.82%   |
| Nvidia                           | 6         | 3.61%   |
| Xiaomi                           | 3         | 1.81%   |
| JMicron Technology               | 3         | 1.81%   |
| Silicon Integrated Systems [SiS] | 1         | 0.6%    |
| Samsung Electronics              | 1         | 0.6%    |
| OPPO Electronics                 | 1         | 0.6%    |
| OnePlus Technology (Shenzhen)    | 1         | 0.6%    |
| Google                           | 1         | 0.6%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 57        | 34.34%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 17        | 10.24%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 13        | 7.83%   |
| Nvidia MCP79 Ethernet                                             | 6         | 3.61%   |
| Intel 82577LM Gigabit Network Connection                          | 6         | 3.61%   |
| Intel Ethernet Connection I219-LM                                 | 4         | 2.41%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 2.41%   |
| Intel 82566MM Gigabit Network Connection                          | 4         | 2.41%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 1.81%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 3         | 1.81%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 3         | 1.81%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 1.81%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 1.81%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 3         | 1.81%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 1.2%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 1.2%    |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 2         | 1.2%    |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.2%    |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 2         | 1.2%    |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.6%    |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.6%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.6%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.6%    |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.6%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.6%    |
| OPPO SDM720G-IDP _SN:8A58D65F RNDIS Control RNDIS Ethernet Data   | 1         | 0.6%    |
| OnePlus (Shenzhen) OnePlus RNDIS Control RNDIS Ethernet Data      | 1         | 0.6%    |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 0.6%    |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller             | 1         | 0.6%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 0.6%    |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller              | 1         | 0.6%    |
| Intel Ethernet Connection I219-V                                  | 1         | 0.6%    |
| Intel Ethernet Connection I218-V                                  | 1         | 0.6%    |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.6%    |
| Intel Ethernet Connection (3) I218-V                              | 1         | 0.6%    |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.6%    |
| Intel 82573L Gigabit Ethernet Controller                          | 1         | 0.6%    |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.6%    |
| Google Nexus/Pixel Device (tether)                                | 1         | 0.6%    |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 0.6%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 171       | 50.59%  |
| Ethernet | 161       | 47.63%  |
| Modem    | 3         | 0.89%   |
| Unknown  | 3         | 0.89%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 118       | 50.21%  |
| WiFi     | 113       | 48.09%  |
| Unknown  | 3         | 1.28%   |
| Modem    | 1         | 0.43%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 157       | 91.28%  |
| 1     | 14        | 8.14%   |
| 0     | 1         | 0.58%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 164       | 95.35%  |
| Yes  | 8         | 4.65%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 41        | 36.28%  |
| Broadcom                        | 15        | 13.27%  |
| Realtek Semiconductor           | 11        | 9.73%   |
| Qualcomm Atheros Communications | 11        | 9.73%   |
| Apple                           | 10        | 8.85%   |
| Lite-On Technology              | 6         | 5.31%   |
| Hewlett-Packard                 | 4         | 3.54%   |
| Foxconn / Hon Hai               | 4         | 3.54%   |
| Ralink                          | 3         | 2.65%   |
| IMC Networks                    | 3         | 2.65%   |
| Dell                            | 3         | 2.65%   |
| Cambridge Silicon Radio         | 2         | 1.77%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 25        | 21.74%  |
| Broadcom BCM2045B (BDC-2.1)                                 | 8         | 6.96%   |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                     | 6         | 5.22%   |
| Intel AX200 Bluetooth                                       | 5         | 4.35%   |
| Apple Bluetooth Host Controller                             | 5         | 4.35%   |
| Lite-On Atheros AR3012 Bluetooth                            | 4         | 3.48%   |
| Intel AX201 Bluetooth                                       | 4         | 3.48%   |
| Realtek  Bluetooth 4.0 Adapter                              | 3         | 2.61%   |
| Ralink RT3290 Bluetooth                                     | 3         | 2.61%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 3         | 2.61%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 3         | 2.61%   |
| Apple Built-in iSight (no firmware loaded)                  | 3         | 2.61%   |
| Realtek RTL8723B Bluetooth                                  | 2         | 1.74%   |
| Realtek  Bluetooth 4.2 Adapter                              | 2         | 1.74%   |
| Realtek Bluetooth Radio                                     | 2         | 1.74%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 2         | 1.74%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 2         | 1.74%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 2         | 1.74%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 2         | 1.74%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 2         | 1.74%   |
| Realtek RTL8821A Bluetooth                                  | 1         | 0.87%   |
| Realtek  Bluetooth Adapter                                  | 1         | 0.87%   |
| Realtek  Bluetooth 4.0 + High Speed Chip                    | 1         | 0.87%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1         | 0.87%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 1         | 0.87%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 1         | 0.87%   |
| Qualcomm Atheros AR3012 Bluetooth                           | 1         | 0.87%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)             | 1         | 0.87%   |
| Lite-On Realtek Bluetooth Adapter                           | 1         | 0.87%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 1         | 0.87%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 1         | 0.87%   |
| Intel Wireless-AC 3168 Bluetooth                            | 1         | 0.87%   |
| IMC Networks Realtek Bluetooth Adapter                      | 1         | 0.87%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS            | 1         | 0.87%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 1         | 0.87%   |
| HP Broadcom 2070 Bluetooth Combo                            | 1         | 0.87%   |
| HP Atheros AR9285 Malbec Bluetooth Adapter                  | 1         | 0.87%   |
| Foxconn / Hon Hai Qualcomm Atheros Bluetooth 4.0            | 1         | 0.87%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device             | 1         | 0.87%   |
| Dell Wireless 355 Bluetooth                                 | 1         | 0.87%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 143       | 73.71%  |
| AMD                              | 28        | 14.43%  |
| Nvidia                           | 18        | 9.28%   |
| GN Netcom                        | 2         | 1.03%   |
| Texas Instruments                | 1         | 0.52%   |
| Silicon Integrated Systems [SiS] | 1         | 0.52%   |
| Creative Technology              | 1         | 0.52%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 20        | 8.55%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 20        | 8.55%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 14        | 5.98%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 13        | 5.56%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 11        | 4.7%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 11        | 4.7%    |
| Intel 8 Series HD Audio Controller                                                                | 11        | 4.7%    |
| AMD Family 17h/19h HD Audio Controller                                                            | 10        | 4.27%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 9         | 3.85%   |
| AMD FCH Azalia Controller                                                                         | 9         | 3.85%   |
| Nvidia MCP79 High Definition Audio                                                                | 6         | 2.56%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 6         | 2.56%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5         | 2.14%   |
| Intel Cannon Lake PCH cAVS                                                                        | 5         | 2.14%   |
| Intel Broadwell-U Audio Controller                                                                | 5         | 2.14%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 5         | 2.14%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 5         | 2.14%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 2.14%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 1.71%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 4         | 1.71%   |
| Intel Comet Lake PCH cAVS                                                                         | 4         | 1.71%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 1.71%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 4         | 1.71%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 4         | 1.71%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4         | 1.71%   |
| AMD Kabini HDMI/DP Audio                                                                          | 4         | 1.71%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 3         | 1.28%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 1.28%   |
| AMD Wrestler HDMI Audio                                                                           | 3         | 1.28%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 0.85%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 0.85%   |
| AMD High Definition Audio Controller                                                              | 2         | 0.85%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 0.85%   |
| Texas Instruments PCM2900 Audio Codec                                                             | 1         | 0.43%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 0.43%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.43%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 1         | 0.43%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.43%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.43%   |
| GN Netcom Jabra UC VOICE 150a MS                                                                  | 1         | 0.43%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 54        | 27%     |
| SK hynix            | 33        | 16.5%   |
| Kingston            | 26        | 13%     |
| Micron Technology   | 17        | 8.5%    |
| Unknown             | 15        | 7.5%    |
| Nanya Technology    | 8         | 4%      |
| Ramaxel Technology  | 6         | 3%      |
| Elpida              | 6         | 3%      |
| Crucial             | 6         | 3%      |
| Unknown             | 5         | 2.5%    |
| A-DATA Technology   | 4         | 2%      |
| Smart               | 3         | 1.5%    |
| Silicon Power       | 2         | 1%      |
| ASint Technology    | 2         | 1%      |
| 48spaces            | 2         | 1%      |
| Unknown (ABCD)      | 1         | 0.5%    |
| Transcend           | 1         | 0.5%    |
| Smart Brazil        | 1         | 0.5%    |
| Sesame              | 1         | 0.5%    |
| PNY                 | 1         | 0.5%    |
| Kingmax             | 1         | 0.5%    |
| High Bridge         | 1         | 0.5%    |
| GOODRAM             | 1         | 0.5%    |
| Corsair             | 1         | 0.5%    |
| Avant               | 1         | 0.5%    |
| Apacer              | 1         | 0.5%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                                | 7         | 3.26%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 5         | 2.33%   |
| Unknown                                                                   | 5         | 2.33%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s                     | 4         | 1.86%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 4         | 1.86%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 4         | 1.86%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s                     | 4         | 1.86%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                                | 3         | 1.4%    |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s                     | 3         | 1.4%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 3         | 1.4%    |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s                    | 3         | 1.4%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s                     | 3         | 1.4%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s                     | 3         | 1.4%    |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s                   | 3         | 1.4%    |
| Unknown RAM Module 2GB SODIMM DDR2                                        | 2         | 0.93%   |
| SK hynix RAM HMT451S6MFR8A-PB 4GB SODIMM DDR3 800MT/s                     | 2         | 0.93%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s                    | 2         | 0.93%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 1333MT/s                     | 2         | 0.93%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                     | 2         | 0.93%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s                     | 2         | 0.93%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s                    | 2         | 0.93%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2400MT/s                     | 2         | 0.93%   |
| Ramaxel RAM RMSA3300ME78HBF-2666 16GB SODIMM DDR4 2667MT/s                | 2         | 0.93%   |
| Nanya RAM Module 1GB SODIMM DDR2 667MT/s                                  | 2         | 0.93%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s                     | 2         | 0.93%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                      | 2         | 0.93%   |
| Kingston RAM Module 2GB SODIMM DDR2 667MT/s                               | 2         | 0.93%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1333MT/s                     | 2         | 0.93%   |
| 48spaces RAM 012345678901234567890123456789012345 2GB SODIMM DDR2 667MT/s | 2         | 0.93%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                               | 1         | 0.47%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                               | 1         | 0.47%   |
| Unknown RAM Module 4GB SODIMM DDR3                                        | 1         | 0.47%   |
| Unknown RAM Module 4GB SODIMM DDR2 667MT/s                                | 1         | 0.47%   |
| Unknown RAM Module 2GB SODIMM DDR3 1067MT/s                               | 1         | 0.47%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2133MT/s          | 1         | 0.47%   |
| Transcend RAM TS512MSK64W6H 4GB SODIMM DDR3 1600MT/s                      | 1         | 0.47%   |
| Smart RAM SH564568FH8NZPHSCR 2GB SODIMM DDR3 1334MT/s                     | 1         | 0.47%   |
| Smart RAM SH564568FH8NWPHSFR 2GB SODIMM DDR3 1333MT/s                     | 1         | 0.47%   |
| Smart RAM SH564128FJ8NZRNSDG 4GB SODIMM DDR3 1600MT/s                     | 1         | 0.47%   |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s                     | 1         | 0.47%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 95        | 56.21%  |
| DDR4    | 43        | 25.44%  |
| DDR2    | 23        | 13.61%  |
| LPDDR3  | 2         | 1.18%   |
| Unknown | 2         | 1.18%   |
| SDRAM   | 1         | 0.59%   |
| LPDDR4  | 1         | 0.59%   |
| DRAM    | 1         | 0.59%   |
| DDR     | 1         | 0.59%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 165       | 98.21%  |
| Row Of Chips | 1         | 0.6%    |
| DIMM         | 1         | 0.6%    |
| Chip         | 1         | 0.6%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 66        | 34.92%  |
| 2048  | 51        | 26.98%  |
| 8192  | 47        | 24.87%  |
| 16384 | 14        | 7.41%   |
| 1024  | 9         | 4.76%   |
| 32768 | 2         | 1.06%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 55        | 29.41%  |
| 2667    | 20        | 10.7%   |
| 1333    | 19        | 10.16%  |
| 667     | 18        | 9.63%   |
| 1334    | 14        | 7.49%   |
| 1067    | 11        | 5.88%   |
| 3200    | 10        | 5.35%   |
| 2133    | 10        | 5.35%   |
| 2400    | 9         | 4.81%   |
| 800     | 7         | 3.74%   |
| Unknown | 5         | 2.67%   |
| 1867    | 4         | 2.14%   |
| 975     | 3         | 1.6%    |
| 1066    | 1         | 0.53%   |
| 533     | 1         | 0.53%   |

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
| Chicony Electronics                    | 37        | 30.58%  |
| Realtek Semiconductor                  | 13        | 10.74%  |
| Microdia                               | 10        | 8.26%   |
| IMC Networks                           | 9         | 7.44%   |
| Acer                                   | 9         | 7.44%   |
| Quanta                                 | 8         | 6.61%   |
| Lite-On Technology                     | 7         | 5.79%   |
| Suyin                                  | 4         | 3.31%   |
| Sunplus Innovation Technology          | 4         | 3.31%   |
| Syntek                                 | 3         | 2.48%   |
| Lenovo                                 | 3         | 2.48%   |
| Alcor Micro                            | 3         | 2.48%   |
| Z-Star Microelectronics                | 2         | 1.65%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 1.65%   |
| Silicon Motion                         | 1         | 0.83%   |
| Ricoh                                  | 1         | 0.83%   |
| Primax Electronics                     | 1         | 0.83%   |
| Luxvisions Innotech Limited            | 1         | 0.83%   |
| Importek                               | 1         | 0.83%   |
| Apple                                  | 1         | 0.83%   |
| ALi                                    | 1         | 0.83%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Chicony Lenovo Integrated Camera (0.3MP)  | 5         | 4.1%    |
| Chicony HD WebCam                         | 5         | 4.1%    |
| Realtek Integrated_Webcam_HD              | 4         | 3.28%   |
| Lite-On Integrated Camera                 | 4         | 3.28%   |
| Chicony Integrated Camera                 | 4         | 3.28%   |
| Realtek USB Camera                        | 3         | 2.46%   |
| Realtek Realtek USB2.0 PC Camera          | 3         | 2.46%   |
| Microdia Integrated Webcam                | 3         | 2.46%   |
| IMC Networks Integrated Camera            | 3         | 2.46%   |
| Chicony HD WebCam (Acer)                  | 3         | 2.46%   |
| Chicony EasyCamera                        | 3         | 2.46%   |
| Syntek Lenovo EasyCamera                  | 2         | 1.64%   |
| Suyin HD Video WebCam                     | 2         | 1.64%   |
| Quanta Realtek DMFT - RGB                 | 2         | 1.64%   |
| Quanta HP Webcam                          | 2         | 1.64%   |
| Quanta HP TrueVision HD Camera            | 2         | 1.64%   |
| Microdia Sonix USB 2.0 Camera             | 2         | 1.64%   |
| Microdia Integrated_Webcam_HD             | 2         | 1.64%   |
| Microdia Dell Laptop Integrated Webcam HD | 2         | 1.64%   |
| Lite-On HP HD Camera                      | 2         | 1.64%   |
| Lenovo Integrated Webcam [R5U877]         | 2         | 1.64%   |
| IMC Networks USB2.0 HD UVC WebCam         | 2         | 1.64%   |
| Chicony HP HD Webcam [Fixed]              | 2         | 1.64%   |
| Chicony Chicony USB 2.0 Camera            | 2         | 1.64%   |
| Acer SunplusIT INC. Integrated Camera     | 2         | 1.64%   |
| Acer Lenovo EasyCamera                    | 2         | 1.64%   |
| Acer Integrated Camera                    | 2         | 1.64%   |
| Z-Star WebCam SC-03FFL11739P              | 1         | 0.82%   |
| Z-Star Webcam                             | 1         | 0.82%   |
| Syntek EasyCamera                         | 1         | 0.82%   |
| Suyin Laptop_Integrated_Webcam_FHD        | 1         | 0.82%   |
| Suyin Integrated_Webcam_HD                | 1         | 0.82%   |
| Sunplus Integrated_Webcam_HD              | 1         | 0.82%   |
| Sunplus Integrated Camera                 | 1         | 0.82%   |
| Sunplus HP Universal Camera               | 1         | 0.82%   |
| Sunplus HD WebCam                         | 1         | 0.82%   |
| Silicon Motion HP Webcam-50               | 1         | 0.82%   |
| Ricoh USB2.0 Camera                       | 1         | 0.82%   |
| Realtek Lenovo EasyCamera                 | 1         | 0.82%   |
| Realtek Integrated_Webcam_FHD             | 1         | 0.82%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart_bsd/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 13        | 33.33%  |
| Upek                       | 11        | 28.21%  |
| AuthenTec                  | 7         | 17.95%  |
| STMicroelectronics         | 3         | 7.69%   |
| Shenzhen Goodix Technology | 2         | 5.13%   |
| LighTuning Technology      | 2         | 5.13%   |
| Synaptics                  | 1         | 2.56%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart_bsd/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 9         | 23.08%  |
| STMicroelectronics Fingerprint Reader                  | 3         | 7.69%   |
| Validity Sensors VFS5011 Fingerprint Reader            | 2         | 5.13%   |
| Validity Sensors VFS495 Fingerprint Reader             | 2         | 5.13%   |
| Validity Sensors VFS491                                | 2         | 5.13%   |
| Validity Sensors VFS471 Fingerprint Reader             | 2         | 5.13%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 2         | 5.13%   |
| Validity Sensors Synaptics WBDI                        | 2         | 5.13%   |
| Upek TCS5B Fingerprint sensor                          | 2         | 5.13%   |
| Shenzhen Goodix Fingerprint Reader                     | 2         | 5.13%   |
| AuthenTec AES2501 Fingerprint Sensor                   | 2         | 5.13%   |
| AuthenTec AES1600                                      | 2         | 5.13%   |
| Validity Sensors Fingerprint scanner                   | 1         | 2.56%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 1         | 2.56%   |
| LighTuning ES603 Swipe Fingerprint Sensor              | 1         | 2.56%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 2.56%   |
| AuthenTec AuthenTec Inc. AES1660                       | 1         | 2.56%   |
| AuthenTec AES2810                                      | 1         | 2.56%   |
| AuthenTec AES1660 Fingerprint Sensor                   | 1         | 2.56%   |

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
| 1     | 60        | 34.68%  |
| 2     | 51        | 29.48%  |
| 0     | 31        | 17.92%  |
| 3     | 24        | 13.87%  |
| 4     | 7         | 4.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 108       | 43.55%  |
| Net/wireless             | 45        | 18.15%  |
| Fingerprint reader       | 37        | 14.92%  |
| Bluetooth                | 29        | 11.69%  |
| Card reader              | 25        | 10.08%  |
| Storage                  | 2         | 0.81%   |
| Sound                    | 1         | 0.4%    |
| Network                  | 1         | 0.4%    |

