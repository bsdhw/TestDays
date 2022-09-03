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

Total: 191

| Vendor        | Model                       | Probe                                                     | Date         |
|---------------|-----------------------------|-----------------------------------------------------------|--------------|
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
| amd64 | 164       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart_bsd/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| helloDesktop | 162       | 98.78%  |
| GNOME        | 2         | 1.22%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart_bsd/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 164       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart_bsd/os_display_manager.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| SLiM | 164       | 100%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart_bsd/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 154       | 93.33%  |
| es_ES | 3         | 1.82%   |
| C     | 3         | 1.82%   |
| fr_FR | 2         | 1.21%   |
| uk_UA | 1         | 0.61%   |
| it_IT | 1         | 0.61%   |
| de_DE | 1         | 0.61%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart_bsd/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 160       | 97.56%  |
| BIOS | 4         | 2.44%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart_bsd/os_filesystem.svg)


| Type   | Notebooks | Percent |
|--------|-----------|---------|
| Cd9660 | 87        | 52.41%  |
| Zfs    | 79        | 47.59%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart_bsd/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 163       | 99.39%  |
| MBR  | 1         | 0.61%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart_bsd/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 49        | 29.88%  |
| Hewlett-Packard     | 28        | 17.07%  |
| Dell                | 21        | 12.8%   |
| Acer                | 16        | 9.76%   |
| ASUSTek Computer    | 10        | 6.1%    |
| Apple               | 10        | 6.1%    |
| Toshiba             | 6         | 3.66%   |
| TUXEDO              | 3         | 1.83%   |
| Samsung Electronics | 3         | 1.83%   |
| Sony                | 2         | 1.22%   |
| MSI                 | 2         | 1.22%   |
| TWINHEAD            | 1         | 0.61%   |
| Razer               | 1         | 0.61%   |
| Panasonic           | 1         | 0.61%   |
| Packard Bell        | 1         | 0.61%   |
| Notebook            | 1         | 0.61%   |
| LG Electronics      | 1         | 0.61%   |
| Itautec             | 1         | 0.61%   |
| HASEE Computer      | 1         | 0.61%   |
| Gateway             | 1         | 0.61%   |
| Fujitsu             | 1         | 0.61%   |
| eMachines           | 1         | 0.61%   |
| DNS                 | 1         | 0.61%   |
| Alienware           | 1         | 0.61%   |
| Unknown             | 1         | 0.61%   |

Model
-----

Motherboard model

![Model](./images/pie_chart_bsd/node_model.svg)


| Name                                               | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Apple MacBook4,1                                   | 3         | 1.83%   |
| TUXEDO Aura 15 Gen1                                | 2         | 1.22%   |
| Dell Latitude E5470                                | 2         | 1.22%   |
| Apple MacBook6,1                                   | 2         | 1.22%   |
| Acer V5-131                                        | 2         | 1.22%   |
| Acer Aspire E1-522                                 | 2         | 1.22%   |
| Acer Aspire 5930                                   | 2         | 1.22%   |
| TWINHEAD U12CT                                     | 1         | 0.61%   |
| TUXEDO InfinityBook13V3                            | 1         | 0.61%   |
| Toshiba Satellite S55t-B                           | 1         | 0.61%   |
| Toshiba Satellite P300                             | 1         | 0.61%   |
| Toshiba Satellite L550                             | 1         | 0.61%   |
| Toshiba Satellite C640                             | 1         | 0.61%   |
| Toshiba Satellite C50-B                            | 1         | 0.61%   |
| Toshiba PORTEGE R700                               | 1         | 0.61%   |
| Sony VGN-NW25GF_S                                  | 1         | 0.61%   |
| Sony SVZ1311C5E                                    | 1         | 0.61%   |
| Samsung N150P/N210P/N220P                          | 1         | 0.61%   |
| Samsung N100                                       | 1         | 0.61%   |
| Samsung 305E4A/305E5A/305E7A                       | 1         | 0.61%   |
| Razer Blade 15 Base Model (Early 2020) - RZ09-0328 | 1         | 0.61%   |
| Panasonic CF-B11JWCYS                              | 1         | 0.61%   |
| Packard Bell EasyNote TE69HW                       | 1         | 0.61%   |
| Notebook N15_17RD                                  | 1         | 0.61%   |
| MSI GF65 Thin 10SER                                | 1         | 0.61%   |
| MSI GF63 Thin 10SC                                 | 1         | 0.61%   |
| LG E300-A.CP20T                                    | 1         | 0.61%   |
| Lenovo Z50-70 20354                                | 1         | 0.61%   |
| Lenovo V310-14IKB 80T2                             | 1         | 0.61%   |
| Lenovo ThinkPad X61 7675K2U                        | 1         | 0.61%   |
| Lenovo ThinkPad X270 W10DG 20K5S0BM01              | 1         | 0.61%   |
| Lenovo ThinkPad X260 20F5S45W00                    | 1         | 0.61%   |
| Lenovo ThinkPad X250 20CLS1WP01                    | 1         | 0.61%   |
| Lenovo ThinkPad X240 20AMS2QDOC                    | 1         | 0.61%   |
| Lenovo ThinkPad X220 Tablet 4298B65                | 1         | 0.61%   |
| Lenovo ThinkPad X220 Tablet 42962WU                | 1         | 0.61%   |
| Lenovo ThinkPad X220 4293B43                       | 1         | 0.61%   |
| Lenovo ThinkPad X220 4293AF4                       | 1         | 0.61%   |
| Lenovo ThinkPad X220 4291H77                       | 1         | 0.61%   |
| Lenovo ThinkPad X1 Carbon 5th 20HRS04C00           | 1         | 0.61%   |
| Lenovo ThinkPad T61 766301U                        | 1         | 0.61%   |
| Lenovo ThinkPad T61 7661GY9                        | 1         | 0.61%   |
| Lenovo ThinkPad T60 1951FEG                        | 1         | 0.61%   |
| Lenovo ThinkPad T510 4384AJ6                       | 1         | 0.61%   |
| Lenovo ThinkPad T460 20FN004CUK                    | 1         | 0.61%   |
| Lenovo ThinkPad T460 20FMS75800                    | 1         | 0.61%   |
| Lenovo ThinkPad T440p 20AWS3RH00                   | 1         | 0.61%   |
| Lenovo ThinkPad T440p 20AWS0DU00                   | 1         | 0.61%   |
| Lenovo ThinkPad T440 20B7000PHV                    | 1         | 0.61%   |
| Lenovo ThinkPad T430s 2356CV6                      | 1         | 0.61%   |
| Lenovo ThinkPad T430 2349AK1                       | 1         | 0.61%   |
| Lenovo ThinkPad T420 4236MY0                       | 1         | 0.61%   |
| Lenovo ThinkPad T420 4236BD5                       | 1         | 0.61%   |
| Lenovo ThinkPad T410 2537EA8                       | 1         | 0.61%   |
| Lenovo ThinkPad T410 2522E38                       | 1         | 0.61%   |
| Lenovo ThinkPad T410 2522CS7                       | 1         | 0.61%   |
| Lenovo ThinkPad SL510 2847R96                      | 1         | 0.61%   |
| Lenovo ThinkPad R61 8935WCS                        | 1         | 0.61%   |
| Lenovo ThinkPad L450 20DSS1S402                    | 1         | 0.61%   |
| Lenovo ThinkPad L440 20ASS0FP00                    | 1         | 0.61%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart_bsd/node_model_family.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 34        | 20.73%  |
| Acer Aspire             | 12        | 7.32%   |
| Dell Latitude           | 10        | 6.1%    |
| HP Pavilion             | 9         | 5.49%   |
| Lenovo IdeaPad          | 7         | 4.27%   |
| HP ProBook              | 6         | 3.66%   |
| Dell Inspiron           | 6         | 3.66%   |
| Toshiba Satellite       | 5         | 3.05%   |
| HP Laptop               | 3         | 1.83%   |
| HP EliteBook            | 3         | 1.83%   |
| Apple MacBook4          | 3         | 1.83%   |
| TUXEDO Aura             | 2         | 1.22%   |
| HP Compaq               | 2         | 1.22%   |
| Dell Precision          | 2         | 1.22%   |
| Apple MacBook6          | 2         | 1.22%   |
| Apple MacBook5          | 2         | 1.22%   |
| Acer V5-131             | 2         | 1.22%   |
| TWINHEAD U12CT          | 1         | 0.61%   |
| TUXEDO InfinityBook13V3 | 1         | 0.61%   |
| Toshiba PORTEGE         | 1         | 0.61%   |
| Sony VGN-NW25GF         | 1         | 0.61%   |
| Sony SVZ1311C5E         | 1         | 0.61%   |
| Samsung N150P           | 1         | 0.61%   |
| Samsung N100            | 1         | 0.61%   |
| Samsung 305E4A          | 1         | 0.61%   |
| Razer Blade             | 1         | 0.61%   |
| Panasonic CF-B11JWCYS   | 1         | 0.61%   |
| Packard Bell EasyNote   | 1         | 0.61%   |
| Notebook N15            | 1         | 0.61%   |
| MSI GF65                | 1         | 0.61%   |
| MSI GF63                | 1         | 0.61%   |
| LG E300-A.CP20T         | 1         | 0.61%   |
| Lenovo Z50-70           | 1         | 0.61%   |
| Lenovo V310-14IKB       | 1         | 0.61%   |
| Lenovo ThinkBook        | 1         | 0.61%   |
| Lenovo Legion           | 1         | 0.61%   |
| Lenovo G51-35           | 1         | 0.61%   |
| Lenovo G40-30           | 1         | 0.61%   |
| Lenovo E31-80           | 1         | 0.61%   |
| Lenovo B470             | 1         | 0.61%   |
| Itautec Infoway         | 1         | 0.61%   |
| HP ZBook                | 1         | 0.61%   |
| HP Mini                 | 1         | 0.61%   |
| HP G62                  | 1         | 0.61%   |
| HP 2000                 | 1         | 0.61%   |
| HP 15                   | 1         | 0.61%   |
| HASEE CW35S             | 1         | 0.61%   |
| Gateway NE56R           | 1         | 0.61%   |
| Fujitsu LIFEBOOK        | 1         | 0.61%   |
| eMachines eME728        | 1         | 0.61%   |
| DNS W9x0LU              | 1         | 0.61%   |
| Dell Vostro             | 1         | 0.61%   |
| Dell Venue              | 1         | 0.61%   |
| Dell Studio             | 1         | 0.61%   |
| ASUS X556UJ             | 1         | 0.61%   |
| ASUS X555LA             | 1         | 0.61%   |
| ASUS X540LA             | 1         | 0.61%   |
| ASUS TUF                | 1         | 0.61%   |
| ASUS S550CA             | 1         | 0.61%   |
| ASUS N56VB              | 1         | 0.61%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart_bsd/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2021    | 15        | 9.15%   |
| 2013    | 15        | 9.15%   |
| 2018    | 14        | 8.54%   |
| 2015    | 14        | 8.54%   |
| 2011    | 14        | 8.54%   |
| 2016    | 13        | 7.93%   |
| 2010    | 13        | 7.93%   |
| 2020    | 10        | 6.1%    |
| 2017    | 9         | 5.49%   |
| 2012    | 9         | 5.49%   |
| 2009    | 9         | 5.49%   |
| 2008    | 9         | 5.49%   |
| 2014    | 6         | 3.66%   |
| 2007    | 5         | 3.05%   |
| 2019    | 4         | 2.44%   |
| 2022    | 2         | 1.22%   |
| 2006    | 2         | 1.22%   |
| Unknown | 1         | 0.61%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart_bsd/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 164       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart_bsd/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 164       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart_bsd/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 64        | 39.02%  |
| 8.01-16.0   | 50        | 30.49%  |
| 16.01-24.0  | 28        | 17.07%  |
| 2.01-3.0    | 11        | 6.71%   |
| 32.01-64.0  | 5         | 3.05%   |
| 3.01-4.0    | 4         | 2.44%   |
| 24.01-32.0  | 1         | 0.61%   |
| 64.01-256.0 | 1         | 0.61%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart_bsd/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 0.01-0.5 | 104       | 63.41%  |
| 0.51-1.0 | 45        | 27.44%  |
| 1.01-2.0 | 10        | 6.1%    |
| 2.01-3.0 | 5         | 3.05%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart_bsd/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 121       | 73.33%  |
| 2      | 33        | 20%     |
| 0      | 8         | 4.85%   |
| 3      | 2         | 1.21%   |
| 4      | 1         | 0.61%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart_bsd/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 86        | 52.44%  |
| Yes       | 78        | 47.56%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart_bsd/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 154       | 93.9%   |
| No        | 10        | 6.1%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart_bsd/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 163       | 99.39%  |
| No        | 1         | 0.61%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart_bsd/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 108       | 65.85%  |
| No        | 56        | 34.15%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart_bsd/node_location.svg)


| Country             | Notebooks | Percent |
|---------------------|-----------|---------|
| USA                 | 26        | 15.85%  |
| Russia              | 12        | 7.32%   |
| Italy               | 10        | 6.1%    |
| Germany             | 10        | 6.1%    |
| UK                  | 9         | 5.49%   |
| Brazil              | 9         | 5.49%   |
| Spain               | 7         | 4.27%   |
| France              | 6         | 3.66%   |
| Romania             | 5         | 3.05%   |
| Netherlands         | 5         | 3.05%   |
| Mexico              | 5         | 3.05%   |
| China               | 5         | 3.05%   |
| Ukraine             | 4         | 2.44%   |
| Indonesia           | 4         | 2.44%   |
| Vietnam             | 3         | 1.83%   |
| Chile               | 3         | 1.83%   |
| Turkey              | 2         | 1.22%   |
| Sweden              | 2         | 1.22%   |
| Portugal            | 2         | 1.22%   |
| Poland              | 2         | 1.22%   |
| Peru                | 2         | 1.22%   |
| Norway              | 2         | 1.22%   |
| India               | 2         | 1.22%   |
| Hungary             | 2         | 1.22%   |
| Greece              | 2         | 1.22%   |
| Denmark             | 2         | 1.22%   |
| Colombia            | 2         | 1.22%   |
| Trinidad and Tobago | 1         | 0.61%   |
| Tanzania            | 1         | 0.61%   |
| Taiwan              | 1         | 0.61%   |
| New Zealand         | 1         | 0.61%   |
| Myanmar             | 1         | 0.61%   |
| Malaysia            | 1         | 0.61%   |
| Lithuania           | 1         | 0.61%   |
| Latvia              | 1         | 0.61%   |
| Ireland             | 1         | 0.61%   |
| Iran                | 1         | 0.61%   |
| Georgia             | 1         | 0.61%   |
| Finland             | 1         | 0.61%   |
| Czechia             | 1         | 0.61%   |
| Cuba                | 1         | 0.61%   |
| Canada              | 1         | 0.61%   |
| Bulgaria            | 1         | 0.61%   |
| Belarus             | 1         | 0.61%   |
| Austria             | 1         | 0.61%   |
| Argentina           | 1         | 0.61%   |

City
----

Geographic location (city)

![City](./images/pie_chart_bsd/node_city.svg)


| City                          | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Moscow                        | 4         | 2.41%   |
| Hanoi                         | 3         | 1.81%   |
| Warsaw                        | 2         | 1.2%    |
| Lima                          | 2         | 1.2%    |
| Leatherhead                   | 2         | 1.2%    |
| Jakarta                       | 2         | 1.2%    |
| Dijon                         | 2         | 1.2%    |
| Bucharest                     | 2         | 1.2%    |
| Amsterdam                     | 2         | 1.2%    |
| Zhaoqing                      | 1         | 0.6%    |
| Zaporizhzhya                  | 1         | 0.6%    |
| Zapopan                       | 1         | 0.6%    |
| Youngsville                   | 1         | 0.6%    |
| Yichun                        | 1         | 0.6%    |
| Yaphank                       | 1         | 0.6%    |
| Yangon                        | 1         | 0.6%    |
| Windsor                       | 1         | 0.6%    |
| Washington                    | 1         | 0.6%    |
| Vilnius                       | 1         | 0.6%    |
| Ventura                       | 1         | 0.6%    |
| VÃ¤sterÃ¥s                | 1         | 0.6%    |
| Vaudreuil-Dorion              | 1         | 0.6%    |
| Vandalia                      | 1         | 0.6%    |
| Ugarchin                      | 1         | 0.6%    |
| Turley                        | 1         | 0.6%    |
| Turin                         | 1         | 0.6%    |
| Tromsø                       | 1         | 0.6%    |
| Torokszentmiklos              | 1         | 0.6%    |
| Tolyatti                      | 1         | 0.6%    |
| Tiruchi                       | 1         | 0.6%    |
| Thessaloniki                  | 1         | 0.6%    |
| Tehran                        | 1         | 0.6%    |
| Tarragona                     | 1         | 0.6%    |
| Taipei                        | 1         | 0.6%    |
| Susanville                    | 1         | 0.6%    |
| Suceava                       | 1         | 0.6%    |
| St Petersburg                 | 1         | 0.6%    |
| Smolensk                      | 1         | 0.6%    |
| Shah Alam                     | 1         | 0.6%    |
| Sevastopol                    | 1         | 0.6%    |
| Sesto San Giovanni            | 1         | 0.6%    |
| Seattle                       | 1         | 0.6%    |
| Scottsdale                    | 1         | 0.6%    |
| Sao Paulo                     | 1         | 0.6%    |
| Sao Bernardo do Campo         | 1         | 0.6%    |
| Santiago                      | 1         | 0.6%    |
| San SebastiÃ¡n de los Reyes | 1         | 0.6%    |
| San Luis PotosÃ­ City       | 1         | 0.6%    |
| San Antonio                   | 1         | 0.6%    |
| Riverton                      | 1         | 0.6%    |
| Rio de Janeiro                | 1         | 0.6%    |
| Riga                          | 1         | 0.6%    |
| Rho                           | 1         | 0.6%    |
| Ransbach-Baumbach             | 1         | 0.6%    |
| Quimper                       | 1         | 0.6%    |
| Putkilahti                    | 1         | 0.6%    |
| Pudong                        | 1         | 0.6%    |
| Pruszcz Gdanski               | 1         | 0.6%    |
| Potsdam                       | 1         | 0.6%    |
| Portland                      | 1         | 0.6%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart_bsd/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 38        | 39     | 19.39%  |
| Samsung Electronics | 27        | 29     | 13.78%  |
| Seagate             | 19        | 22     | 9.69%   |
| Toshiba             | 16        | 16     | 8.16%   |
| Kingston            | 16        | 17     | 8.16%   |
| Crucial             | 12        | 12     | 6.12%   |
| SanDisk             | 9         | 10     | 4.59%   |
| Intel               | 7         | 8      | 3.57%   |
| Hitachi             | 7         | 7      | 3.57%   |
| HGST                | 6         | 6      | 3.06%   |
| Micron Technology   | 5         | 5      | 2.55%   |
| Fujitsu             | 4         | 4      | 2.04%   |
| A-DATA Technology   | 3         | 3      | 1.53%   |
| SPCC                | 2         | 3      | 1.02%   |
| SK hynix            | 2         | 2      | 1.02%   |
| Patriot             | 2         | 2      | 1.02%   |
| KingSpec            | 2         | 2      | 1.02%   |
| Intenso             | 2         | 2      | 1.02%   |
| Zheino              | 1         | 1      | 0.51%   |
| Transcend           | 1         | 1      | 0.51%   |
| Team                | 1         | 1      | 0.51%   |
| SSSTC               | 1         | 1      | 0.51%   |
| Netac               | 1         | 1      | 0.51%   |
| Mushkin             | 1         | 1      | 0.51%   |
| LITEON              | 1         | 1      | 0.51%   |
| Lexar               | 1         | 1      | 0.51%   |
| KIOXIA              | 1         | 1      | 0.51%   |
| Integral            | 1         | 1      | 0.51%   |
| INDMEM              | 1         | 1      | 0.51%   |
| Hewlett-Packard     | 1         | 1      | 0.51%   |
| Corsair             | 1         | 1      | 0.51%   |
| Apple               | 1         | 1      | 0.51%   |
| Apacer              | 1         | 1      | 0.51%   |
| ANACOMDA            | 1         | 1      | 0.51%   |
| AGI                 | 1         | 1      | 0.51%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart_bsd/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| HGST HTS545050A7E680 500GB           | 5         | 2.5%    |
| WDC WDS120G2G0A-00JH30 120GB         | 4         | 2%      |
| Toshiba MQ01ABF050 500GB             | 4         | 2%      |
| Kingston SA400S37240G 240GB          | 4         | 2%      |
| Kingston SA400S37120G 120GB          | 3         | 1.5%    |
| Crucial CT500MX500SSD1 500GB         | 3         | 1.5%    |
| Crucial CT240BX500SSD1 240GB         | 3         | 1.5%    |
| WDC WDS240G2G0A-00JH30 240GB         | 2         | 1%      |
| WDC WD5000LPVX-22V0TT0 500GB         | 2         | 1%      |
| WDC WD5000LPCX-60VHAT0 500GB         | 2         | 1%      |
| WDC WD10JPCX-24UE4T0 1TB             | 2         | 1%      |
| Toshiba MQ01ABD100 1TB               | 2         | 1%      |
| SK hynix HFS256G39TND-N210A 256GB    | 2         | 1%      |
| Seagate ST500LT012-9WS142 500GB      | 2         | 1%      |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 2         | 1%      |
| Samsung SSD PM871 2.5 7mm 128GB      | 2         | 1%      |
| Samsung SSD 850 EVO 500GB            | 2         | 1%      |
| Samsung MZVLW256HEHP-000L7 256GB     | 2         | 1%      |
| Zheino CHN mSATAM1 256 256GB         | 1         | 0.5%    |
| WDC WDS500G2B0C-00PXH0 500GB         | 1         | 0.5%    |
| WDC WDS240G1G0A-00SS50 240GB         | 1         | 0.5%    |
| WDC WDBNCE5000PNC 500GB              | 1         | 0.5%    |
| WDC WD6400BPVT-60HXZT1 640GB         | 1         | 0.5%    |
| WDC WD6400BEVT-22A0RT0 640GB         | 1         | 0.5%    |
| WDC WD5000LPVX-80V0TT0 500GB         | 1         | 0.5%    |
| WDC WD5000LPLX-60ZNTT1 500GB         | 1         | 0.5%    |
| WDC WD5000LPCX-75VHAT0 500GB         | 1         | 0.5%    |
| WDC WD5000BPVT-22HXZT3 500GB         | 1         | 0.5%    |
| WDC WD5000BPKX-22HPJT0 500GB         | 1         | 0.5%    |
| WDC WD3200BEVT-22ZCT0 320GB          | 1         | 0.5%    |
| WDC WD3200BEKX-60B7WT0 320GB         | 1         | 0.5%    |
| WDC WD2500BEVT-00ZCT0 250GB          | 1         | 0.5%    |
| WDC WD2500BEVS-22UST0 250GB          | 1         | 0.5%    |
| WDC WD1600BEVT-80A23T0 160GB         | 1         | 0.5%    |
| WDC WD1600BEVT-22A23T0 160GB         | 1         | 0.5%    |
| WDC WD1600BEKT-66F3T2 160GB          | 1         | 0.5%    |
| WDC WD1200BEVS-75UST0 120GB          | 1         | 0.5%    |
| WDC WD1200BEVS-07RST0 120GB          | 1         | 0.5%    |
| WDC WD10SPZX-24Z10T0 1TB             | 1         | 0.5%    |
| WDC WD10SPZX-22Z10T1 1TB             | 1         | 0.5%    |
| WDC WD10SDZW-11UMGS0 1TB             | 1         | 0.5%    |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 0.5%    |
| WDC WD10JMVW-11AJGS4 1TB             | 1         | 0.5%    |
| WDC PC SN530 SDBPNPZ-512G-1002 512GB | 1         | 0.5%    |
| WDC PC SN530 SDBPMPZ-256G-1101 256GB | 1         | 0.5%    |
| WDC PC SN530 NVMe 256GB              | 1         | 0.5%    |
| Transcend TS240GMTS420S 240GB        | 1         | 0.5%    |
| Toshiba THNSNX024GMNT 24GB           | 1         | 0.5%    |
| Toshiba MQ04ABF100 1TB               | 1         | 0.5%    |
| Toshiba MQ01ABD075 752GB             | 1         | 0.5%    |
| Toshiba MK8034GSX 80GB               | 1         | 0.5%    |
| Toshiba MK7559GSXF 752GB             | 1         | 0.5%    |
| Toshiba MK6034GSX 64GB               | 1         | 0.5%    |
| Toshiba MK3265GSXN 320GB             | 1         | 0.5%    |
| Toshiba MK3261GSYN 320GB             | 1         | 0.5%    |
| Toshiba MK2561GSYN 250GB             | 1         | 0.5%    |
| Toshiba KBG40ZNT512G MEMORY 512GB    | 1         | 0.5%    |
| Team TEAML5Lite3D120G 120GB          | 1         | 0.5%    |
| SSSTC CL1-4D256 256GB                | 1         | 0.5%    |
| SPCC Solid State Disk 512GB          | 1         | 0.5%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart_bsd/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 26        | 27     | 33.77%  |
| Seagate             | 19        | 22     | 24.68%  |
| Toshiba             | 14        | 14     | 18.18%  |
| Hitachi             | 7         | 7      | 9.09%   |
| HGST                | 6         | 6      | 7.79%   |
| Fujitsu             | 3         | 3      | 3.9%    |
| Samsung Electronics | 2         | 2      | 2.6%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart_bsd/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 15        | 16     | 16.48%  |
| Kingston            | 13        | 13     | 14.29%  |
| Crucial             | 12        | 12     | 13.19%  |
| SanDisk             | 9         | 10     | 9.89%   |
| WDC                 | 8         | 8      | 8.79%   |
| Intel               | 5         | 5      | 5.49%   |
| SPCC                | 2         | 3      | 2.2%    |
| SK hynix            | 2         | 2      | 2.2%    |
| Patriot             | 2         | 2      | 2.2%    |
| KingSpec            | 2         | 2      | 2.2%    |
| Intenso             | 2         | 2      | 2.2%    |
| A-DATA Technology   | 2         | 2      | 2.2%    |
| Zheino              | 1         | 1      | 1.1%    |
| Transcend           | 1         | 1      | 1.1%    |
| Toshiba             | 1         | 1      | 1.1%    |
| Team                | 1         | 1      | 1.1%    |
| Netac               | 1         | 1      | 1.1%    |
| Mushkin             | 1         | 1      | 1.1%    |
| Micron Technology   | 1         | 1      | 1.1%    |
| LITEON              | 1         | 1      | 1.1%    |
| Lexar               | 1         | 1      | 1.1%    |
| Integral            | 1         | 1      | 1.1%    |
| INDMEM              | 1         | 1      | 1.1%    |
| Hewlett-Packard     | 1         | 1      | 1.1%    |
| Fujitsu             | 1         | 1      | 1.1%    |
| Corsair             | 1         | 1      | 1.1%    |
| Apple               | 1         | 1      | 1.1%    |
| Apacer              | 1         | 1      | 1.1%    |
| ANACOMDA            | 1         | 1      | 1.1%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart_bsd/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 80        | 94     | 44.69%  |
| HDD  | 71        | 81     | 39.66%  |
| NVMe | 28        | 31     | 15.64%  |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart_bsd/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 142       | 175    | 83.53%  |
| NVMe | 28        | 31     | 16.47%  |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart_bsd/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 120       | 142    | 80%     |
| 0.51-1.0   | 28        | 31     | 18.67%  |
| 1.01-2.0   | 1         | 1      | 0.67%   |
| 4.01-10.0  | 1         | 1      | 0.67%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart_bsd/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 1-20       | 85        | 51.2%   |
| 101-250    | 33        | 19.88%  |
| 251-500    | 26        | 15.66%  |
| 501-1000   | 11        | 6.63%   |
| 21-50      | 6         | 3.61%   |
| 51-100     | 4         | 2.41%   |
| Unknown    | 1         | 0.6%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart_bsd/drive_space_used.svg)


| Used GB | Notebooks | Percent |
|---------|-----------|---------|
| 1-20    | 160       | 97.56%  |
| 21-50   | 2         | 1.22%   |
| 101-250 | 1         | 0.61%   |
| Unknown | 1         | 0.61%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart_bsd/drive_malfunc.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| WDC WD5000LPLX-60ZNTT1 500GB       | 1         | 1      | 2.44%   |
| WDC WD5000LPCX-75VHAT0 500GB       | 1         | 1      | 2.44%   |
| WDC WD5000LPCX-60VHAT0 500GB       | 1         | 1      | 2.44%   |
| WDC WD5000BPVT-22HXZT3 500GB       | 1         | 1      | 2.44%   |
| WDC WD3200BEVT-22ZCT0 320GB        | 1         | 1      | 2.44%   |
| WDC WD1600BEVT-80A23T0 160GB       | 1         | 1      | 2.44%   |
| WDC WD1600BEKT-66F3T2 160GB        | 1         | 1      | 2.44%   |
| WDC WD10SPZX-24Z10T0 1TB           | 1         | 1      | 2.44%   |
| WDC WD10JPVX-22JC3T0 1TB           | 1         | 1      | 2.44%   |
| Toshiba THNSNX024GMNT 24GB         | 1         | 1      | 2.44%   |
| Toshiba MQ01ABF050 500GB           | 1         | 1      | 2.44%   |
| Toshiba MQ01ABD100 1TB             | 1         | 1      | 2.44%   |
| Toshiba MQ01ABD075 752GB           | 1         | 1      | 2.44%   |
| Toshiba MK8034GSX 80GB             | 1         | 1      | 2.44%   |
| Toshiba MK7559GSXF 752GB           | 1         | 1      | 2.44%   |
| Toshiba MK6034GSX 64GB             | 1         | 1      | 2.44%   |
| Toshiba MK3265GSXN 320GB           | 1         | 1      | 2.44%   |
| Toshiba MK3261GSYN 320GB           | 1         | 1      | 2.44%   |
| Seagate ST9640320AS 640GB          | 1         | 1      | 2.44%   |
| Seagate ST9500325AS 500GB          | 1         | 1      | 2.44%   |
| Seagate ST9320423AS 320GB          | 1         | 1      | 2.44%   |
| Seagate ST9120821AS 118GB          | 1         | 1      | 2.44%   |
| Seagate ST500LT012-9WS142 500GB    | 1         | 1      | 2.44%   |
| Seagate ST320LT020-9YG142 320GB    | 1         | 1      | 2.44%   |
| Seagate ST320LT007-9ZV142 320GB    | 1         | 1      | 2.44%   |
| Seagate ST3160212AS 160GB          | 1         | 1      | 2.44%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 1         | 1      | 2.44%   |
| Samsung Electronics HS082HB 80GB   | 1         | 1      | 2.44%   |
| Samsung Electronics HM160HI 160GB  | 1         | 1      | 2.44%   |
| LITEON CV8-8E128-HP 128GB          | 1         | 1      | 2.44%   |
| Kingston SV300S37A120G 120GB       | 1         | 1      | 2.44%   |
| Kingston SUV500MS480G 480GB        | 1         | 1      | 2.44%   |
| Hitachi HTS723216L9SA60 160GB      | 1         | 1      | 2.44%   |
| Hitachi HTS547564A9E384 640GB      | 1         | 1      | 2.44%   |
| Hitachi HTS545050A7E380 500GB      | 1         | 1      | 2.44%   |
| Hitachi HTS545025B9SA02 250GB      | 1         | 1      | 2.44%   |
| Hitachi HTS542516K9SA00 160GB      | 1         | 1      | 2.44%   |
| HGST HTS545050A7E680 500GB         | 1         | 1      | 2.44%   |
| HGST HTS541075A7E630 752GB         | 1         | 1      | 2.44%   |
| Fujitsu MHZ2250BH G2 250GB         | 1         | 1      | 2.44%   |
| AGI AGI512G16AI198 512GB           | 1         | 1      | 2.44%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart_bsd/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 9         | 9      | 21.95%  |
| Toshiba             | 9         | 9      | 21.95%  |
| Seagate             | 9         | 9      | 21.95%  |
| Hitachi             | 5         | 5      | 12.2%   |
| Samsung Electronics | 2         | 2      | 4.88%   |
| Kingston            | 2         | 2      | 4.88%   |
| HGST                | 2         | 2      | 4.88%   |
| LITEON              | 1         | 1      | 2.44%   |
| Fujitsu             | 1         | 1      | 2.44%   |
| AGI                 | 1         | 1      | 2.44%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart_bsd/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 9         | 9      | 25%     |
| Seagate             | 9         | 9      | 25%     |
| Toshiba             | 8         | 8      | 22.22%  |
| Hitachi             | 5         | 5      | 13.89%  |
| Samsung Electronics | 2         | 2      | 5.56%   |
| HGST                | 2         | 2      | 5.56%   |
| Fujitsu             | 1         | 1      | 2.78%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart_bsd/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 33        | 36     | 86.84%  |
| SSD  | 4         | 4      | 10.53%  |
| NVMe | 1         | 1      | 2.63%   |

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
| Works    | 125       | 164    | 76.22%  |
| Malfunc  | 38        | 41     | 23.17%  |
| Detected | 1         | 1      | 0.61%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart_bsd/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 133       | 73.08%  |
| AMD                              | 17        | 9.34%   |
| Samsung Electronics              | 11        | 6.04%   |
| Nvidia                           | 5         | 2.75%   |
| SanDisk                          | 4         | 2.2%    |
| Micron Technology                | 4         | 2.2%    |
| KIOXIA                           | 2         | 1.1%    |
| Kingston Technology Company      | 2         | 1.1%    |
| Solid State Storage Technology   | 1         | 0.55%   |
| Silicon Motion                   | 1         | 0.55%   |
| Silicon Integrated Systems [SiS] | 1         | 0.55%   |
| ADATA Technology                 | 1         | 0.55%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart_bsd/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 17        | 8.63%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 16        | 8.12%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 16        | 8.12%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 13        | 6.6%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 10        | 5.08%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 9         | 4.57%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 9         | 4.57%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 8         | 4.06%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 8         | 4.06%   |
| Unknown                                                                          | 7         | 3.55%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 6         | 3.05%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 6         | 3.05%   |
| Nvidia MCP79 AHCI Controller                                                     | 5         | 2.54%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 5         | 2.54%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 5         | 2.54%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 4         | 2.03%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 4         | 2.03%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 4         | 2.03%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 3         | 1.52%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 3         | 1.52%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 2         | 1.02%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2         | 1.02%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 2         | 1.02%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 2         | 1.02%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 2         | 1.02%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 2         | 1.02%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 2         | 1.02%   |
| Intel Comet Lake SATA AHCI Controller                                            | 2         | 1.02%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 2         | 1.02%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 2         | 1.02%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 2         | 1.02%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 2         | 1.02%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 1         | 0.51%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 1         | 0.51%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 1         | 0.51%   |
| SanDisk unknown                                                                  | 1         | 0.51%   |
| SanDisk PC SN530                                                                 | 1         | 0.51%   |
| Samsung NVMe SSD Controller 980                                                  | 1         | 0.51%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 1         | 0.51%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 1         | 0.51%   |
| Intel SATA Controller [RAID mode]                                                | 1         | 0.51%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                 | 1         | 0.51%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 1         | 0.51%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 1         | 0.51%   |
| AMD SB600 Non-Raid-5 SATA                                                        | 1         | 0.51%   |
| AMD SB600 IDE                                                                    | 1         | 0.51%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                      | 1         | 0.51%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart_bsd/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 143       | 74.09%  |
| NVMe | 27        | 13.99%  |
| IDE  | 16        | 8.29%   |
| RAID | 7         | 3.63%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart_bsd/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 143       | 87.2%   |
| AMD    | 21        | 12.8%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart_bsd/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz           | 8         | 4.88%   |
| Intel CPU Version                           | 5         | 3.05%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 4         | 2.44%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 4         | 2.44%   |
| Intel Core 2 Duo CPU T8300 @ 2.40GHz        | 4         | 2.44%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 3         | 1.83%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 3         | 1.83%   |
| Intel Core i5-4300M CPU @ 2.60GHz           | 3         | 1.83%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 3         | 1.83%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 3         | 1.83%   |
| Intel Core 2 Duo CPU P7550 @ 2.26GHz        | 3         | 1.83%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 2         | 1.22%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 2         | 1.22%   |
| Intel Core i7-3612QM CPU @ 2.10GHz          | 2         | 1.22%   |
| Intel Core i5-9300H CPU @ 2.40GHz           | 2         | 1.22%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 2         | 1.22%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 2         | 1.22%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 2         | 1.22%   |
| Intel Core i5-10300H CPU @ 2.50GHz          | 2         | 1.22%   |
| Intel Core i3-6006U CPU @ 2.00GHz           | 2         | 1.22%   |
| Intel Core i3-4005U CPU @ 1.70GHz           | 2         | 1.22%   |
| Intel Core i3-3110M CPU @ 2.40GHz           | 2         | 1.22%   |
| Intel Core i3-2310M CPU @ 2.10GHz           | 2         | 1.22%   |
| Intel Core i3 CPU M 330 @ 2.13GHz           | 2         | 1.22%   |
| Intel Core 2 Duo CPU T6600 @ 2.20GHz        | 2         | 1.22%   |
| Intel Celeron CPU N3350 @ 1.10GHz           | 2         | 1.22%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 2         | 1.22%   |
| Intel Atom CPU N450 @ 1.66GHz               | 2         | 1.22%   |
| AMD Ryzen 7 4700U with Radeon Graphics      | 2         | 1.22%   |
| AMD E1-1200 APU with Radeon HD Graphics     | 2         | 1.22%   |
| Intel Xeon E-2276M CPU @ 2.80GHz            | 1         | 0.61%   |
| Intel Pentium M                             | 1         | 0.61%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 1         | 0.61%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz | 1         | 0.61%   |
| Intel Pentium CPU P6200 @ 2.13GH            | 1         | 0.61%   |
| Intel Pentium CPU N3700 @ 1.60GHz           | 1         | 0.61%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 1         | 0.61%   |
| Intel Pentium CPU N3530 @ 2.16GHz           | 1         | 0.61%   |
| Intel Pentium CPU B950 @ 2.10GHz            | 1         | 0.61%   |
| Intel Genuine CPU                           | 1         | 0.61%   |
| Intel Core M-5Y71 CPU @ 1.20GHz             | 1         | 0.61%   |
| Intel Core i7-9750HF CPU @ 2.60GHz          | 1         | 0.61%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 1         | 0.61%   |
| Intel Core i7-7600U CPU @ 2.80GHz           | 1         | 0.61%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz          | 1         | 0.61%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 1         | 0.61%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz          | 1         | 0.61%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 1         | 0.61%   |
| Intel Core i7-4600U CPU @ 2.10GHz           | 1         | 0.61%   |
| Intel Core i7-3940XM CPU @ 3.00GHz          | 1         | 0.61%   |
| Intel Core i7-3630QM CPU @ 2.40GHz          | 1         | 0.61%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 1         | 0.61%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 1         | 0.61%   |
| Intel Core i5-7300U CPU @ 2.60GHz           | 1         | 0.61%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz          | 1         | 0.61%   |
| Intel Core i5-6440HQ CPU @ 2.60GHz          | 1         | 0.61%   |
| Intel Core i5-4310U CPU @ 2.00GHz           | 1         | 0.61%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 1         | 0.61%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 1         | 0.61%   |
| Intel Core i5-3437U CPU @ 1.90GHz           | 1         | 0.61%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart_bsd/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 56        | 34.15%  |
| Intel Core 2 Duo        | 19        | 11.59%  |
| Intel Core i7           | 18        | 10.98%  |
| Intel Core i3           | 18        | 10.98%  |
| Intel Celeron           | 11        | 6.71%   |
| AMD Ryzen 5             | 6         | 3.66%   |
| Other                   | 5         | 3.05%   |
| Intel Pentium           | 5         | 3.05%   |
| AMD A6                  | 4         | 2.44%   |
| Intel Atom              | 3         | 1.83%   |
| AMD Ryzen 7             | 3         | 1.83%   |
| AMD E1                  | 3         | 1.83%   |
| Intel Pentium Dual-Core | 2         | 1.22%   |
| Intel Core 2            | 2         | 1.22%   |
| AMD E2                  | 2         | 1.22%   |
| Intel Xeon              | 1         | 0.61%   |
| Intel Pentium M         | 1         | 0.61%   |
| Intel Genuine           | 1         | 0.61%   |
| Intel Core M            | 1         | 0.61%   |
| AMD Ryzen 3             | 1         | 0.61%   |
| AMD A8                  | 1         | 0.61%   |
| AMD A10                 | 1         | 0.61%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart_bsd/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 97        | 59.15%  |
| 4       | 30        | 18.29%  |
| Unknown | 23        | 14.02%  |
| 8       | 6         | 3.66%   |
| 6       | 5         | 3.05%   |
| 12      | 2         | 1.22%   |
| 1       | 1         | 0.61%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart_bsd/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 153       | 93.29%  |
| 2       | 9         | 5.49%   |
| Unknown | 2         | 1.22%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart_bsd/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 94        | 57.32%  |
| 1       | 47        | 28.66%  |
| Unknown | 23        | 14.02%  |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart_bsd/cpu_microarch.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| Penryn      | 21        | 12.8%   |
| IvyBridge   | 19        | 11.59%  |
| KabyLake    | 16        | 9.76%   |
| Haswell     | 15        | 9.15%   |
| Westmere    | 14        | 8.54%   |
| Skylake     | 14        | 8.54%   |
| SandyBridge | 14        | 8.54%   |
| Silvermont  | 8         | 4.88%   |
| Core        | 8         | 4.88%   |
| Broadwell   | 5         | 3.05%   |
| Zen+        | 4         | 2.44%   |
| Zen 2       | 4         | 2.44%   |
| CometLake   | 4         | 2.44%   |
| Jaguar      | 3         | 1.83%   |
| Bonnell     | 3         | 1.83%   |
| Bobcat      | 3         | 1.83%   |
| Goldmont    | 2         | 1.22%   |
| Excavator   | 2         | 1.22%   |
| Zen 3       | 1         | 0.61%   |
| Zen         | 1         | 0.61%   |
| Puma        | 1         | 0.61%   |
| Piledriver  | 1         | 0.61%   |
| K10 Llano   | 1         | 0.61%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart_bsd/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 121       | 62.69%  |
| AMD    | 37        | 19.17%  |
| Nvidia | 35        | 18.13%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart_bsd/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 18        | 8.87%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 14        | 6.9%    |
| Intel Core Processor Integrated Graphics Controller                                      | 11        | 5.42%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 10        | 4.93%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 9         | 4.43%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 8         | 3.94%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 8         | 3.94%   |
| Intel HD Graphics 620                                                                    | 6         | 2.96%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 2.46%   |
| Nvidia C79 [GeForce 9400M]                                                               | 4         | 1.97%   |
| Intel HD Graphics 5500                                                                   | 4         | 1.97%   |
| Intel HD Graphics 530                                                                    | 4         | 1.97%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 4         | 1.97%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 1.97%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 1.97%   |
| AMD Renoir                                                                               | 4         | 1.97%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 1.97%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 1.48%   |
| Intel UHD Graphics 620                                                                   | 3         | 1.48%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 1.48%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 3         | 1.48%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/545v]                                        | 3         | 1.48%   |
| Nvidia TU117M                                                                            | 2         | 0.99%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 0.99%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 2         | 0.99%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 2         | 0.99%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 2         | 0.99%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 2         | 0.99%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 2         | 0.99%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 2         | 0.99%   |
| Intel HD Graphics 500                                                                    | 2         | 0.99%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 0.99%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 0.99%   |
| AMD Wrestler [Radeon HD 7310]                                                            | 2         | 0.99%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 2         | 0.99%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 0.99%   |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                             | 2         | 0.99%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 1         | 0.49%   |
| Nvidia GP108M [GeForce MX150]                                                            | 1         | 0.49%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1         | 0.49%   |
| Nvidia GM204GLM [Quadro M4000M]                                                          | 1         | 0.49%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 0.49%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 0.49%   |
| Nvidia GK107M [GeForce GT 740M]                                                          | 1         | 0.49%   |
| Nvidia GK106M [GeForce GTX 765M]                                                         | 1         | 0.49%   |
| Nvidia GK104M [GeForce GTX 780M]                                                         | 1         | 0.49%   |
| Nvidia GF119M [GeForce GT 520M]                                                          | 1         | 0.49%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 0.49%   |
| Nvidia GF108M [GeForce GT 420M]                                                          | 1         | 0.49%   |
| Nvidia GF108GLM [NVS 5200M]                                                              | 1         | 0.49%   |
| Nvidia G86M [Quadro NVS 140M]                                                            | 1         | 0.49%   |
| Nvidia G86M [Quadro NVS 135M]                                                            | 1         | 0.49%   |
| Nvidia C79 [GeForce 9400M G]                                                             | 1         | 0.49%   |
| Intel HD Graphics 630                                                                    | 1         | 0.49%   |
| Intel HD Graphics 5300                                                                   | 1         | 0.49%   |
| Intel HD Graphics 520                                                                    | 1         | 0.49%   |
| AMD Wrestler [Radeon HD 7340]                                                            | 1         | 0.49%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 1         | 0.49%   |
| AMD Temash [Radeon HD 8250/8280G]                                                        | 1         | 0.49%   |
| AMD Sumo [Radeon HD 6520G]                                                               | 1         | 0.49%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart_bsd/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 79        | 48.17%  |
| 1 x AMD        | 27        | 16.46%  |
| Intel + Nvidia | 19        | 11.59%  |
| 2 x Intel      | 16        | 9.76%   |
| 1 x Nvidia     | 13        | 7.93%   |
| Intel + AMD    | 7         | 4.27%   |
| AMD + Nvidia   | 3         | 1.83%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart_bsd/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 147       | 89.63%  |
| Proprietary | 14        | 8.54%   |
| Unknown     | 3         | 1.83%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart_bsd/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 126       | 76.83%  |
| 0.01-0.5   | 26        | 15.85%  |
| 0.51-1.0   | 6         | 3.66%   |
| 1.01-2.0   | 3         | 1.83%   |
| 3.01-4.0   | 2         | 1.22%   |
| 5.01-6.0   | 1         | 0.61%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart_bsd/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 34        | 20.36%  |
| AU Optronics            | 27        | 16.17%  |
| Chimei Innolux          | 26        | 15.57%  |
| Samsung Electronics     | 22        | 13.17%  |
| Lenovo                  | 16        | 9.58%   |
| BOE                     | 16        | 9.58%   |
| Apple                   | 10        | 5.99%   |
| Chi Mei Optoelectronics | 2         | 1.2%    |
| Vestel Elektronik       | 1         | 0.6%    |
| Toshiba                 | 1         | 0.6%    |
| Sony                    | 1         | 0.6%    |
| SLD                     | 1         | 0.6%    |
| Sharp                   | 1         | 0.6%    |
| Philips                 | 1         | 0.6%    |
| PANDA                   | 1         | 0.6%    |
| LG Philips              | 1         | 0.6%    |
| Lenovo Group Limited    | 1         | 0.6%    |
| LED                     | 1         | 0.6%    |
| Goldstar                | 1         | 0.6%    |
| BenQ                    | 1         | 0.6%    |
| Ancor Communications    | 1         | 0.6%    |
| Acer                    | 1         | 0.6%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart_bsd/mon_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 310x170mm 13.9-inch       | 4         | 2.35%   |
| Lenovo LCD Monitor LEN4031 1280x800 300x190mm 14.0-inch                | 3         | 1.76%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 340x190mm 15.3-inch        | 3         | 1.76%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x170mm 13.9-inch   | 2         | 1.18%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 340x190mm 15.3-inch  | 2         | 1.18%   |
| LG Display LCD Monitor LGD02D8 1366x768 280x160mm 12.7-inch            | 2         | 1.18%   |
| LG Display LCD Monitor LGD0250 1366x768 350x190mm 15.7-inch            | 2         | 1.18%   |
| Lenovo LCD Monitor LEN40B0 1366x768 340x190mm 15.3-inch                | 2         | 1.18%   |
| Lenovo LCD Monitor LEN40A0 1366x768 310x170mm 13.9-inch                | 2         | 1.18%   |
| Lenovo LCD Monitor LEN4035 1280x800 300x190mm 14.0-inch                | 2         | 1.18%   |
| Chimei Innolux LCD Monitor CMN1492 1366x768 310x170mm 13.9-inch        | 2         | 1.18%   |
| AU Optronics LCD Monitor AUO325C 1366x768 260x140mm 11.6-inch          | 2         | 1.18%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 340x190mm 15.3-inch          | 2         | 1.18%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 310x170mm 13.9-inch         | 2         | 1.18%   |
| AU Optronics LCD Monitor AUO106C 1366x768 280x160mm 12.7-inch          | 2         | 1.18%   |
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 710x400mm 32.1-inch     | 1         | 0.59%   |
| Toshiba TV TSB0108 1360x768 700x390mm 31.5-inch                        | 1         | 0.59%   |
| Sony LCD SNY06FA 1600x900 290x160mm 13.0-inch                          | 1         | 0.59%   |
| SLD LCD Monitor SLD003C 1366x768 310x170mm 13.9-inch                   | 1         | 0.59%   |
| Sharp LCD Monitor SHP14BA 1920x1080 340x190mm 15.3-inch                | 1         | 0.59%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 610x350mm 27.7-inch      | 1         | 0.59%   |
| Samsung Electronics S27C350 SAM0A3E 1920x1080 600x340mm 27.2-inch      | 1         | 0.59%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch      | 1         | 0.59%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 410x230mm 18.5-inch  | 1         | 0.59%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 330x210mm 15.4-inch   | 1         | 0.59%   |
| Samsung Electronics LCD Monitor SEC4E41 1280x800 260x160mm 12.0-inch   | 1         | 0.59%   |
| Samsung Electronics LCD Monitor SEC4542 1280x800 300x190mm 14.0-inch   | 1         | 0.59%   |
| Samsung Electronics LCD Monitor SEC384A 1366x768 340x190mm 15.3-inch   | 1         | 0.59%   |
| Samsung Electronics LCD Monitor SEC3847 1440x900 370x230mm 17.2-inch   | 1         | 0.59%   |
| Samsung Electronics LCD Monitor SEC334A 1366x768 340x190mm 15.3-inch   | 1         | 0.59%   |
| Samsung Electronics LCD Monitor SEC3157 1280x800 300x190mm 14.0-inch   | 1         | 0.59%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 340x190mm 15.3-inch  | 1         | 0.59%   |
| Samsung Electronics LCD Monitor SEC3052 1024x600 220x130mm 10.1-inch   | 1         | 0.59%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 350x200mm 15.9-inch   | 1         | 0.59%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 280x160mm 12.7-inch   | 1         | 0.59%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 340x190mm 15.3-inch   | 1         | 0.59%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 1420x800mm 64.2-inch | 1         | 0.59%   |
| Samsung Electronics LCD Monitor SAM0DF7 3840x2160 1020x570mm 46.0-inch | 1         | 0.59%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch      | 1         | 0.59%   |
| Philips PHL 193V5 PHLC0CD 1366x768 410x230mm 18.5-inch                 | 1         | 0.59%   |
| PANDA LCD Monitor NCP002D 1920x1080 340x190mm 15.3-inch                | 1         | 0.59%   |
| LG Philips LCD Monitor LPL3B01 1280x800 330x210mm 15.4-inch            | 1         | 0.59%   |
| LG Display LCD Monitor LGD059B 1920x1080 290x170mm 13.2-inch           | 1         | 0.59%   |
| LG Display LCD Monitor LGD0521 1920x1080 310x170mm 13.9-inch           | 1         | 0.59%   |
| LG Display LCD Monitor LGD0508 1366x768 310x170mm 13.9-inch            | 1         | 0.59%   |
| LG Display LCD Monitor LGD04E2 1366x768 340x190mm 15.3-inch            | 1         | 0.59%   |
| LG Display LCD Monitor LGD0470 1920x1080 350x190mm 15.7-inch           | 1         | 0.59%   |
| LG Display LCD Monitor LGD046C 1920x1080 380x210mm 17.1-inch           | 1         | 0.59%   |
| LG Display LCD Monitor LGD0469 1920x1080 380x210mm 17.1-inch           | 1         | 0.59%   |
| LG Display LCD Monitor LGD0465 1366x768 340x190mm 15.3-inch            | 1         | 0.59%   |
| LG Display LCD Monitor LGD045E 1366x768 310x170mm 13.9-inch            | 1         | 0.59%   |
| LG Display LCD Monitor LGD045C 1366x768 350x190mm 15.7-inch            | 1         | 0.59%   |
| LG Display LCD Monitor LGD0459 1920x1080 380x210mm 17.1-inch           | 1         | 0.59%   |
| LG Display LCD Monitor LGD0455 1366x768 310x170mm 13.9-inch            | 1         | 0.59%   |
| LG Display LCD Monitor LGD0430 1366x768 350x190mm 15.7-inch            | 1         | 0.59%   |
| LG Display LCD Monitor LGD03DF 1366x768 340x190mm 15.3-inch            | 1         | 0.59%   |
| LG Display LCD Monitor LGD03CD 1366x768 280x160mm 12.7-inch            | 1         | 0.59%   |
| LG Display LCD Monitor LGD03AB 1366x768 340x190mm 15.3-inch            | 1         | 0.59%   |
| LG Display LCD Monitor LGD0395 1366x768 340x190mm 15.3-inch            | 1         | 0.59%   |
| LG Display LCD Monitor LGD0385 1366x768 310x170mm 13.9-inch            | 1         | 0.59%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart_bsd/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1366x768 (WXGA)   | 77        | 46.95%  |
| 1920x1080 (FHD)   | 42        | 25.61%  |
| 1280x800 (WXGA)   | 21        | 12.8%   |
| 1600x900 (HD+)    | 8         | 4.88%   |
| 3840x2160 (4K)    | 3         | 1.83%   |
| 2560x1440 (QHD)   | 2         | 1.22%   |
| 1920x540          | 2         | 1.22%   |
| 1440x900 (WXGA+)  | 2         | 1.22%   |
| 1024x768 (XGA)    | 2         | 1.22%   |
| 1024x600          | 2         | 1.22%   |
| 2560x1080         | 1         | 0.61%   |
| 1920x1200 (WUXGA) | 1         | 0.61%   |
| 1280x1024 (SXGA)  | 1         | 0.61%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart_bsd/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 61        | 35.88%  |
| 13      | 48        | 28.24%  |
| 12      | 14        | 8.24%   |
| 14      | 9         | 5.29%   |
| 17      | 8         | 4.71%   |
| 11      | 6         | 3.53%   |
| 27      | 4         | 2.35%   |
| 24      | 3         | 1.76%   |
| 23      | 3         | 1.76%   |
| 10      | 3         | 1.76%   |
| 18      | 2         | 1.18%   |
| 64      | 1         | 0.59%   |
| 54      | 1         | 0.59%   |
| 42      | 1         | 0.59%   |
| 40      | 1         | 0.59%   |
| 34      | 1         | 0.59%   |
| 31      | 1         | 0.59%   |
| 20      | 1         | 0.59%   |
| 16      | 1         | 0.59%   |
| Unknown | 1         | 0.59%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart_bsd/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 93        | 54.71%  |
| 201-300     | 48        | 28.24%  |
| 351-400     | 10        | 5.88%   |
| 501-600     | 9         | 5.29%   |
| 601-700     | 2         | 1.18%   |
| 401-500     | 2         | 1.18%   |
| 1001-1500   | 2         | 1.18%   |
| 801-900     | 1         | 0.59%   |
| 701-800     | 1         | 0.59%   |
| 901-1000    | 1         | 0.59%   |
| Unknown     | 1         | 0.59%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart_bsd/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 127       | 80.38%  |
| 16/10   | 22        | 13.92%  |
| 3/2     | 4         | 2.53%   |
| 4/3     | 2         | 1.27%   |
| 5/4     | 1         | 0.63%   |
| 21/9    | 1         | 0.63%   |
| Unknown | 1         | 0.63%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart_bsd/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 49        | 28.82%  |
| 91-100         | 49        | 28.82%  |
| 61-70          | 15        | 8.82%   |
| 101-110        | 13        | 7.65%   |
| 71-80          | 7         | 4.12%   |
| 121-130        | 6         | 3.53%   |
| 51-60          | 5         | 2.94%   |
| 201-250        | 5         | 2.94%   |
| 301-350        | 4         | 2.35%   |
| 41-50          | 3         | 1.76%   |
| More than 1000 | 2         | 1.18%   |
| 351-500        | 2         | 1.18%   |
| 141-150        | 2         | 1.18%   |
| 131-140        | 2         | 1.18%   |
| 501-1000       | 2         | 1.18%   |
| 251-300        | 1         | 0.59%   |
| 151-200        | 1         | 0.59%   |
| 111-120        | 1         | 0.59%   |
| Unknown        | 1         | 0.59%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart_bsd/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 72        | 43.11%  |
| 121-160 | 65        | 38.92%  |
| 51-100  | 26        | 15.57%  |
| 161-240 | 3         | 1.8%    |
| Unknown | 1         | 0.6%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart_bsd/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 144       | 87.27%  |
| 2     | 16        | 9.7%    |
| 0     | 5         | 3.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart_bsd/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 85        | 30.91%  |
| Realtek Semiconductor             | 77        | 28%     |
| Qualcomm Atheros                  | 41        | 14.91%  |
| Broadcom                          | 31        | 11.27%  |
| Marvell Technology Group          | 9         | 3.27%   |
| Nvidia                            | 5         | 1.82%   |
| Xiaomi                            | 3         | 1.09%   |
| Ralink                            | 3         | 1.09%   |
| JMicron Technology                | 3         | 1.09%   |
| NetGear                           | 2         | 0.73%   |
| Ericsson Business Mobile Networks | 2         | 0.73%   |
| Edimax Technology                 | 2         | 0.73%   |
| Dell                              | 2         | 0.73%   |
| TP-Link                           | 1         | 0.36%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.36%   |
| Sierra Wireless                   | 1         | 0.36%   |
| Samsung Electronics               | 1         | 0.36%   |
| OPPO Electronics                  | 1         | 0.36%   |
| Mercucys                          | 1         | 0.36%   |
| Huawei Technologies               | 1         | 0.36%   |
| Hewlett-Packard                   | 1         | 0.36%   |
| Google                            | 1         | 0.36%   |
| D-Link System                     | 1         | 0.36%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart_bsd/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 54        | 15.7%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 17        | 4.94%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 13        | 3.78%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 12        | 3.49%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 12        | 3.49%   |
| Intel Wireless 8260                                                     | 10        | 2.91%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 8         | 2.33%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 7         | 2.03%   |
| Intel Centrino Advanced-N 6200                                          | 7         | 2.03%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 6         | 1.74%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 6         | 1.74%   |
| Intel Wireless 7260                                                     | 6         | 1.74%   |
| Intel 82577LM Gigabit Network Connection                                | 6         | 1.74%   |
| Nvidia MCP79 Ethernet                                                   | 5         | 1.45%   |
| Intel Wireless 7265                                                     | 5         | 1.45%   |
| Intel WiFi Link 5100                                                    | 5         | 1.45%   |
| Intel Wi-Fi 6 AX200                                                     | 5         | 1.45%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 5         | 1.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 1.16%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 4         | 1.16%   |
| Intel Ethernet Connection I219-LM                                       | 4         | 1.16%   |
| Intel Ethernet Connection I217-LM                                       | 4         | 1.16%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 4         | 1.16%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 4         | 1.16%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 4         | 1.16%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 3         | 0.87%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 3         | 0.87%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 3         | 0.87%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                 | 3         | 0.87%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                  | 3         | 0.87%   |
| Intel Wireless 8265 / 8275                                              | 3         | 0.87%   |
| Intel Ethernet Connection I218-LM                                       | 3         | 0.87%   |
| Intel Ethernet Connection (2) I219-LM                                   | 3         | 0.87%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 3         | 0.87%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 0.87%   |
| Intel 82566MM Gigabit Network Connection                                | 3         | 0.87%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 3         | 0.87%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 3         | 0.87%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 3         | 0.87%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 2         | 0.58%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 0.58%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 2         | 0.58%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 0.58%   |
| Realtek Realtek Bluetooth 4.2 Adapter                                   | 2         | 0.58%   |
| Realtek 802.11n WLAN Adapter                                            | 2         | 0.58%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 2         | 0.58%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 2         | 0.58%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.58%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller                 | 2         | 0.58%   |
| Intel Centrino Ultimate-N 6300                                          | 2         | 0.58%   |
| Intel Centrino Advanced-N 6235                                          | 2         | 0.58%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 2         | 0.58%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                  | 2         | 0.58%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                    | 1         | 0.29%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                     | 1         | 0.29%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 1         | 0.29%   |
| Sierra Wireless Sierra Wireless EM7345 4G LTE                           | 1         | 0.29%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)             | 1         | 0.29%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 0.29%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.29%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart_bsd/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 84        | 47.73%  |
| Qualcomm Atheros      | 39        | 22.16%  |
| Realtek Semiconductor | 23        | 13.07%  |
| Broadcom              | 19        | 10.8%   |
| Ralink                | 3         | 1.7%    |
| NetGear               | 2         | 1.14%   |
| Edimax Technology     | 2         | 1.14%   |
| TP-Link               | 1         | 0.57%   |
| Sierra Wireless       | 1         | 0.57%   |
| Mercucys              | 1         | 0.57%   |
| Dell                  | 1         | 0.57%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart_bsd/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 12        | 6.67%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 12        | 6.67%   |
| Intel Wireless 8260                                                     | 10        | 5.56%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 8         | 4.44%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 7         | 3.89%   |
| Intel Centrino Advanced-N 6200                                          | 7         | 3.89%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 6         | 3.33%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 6         | 3.33%   |
| Intel Wireless 7260                                                     | 6         | 3.33%   |
| Intel Wireless 7265                                                     | 5         | 2.78%   |
| Intel WiFi Link 5100                                                    | 5         | 2.78%   |
| Intel Wi-Fi 6 AX200                                                     | 5         | 2.78%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 5         | 2.78%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 2.22%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 4         | 2.22%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 4         | 2.22%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 4         | 2.22%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 4         | 2.22%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 3         | 1.67%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 3         | 1.67%   |
| Intel Wireless 8265 / 8275                                              | 3         | 1.67%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 3         | 1.67%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 1.67%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 3         | 1.67%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 3         | 1.67%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 1.11%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 2         | 1.11%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 1.11%   |
| Realtek Realtek Bluetooth 4.2 Adapter                                   | 2         | 1.11%   |
| Realtek 802.11n WLAN Adapter                                            | 2         | 1.11%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 2         | 1.11%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.11%   |
| Intel Centrino Ultimate-N 6300                                          | 2         | 1.11%   |
| Intel Centrino Advanced-N 6235                                          | 2         | 1.11%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 2         | 1.11%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                     | 1         | 0.56%   |
| Sierra Wireless Sierra Wireless EM7345 4G LTE                           | 1         | 0.56%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 0.56%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.56%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 1         | 0.56%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 0.56%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 0.56%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 0.56%   |
| NetGear WNA1000M 802.11bgn [Realtek RTL8188CUS]                         | 1         | 0.56%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]             | 1         | 0.56%   |
| Mercucys MERCUSYS Wireless USB Adapter                                  | 1         | 0.56%   |
| Intel Wireless-AC 9260                                                  | 1         | 0.56%   |
| Intel Wireless 3160                                                     | 1         | 0.56%   |
| Intel Ultimate N WiFi Link 5300                                         | 1         | 0.56%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 1         | 0.56%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 1         | 0.56%   |
| Intel Centrino Wireless-N 100                                           | 1         | 0.56%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]          | 1         | 0.56%   |
| Edimax Edimax AC600 Wireless LAN USB Adapter                            | 1         | 0.56%   |
| Dell Hub of E-Port Replicator                                           | 1         | 0.56%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                      | 1         | 0.56%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 1         | 0.56%   |
| Broadcom BCM43227 802.11b/g/n                                           | 1         | 0.56%   |
| Broadcom BCM43225 802.11b/g/n                                           | 1         | 0.56%   |
| Broadcom BCM43142 802.11b/g/n                                           | 1         | 0.56%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart_bsd/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 71        | 44.94%  |
| Intel                            | 43        | 27.22%  |
| Broadcom                         | 12        | 7.59%   |
| Marvell Technology Group         | 9         | 5.7%    |
| Qualcomm Atheros                 | 8         | 5.06%   |
| Nvidia                           | 5         | 3.16%   |
| Xiaomi                           | 3         | 1.9%    |
| JMicron Technology               | 3         | 1.9%    |
| Silicon Integrated Systems [SiS] | 1         | 0.63%   |
| Samsung Electronics              | 1         | 0.63%   |
| OPPO Electronics                 | 1         | 0.63%   |
| Google                           | 1         | 0.63%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart_bsd/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 54        | 34.18%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 17        | 10.76%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 13        | 8.23%   |
| Intel 82577LM Gigabit Network Connection                          | 6         | 3.8%    |
| Nvidia MCP79 Ethernet                                             | 5         | 3.16%   |
| Intel Ethernet Connection I219-LM                                 | 4         | 2.53%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 2.53%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 1.9%    |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 3         | 1.9%    |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 3         | 1.9%    |
| Intel Ethernet Connection I218-LM                                 | 3         | 1.9%    |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 1.9%    |
| Intel 82566MM Gigabit Network Connection                          | 3         | 1.9%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 3         | 1.9%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 1.27%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 1.27%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 2         | 1.27%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 2         | 1.27%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.63%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 1         | 0.63%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.63%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.63%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.63%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.63%   |
| OPPO SDM720G-IDP _SN:8A58D65F RNDIS Control RNDIS Ethernet Data   | 1         | 0.63%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 0.63%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller             | 1         | 0.63%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 0.63%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller              | 1         | 0.63%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.63%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.63%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 0.63%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 0.63%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.63%   |
| Intel 82573L Gigabit Ethernet Controller                          | 1         | 0.63%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.63%   |
| Google Nexus/Pixel Device (tether)                                | 1         | 0.63%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 0.63%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1         | 0.63%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express          | 1         | 0.63%   |
| Broadcom NetXtreme BCM5753M Gigabit Ethernet PCI Express          | 1         | 0.63%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 0.63%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 0.63%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 1         | 0.63%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart_bsd/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 163       | 50.46%  |
| Ethernet | 154       | 47.68%  |
| Modem    | 3         | 0.93%   |
| Unknown  | 3         | 0.93%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart_bsd/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| Ethernet | 116       | 50.88%  |
| WiFi     | 108       | 47.37%  |
| Unknown  | 3         | 1.32%   |
| Modem    | 1         | 0.44%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart_bsd/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 150       | 91.46%  |
| 1     | 13        | 7.93%   |
| 0     | 1         | 0.61%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart_bsd/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 156       | 95.12%  |
| Yes  | 8         | 4.88%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart_bsd/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 39        | 36.11%  |
| Broadcom                        | 14        | 12.96%  |
| Qualcomm Atheros Communications | 11        | 10.19%  |
| Realtek Semiconductor           | 10        | 9.26%   |
| Apple                           | 9         | 8.33%   |
| Lite-On Technology              | 6         | 5.56%   |
| Hewlett-Packard                 | 4         | 3.7%    |
| Foxconn / Hon Hai               | 4         | 3.7%    |
| Ralink                          | 3         | 2.78%   |
| IMC Networks                    | 3         | 2.78%   |
| Dell                            | 3         | 2.78%   |
| Cambridge Silicon Radio         | 2         | 1.85%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart_bsd/bt_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 24        | 21.82%  |
| Broadcom BCM2045B (BDC-2.1)                                 | 8         | 7.27%   |
| Qualcomm Atheros  QCA9377 Bluetooth 4.1                     | 6         | 5.45%   |
| Intel AX200 Bluetooth                                       | 5         | 4.55%   |
| Lite-On Atheros AR3012 Bluetooth                            | 4         | 3.64%   |
| Intel AX201 Bluetooth                                       | 4         | 3.64%   |
| Apple Bluetooth Host Controller                             | 4         | 3.64%   |
| Realtek  Bluetooth 4.0 Adapter                              | 3         | 2.73%   |
| Ralink RT3290 Bluetooth                                     | 3         | 2.73%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]            | 3         | 2.73%   |
| Apple Built-in iSight (no firmware loaded)                  | 3         | 2.73%   |
| Realtek RTL8723B Bluetooth                                  | 2         | 1.82%   |
| Realtek  Bluetooth 4.2 Adapter                              | 2         | 1.82%   |
| Realtek Bluetooth Radio                                     | 2         | 1.82%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 2         | 1.82%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 2         | 1.82%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 2         | 1.82%   |
| Foxconn / Hon Hai Bluetooth USB Module                      | 2         | 1.82%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 2         | 1.82%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 2         | 1.82%   |
| Realtek RTL8821A Bluetooth                                  | 1         | 0.91%   |
| Realtek  Bluetooth 4.0 + High Speed Chip                    | 1         | 0.91%   |
| Qualcomm Atheros Dell Wireless 1707 Bluetooth 4.0 LE Device | 1         | 0.91%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 1         | 0.91%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 1         | 0.91%   |
| Qualcomm Atheros AR3012 Bluetooth                           | 1         | 0.91%   |
| Qualcomm Atheros AR3011 Bluetooth (no firmware)             | 1         | 0.91%   |
| Lite-On Realtek Bluetooth Adapter                           | 1         | 0.91%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 1         | 0.91%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 1         | 0.91%   |
| Intel Wireless-AC 3168 Bluetooth                            | 1         | 0.91%   |
| IMC Networks Realtek Bluetooth Adapter                      | 1         | 0.91%   |
| IMC Networks Qualcomm Atheros Bluetooth 4.0 + HS            | 1         | 0.91%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 1         | 0.91%   |
| HP Broadcom 2070 Bluetooth Combo                            | 1         | 0.91%   |
| HP Atheros AR9285 Malbec Bluetooth Adapter                  | 1         | 0.91%   |
| Foxconn / Hon Hai Qualcomm Atheros Bluetooth 4.0            | 1         | 0.91%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device             | 1         | 0.91%   |
| Dell Wireless 355 Bluetooth                                 | 1         | 0.91%   |
| Dell DW375 Bluetooth Module                                 | 1         | 0.91%   |
| Dell Dell Wireless 380 Bluetooth 4.0 Module                 | 1         | 0.91%   |
| Broadcom Broadcom BCM2070 Bluetooth 2.1+EDR USB Device      | 1         | 0.91%   |
| Broadcom BCM43142 Bluetooth 4.0                             | 1         | 0.91%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                  | 1         | 0.91%   |
| Apple Broadcom Bluetooth 2.1 module                         | 1         | 0.91%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart_bsd/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 136       | 73.51%  |
| AMD                              | 28        | 15.14%  |
| Nvidia                           | 16        | 8.65%   |
| GN Netcom                        | 2         | 1.08%   |
| Texas Instruments                | 1         | 0.54%   |
| Silicon Integrated Systems [SiS] | 1         | 0.54%   |
| Creative Technology              | 1         | 0.54%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart_bsd/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 20        | 8.93%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 19        | 8.48%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 14        | 6.25%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 13        | 5.8%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 10        | 4.46%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 10        | 4.46%   |
| Intel 8 Series HD Audio Controller                                                                | 10        | 4.46%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 10        | 4.46%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 9         | 4.02%   |
| AMD FCH Azalia Controller                                                                         | 9         | 4.02%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 6         | 2.68%   |
| Nvidia MCP79 High Definition Audio                                                                | 5         | 2.23%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5         | 2.23%   |
| Intel Broadwell-U Audio Controller                                                                | 5         | 2.23%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 5         | 2.23%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 1.79%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 4         | 1.79%   |
| Intel Comet Lake PCH cAVS                                                                         | 4         | 1.79%   |
| Intel Cannon Lake PCH cAVS                                                                        | 4         | 1.79%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 1.79%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 1.79%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 4         | 1.79%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 4         | 1.79%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 4         | 1.79%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4         | 1.79%   |
| AMD Kabini HDMI/DP Audio                                                                          | 4         | 1.79%   |
| AMD Wrestler HDMI Audio                                                                           | 3         | 1.34%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 0.89%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 2         | 0.89%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 0.89%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 0.89%   |
| AMD High Definition Audio Controller                                                              | 2         | 0.89%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 2         | 0.89%   |
| Texas Instruments PCM2900 Audio Codec                                                             | 1         | 0.45%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 1         | 0.45%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.45%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 1         | 0.45%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.45%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.45%   |
| GN Netcom Jabra UC VOICE 150a MS                                                                  | 1         | 0.45%   |
| GN Netcom Jabra Evolve 65                                                                         | 1         | 0.45%   |
| Creative Technology SB X-Fi Surround 5.1                                                          | 1         | 0.45%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 0.45%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 0.45%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                                              | 1         | 0.45%   |
| AMD RS600 HDMI Audio [Radeon Xpress 1250]                                                         | 1         | 0.45%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 1         | 0.45%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 1         | 0.45%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart_bsd/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 51        | 26.56%  |
| SK hynix            | 32        | 16.67%  |
| Kingston            | 25        | 13.02%  |
| Micron Technology   | 16        | 8.33%   |
| Unknown             | 14        | 7.29%   |
| Nanya Technology    | 8         | 4.17%   |
| Ramaxel Technology  | 6         | 3.13%   |
| Elpida              | 6         | 3.13%   |
| Crucial             | 6         | 3.13%   |
| Unknown             | 5         | 2.6%    |
| Smart               | 3         | 1.56%   |
| A-DATA Technology   | 3         | 1.56%   |
| Silicon Power       | 2         | 1.04%   |
| ASint Technology    | 2         | 1.04%   |
| 48spaces            | 2         | 1.04%   |
| Unknown (ABCD)      | 1         | 0.52%   |
| Transcend           | 1         | 0.52%   |
| Smart Brazil        | 1         | 0.52%   |
| Sesame              | 1         | 0.52%   |
| PNY                 | 1         | 0.52%   |
| Kingmax             | 1         | 0.52%   |
| High Bridge         | 1         | 0.52%   |
| GOODRAM             | 1         | 0.52%   |
| Corsair             | 1         | 0.52%   |
| Avant               | 1         | 0.52%   |
| Apacer              | 1         | 0.52%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart_bsd/memory_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                                | 7         | 3.38%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 5         | 2.42%   |
| Unknown                                                                   | 5         | 2.42%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1334MT/s                     | 4         | 1.93%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 4         | 1.93%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 4         | 1.93%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s                     | 4         | 1.93%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s                     | 3         | 1.45%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 3         | 1.45%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s                    | 3         | 1.45%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s                     | 3         | 1.45%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s                   | 3         | 1.45%   |
| Unknown RAM Module 2GB SODIMM DDR2                                        | 2         | 0.97%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                                | 2         | 0.97%   |
| SK hynix RAM HMT451S6MFR8A-PB 4GB SODIMM DDR3 800MT/s                     | 2         | 0.97%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s                    | 2         | 0.97%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 1333MT/s                     | 2         | 0.97%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                     | 2         | 0.97%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s                     | 2         | 0.97%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s                     | 2         | 0.97%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s                    | 2         | 0.97%   |
| Ramaxel RAM RMSA3300ME78HBF-2666 16GB SODIMM DDR4 2667MT/s                | 2         | 0.97%   |
| Nanya RAM Module 1GB SODIMM DDR2 667MT/s                                  | 2         | 0.97%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s                     | 2         | 0.97%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                      | 2         | 0.97%   |
| Kingston RAM Module 2GB SODIMM DDR2 667MT/s                               | 2         | 0.97%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1333MT/s                     | 2         | 0.97%   |
| 48spaces RAM 012345678901234567890123456789012345 2GB SODIMM DDR2 667MT/s | 2         | 0.97%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                               | 1         | 0.48%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                               | 1         | 0.48%   |
| Unknown RAM Module 4GB SODIMM DDR3                                        | 1         | 0.48%   |
| Unknown RAM Module 4GB SODIMM DDR2 667MT/s                                | 1         | 0.48%   |
| Unknown RAM Module 2GB SODIMM DDR3 1067MT/s                               | 1         | 0.48%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2133MT/s          | 1         | 0.48%   |
| Transcend RAM TS512MSK64W6H 4GB SODIMM DDR3 1600MT/s                      | 1         | 0.48%   |
| Smart RAM SH564568FH8NZPHSCR 2GB SODIMM DDR3 1334MT/s                     | 1         | 0.48%   |
| Smart RAM SH564568FH8NWPHSFR 2GB SODIMM DDR3 1333MT/s                     | 1         | 0.48%   |
| Smart RAM SH564128FJ8NZRNSDG 4GB SODIMM DDR3 1600MT/s                     | 1         | 0.48%   |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s                     | 1         | 0.48%   |
| Smart Brazil RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2400MT/s              | 1         | 0.48%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                              | 1         | 0.48%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1333MT/s                              | 1         | 0.48%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1067MT/s                              | 1         | 0.48%   |
| SK hynix RAM HYMP512S64CP8-Y5 1GB SODIMM DDR 667MT/s                      | 1         | 0.48%   |
| SK hynix RAM HYMP512S64CP8-C4 1GB SODIMM DDR 533MT/s                      | 1         | 0.48%   |
| SK hynix RAM HYMP112S64CP6-Y5 1GB SODIMM DDR 667MT/s                      | 1         | 0.48%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s                    | 1         | 0.48%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 1         | 0.48%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1333MT/s                    | 1         | 0.48%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM 1333MT/s                         | 1         | 0.48%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s                    | 1         | 0.48%   |
| SK hynix RAM HMA82GS6MFR8N-TF 16GB SODIMM DDR4 2133MT/s                   | 1         | 0.48%   |
| SK hynix RAM HMA82GS6DJR8N-VK 16GB SODIMM DDR4 2667MT/s                   | 1         | 0.48%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2400MT/s                   | 1         | 0.48%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s                    | 1         | 0.48%   |
| SK hynix RAM H9CCNNNBJTALAR-NUD 4GB Row Of Chips LPDDR3 1867MT/s          | 1         | 0.48%   |
| Silicon Power RAM SP008GBSFU240B02 8GB SODIMM DDR4 2400MT/s               | 1         | 0.48%   |
| Silicon Power RAM SP004GLSTU160N02 4GB SODIMM DDR3 1600MT/s               | 1         | 0.48%   |
| Sesame RAM S939A2SGS-ITR 8GB SODIMM DDR3 1600MT/s                         | 1         | 0.48%   |
| Samsung RAM Module 8GB SODIMM DDR4 2400MT/s                               | 1         | 0.48%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart_bsd/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 92        | 57.14%  |
| DDR4    | 39        | 24.22%  |
| DDR2    | 22        | 13.66%  |
| LPDDR3  | 2         | 1.24%   |
| Unknown | 2         | 1.24%   |
| SDRAM   | 1         | 0.62%   |
| LPDDR4  | 1         | 0.62%   |
| DRAM    | 1         | 0.62%   |
| DDR     | 1         | 0.62%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart_bsd/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 158       | 98.75%  |
| Row Of Chips | 1         | 0.63%   |
| DIMM         | 1         | 0.63%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart_bsd/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 65        | 35.91%  |
| 2048  | 50        | 27.62%  |
| 8192  | 44        | 24.31%  |
| 16384 | 12        | 6.63%   |
| 1024  | 8         | 4.42%   |
| 32768 | 2         | 1.1%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart_bsd/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 54        | 30.17%  |
| 1333    | 19        | 10.61%  |
| 2667    | 18        | 10.06%  |
| 667     | 17        | 9.5%    |
| 1334    | 14        | 7.82%   |
| 3200    | 10        | 5.59%   |
| 1067    | 10        | 5.59%   |
| 2133    | 9         | 5.03%   |
| 2400    | 8         | 4.47%   |
| 800     | 7         | 3.91%   |
| Unknown | 5         | 2.79%   |
| 1867    | 3         | 1.68%   |
| 975     | 3         | 1.68%   |
| 1066    | 1         | 0.56%   |
| 533     | 1         | 0.56%   |

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
| Chicony Electronics                    | 36        | 30.77%  |
| Realtek Semiconductor                  | 11        | 9.4%    |
| Microdia                               | 10        | 8.55%   |
| Acer                                   | 9         | 7.69%   |
| Quanta                                 | 8         | 6.84%   |
| IMC Networks                           | 8         | 6.84%   |
| Lite-On Technology                     | 7         | 5.98%   |
| Suyin                                  | 4         | 3.42%   |
| Sunplus Innovation Technology          | 4         | 3.42%   |
| Syntek                                 | 3         | 2.56%   |
| Lenovo                                 | 3         | 2.56%   |
| Alcor Micro                            | 3         | 2.56%   |
| Z-Star Microelectronics                | 2         | 1.71%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 1.71%   |
| Silicon Motion                         | 1         | 0.85%   |
| Ricoh                                  | 1         | 0.85%   |
| Primax Electronics                     | 1         | 0.85%   |
| Luxvisions Innotech Limited            | 1         | 0.85%   |
| Importek                               | 1         | 0.85%   |
| Apple                                  | 1         | 0.85%   |
| ALi                                    | 1         | 0.85%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart_bsd/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Lenovo Integrated Camera (0.3MP)            | 5         | 4.24%   |
| Chicony HD WebCam                                   | 5         | 4.24%   |
| Lite-On Integrated Camera                           | 4         | 3.39%   |
| Realtek USB Camera                                  | 3         | 2.54%   |
| Realtek Realtek USB2.0 PC Camera                    | 3         | 2.54%   |
| Realtek Integrated_Webcam_HD                        | 3         | 2.54%   |
| Microdia Integrated Webcam                          | 3         | 2.54%   |
| Chicony Integrated Camera                           | 3         | 2.54%   |
| Chicony HD WebCam (Acer)                            | 3         | 2.54%   |
| Chicony EasyCamera                                  | 3         | 2.54%   |
| Syntek Lenovo EasyCamera                            | 2         | 1.69%   |
| Suyin HD Video WebCam                               | 2         | 1.69%   |
| Quanta Realtek DMFT - RGB                           | 2         | 1.69%   |
| Quanta HP Webcam                                    | 2         | 1.69%   |
| Quanta HP TrueVision HD Camera                      | 2         | 1.69%   |
| Microdia Sonix USB 2.0 Camera                       | 2         | 1.69%   |
| Microdia Integrated_Webcam_HD                       | 2         | 1.69%   |
| Microdia Dell Laptop Integrated Webcam HD           | 2         | 1.69%   |
| Lite-On HP HD Camera                                | 2         | 1.69%   |
| Lenovo Integrated Webcam [R5U877]                   | 2         | 1.69%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 2         | 1.69%   |
| IMC Networks Integrated Camera                      | 2         | 1.69%   |
| Chicony HP HD Webcam [Fixed]                        | 2         | 1.69%   |
| Chicony Chicony USB 2.0 Camera                      | 2         | 1.69%   |
| Acer SunplusIT INC. Integrated Camera               | 2         | 1.69%   |
| Acer Lenovo EasyCamera                              | 2         | 1.69%   |
| Acer Integrated Camera                              | 2         | 1.69%   |
| Z-Star WebCam SC-03FFL11739P                        | 1         | 0.85%   |
| Z-Star Webcam                                       | 1         | 0.85%   |
| Syntek EasyCamera                                   | 1         | 0.85%   |
| Suyin Laptop_Integrated_Webcam_FHD                  | 1         | 0.85%   |
| Suyin Integrated_Webcam_HD                          | 1         | 0.85%   |
| Sunplus Integrated_Webcam_HD                        | 1         | 0.85%   |
| Sunplus Integrated Camera                           | 1         | 0.85%   |
| Sunplus HP Universal Camera                         | 1         | 0.85%   |
| Sunplus HD WebCam                                   | 1         | 0.85%   |
| Silicon Motion HP Webcam-50                         | 1         | 0.85%   |
| Ricoh USB2.0 Camera                                 | 1         | 0.85%   |
| Realtek Integrated_Webcam_FHD                       | 1         | 0.85%   |
| Realtek Integrated_Webcam_8M                        | 1         | 0.85%   |
| Realtek HD WebCam                                   | 1         | 0.85%   |
| Quanta VGA WebCam                                   | 1         | 0.85%   |
| Quanta HD WebCam                                    | 1         | 0.85%   |
| Primax Dell Laptop Integrated Webcam 2Mpix          | 1         | 0.85%   |
| Microdia Lenovo EasyCamera                          | 1         | 0.85%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 0.85%   |
| Lite-On TOSHIBA Web Camera - HD                     | 1         | 0.85%   |
| Lenovo Integrated Webcam                            | 1         | 0.85%   |
| Importek TOSHIBA Web Camera                         | 1         | 0.85%   |
| IMC Networks USB Camera                             | 1         | 0.85%   |
| IMC Networks SunplusIT Integrated Camera            | 1         | 0.85%   |
| IMC Networks Integrated Webcam                      | 1         | 0.85%   |
| IMC Networks EasyCamera                             | 1         | 0.85%   |
| Chicony Webcam-101                                  | 1         | 0.85%   |
| Chicony UVC 1.00 device HD UVC WebCam               | 1         | 0.85%   |
| Chicony USB2.0 VGA UVC WebCam                       | 1         | 0.85%   |
| Chicony USB 2.0 VGA UVC WebCam                      | 1         | 0.85%   |
| Chicony USB 2.0 Camera                              | 1         | 0.85%   |
| Chicony TOSHIBA Web Camera - HD                     | 1         | 0.85%   |
| Chicony thinkpad t430s camera                       | 1         | 0.85%   |

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
| 1     | 58        | 35.15%  |
| 2     | 49        | 29.7%   |
| 0     | 29        | 17.58%  |
| 3     | 22        | 13.33%  |
| 4     | 7         | 4.24%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart_bsd/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Communication controller | 103       | 43.28%  |
| Net/wireless             | 43        | 18.07%  |
| Fingerprint reader       | 37        | 15.55%  |
| Bluetooth                | 27        | 11.34%  |
| Card reader              | 24        | 10.08%  |
| Storage                  | 2         | 0.84%   |
| Sound                    | 1         | 0.42%   |
| Network                  | 1         | 0.42%   |

